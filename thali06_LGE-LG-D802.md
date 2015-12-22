#### Test 543122982543be8_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4583): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  955): Killing 3918:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 1 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313de88 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1856): GC_CONCURRENT freed 1595K, 22% free 19452K/24832K, paused 11ms+5ms, total 69ms
D/dalvikvm( 1856): WAIT_FOR_CONCURRENT_GC blocked 24ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ConfigFetchService( 1856): fetch service done; releasing wakelock
I/ConfigFetchService( 1856): stopping self
D/ChimeraCfgMgr( 1856): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1856): Module APK com.google.android.play.games already loaded
D/WifiStateMachine(  955): handleMessage: E msg.what=131155
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2026): nl80211: survey data missing!
D/WifiStateMachine(  955): handleMessage: X
I/Icing   ( 1856): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Icing   ( 1856): Loaded CLD2 Version V2.0 - 20141016
D/AndroidRuntime( 4623): 
D/AndroidRuntime( 4623): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4623): CheckJNI is OFF
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4623): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4623): Added shared lib libjavacore.so 0x0
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/dalvikvm( 4623): Trying to load lib libnativehelper.so 0x0
D/WifiController(  955): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4623): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4623): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/WifiController(  955): battery changed pluggedType: 2
D/dalvikvm( 4623): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1856): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4623): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4623): failed to load memtrack module: -2
D/AndroidRuntime( 4623): Calling main entry com.android.commands.am.Am
I/ActivityManager(  955): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4623
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (137 us)
V/ActivityManager(  955): Moving to PAUSING: ActivityRecord{4313de88 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  955): resumeTopActivityLocked: Pausing null
V/ActivityManager(  955): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  955): startService SlideAside
W/ContextImpl(  955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  955): setFocusedStack: mFocusedStack=ActivityStack{432fcaa8 stackId=1, 2 tasks}
D/UsbSettingsControl( 2609): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2609): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4623): Shutting down VM
I/SlideAside( 3677): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4623): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 3ms
D/ActivityManager(  955): allPausedActivitiesComplete: r=ActivityRecord{4313de88 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  955): Moving to PAUSED: ActivityRecord{4313de88 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/ActivityManager(  955): resumeTopActivityLocked: Restarting ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  955): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4647 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3677): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/SlideAside( 3677): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  955): Moving to RESUMED: ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4647): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4647): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4647): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4647): Binding Chromium to the background looper Looper (main, tid 1) {42830330}
I/chromium( 4647): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4647): Initializing chromium process, renderers=0
W/chromium( 4647): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4647): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4647): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4647): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4647): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4647): Remote Branch: 
I/Adreno-EGL( 4647): Local Patches: 
I/Adreno-EGL( 4647): Reconstruct Branch: 
I/dalvikvm( 4647): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4647): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4647): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4647): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4647): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4647): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4647): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4647): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4647): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4647): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4647): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4647): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4647): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4647): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4647): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4647): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4647): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4647): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4647): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4647): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4647): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4647): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4647): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4647): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.449951 Y: -0.413406 Z: 9.772354 
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449951 .y:-0.413406 .z:9.772354
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,D/OpenGLRenderer( 4647): Enabling debug mode 0
,W/AwContents( 4647): nativeOnDraw failed; clearing to background color.
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.459015 Y: -0.406326 Z: 9.765320 
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.471237 Y: -0.410767 Z: 9.751999 
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.459015 .y:-0.406326 .z:9.765320
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,I/InputMethodManagerService(  955): IME STATUS OFF
,W/AwContents( 4647): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  955): Displayed com.test.thalitest/.MainActivity: +540ms
,I/ActivityManager( 4647): Timeline: Activity_idle id: android.os.BinderProxy@42831b60 time:112821
,D/JsMessageQueue( 4647): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  955): Timeline: Activity_windows_visible id: ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3} time:113054
D/ActivityManager(  955): no-history finish of ActivityRecord{4313de88 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  955): Finishing activity token=Token{430d2c70 ActivityRecord{4313de88 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  955): Moving to FINISHING: ActivityRecord{4313de88 u0 com.android.settings/.UsbSettings t2 f}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3}
,D/UsbSettings( 2609): [AUTORUN] onStop()
V/ActivityManager(  955): Moving to STOPPING: ActivityRecord{4313de88 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  955): Moving to STOPPED: ActivityRecord{4313de88 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4647): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42835c40
,D/dalvikvm( 4647): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42835c40
,D/jxcore_app_log( 4647): JniHelper::setJavaVM(0x416fd838), pthread_self() = 1632000656
,D/JX-Cordova( 4647): jxcore cordova android initializing
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/dalvikvm( 4647): GC_CONCURRENT freed 2818K, 13% free 21826K/24832K, paused 1ms+1ms, total 36ms
D/dalvikvm( 4647): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 4647): GC_FOR_ALLOC freed 132K, 13% free 21840K/24832K, paused 38ms, total 38ms
I/dalvikvm-heap( 4647): Grow heap (frag case) to 23.593MB for 96598-byte allocation
D/dalvikvm( 4647): GC_FOR_ALLOC freed 199K, 13% free 21854K/24928K, paused 26ms, total 26ms
I/dalvikvm-heap( 4647): Grow heap (frag case) to 23.654MB for 144892-byte allocation
D/dalvikvm( 4647): GC_FOR_ALLOC freed 253K, 13% free 21902K/25072K, paused 22ms, total 22ms
I/dalvikvm-heap( 4647): Grow heap (frag case) to 23.770MB for 217334-byte allocation
D/dalvikvm( 4647): GC_FOR_ALLOC freed 369K, 14% free 21977K/25288K, paused 22ms, total 22ms
I/dalvikvm-heap( 4647): Grow heap (frag case) to 23.946MB for 325996-byte allocation
D/dalvikvm( 4647): GC_FOR_ALLOC freed 568K, 14% free 22099K/25608K, paused 22ms, total 22ms
I/dalvikvm-heap( 4647): Grow heap (frag case) to 24.220MB for 488990-byte allocation
D/dalvikvm( 4647): GC_FOR_ALLOC freed 867K, 15% free 22275K/26088K, paused 38ms, total 38ms
D/dalvikvm( 4647): GC_FOR_ALLOC freed 1285K, 14% free 22533K/26088K, paused 23ms, total 23ms
I/dalvikvm-heap( 4647): Grow heap (frag case) to 25.228MB for 1100216-byte allocation
D/dalvikvm( 4647): GC_CONCURRENT freed 1744K, 16% free 22915K/27164K, paused 2ms+2ms, total 31ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
D/WifiController(  955): battery changed pluggedType: 2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1217): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/dalvikvm( 4647): GC_FOR_ALLOC freed 308K, 16% free 22854K/27164K, paused 25ms, total 26ms
I/dalvikvm-heap( 4647): Grow heap (frag case) to 26.066MB for 1650320-byte allocation
D/dalvikvm( 4647): GC_CONCURRENT freed 1714K, 19% free 23435K/28776K, paused 2ms+2ms, total 29ms
D/dalvikvm( 4647): GC_FOR_ALLOC freed 1335K, 19% free 23512K/28776K, paused 25ms, total 25ms
I/dalvikvm-heap( 4647): Grow heap (frag case) to 27.495MB for 2475476-byte allocation
D/dalvikvm( 4647): GC_CONCURRENT freed 2060K, 23% free 24210K/31196K, paused 1ms+5ms, total 48ms
D/dalvikvm( 4647): GC_CONCURRENT freed 2346K, 22% free 24446K/31196K, paused 1ms+7ms, total 59ms
D/dalvikvm( 4647): WAIT_FOR_CONCURRENT_GC blocked 46ms
D/dalvikvm( 4647): GC_FOR_ALLOC freed 394K, 23% free 24294K/31196K, paused 42ms, total 42ms
I/dalvikvm-heap( 4647): Grow heap (frag case) to 29.439MB for 3713210-byte allocation
,D/dalvikvm( 4647): GC_CONCURRENT freed 427K, 21% free 27831K/34824K, paused 2ms+2ms, total 40ms
,W/jxcore-log( 4647): Initializing JXcore engine
,W/jxcore-log( 4647): JXcore engine is ready
,W/jxcore-log( 4647): Starting JXcore engine
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,W/jxcore-log( 4647): Platform android
W/jxcore-log( 4647): 
,W/jxcore-log( 4647): Process ARCH arm
W/jxcore-log( 4647): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  955): battery changed pluggedType: 2
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/jxcore-log( 4647): JXcore Cordova bridge is ready!
I/jxcore-log( 4647): 
,W/jxcore-log( 4647): JXcore engine is started
,I/chromium( 4647): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4647): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4647): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/ActivityManager(  955): Killing 4126:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  955): battery changed pluggedType: 2
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/GAV2    ( 4583): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/jxcore-log( 4647): Toggling radios to true
I/jxcore-log( 4647): 
,D/BluetoothManagerService(  955): Message: 20
,D/BluetoothManagerService(  955): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43139ea8:true
,D/BluetoothAdapter( 4647): enable(): BT is already enabled..!
D/WifiService(  955): New client listening to asynchronous messages
,D/WifiStateMachine(  955): handleMessage: E msg.what=131145
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doBoolean: DISCONNECT
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2026): wlan0: Cancelling scan request
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2026): TDLS: Tear down peers
,D/wpa_supplicant( 2026): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4647): Radios toggled
I/jxcore-log( 4647): 
,D/BluetoothManagerService(  955): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4647): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4647): 
D/WifiService(  955): setWifiEnabled: true pid=4647, uid=10304
E/WifiService(  955): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  955): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  955): disconnect pid=4647, uid=10304
,D/WifiService(  955): reconnect pid=4647, uid=10304
I/jxcore-log( 4647): Perf Test app loaded loaded
I/jxcore-log( 4647): 
I/Choreographer( 4647): Skipped 64 frames!  The application may be doing too much work on its main thread.
D/wpa_supplicant( 2026): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2026): wlan0: Deauthentication notification
D/wpa_supplicant( 2026): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2026): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2026): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2026): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2026): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2026): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb85aed6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2026): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2026): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
,D/WifiNative-wlan0(  955):    returned true
D/WifiStateMachine(  955): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  955): invokeExitMethods: ConnectedState
W/Settings(  955): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  955): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  955): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131146
D/WifiStateMachine(  955): processMsg: DisconnectingState
D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiNative-wlan0(  955): doBoolean: RECONNECT
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2026): Fast associate: Old scan results
D/wpa_supplicant( 2026): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2026): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2026): wlan0: nl80211: scan request
,D/wpa_supplicant( 2026): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2026): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2026): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  955):    returned true
,D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147460
D/WifiStateMachine(  955): processMsg: DisconnectingState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): Network connection lost
,D/WifiStateMachine(  955): Stopping DHCP and clearing IP
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  955): doBoolean: SET ps 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  955):    returned true
D/WifiNative-wlan0(  955): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  955):    returned true
D/DhcpStateMachine(  955): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/chromium( 4647): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiP2pService(  955): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  955): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 4647): check test folder
I/jxcore-log( 4647): 
D/CommandListener(  264): Clearing all IP addresses on wlan0
I/jxcore-log( 4647): found test : ./testFindPeers.js
I/jxcore-log( 4647): 
D/WifiStateMachine(  955): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  955): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  955): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 0
D/WifiHS20(  955): hidePasspointNotification off =false
D/QcConnectivityService(  955): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/QCNEA   (  410): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  410): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  410): |CAC| updateNetCfgInfo
V/QCNEA   (  410): |CAC| *********************************************
V/QCNEA   (  410): |CAC|                   Netconfig               
V/QCNEA   (  410): |CAC| *********************************************
V/QCNEA   (  410): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  410): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  410): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  410): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  410): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  410): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  410): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  410): |CAC| *********************************************
D/QCNEA   (  410): |CAC| Received bssid= 
D/QCNEA   (  410): |CAC| net type = 3
V/QCNEA   (  410): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  410): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  410): |CAC| 	ssid           =NG700
V/QCNEA   (  410): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  410): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  410): |CAC| *********************************************
D/QCNEA   (  410): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  410): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  410): |CAC| dispatchNetCfg: updating:0xb74c48dc
,D/QCNEA   (  410): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  955): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  955): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  955): invokeEnterMethods: DisconnectedState
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  955): Attempting to switch to mobile
D/QcConnectivityService(  955): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  955): handleConnectivityChange: preConnState=1 connState=2
I/ActivityManager(  955): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4698 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/WifiStateMachine(  955): handleMessage: X
,D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
,D/WifiStateMachine(  955): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131213
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  955): processMsg: SupplicantStartedState
D/WifiStateMachine(  955): processMsg: DefaultState
,D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131213
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
,D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
D/WifiStateMachine(  955): processMsg: DefaultState
,D/WifiStateMachine(  955): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ConfigService( 1538): onDestroy
D/NetworkManagementService(  955): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  955): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  955): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
D/HyLog   ( 4698): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4698): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4698): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
,I/jxcore-log( 4647): found test : ./testSendData.js
I/jxcore-log( 4647): 
,I/PCSuite ( 4698): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/PCSuite ( 4698): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4698): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
I/ActivityManager(  955): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4724 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  955): Killing 3848:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,V/        (  264): RouteController
,I/jxcore-log( 4647): found test : ./testSendData2.js
I/jxcore-log( 4647): 
,V/        (  264): RouteController
,V/        (  264): RouteController
D/HyLog   ( 4724): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4724): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4724): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/NetworkManagementService(  955): route cmd failed: 
W/NetworkManagementService(  955): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  955): '
W/NetworkManagementService(  955): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  955): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  955): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  955): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  955): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  955): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  955): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  955): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  955): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  955): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  955): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  955): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  955): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  955): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  955): android_net_utils_resetConnections in env=0x609d5298 clazz=0x6d700001 iface=wlan0 mask=0x3
D/QcConnectivityService(  955): resetConnections(wlan0, 3)
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3}
,V/NativeCrypto( 1538): Read error: ssl=0x6383e3e0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1538): SSL shutdown failed: ssl=0x6383e3e0: I/O error during system call, Broken pipe
,D/QRemote ( 4724): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4724): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4724): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4724): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4724): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4724): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4724): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  955): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/QcConnectivityService(  955): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  955): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/QRemote ( 4724): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4724): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  955): Killing 2165:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  955): StoppedState
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
,D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  955): processMsg: SupplicantStartedState
D/WifiStateMachine(  955): processMsg: DefaultState
,D/WifiStateMachine(  955): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  955): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Tethering(  955): MasterInitialState.processMessage what=3
D/QcConnectivityService(  955): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] connect :false
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2026): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2026): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2026): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 2026): nl80211: Survey data missing
D/wpa_supplicant( 2026): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 6 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 7 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 8 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 9 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 2026): wlan0: New scan results available
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2026): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2026): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2026): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2026): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2026): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2026): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2026): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2026): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-62
D/wpa_supplicant( 2026): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2026): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-62 wps
D/wpa_supplicant( 2026): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2026): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2026): wlan0: Considering connect ,request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85b05a8  current_ssid=0x0
D/wpa_supplicant( 2026): scard is not null..
D/wpa_supplicant( 2026): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2026): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2026): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 2026): wlan0: Cancelling scan request,
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
,D/wpa_supplicant( 2026): wlan0: WPA: clearing own WPA/RSN IE,
D/wpa_supplicant( 2026): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2026): RSN: PMKSA cache search - network_ctx=0xb85b05a8 try_opportunistic=0
D/wpa_supplicant( 2026): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2026): RSN: No PMKSA cache entry found,
D/wpa_supplicant( 2026): wlan0: RSN: using IEEE 802.11i/D9.0,
D/wpa_supplicant( 2026): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2026): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2026): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): wlan0: WPA: using GTK CCMP
,D/wpa_supplicant( 2026): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2026): wlan0: WPA: using KEY_MGMT WPA-PSK,
D/wpa_supplicant( 2026): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2026): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2026): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2026): wlan0: State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 2026): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2026): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2026): nl80211: Unsubscribe mgmt frames handle 0xb85af590 (mode change)
D/wpa_supplicant( 2026): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85af590
,D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb85af590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb85af590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0b,
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb85af590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0c
,D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb85af590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb85af590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb85af590
,D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb85af590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb85af590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=1): 06
,D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb85af590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb85af590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2026): nl80211: Connect (ifindex=23)
,D/wpa_supplicant( 2026):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026):   * freq=2412
D/wpa_supplicant( 2026):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2026):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026):   * Auth Type 0
,D/wpa_supplicant( 2026):   * WPA Versions 0x2
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 a0:c5:62:7a:49:97],
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 10:9a:dd:8e:22:d9]
D/wpa_supplicant( 2026): nl80211: Connect request send successfully
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2026): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 fe:94:e3:11:35:3c]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 fc:94:e3:11:35:3a]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,D/WifiStateMachine(  955): handleMessage: E msg.what=147461
D/WifiStateMachine(  955): processMsg: DisconnectedState
,D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
,W/WifiMonitor(  955): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiNative-wlan0(  955): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2026): nl80211: Connect event
D/wpa_supplicant( 2026): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2026): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2026): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2026): wlan0: Association info event
D/wpa_supplicant( 2026): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2026): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2026): wlan0: freq=2412 MHz
D/wpa_supplicant( 2026): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2026): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2026): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2026): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): scard is not null..
D/wpa_supplicant( 2026): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2026): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2026): TDLS: Remove peers on association
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2026): EAPOL: enable timer tick
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): wlan0: Cancelling scan request
,D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/WifiMonitor(  955): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  955): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2026): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
,D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/AppUp4:CustModeStarterReceiver( 3978): onReceive
D/AppUp4:CustFacade( 3978): Context : android.app.ReceiverRestrictedContext@4284de70
D/AppUp4:CustFacade( 3978): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3978): isOpenOperator : true
D/AppUp4:CustFacade( 3978): isPhone : true
D/wpa_supplicant( 2026): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 99 ec 83 bf 47 2f ae f1 64 c2 04 a3 99 df f0 ...
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2026): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2026): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2026): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2026):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2026):   key_nonce - hexdump(len=32): 99 ec 83 bf 47 2f ae f1 64 c2 04 a3 99 df f0 da 5e bb 0c 8f 93 a4 df 43 fa 3c c6 ff d1 37 86 58
D/wpa_supplicant( 2026):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 99 ec 83 bf 47 2f ae f1 64 c2 04 a3 99 df f0 ...
D/wpa_supplicant( 2026): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2026): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2026): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2026): WPA: Renewed SNonce - hexdump(len=32): e1 ba 13 30 98 9d 94 9d c9 af da f8 6e 98 62 ff ad 0e 13 ac 91 23 13 d9 91 5a 20 b9 22 81 f2 67
D/wpa_supplicant( 2026): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): WPA: Nonce1 - hexdump(len=32): e1 ba 13 30 98 9d 94 9d c9 af da f8 6e 98 62 ff ad 0e 13 ac 91 23 13 d9 91 5a 20 b9 22 81 f2 67
D/wpa_supplicant( 2026): WPA: Nonce2 - hexdump(len=32): 99 ec 83 bf 47 2f ae f1 64 c2 04 a3 99 df f0 da 5e bb 0c 8f 93 a4 df 43 fa 3c c6 ff d1 37 86 58
D/wpa_supplicant( 2026): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2026): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2026): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2026): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2026): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): WPA: Derived Key MIC - hexdump(len=16): 12 32 76 e6 b0 9a ca 57 2f 5a e6 c7 fd c2 2a 29
D/wpa_supplicant( 2026): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 e1 ba 13 30 98 9d 94 9d c9 af da f8 6e 98 62 ...
I/LicenseContentProvider( 2976): start selecting data
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/SIMObserver( 2976): simInfo1
I/AppUp4:EulaManager( 3978): getAgreementForKK : Eula agreement is false
D,/AppUp4:CustModeStarterReceiver( 3978): begin check event
I/AppUp4:CustModeStarterReceiver( 3978): Event For GoodConnectivity
D/wpa_supplicant( 2026): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 99 ec 83 bf 47 2f ae f1 64 c2 04 a3 99 df f0 ...
D/wpa_supplicant( 2026): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2026): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2026): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2026): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2026):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2026):   key_nonce - hexdump(len=32): 99 ec 83 bf 47 2f ae f1 64 c2 04 a3 99 df f0 da 5e bb 0c 8f 93 a4 df 43 fa 3c c6 ff d1 37 86 58
D/wpa_supplicant( 2026):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_rsc - hexdump(len=8): e3 76 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_mic - hexdump(len=16): e1 07 da 52 ce 5f fd a9 81 55 0b c5 77 3b e3 84
D/wpa_supplicant( 2026): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 99 ec 83 bf 47 2f ae f1 64 c2 04 a3 99 df f0 ...
D/wpa_supplicant( 2026): RSN: encrypted key data - hexdump(len=56): c6 89 2e f5 04 17 76 82 0c 9d 79 88 c5 91 ea 64 42 0b fa 69 aa 72 7e 58 bd 8e 0e f6 b1 c9 48 68 ...
D/wpa_supplicant( 2026): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2026): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2026): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2026): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 81 f8 ...
D/wpa_supplicant( 2026): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2026): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2026): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): WPA: Derived Key MIC - hexdump(len=16): e6 09 41 cf 83 14 fa b8 0f c0 e8 75 12 ca e3 39
D/wpa_supplicant( 2026): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2026): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb85afc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2026):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2026): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2026): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2026): WPA: RSC - hexdump(len=6): e3 76 00 00 00 00
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f3703a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2026):    broadcast key
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  955): processMsg: ConnectModeState
I/wpa_supplicant( 2026): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2026): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2026): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=6
D/WifiStateMachine(  955): handleMessage: X
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2026): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2026): EAPOL authentication completed successfully
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  955): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  955): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  955): handleMessage: E msg.what=147459
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): Network connection established
D/WifiNative-wlan0(  955): doString: STATUS
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2026): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  955):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  955): ssid=NG700
D/WifiNative-wlan0(  955): id=0
D/WifiNative-wlan0(  955): mode=station
D/WifiNative-wlan0(  955): pairwise_cipher=CCMP
D/WifiNative-wlan0(  955): group_cipher=CCMP
D/WifiNative-wlan0(  955): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  955): wpa_state=COMPLETED
D/WifiNative-wlan0(  955): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  955): address=34:fc:ef:de:0a:e2
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/WifiServiceExtension(  955): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  955): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  955): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  955): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  955): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
I/ActivityManager(  955): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4779 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/WifiStateMachine(  955): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  955): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  955): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm(  955): GC_CONCURRENT freed 1181K, 49% free 29663K/57524K, paused 43ms+6ms, total 137ms
D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 46ms
D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 46ms
D/WifiStateMachine(  955): ObtainingIpState{ when=-26ms what=147462 obj=android.net.wifi.StateChangeResult@4496b858 target=com.android.internal.util.StateMachine$SmHandler }
D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 45ms
D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 32ms
D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 44ms
D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 46ms
D/DhcpStateMachine(  955): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  955): WaitBeforeStartState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/HyLog   ( 4779): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/HyLog   ( 4779): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4779): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  955): ObtainingIpState{ when=-56ms what=147462 obj=android.net.wifi.StateChangeResult@44852f68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147459
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-56ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131155
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-51ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
D/WifiStateMachine(  955): handleMessage: X
,D/WifiStateMachine(  955): handleMessage: E msg.what=196612
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-11ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiNative-wlan0(  955): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,V/DownloadManager( 4779): DownloadService onCreate
,D/EAS     ( 4563): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 4779): in removeSpuriousFiles
,D/EAS     ( 4563): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4779): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/eas_req ( 4563): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@42876998 on behalf of 4779
,I/DownloadManager( 4779): in trimDatabase
,V/DownloadManager( 4779): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4779): DownloadService onStartCommand
,V/DownloadManager( 4779): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@42879130 on behalf of 4779
,V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@4287b528 on behalf of 4779
I/LgeMiscReceiver( 4305): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4305): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4305): networkInfo.isConnected() = false
,V/DownloadManager( 4779): DownloadService onDestroy
,W/linker  ( 4563): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4563): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4563): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4563): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4563): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4563): register_HtmlEditor, Success
D/HtmlEditor( 4563): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4563): register_HtmlEditorTimer, Success
D/HtmlEditor( 4563): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4563): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4563): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4563): register_HtmlEditorFont, Success
,D/HtmlEditor( 4563): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4563): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4563): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4563): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4563): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4563): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4563): JNI_OnLoad Success
,I/HubEmail( 4563): JNI_OnLoad()
I/HubEmail( 4563): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4563): registerNatives()
I/HubEmail( 4563): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4563): registerNativeMethods()
,I/HubEmail( 4563): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4563): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  955):    returned true
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  955): doBoolean: SET ps 0
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  955):    returned true
D/WifiNative-wlan0(  955): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  955):    returned null
E/WifiStateMachine(  955): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  955): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  955):    returned null
,E/WifiStateMachine(  955): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  955): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  955): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  955): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  955): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
,D/WifiStateMachine(  955): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  955): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  955): handleMessage: X
,D/WifiStateMachine(  955): handleMessage: E msg.what=131212
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
I/ActivityManager(  955): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4806 uid=10052 gids={50052, 3003}
D/WifiP2pService(  955): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4332f838 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  955): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4332f838 target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
D/WifiStateMachine(  955): processMsg: DefaultState
D/WifiStateMachine(  955): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=196613
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  955): doBoolean: SET ps 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  955):    returned true
,D/WifiNative-wlan0(  955): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  955):    returned true
,D/WifiStateMachine(  955): DHCP successful
D/WifiStateMachine(  955): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  955): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  955): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  955): invokeEnterMethods: VerifyingLinkState
,D/WifiStateMachine(  955): VerifyingLinkState enter
,D/WifiStateMachine(  955): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  955): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  955): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  955): Killing 4278:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  955): send additional Connectivity Action
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  955): handleMessage: X
E/Parcel  (  410): Reading a NULL string not supported here.
D/WifiStateMachine(  955): handleMessage: E msg.what=135190
D/WifiStateMachine(  955): processMsg: VerifyingLinkState
D/WifiStateMachine(  955): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  955): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  955): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  955): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  955): CaptivePortalCheckState enter
,D/WifiStateMachine(  955): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/WifiStateTracker(  955): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  955): 
W/WifiStateTracker(  955):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  955):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  955): handleMessage: X
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
,E/Parcel  (  410): Reading a NULL string not supported here.
D/WifiStateMachine(  955): handleMessage: E msg.what=131092
D/WifiStateMachine(  955): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  955): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  955): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/LocSvc_java(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  955): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/QcConnectivityService(  955): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  955): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  955): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  955): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  955): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  955): handleMessage: X
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 1
D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  410): Reading a NULL string not supported here.
,E/Parcel  (  410): Reading a NULL string not supported here.
,E/Parcel  (  410): Reading a NULL string not supported here.
D/GpsLocationProvider(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiController(  955): battery changed pluggedType: 2
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3}
,E/ActivityThread(  955): Failed to find provider info for com.lge.ims.provisioning
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/HyLog   ( 4806): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4806): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4806): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/QcConnectivityService(  955): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  955): handleConnectivityChange: preConnState=2 connState=1
,V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
V/LGRssiData( 4806): [loadRssi] File not exist 
,V/LGRssiData( 4806): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4806): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4806): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4806): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4806): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4806): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4806): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4806): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4806): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
,D/MobileConnectivityChangeReceiver( 4806): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4806): onReceive CONNECTIVITY_CHANGE networkType=1
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  955): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4829 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  955): Killing 4482:com.android.defcontainer/u0a4 (adj 15): empty #17
E/PhoneMonitor( 4806): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4806): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
D/HyLog   ( 4829): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4829): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4829): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3}
I/CheckinService( 1856): Checking schedule, now: 1450745498917 next: 1450745439949
,I/CheckinService( 1856): active receiver: enabled
D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinService( 1856): Preparing to send checkin request
,I/EventLogService( 1856): Accumulating logs since 1450745406715
D/QCNEA   (  410): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  410): |CAC| updateWlanNetCfgInfo
,D/QCNEA   (  410): |CAC| updateNetCfgInfo
,V/QCNEA   (  410): |CAC| *********************************************
V/QCNEA   (  410): |CAC|                   Netconfig               
V/QCNEA   (  410): |CAC| *********************************************
V/QCNEA   (  410): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  410): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  410): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  410): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  410): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  410): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  410): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  410): |CAC| *********************************************
D/QCNEA   (  410): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  410): |CAC| net type = 1
V/QCNEA   (  410): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  410): |CAC| Received ssid= NG700
V/QCNEA   (  410): |CAC| 	ssid           =NG700
V/QCNEA   (  410): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  410): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  410): |CAC| *********************************************
D/QCNEA   (  410): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  410): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  410): |CAC| dispatchNetCfg: updating:0xb74c48dc
D/QCNEA   (  410): |CAC| readCallback: read len:0, ret:-1, errno:11
D/GpsLocationProvider(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/CheckinRequestBuilder( 1856): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  955): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4853 uid=10066 gids={50066, 4002, 3003, 1028}
,E/ActivityThread( 1856): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 4853): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4853): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4853): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  955): Killing 4522:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2853): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2853): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2853): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  955): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4866 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3}
E/LGDMClient( 2853): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/DhcpStateMachine(  955): DHCP request on wlan0
D/LGDMClient( 2853): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LgDhcpStateMachineHelper(  955): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/LGDMClient( 2853): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2853): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 4866): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4866): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4866): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1538): GC_EXPLICIT freed 1124K, 29% free 17813K/24832K, paused 1ms+7ms, total 39ms
,D/LGDMSGCM( 4866): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  955): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4886 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  955): Killing 4549:com.lge.bnr/1000 (adj 15): empty #17
,D/HyLog   ( 4886): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4886): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4886): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 4886): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4886): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4886): intf.getDisplayName() = lo
I/Wireless_Storage( 4886): intf.getDisplayName() = sit0
I/Wireless_Storage( 4886): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4886): intf.getDisplayName() = teql0
,I/Wireless_Storage( 4886): intf.getDisplayName() = wlan0
,D/NFS     ( 4886): interface name:wlan0 name:wlan0
D/NFS     ( 4886): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4886): interface name:wlan0 name:wlan0
D/NFS     ( 4886): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 4886): CONNECT : WIFI_CONNECT
,I/ActivityManager(  955): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4900 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  955): Killing 4178:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
,D/HyLog   ( 4900): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4900): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4900): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3}
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4900): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  955): updateLightListLocked :r=NotificationRecord(0x4295a430: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  955): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1856): awaiting user notification for token
,I/ActivityManager(  955): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4919 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4919): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4919): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4919): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 15ms
W/dalvikvm( 4919): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4919): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4919): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4919): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4919): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4919): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4919): install
,I/MultiDex( 4919): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,V/WebViewChromium( 4900): Binding Chromium to the main looper Looper (main, tid 1) {4283a3d0}
,I/MultiDex( 4919): loading existing secondary dex files
,I/chromium( 4900): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4900): Initializing chromium process, renderers=0
,I/MultiDex( 4919): load found 3 secondary dex files
,I/MultiDex( 4919): install done
,W/chromium( 4900): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4900): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4900): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4900): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4900): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4900): Remote Branch: 
I/Adreno-EGL( 4900): Local Patches: 
I/Adreno-EGL( 4900): Reconstruct Branch: 
D/dalvikvm( 4919): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4919): VFY: unable to resolve instance field 61
,D/dalvikvm( 4919): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4919): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4919): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4919): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4919): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4919): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4919): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4919): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4919): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4919): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42841850
D/dalvikvm( 4919): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42841850
,D/dalvikvm( 4919): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42841850, skipping init
,D/dalvikvm( 4919): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42841850
D/dalvikvm( 4919): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42841850
,V/JNIHelp ( 4919): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 4900): Starting up...
,I/ActivityManager(  955): Killing 4193:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/dalvikvm( 4919): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42841850
,D/dalvikvm( 4919): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42841850
D/dalvikvm( 4919): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42841850
,D/dalvikvm( 4919): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42841850
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4724): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4724): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4724): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4724): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4724): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4724): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4698): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4698): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4724): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4724): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4724): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4724): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ProviderInstaller( 4919): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1538): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1538): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1856): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1753): callingUid 10006, callindPid: 1753
,E/MDM     ( 1422): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1856): Restart initialization of location
,I/dalvikvm( 4919): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4919): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4919): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4919): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4919): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4919): VFY: replacing opcode 0x6e at 0x0201
,D/DhcpStateMachine(  955): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  955): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  955): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  955): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  955): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  955): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  955): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  955): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  955): RunningState
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d98000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d98000
,D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=2396058039
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4919): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a30620
D/dalvikvm( 4919): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a30620
,D/dalvikvm( 4919): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a30620, skipping init
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/GCM     ( 1538): Connected
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1538): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/wpa_supplicant( 2026): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2026): EAPOL: disable timer tick
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  955): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=1106929083
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  955): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4919): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4987): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,I/dalvikvm( 4647): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4647): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4647): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4647): Shutting down VM
,W/dalvikvm( 4647): threadid=1: thread exiting with uncaught exception (group=0x417f8e48)
D/dalvikvm( 4919): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4919): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 1ms, rewrite 116ms
,I/Adreno-EGL( 4919): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4919): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4919): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4919): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4919): Remote Branch: 
I/Adreno-EGL( 4919): Local Patches: 
I/Adreno-EGL( 4919): Reconstruct Branch: 
E/AndroidRuntime( 4647): FATAL EXCEPTION: main
E/AndroidRuntime( 4647): Process: com.test.thalitest, PID: 4647
E/AndroidRuntime( 4647): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4647): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4647): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4647): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4647): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4647): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4647): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4647): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4647): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4647): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4647): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4647): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4647): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4647): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4647): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4647): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4647): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4647): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4647): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  955):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  955): Moving to PAUSING: ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3 f}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 4919): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm(  955): GC_CONCURRENT freed 2554K, 48% free 30415K/57524K, paused 4ms+6ms, total 109ms
,D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 93ms
D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 84ms
,D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/WifiStateMachine(  955): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  955): handleMessage: E msg.what=131212
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
,D/WifiStateMachine(  955): processMsg: DefaultState
,D/WifiStateMachine(  955): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,I/Adreno-EGL( 4919): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4919): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4919): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4919): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4919): Remote Branch: 
I/Adreno-EGL( 4919): Local Patches: 
I/Adreno-EGL( 4919): Reconstruct Branch: 
,D/WifiStateMachine(  955): handleMessage: X
,I/Adreno-EGL( 4919): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4919): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4919): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4919): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4919): Remote Branch: 
I/Adreno-EGL( 4919): Local Patches: 
I/Adreno-EGL( 4919): Reconstruct Branch: 
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  955): send additional Connectivity Action
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  955): handleConnectivityChange:1 is conntected
,D/GpsLocationProvider(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  955): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  955):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  955): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/CheckinRequestBuilder( 1856): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1856): Sending checkin request (11450 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/ActivityManager(  955): Activity pause timeout for ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  955): Moving to PAUSED: ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  955): Moving to STOPPING: ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcaa8 stackId=1, 2 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  955): moveHomeStack:
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c2cbe8 stackId=0, 1 tasks}
,V/ActivityManager(  955): Moving to RESUMED: ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  955): resumeTopActivityLocked: Resumed ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  955): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c2cbe8 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1813): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:51:40
,D/UpdateThreadPoolManager( 1813): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1813): 2 : quick cover state : opened : 0
,D/WeatherService( 1813): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1813): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1813): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1813): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1813): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1813): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:51:40
,D/WeatherService( 1813): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1813): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1813): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1813): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1813): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1813): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1813): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1813): 2 : This is isUpdating : false
D/WeatherService( 1813): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1813): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1813): 2 : Map key string is -2
,D/lim     ( 1813): 2 : time = 01:51
I/WeatherReflect( 1813): Model Name : LG-D802
,D/WeatherTheme( 1813): 2 : Different view - status_min_formatted : 50 != 51
D/WeatherTheme( 1813): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
,D/WeatherTheme( 1813): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1813): 2 : Fixed theme : optimus
,D/WeatherTheme( 1813): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1813): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1813): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1813): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1813): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1487): GC_CONCURRENT freed 5526K, 9% free 60857K/66652K, paused 1ms+2ms, total 27ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 1141): GC_FOR_ALLOC freed 6688K, 10% free 70783K/78396K, paused 44ms, total 47ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/CheckinRequestBuilder( 1856): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1856): Failed to find provider info for com.google.android.wearable.settings
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1487): GC_FOR_ALLOC freed 4800K, 9% free 61906K/67520K, paused 20ms, total 21ms
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1856): awaiting user notification for token
D/NotificationService(  955): updateLightListLocked :r=NotificationRecord(0x432ec0c0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  955): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1856): Classify the device as Phone.
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@42836388 time:122680
,D/UsbSettings( 2609): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2609): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2609): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2609): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  955): Moving to DESTROYING: ActivityRecord{4313de88 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,I/CheckinTask( 1856): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1856): Checking schedule, now: 1450745501396 next: 1451322897393
,I/CheckinService( 1856): active receiver: disabled
V/ActivityManager(  955): Moving to DESTROYED: ActivityRecord{4313de88 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c2cbe8 stackId=0, 1 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  955): Timeline: Activity_windows_visible id: ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1} time:122708
V/ActivityManager(  955): Moving to FINISHING: ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  955): Moving to DESTROYING: ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  955): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  955): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3978): onReceive
,D/AppUp4:CustFacade( 3978): Context : android.app.ReceiverRestrictedContext@4284de70
,D/AppUp4:CustFacade( 3978): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3978): isOpenOperator : true
,D/AppUp4:CustFacade( 3978): isPhone : true
,I/LicenseContentProvider( 2976): start selecting data
,D/SIMObserver( 2976): simInfo1
,I/AppUp4:EulaManager( 3978): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3978): begin check event
,I/AppUp4:CustModeStarterReceiver( 3978): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3978): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 3978): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3978): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 3978): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3978): handleAsyncCustNotification do not startCustService
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  955): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  955): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/EAS     ( 4563): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4779): DownloadService onCreate
,D/EAS     ( 4563): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4563): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4779): in removeSpuriousFiles
,V/DownloadManager( 4779): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@428813d8 on behalf of 4779
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/LgeMiscReceiver( 4305): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4305): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4305): networkInfo.isConnected() = false
I/DownloadManager( 4779): in trimDatabase
V/DownloadManager( 4779): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@42883248 on behalf of 4779
W/Settings( 4563): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4779): DownloadService onStartCommand
V/DownloadManager( 4779): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/MobileConnectivityChangeReceiver( 4806): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4806): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@42884f80 on behalf of 4779
D/LGDMClient( 2853): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4779): DownloadService onDestroy
D/LGDMClient( 2853): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2853): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMSGCM( 4866): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4886): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4886): CONNECT : WIFI_CONNECT
E/LGDMClient( 2853): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2853): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2853): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2853): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3978): onReceive
,D/AppUp4:CustFacade( 3978): Context : android.app.ReceiverRestrictedContext@4284de70
D/AppUp4:CustFacade( 3978): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3978): isOpenOperator : true
,D/AppUp4:CustFacade( 3978): isPhone : true
,I/LicenseContentProvider( 2976): start selecting data
,D/SIMObserver( 2976): simInfo1
,I/AppUp4:EulaManager( 3978): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3978): begin check event
,I/AppUp4:CustModeStarterReceiver( 3978): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4779): DownloadService onCreate
,I/DownloadManager( 4779): in removeSpuriousFiles
,D/EAS     ( 4563): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 4779): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4563): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@428899f0 on behalf of 4779
,V/DownloadManager( 4779): DownloadService onStartCommand
,V/DownloadManager( 4779): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4779): in trimDatabase
,V/DownloadManager( 4779): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@4288bc40 on behalf of 4779
V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@4288c808 on behalf of 4779
I/LgeMiscReceiver( 4305): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4305): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4305): networkInfo.isConnected() = true
,D/PhoneState( 4305): setPdpRejectCasuse : false
,W/Settings( 4563): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4806): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4806): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4779): DownloadService onDestroy
,D/LGDMClient( 2853): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2853): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4866): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2853): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 4886): connectivityManager.getNetworkInfo = TYPE_WIFI
,W/ContextImpl( 4866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Wireless_Storage( 4886): CONNECT : WIFI_CONNECT
E/LGDMClient( 2853): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2853): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2853): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2853): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  955): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1487): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  955): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  955): DelayedCaptiveCheckState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3978): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3978): onReceive
,D/AppUp4:CustFacade( 3978): Context : android.app.ReceiverRestrictedContext@4284de70
,D/AppUp4:CustFacade( 3978): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3978): isOpenOperator : true
,D/AppUp4:CustFacade( 3978): isPhone : true
,I/LicenseContentProvider( 2976): start selecting data
,D/SIMObserver( 2976): simInfo1
,I/AppUp4:EulaManager( 3978): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3978): begin check event
,I/AppUp4:CustModeStarterReceiver( 3978): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4563): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4779): DownloadService onCreate
,D/EAS     ( 4563): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4305): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4305): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4305): networkInfo.isConnected() = true
,D/PhoneState( 4305): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4806): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4806): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 4779): in removeSpuriousFiles
,V/DownloadManager( 4779): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGDMClient( 2853): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@42890e38 on behalf of 4779
D/LGDMClient( 2853): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/DownloadManager( 4779): in trimDatabase
V/DownloadManager( 4779): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMSGCM( 4866): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@428924e0 on behalf of 4779
,W/Settings( 4563): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NFS     ( 4886): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4886): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2853): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 4779): DownloadService onStartCommand
V/DownloadManager( 4779): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@428949e0 on behalf of 4779
E/LGDMClient( 2853): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2853): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2853): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2853): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4779): DownloadService onDestroy
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/WifiServiceExtension(  955): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/WifiServiceExtension(  955): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  955): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4900): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  955): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.454315 Y: -0.413101 Z: 9.763489 
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454315 .y:-0.413101 .z:9.763489
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,I/ActivityManager(  955): Killing 4583:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  955): Killing 4698:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  955): Killing 4211:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c2cbe8 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c2cbe8 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1}
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.441147 Y: -0.401825 Z: 9.740906 
,V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.465591 Y: -0.418488 Z: 9.739807 
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.441147 .y:-0.401825 .z:9.740906
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c2cbe8 stackId=0, 1 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
,D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,I/ActivityManager(  955): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5135 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5135): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5135): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5135): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5135): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5135): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5135): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5135): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5135): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 5135): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5135): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5135): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5135): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5135): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5135): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5135): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5135): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5135): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5135): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5135): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5135): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5135): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5135): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5135): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5135): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5135): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5135): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 4779): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4779): created cursor android.database.sqlite.SQLiteCursor@42899b80 on behalf of 5135
I/dalvikvm( 5135): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5135): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5135): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5135): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 5135): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5135): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5135): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5135): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5135): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5135): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm( 5135): Total arena pages for JIT: 11
,I/dalvikvm( 5135): Total arena pages for JIT: 12
I/dalvikvm( 5135): Total arena pages for JIT: 13
,I/dalvikvm( 5135): Total arena pages for JIT: 14
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/Finsky  ( 5135): [459] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5135): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  955): Killing 4724:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c2cbe8 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5135): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5135): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5135): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5135): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Finsky  ( 5135): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  955): GC_EXPLICIT freed 1760K, 47% free 30536K/57468K, paused 3ms+7ms, total 96ms
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1538): GC_EXPLICIT freed 1302K, 29% free 17821K/24832K, paused 2ms+3ms, total 25ms
,W/Finsky  ( 5135): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5135): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5135): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5135): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5135): [1] DailyHygiene.reschedule: Scheduling new run in 98 minutes (failures=3)
,D/DeviceConnectionService( 1422): client connected with version: 7571000
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
,D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/ActivityManager(  955): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5202 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "sms"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3677): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/SlideAside( 3677): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "smsto"
D/administrator(  955): Handling package changes for user 0
,I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/InputReader(  955): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
D/HyLog   ( 5202): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
D/HyLog   ( 5202): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/PackageManager(  955):   Scheme: "mms"
,D/HyLog   ( 5202): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "mmsto"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "sms"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "smsto"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "mms"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "mmsto"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5202): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5202): MmsConfig.loadMmsSettings
,I/Babel   ( 5202): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 5202): MmsConfig.loadFromDatabase
I/MediaCodecList( 5202): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5202): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5202): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5202): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5202): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5202): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5202): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5202): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5202): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5202): MmsConfig.loadFromResources
E/Babel   ( 5202): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5202): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5202): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:Utils( 3978): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3978): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3978): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/LGRssiData( 5202): [loadRssi] File not exist 
V/LGRssiData( 5202): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5202): [loadFeatureFromXml] *** start feature loading from xml
,I/AppUp4:CustModeStarterReceiver( 3978): onReceive
D/AppUp4:CustFacade( 3978): Context : android.app.ReceiverRestrictedContext@4284de70
D/AppUp4:CustFacade( 3978): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3978): isOpenOperator : true
D/AppUp4:CustFacade( 3978): isPhone : true
,I/LicenseContentProvider( 2976): start selecting data
,D/SIMObserver( 2976): simInfo1
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/TelephonyAutoProfiling( 5202): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5202): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5202): [getValue] FEATURE key : vzw_roaming_state, value : null
I/AppUp4:EulaManager( 3978): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3978): begin check event
D/AppUp4:Utils( 3978): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3978): Event For Nothing, skip.
,I/ActivityManager(  955): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5251 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
V/GmsNetworkLocationProvi( 1422): DISABLE
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/HyLog   ( 5251): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5251): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5251): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/SystemConfig( 5251): BUILD Country: EU
,I/SystemConfig( 5251): BUILD Operator: OPEN
E/BatteryObserver( 1155): usb Uevent not necessary.
I/ActivityManager(  955): Killing 4647:com.test.thalitest/u0a304 (adj 15): empty #17
,D/LocationProviderProxy(  955): applying state to connected service
,D/LocationProviderProxy(  955): applying state to connected service
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  955): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5266 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
D/WifiController(  955): battery changed pluggedType: 2
I/ActivityManager(  955): Killing 4563:com.lge.email/u0a24 (adj 15): empty #17
I/WindowState(  955): WIN DEATH: Window{430ed2e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  955): Client connection lost with reason: 4
,V/ActivityManager(  955): Moving to DESTROYED: ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/SystemConfig( 5251): systemFeature RCS result false
,I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,D/SystemConfig( 5251): refreshRcsSupport() :false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/ActivityManager(  955): Moving to DESTROYED: ActivityRecord{4282a068 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/InputMethodManagerService(  955): IME STATUS OFF
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c2cbe8 stackId=0, 1 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1}
W/InputMethodManagerService(  955): Got RemoteException sending setActive(false) notification to pid 4647 uid 10304
,W/Binder  ( 1315): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1315): java.lang.NullPointerException
W/Binder  ( 1315): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1315): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1315): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1315): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c2cbe8 stackId=0, 1 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 5266): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5266): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5266): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  955): Killing 4806:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/IcingCorporaProvider( 2675): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c2cbe8 stackId=0, 1 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1856): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1856): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  955): Delaying start of: ServiceRecord{43252558 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1856): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1856): GC_CONCURRENT freed 1943K, 22% free 19549K/24832K, paused 2ms+4ms, total 36ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2675): UpdateCorporaTask done [took 203 ms] updated apps [took 203 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  955): battery changed pluggedType: 2
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/CaptivePortalTracker(  955): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  955): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  955): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  955): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  955): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  955): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  955): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  955): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/GAV4    ( 5202): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,I/PowerManagerService(  955): Going to sleep due to screen timeout...,
D/KnockOnPowerController(  955): [updateScreenState] screen on = false
,D/KnockOnPowerController(  955): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  955): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  955): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  955): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  955): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  955): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  955): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  955): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8370 usec,
D/KnockOnPowerController(  955): [setProximitySensorEnabled] enable = true
V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.451462 Y: -0.403412 Z: 9.764755 
D/qcom_sensors_hal(  955): hal_acquire_resources
I/qcom_sensors_hal(  955): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  955): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  955): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  955): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  955): hal_sam_algo_activate: Update freq 0 -> 20
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451462 .y:-0.403412 .z:9.764755
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,I/qcom_sensors_hal(  955): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  955): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  955): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.469955 Y: -0.402924 Z: 9.774918 
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.469955 .y:-0.402924 .z:9.774918
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,I/Sensors (  318): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  955): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  955): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  955): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
D/KnockOnPowerController(  955): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  955): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  955): current mode = 1  value = 1 1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.476898 Y: -0.412140 Z: 9.772324 
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.476898 .y:-0.412140 .z:9.772324
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.471405 Y: -0.401138 Z: 9.779572 
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471405 .y:-0.401138 .z:9.779572
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.466843 Y: -0.395218 Z: 9.765274 
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466843 .y:-0.395218 .z:9.765274
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.466980 Y: -0.414398 Z: 9.763214 
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466980 .y:-0.414398 .z:9.763214
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.444458 Y: -0.406158 Z: 9.765961 
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444458 .y:-0.406158 .z:9.765961
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  955): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44debcc0)
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb70c0450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  955): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
I/WindowManager(  955): No lock screen! windowToken=null
,E/SlideAside( 3677): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  955): handleScreenStateChanged: true
,D/WifiStateMachine(  955): handleMessage: E msg.what=131154
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  955): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.478622 Y: -0.393036 Z: 9.750595 
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.473083 Y: -0.411896 Z: 9.763901 
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.478622 .y:-0.393036 .z:9.750595
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  955): handleMessage: E msg.what=131127
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131158
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  955): handleMessage: X
,D/WifiStateMachine(  955): handleMessage: E msg.what=132097
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
,D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  955): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2026): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2026): initialize kt scan interval and do scan state=9
D/WifiStateMachine(  955): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  955): stopMonitoring
,E/AudioSystem(  955): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 955
V/SRS_Proc(  270): ParamSet string: screen_state=on
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433a9c48 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1813): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:51:57
,I/SlideAside( 3677): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1813): 2 : This is isUpdating : false
,D/WeatherAncestor( 1813): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:51:57
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/WeatherService( 1813): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1813): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1813): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1813): 2 : shouldTimeTickRegistered : false
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1155): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1155): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1155): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1155): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1155): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1155): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  955): Excessive delay in blankDisplay() while turning screen off: 391ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745517830, nextTick: 2202, mDrawingTime: 0
,D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745517854, nextTick: 2179, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
,E/Parcel  (  410): Reading a NULL string not supported here.
D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/GsmSST  ( 1448): Emergency Service
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
D/WeatherService( 1813): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:51:57
D/WeatherService( 1813): 2 : ACTION screen on
,D/WeatherService( 1813): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1813): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:51:57
D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  955): ACTION_SCREEN_ON
D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  955): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  955): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  955): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  955): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
,V/ActivityManager(  955): Moving to PAUSING: ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  955): hal_acquire_resources
D/qcom_sensors_hal(  955): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  955): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  955): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  955): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  955): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
,W/ProcessCpuTracker(  955): Skipping unknown process pid 5316
,D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
W/ProcessCpuTracker(  955): Skipping unknown process pid 5317
W/ProcessCpuTracker(  955): Skipping unknown process pid 5322
W/ProcessCpuTracker(  955): Skipping unknown process pid 5327
W/ProcessCpuTracker(  955): Skipping unknown process pid 5332
W/ProcessCpuTracker(  955): Skipping unknown process pid 5337
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
,I/LGImmersionVibrator(  955): Vibrator off
,D/WifiStateMachine(  955): handleScreenStateChanged: false
D/WifiStateMachine(  955): handleMessage: E msg.what=131154
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiStateMachine(  955): handleMessage: X
,D/WifiStateMachine(  955): handleMessage: E msg.what=131158
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
,I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  955): doBoolean: DRIVER SETSUSPENDMODE 1
V/ActivityManager(  955): Moving to PAUSED: ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  955): Moving to STOPPING: ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/AudioSystem(  955): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 955
V/SRS_Proc(  270): ParamSet string: screen_state=off
V/ActivityManager(  955): Moving to STOPPED: ActivityRecord{42c81208 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  955): CMD_SCREEN_OFF 
,D/WifiController(  955): shouldWifiStayAwake TRUE
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
D/KeyguardViewManager( 1141): onScreenTurnedOff()
D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
,I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  955):    returned true
,D/WifiStateMachine(  955): handleMessage: X
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
D/VolumeVibrator( 1155): clear
,I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
,V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
E/Parcel  (  410): Reading a NULL string not supported here.
,E/Parcel  (  410): Reading a NULL string not supported here.
D/WeatherService( 1813): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:51:58
D/WeatherService( 1813): 2 : ACTION screen off
,D/WeatherService( 1813): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:51:58
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,D/NfcService( 1474): NFC-C OFF
D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): ACTION_SCREEN_OFF
D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1155): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1155): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1155): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1155): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1155): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1155): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1155): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 27, B = 27
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
,D/dalvikvm( 1155): GC_CONCURRENT freed 2888K, 11% free 25447K/28512K, paused 2ms+3ms, total 32ms
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  318): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiStateMachine(  955): handleMessage: X
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745520036, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745520044, nextTick: 59988, mDrawingTime: 0
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiStateMachine(  955): handleMessage: X
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Procstats( 1856): User is not opted-in to Usage & Diagnostics.
,D/Diskstats( 1856): User is not opted-in to Usage & Diagnostics.
,D/Finsky  ( 5135): [459] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5135): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745535641684848; DSPS: 5288013; Offset: 1450745374264334995
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  955): battery changed pluggedType: 2
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/VacuumService( 1538): Vacuum at: now=1450745548231 tag=VacuumService
,I/GoogleURLConnFactory( 1538): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1538): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1538): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1538): No account for auth token provided
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1538):  no longer exists, so no auth token.
,W/Uploader( 1538): No account for auth token provided
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745555642557304; DSPS: 5943402; Offset: 1450745374264322441
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745575643022605; DSPS: 6598777; Offset: 1450745374264329979
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745580048, nextTick: 59981, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745580051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745595643952445; DSPS: 7254168; Offset: 1450745374264313774
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745615644396588; DSPS: 7909542; Offset: 1450745374264330671
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745635644844712; DSPS: 8564917; Offset: 1450745374264321031
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745640044, nextTick: 59985, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745640047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745655646224689; DSPS: 9220322; Offset: 1450745374264327717
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745675647657446; DSPS: 9875729; Offset: 1450745374264326148
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  955): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/wpa_supplicant( 2026): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 6 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 7 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 3 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 8 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 9 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 5 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 a0:c5:62:7a:49:97]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 10:9a:dd:8e:22:d9]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 fe:94:e3:11:35:3c]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 fc:94:e3:11:35:3a]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:96]
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745695648113955; DSPS: 10531104; Offset: 1450745374264324893
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745700038, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745700041, nextTick: 59991, mDrawingTime: 0
,D/dalvikvm( 2662): GC_CONCURRENT freed 7690K, 32% free 16894K/24832K, paused 3ms+2ms, total 48ms
,D/dalvikvm( 2662): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm(  955): GC_EXPLICIT freed 2271K, 47% free 30705K/57468K, paused 3ms+10ms, total 122ms
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745715649038724; DSPS: 11186494; Offset: 1450745374264334135
,I/LocationManagerService(  955): remove 42fef800
D/LocationManagerService(  955): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  955): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  955): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  955): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  955): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2662): GC_CONCURRENT freed 1842K, 32% free 17062K/24832K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 2662): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/Mlt MonitorService( 2662): parseLastkmsg to dump
,D/dalvikvm( 2662): GC_CONCURRENT freed 1473K, 30% free 17606K/24832K, paused 3ms+2ms, total 40ms
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745735649936435; DSPS: 11841884; Offset: 1450745374264316318
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745755651248086; DSPS: 12497287; Offset: 1450745374264315713
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745760032, nextTick: 59987, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745760041, nextTick: 59991, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745775652161388; DSPS: 13152676; Offset: 1450745374264344006
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745795653042911; DSPS: 13808066; Offset: 1450745374264310001
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NotificationService(  955): updateLightListLocked :r=NotificationRecord(0x43236b88: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  955): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 5135): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5135): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5135): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5135): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5135): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5135): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5135): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5135): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 5135): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5135): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745815654068557; DSPS: 14463459; Offset: 1450745374264328567
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745820039, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745820042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745835654976384; DSPS: 15118849; Offset: 1450745374264320867
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745855655405895; DSPS: 15774223; Offset: 1450745374264323132
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745875657465892; DSPS: 16429651; Offset: 1450745374264307934
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745880052, nextTick: 59977, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745880055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745895658373823; DSPS: 17085040; Offset: 1450745374264330855
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745915658809895; DSPS: 17740414; Offset: 1450745374264339681
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745935659244737; DSPS: 18395789; Offset: 1450745374264316759
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745940032, nextTick: 59997, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450745940035, nextTick: 59997, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745955660181921; DSPS: 19051179; Offset: 1450745374264338416
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745975660619969; DSPS: 19706554; Offset: 1450745374264318700
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450745995661498313; DSPS: 20361943; Offset: 1450745374264312034
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746000034, nextTick: 59982, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746000045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746015662425903; DSPS: 21017333; Offset: 1450745374264324097
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746035662881391; DSPS: 21672708; Offset: 1450745374264321821
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746055663338029; DSPS: 22328083; Offset: 1450745374264320696
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746060034, nextTick: 59986, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746060042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746075664304617; DSPS: 22983475; Offset: 1450745374264310721
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746095664742809; DSPS: 23638849; Offset: 1450745374264321667
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746115665653367; DSPS: 24294238; Offset: 1450745374264347215
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746120027, nextTick: 60000, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746120051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746135666601379; DSPS: 24949630; Offset: 1450745374264318665
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746155667028474; DSPS: 25605004; Offset: 1450745374264318514
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  955): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746175667910250; DSPS: 26260393; Offset: 1450745374264315280
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746180037, nextTick: 59988, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746180042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746195668791172; DSPS: 26915781; Offset: 1450745374264341710
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746215669246351; DSPS: 27571156; Offset: 1450745374264339125
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  955): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  955): Done.
,D/QcConnectivityService(  955): Setting timer for 720seconds
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746235670120185; DSPS: 28226545; Offset: 1450745374264327949
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746240043, nextTick: 59966, mDrawingTime: 9,
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746240058, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746255671067381; DSPS: 28881936; Offset: 1450745374264329100
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746275671516445; DSPS: 29537311; Offset: 1450745374264320401
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746295672360470; DSPS: 30192699; Offset: 1450745374264309933
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746300037, nextTick: 59989, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746300040, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746315673754031; DSPS: 30848104; Offset: 1450745374264330203
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746335674177942; DSPS: 31503478; Offset: 1450745374264326868
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746355675081446; DSPS: 32158868; Offset: 1450745374264314845
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746360037, nextTick: 59991, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746360040, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746375676025810; DSPS: 32814259; Offset: 1450745374264313164
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746395676458067; DSPS: 33469633; Offset: 1450745374264318175
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746415677907738; DSPS: 34125040; Offset: 1450745374264333520
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746420031, nextTick: 59987, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746420054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746435678857186; DSPS: 34780431; Offset: 1450745374264336923
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746455679291128; DSPS: 35435806; Offset: 1450745374264313101
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746475680151272; DSPS: 36091194; Offset: 1450745374264318753
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746480035, nextTick: 59983, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746480050, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746495681147746; DSPS: 36746586; Offset: 1450745374264338664
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746515681586029; DSPS: 37401961; Offset: 1450745374264319184
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746535682446657; DSPS: 38057349; Offset: 1450745374264325320
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746540041, nextTick: 59977, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746540049, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746555683405792; DSPS: 38712740; Offset: 1450745374264338410
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746575683849136; DSPS: 39368115; Offset: 1450745374264323990
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746595684293986; DSPS: 40023490; Offset: 1450745374264311076
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746600036, nextTick: 59982, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746600045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746615685236950; DSPS: 40678880; Offset: 1450745374264338513
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746635685700952; DSPS: 41334256; Offset: 1450745374264314234
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746655686142262; DSPS: 41989630; Offset: 1450745374264328298
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746660052, nextTick: 59975, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746660054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746675695979755; DSPS: 42645312; Offset: 1450745374264339130
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746695696413809; DSPS: 43300687; Offset: 1450745374264315421
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746715697900267; DSPS: 43956095; Offset: 1450745374264337035
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746720059, nextTick: 59971, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746720060, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746735698760526; DSPS: 44611483; Offset: 1450745374264342802
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746755699188060; DSPS: 45266858; Offset: 1450745374264312572
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746775700083900; DSPS: 45922247; Offset: 1450745374264323402
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746780056, nextTick: 59972, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746780059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746795700952241; DSPS: 46577635; Offset: 1450745374264337251
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746815701379924; DSPS: 47233009; Offset: 1450745374264337688
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746835702312651; DSPS: 47888400; Offset: 1450745374264324370
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746840040, nextTick: 59986, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746840045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746855703673358; DSPS: 48543805; Offset: 1450745374264311786
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746875704532534; DSPS: 49199193; Offset: 1450745374264316470
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746895705373232; DSPS: 49854580; Offset: 1450745374264333193
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746900051, nextTick: 59978, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746900061, nextTick: 59971, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746915707522436; DSPS: 50510011; Offset: 1450745374264315649
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746935707939688; DSPS: 51165384; Offset: 1450745374264336173
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  955): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  955): Done.
,D/QcConnectivityService(  955): Setting timer for 720seconds
,I/EventLogService( 1856): Aggregate from 1450745498951 (log), 1450744609188 (data)
,D/GCM     ( 1538): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  955): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746955709286225; DSPS: 51820789; Offset: 1450745374264309419
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746960048, nextTick: 59968, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450746960060, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746975711308181; DSPS: 52476215; Offset: 1450745374264317215
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450746995712171741; DSPS: 53131603; Offset: 1450745374264326283
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747015713033631; DSPS: 53786991; Offset: 1450745374264333680
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450747020031, nextTick: 59996, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450747020054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747035714451471; DSPS: 54442398; Offset: 1450745374264317194
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747055714900477; DSPS: 55097772; Offset: 1450745374264338954
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747075716211915; DSPS: 55753176; Offset: 1450745374264307619
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450747080038, nextTick: 59974, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450747080051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747095718188392; DSPS: 56408600; Offset: 1450745374264330971
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747115719529290; DSPS: 57064004; Offset: 1450745374264329095
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747135720386657; DSPS: 57719392; Offset: 1450745374264331970
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450747140058, nextTick: 59970, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450747140059, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747155721337049; DSPS: 58374783; Offset: 1450745374264336317
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747175721777131; DSPS: 59030158; Offset: 1450745374264318635
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747195723189919; DSPS: 59685564; Offset: 1450745374264327615
,I/ProcessStatsService(  955): Prepared write state in 60ms
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450747200080, nextTick: 59947, mDrawingTime: 3
D/Clock   ( 1141): Clock updated, drawingStartTime : 1450747200083, nextTick: 59949, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  955): Pruning old procstats: /data/system/procstats/state-2015-12-21-08-09-00.bin
,D/LocationManagerService(  955): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1538): GC_CONCURRENT freed 1815K, 28% free 18043K/24832K, paused 2ms+4ms, total 120ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747215724875506; DSPS: 60340979; Offset: 1450745374264334735
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747235726159728; DSPS: 60996381; Offset: 1450745374264337219
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747255726602937; DSPS: 61651756; Offset: 1450745374264322664
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450747260048, nextTick: 59978, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450747260053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747275728002767; DSPS: 62307162; Offset: 1450745374264318685
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450747295728867900; DSPS: 62962550; Offset: 1450745374264329326
,TIME-OUT KILL (timeout was 1800000ms)
```
