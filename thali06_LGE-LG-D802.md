#### Test 50650278923ff9f_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4681): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  963): Killing 4149:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4316f1b0 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1844): GC_CONCURRENT freed 1529K, 22% free 19437K/24836K, paused 5ms+4ms, total 41ms
D/dalvikvm( 1844): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 1844): WAIT_FOR_CONCURRENT_GC blocked 14ms
I/ConfigFetchService( 1844): fetch service done; releasing wakelock
I/ConfigFetchService( 1844): stopping self
D/ChimeraCfgMgr( 1844): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1844): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1844): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1844): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1844): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4738): 
D/AndroidRuntime( 4738): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4738): CheckJNI is OFF
D/dalvikvm( 4738): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4738): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4738): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4738): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4738): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4738): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4738): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4738): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4738): Calling main entry com.android.commands.am.Am
I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4738
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (120 us)
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{4316f1b0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  963): startService SlideAside
W/ContextImpl(  963): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{433021a0 stackId=1, 2 tasks}
D/UsbSettingsControl( 2632): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2632): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4738): Shutting down VM
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{4316f1b0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{4316f1b0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 4116): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4738): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+4ms, total 6ms
I/ActivityManager(  963): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4756 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 4116): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/SlideAside( 4116): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4756): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4756): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4756): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
V/WebViewChromium( 4756): Binding Chromium to the background looper Looper (main, tid 1) {4283cdd0}
I/chromium( 4756): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4756): Initializing chromium process, renderers=0
D/wpa_supplicant( 2037): nl80211: survey data missing!
D/WifiStateMachine(  963): handleMessage: X
W/chromium( 4756): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4756): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4756): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4756): Remote Branch: 
I/Adreno-EGL( 4756): Local Patches: 
I/Adreno-EGL( 4756): Reconstruct Branch: 
I/dalvikvm( 4756): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4756): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4756): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4756): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4756): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4756): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4756): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4756): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4756): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4756): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4756): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4756): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4756): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4756): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4756): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4756): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4756): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4756): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4756): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4756): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4756): Enabling debug mode 0
,W/AwContents( 4756): nativeOnDraw failed; clearing to background color.
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.446548 Y: -0.407623 Z: 9.788467 
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.451004 Y: -0.388779 Z: 9.754074 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.446548 .y:-0.407623 .z:9.788467
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/InputMethodManagerService(  963): IME STATUS OFF
W/AwContents( 4756): nativeOnDraw failed; clearing to background color.
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
I/ActivityManager(  963): Displayed com.test.thalitest/.MainActivity: +414ms
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.452209 Y: -0.393494 Z: 9.795776 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452209 .y:-0.393494 .z:9.795776
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/ActivityManager( 4756): Timeline: Activity_idle id: android.os.BinderProxy@4283e690 time:111986
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/JsMessageQueue( 4756): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4756): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42842c28
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4756): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42842c28
,D/jxcore_app_log( 4756): JniHelper::setJavaVM(0x41705838), pthread_self() = 1638974904
,D/JX-Cordova( 4756): jxcore cordova android initializing
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3} time:112311
,D/UsbSettings( 2632): [AUTORUN] onStop()
D/ActivityManager(  963): no-history finish of ActivityRecord{4316f1b0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  963): Finishing activity token=Token{430bca80 ActivityRecord{4316f1b0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{4316f1b0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{4316f1b0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{4316f1b0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4756): GC_CONCURRENT freed 2784K, 12% free 21868K/24836K, paused 2ms+1ms, total 42ms
,D/dalvikvm( 4756): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 4756): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 4756): GC_FOR_ALLOC freed 220K, 13% free 21852K/24836K, paused 23ms, total 23ms
,D/dalvikvm( 4756): GC_FOR_ALLOC freed 184K, 12% free 21886K/24836K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 23.689MB for 144892-byte allocation
,D/dalvikvm( 4756): GC_FOR_ALLOC freed 250K, 13% free 21939K/24980K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 23.809MB for 217334-byte allocation
,D/dalvikvm( 4756): GC_FOR_ALLOC freed 382K, 13% free 22000K/25196K, paused 40ms, total 40ms
I/dalvikvm-heap( 4756): Grow heap (frag case) to 23.972MB for 325996-byte allocation
D/dalvikvm( 4756): GC_FOR_ALLOC freed 570K, 14% free 22122K/25516K, paused 23ms, total 23ms
I/dalvikvm-heap( 4756): Grow heap (frag case) to 24.248MB for 488990-byte allocation
D/dalvikvm( 4756): GC_FOR_ALLOC freed 868K, 15% free 22299K/25996K, paused 25ms, total 26ms
I/dalvikvm-heap( 4756): Grow heap (frag case) to 24.653MB for 733480-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4756): GC_FOR_ALLOC freed 1289K, 16% free 22557K/26716K, paused 24ms, total 25ms
D/dalvikvm( 4756): GC_CONCURRENT freed 1676K, 15% free 22928K/26716K, paused 3ms+2ms, total 44ms
D/dalvikvm( 4756): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/dalvikvm( 4756): WAIT_FOR_CONCURRENT_GC blocked 23ms
D/dalvikvm( 4756): GC_FOR_ALLOC freed 376K, 15% free 22886K/26716K, paused 23ms, total 23ms
I/dalvikvm-heap( 4756): Grow heap (frag case) to 26.101MB for 1650320-byte allocation
D/dalvikvm( 4756): GC_CONCURRENT freed 1854K, 17% free 23526K/28328K, paused 0ms+4ms, total 48ms
D/dalvikvm( 4756): GC_FOR_ALLOC freed 1226K, 17% free 23520K/28328K, paused 25ms, total 26ms
I/dalvikvm-heap( 4756): Grow heap (frag case) to 27.506MB for 2475476-byte allocation
,D/dalvikvm( 4756): GC_CONCURRENT freed 384K, 16% free 25854K/30748K, paused 3ms+2ms, total 57ms
,D/dalvikvm( 4756): GC_FOR_ALLOC freed 4238K, 21% free 24498K/30748K, paused 29ms, total 31ms
,I/dalvikvm-heap( 4756): Grow heap (frag case) to 29.643MB for 3713210-byte allocation
,D/dalvikvm( 4756): GC_CONCURRENT freed 264K, 19% free 27948K/34376K, paused 2ms+4ms, total 30ms
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/dalvikvm( 4756): GC_FOR_ALLOC freed 3205K, 26% free 25473K/34376K, paused 24ms, total 24ms
,W/jxcore-log( 4756): Initializing JXcore engine
,W/jxcore-log( 4756): JXcore engine is ready
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  963): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4756): GC_CONCURRENT freed 371K, 19% free 28102K/34376K, paused 2ms+1ms, total 33ms
,D/dalvikvm( 4756): WAIT_FOR_CONCURRENT_GC blocked 30ms
,W/jxcore-log( 4756): Starting JXcore engine
,W/jxcore-log( 4756): Platform android
W/jxcore-log( 4756): 
,W/jxcore-log( 4756): Process ARCH arm
W/jxcore-log( 4756): 
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/GAV2    ( 4681): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4756): JXcore Cordova bridge is ready!
I/jxcore-log( 4756): 
,W/jxcore-log( 4756): JXcore engine is started
,I/chromium( 4756): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4756): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4756): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1548): onDestroy
,I/jxcore-log( 4756): Toggling radios to true
I/jxcore-log( 4756): 
,D/BluetoothManagerService(  963): Message: 20
,D/BluetoothManagerService(  963): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c871f0:true
,D/BluetoothAdapter( 4756): enable(): BT is already enabled..!
D/WifiService(  963): New client listening to asynchronous messages
,D/WifiStateMachine(  963): handleMessage: E msg.what=131145
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doBoolean: DISCONNECT
,I/jxcore-log( 4756): Radios toggled
I/jxcore-log( 4756): 
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2037): wlan0: Cancelling scan request
D/wpa_supplicant( 2037): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2037): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2037): TDLS: Tear down peers
,D/wpa_supplicant( 2037): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  963): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4756): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4756): 
,I/jxcore-log( 4756): Perf Test app loaded loaded
I/jxcore-log( 4756): 
D/WifiService(  963): setWifiEnabled: true pid=4756, uid=10304
E/WifiService(  963): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  963): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  963): disconnect pid=4756, uid=10304
,D/WifiService(  963): reconnect pid=4756, uid=10304
I/Choreographer( 4756): Skipped 59 frames!  The application may be doing too much work on its main thread.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2037): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2037): wlan0: Deauthentication notification
D/wpa_supplicant( 2037): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2037): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
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
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8bf6d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
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
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2037): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' adde,d
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2037): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: ConnectedState
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/jxcore-log( 4756): check test folder
I/jxcore-log( 4756): 
W/Settings(  963): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  963): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=5
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  963): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131146
D/WifiStateMachine(  963): processMsg: DisconnectingState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiNative-wlan0(  963): doBoolean: RECONNECT
I/jxcore-log( 4756): found test : ./testFindPeers.js
I/jxcore-log( 4756): 
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2037): Fast associate: Old scan results
D/wpa_supplicant( 2037): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2037): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2037): wlan0: nl80211: scan request
D/wpa_supplicant( 2037): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2037): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2037): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147460
D/WifiStateMachine(  963): processMsg: DisconnectingState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): Network connection lost
D/WifiStateMachine(  963): Stopping DHCP and clearing IP
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  963): doBoolean: SET ps 1
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
D/DhcpStateMachine(  963): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiP2pService(  963): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): addressRemoved: 192.168.1.140/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  963): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  963): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
D/QCNEA   (  491): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  491): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  491): |CAC| updateNetCfgInfo
V/QCNEA   (  491): |CAC| *********************************************
V/QCNEA   (  491): |CAC|                   Netconfig               
V/QCNEA   (  491): |CAC| *********************************************
V/QCNEA   (  491): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  491): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  491): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  491): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  491): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  491): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  491): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  491): |CAC| *********************************************
D/QCNEA   (  491): |CAC| Received bssid= 
D/QCNEA   (  491): |CAC| net type = 3
V/QCNEA   (  491): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  491): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  491): |CAC| 	ssid           =NG700
V/QCNEA   (  491): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  491): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  491): |CAC| *********************************************
D/QCNEA   (  491): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  491): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  491): |CAC| dispatchNetCfg: updating:0xb81e18dc
,D/QCNEA   (  491): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  491): Reading a NULL string not supported here.
,E/Parcel  (  491): Reading a NULL string not supported here.
D/WifiHS20(  963): hidePasspointNotification off =false
,D/QcConnectivityService(  963): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 0
D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  963): Attempting to switch to mobile
D/QcConnectivityService(  963): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  963): handleConnectivityChange: preConnState=1 connState=2
I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/jxcore-log( 4756): found test : ./testSendData.js
I/jxcore-log( 4756): 
D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  963): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  963): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131213
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131213
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
,V/        (  264): RouteController
I/ActivityManager(  963): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4822 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,D/HyLog   ( 4822): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4822): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4822): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
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
,D/NetUtils(  963): android_net_utils_resetConnections in env=0x62864468 clazz=0x6be00001 iface=wlan0 mask=0x3
,I/PCSuite ( 4822): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 4822): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4822): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QcConnectivityService(  963): resetConnections(wlan0, 3)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,V/NativeCrypto( 1548): Read error: ssl=0x62562380: I/O error during system call, Connection timed out
,V/NativeCrypto( 1548): SSL shutdown failed: ssl=0x62562380: I/O error during system call, Broken pipe
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  963): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4858 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  963): Killing 4235:com.google.android.talk/u0a77 (adj 15): empty #17
,I/chromium( 4756): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/GpsLocationProvider(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 4858): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4858): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4858): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiController(  963): battery changed pluggedType: 2
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4858): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4858): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4858): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4858): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4858): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4858): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4858): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4858): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4858): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  963): Killing 4356:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  963): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  963): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :false
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2037): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2037): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2037): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 2037): nl80211: Survey data missing
D/wpa_supplicant( 2037): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2037): wlan0: BSS: Add new id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Add new id 6 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 2037): wlan0: New scan results available
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2037): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2037): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2037): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2037): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2037): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-47 wps
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
D/wpa_supplicant( 2037): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8bf85a8  current_ssid=0x0
D/wpa_supplicant( 2037): scard is not null..
D/wpa_supplicant( 2037): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wl,an0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2037): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2037): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2037): wlan0: Cancelling scan request
D/wpa_supplicant( 2037): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2037): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2037): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2037): RSN: PMKSA cache search - network_ctx=0xb8bf85a8 try_opportunistic=0
D/wpa_supplicant( 2037): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2037): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2037): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2037): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2037): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2037): wlan0: WPA: using PTK CCMP,
,D/wpa_supplicant( 2037): wlan0: WPA: using KEY_MGMT WPA-PSK,
,D/wpa_supplicant( 2037): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2037): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2037): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2037): wlan0: No keys have been configured - skip key clearing
,D/wpa_supplicant( 2037): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2037): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2037): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2037): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2037): nl80211: Unsubscribe mgmt frames handle 0xb8bf7590 (mode change)
D/wpa_supplicant( 2037): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8bf7590
,D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb8bf7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb8bf7590,
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb8bf7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb8bf7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb8bf7590,
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09,
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb8bf7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb8bf7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0e,
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb8bf7590,
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb8bf7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb8bf7590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 0a 11,
,D/wpa_supplicant( 2037): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2037):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037):   * freq=2412
D/wpa_supplicant( 2037):   * SSID - hexdump(len=5): 4e 47 37 30 30,
D/wpa_supplicant( 2037):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037):   * Auth Type 0
D/wpa_supplicant( 2037):   * WPA Versions 0x2
D/wpa_supplicant( 2037): nl80211: Connect request send successfully
D/wpa_supplicant( 2037): wlan0: Setting authentication timeout: 10 sec 0 usec,
D/wpa_supplicant( 2037): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2037): EAPOL: External notification - portControl=Auto,
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c2:ff:d4:d3:aa:48]
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 a0:c5:62:7a:49:97]
D/WifiStateMachine(  963): handleMessage: E msg.what=147461
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiMonitor(  963): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,W/WifiMonitor(  963): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiNative-wlan0(  963): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2037): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
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
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700],
D/WifiMonitor(  963): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  963): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428593c0
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
D/AppUp4:CustFacade( 4091): isPhone : true
I/LicenseContentProvider( 3065): start selecting data
D/SIMObserver( 3065): simInfo1
I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4091): begin check event
I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity
,D/wpa_supplicant( 2037): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2037): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 51 d5 9a 53 51 39 20 b2 3a 6e 80 95 65 fe 6f ...
D/wpa_supplicant( 2037): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2037): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2037): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2037): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2037): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2037):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2037):   key_nonce - hexdump(len=32): 51 d5 9a 53 51 39 20 b2 3a 6e 80 95 65 fe 6f c0 d6 7a 37 1d a5 97 03 ad 88 2c b1 88 a8 97 9f 84
D/wpa_supplicant( 2037):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 51 d5 9a 53 51 39 20 b2 3a 6e 80 95 65 fe 6f ...
D/wpa_supplicant( 2037): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
,D/wpa_supplicant( 2037): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2037): Get randomness: len=32 entropy=8
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,I/ActivityManager(  963): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4902 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/wpa_supplicant( 2037): WPA: Renewed SNonce - hexdump(len=32): c2 19 40 f0 a9 56 45 c6 44 95 39 4c e8 1c f9 ac cc 59 96 67 ea ec 5d c5 b1 a3 23 33 48 9c c0 33
D/wpa_supplicant( 2037): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): WPA: Nonce1 - hexdump(len=32): c2 19 40 f0 a9 56 45 c6 44 95 39 4c e8 1c f9 ac cc 59 96 67 ea ec 5d c5 b1 a3 23 33 48 9c c0 33
D/wpa_supplicant( 2037): WPA: Nonce2 - hexdump(len=32): 51 d5 9a 53 51 39 20 b2 3a 6e 80 95 65 fe 6f c0 d6 7a 37 1d a5 97 03 ad 88 2c b1 88 a8 97 9f 84
D/wpa_supplicant( 2037): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2037): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2037): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2037): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2037): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): WPA: Derived Key MIC - hexdump(len=16): 3f 78 3a 98 bc 7e 3e bd db 65 29 bf 6e eb a2 b8
D/wpa_supplicant( 2037): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 c2 19 40 f0 a9 56 45 c6 44 95 39 4c e8 1c f9 ...
,D/wpa_supplicant( 2037): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2037): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 51 d5 9a 53 51 39 20 b2 3a 6e 80 95 65 fe 6f ...,
,D/wpa_supplicant( 2037): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2037): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2037): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
,D/wpa_supplicant( 2037): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2037):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2037):   key_nonce - hexdump(len=32): 51 d5 9a 53 51 39 20 b2 3a 6e 80 95 65 fe 6f c0 d6 7a 37 1d a5 97 03 ad 88 2c b1 88 a8 97 9f 84
D/wpa_supplicant( 2037):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_rsc - hexdump(len=8): ca 22 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 2037):   key_mic - hexdump(len=16): 73 d5 56 97 d4 a6 fa fe b8 0d c8 34 3b f7 c0 63
D/wpa_supplicant( 2037): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 51 d5 9a 53 51 39 20 b2 3a 6e 80 95 65 fe 6f ...
,D/wpa_supplicant( 2037): RSN: encrypted key data - hexdump(len=56): aa 3f a5 49 5d 21 a0 5c b0 55 f7 ef 0b 0d 76 87 a3 92 3c be ef 8c ab 26 a0 49 e1 15 0d 67 e3 a9 ...
D/wpa_supplicant( 2037): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2037): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2037): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2037): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 da 36 ...
D/wpa_supplicant( 2037): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2037): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2037): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): WPA: Derived Key MIC - hexdump(len=16): a9 4e 13 78 8b a2 7d 3c 7d bd cb c5 97 60 ac 62
D/wpa_supplicant( 2037): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2037): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8bf7c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2037):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2037): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2037): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2037): WPA: RSC - hexdump(len=6): ca 22 00 00 00 00
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ee503a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2037):    broadcast key
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
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
,D/wpa_supplicant( 2037): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2037): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2037): EAP: EAP entering state DISABLED,
D/wpa_supplicant( 2037): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2037): EAPOL authentication completed successfully
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  963): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  963): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): Network connection established
D/WifiNative-wlan0(  963): doString: STATUS
D/HyLog   ( 4902): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4902): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4902): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2037): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/WifiServiceExtension(  963): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  963): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  963): transitionTo: destState=ObtainingIpState
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  963): invokeExitMethods: DisconnectedState
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  963): moveTempStackToStateStack: i=1,j=5
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
,E/Parcel  (  491): Reading a NULL string not supported here.
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
D/WifiStateMachine(  963): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  963): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  963): handleMessage: X
D/DhcpStateMachine(  963): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/DhcpStateMachine(  963): WaitBeforeStartState
,D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-12ms what=147462 obj=android.net.wifi.StateChangeResult@44dbd848 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=147462
,D/WifiStateMachine(  963): processMsg: ObtainingIpState
,D/dalvikvm(  963): GC_CONCURRENT freed 1167K, 49% free 29652K/57648K, paused 23ms+7ms, total 162ms
D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 63ms
,D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 63ms
D/WifiStateMachine(  963): ObtainingIpState{ when=-9ms what=147462 obj=android.net.wifi.StateChangeResult@4418ef60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
,D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 58ms
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-77ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-70ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196612
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-73ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,V/DownloadManager( 4902): DownloadService onCreate
,D/EAS     ( 4664): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 4902): in removeSpuriousFiles
,D/EAS     ( 4664): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4664): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4902): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@42882d68 on behalf of 4902
,I/DownloadManager( 4902): in trimDatabase
,V/DownloadManager( 4902): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4902): DownloadService onStartCommand
V/DownloadManager( 4902): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@428851e8 on behalf of 4902
,V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@428877b0 on behalf of 4902
I/LgeMiscReceiver( 4429): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4429): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4429): networkInfo.isConnected() = false
,I/ActivityManager(  963): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4928 uid=10052 gids={50052, 3003}
V/DownloadManager( 4902): DownloadService onDestroy
W/linker  ( 4664): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4664): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4664): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4664): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4664): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4664): register_HtmlEditor, Success
D/HtmlEditor( 4664): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4664): register_HtmlEditorTimer, Success
D/HtmlEditor( 4664): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4664): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4664): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4664): register_HtmlEditorFont, Success
D/HtmlEditor( 4664): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4664): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4664): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4664): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4664): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4664): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4664): JNI_OnLoad Success
I/HubEmail( 4664): JNI_OnLoad()
I/HubEmail( 4664): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4664): registerNatives()
I/HubEmail( 4664): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4664): registerNativeMethods()
I/HubEmail( 4664): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/HyLog   ( 4928): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4928): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4928): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/Settings( 4664): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  963): doBoolean: SET ps 0
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,I/ActivityManager(  963): Killing 3963:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  963): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  963): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/CommandListener(  264): Setting iface cfg
,D/CommandListener(  264): Trying to bring up wlan0
V/LGRssiData( 4928): [loadRssi] File not exist 
,V/LGRssiData( 4928): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4928): [loadFeatureFromXml] *** start feature loading from xml
,D/WifiStateMachine(  963): addressUpdated: 192.168.1.140/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  963): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  963): handleMessage: X
W/BaseRuntimeLoader( 4928): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4928): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4928): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/WifiP2pService(  963): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432d38d0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432d38d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.140/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
W/BaseRuntimeLoader( 4928): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196613
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  963): doBoolean: SET ps 1
V/TelephonyAutoProfiling( 4928): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4928): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4928): [getValue] FEATURE key : vzw_roaming_state, value : null
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/MobileConnectivityChangeReceiver( 4928): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/MobileConnectivityChangeReceiver( 4928): onReceive CONNECTIVITY_CHANGE networkType=1
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,E/PhoneMonitor( 4928): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4928): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): DHCP successful
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  963): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  963): VerifyingLinkState enter
,D/WifiStateMachine(  963): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
I/ActivityManager(  963): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4944 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  963): Killing 4414:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  963): send additional Connectivity Action
D/WifiStateMachine(  963): handleMessage: E msg.what=135190
D/WifiStateMachine(  963): processMsg: VerifyingLinkState
,E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
D/WifiStateMachine(  963): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  963): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/Parcel  (  491): Reading a NULL string not supported here.
D/WifiStateMachine(  963): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  963): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): CaptivePortalCheckState enter
,D/WifiStateMachine(  963): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/WifiStateTracker(  963): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  963): 
W/WifiStateTracker(  963):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  963):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  963): handleMessage: X
,D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  963): handleMessage: E msg.what=131092
D/WifiStateMachine(  963): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  963): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  491): Reading a NULL string not supported here.
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  491): Reading a NULL string not supported here.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiStateMachine(  963): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  963): transitionTo: destState=ConnectedState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
E/Parcel  (  491): Reading a NULL string not supported here.
,D/WifiStateMachine(  963): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 1
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/Parcel  (  491): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  963): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
E/ActivityThread(  963): Failed to find provider info for com.lge.ims.provisioning
,D/HyLog   ( 4944): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4944): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4944): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  963): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4969 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  963): Killing 4586:com.android.defcontainer/u0a4 (adj 15): empty #17
V/        (  264): RouteController
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
,D/QCNEA   (  491): |CAC| readCallback: read len:492, ret:0, errno:0
,D/QCNEA   (  491): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  491): |CAC| updateNetCfgInfo
V/QCNEA   (  491): |CAC| *********************************************
V/QCNEA   (  491): |CAC|                   Netconfig               
V/QCNEA   (  491): |CAC| *********************************************
V/QCNEA   (  491): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  491): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  491): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  491): |CAC| 	NetConfig: ip4        =192.168.1.140
V/QCNEA   (  491): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  491): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  491): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  491): |CAC| *********************************************
D/QCNEA   (  491): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  491): |CAC| net type = 1
V/QCNEA   (  491): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  491): |CAC| Received ssid= NG700
V/QCNEA   (  491): |CAC| 	ssid           =NG700
V/QCNEA   (  491): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  491): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  491): |CAC| *********************************************
D/QCNEA   (  491): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  491): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  491): |CAC| dispatchNetCfg: updating:0xb81e18dc
,D/QCNEA   (  491): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/HyLog   ( 4969): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4969): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4969): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1844): Checking schedule, now: 1450280783850 next: 1450280726367
I/CheckinService( 1844): active receiver: enabled
,I/CheckinService( 1844): Preparing to send checkin request
,I/EventLogService( 1844): Accumulating logs since 1450280693163
,I/ActivityManager(  963): Killing 4621:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2916): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
,D/LGDMClient( 2916): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2916): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
,E/LGDMClient( 2916): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2916): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2916): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2916): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  963): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4987 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 4987): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4987): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4987): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinRequestBuilder( 1844): Checkin reason type: 8 attempt count: 1
,D/DhcpStateMachine(  963): DHCP request on wlan0
D/LGDMSGCM( 4987): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LgDhcpStateMachineHelper(  963): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  268): GC_EXPLICIT freed 46K, 34% free 16472K/24836K, paused 1ms+2ms, total 22ms
E/ActivityThread( 1844): Failed to find provider info for com.google.android.wearable.settings
W/ContextImpl( 4987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 2ms+2ms, total 22ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+2ms, total 20ms
,I/ActivityManager(  963): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5008 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  963): Killing 4649:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 5008): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5008): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5008): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 5008): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5008): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5008): intf.getDisplayName() = lo
I/Wireless_Storage( 5008): intf.getDisplayName() = sit0
I/Wireless_Storage( 5008): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5008): intf.getDisplayName() = teql0
I/Wireless_Storage( 5008): intf.getDisplayName() = wlan0
,D/NFS     ( 5008): interface name:wlan0 name:wlan0
D/NFS     ( 5008): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5008): interface name:wlan0 name:wlan0
D/NFS     ( 5008): addr:192.168.1.140 broadcast:192.168.1.255
,I/Wireless_Storage( 5008): CONNECT : WIFI_CONNECT
,I/ActivityManager(  963): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5020 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  963): Killing 4283:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 5020): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5020): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5020): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 5020): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1548): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1844): awaiting user notification for token
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x42ca4f78: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  963): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5038 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5038): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5038): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5038): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5038): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5038): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5038): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5038): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5038): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5038): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5038): install
,I/MultiDex( 5038): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5038): loading existing secondary dex files
,I/MultiDex( 5038): load found 3 secondary dex files
,V/WebViewChromium( 5020): Binding Chromium to the main looper Looper (main, tid 1) {4283ac18}
,I/chromium( 5020): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5020): Initializing chromium process, renderers=0
,I/MultiDex( 5038): install done
,W/chromium( 5020): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/dalvikvm( 5038): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5038): VFY: unable to resolve instance field 61
,D/dalvikvm( 5038): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 5038): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5038): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5038): VFY: replacing opcode 0x62 at 0x0067
,I/Adreno-EGL( 5020): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5020): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5020): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5020): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5020): Remote Branch: 
I/Adreno-EGL( 5020): Local Patches: 
I/Adreno-EGL( 5020): Reconstruct Branch: 
D/dalvikvm( 5038): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5038): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5038): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5038): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5038): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5038): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42842208
,D/dalvikvm( 5038): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42842208
,D/dalvikvm( 5038): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42842208, skipping init
,D/dalvikvm( 5038): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42842208
D/dalvikvm( 5038): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42842208
,V/JNIHelp ( 5038): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 5020): Starting up...
,I/ActivityManager(  963): Killing 4298:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 5038): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42842208
D/dalvikvm( 5038): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42842208
D/dalvikvm( 5038): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42842208
D/dalvikvm( 5038): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42842208
,D/QRemote ( 4858): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4858): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4858): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4858): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4858): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4858): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4822): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4822): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4858): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4858): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4858): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4858): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 5038): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1548): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1548): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1548): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1844): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3470): callingUid 10006, callindPid: 3470
,E/MDM     ( 1424): [67] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1844): Restart initialization of location
I/dalvikvm( 5038): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5038): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5038): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5038): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5038): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5038): VFY: replacing opcode 0x6e at 0x0201
,D/DhcpStateMachine(  963): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  963): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  963): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.140
V/LgDhcpStateMachineHelper(  963): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  963): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  963): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  963): RunningState
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e76000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e76000
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
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/WifiController(  963): battery changed pluggedType: 2
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=3710821479
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5038): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a0eb28
,D/dalvikvm( 5038): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a0eb28
,D/dalvikvm( 5038): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a0eb28, skipping init
,D/wpa_supplicant( 2037): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2037): EAPOL: disable timer tick
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
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
D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=2442982580
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  963): NetTransition Wakelock for ConnectedState released by timeout
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Settings( 5038): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine(  963): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): handleMessage: X
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  963): send additional Connectivity Action
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  963):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  963): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/dalvikvm( 5038): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/jxcore-log( 4756): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4756): 
,D/dalvikvm( 5106): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 5038): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5038): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 99ms
,I/Adreno-EGL( 5038): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5038): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5038): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5038): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5038): Remote Branch: 
I/Adreno-EGL( 5038): Local Patches: 
I/Adreno-EGL( 5038): Reconstruct Branch: 
,I/Adreno-EGL( 5038): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5038): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5038): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5038): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5038): Remote Branch: 
I/Adreno-EGL( 5038): Local Patches: 
I/Adreno-EGL( 5038): Reconstruct Branch: 
,I/Adreno-EGL( 5038): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5038): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5038): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5038): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5038): Remote Branch: 
I/Adreno-EGL( 5038): Local Patches: 
I/Adreno-EGL( 5038): Reconstruct Branch: 
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/CheckinRequestBuilder( 1844): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1844): Sending checkin request (11462 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,D/WifiController(  963): battery changed pluggedType: 2
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/CheckinRequestBuilder( 1844): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1844): Failed to find provider info for com.google.android.wearable.settings
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1548): GC_EXPLICIT freed 824K, 29% free 17840K/24836K, paused 6ms+6ms, total 91ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  963): GC_EXPLICIT freed 1800K, 49% free 29575K/57648K, paused 4ms+13ms, total 155ms
,D/GCM     ( 1548): Connected
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GCM     ( 1844): Message from null null
,E/GCM     ( 1844): Dropping message from null
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1548): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1548): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1844): awaiting user notification for token
D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x43332f50: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/wpa_supplicant( 2037): nl80211: survey data missing!
E/Parcel  (  491): Reading a NULL string not supported here.
,E/Parcel  (  491): Reading a NULL string not supported here.
,D/WifiStateMachine(  963): handleMessage: X
,I/CheckinRequestBuilder( 1844): Classify the device as Phone.
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/CheckinTask( 1844): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1844): Checking schedule, now: 1450280786689 next: 1450858182685
,I/CheckinService( 1844): active receiver: disabled
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/GCM     ( 1548): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428593c0
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3065): start selecting data
,D/SIMObserver( 3065): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4091): begin check event
I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4091): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4091): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4091): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4091): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4091): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4902): DownloadService onCreate
,D/EAS     ( 4664): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4664): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4664): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4902): in removeSpuriousFiles
,V/DownloadManager( 4902): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@4288d660 on behalf of 4902
I/LgeMiscReceiver( 4429): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4429): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4429): networkInfo.isConnected() = false
,W/Settings( 4664): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4928): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4928): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 4902): in trimDatabase
,V/DownloadManager( 4902): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4902): DownloadService onStartCommand
V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@4288f4d0 on behalf of 4902
,V/DownloadManager( 4902): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2916): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@428911a0 on behalf of 4902
D/LGDMClient( 2916): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2916): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/Tethering(  963): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/LGDMSGCM( 4987): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2916): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
V/DownloadManager( 4902): DownloadService onDestroy
D/LGDMClient( 2916): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2916): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/NFS     ( 5008): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5008): CONNECT : WIFI_CONNECT
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
I/LGDMClient( 2916): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
,D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428593c0
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3065): start selecting data
,D/SIMObserver( 3065): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4091): begin check event
,I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4902): DownloadService onCreate
,I/DownloadManager( 4902): in removeSpuriousFiles
,V/DownloadManager( 4902): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4664): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4664): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@428953c8 on behalf of 4902
,V/DownloadManager( 4902): DownloadService onStartCommand
,V/DownloadManager( 4902): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4902): in trimDatabase
I/LgeMiscReceiver( 4429): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
V/DownloadManager( 4902): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4429): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4429): networkInfo.isConnected() = true
,D/PhoneState( 4429): setPdpRejectCasuse : false
,V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@42897a00 on behalf of 4902
,V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@42898ac8 on behalf of 4902
,D/MobileConnectivityChangeReceiver( 4928): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4928): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4664): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4902): DownloadService onDestroy
,D/LGDMClient( 2916): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4987): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/NFS     ( 5008): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5008): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2916): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2916): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2916): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2916): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2916): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2916): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
,D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428593c0
,D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3065): start selecting data
,D/SIMObserver( 3065): simInfo1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4091): begin check event
,I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4902): DownloadService onCreate
,I/DownloadManager( 4902): in removeSpuriousFiles
V/DownloadManager( 4902): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4664): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4664): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@4289d0f8 on behalf of 4902
,I/DownloadManager( 4902): in trimDatabase
,V/DownloadManager( 4902): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@4289e1c8 on behalf of 4902
I/LgeMiscReceiver( 4429): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4429): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4429): networkInfo.isConnected() = true
D/PhoneState( 4429): setPdpRejectCasuse : false
V/DownloadManager( 4902): DownloadService onStartCommand
,V/DownloadManager( 4902): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/MobileConnectivityChangeReceiver( 4928): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4928): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4902): created cursor android.database.sqlite.SQLiteCursor@428a0ca0 on behalf of 4902
,W/Settings( 4664): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4902): DownloadService onDestroy
,D/LGDMClient( 2916): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2916): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2916): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMSGCM( 4987): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,E/LGDMClient( 2916): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2916): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2916): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/ContextImpl( 4987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 5008): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5008): CONNECT : WIFI_CONNECT
I/LGDMClient( 2916): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 1844): GC_CONCURRENT freed 1832K, 22% free 19551K/24836K, paused 3ms+3ms, total 43ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,V/WifiServiceExtension(  963): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 5020): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.463196 Y: -0.405899 Z: 9.759186 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463196 .y:-0.405899 .z:9.759186
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.449860 Y: -0.394867 Z: 9.749908 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449860 .y:-0.394867 .z:9.749908
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/Finsky  ( 4315): [408] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4315): [1] 5.onFinished: Installation state replication succeeded.
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  963): Killing 4681:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/InputReader(  963): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  963): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5204 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,E/SlideAside( 4116): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/administrator(  963): Handling package changes for user 0
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/SlideAside( 4116): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/GlobalAccess( 1139): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1139): changeTargets() succeeded. size: 20
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
D/HyLog   ( 5204): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5204): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5204): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/MediaCodecList( 5204): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 5204): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5204): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/Babel   ( 5204): MmsConfig: mnc/mcc: 0/0
I/MediaCodecList( 5204): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 5204): MmsConfig.loadMmsSettings
I/Babel   ( 5204): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5204): MmsConfig.loadFromDatabase
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/BaseRuntimeLoader( 5204): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5204): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5204): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5204): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5204): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5204): MmsConfig.loadFromResources
,E/Babel   ( 5204): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5204): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1424): DISABLE
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 5204): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5204): [loadRssi] File not exist 
V/LGRssiData( 5204): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5204): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5204): [getMatchedProfile] selected file : /cust/config/featureset.xml
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
V/TelephonyAutoProfiling( 5204): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5204): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:Utils( 4091): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4091): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 4091): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
I/AppUp4:CustModeStarterReceiver( 4091): onReceive
D/WifiController(  963): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428593c0
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3065): start selecting data
,D/SIMObserver( 3065): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4091): begin check event
D/AppUp4:Utils( 4091): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4091): Event For Nothing, skip.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  963): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5253 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,D/WifiController(  963): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/LocationProviderProxy(  963): applying state to connected service
D/LocationProviderProxy(  963): applying state to connected service
D/HyLog   ( 5253): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5253): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5253): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5253): BUILD Country: EU
,I/SystemConfig( 5253): BUILD Operator: OPEN
,I/SystemConfig( 5253): systemFeature RCS result false
,D/SystemConfig( 5253): refreshRcsSupport() :false
I/ActivityManager(  963): Killing 4822:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  963): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5268 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  963): Killing 4858:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 5268): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5268): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5268): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2711): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  963): Killing 4902:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1844): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1844): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1844): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2711): UpdateCorporaTask done [took 218 ms] updated apps [took 218 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  963): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  963): battery changed pluggedType: 2
D/HeadsetStateMachine( 1211): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  963): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  963): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  963): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  963): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  963): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/GAV4    ( 5204): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.456696 Y: -0.394669 Z: 9.771347 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456696 .y:-0.394669 .z:9.771347
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/PowerManagerService(  963): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  963): [updateScreenState] screen on = false
D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
D/qcom_sensors_hal(  963): _hal_sensors_batch: sample_rate=20 report_rate=0 curr sample rate:0 cur rpt rate:0 max:20.000000 min:1.000000
D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
I/qcom_sensors_hal(  963): _hal_sensors_flush: handle=35
D/qcom_sensors_hal(  963): _hal_sensors_flush: handle 35 is inactive
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, enabled=1
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.458084 Y: -0.405457 Z: 9.774216 
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 5903 usec
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458084 .y:-0.405457 .z:9.774216
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  963): hal_acquire_resources
I/qcom_sensors_hal(  963): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  963): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  963): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  963): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  963): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  963): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  963): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  963): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.459198 Y: -0.408463 Z: 9.775330 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459198 .y:-0.408463 .z:9.775330
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Sensors (  324): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  963): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  963): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  963): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.445251 Y: -0.410049 Z: 9.761383 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445251 .y:-0.410049 .z:9.761383
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  963): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  963): proximitySensorChanged  positive = true
I/KnockOnPowerController(  963): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.448563 Y: -0.412277 Z: 9.757645 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448563 .y:-0.412277 .z:9.757645
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.452835 Y: -0.412643 Z: 9.758850 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452835 .y:-0.412643 .z:9.758850
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.448349 Y: -0.422714 Z: 9.761948 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448349 .y:-0.422714 .z:9.761948
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.444580 Y: -0.419968 Z: 9.773499 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444580 .y:-0.419968 .z:9.773499
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  963): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@449527c8)
,D/KeyguardViewMediator( 1139): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1139): notifyScreenOnLocked
,D/KeyguardViewMediator( 1139): handleNotifyScreenOn
,D/KeyguardViewManager( 1139): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  963): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,I/WindowManager(  963): No lock screen! windowToken=null
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb892f450
D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,E/SlideAside( 4116): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/WifiStateMachine(  963): handleScreenStateChanged: true
,D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  963): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131127
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=132097
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  963): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2037): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2037): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  963): stopMonitoring
,E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 963
V/SRS_Proc(  270): ParamSet string: screen_state=on
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4334fe00 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1816): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:46:42
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/SlideAside( 4116): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1816): 2 : This is isUpdating : false
D/WeatherAncestor( 1816): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:46:42
D/WeatherService( 1816): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered : false
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
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
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
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
,D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  963): Excessive delay in blankDisplay() while turning screen off: 410ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/GlobalAccess( 1139): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1139): changeTargets() succeeded. size: 20
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450280803215, nextTick: 16818, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450280803255, nextTick: 16777, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
,D/WeatherService( 1816): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:46:43
,D/WeatherService( 1816): 2 : ACTION screen on
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1816): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:46:43
D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
,E/Parcel  (  491): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): ACTION_SCREEN_ON
D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, enabled=0
,D/KeyguardViewMediator( 1139): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1139): notifyScreenOffLocked
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3} (pause complete)
D/qcom_sensors_hal(  963): hal_acquire_resources
D/qcom_sensors_hal(  963): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  963): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
,D/KeyguardViewMediator( 1139): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  963): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  963): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  963): hal_smgr_report_delete: Rcvd success response from request
,I/LGImmersionVibrator(  963): Vibrator off
D/KeyguardViewMediator( 1139): handleNotifyScreenOff
,D/KeyguardViewManager( 1139): onScreenTurnedOff()
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{4316f1b0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/WifiStateMachine(  963): handleScreenStateChanged: false
D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: ConnectedState
D/UsbSettings( 2632): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  963): doBoolean: DRIVER SETSUSPENDMODE 1
D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=off
,D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 963
V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{4307a208 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  963): CMD_SCREEN_OFF 
,D/WifiController(  963): shouldWifiStayAwake TRUE
V/UsbSettings( 2632): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2632): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/SRS_Proc(  270): ParamSet string: screen_state=off
V/UsbSettings( 2632): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1155): clear
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  963):    returned true
,D/WifiStateMachine(  963): handleMessage: X
,D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{4316f1b0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
D/WeatherService( 1816): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:46:43
D/WeatherService( 1816): 2 : ACTION screen off
D/WeatherService( 1816): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:46:43
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1449): Emergency Service
D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/NfcService( 1473): NFC-C OFF
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): ACTION_SCREEN_OFF
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  963): battery changed pluggedType: 2
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  963): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
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
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  324): sns_pwr.c(320):releasing wakelock
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardViewMediator( 1139): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1139): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,D/KeyguardViewMediator( 1139): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1139): doKeyguard is called, but is not locked.
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450280820038, nextTick: 59977, mDrawingTime: 6,
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450280820059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450280821045904274; DSPS: 5276894; Offset: 1450280660007879372
,I/GoogleURLConnFactory( 1548): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1548): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1548): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1548): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1548): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1548): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  963): GC_EXPLICIT freed 2921K, 49% free 29790K/57644K, paused 6ms+14ms, total 198ms
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1548): No account for auth token provided
,W/Uploader( 1548): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1548):  no longer exists, so no auth token.
,W/Uploader( 1548): No account for auth token provided
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450280841047038120; DSPS: 5932291; Offset: 1450280660007884068
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/rmt_storage(  503): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb7c53178
I/rmt_storage(  503): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  503): wakelock acquired: 1, error no: 42
,I/rmt_storage(  503): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1211813320)
,I/rmt_storage(  503): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  503): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  503): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1211813320) wakelock released: 1, error no: 0
I/rmt_storage(  503): 
I/rmt_storage(  503): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb7c53178
,E/Diag_Lib(  726): [IMS_FATAL]| 2912 | 733 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450280861054049310; DSPS: 6587880; Offset: 1450280660007906732
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450280880033, nextTick: 59993, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450280880051, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450280881064051803; DSPS: 7243568; Offset: 1450280660007899460
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450280901064498930; DSPS: 7898943; Offset: 1450280660007888823
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450280921066795849; DSPS: 8554378; Offset: 1450280660007896924
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450280940045, nextTick: 59980, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450280940058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450280941068388446; DSPS: 9209790; Offset: 1450280660007902607
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450280961070182345; DSPS: 9865209; Offset: 1450280660007895969
,I/jxcore-log( 4756): Connected to the server!
I/jxcore-log( 4756): 
,I/chromium( 4756): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/wpa_supplicant( 2037): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 6 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 2 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2037): wlan0: BSS: Remove id 3 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 4 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a],
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 a0:c5:62:7a:49:97]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 06:7c:34:12:7f:81]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11]
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450280981073835411; DSPS: 10520689; Offset: 1450280660007886925
,D/dalvikvm( 2696): GC_CONCURRENT freed 7680K, 33% free 16861K/24836K, paused 3ms+1ms, total 39ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1548): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x428556d8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1548): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1548): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1548): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1548): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1548): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4315): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4315): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4315): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4315): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4315): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4315): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4315): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4315): 	at dalvik.system.NativeStart.run(Native Method)
,D/dalvikvm( 1548): GC_CONCURRENT freed 1656K, 27% free 18204K/24836K, paused 4ms+4ms, total 116ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4315): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4315): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281000029, nextTick: 60001, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281000047, nextTick: 59984, mDrawingTime: 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281001075557747; DSPS: 11176105; Offset: 1450280660007900277
,I/LocationManagerService(  963): remove 4324d678
,D/LocationManagerService(  963): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  963): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2696): GC_CONCURRENT freed 1614K, 31% free 17294K/24836K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 2696): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 2696): GC_FOR_ALLOC freed 1657K, 31% free 17247K/24836K, paused 24ms, total 24ms
,I/Mlt MonitorService( 2696): parseLastkmsg to dump
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281021077099301; DSPS: 11831516; Offset: 1450280660007885434
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281041077698200; DSPS: 12486895; Offset: 1450280660007904499
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281060041, nextTick: 59990, mDrawingTime: 1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281060058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281061079344130; DSPS: 13142309; Offset: 1450280660007902480
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281081080200632; DSPS: 13797697; Offset: 1450280660007904490
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281101081070625; DSPS: 14453086; Offset: 1450280660007889473
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281120040, nextTick: 59990, mDrawingTime: 1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281120062, nextTick: 59966, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281121082973846; DSPS: 15108508; Offset: 1450280660007900604
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281141084644777; DSPS: 15763923; Offset: 1450280660007893069
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281161085765498; DSPS: 16419320; Offset: 1450280660007884639
,D/dalvikvm( 2696): GC_CONCURRENT freed 1931K, 31% free 17237K/24836K, paused 14ms+5ms, total 92ms
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281180045, nextTick: 59986, mDrawingTime: 1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281180057, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281181089924709; DSPS: 17074816; Offset: 1450280660007893459
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281201091675066; DSPS: 17730233; Offset: 1450280660007904315
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281221092651777; DSPS: 18385625; Offset: 1450280660007904463
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281240039, nextTick: 59991, mDrawingTime: 1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281240045, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281241097908904; DSPS: 19041158; Offset: 1450280660007882049
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281261099543480; DSPS: 19696571; Offset: 1450280660007899193
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281281100623108; DSPS: 20351967; Offset: 1450280660007880189
,I/ActivityManager(  963): Killing 4664:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433021a0 stackId=1, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281300049, nextTick: 59972, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281300068, nextTick: 59963, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281301101071382; DSPS: 21007341; Offset: 1450280660007901216
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281321102676426; DSPS: 21662754; Offset: 1450280660007888829
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281341104542148; DSPS: 22318175; Offset: 1450280660007892979
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281360046, nextTick: 59979, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281360051, nextTick: 59974, mDrawingTime: 3
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281361105465057; DSPS: 22973565; Offset: 1450280660007900360
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281381106393122; DSPS: 23628956; Offset: 1450280660007882380
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281401108236864; DSPS: 24284376; Offset: 1450280660007895068
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281420040, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281420051, nextTick: 59958, mDrawingTime: 9
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281421109364097; DSPS: 24939773; Offset: 1450280660007893150
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281441109894349; DSPS: 25595150; Offset: 1450280660007904603
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281461111424913; DSPS: 26250561; Offset: 1450280660007878771
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281480042, nextTick: 59975, mDrawingTime: 8
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281480051, nextTick: 59973, mDrawingTime: 4
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281481112964698; DSPS: 26905971; Offset: 1450280660007892677
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281501113963545; DSPS: 27561364; Offset: 1450280660007884444
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  963): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  963): Done.
,D/QcConnectivityService(  963): Setting timer for 720seconds
,I/EventLogService( 1844): Aggregate from 1450280783884 (log), 1450279677142 (data)
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281521118068798; DSPS: 28216858; Offset: 1450280660007900341
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281540046, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281540050, nextTick: 59975, mDrawingTime: 4
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281541119810144; DSPS: 28872275; Offset: 1450280660007902186
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281561121418834; DSPS: 29527688; Offset: 1450280660007893444
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281581122440077; DSPS: 30183081; Offset: 1450280660007907607
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281600047, nextTick: 59982, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281600049, nextTick: 59954, mDrawingTime: 11
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281601124026580; DSPS: 30838493; Offset: 1450280660007907196
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281621125581780; DSPS: 31493904; Offset: 1450280660007905999
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281641129714273; DSPS: 32149400; Offset: 1450280660007888102
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281660046, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281660050, nextTick: 59979, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281661131368119; DSPS: 32804814; Offset: 1450280660007893998
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281681133034883; DSPS: 33460229; Offset: 1450280660007882296
,D/GCM     ( 1548): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281701134796594; DSPS: 34115646; Offset: 1450280660007904505
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281720058, nextTick: 59971, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281720059, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281721139063461; DSPS: 34771146; Offset: 1450280660007898911
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281741140897308; DSPS: 35426566; Offset: 1450280660007901703
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281761141746258; DSPS: 36081954; Offset: 1450280660007896161
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281780044, nextTick: 59982, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281780051, nextTick: 59976, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281781142657344; DSPS: 36737344; Offset: 1450280660007891719
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281801144374890; DSPS: 37392760; Offset: 1450280660007900281
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281821145002121; DSPS: 38048141; Offset: 1450280660007886643
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281840046, nextTick: 59981, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281840051, nextTick: 59975, mDrawingTime: 3
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281841146137374; DSPS: 38703538; Offset: 1450280660007892746
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281861147990804; DSPS: 39358959; Offset: 1450280660007884603
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281881149624337; DSPS: 40014372; Offset: 1450280660007900705
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281900052, nextTick: 59975, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281900058, nextTick: 59972, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281901151190736; DSPS: 40669784; Offset: 1450280660007880190
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281921152189426; DSPS: 41325176; Offset: 1450280660007902317
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281941153777648; DSPS: 41980588; Offset: 1450280660007903625
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281960046, nextTick: 59981, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450281960050, nextTick: 59976, mDrawingTime: 3
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281961155039203; DSPS: 42635990; Offset: 1450280660007883442
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450281981157928518; DSPS: 43291444; Offset: 1450280660007904104
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282001159633198; DSPS: 43946860; Offset: 1450280660007899800
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282020047, nextTick: 59970, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282020057, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282021161270742; DSPS: 44602274; Offset: 1450280660007889395
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282041161785474; DSPS: 45257651; Offset: 1450280660007885328
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282061167655728; DSPS: 45913203; Offset: 1450280660007896207
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282080047, nextTick: 59980, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282080049, nextTick: 59982, mDrawingTime: 1,
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282081169315824; DSPS: 46568618; Offset: 1450280660007877836
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282101170621753; DSPS: 47224020; Offset: 1450280660007902027
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282121174631330; DSPS: 47879512; Offset: 1450280660007883284
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282140063, nextTick: 59962, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282140068, nextTick: 59963, mDrawingTime: 1
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282141176198145; DSPS: 48534923; Offset: 1450280660007893702
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282161177696470; DSPS: 49190332; Offset: 1450280660007896666
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282181178581411; DSPS: 49845721; Offset: 1450280660007896597
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282200041, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282200050, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282201180286924; DSPS: 50501137; Offset: 1450280660007893126
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282221182117281; DSPS: 51156557; Offset: 1450280660007892428
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282241183416284; DSPS: 51811959; Offset: 1450280660007909693
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282260070, nextTick: 59952, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282260085, nextTick: 59948, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282261185311172; DSPS: 52467382; Offset: 1450280660007881973
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282281186920227; DSPS: 53122794; Offset: 1450280660007904114
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282301187353136; DSPS: 53778169; Offset: 1450280660007879260
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282320049, nextTick: 59968, mDrawingTime: 7
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282320059, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282321192266201; DSPS: 54433689; Offset: 1450280660007909512
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282341193730881; DSPS: 55089098; Offset: 1450280660007878831
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282361194873165; DSPS: 55744495; Offset: 1450280660007891964
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282380049, nextTick: 59972, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282380059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282381196061074; DSPS: 56399894; Offset: 1450280660007889688
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282401197734035; DSPS: 57055309; Offset: 1450280660007884182
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282421199658715; DSPS: 57710732; Offset: 1450280660007886255
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282440055, nextTick: 59974, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282440057, nextTick: 59976, mDrawingTime: 0,
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282441208867770; DSPS: 58366394; Offset: 1450280660007879001
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282461210703075; DSPS: 59021814; Offset: 1450280660007883251
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282481212042390; DSPS: 59677218; Offset: 1450280660007879793
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282500080, nextTick: 59952, mDrawingTime: 1
,I/ProcessStatsService(  963): Prepared write state in 56ms
D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282500083, nextTick: 59950, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  963): Pruning old procstats: /data/system/procstats/state-2015-12-16-02-32-54.bin
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282501212872955; DSPS: 60332605; Offset: 1450280660007886383
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282521217357427; DSPS: 60988112; Offset: 1450280660007884771
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282541219260388; DSPS: 61643534; Offset: 1450280660007895642
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282560045, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1450282560051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282561219712724; DSPS: 62298909; Offset: 1450280660007890215
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450282581222985737; DSPS: 62954376; Offset: 1450280660007897847
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  963): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  963): Done.
,D/QcConnectivityService(  963): Setting timer for 720seconds
,D/LocationManagerService(  963): getAllProviders()=[passive, gps, network]
,D/GCM     ( 1548): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GoogleURLConnFactory( 1548): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1548): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,TIME-OUT KILL (timeout was 1800000ms)
```
