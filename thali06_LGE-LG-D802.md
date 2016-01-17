#### Test 561510933390750_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,--------- beginning of /dev/log/main
W/GAV2    ( 4614): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  967): Killing 3958:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d06f60 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1962): GC_CONCURRENT freed 1580K, 22% free 19438K/24832K, paused 4ms+3ms, total 49ms
D/dalvikvm( 1962): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/ConfigFetchService( 1962): fetch service done; releasing wakelock
I/ConfigFetchService( 1962): stopping self
D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4658): 
D/AndroidRuntime( 4658): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4658): CheckJNI is OFF
D/dalvikvm( 4658): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4658): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4658): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4658): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4658): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4658): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1962): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1962): Loaded CLD2 Version V2.0 - 20141016
E/memtrack( 4658): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4658): failed to load memtrack module: -2
I/Icing   ( 1962): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/AndroidRuntime( 4658): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4658
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (833 us)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{42d06f60 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  967): GC_FOR_ALLOC freed 24338K, 54% free 27967K/59796K, paused 137ms, total 139ms
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{4331ef70 stackId=1, 2 tasks}
D/UsbSettingsControl( 2583): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2583): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4658): Shutting down VM
D/dalvikvm( 4658): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42d06f60 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{42d06f60 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4676 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3718): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3718): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3718): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4676): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4676): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4676): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/WebViewChromium( 4676): Binding Chromium to the background looper Looper (main, tid 1) {428c9b18}
I/chromium( 4676): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4676): Initializing chromium process, renderers=0
W/chromium( 4676): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4676): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4676): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4676): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4676): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4676): Remote Branch: 
I/Adreno-EGL( 4676): Local Patches: 
I/Adreno-EGL( 4676): Reconstruct Branch: 
I/dalvikvm( 4676): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4676): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4676): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4676): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4676): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4676): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4676): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4676): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4676): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4676): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4676): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4676): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4676): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4676): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4676): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4676): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4676): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4676): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4676): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4676): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2037): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
W/BaseRuntimeLoader( 4676): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4676): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4676): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4676): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
D/OpenGLRenderer( 4676): Enabling debug mode 0
W/AwContents( 4676): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +394ms
I/InputMethodManagerService(  967): IME STATUS OFF
W/AwContents( 4676): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 4676): Timeline: Activity_idle id: android.os.BinderProxy@428cb3d8 time:112036
D/JsMessageQueue( 4676): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4676): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428cf4b8
D/dalvikvm( 4676): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428cf4b8
D/jxcore_app_log( 4676): JniHelper::setJavaVM(0x41796838), pthread_self() = 1632044440
D/JX-Cordova( 4676): jxcore cordova android initializing
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3} time:112384
D/ActivityManager(  967): no-history finish of ActivityRecord{42d06f60 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{42c1f9d0 ActivityRecord{42d06f60 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{42d06f60 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{42d06f60 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2583): [AUTORUN] onStop()
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{42d06f60 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.463226 Y: -0.402481 Z: 9.807770 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463226 .y:-0.402481 .z:9.807770
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/dalvikvm( 4676): GC_CONCURRENT freed 2667K, 12% free 21985K/24832K, paused 1ms+2ms, total 31ms
D/dalvikvm( 4676): WAIT_FOR_CONCURRENT_GC blocked 25ms
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.457306 Y: -0.398071 Z: 9.798553 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457306 .y:-0.398071 .z:9.798553
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/dalvikvm( 4676): GC_FOR_ALLOC freed 327K, 10% free 22357K/24832K, paused 22ms, total 22ms
I/dalvikvm-heap( 4676): Grow heap (frag case) to 24.047MB for 42652-byte allocation
D/dalvikvm( 4676): GC_FOR_ALLOC freed 102K, 11% free 22364K/24876K, paused 37ms, total 37ms
D/dalvikvm( 4676): GC_FOR_ALLOC freed 124K, 11% free 22384K/24876K, paused 34ms, total 34ms
I/dalvikvm-heap( 4676): Grow heap (frag case) to 24.125MB for 95956-byte allocation
D/dalvikvm( 4676): GC_FOR_ALLOC freed 178K, 11% free 22419K/24972K, paused 22ms, total 22ms
I/dalvikvm-heap( 4676): Grow heap (frag case) to 24.205MB for 143930-byte allocation
D/dalvikvm( 4676): GC_FOR_ALLOC freed 251K, 11% free 22466K/25116K, paused 22ms, total 22ms
I/dalvikvm-heap( 4676): Grow heap (frag case) to 24.319MB for 215890-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
D/dalvikvm( 4676): GC_FOR_ALLOC freed 366K, 12% free 22540K/25328K, paused 26ms, total 27ms
I/dalvikvm-heap( 4676): Grow heap (frag case) to 24.494MB for 323830-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/dalvikvm( 4676): GC_FOR_ALLOC freed 565K, 12% free 22661K/25648K, paused 34ms, total 35ms
I/dalvikvm-heap( 4676): Grow heap (frag case) to 24.766MB for 485740-byte allocation
D/dalvikvm( 4676): GC_FOR_ALLOC freed 858K, 13% free 22837K/26124K, paused 23ms, total 23ms
D/dalvikvm( 4676): GC_FOR_ALLOC freed 1075K, 12% free 23072K/26124K, paused 22ms, total 23ms
D/dalvikvm( 4676): GC_FOR_ALLOC freed 242K, 12% free 23050K/26124K, paused 22ms, total 22ms
I/dalvikvm-heap( 4676): Grow heap (frag case) to 25.725MB for 1092904-byte allocation
D/dalvikvm( 4676): GC_CONCURRENT freed 1812K, 14% free 23567K/27192K, paused 2ms+2ms, total 40ms
D/dalvikvm( 4676): GC_FOR_ALLOC freed 115K, 14% free 23478K/27192K, paused 22ms, total 22ms
I/dalvikvm-heap( 4676): Grow heap (frag case) to 26.665MB for 1639352-byte allocation
D/dalvikvm( 4676): GC_CONCURRENT freed 1891K, 17% free 24004K/28796K, paused 2ms+2ms, total 30ms
D/dalvikvm( 4676): GC_FOR_ALLOC freed 1073K, 17% free 23992K/28796K, paused 24ms, total 24ms
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
I/dalvikvm-heap( 4676): Grow heap (frag case) to 27.948MB for 2459024-byte allocation
D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
D/Clock   ( 1141): Clock updated, drawingStartTime : 1453032840033, nextTick: 60000, mDrawingTime: 0
D/Clock   ( 1141): Clock updated, drawingStartTime : 1453032840034, nextTick: 59998, mDrawingTime: 0
D/dalvikvm( 4676): GC_CONCURRENT freed 2209K, 21% free 24833K/31200K, paused 10ms+7ms, total 68ms
,D/dalvikvm( 4676): GC_FOR_ALLOC freed 2299K, 20% free 24996K/31200K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4676): Grow heap (frag case) to 30.101MB for 3688532-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4676): GC_CONCURRENT freed 316K, 18% free 28543K/34804K, paused 1ms+12ms, total 45ms
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1221): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,D/dalvikvm( 4676): GC_FOR_ALLOC freed 4410K, 25% free 26132K/34804K, paused 27ms, total 27ms
,W/jxcore-log( 4676): Initializing JXcore engine
,W/jxcore-log( 4676): JXcore engine is ready
,D/dalvikvm( 4676): GC_CONCURRENT freed 412K, 17% free 28942K/34804K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 4676): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4676): Starting JXcore engine
,W/jxcore-log( 4676): Platform android
W/jxcore-log( 4676): 
,W/jxcore-log( 4676): Process ARCH arm
W/jxcore-log( 4676): 
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4676): JXcore Cordova bridge is ready!
I/jxcore-log( 4676): 
,W/jxcore-log( 4676): JXcore engine is started
,I/chromium( 4676): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4676): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4676): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4676): Toggling radios to true
I/jxcore-log( 4676): 
,D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@432da4c0:true
,D/BluetoothAdapter( 4676): enable(): BT is already enabled..!
D/WifiStateMachine(  967): handleMessage: E msg.what=131145
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doBoolean: DISCONNECT
D/WifiService(  967): New client listening to asynchronous messages
D/WifiService(  967): setWifiEnabled: true pid=4676, uid=10304
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  967): disconnect pid=4676, uid=10304
,D/WifiService(  967): reconnect pid=4676, uid=10304
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2037): wlan0: Cancelling scan request
D/wpa_supplicant( 2037): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2037): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2037): TDLS: Tear down peers
D/wpa_supplicant( 2037): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4676): Radios toggled
I/jxcore-log( 4676): 
I/jxcore-log( 4676): My device name is: LGE-LG-D802
I/jxcore-log( 4676): 
,D/wpa_supplicant( 2037): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2037): wlan0: Deauthentication notification
D/wpa_supplicant( 2037): wlan0:  * reason 3 (locally generated)
,D/wpa_supplicant( 2037): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2037): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2037): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2037): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2037): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb76d6d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
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
,D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2037): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2037): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2037): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2037): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2037): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
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
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2037): Fast associate: Old scan results
D/wpa_supplicant( 2037): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2037): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2037): wlan0: nl80211: scan request
D/wpa_supplicant( 2037): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2037): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2037): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147460
D/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection lost
D/WifiStateMachine(  967): Stopping DHCP and clearing IP
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
,D/DhcpStateMachine(  967): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  967): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
D/QCNEA   (  391): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  391): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  391): |CAC| updateNetCfgInfo
V/QCNEA   (  391): |CAC| *********************************************
V/QCNEA   (  391): |CAC|                   Netconfig               
V/QCNEA   (  391): |CAC| *********************************************
V/QCNEA   (  391): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  391): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  391): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  391): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  391): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  391): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  391): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  391): |CAC| *********************************************
D/QCNEA   (  391): |CAC| Received bssid= 
D/QCNEA   (  391): |CAC| net type = 3
V/QCNEA   (  391): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  391): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  391): |CAC| 	ssid           =NG700
V/QCNEA   (  391): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  391): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  391): |CAC| *********************************************
D/QCNEA   (  391): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  391): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  391): |CAC| dispatchNetCfg: updating:0xb7ced8dc
D/QCNEA   (  391): |CAC| readCallback: read len:0, ret:-1, errno:11
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/Parcel  (  391): Reading a NULL string not supported here.
,E/Parcel  (  391): Reading a NULL string not supported here.
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiHS20(  967): hidePasspointNotification off =false
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  967): Attempting to switch to mobile
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
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
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4736 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
,D/HyLog   ( 4736): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4736): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4736): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
W/NetworkManagementService(  967): route cmd failed: 
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
D/NetUtils(  967): android_net_utils_resetConnections in env=0x6207f978 clazz=0x6c300001 iface=wlan0 mask=0x3
V/NativeCrypto( 1554): Read error: ssl=0x6417d700: I/O error during system call, Connection timed out
,V/NativeCrypto( 1554): SSL shutdown failed: ssl=0x6417d700: I/O error during system call, Broken pipe
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PCSuite ( 4736): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 4736): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4736): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4767 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  967): Killing 4166:com.google.android.talk/u0a77 (adj 15): empty #17
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4767): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4767): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4767): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4767): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4767): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4767): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4767): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4767): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4767): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4767): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  967): Killing 3110:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  967): StoppedState
,I/GAV2    ( 4614): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1554): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4676): 
,I/jxcore-log( 4676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4676): 
,I/jxcore-log( 4676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4676): 
,I/jxcore-log( 4676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4676): 
,I/jxcore-log( 4676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4676): 
,I/jxcore-log( 4676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4676): 
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4676): Test app app.js loaded
I/jxcore-log( 4676): 
,I/Choreographer( 4676): Skipped 193 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4676): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Tethering(  967): MasterInitialState.processMessage what=3
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4013): onReceive
,D/AppUp4:CustFacade( 4013): Context : android.app.ReceiverRestrictedContext@428e7f10
D/AppUp4:CustFacade( 4013): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4013): isOpenOperator : true
,D/AppUp4:CustFacade( 4013): isPhone : true
,I/LicenseContentProvider( 2963): start selecting data
,D/SIMObserver( 2963): simInfo1
,I/AppUp4:EulaManager( 4013): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4013): begin check event
,I/AppUp4:CustModeStarterReceiver( 4013): Event For GoodConnectivity
,I/ActivityManager(  967): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4795 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4795): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4795): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4795): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/EAS     ( 4596): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4596): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4795): DownloadService onCreate
,I/DownloadManager( 4795): in removeSpuriousFiles
,D/eas_req ( 4596): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2037): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2037): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2037): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 2037): nl80211: Survey data missing
D/wpa_supplicant( 2037): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2037): wlan0: BSS: Add new id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 2037): wlan0: New scan results available
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2037): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2037): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 2037): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2037): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2037): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2037): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2037): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59
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
D/wpa_supplicant( 2037): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb76d85a8  current_ssid=0x0
D/wpa_supplicant( 2037): scard is not null..
D/wpa_supplicant( 2037): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2037): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2037): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 2037): wlan0: Cancelling scan request
D/wpa_supplicant( 2037): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2037): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2037): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2037): RSN: PMKSA cache search - network_ctx=0xb76d85a8 try_opportunistic=0
D/wpa_supplicant( 2037): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2037): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2037): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2037): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2037): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2037): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2037): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2037): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2037): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2037): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2037): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2037): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2037): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2037): nl80211: Unsubscribe mgmt frames handle 0xb76d7590 (mode change)
D/wpa_supplicant( 2037): nl80211: Subscribe to mgmt frames with non-AP handle 0xb76d7590
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb76d7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb76d7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb76d7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb76d7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb76d7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb76d7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb76d7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb76d7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb76d7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb76d7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2037): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2037):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037):   * freq=2412
D/wpa_supplicant( 2037):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2037):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037):   * Auth Type 0
D/wpa_supplicant( 2037):   * WPA Versions 0x2
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 c2:ff:d4:d3:aa:48]
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
D/wpa_supplicant( 2037): nl80211: Connect request send successfully
D/wpa_supplicant( 2037): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2037): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): EAPOL: External notification - EAP fail=0
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2037): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
V/DownloadManager( 4795): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@4290f8e0 on behalf of 4795
I/DownloadManager( 4795): in trimDatabase
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
V/DownloadManager( 4795): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/WifiStateMachine(  967): handleMessage: X
V/DownloadManager( 4795): DownloadService onStartCommand
V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@42911730 on behalf of 4795
I/LgeMiscReceiver( 4353): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4353): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4795): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4353): networkInfo.isConnected() = false
W/linker  ( 4596): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4596): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4596): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4596): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4596): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4596): register_HtmlEditor, Success
D/HtmlEditor( 4596): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4596): register_HtmlEditorTimer, Success
D/HtmlEditor( 4596): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4596): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4596): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4596): register_HtmlEditorFont, Success
D/HtmlEditor( 4596): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4596): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4596): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4596): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4596): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4596): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4596): JNI_OnLoad Success
I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4814 uid=10052 gids={50052, 3003}
I/HubEmail( 4596): JNI_OnLoad()
I/HubEmail( 4596): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4596): registerNatives()
I/HubEmail( 4596): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4596): registerNativeMethods()
I/HubEmail( 4596): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4596): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2037): nl80211: Connect event
D/wpa_supplicant( 2037): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2037): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2037): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2037): wlan0: Association info event
D/wpa_supplicant( 2037): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2037): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
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
D/HyLog   ( 4814): I : /data/font/config/sfconfig.dat, No such file or directory (2)
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
D/wpa_supplicant( 2037): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@42914448 on behalf of 4795
D/HyLog   ( 4814): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4814): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/DownloadManager( 4795): DownloadService onDestroy
D/wpa_supplicant( 2037): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 de c0 79 d2 72 b1 92 f3 ec a0 ec c2 f6 1e 4e ...
D/wpa_supplicant( 2037): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2037): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2037): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2037): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2037): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2037):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2037):   key_nonce - hexdump(len=32): de c0 79 d2 72 b1 92 f3 ec a0 ec c2 f6 1e 4e 9c 24 97 36 1f 88 db 5d b7 a7 cd f2 ce 9e 49 d7 d9
D/wpa_supplicant( 2037):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 de c0 79 d2 72 b1 92 f3 ec a0 ec c2 f6 1e 4e ...
D/wpa_supplicant( 2037): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2037): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2037): Get randomness: len=32 entropy=8
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 2037): WPA: Renewed SNonce - hexdump(len=32): 09 b3 a2 e3 34 d4 2d 18 48 1a 48 a0 83 03 bc 8a 70 3b d1 1c 6e d4 3d a5 4c c5 14 d9 70 11 e7 ba
D/wpa_supplicant( 2037): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): WPA: Nonce1 - hexdump(len=32): 09 b3 a2 e3 34 d4 2d 18 48 1a 48 a0 83 03 bc 8a 70 3b d1 1c 6e d4 3d a5 4c c5 14 d9 70 11 e7 ba
D/wpa_supplicant( 2037): WPA: Nonce2 - hexdump(len=32): de c0 79 d2 72 b1 92 f3 ec a0 ec c2 f6 1e 4e 9c 24 97 36 1f 88 db 5d b7 a7 cd f2 ce 9e 49 d7 d9
D/wpa_supplicant( 2037): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2037): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2037): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2037): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2037): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): WPA: Derived Key MIC - hexdump(len=16): 59 8c 51 35 76 a8 fb 4d a0 54 04 68 21 48 44 96
D/wpa_supplicant( 2037): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 09 b3 a2 e3 34 d4 2d 18 48 1a 48 a0 83 03 bc ...
,I/ActivityManager(  967): Killing 3899:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
D/wpa_supplicant( 2037): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 de c0 79 d2 72 b1 92 f3 ec a0 ec c2 f6 1e 4e ...
D/wpa_supplicant( 2037): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2037): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2037): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2037): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2037):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2037):   key_nonce - hexdump(len=32): de c0 79 d2 72 b1 92 f3 ec a0 ec c2 f6 1e 4e 9c 24 97 36 1f 88 db 5d b7 a7 cd f2 ce 9e 49 d7 d9
D/wpa_supplicant( 2037):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_rsc - hexdump(len=8): 6e 03 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_mic - hexdump(len=16): 22 8c d2 cf da 34 ec d3 77 dd c7 77 1f 82 26 bc
D/wpa_supplicant( 2037): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 de c0 79 d2 72 b1 92 f3 ec a0 ec c2 f6 1e 4e ...
D/wpa_supplicant( 2037): RSN: encrypted key data - hexdump(len=56): 4b a6 db de 5c 65 21 2e 10 62 47 f7 03 b5 ee c5 fc 50 e6 7a 1d 2a ea cb 0f ab 5b 8f a6 9d be 1a ...
D/wpa_supplicant( 2037): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2037): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2037): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2037): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 44 4c ...
D/wpa_supplicant( 2037): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
V/LGRssiData( 4814): [loadRssi] File not exist 
D/wpa_supplicant( 2037): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2037): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2037): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): WPA: Derived Key MIC - hexdump(len=16): 13 72 c4 c4 c4 55 3c b6 e9 73 e5 b3 92 82 7f 61
D/wpa_supplicant( 2037): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2037): wlan0: WPA: Installing PTK to the driver
V/LGRssiData( 4814): [loadRssi] File not exist 
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb76d7c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2037):    addr=c0:ff:d4:d3:aa:48
V/TelephonyAutoProfiling( 4814): [loadFeatureFromXml] *** start feature loading from xml
D/wpa_supplicant( 2037): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2037): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2037): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2037): WPA: RSC - hexdump(len=6): 6e 03 00 00 00 00
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f3603a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2037):    broadcast key
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
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
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
W/BaseRuntimeLoader( 4814): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4814): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection established
W/BaseRuntimeLoader( 4814): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4814): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2037): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
V/TelephonyAutoProfiling( 4814): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
V/TelephonyAutoProfiling( 4814): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4814): [getValue] FEATURE key : vzw_roaming_state, value : null
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  967):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  967): ssid=NG700
D/WifiNative-wlan0(  967): id=0
D/WifiNative-wlan0(  967): mode=station
D/WifiNative-wlan0(  967): pairwise_cipher=CCMP
D/WifiNative-wlan0(  967): group_cipher=CCMP
D/WifiNative-wlan0(  967): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  967): wpa_state=COMPLETED
D/WifiNative-wlan0(  967): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  967): address=34:fc:ef:de:0a:e2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/WifiServiceExtension(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/MobileConnectivityChangeReceiver( 4814): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
D/MobileConnectivityChangeReceiver( 4814): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/PhoneMonitor( 4814): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4814): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-13ms what=147462 obj=android.net.wifi.StateChangeResult@432ccd38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/DhcpStateMachine(  967): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-8ms what=147462 obj=android.net.wifi.StateChangeResult@43c13100 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-8ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-1ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 2037): nl80211: survey data missing!
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
D/WifiStateMachine(  967): handleMessage: X
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  967): handleMessage: E msg.what=196612
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4839 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4325:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/HyLog   ( 4839): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4839): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4839): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4855 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  967): Killing 4488:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4855): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4855): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4855): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,I/ActivityManager(  967): Killing 4551:com.google.android.partnersetup/u0a9 (adj 15): empty #17
E/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
,E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  264): Setting iface cfg
,D/WifiStateMachine(  967): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  967): handleMessage: X
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42aab160 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42aab160 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4868 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-5ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-6ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/HyLog   ( 4868): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/HyLog   ( 4868): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4868): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): DHCP successful
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  967): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState enter
,D/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
,E/Parcel  (  391): Reading a NULL string not supported here.
D/LGDMSGCM( 4868): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
,D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/WifiStateMachine(  967): handleMessage: X
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  967): handleMessage: E msg.what=131092
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
,D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 1
,I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4882 uid=10101 gids={50101, 1028, 1015, 3003}
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/ActivityManager(  967): Killing 4584:com.lge.bnr/1000 (adj 15): empty #17
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/dalvikvm(  967): GC_CONCURRENT freed 1178K, 51% free 29670K/59796K, paused 4ms+6ms, total 88ms
D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 58ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 56ms
D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 57ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 57ms
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
D/HyLog   ( 4882): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4882): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4882): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,I/NFS     ( 4882): connectivityManager.getNetworkInfo = TYPE_WIFI
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/Wireless_Storage( 4882): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4882): intf.getDisplayName() = lo
I/Wireless_Storage( 4882): intf.getDisplayName() = sit0
I/Wireless_Storage( 4882): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4882): intf.getDisplayName() = teql0
,I/Wireless_Storage( 4882): intf.getDisplayName() = wlan0
D/NFS     ( 4882): interface name:wlan0 name:wlan0
D/NFS     ( 4882): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4882): interface name:wlan0 name:wlan0
D/NFS     ( 4882): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4882): CONNECT : WIFI_CONNECT
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4902 uid=10104 gids={50104, 3003, 1028, 1015}
I/ActivityManager(  967): Killing 4213:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
,D/HyLog   ( 4902): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4902): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4902): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
V/        (  264): RouteController
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/QCNEA   (  391): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  391): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  391): |CAC| updateNetCfgInfo
V/QCNEA   (  391): |CAC| *********************************************
V/QCNEA   (  391): |CAC|                   Netconfig               
V/QCNEA   (  391): |CAC| *********************************************
V/QCNEA   (  391): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  391): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  391): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  391): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  391): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  391): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  391): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  391): |CAC| *********************************************
D/QCNEA   (  391): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  391): |CAC| net type = 1
V/QCNEA   (  391): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  391): |CAC| Received ssid= NG700
V/QCNEA   (  391): |CAC| 	ssid           =NG700
V/QCNEA   (  391): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  391): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  391): |CAC| *********************************************
D/QCNEA   (  391): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  391): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  391): |CAC| dispatchNetCfg: updating:0xb7ced8dc
D/QCNEA   (  391): |CAC| readCallback: read len:0, ret:-1, errno:11
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinService( 1962): Checking schedule, now: 1453032845289 next: 1453032787686
,I/CheckinService( 1962): active receiver: enabled
,W/GAV2    ( 4902): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/CheckinService( 1962): Preparing to send checkin request
,I/EventLogService( 1962): Accumulating logs since 1453032835018
,I/CheckinRequestBuilder( 1962): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1962): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1554): GC_EXPLICIT freed 1211K, 29% free 17822K/24832K, paused 2ms+3ms, total 25ms
,V/WebViewChromium( 4902): Binding Chromium to the main looper Looper (main, tid 1) {428d3448}
,I/chromium( 4902): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4902): Initializing chromium process, renderers=0
,W/chromium( 4902): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4902): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4902): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4902): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4902): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4902): Remote Branch: 
I/Adreno-EGL( 4902): Local Patches: 
I/Adreno-EGL( 4902): Reconstruct Branch: 
,I/NSApplication( 4902): Starting up...
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  967): Killing 4233:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,D/QRemote ( 4767): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4767): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4767): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4767): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,W/CheckinRequestBuilder( 1962): awaiting user notification for token
,D/QRemote ( 4767): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4767): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x432a3df0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,I/PCSuite ( 4736): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/PCSuite ( 4736): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4767): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4767): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4767): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4767): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4952 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,D/HyLog   ( 4952): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4952): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4952): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,W/dalvikvm( 4952): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4952): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4952): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4952): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4952): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4952): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4952): install
,I/MultiDex( 4952): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
,I/MultiDex( 4952): loading existing secondary dex files
,I/MultiDex( 4952): load found 3 secondary dex files
,I/MultiDex( 4952): install done
,D/dalvikvm( 4952): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 4952): VFY: unable to resolve instance field 61
,D/dalvikvm( 4952): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4952): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4952): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4952): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4952): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4952): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4952): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4952): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4952): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4952): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428da5f8
,D/dalvikvm( 4952): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428da5f8
,D/dalvikvm( 4952): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428da5f8, skipping init
,D/dalvikvm( 4952): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428da5f8
D/dalvikvm( 4952): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428da5f8
,V/JNIHelp ( 4952): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4952): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428da5f8
,D/dalvikvm( 4952): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428da5f8
D/dalvikvm( 4952): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428da5f8
,D/dalvikvm( 4952): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428da5f8
,I/ProviderInstaller( 4952): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1554): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1554): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1962): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1865): callingUid 10006, callindPid: 1865
,E/MDM     ( 1419): [61] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1962): Restart initialization of location
I/dalvikvm( 4952): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4952): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4952): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4952): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4952): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4952): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ff3000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ff3000
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
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=405778559
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4952): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ab5638
D/dalvikvm( 4952): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ab5638
,D/dalvikvm( 4952): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ab5638, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
D/wpa_supplicant( 2037): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2037): EAPOL: disable timer tick
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=3465509050
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4952): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4972): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 4952): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4952): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 85ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Adreno-EGL( 4952): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4952): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4952): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4952): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4952): Remote Branch: 
I/Adreno-EGL( 4952): Local Patches: 
I/Adreno-EGL( 4952): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Adreno-EGL( 4952): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4952): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4952): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4952): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4952): Remote Branch: 
I/Adreno-EGL( 4952): Local Patches: 
I/Adreno-EGL( 4952): Reconstruct Branch: 
,I/Adreno-EGL( 4952): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4952): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4952): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4952): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4952): Remote Branch: 
I/Adreno-EGL( 4952): Local Patches: 
I/Adreno-EGL( 4952): Reconstruct Branch: 
,W/Settings( 4952): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
,V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  967): RunningState
,I/CheckinRequestBuilder( 1962): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  967): battery changed pluggedType: 2
D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/CheckinTask( 1962): Sending checkin request (11588 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1962): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1962): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x430f4260: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1962): awaiting user notification for token
,I/CheckinRequestBuilder( 1962): Classify the device as Phone.,
,I/CheckinTask( 1962): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1962): Checking schedule, now: 1453032847603 next: 1453610243598
,I/CheckinService( 1962): active receiver: disabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1554): Connected
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1554): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,E/Parcel  (  391): Reading a NULL string not supported here.
,E/Parcel  (  391): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4013): onReceive
,D/AppUp4:CustFacade( 4013): Context : android.app.ReceiverRestrictedContext@428e7f10
,D/AppUp4:CustFacade( 4013): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4013): isOpenOperator : true
D/AppUp4:CustFacade( 4013): isPhone : true
,I/LicenseContentProvider( 2963): start selecting data
,D/SIMObserver( 2963): simInfo1
,I/AppUp4:EulaManager( 4013): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4013): begin check event
,I/AppUp4:CustModeStarterReceiver( 4013): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4013): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4013): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4013): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4013): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4013): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4795): DownloadService onCreate
,D/EAS     ( 4596): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4596): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4596): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4353): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4353): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4353): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4814): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4814): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,I/DownloadManager( 4795): in removeSpuriousFiles
,V/DownloadManager( 4795): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@4291a2a0 on behalf of 4795
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 4795): in trimDatabase
,V/DownloadManager( 4795): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@4291c110 on behalf of 4795
,V/DownloadManager( 4795): DownloadService onStartCommand
,V/DownloadManager( 4795): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,W/Settings( 4596): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@4291de48 on behalf of 4795
,D/LGDMSGCM( 4868): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 4882): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4882): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/DownloadManager( 4795): DownloadService onDestroy
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4013): onReceive
,D/AppUp4:CustFacade( 4013): Context : android.app.ReceiverRestrictedContext@428e7f10
D/AppUp4:CustFacade( 4013): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4013): isOpenOperator : true
,D/AppUp4:CustFacade( 4013): isPhone : true
,I/LicenseContentProvider( 2963): start selecting data
,D/SIMObserver( 2963): simInfo1
,I/AppUp4:EulaManager( 4013): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4013): begin check event
,I/AppUp4:CustModeStarterReceiver( 4013): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4795): DownloadService onCreate
D/EAS     ( 4596): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,I/DownloadManager( 4795): in removeSpuriousFiles
D/EAS     ( 4596): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4795): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@429224d0 on behalf of 4795
,I/DownloadManager( 4795): in trimDatabase
V/DownloadManager( 4795): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@42923e40 on behalf of 4795
V/DownloadManager( 4795): DownloadService onStartCommand
I/LgeMiscReceiver( 4353): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4353): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4353): networkInfo.isConnected() = true
D/PhoneState( 4353): setPdpRejectCasuse : false
,V/DownloadManager( 4795): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/MobileConnectivityChangeReceiver( 4814): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4814): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4596): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@42925b78 on behalf of 4795
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4795): DownloadService onDestroy
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4868): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4882): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4882): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
D/HeadsetStateMachine( 1221): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
D/HeadsetStateMachine( 1221): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] connect :true,
,I/NetworkStateForAutoUpdateMonitor( 4013): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4013): onReceive
,D/AppUp4:CustFacade( 4013): Context : android.app.ReceiverRestrictedContext@428e7f10
,D/AppUp4:CustFacade( 4013): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4013): isOpenOperator : true
,D/AppUp4:CustFacade( 4013): isPhone : true
,I/LicenseContentProvider( 2963): start selecting data
,D/SIMObserver( 2963): simInfo1
,I/AppUp4:EulaManager( 4013): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4013): begin check event
,I/AppUp4:CustModeStarterReceiver( 4013): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4596): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4596): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4795): DownloadService onCreate
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 4795): in removeSpuriousFiles
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4795): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@42929d00 on behalf of 4795
,I/DownloadManager( 4795): in trimDatabase
,V/DownloadManager( 4795): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@4292bb70 on behalf of 4795
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  967): GC_EXPLICIT freed 2215K, 51% free 29707K/59796K, paused 7ms+6ms, total 138ms
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
V/DownloadManager( 4795): DownloadService onStartCommand
,V/DownloadManager( 4795): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,V/DownloadManager( 4795): created cursor android.database.sqlite.SQLiteCursor@4292d8a8 on behalf of 4795
I/LgeMiscReceiver( 4353): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4353): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4353): networkInfo.isConnected() = true
,D/PhoneState( 4353): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4814): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/WifiController(  967): battery changed pluggedType: 2
D/MobileConnectivityChangeReceiver( 4814): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4596): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4795): DownloadService onDestroy
D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4868): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4882): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4882): CONNECT : WIFI_CONNECT
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4902): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  391): Reading a NULL string not supported here.
,E/Parcel  (  391): Reading a NULL string not supported here.
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  967): Killing 4614:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.462219 Y: -0.403580 Z: 9.792191 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462219 .y:-0.403580 .z:9.792191
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.468491 Y: -0.411469 Z: 9.782242 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.468491 .y:-0.411469 .z:9.782242
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.467041 Y: -0.411102 Z: 9.794220 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467041 .y:-0.411102 .z:9.794220
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4252): [402] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4252): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5116 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,E/SlideAside( 3718): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
D/administrator(  967): Handling package changes for user 0
,I/[LGHome]EVENT( 1482): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/SlideAside( 3718): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/[LGHome]LGPlusHomeDBManager( 1482): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1482): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1482): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5116): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5116): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5116): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/HeadsetStateMachine( 1221): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5116): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5116): MmsConfig.loadMmsSettings
,I/Babel   ( 5116): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5116): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5116): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5116): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5116): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5116): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/[LGHome]EVENT( 1482): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/BaseRuntimeLoader( 5116): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5116): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5116): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5116): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5116): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5116): MmsConfig.loadFromResources
,E/Babel   ( 5116): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5116): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1419): DISABLE
,I/GCoreNlp( 1419): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 5116): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5116): [loadRssi] File not exist 
,V/LGRssiData( 5116): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5116): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5116): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5116): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5116): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4013): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 4013): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4013): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4013): onReceive
,D/AppUp4:CustFacade( 4013): Context : android.app.ReceiverRestrictedContext@428e7f10
D/AppUp4:CustFacade( 4013): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4013): isOpenOperator : true
,D/AppUp4:CustFacade( 4013): isPhone : true
,I/LicenseContentProvider( 2963): start selecting data
,D/SIMObserver( 2963): simInfo1
,I/AppUp4:EulaManager( 4013): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4013): begin check event
D/AppUp4:Utils( 4013): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4013): Event For Nothing, skip.
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5170 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5170): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5170): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5170): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5170): BUILD Country: EU
,I/SystemConfig( 5170): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 4736:com.lge.sync/1000 (adj 15): empty #17
,I/SystemConfig( 5170): systemFeature RCS result false
,D/SystemConfig( 5170): refreshRcsSupport() :false
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5184 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  967): Killing 4767:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5184): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5184): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5184): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  967): Killing 4795:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2654): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1962): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  967): Delaying start of: ServiceRecord{44c4b350 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1962): updateResources: need to parse f{com.google.android.gms}
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm( 1962): GC_CONCURRENT freed 1891K, 22% free 19555K/24832K, paused 2ms+5ms, total 47ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2654): UpdateCorporaTask done [took 261 ms] updated apps [took 261 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  967): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/GAV4    ( 5116): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
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
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9000 usec
,D/qcom_sensors_hal(  967): hal_acquire_resources
,I/qcom_sensors_hal(  967): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  967): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  967): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  967): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  967): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  967): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  967): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  967): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.465805 Y: -0.407394 Z: 9.814316 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465805 .y:-0.407394 .z:9.814316
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.457321 Y: -0.408417 Z: 9.840500 
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.465088 Y: -0.406189 Z: 9.800552 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.457321 .y:-0.408417 .z:9.840500
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  360): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  967): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  967): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  967): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  967): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  967): proximitySensorChanged  positive = true
I/KnockOnPowerController(  967): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.456345 Y: -0.399979 Z: 9.776001 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456345 .y:-0.399979 .z:9.776001
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.459503 Y: -0.399857 Z: 9.793060 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459503 .y:-0.399857 .z:9.793060
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.465958 Y: -0.410599 Z: 9.800125 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465958 .y:-0.410599 .z:9.800125
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.462372 Y: -0.411301 Z: 9.797623 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462372 .y:-0.411301 .z:9.797623
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43b5a108)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
I/WindowManager(  967): No lock screen! windowToken=null
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.448975 Y: -0.408264 Z: 9.788254 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448975 .y:-0.408264 .z:9.788254
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb7df3450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/WifiStateMachine(  967): handleScreenStateChanged: true
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131127
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  967): handleMessage: X
,D/NativeNfcBrcmPowerMode( 1468): setPowerMode; state=4
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=132097
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2037): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2037): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4343c050 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3718): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WeatherAncestor( 1851): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:14:24
,I/SlideAside( 3718): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/UpdateThreadPoolManager( 1851): 2 : This is isUpdating : false
D/WeatherAncestor( 1851): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:14:24
D/WeatherService( 1851): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1851): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/WeatherService( 1851): 2 : shouldTimeTickRegistered : false
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
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255,
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.471970 Y: -0.421432 Z: 9.796585 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471970 .y:-0.421432 .z:9.796585
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255,
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2,
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255,
,D/qdlights( 1155): set_light_notifications: 2,ff00f9f9,10,0,2,
,D/qdlights( 1155): [Current] = 255, R = 0, G = 249, B = 249
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 243, B = 243
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1155): set_light_notifications: 2,ff00eded,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1155): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 231, B = 231
,D/dalvikvm( 1155): GC_CONCURRENT freed 2882K, 11% free 25445K/28504K, paused 1ms+1ms, total 15ms
,D/qdlights( 1155): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 225, B = 225
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.470825 Y: -0.411331 Z: 9.796432 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470825 .y:-0.411331 .z:9.796432
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/qdlights( 1155): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1155): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 390ms
,D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453032865243, nextTick: 34790, mDrawingTime: 0
D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453032865260, nextTick: 34773, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1468): setPowerMode; state=4
D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
,D/WeatherService( 1851): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:14:25
,D/WeatherService( 1851): 2 : ACTION screen on
,D/WeatherService( 1851): 2 : shouldTimeTickRegistered : false
D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,D/WeatherService( 1851): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:14:25
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1444): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1444): Emergency Service
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1444): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1444): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1444): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : vzw_gfit, value : null
V/PhoneApp( 1444): Action intent recieved:android.intent.action.SCREEN_ON
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
,D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,I/LGImmersionVibrator(  967): Vibrator off
,D/WifiStateMachine(  967): handleScreenStateChanged: false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
,D/UsbSettings( 2583): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{42d06f60 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  967): CMD_SCREEN_OFF 
,D/WifiController(  967): shouldWifiStayAwake TRUE
D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd  len = 0, 0
E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
D/WifiNative-wlan0(  967):    returned true
V/UsbSettings( 2583): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
D/WifiStateMachine(  967): handleMessage: X
D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
V/UsbSettings( 2583): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2583): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1155): clear
E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,D/NativeNfcBrcmPowerMode( 1468): setPowerMode; state=2
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{42d06f60 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331ef70 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1482): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
D/WeatherService( 1851): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:14:25
,D/WeatherService( 1851): 2 : ACTION screen off
,D/WeatherService( 1851): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:14:25
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
,E/Parcel  (  391): Reading a NULL string not supported here.
,D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1444): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1444): Emergency Service
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1444): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/PhoneApp( 1444): Action intent recieved:android.intent.action.SCREEN_OFF
,V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1444): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1444): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : vzw_gfit, value : null
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/BrcmNfcJni( 1468): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1468): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1456): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/NfcService( 1468): NFC-C OFF
,D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
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
,D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  360): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1444): getIsInUseVoLTE : false
,D/PhoneApp( 1444): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1554): Vacuum at: now=1453032873987 tag=VacuumService
,I/GoogleURLConnFactory( 1554): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1554): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1554): GC_CONCURRENT freed 1786K, 28% free 18035K/24832K, paused 4ms+3ms, total 35ms
,W/Uploader( 1554):  no longer exists, so no auth token.
,W/Uploader( 1554): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453032883125816773; DSPS: 5270914; Offset: 1453032722270286988
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453032900039, nextTick: 59984, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453032900049, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453032903127816870; DSPS: 5926339; Offset: 1453032722270303443
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453032923129772904; DSPS: 6581763; Offset: 1453032722270306352,
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453032943131429667; DSPS: 7237178; Offset: 1453032722270284648
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1456): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1456): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1456): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/OtgUmsTangibleController( 1456): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453032960037, nextTick: 59981, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453032960048, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453032963133357263; DSPS: 7892601; Offset: 1453032722270289637
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453032983134803402; DSPS: 8548008; Offset: 1453032722270301449
,I/jxcore-log( 4676): --= Surplus to requirements =--
I/jxcore-log( 4676): 
,I/jxcore-log( 4676): ****TEST TOOK:  ms ****
I/jxcore-log( 4676): 
,I/jxcore-log( 4676): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4676): 
,D/AndroidRuntime( 5432): 
D/AndroidRuntime( 5432): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5432): CheckJNI is OFF
,D/dalvikvm( 5432): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5432): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 5432): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5432): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5432): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5432): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5432): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5432): failed to load memtrack module: -2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 5432): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  967): Killing 4676:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
,I/MDM     (  967):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  967):   Force finishing activity ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3 f}
,D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  967): moveHomeStack:
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d5ad08 stackId=0, 1 tasks}
,V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d5ad08 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{43cbbfa0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/WindowState(  967): WIN DEATH: Window{43160a38 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  967): Client connection lost with reason: 4
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d5ad08 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,I/[LGHome]EVENT( 1482): [Launcher.java:4947:onStart()]onStart
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/PackageSettings(  967): Skipping PackageSetting{42dae920 com.example.hello/10312} due to missing metadata
,I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d5ad08 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1482): [Launcher.java:717:onResume()]onResume
,D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1482): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1482): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1444): getIsInUseVoLTE : false
,E/SlideAside( 3718): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/SlideAside( 3718): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
,D/AppUp4:Utils( 4013): [getPackageName] uri : package:com.test.thalitest
,D/AppUp4  ( 4013): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 4013):  isExcludedPackage  packagename = com.test.thalitest
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/AppUp4  ( 4013):  isExcludedPackage TRUE : com.test.thalitest
,I/PackageManager(  967):   Scheme: "sms"
I/ActivityManager(  967): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5457 uid=10090 gids={50090}
,W/System.err( 2638): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/GeofencerStateMachine( 1419): Ignoring removeGeofence because network location is disabled.
,W/System.err( 2638): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2638): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2638): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
,W/System.err( 2638): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2638): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2638): 	at android.os.Looper.loop(Looper.java:136)
,W/System.err( 2638): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2638): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2638): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 2638): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2638): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2638): 	at dalvik.system.NativeStart.main(Native Method)
,D/dalvikvm( 2654): GC_EXPLICIT freed 4389K, 27% free 18155K/24832K, paused 3ms+26ms, total 65ms
,I/[LGHome]LGActivityUtil( 1482): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1482): [Launcher.java:868:onResume()]onResume end
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  967): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5469 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/[LGHome]EVENT( 1482): [Launcher.java:894:onPause()]onPause
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5457): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5457): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5457): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1482): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1482): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1482): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,D/dalvikvm(  967): GC_EXPLICIT freed 3062K, 50% free 29994K/59620K, paused 6ms+14ms, total 166ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 61ms
,D/HyLog   ( 5469): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5469): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5469): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
,I/LockScreenSettings( 5457): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
,I/[LGHome]EVENT( 1482): [Launcher.java:4955:onStop()]onStop
D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1141): createShortcutInfo...
,I/[LGHome]EVENT( 1482): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/Binder  ( 1313): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1313): java.lang.NullPointerException
W/Binder  ( 1313): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1313): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1313): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1313): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  967): IME STATUS OFF
W/InputMethodManagerService(  967): Got RemoteException sending setActive(false) notification to pid 4676 uid 10304
,D/administrator(  967): Handling package changes for user 0
D/[BNRAppListMgrReceiver]( 5469): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1141): createShortcutInfo...
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1141): createShortcutInfo...
,D/KeyguardModel( 1141): handleShortcutListChanged...
,I/ActivityManager(  967): Killing 4596:com.lge.email/u0a24 (adj 15): empty #17
E/JavaBinder(  967): !!! FAILED BINDER TRANSACTION !!!
,I/Process (  967): Sending signal. PID: 4596 SIG: 9
,D/VoicemailCleanupService( 1798): Cleaning up data for package: com.test.thalitest
W/BroadcastQueue(  967): Catch TransactionTooLargeException and so be it shredded ComponentInfo{com.lge.email/.receiver.PackageChangeReceiver}
W/BroadcastQueue(  967): Process Killing Confirmation (pid:4596)
W/BroadcastQueue(  967): Exception when sending broadcast to ComponentInfo{com.lge.email/com.lge.email.receiver.PackageChangeReceiver}
W/BroadcastQueue(  967): android.os.TransactionTooLargeException
W/BroadcastQueue(  967): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  967): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:814)
W/BroadcastQueue(  967): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:239)
W/BroadcastQueue(  967): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:895)
W/BroadcastQueue(  967): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:14216)
W/BroadcastQueue(  967): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:387)
W/BroadcastQueue(  967): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2168)
W/BroadcastQueue(  967): 	at android.os.Binder.execTransact(Binder.java:407)
W/BroadcastQueue(  967): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  967): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5491 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1141): createShortcutInfo...
,D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1141): createShortcutInfo...
I/ActivityManager(  967): Process com.lge.email (pid 4596) has died and restarted (pid 5491).
,V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
I/[LGHome]Launcher.Model( 1482): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
D/KeyguardModel( 1141): createShortcutInfo...
I/[LGHome]Launcher( 1482): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1141): createShortcutInfo...
,D/KeyguardModel( 1141): handleShortcutListChanged...
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{430f0958 u0 com.lge.launcher2/.Launcher t1} time:268117
D/HyLog   ( 5491): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5491): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5491): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): Killing 4814:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d5ad08 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
I/InteractionManagerConfigurator(  967): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  967): com.test.thalitest isn't inclued in dragdropPackageList
D/BackupManagerService(  967): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  967): removePackageParticipantsLocked: uid=10304 #1
,I/LGEmail ( 5491): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/dalvikvm(  967): GC_EXPLICIT freed 639K, 50% free 29899K/59620K, paused 3ms+14ms, total 231ms
D/dalvikvm( 1482): GC_CONCURRENT freed 5662K, 9% free 60778K/66668K, paused 2ms+5ms, total 36ms
,D/dalvikvm( 1482): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/AndroidRuntime( 5432): Shutting down VM
,D/dalvikvm( 5432): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
,D/LGEmail ( 5491): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,D/dalvikvm( 1141): GC_CONCURRENT freed 7716K, 11% free 70582K/78484K, paused 4ms+5ms, total 61ms
,D/dalvikvm( 1141): WAIT_FOR_CONCURRENT_GC blocked 50ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1482): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,W/BaseRuntimeLoader( 5491): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5491): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/[LGHome]EVENT( 1482): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/BaseRuntimeLoader( 5491): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5491): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1482): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1482): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1482): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,E/[LGHome]NumberBadge( 1482): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher.Model( 1482): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1482): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1482): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/PackageChangeReceiver( 5491): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1482): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1482): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1482): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]Launcher( 1482): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/PackageIntentReceiver( 2583): Not supported Hotkey customization function 
,D/HideNavigationAppsReceiver( 2583): Receive package name : com.test.thalitest
,D/HideNavigationAppsReceiver( 2583): Delete mPackageMame : com.test.thalitest
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/IcingCorporaProvider( 2654): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
I/ActivityManager(  967): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5514 uid=10073 gids={50073, 3003, 1028, 1015}
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,D/HyLog   ( 5514): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5514): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5514): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]Launcher( 1482): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/IcingCorporaProvider( 2654): UpdateCorporaTask done [took 74 ms] updated apps [took 74 ms] 
I/[LGHome]Launcher( 1482): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1482): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1482): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1482): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]Launcher( 1482): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1482): Timeline: Activity_idle id: android.os.BinderProxy@428cefd0 time:268439

```
