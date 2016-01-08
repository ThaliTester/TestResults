#### Test 55431344e5dd625_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4710): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  966): Killing 4160:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 1 tasks}
I/ConfigFetchService( 1971): fetch service done; releasing wakelock
I/ConfigFetchService( 1971): stopping self
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431068f8 u0 com.android.settings/.UsbSettings t2}
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1971): Module APK com.google.android.play.games already loaded
D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2022): nl80211: survey data missing!
D/WifiStateMachine(  966): handleMessage: X
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
D/dalvikvm( 1971): GC_CONCURRENT freed 1392K, 22% free 19510K/24832K, paused 5ms+3ms, total 51ms
D/AndroidRuntime( 4756): 
D/AndroidRuntime( 4756): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4756): CheckJNI is OFF
D/dalvikvm( 4756): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4756): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4756): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4756): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4756): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1971): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/dalvikvm( 4756): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/Icing   ( 1971): Loaded CLD2 Version V2.0 - 20141016
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Icing   ( 1971): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4756): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4756): failed to load memtrack module: -2
D/AndroidRuntime( 4756): Calling main entry com.android.commands.am.Am
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4756
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
D/PermissionCache(  273): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (144 us)
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{431068f8 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  966): resumeTopActivityLocked: Pausing null
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  966): startService SlideAside
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  966): setFocusedStack: mFocusedStack=ActivityStack{4324f140 stackId=1, 2 tasks}
D/UsbSettingsControl( 2613): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2613): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{431068f8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/AndroidRuntime( 4756): Shutting down VM
I/SlideAside( 3841): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4756): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 3ms
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{431068f8 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Restarting ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  966): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4771 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3841): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3841): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4771): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4771): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4771): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/WebViewChromium( 4771): Binding Chromium to the background looper Looper (main, tid 1) {428796b0}
I/chromium( 4771): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4771): Initializing chromium process, renderers=0
W/chromium( 4771): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4771): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4771): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4771): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4771): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4771): Remote Branch: 
I/Adreno-EGL( 4771): Local Patches: 
I/Adreno-EGL( 4771): Reconstruct Branch: 
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.420898 Y: -0.413788 Z: 9.835785 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.420898 .y:-0.413788 .z:9.835785
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
I/dalvikvm( 4771): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4771): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4771): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4771): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4771): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4771): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4771): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4771): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4771): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4771): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4771): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4771): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4771): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4771): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4771): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4771): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4771): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4771): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4771): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4771): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.430374 Y: -0.412415 Z: 9.807693 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.430374 .y:-0.412415 .z:9.807693
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/BaseRuntimeLoader( 4771): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4771): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4771): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4771): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4771): Enabling debug mode 0
W/AwContents( 4771): nativeOnDraw failed; clearing to background color.
W/AwContents( 4771): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  966): IME STATUS OFF
I/ActivityManager( 4771): Timeline: Activity_idle id: android.os.BinderProxy@4287af70 time:112752
I/ActivityManager(  966): Displayed com.test.thalitest/.MainActivity: +534ms
D/JsMessageQueue( 4771): Set native->JS mode to OnlineEventsBridgeMode
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
D/dalvikvm( 4771): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4287f8d0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3} time:112991
D/dalvikvm( 4771): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4287f8d0
D/jxcore_app_log( 4771): JniHelper::setJavaVM(0x41745838), pthread_self() = 1639309240
D/JX-Cordova( 4771): jxcore cordova android initializing
D/UsbSettings( 2613): [AUTORUN] onStop()
D/ActivityManager(  966): no-history finish of ActivityRecord{431068f8 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  966): Finishing activity token=Token{4322a190 ActivityRecord{431068f8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{431068f8 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{431068f8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
I/chromium( 4771): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{431068f8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/chromium( 4771): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4771): GC_CONCURRENT freed 2767K, 12% free 21885K/24832K, paused 2ms+1ms, total 42ms
,D/dalvikvm( 4771): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 4771): GC_FOR_ALLOC freed 133K, 12% free 21863K/24832K, paused 23ms, total 23ms
,D/dalvikvm( 4771): GC_FOR_ALLOC freed 126K, 12% free 21883K/24832K, paused 23ms, total 24ms
,I/dalvikvm-heap( 4771): Grow heap (frag case) to 23.636MB for 96598-byte allocation
,D/dalvikvm( 4771): GC_FOR_ALLOC freed 180K, 13% free 21918K/24928K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4771): Grow heap (frag case) to 23.716MB for 144892-byte allocation
,D/dalvikvm( 4771): GC_FOR_ALLOC freed 254K, 13% free 21966K/25072K, paused 24ms, total 24ms
I/dalvikvm-heap( 4771): Grow heap (frag case) to 23.832MB for 217334-byte allocation
,D/dalvikvm( 4771): GC_FOR_ALLOC freed 370K, 13% free 22040K/25288K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4771): Grow heap (frag case) to 24.008MB for 325996-byte allocation
,D/dalvikvm( 4771): GC_FOR_ALLOC freed 570K, 14% free 22162K/25608K, paused 22ms, total 23ms
I/dalvikvm-heap( 4771): Grow heap (frag case) to 24.283MB for 488990-byte allocation
D/dalvikvm( 4771): GC_FOR_ALLOC freed 870K, 15% free 22339K/26088K, paused 22ms, total 23ms
D/dalvikvm( 4771): GC_FOR_ALLOC freed 1288K, 14% free 22596K/26088K, paused 25ms, total 26ms
I/dalvikvm-heap( 4771): Grow heap (frag case) to 25.289MB for 1100216-byte allocation
D/dalvikvm( 4771): GC_CONCURRENT freed 1728K, 16% free 22993K/27164K, paused 2ms+3ms, total 34ms
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  966): battery changed pluggedType: 2
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/dalvikvm( 4771): GC_FOR_ALLOC freed 311K, 16% free 22937K/27164K, paused 26ms, total 26ms
I/dalvikvm-heap( 4771): Grow heap (frag case) to 26.147MB for 1650320-byte allocation
D/dalvikvm( 4771): GC_CONCURRENT freed 1938K, 19% free 23576K/28776K, paused 2ms+5ms, total 49ms
D/dalvikvm( 4771): GC_FOR_ALLOC freed 1128K, 19% free 23539K/28776K, paused 26ms, total 26ms
I/dalvikvm-heap( 4771): Grow heap (frag case) to 27.522MB for 2475476-byte allocation
D/dalvikvm( 4771): GC_CONCURRENT freed 1865K, 23% free 24315K/31196K, paused 1ms+2ms, total 43ms
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/dalvikvm( 4771): GC_CONCURRENT freed 2419K, 22% free 24514K/31196K, paused 1ms+4ms, total 47ms
,D/dalvikvm( 4771): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4771): GC_FOR_ALLOC freed 636K, 23% free 24276K/31196K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4771): Grow heap (frag case) to 29.422MB for 3713210-byte allocation
,D/dalvikvm( 4771): GC_CONCURRENT freed 2701K, 27% free 25488K/34824K, paused 2ms+3ms, total 30ms
,D/dalvikvm( 4771): GC_FOR_ALLOC freed 593K, 27% free 25503K/34824K, paused 24ms, total 24ms
,W/jxcore-log( 4771): Initializing JXcore engine
,W/jxcore-log( 4771): JXcore engine is ready
,D/dalvikvm( 4771): GC_CONCURRENT freed 323K, 20% free 28173K/34824K, paused 1ms+2ms, total 34ms
,D/dalvikvm( 4771): WAIT_FOR_CONCURRENT_GC blocked 32ms
,W/jxcore-log( 4771): Starting JXcore engine
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,W/jxcore-log( 4771): Platform android
W/jxcore-log( 4771): 
W/jxcore-log( 4771): Process ARCH arm
W/jxcore-log( 4771): 
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/jxcore-log( 4771): JXcore Cordova bridge is ready!
I/jxcore-log( 4771): 
,W/jxcore-log( 4771): JXcore engine is started
,I/chromium( 4771): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4771): Skipped 153 frames!  The application may be doing too much work on its main thread.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4710): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1559): onDestroy
,I/jxcore-log( 4771): Toggling radios to true
I/jxcore-log( 4771): 
D/BluetoothManagerService(  966): Message: 20
,D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d53bd8:true
,D/BluetoothAdapter( 4771): enable(): BT is already enabled..!
D/WifiStateMachine(  966): handleMessage: E msg.what=131145
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doBoolean: DISCONNECT
,I/jxcore-log( 4771): Radios toggled
I/jxcore-log( 4771): 
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2022): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2022): wlan0: Cancelling scan request
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2022): TDLS: Tear down peers
,D/wpa_supplicant( 2022): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  966): New client listening to asynchronous messages
D/WifiService(  966): setWifiEnabled: true pid=4771, uid=10304
E/WifiService(  966): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  966): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  966): disconnect pid=4771, uid=10304
,D/WifiService(  966): reconnect pid=4771, uid=10304
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4771): Received device characteristics:
I/jxcore-log( 4771): Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4771): Bluetooth name: Thali Test's G2
I/jxcore-log( 4771): Device name: LGE-LG-D802
I/jxcore-log( 4771): 
I/jxcore-log( 4771): Perf Test app loaded loaded
I/jxcore-log( 4771): 
I/jxcore-log( 4771): check test folder
I/jxcore-log( 4771): 
I/jxcore-log( 4771): found test : ./testFindPeers.js
I/jxcore-log( 4771): 
D/wpa_supplicant( 2022): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2022): wlan0: Deauthentication notification
D/wpa_supplicant( 2022): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2022): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2022): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2022): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2022): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2022): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7759d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2022): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2022): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2022): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  966): invokeExitMethods: ConnectedState
W/Settings(  966): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  966): invokeExitMethods: L2ConnectedState
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  966): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131146
D/WifiStateMachine(  966): processMsg: DisconnectingState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiNative-wlan0(  966): doBoolean: RECONNECT
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2022): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2022): Fast associate: Old scan results
D/wpa_supplicant( 2022): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2022): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2022): wlan0: nl80211: scan request
D/wpa_supplicant( 2022): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2022): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2022): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147460
D/WifiStateMachine(  966): processMsg: DisconnectingState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): Network connection lost
D/WifiStateMachine(  966): Stopping DHCP and clearing IP
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  966): doBoolean: SET ps 1
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  966):    returned true
D/WifiP2pService(  966): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  966): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  966): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  270): Clearing all IP addresses on wlan0
D/WifiStateMachine(  966): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  966): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  966): transitionTo: destState=DisconnectedState
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
D/QCNEA   (  402): |CAC| readCallback: read len:492, ret:0, errno:0
,D/QCNEA   (  402): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  402): |CAC| updateNetCfgInfo
V/QCNEA   (  402): |CAC| *********************************************
V/QCNEA   (  402): |CAC|                   Netconfig               
V/QCNEA   (  402): |CAC| *********************************************
V/QCNEA   (  402): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  402): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  402): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  402): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  402): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  402): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  402): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  402): |CAC| *********************************************
D/QCNEA   (  402): |CAC| Received bssid= 
D/QCNEA   (  402): |CAC| net type = 3
V/QCNEA   (  402): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  402): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  402): |CAC| 	ssid           =NG700
V/QCNEA   (  402): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  402): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  402): |CAC| *********************************************
D/QCNEA   (  402): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
,D/WifiHS20(  966): hidePasspointNotification off =false
D/QCNEA   (  402): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  402): |CAC| dispatchNetCfg: updating:0xb79018dc
D/QCNEA   (  402): |CAC| readCallback: read len:0, ret:-1, errno:11
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  966): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  966): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  966): invokeEnterMethods: DisconnectedState
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
,D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131213
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131213
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
I/jxcore-log( 4771): found test : ./testSendData.js
I/jxcore-log( 4771): 
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/NetworkManagementService(  966): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/QcConnectivityService(  966): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  966): Attempting to switch to mobile
D/QcConnectivityService(  966): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  966): handleConnectivityChange: preConnState=1 connState=2
,I/ActivityManager(  966): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4856 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/NetworkManagementService(  966): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  966): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  270): RouteController
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,D/HyLog   ( 4856): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4856): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4856): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  270): RouteController
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PCSuite ( 4856): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
V/        (  270): RouteController
V/        (  270): RouteController
D/PCSuite ( 4856): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4856): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/        (  270): RouteController
W/NetworkManagementService(  966): route cmd failed: 
W/NetworkManagementService(  966): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  966): '
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  966): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  966): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  966): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  966): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  966): android_net_utils_resetConnections in env=0x6180c8a8 clazz=0x6d400001 iface=wlan0 mask=0x3
D/QcConnectivityService(  966): resetConnections(wlan0, 3)
I/ActivityManager(  966): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4890 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  966): Killing 4266:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
,V/NativeCrypto( 1559): Read error: ssl=0x63ae6ba0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1559): SSL shutdown failed: ssl=0x63ae6ba0: I/O error during system call, Broken pipe
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4890): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4890): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4890): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  966): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/QRemote ( 4890): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  966): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
,D/QRemote ( 4890): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 4890): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4890): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4890): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4890): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4890): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,I/chromium( 4771): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/QRemote ( 4890): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4890): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  966): Killing 2146:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  966): StoppedState
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiStateMachine(  966): processMsg: DefaultState
,D/WifiStateMachine(  966): handleMessage: X
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  966): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4122): onReceive
,D/AppUp4:CustFacade( 4122): Context : android.app.ReceiverRestrictedContext@428983a0
,D/AppUp4:CustFacade( 4122): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4122): isOpenOperator : true
,D/AppUp4:CustFacade( 4122): isPhone : true
,I/LicenseContentProvider( 3008): start selecting data
,D/SIMObserver( 3008): simInfo1
,I/AppUp4:EulaManager( 4122): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4122): begin check event
,I/AppUp4:CustModeStarterReceiver( 4122): Event For GoodConnectivity
,D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2022): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2022): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2022): nl80211: Received scan results (14 BSSes)
D/wpa_supplicant( 2022): nl80211: Survey data missing
D/wpa_supplicant( 2022): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 7 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 8 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 9 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 10 BSSID 8c:04:ff:b9:af:25 SSID 'SALVADOR'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 11 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 12 BSSID 64:7c:34:b0:03:6e SSID 'UPC4688432'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 13 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): BSS: last_scan_res_used=14/32 last_scan_full=0
D/wpa_supplicant( 2022): wlan0: New scan results available
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2022): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2022): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2022): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2022): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2022): WPS: AP 44:e9:dd:10:c0:ac type 0 added
D/wpa_supplicant( 2022): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2022): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 2022): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[4] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=,0
D/wpa_supplicant( 2022): WPS: AP[5] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[6] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[7] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2022): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2022): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2022): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2022): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2022): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2022): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb775b5a8  current_ssid=0x0
D/wpa_supplicant( 2022): scard is not null..
D/wpa_supplicant( 2022): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2022): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2022): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2022): wlan0: Cancelling scan request
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2022): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2022): RSN: PMKSA cache search - network_ctx=0xb775b5a8 try_opportunistic=0
D/wpa_supplicant( 2022): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2022): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2022): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2022): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2022): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2022): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2022): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2022): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2022): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2022): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2022): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2022): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2022): nl80211: Unsubscribe mgmt frames handle 0xb775a590 (mode change)
D/wpa_supplicant( 2022): nl80211: Subscribe to mgmt frames with non-AP handle 0xb775a590
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb775a590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb775a590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb775a590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb775a590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb775a590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb775a590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb775a590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb775a590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb775a590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb775a590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2022): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2022):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022):   * freq=2412
D/wpa_supplicant( 2022):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2022):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022):   * Auth Type 0
D/wpa_supplicant( 2022):   * WPA Versions 0x2
D/wpa_supplicant( 2022): nl80211: Connect request send successfully
D/wpa_supplicant( 2022): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
,I/ActivityManager(  966): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4923 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 00:37:b7:9d:3e:73]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 44:e9:dd:10:c0:ac]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 06:7c:34:38:27:cc]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 8c:04:ff:b9:af:25]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 64:7c:34:38:27:cc]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 64:7c:34:b0:03:6e]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 00:26:f2:18:08:c8]
D/WifiStateMachine(  966): handleMessage: E msg.what=147461
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiMonitor(  966): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  966): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2022): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
W/WifiMonitor(  966): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2022): nl80211: Connect event
D/wpa_supplicant( 2022): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2022): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2022): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2022): wlan0: Association info event
D/wpa_supplicant( 2022): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2022): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2022): wlan0: freq=2412 MHz
D/wpa_supplicant( 2022): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2022): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2022): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2022): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): scard is not null..
D/wpa_supplicant( 2022): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2022): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2022): TDLS: Remove peers on association
D/wpa_supplicant( 2022): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2022): EAPOL: enable timer tick
D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2022): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2022): wlan0: Cancelling scan request
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  966): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  966): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 46 7c 07 de 2d 46 a0 5c 5f 63 3f f1 3f ce 43 ...
D/wpa_supplicant( 2022): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2022): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2022): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2022): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2022): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2022):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2022):   key_nonce - hexdump(len=32): 46 7c 07 de 2d 46 a0 5c 5f 63 3f f1 3f ce 43 f0 c3 26 0e 1b e8 72 e7 d2 68 df 2b 7e e0 d5 13 c3
D/wpa_supplicant( 2022):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 46 7c 07 de 2d 46 a0 5c 5f 63 3f f1 3f ce 43 ...
D/wpa_supplicant( 2022): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2022): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2022): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2022): WPA: Renewed SNonce - hexdump(len=32): ce af 13 18 d7 a8 d5 98 98 91 68 7c 96 4e 82 d5 d7 44 fa b3 6f 01 e8 3e 10 b6 80 c6 5b 3b 4e 7d
D/wpa_supplicant( 2022): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): WPA: Nonce1 - hexdump(len=32): ce af 13 18 d7 a8 d5 98 98 91 68 7c 96 4e 82 d5 d7 44 fa b3 6f 01 e8 3e 10 b6 80 c6 5b 3b 4e 7d
D/wpa_supplicant( 2022): WPA: Nonce2 - hexdump(len=32): 46 7c 07 de 2d 46 a0 5c 5f 63 3f f1 3f ce 43 f0 c3 26 0e 1b e8 72 e7 d2 68 df 2b 7e e0 d5 13 c3
D/wpa_supplicant( 2022): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2022): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2022): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2022): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2022): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2022): WPA: Derived Key MIC - hexdump(len=16): b1 33 1f 40 99 8d 9f 2a 05 41 3a 7a ff 2e 80 23
,D/wpa_supplicant( 2022): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 ce af 13 18 d7 a8 d5 98 98 91 68 7c 96 4e 82 ...
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2022): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 46 7c 07 de 2d 46 a0 5c 5f 63 3f f1 3f ce 43 ...
D/wpa_supplicant( 2022): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2022): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2022): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2022): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2022):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2022):   key_nonce - hexdump(len=32): 46 7c 07 de 2d 46 a0 5c 5f 63 3f f1 3f ce 43 f0 c3 26 0e 1b e8 72 e7 d2 68 df 2b 7e e0 d5 13 c3
D/wpa_supplicant( 2022):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_rsc - hexdump(len=8): a5 a8 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_mic - hexdump(len=16): 95 a7 0d 5a bf 8d 95 60 51 93 a1 ef 84 65 c8 b1
D/wpa_supplicant( 2022): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 46 7c 07 de 2d 46 a0 5c 5f 63 3f f1 3f ce 43 ...
D/wpa_supplicant( 2022): RSN: encrypted key data - hexdump(len=56): 4f 81 00 6f 6b 77 b2 25 bc cd b6 67 ee 77 ff 60 e0 84 1b b6 47 08 96 0c ca c5 21 19 df b2 56 fa ...
D/wpa_supplicant( 2022): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2022): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2022): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2022): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 13 1c ...
D/wpa_supplicant( 2022): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2022): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2022): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2022): WPA: Derived Key MIC - hexdump(len=16): d7 b9 d9 c3 47 39 4e 1c 47 b2 63 4e f3 d8 a1 87
D/wpa_supplicant( 2022): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2022): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb775ac54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2022):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2022): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2022): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2022): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2022): WPA: RSC - hexdump(len=6): a5 a8 00 00 00 00
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6fad03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2022):    broadcast key
I/wpa_supplicant( 2022): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2022): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2022): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2022): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2022): EAPOL authentication completed successfully
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  966): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  966): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=147459
,D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): Network connection established
,D/WifiNative-wlan0(  966): doString: STATUS
,D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2022): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  966):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  966): ssid=NG700
D/WifiNative-wlan0(  966): id=0
D/WifiNative-wlan0(  966): mode=station
D/WifiNative-wlan0(  966): pairwise_cipher=CCMP
D/WifiNative-wlan0(  966): group_cipher=CCMP
D/WifiNative-wlan0(  966): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  966): wpa_state=COMPLETED
D/WifiNative-wlan0(  966): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  966): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  966): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  966): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  966): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
,E/Parcel  (  402): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  966): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  966): invokeExitMethods: DisconnectedState
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  966): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  966): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  966): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-63ms what=147462 obj=android.net.wifi.StateChangeResult@444495c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/DhcpStateMachine(  966): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  966): WaitBeforeStartState
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-36ms what=147462 obj=android.net.wifi.StateChangeResult@44fa9490 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147459
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-35ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-4ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2022): nl80211: survey data missing!
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=196612
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-8ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/HyLog   ( 4923): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4923): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4923): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4923): DownloadService onCreate
,D/EAS     ( 4687): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 4923): in removeSpuriousFiles
,D/EAS     ( 4687): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  966): doBoolean: SET ps 0
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  966):    returned true
,D/WifiNative-wlan0(  966): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  966):    returned null
E/WifiStateMachine(  966): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  966): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  966):    returned null
,E/WifiStateMachine(  966): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DownloadManager( 4923): DownloadService onStartCommand
D/DhcpStateMachine(  966): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  966): DHCP Start wake lock is acquired.
V/DhcpStateMachine(  966): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  966): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/DownloadManager( 4923): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4923): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/WifiP2pService(  966): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433461d0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  966): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433461d0 target=com.android.internal.util.StateMachine$SmHandler }
V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428c2188 on behalf of 4923
D/CommandListener(  270): Setting iface cfg
V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428c26b0 on behalf of 4923
D/CommandListener(  270): Trying to bring up wlan0
I/DownloadManager( 4923): in trimDatabase
V/DownloadManager( 4923): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/WifiStateMachine(  966): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428c5a40 on behalf of 4923
V/LgDhcpStateMachineHelper(  966): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  966): handleMessage: X
D/eas_req ( 4687): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/WifiStateMachine(  966): handleMessage: E msg.what=131212
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=196613
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  966): doBoolean: SET ps 1
V/DownloadManager( 4923): DownloadService onDestroy
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  966):    returned true
,D/WifiStateMachine(  966): DHCP successful
D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  966): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  966): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  966): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  966): VerifyingLinkState enter
,D/WifiStateMachine(  966): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  966): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=135190
D/WifiStateMachine(  966): processMsg: VerifyingLinkState
D/WifiStateMachine(  966): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  966): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  966): invokeExitMethods: VerifyingLinkState
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  966): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  966): CaptivePortalCheckState enter
,D/WifiStateMachine(  966): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,E/Parcel  (  402): Reading a NULL string not supported here.
D/WifiP2pService(  966): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  966): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  966): 
W/WifiStateTracker(  966):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  966):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/LgeMiscReceiver( 4441): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4441): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4441): networkInfo.isConnected() = false
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
W/linker  ( 4687): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4687): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4687): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4687): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4687): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4687): register_HtmlEditor, Success
,D/HtmlEditor( 4687): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
,D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
D/HtmlEditor( 4687): register_HtmlEditorTimer, Success
D/HtmlEditor( 4687): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4687): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4687): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4687): register_HtmlEditorFont, Success
D/HtmlEditor( 4687): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4687): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4687): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4687): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4687): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4687): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4687): JNI_OnLoad Success
I/HubEmail( 4687): JNI_OnLoad()
I/HubEmail( 4687): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4687): registerNatives()
I/HubEmail( 4687): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4687): registerNativeMethods()
,I/HubEmail( 4687): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,D/WifiStateMachine(  966): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,I/ActivityManager(  966): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4964 uid=10052 gids={50052, 3003}
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
W/Settings( 4687): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
E/Parcel  (  402): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  966): handleMessage: E msg.what=131092
D/WifiStateMachine(  966): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  966): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/QcConnectivityService(  966): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  966): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  966): transitionTo: destState=ConnectedState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  966): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  966): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  966): handleMessage: X
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
E/Parcel  (  402): Reading a NULL string not supported here.
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/ActivityThread(  966): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  966): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  966): handleConnectivityChange: preConnState=2 connState=1
I/ActivityManager(  966): Killing 4004:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  270): RouteController
D/HyLog   ( 4964): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4964): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4964): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  270): RouteController
V/        (  270): RouteController
,V/        (  270): RouteController
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3}
V/        (  270): RouteController
V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
V/        (  270): RouteController
V/LGRssiData( 4964): [loadRssi] File not exist 
V/LGRssiData( 4964): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4964): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4964): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4964): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4964): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4964): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/        (  270): RouteController
D/MobileConnectivityChangeReceiver( 4964): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/        (  270): RouteController
D/MobileConnectivityChangeReceiver( 4964): onReceive CONNECTIVITY_CHANGE networkType=1
,V/TelephonyAutoProfiling( 4964): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4964): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  270): RouteController
I/ActivityManager(  966): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4993 uid=10063 gids={50063, 3003, 1028, 1015}
,D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  402): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  402): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  402): |CAC| updateNetCfgInfo
V/QCNEA   (  402): |CAC| *********************************************
V/QCNEA   (  402): |CAC|                   Netconfig               
V/QCNEA   (  402): |CAC| *********************************************
V/QCNEA   (  402): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  402): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  402): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  402): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  402): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  402): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  402): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  402): |CAC| *********************************************
D/QCNEA   (  402): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  402): |CAC| net type = 1
V/QCNEA   (  402): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  402): |CAC| Received ssid= NG700
V/QCNEA   (  402): |CAC| 	ssid           =NG700
V/QCNEA   (  402): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  402): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  402): |CAC| *********************************************
D/QCNEA   (  402): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  402): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  402): |CAC| dispatchNetCfg: updating:0xb79018dc
D/QCNEA   (  402): |CAC| readCallback: read len:0, ret:-1, errno:11
D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,E/PhoneMonitor( 4964): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4964): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  966): Killing 4422:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3}
,D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 4993): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4993): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4993): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1971): Checking schedule, now: 1452238042629 next: 1452237983704
,I/CheckinService( 1971): active receiver: enabled
,I/CheckinService( 1971): Preparing to send checkin request
,I/EventLogService( 1971): Accumulating logs since 1452237951132
,D/DhcpStateMachine(  966): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  966): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  966): GC_EXPLICIT freed 23489K, 49% free 29736K/57844K, paused 3ms+8ms, total 143ms
,I/ActivityManager(  966): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5017 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  966): Killing 4612:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
,D/HyLog   ( 5017): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5017): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5017): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3}
,I/CheckinRequestBuilder( 1971): Checkin reason type: 8 attempt count: 1
,D/LGDMClient( 2889): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2889): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
E/ActivityThread( 1971): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  966): Killing 4643:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/LGDMClient( 2889): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2889): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2889): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2889): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager(  966): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5030 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3}
I/LGDMClient( 2889): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 5030): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5030): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5030): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5030): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  966): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5044 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  966): Killing 4671:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 5044): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5044): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5044): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 5044): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5044): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 5044): intf.getDisplayName() = lo
I/Wireless_Storage( 5044): intf.getDisplayName() = sit0
I/Wireless_Storage( 5044): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5044): intf.getDisplayName() = teql0
,I/Wireless_Storage( 5044): intf.getDisplayName() = wlan0
D/NFS     ( 5044): interface name:wlan0 name:wlan0
D/NFS     ( 5044): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5044): interface name:wlan0 name:wlan0
D/NFS     ( 5044): addr:192.168.1.145 broadcast:192.168.1.255
I/Wireless_Storage( 5044): CONNECT : WIFI_CONNECT
,E/ThermalEngine(  292): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/ActivityManager(  966): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5056 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  966): Killing 4317:com.android.contacts/u0a21 (adj 15): empty #17
,D/dalvikvm(  274): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
,D/HyLog   ( 5056): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5056): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5056): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,I/GLSUser ( 1559): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1559): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1559): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1559): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5056): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Auth    ( 1559): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x43093be0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1971): awaiting user notification for token
D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  966): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5075 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5075): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5075): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5075): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5075): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5075): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5075): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5075): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5075): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5075): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5075): install
,I/MultiDex( 5075): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5075): loading existing secondary dex files
,I/MultiDex( 5075): load found 3 secondary dex files
,I/MultiDex( 5075): install done
,D/dalvikvm( 5075): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5075): VFY: unable to resolve instance field 61
,D/dalvikvm( 5075): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5075): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5075): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5075): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5075): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5075): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5075): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 5075): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 5075): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5075): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4287f380
D/dalvikvm( 5075): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4287f380
,D/dalvikvm( 5075): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4287f380, skipping init
,D/dalvikvm( 5075): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4287f380
D/dalvikvm( 5075): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4287f380
,V/JNIHelp ( 5075): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 5056): Binding Chromium to the main looper Looper (main, tid 1) {42883388}
,I/chromium( 5056): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5056): Initializing chromium process, renderers=0
,W/chromium( 5056): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5056): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5056): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5056): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5056): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5056): Remote Branch: 
I/Adreno-EGL( 5056): Local Patches: 
I/Adreno-EGL( 5056): Reconstruct Branch: 
,D/dalvikvm( 5075): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4287f380
,D/dalvikvm( 5075): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4287f380
D/dalvikvm( 5075): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4287f380
,D/dalvikvm( 5075): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4287f380
,I/NSApplication( 5056): Starting up...
,I/ActivityManager(  966): Killing 4332:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4890): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4890): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4890): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4890): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4890): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4890): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4856): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4856): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4890): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4890): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4890): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4890): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 5075): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1559): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1559): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1559): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1971): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1874): callingUid 10006, callindPid: 1874
,E/MDM     ( 1422): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1971): Restart initialization of location
I/dalvikvm( 5075): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5075): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5075): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5075): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5075): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5075): VFY: replacing opcode 0x6e at 0x0201
,D/wpa_supplicant( 2022): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2022): EAPOL: disable timer tick
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d2d000
E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d2d000
,D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  276): PrepareKeyRequest: nonce=2131800817
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5075): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a35198
D/dalvikvm( 5075): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a35198
,D/dalvikvm( 5075): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a35198, skipping init
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  966): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  276): PrepareKeyRequest: nonce=2290469657
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 5075): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5120): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 5075): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5075): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 69ms
,I/Adreno-EGL( 5075): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5075): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5075): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5075): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5075): Remote Branch: 
I/Adreno-EGL( 5075): Local Patches: 
I/Adreno-EGL( 5075): Reconstruct Branch: 
,I/Adreno-EGL( 5075): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5075): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5075): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5075): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5075): Remote Branch: 
I/Adreno-EGL( 5075): Local Patches: 
I/Adreno-EGL( 5075): Reconstruct Branch: 
,D/WifiStateMachine(  966): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  966): handleMessage: E msg.what=131212
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
,D/WifiStateMachine(  966): processMsg: DefaultState
,D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  966): send additional Connectivity Action
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  966): handleConnectivityChange:1 is conntected
,D/WifiStateMachine(  966): handleMessage: X
,D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
I/dalvikvm( 4771): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4771): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4771): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4771): Shutting down VM
,W/dalvikvm( 4771): threadid=1: thread exiting with uncaught exception (group=0x41840e48)
E/AndroidRuntime( 4771): FATAL EXCEPTION: main
E/AndroidRuntime( 4771): Process: com.test.thalitest, PID: 4771
E/AndroidRuntime( 4771): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4771): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4771): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4771): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4771): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4771): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4771): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4771): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4771): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4771): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4771): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4771): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4771): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4771): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4771): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4771): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4771): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4771): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4771): 	at dalvik.system.NativeStart.main(Native Method)
,D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  966):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  966): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
W/ActivityManager(  966):   Force finishing activity com.test.thalitest/.MainActivity
,V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3 f}
W/Settings( 5075): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 5075): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5075): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5075): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5075): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5075): Remote Branch: 
I/Adreno-EGL( 5075): Local Patches: 
I/Adreno-EGL( 5075): Reconstruct Branch: 
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DhcpStateMachine(  966): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  966): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  966): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  966): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  966): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  966): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  966): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  966): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  966): RunningState
,I/CheckinRequestBuilder( 1971): Classify the device as Phone.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  966): Activity pause timeout for ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4324f140 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  966): moveHomeStack:
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c52988 stackId=0, 1 tasks}
,V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  966): resumeTopActivityLocked: Resumed ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c52988 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1}
,I/CheckinTask( 1971): Sending checkin request (11583 bytes)
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1862): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 8:27:24
,D/UpdateThreadPoolManager( 1862): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1862): 2 : quick cover state : opened : 0
,D/WeatherService( 1862): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1862): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1862): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1862): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1862): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1862): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 8:27:24
,D/WeatherService( 1862): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1862): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1862): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1862): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1862): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1862): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1862): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1862): 2 : This is isUpdating : false
,D/WeatherService( 1862): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1862): 2 : buildUpdate, appWidgetId: 1
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WeatherReflect( 1862): 2 : Map key string is -2
D/lim     ( 1862): 2 : time = 08:27
I/WeatherReflect( 1862): Model Name : LG-D802
D/WeatherTheme( 1862): 2 : Different view - status_min_formatted : 25 != 27
D/WeatherTheme( 1862): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1862): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1862): 2 : Fixed theme : optimus
D/WeatherTheme( 1862): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1862): 2 : quick cover state : opened : 0
D/Weather.Utils( 1862): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1862): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1862): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1487): GC_CONCURRENT freed 5524K, 9% free 60929K/66636K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 3503K, 9% free 71492K/78288K, paused 39ms, total 39ms
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
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1487): GC_FOR_ALLOC freed 4872K, 9% free 61906K/67432K, paused 19ms, total 20ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@4287dfb8 time:122875
,D/UsbSettings( 2613): [AUTORUN] onDestroy() : getDefaultFunction =boot
,V/UsbSettings( 2613): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2613): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2613): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{431068f8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{431068f8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c52988 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1} time:122906
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/CheckinRequestBuilder( 1971): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1971): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1559): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1559): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1559): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1559): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1559): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1971): awaiting user notification for token
,I/CheckinRequestBuilder( 1971): Classify the device as Phone.
,D/dalvikvm(  966): GC_CONCURRENT freed 2237K, 47% free 30822K/57844K, paused 3ms+6ms, total 108ms
,D/dalvikvm(  966): WAIT_FOR_CONCURRENT_GC blocked 103ms
,D/dalvikvm(  966): WAIT_FOR_CONCURRENT_GC blocked 78ms
D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x431f4528: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/CheckinTask( 1971): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1971): Checking schedule, now: 1452238045291 next: 1452815441287
I/CheckinService( 1971): active receiver: disabled
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  966): battery changed pluggedType: 2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1559): GC_EXPLICIT freed 722K, 29% free 17825K/24832K, paused 1ms+2ms, total 21ms
,D/GCM     ( 1559): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
E/Parcel  (  402): Reading a NULL string not supported here.
,E/Parcel  (  402): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  966): NoActiveNetworkState{ when=-6ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4122): onReceive
,D/AppUp4:CustFacade( 4122): Context : android.app.ReceiverRestrictedContext@428983a0
D/AppUp4:CustFacade( 4122): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4122): isOpenOperator : true
,D/AppUp4:CustFacade( 4122): isPhone : true
,I/LicenseContentProvider( 3008): start selecting data
,D/SIMObserver( 3008): simInfo1
,I/AppUp4:EulaManager( 4122): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4122): begin check event
,I/AppUp4:CustModeStarterReceiver( 4122): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4122): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4122): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4122): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4122): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4122): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4687): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4687): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4923): DownloadService onCreate
,D/eas_req ( 4687): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4923): in removeSpuriousFiles
,V/DownloadManager( 4923): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4923): DownloadService onStartCommand
W/Settings( 4687): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4441): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4441): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4923): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428cb128 on behalf of 4923
I/LgeMiscReceiver( 4441): networkInfo.isConnected() = false
V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428cce38 on behalf of 4923
D/MobileConnectivityChangeReceiver( 4964): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4964): onReceive CONNECTIVITY_CHANGE networkType=1
I/DownloadManager( 4923): in trimDatabase
V/DownloadManager( 4923): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428cdf78 on behalf of 4923
D/LGDMClient( 2889): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/GCM     ( 1559): Connected
D/LGDMClient( 2889): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
V/DownloadManager( 4923): DownloadService onDestroy
,D/LGDMSGCM( 5030): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2889): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 5030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 5044): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5044): CONNECT : WIFI_CONNECT
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
E/LGDMClient( 2889): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2889): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2889): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/Tethering(  966): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  966): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/LGDMClient( 2889): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/GCM     ( 1559): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] request level :IDLE....
,I/GoogleURLConnFactory( 1559): Using platform SSLCertificateSocketFactory
,I/AppUp4:CustModeStarterReceiver( 4122): onReceive
,D/AppUp4:CustFacade( 4122): Context : android.app.ReceiverRestrictedContext@428983a0
D/AppUp4:CustFacade( 4122): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4122): isOpenOperator : true
,D/AppUp4:CustFacade( 4122): isPhone : true
,I/LicenseContentProvider( 3008): start selecting data
,D/SIMObserver( 3008): simInfo1
,I/AppUp4:EulaManager( 4122): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4122): begin check event
,I/AppUp4:CustModeStarterReceiver( 4122): Event For GoodConnectivity, noConnectivity : false, but skip! 
,W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/DownloadManager( 4923): DownloadService onCreate
D/EAS     ( 4687): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,I/DownloadManager( 4923): in removeSpuriousFiles
D/EAS     ( 4687): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4923): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4923): DownloadService onStartCommand
V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428d2a48 on behalf of 4923
,V/DownloadManager( 4923): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/Uploader( 1559): No account for auth token provided
I/LgeMiscReceiver( 4441): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4441): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4441): networkInfo.isConnected() = true
,D/PhoneState( 4441): setPdpRejectCasuse : false
,V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428d4bd0 on behalf of 4923
I/DownloadManager( 4923): in trimDatabase
W/Settings( 4687): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4923): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/MobileConnectivityChangeReceiver( 4964): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4964): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428d5cd8 on behalf of 4923
,D/LGDMClient( 2889): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4923): DownloadService onDestroy
,D/LGDMClient( 2889): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5030): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/NFS     ( 5044): connectivityManager.getNetworkInfo = TYPE_WIFI
D/libc    (  270): _dns_getaddrinfo: iptype =1
D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/LGDMClient( 2889): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/Wireless_Storage( 5044): CONNECT : WIFI_CONNECT
,W/ContextImpl( 5030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2889): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2889): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2889): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2889): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1559): No account for auth token provided
,W/Uploader( 1559): No account for auth token provided
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/Uploader( 1559):  no longer exists, so no auth token.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1559): No account for auth token provided
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1487): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  966): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4122): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4122): onReceive
,D/AppUp4:CustFacade( 4122): Context : android.app.ReceiverRestrictedContext@428983a0
D/AppUp4:CustFacade( 4122): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4122): isOpenOperator : true
,D/AppUp4:CustFacade( 4122): isPhone : true
,I/LicenseContentProvider( 3008): start selecting data
,D/SIMObserver( 3008): simInfo1
,I/AppUp4:EulaManager( 4122): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4122): begin check event
,I/AppUp4:CustModeStarterReceiver( 4122): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/EAS     ( 4687): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4687): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4923): DownloadService onCreate
,I/DownloadManager( 4923): in removeSpuriousFiles
,V/DownloadManager( 4923): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428d9f80 on behalf of 4923
,I/DownloadManager( 4923): in trimDatabase
,V/DownloadManager( 4923): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428db978 on behalf of 4923
,V/DownloadManager( 4923): DownloadService onStartCommand
,V/DownloadManager( 4923): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4923): created cursor android.database.sqlite.SQLiteCursor@428ddb28 on behalf of 4923
,I/LgeMiscReceiver( 4441): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4441): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4441): networkInfo.isConnected() = true
,D/PhoneState( 4441): setPdpRejectCasuse : false
,W/Settings( 4687): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4964): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4964): onReceive CONNECTIVITY_CHANGE networkType=1
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4923): DownloadService onDestroy
,D/LGDMClient( 2889): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2889): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5030): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LGDMClient( 2889): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2889): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
I/NFS     ( 5044): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5044): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2889): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2889): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2889): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
W/ContextImpl( 5030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  966): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.440613 Y: -0.424179 Z: 9.809708 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440613 .y:-0.424179 .z:9.809708
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.432098 Y: -0.426620 Z: 9.815903 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.432098 .y:-0.426620 .z:9.815903
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/WifiServiceExtension(  966): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  966): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 5056): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  966): Killing 4710:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c52988 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1}
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/Finsky  ( 4351): [406] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4351): [1] 5.onFinished: Installation state replication succeeded.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  966): battery changed pluggedType: 2
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  966): battery changed pluggedType: 2
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/ActivityManager(  966): Killing 4856:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c52988 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1}
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
,D/WifiController(  966): battery changed pluggedType: 2
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3841): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3841): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  966): Handling package changes for user 0
,I/ActivityManager(  966): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5290 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/InputReader(  966): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
D/HyLog   ( 5290): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5290): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5290): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
,I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "smsto"
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5290): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5290): MmsConfig.loadMmsSettings
,I/Babel   ( 5290): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5290): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5290): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5290): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5290): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5290): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5290): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5290): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5290): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5290): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5290): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5290): MmsConfig.loadFromResources
,E/Babel   ( 5290): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5290): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5290): [loadRssi] File not exist 
V/LGRssiData( 5290): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5290): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:Utils( 4122): [getPackageName] uri : package:com.google.android.gms
V/TelephonyAutoProfiling( 5290): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/AppUp4  ( 4122): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 4122): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/TelephonyAutoProfiling( 5290): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5290): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:CustModeStarterReceiver( 4122): onReceive
D/AppUp4:CustFacade( 4122): Context : android.app.ReceiverRestrictedContext@428983a0
,D/AppUp4:CustFacade( 4122): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4122): isOpenOperator : true
,D/AppUp4:CustFacade( 4122): isPhone : true
,I/LicenseContentProvider( 3008): start selecting data
,D/SIMObserver( 3008): simInfo1
,I/AppUp4:EulaManager( 4122): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4122): begin check event
D/AppUp4:Utils( 4122): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4122): Event For Nothing, skip.
,I/ActivityManager(  966): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5339 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/HyLog   ( 5339): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5339): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5339): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/GmsNetworkLocationProvi( 1422): DISABLE
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SystemConfig( 5339): BUILD Country: EU
,I/SystemConfig( 5339): BUILD Operator: OPEN
I/ActivityManager(  966): Killing 4890:com.lge.qremote/u0a96 (adj 15): empty #17
,I/SystemConfig( 5339): systemFeature RCS result false
,D/SystemConfig( 5339): refreshRcsSupport() :false
,I/ActivityManager(  966): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5358 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c52988 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): Killing 4771:com.test.thalitest/u0a304 (adj 15): empty #17
,D/LocationProviderProxy(  966): applying state to connected service
,D/LocationProviderProxy(  966): applying state to connected service
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HyLog   ( 5358): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5358): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5358): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiController(  966): battery changed pluggedType: 2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WindowState(  966): WIN DEATH: Window{44f26d68 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  966): Client connection lost with reason: 4
,I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{43cdf650 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,W/Binder  ( 1316): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1316): java.lang.NullPointerException
W/Binder  ( 1316): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1316): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1316): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1316): 	at dalvik.system.NativeStart.run(Native Method)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/InputMethodManagerService(  966): IME STATUS OFF
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c52988 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1}
W/InputMethodManagerService(  966): Got RemoteException sending setActive(false) notification to pid 4771 uid 10304
D/WifiController(  966): battery changed pluggedType: 2
,I/ActivityManager(  966): Killing 4923:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2690): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c52988 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1971): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1971): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  966): Delaying start of: ServiceRecord{4477ea28 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1971): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1971): GC_CONCURRENT freed 1911K, 22% free 19593K/24832K, paused 2ms+3ms, total 30ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/IcingCorporaProvider( 2690): UpdateCorporaTask done [took 218 ms] updated apps [took 218 ms] 
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  966): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  966): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  966): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  966): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  966): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  966): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  966): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV4    ( 5290): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PowerManagerService(  966): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  966): [updateScreenState] screen on = false
D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  966): _hal_sensors_flush: handle=35
,I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 6720 usec
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = true
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.441986 Y: -0.425903 Z: 9.817978 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441986 .y:-0.425903 .z:9.817978
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  966): hal_acquire_resources
I/qcom_sensors_hal(  966): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0,
D/qcom_sensors_hal(  966): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,I/qcom_sensors_hal(  966): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  966): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  966): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  966): hal_sam_send_cancel: Sending cancel to 21,
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  966): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.428009 Y: -0.429443 Z: 9.804581 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.428009 .y:-0.429443 .z:9.804581
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.435883 Y: -0.423035 Z: 9.818756 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.435883 .y:-0.423035 .z:9.818756
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/Sensors (  375): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  966): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  966): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  966): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  966): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  966): proximitySensorChanged  positive = true
I/KnockOnPowerController(  966): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.441559 Y: -0.418518 Z: 9.819778 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441559 .y:-0.418518 .z:9.819778
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.429977 Y: -0.430283 Z: 9.817062 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.429977 .y:-0.430283 .z:9.817062
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.422272 Y: -0.439102 Z: 9.829315 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.422272 .y:-0.439102 .z:9.829315
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.433319 Y: -0.429642 Z: 9.829178 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.433319 .y:-0.429642 .z:9.829178
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  273): Screen released, type=0 flinger=0xb8c90450
,V/KeyguardServiceDelegate(  966): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@442ead50)
,D/qdhwcomposer(  273): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.442505 Y: -0.419586 Z: 9.812271 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442505 .y:-0.419586 .z:9.812271
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  966): **** SHOWN CALLED ****
I/WindowManager(  966): No lock screen! windowToken=null
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,D/WifiStateMachine(  966): handleScreenStateChanged: true
,D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=131127
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  966): handleMessage: X
,D/WifiServiceExtension(  966): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  966): handleMessage: E msg.what=132097
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
,D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  966): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2022): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2022): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
,D/WifiOffDelayIfNotUsed(  966): stopMonitoring
,E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 966
V/SRS_Proc(  276): ParamSet string: screen_state=on
,D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1158): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433aec38 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1158): enqueuing start. mLedList.size()=2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1158): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1862): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 8:27:40
,E/SlideAside( 3841): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3841): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1862): 2 : This is isUpdating : false
,D/WeatherAncestor( 1862): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 8:27:40
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1862): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1862): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1862): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1862): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.434937 Y: -0.439575 Z: 9.815536 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.434937 .y:-0.439575 .z:9.815536
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.447250 Y: -0.436310 Z: 9.816635 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447250 .y:-0.436310 .z:9.816635
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1158): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1158): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1158): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1158): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1158): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 219, B = 219
,D/qdhwcomposer(  273): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  966): Excessive delay in blankDisplay() while turning screen off: 400ms
D/qdlights( 1158): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1158): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 207, B = 207
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 201, B = 201
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/qdlights( 1158): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 195, B = 195
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238060853, nextTick: 19180, mDrawingTime: 0
,D/qdlights( 1158): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1158): set_light_notifications: 2,ff00b7b7,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238060874, nextTick: 19159, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,D/qdlights( 1158): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 177, B = 177
,D/WeatherService( 1862): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 8:27:40
,D/WeatherService( 1862): 2 : ACTION screen on
,D/WeatherService( 1862): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1158): set_light_notifications: 2,ff00abab,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 171, B = 171
,D/WeatherService( 1862): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 8:27:40
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
,D/qdlights( 1158): set_light_notifications: 2,ff00a5a5,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 165, B = 165
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): ACTION_SCREEN_ON
,D/qdlights( 1158): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 159, B = 159
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, enabled=0
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
,I/LGImmersionVibrator(  966): Vibrator off
D/qdlights( 1158): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 153, B = 153
,I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
D/qcom_sensors_hal(  966): hal_acquire_resources
D/qcom_sensors_hal(  966): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  966): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
D/WifiStateMachine(  966): handleScreenStateChanged: false
D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  966): doBoolean: DRIVER SETSUSPENDMODE 1
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1} (stop requested)
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.433182 Y: -0.410614 Z: 9.819031 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.433182 .y:-0.410614 .z:9.819031
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/qdlights( 1158): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 147, B = 147
,E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=off
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  966): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  966): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  966): hal_smgr_report_delete: Rcvd success response from request
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 966
V/SRS_Proc(  276): ParamSet string: screen_state=off
,D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/WifiController(  966): CMD_SCREEN_OFF 
D/WifiController(  966): shouldWifiStayAwake TRUE
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{42cebea8 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): handleMessage: X
D/qdlights( 1158): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 141, B = 141
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1158): clear
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
D/KeyguardViewManager( 1142): onScreenTurnedOff()
E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1158): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 135, B = 135
D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=2
I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1158): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 129, B = 129
D/WeatherService( 1862): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 8:27:40
D/WeatherService( 1862): 2 : ACTION screen off
D/WeatherService( 1862): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 8:27:40
V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
E/Parcel  (  402): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/qdlights( 1158): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 123, B = 123
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_OFF
D/NfcService( 1471): NFC-C OFF
D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/qdlights( 1158): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 117, B = 117
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): ACTION_SCREEN_OFF
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1459): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1459): ,[TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/qdlights( 1158): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1158): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1158): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1158): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1158): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1158): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1158): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1158): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1158): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1158): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1158): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1158): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1158): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1158): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1158): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1158): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1158): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
D/qdlights( 1158): set_light_notifications: 1,ff00ff00,500,2000,1
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Sensors (  375): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  292): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238078758074079; DSPS: 5270638; Offset: 1452237917910967146
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238080039, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238080045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238098759394902; DSPS: 5926041; Offset: 1452237917910975713
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238118760264666; DSPS: 6581429; Offset: 1452237917910990985
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238138761736107; DSPS: 7236838; Offset: 1452237917910967065
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238140050, nextTick: 59979, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238140053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238158763054820; DSPS: 7892241; Offset: 1452237917910973522
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238178764365090; DSPS: 8547644; Offset: 1452237917910971536
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 270 plugged : true isCharging : false
D/WifiController(  966): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238198765225890; DSPS: 9203032; Offset: 1452237917910977844
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238200038, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238200041, nextTick: 59991, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238218766127101; DSPS: 9858422; Offset: 1452237917910963527
,D/wpa_supplicant( 2022): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 7 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 8 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a],
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 9 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 10 BSSID 8c:04:ff:b9:af:25 SSID 'SALVADOR' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2022): wlan0: BSS: Remove id 11 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 12 BSSID 64:7c:34:b0:03:6e SSID 'UPC4688432' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 13 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:37:b7:9d:3e:73]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 44:e9:dd:10:c0:ac]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 06:7c:34:38:27:cc]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 8c:04:ff:b9:af:25]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 64:7c:34:38:27:cc]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 64:7c:34:b0:03:6e]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:26:f2:18:08:c8]
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238238766585344; DSPS: 10513797; Offset: 1452237917910964007
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/EventLogService( 1971): Aggregate from 1452238042810 (log), 1452236421832 (data)
,D/dalvikvm(  966): GC_EXPLICIT freed 3078K, 47% free 30779K/57184K, paused 6ms+18ms, total 204ms
,D/dalvikvm( 2668): GC_CONCURRENT freed 7731K, 32% free 16922K/24832K, paused 2ms+2ms, total 38ms
,D/dalvikvm( 2668): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1559): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1559): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1559): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1559): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1559): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x43303c58: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1559): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1559): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1559): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1559): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1559): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1559): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1559): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1559): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4351): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4351): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4351): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4351): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4351): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4351): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4351): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4351): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4351): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4351): isDataSchedulerEnabled():false
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238258768517475; DSPS: 11169220; Offset: 1452237917910973530
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238260059, nextTick: 59973, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238260060, nextTick: 59973, mDrawingTime: 0
,I/LocationManagerService(  966): remove 4332d5c8
,D/LocationManagerService(  966): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  966): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  966): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  966): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  966): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2668): GC_CONCURRENT freed 1954K, 32% free 17005K/24832K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 2668): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2668): GC_CONCURRENT freed 1780K, 31% free 17272K/24832K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 2668): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2668): GC_FOR_ALLOC freed 1586K, 30% free 17467K/24832K, paused 19ms, total 19ms
,I/Mlt MonitorService( 2668): parseLastkmsg to dump
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238278769425412; DSPS: 11824610; Offset: 1452237917910965940,
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 268 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238298769870143; DSPS: 12479984; Offset: 1452237917910983425
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238318773391358; DSPS: 13135460; Offset: 1452237917910964601
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238320037, nextTick: 59993, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238320039, nextTick: 59993, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238338774312222; DSPS: 13790850; Offset: 1452237917910969937
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238358775200364; DSPS: 14446239; Offset: 1452237917910973070
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238378775650005; DSPS: 15101614; Offset: 1452237917910964947
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238380033, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238380048, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238398776091544; DSPS: 15756988; Offset: 1452237917910979240
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238418778972136; DSPS: 16412443; Offset: 1452237917910960662
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238438779880638; DSPS: 17067833; Offset: 1452237917910953637
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238440046, nextTick: 59982, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238440049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238458780802259; DSPS: 17723222; Offset: 1452237917910990248
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238478781678395; DSPS: 18378611; Offset: 1452237917910981374
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238498782611779; DSPS: 19034002; Offset: 1452237917910968713
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238500032, nextTick: 59983, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452238500045, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238518783521415; DSPS: 19689392; Offset: 1452237917910962822
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452238538784434231; DSPS: 20344782; Offset: 1452237917910960110
,I/ActivityManager(  966): Killing 4687:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c52988 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused

```
