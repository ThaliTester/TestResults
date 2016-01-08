#### Test 54970261ac9928f_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1921): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/GAV2    ( 4665): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  967): Killing 4095:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c50ec0 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1921): GC_CONCURRENT freed 1561K, 22% free 19449K/24832K, paused 2ms+2ms, total 30ms
D/dalvikvm( 1921): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/ConfigFetchService( 1921): fetch service done; releasing wakelock
I/ConfigFetchService( 1921): stopping self
D/ChimeraCfgMgr( 1921): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1921): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1921): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1921): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1921): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
,E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4718): 
D/AndroidRuntime( 4718): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4718): CheckJNI is OFF
D/dalvikvm( 4718): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4718): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4718): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4718): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4718): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4718): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4718): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4718): failed to load memtrack module: -2
D/AndroidRuntime( 4718): Calling main entry com.android.commands.am.Am
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4718
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (117 us)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{42c50ec0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{43316298 stackId=1, 2 tasks}
D/AndroidRuntime( 4718): Shutting down VM
D/UsbSettingsControl( 2632): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2632): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4718): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 3798): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42c50ec0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{42c50ec0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4736 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3798): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 3ms+2ms, total 20ms
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 13ms
D/SlideAside( 3798): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 4736): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4736): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4736): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
V/WebViewChromium( 4736): Binding Chromium to the background looper Looper (main, tid 1) {42803060}
I/chromium( 4736): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4736): Initializing chromium process, renderers=0
W/chromium( 4736): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4736): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4736): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4736): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4736): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4736): Remote Branch: 
I/Adreno-EGL( 4736): Local Patches: 
I/Adreno-EGL( 4736): Reconstruct Branch: 
I/dalvikvm( 4736): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4736): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4736): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4736): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4736): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4736): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4736): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4736): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4736): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4736): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4736): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4736): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4736): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4736): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4736): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4736): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4736): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4736): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4736): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4736): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/OpenGLRenderer( 4736): Enabling debug mode 0
,W/AwContents( 4736): nativeOnDraw failed; clearing to background color.
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.441666 Y: -0.414352 Z: 9.787109 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441666 .y:-0.414352 .z:9.787109
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.450897 Y: -0.424927 Z: 9.806839 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450897 .y:-0.424927 .z:9.806839
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
I/InputMethodManagerService(  967): IME STATUS OFF
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/AwContents( 4736): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +707ms
,I/ActivityManager( 4736): Timeline: Activity_idle id: android.os.BinderProxy@42804830 time:111706
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3} time:111772
D/UsbSettings( 2632): [AUTORUN] onStop()
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ActivityManager(  967): no-history finish of ActivityRecord{42c50ec0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{43018eb8 ActivityRecord{42c50ec0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{42c50ec0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{42c50ec0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{42c50ec0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/JsMessageQueue( 4736): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4736): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42808a00
,I/chromium( 4736): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/dalvikvm( 4736): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42808a00
,D/jxcore_app_log( 4736): JniHelper::setJavaVM(0x416c5838), pthread_self() = 1631802288
,D/JX-Cordova( 4736): jxcore cordova android initializing
,I/chromium( 4736): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4736): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4736): GC_CONCURRENT freed 2792K, 12% free 21860K/24832K, paused 1ms+2ms, total 56ms
D/dalvikvm( 4736): WAIT_FOR_CONCURRENT_GC blocked 40ms
D/dalvikvm( 4736): WAIT_FOR_CONCURRENT_GC blocked 31ms
D/dalvikvm( 4736): GC_FOR_ALLOC freed 138K, 12% free 21868K/24832K, paused 22ms, total 23ms
D/dalvikvm( 4736): GC_FOR_ALLOC freed 131K, 12% free 21884K/24832K, paused 29ms, total 29ms
I/dalvikvm-heap( 4736): Grow heap (frag case) to 23.636MB for 95956-byte allocation
D/dalvikvm( 4736): GC_FOR_ALLOC freed 179K, 13% free 21918K/24928K, paused 21ms, total 21ms
I/dalvikvm-heap( 4736): Grow heap (frag case) to 23.715MB for 143930-byte allocation
D/dalvikvm( 4736): GC_FOR_ALLOC freed 252K, 13% free 21966K/25072K, paused 26ms, total 27ms
I/dalvikvm-heap( 4736): Grow heap (frag case) to 23.831MB for 215890-byte allocation
D/dalvikvm( 4736): GC_FOR_ALLOC freed 368K, 13% free 22039K/25284K, paused 21ms, total 21ms
I/dalvikvm-heap( 4736): Grow heap (frag case) to 24.005MB for 323830-byte allocation
D/dalvikvm( 4736): GC_FOR_ALLOC freed 566K, 14% free 22160K/25604K, paused 22ms, total 22ms
I/dalvikvm-heap( 4736): Grow heap (frag case) to 24.278MB for 485740-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4736): GC_FOR_ALLOC freed 864K, 15% free 22336K/26080K, paused 32ms, total 32ms
D/dalvikvm( 4736): GC_FOR_ALLOC freed 1279K, 14% free 22591K/26080K, paused 22ms, total 22ms
I/dalvikvm-heap( 4736): Grow heap (frag case) to 25.277MB for 1092904-byte allocation
D/dalvikvm( 4736): GC_CONCURRENT freed 1785K, 16% free 22977K/27148K, paused 1ms+2ms, total 32ms
D/dalvikvm( 4736): GC_FOR_ALLOC freed 267K, 16% free 22905K/27148K, paused 23ms, total 23ms
I/dalvikvm-heap( 4736): Grow heap (frag case) to 26.105MB for 1639352-byte allocation
D/dalvikvm( 4736): GC_CONCURRENT freed 1670K, 19% free 23485K/28752K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 4736): GC_FOR_ALLOC freed 1314K, 19% free 23549K/28752K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4736): Grow heap (frag case) to 27.515MB for 2459024-byte allocation
,D/dalvikvm( 4736): GC_CONCURRENT freed 230K, 18% free 25834K/31156K, paused 2ms+3ms, total 28ms
,D/dalvikvm( 4736): GC_CONCURRENT freed 4385K, 22% free 24554K/31156K, paused 2ms+4ms, total 47ms
,D/dalvikvm( 4736): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/dalvikvm-heap( 4736): Grow heap (frag case) to 29.670MB for 3688532-byte allocation
,D/dalvikvm( 4736): GC_CONCURRENT freed 2750K, 27% free 25569K/34760K, paused 2ms+5ms, total 40ms
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/dalvikvm( 4736): GC_FOR_ALLOC freed 870K, 27% free 25495K/34760K, paused 27ms, total 28ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  967): battery changed pluggedType: 2
,W/jxcore-log( 4736): Initializing JXcore engine
,W/jxcore-log( 4736): JXcore engine is ready
,D/dalvikvm( 4736): GC_CONCURRENT freed 377K, 20% free 28112K/34760K, paused 1ms+1ms, total 29ms
,D/dalvikvm( 4736): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/jxcore-log( 4736): Starting JXcore engine
,W/jxcore-log( 4736): Platform android
W/jxcore-log( 4736): 
,W/jxcore-log( 4736): Process ARCH arm
W/jxcore-log( 4736): 
,I/ActivityManager(  967): Killing 4181:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
,I/GAV2    ( 4665): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4736): JXcore Cordova bridge is ready!
I/jxcore-log( 4736): 
,W/jxcore-log( 4736): JXcore engine is started
,I/Choreographer( 4736): Skipped 150 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4736): Toggling radios to true
I/jxcore-log( 4736): 
,D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44e4b070:true
,D/BluetoothAdapter( 4736): enable(): BT is already enabled..!
D/WifiService(  967): New client listening to asynchronous messages
D/WifiStateMachine(  967): handleMessage: E msg.what=131145
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doBoolean: DISCONNECT
,I/jxcore-log( 4736): Radios toggled
I/jxcore-log( 4736): 
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2019): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2019): wlan0: Cancelling scan request
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2019): TDLS: Tear down peers
,D/wpa_supplicant( 2019): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  967): setWifiEnabled: true pid=4736, uid=10304
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  967): disconnect pid=4736, uid=10304
D/WifiService(  967): reconnect pid=4736, uid=10304
,D/wpa_supplicant( 2019): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2019): wlan0: Deauthentication notification
,D/wpa_supplicant( 2019): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2019): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2019): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2019): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2019): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2019): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb797ad6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2019): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2019): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): transitionTo: destState=DisconnectingState
,D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
W/Settings(  967): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
,D/WifiStateMachine(  967): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131146
D/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiNative-wlan0(  967): doBoolean: RECONNECT
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2019): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2019): Fast associate: Old scan results
D/wpa_supplicant( 2019): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2019): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2019): wlan0: nl80211: scan request
,D/wpa_supplicant( 2019): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2019): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2019): wlan0: nl80211: Scan trigger
,D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147460
D/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): Network connection lost
D/WifiStateMachine(  967): Stopping DHCP and clearing IP
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2019): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2019): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2019): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
,D/DhcpStateMachine(  967): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  967): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/WifiHS20(  967): hidePasspointNotification off =false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
,E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/QCNEA   (  401): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  401): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  401): |CAC| updateNetCfgInfo
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC|                   Netconfig               
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  401): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  401): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  401): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  401): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  401): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  401): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| Received bssid= 
D/QCNEA   (  401): |CAC| net type = 3
V/QCNEA   (  401): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  401): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  401): |CAC| 	ssid           =NG700
V/QCNEA   (  401): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  401): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  401): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  401): |CAC| dispatchNetCfg: updating:0xb89e68dc
D/QCNEA   (  401): |CAC| readCallback: read len:0, ret:-1, errno:11
D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: DisconnectedState
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  967): Attempting to switch to mobile
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4823 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  967): handleMessage: X
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
V/        (  264): RouteController
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,V/        (  264): RouteController
D/HyLog   ( 4823): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4823): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4823): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,W/NetworkManagementService(  967): route cmd failed: 
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
D/NetUtils(  967): android_net_utils_resetConnections in env=0x62819b18 clazz=0x6c600001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1551): Read error: ssl=0x644afbb0: I/O error during system call, Connection timed out
V/NativeCrypto( 1551): SSL shutdown failed: ssl=0x644afbb0: I/O error during system call, Broken pipe
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/PCSuite ( 4823): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 4823): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4823): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4860 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  967): Killing 3168:android.process.media/u0a23 (adj 15): empty #17
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4860): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 4860): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4860): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4860): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4860): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4860): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4860): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4860): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4860): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4860): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  967): Killing 3966:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  967): StoppedState
,I/ConfigService( 1551): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4066): onReceive
,D/AppUp4:CustFacade( 4066): Context : android.app.ReceiverRestrictedContext@42817340
D/AppUp4:CustFacade( 4066): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4066): isOpenOperator : true
,D/AppUp4:CustFacade( 4066): isPhone : true
,I/LicenseContentProvider( 3011): start selecting data
,D/SIMObserver( 3011): simInfo1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
I/AppUp4:EulaManager( 4066): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4066): begin check event
I/AppUp4:CustModeStarterReceiver( 4066): Event For GoodConnectivity
,I/ActivityManager(  967): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4886 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 4886): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4886): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4886): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2019): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2019): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2019): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 2019): nl80211: Survey data missing
D/wpa_supplicant( 2019): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2019): wlan0: BSS: Add new id 7 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Add new id 8 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 2019): wlan0: New scan results available
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 2019): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2019): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2019): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2019): WPS: AP 64:7c:34:12:7f:81 type 0 added
,D/wpa_supplicant( 2019): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2019): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2019): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2019): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2019): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2019): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 38:f8:89:11:e9:11]
D/wpa_supplicant( 2019): WPS: AP[4] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2019): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2019): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2019): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2019): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2019): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2019): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2019): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb797c5a8  current_ssid=0x0
D/wpa_supplicant( 2019): scard is not null..
D/wpa_supplicant( 2019): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
,D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2019): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2019): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2019): wlan0: Cancelling scan request
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2019): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2019): RSN: PMKSA cache search - network_ctx=0xb797c5a8 try_opportunistic=0
D/wpa_supplicant( 2019): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2019): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2019): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2019): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2019): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2019): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2019): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2019): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2019): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2019): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2019): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2019): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2019): nl80211: Unsubscribe mgmt frames handle 0xb797b590 (mode change)
,D/wpa_supplicant( 2019): nl80211: Subscribe to mgmt frames with non-AP handle 0xb797b590
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb797b590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb797b590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb797b590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb797b590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0d
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb797b590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb797b590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb797b590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb797b590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=1): 06
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb797b590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 0a 07
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb797b590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 0a 11
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/wpa_supplicant( 2019): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2019):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019):   * freq=2412
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/wpa_supplicant( 2019):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2019):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019):   * Auth Type 0
D/wpa_supplicant( 2019):   * WPA Versions 0x2
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2019): nl80211: Connect request send successfully
D/wpa_supplicant( 2019): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2019): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2019): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2019): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2019): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
V/DownloadManager( 4886): DownloadService onCreate
D/EAS     ( 4644): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4644): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4886): in removeSpuriousFiles
D/eas_req ( 4644): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4886): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@4283ace8 on behalf of 4886
I/DownloadManager( 4886): in trimDatabase
V/DownloadManager( 4886): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4886): DownloadService onStartCommand
V/DownloadManager( 4886): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4374): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4374): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@42840280 on behalf of 4886
V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@42842018 on behalf of 4886
I/LgeMiscReceiver( 4374): networkInfo.isConnected() = false
W/linker  ( 4644): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2019): nl80211: Connect event
D/wpa_supplicant( 2019): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2019): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2019): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2019): wlan0: Association info event
D/wpa_supplicant( 2019): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2019): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2019): wlan0: freq=2412 MHz
D/wpa_supplicant( 2019): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2019): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2019): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2019): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): scard is not null..
D/wpa_supplicant( 2019): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2019): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2019): TDLS: Remove peers on association
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2019): EAPOL: enable timer tick
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2019): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2019): wlan0: Cancelling scan request
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/HtmlEditor( 4644): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4644): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4644): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
V/DownloadManager( 4886): DownloadService onDestroy
I/dalvikvm( 4644): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4644): register_HtmlEditor, Success
D/HtmlEditor( 4644): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4915 uid=10052 gids={50052, 3003}
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
D/HyLog   ( 4915): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4915): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4915): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/HubEmail( 4644): JNI_OnLoad()
I/HubEmail( 4644): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4644): registerNatives()
I/HubEmail( 4644): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4644): registerNativeMethods()
I/HubEmail( 4644): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 2019): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 2b e8 e3 00 a7 b8 55 7b a0 62 61 18 65 8c 6d ...
D/wpa_supplicant( 2019): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2019): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2019): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2019): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2019): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2019):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2019):   key_nonce - hexdump(len=32): 2b e8 e3 00 a7 b8 55 7b a0 62 61 18 65 8c 6d 63 5d 28 9c 80 ce 3d 78 f5 b6 a3 ff a3 92 da 51 96
D/wpa_supplicant( 2019):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 2b e8 e3 00 a7 b8 55 7b a0 62 61 18 65 8c 6d ...
D/wpa_supplicant( 2019): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2019): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2019): Get randomness: len=32 entropy=9
D/wpa_supplicant( 2019): WPA: Renewed SNonce - hexdump(len=32): d3 f6 c8 39 e6 9f da 0d 36 9b bb d6 a7 8a a1 92 a5 58 c6 f0 86 c1 3c e5 90 a9 a2 08 6c 61 c8 4d
D/wpa_supplicant( 2019): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): WPA: Nonce1 - hexdump(len=32): d3 f6 c8 39 e6 9f da 0d 36 9b bb d6 a7 8a a1 92 a5 58 c6 f0 86 c1 3c e5 90 a9 a2 08 6c 61 c8 4d
D/wpa_supplicant( 2019): WPA: Nonce2 - hexdump(len=32): 2b e8 e3 00 a7 b8 55 7b a0 62 61 18 65 8c 6d 63 5d 28 9c 80 ce 3d 78 f5 b6 a3 ff a3 92 da 51 96
D/wpa_supplicant( 2019): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2019): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2019): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2019): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2019): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2019): WPA: Derived Key MIC - hexdump(len=16): 9d b5 93 52 fb 8d 36 2d 83 e3 e3 07 72 b6 44 62
D/wpa_supplicant( 2019): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 d3 f6 c8 39 e6 9f da 0d 36 9b bb d6 a7 8a a1 ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
,I/ActivityManager(  967): Killing 4354:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4915): [loadRssi] File not exist 
V/LGRssiData( 4915): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4915): [loadFeatureFromXml] *** start feature loading from xml
D/wpa_supplicant( 2019): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 2b e8 e3 00 a7 b8 55 7b a0 62 61 18 65 8c 6d ...
D/wpa_supplicant( 2019): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2019): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2019): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2019): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2019):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2019):   key_nonce - hexdump(len=32): 2b e8 e3 00 a7 b8 55 7b a0 62 61 18 65 8c 6d 63 5d 28 9c 80 ce 3d 78 f5 b6 a3 ff a3 92 da 51 96
D/wpa_supplicant( 2019):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_rsc - hexdump(len=8): 68 33 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_mic - hexdump(len=16): 21 a2 13 b6 ae 9c eb 4e ff 47 6b b0 d7 d2 e9 b8
D/wpa_supplicant( 2019): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 2b e8 e3 00 a7 b8 55 7b a0 62 61 18 65 8c 6d ...
D/wpa_supplicant( 2019): RSN: encrypted key data - hexdump(len=56): 6f 6e 54 66 c5 0d af dd 97 8b 21 4c 49 1d 5e a0 6b af c5 15 a4 1f 75 9d 8e 6e 98 02 28 da 06 c2 ...
D/wpa_supplicant( 2019): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2019): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2019): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2019): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 22 85 ...
D/wpa_supplicant( 2019): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2019): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2019): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2019): WPA: Derived Key MIC - hexdump(len=16): dc 71 60 d2 ed a5 a0 d9 a9 60 68 09 5e cc ad 08
D/wpa_supplicant( 2019): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2019): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb797bc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2019):    addr=c0:ff:d4:d3:aa:48
W/BaseRuntimeLoader( 4915): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4915): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4915): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4915): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2019): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2019): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2019): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2019): WPA: RSC - hexdump(len=6): 68 33 00 00 00 00
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f0803a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2019):    broadcast key
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
V/TelephonyAutoProfiling( 4915): [getMatchedProfile] selected file : /cust/config/featureset.xml
I/wpa_supplicant( 2019): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2019): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2019): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2019): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2019): EAPOL authentication completed successfully
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
V/TelephonyAutoProfiling( 4915): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4915): [getValue] FEATURE key : vzw_roaming_state, value : null
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection established
D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2019): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
I/WifiServiceExtension(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/MobileConnectivityChangeReceiver( 4915): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4915): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4915): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4915): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  967): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-13ms what=147462 obj=android.net.wifi.StateChangeResult@44e44418 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-8ms what=147462 obj=android.net.wifi.StateChangeResult@4427d900 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-9ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 2019): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196612
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4930 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  967): Killing 4565:com.android.defcontainer/u0a4 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/HyLog   ( 4930): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4930): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4930): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4943 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  967): Killing 4602:com.google.android.partnersetup/u0a9 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4943): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4943): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4943): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2896): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  967): Killing 4631:com.lge.bnr/1000 (adj 15): empty #17
,D/LGDMClient( 2896): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2019): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2019): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2019): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
,D/WifiStateMachine(  967): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-4ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431a8a08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431a8a08 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4956 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
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
D/WifiStateMachine(  967): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2019): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2019): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2019): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): DHCP successful
,D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  967): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState enter
,D/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,E/Parcel  (  401): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  967): CaptivePortalCheckState enter
,D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  967): handleMessage: X
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  967): handleMessage: E msg.what=131092
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
E/Parcel  (  401): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
D/HyLog   ( 4956): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/HyLog   ( 4956): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4956): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
,D/LGDMSGCM( 4956): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm(  967): GC_EXPLICIT freed 23435K, 49% free 29758K/57864K, paused 3ms+8ms, total 132ms
,D/DhcpStateMachine(  967): DHCP request on wlan0
D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/QCNEA   (  401): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  401): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  401): |CAC| updateNetCfgInfo
V/QCNEA   (  401): |CAC| *********************************************
,V/QCNEA   (  401): |CAC|                   Netconfig               
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  401): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  401): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  401): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  401): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  401): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  401): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  401): |CAC| net type = 1
V/QCNEA   (  401): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  401): |CAC| Received ssid= NG700
V/QCNEA   (  401): |CAC| 	ssid           =NG700
V/QCNEA   (  401): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  401): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  401): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  401): |CAC| dispatchNetCfg: updating:0xb89e68dc
,D/QCNEA   (  401): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4986 uid=10101 gids={50101, 1028, 1015, 3003}
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 4986): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4986): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4986): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1921): Checking schedule, now: 1452269602075 next: 1452269544445
,I/CheckinService( 1921): active receiver: enabled
,I/CheckinService( 1921): Preparing to send checkin request
,I/EventLogService( 1921): Accumulating logs since 1452269511875
,I/NFS     ( 4986): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4986): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4986): intf.getDisplayName() = lo
I/Wireless_Storage( 4986): intf.getDisplayName() = sit0
I/Wireless_Storage( 4986): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4986): intf.getDisplayName() = teql0
,I/Wireless_Storage( 4986): intf.getDisplayName() = wlan0
,D/NFS     ( 4986): interface name:wlan0 name:wlan0
D/NFS     ( 4986): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4986): interface name:wlan0 name:wlan0
D/NFS     ( 4986): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4986): CONNECT : WIFI_CONNECT
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5006 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4231:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/HyLog   ( 5006): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5006): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5006): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
,I/CheckinRequestBuilder( 1921): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1921): Failed to find provider info for com.google.android.wearable.settings
,W/GAV2    ( 5006): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 1551): GC_EXPLICIT freed 952K, 29% free 17811K/24832K, paused 3ms+3ms, total 25ms
,V/WebViewChromium( 5006): Binding Chromium to the main looper Looper (main, tid 1) {42801548}
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/chromium( 5006): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5006): Initializing chromium process, renderers=0
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 5006): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5006): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5006): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5006): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5006): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5006): Remote Branch: 
I/Adreno-EGL( 5006): Local Patches: 
I/Adreno-EGL( 5006): Reconstruct Branch: 
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x42c5e280: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1921): awaiting user notification for token
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/NSApplication( 5006): Starting up...
I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5039 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5039): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5039): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5039): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): Killing 4246:com.android.gallery3d/u0a27 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4860): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4860): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,W/dalvikvm( 5039): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5039): VFY: replacing opcode 0x60 at 0x000b
,D/QRemote ( 4860): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/dalvikvm( 5039): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5039): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5039): VFY: replacing opcode 0x62 at 0x005e
,I/QRemote ( 4860): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/MultiDex( 5039): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5039): install
,D/QRemote ( 4860): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4860): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/MultiDex( 5039): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/PCSuite ( 4823): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4823): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/MultiDex( 5039): loading existing secondary dex files
D/QRemote ( 4860): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4860): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4860): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4860): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/MultiDex( 5039): load found 3 secondary dex files
,I/MultiDex( 5039): install done
,D/dalvikvm( 5039): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 5039): VFY: unable to resolve instance field 61
D/dalvikvm( 5039): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 5039): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5039): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5039): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5039): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5039): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5039): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5039): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5039): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5039): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428086f8
D/dalvikvm( 5039): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428086f8
,D/dalvikvm( 5039): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428086f8, skipping init
,D/dalvikvm( 5039): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428086f8
D/dalvikvm( 5039): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428086f8
,V/JNIHelp ( 5039): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 5039): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428086f8
,D/dalvikvm( 5039): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428086f8
D/dalvikvm( 5039): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428086f8
,D/dalvikvm( 5039): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428086f8
,I/ProviderInstaller( 5039): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1551): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1551): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1551): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1921): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1753): callingUid 10006, callindPid: 1753
,E/MDM     ( 1427): [61] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 5039): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5039): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5039): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1921): Restart initialization of location
,I/dalvikvm( 5039): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5039): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5039): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  272): Instantiating CDM.
,I/WVCdm   (  272): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  272): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  272): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  272): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f2f000
,E/DrmWidevineDash(  272): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f2f000
,D/DrmWidevineDash(  272): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  272): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  272): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  272): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  272): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  272): CdmEngine::OpenSession
,D/DrmWidevineDash(  272): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  272): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,E/BatteryObserver( 1158): usb Uevent not necessary.
,D/DrmWidevineDash(  272): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GetDeviceID...
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  272): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateNonce. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/DrmWidevineDash(  272): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  272): PrepareKeyRequest: nonce=2508694644
D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
D/WifiController(  967): battery changed pluggedType: 2
,D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  967): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/dalvikvm( 5039): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429f5548
D/dalvikvm( 5039): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429f5548
,D/dalvikvm( 5039): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429f5548, skipping init
D/wpa_supplicant( 2019): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2019): EAPOL: disable timer tick
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  272): CdmEngine::CloseSession
,D/DrmWidevineDash(  272): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/GCM     ( 1551): Connected
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1551): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 5039): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5065): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 5039): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5039): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 76ms
,I/Adreno-EGL( 5039): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5039): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5039): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5039): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5039): Remote Branch: 
I/Adreno-EGL( 5039): Local Patches: 
I/Adreno-EGL( 5039): Reconstruct Branch: 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WVCdm   (  272): CdmEngine::OpenSession
,D/DrmWidevineDash(  272): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  272): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  272): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  272): PrepareKeyRequest: nonce=3859408642
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/ProcessCpuTracker(  967): Skipping unknown process pid 5079
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  272): CdmEngine::CloseSession
,D/DrmWidevineDash(  272): calling OEMCrypto_CloseSession. SID = 1,
,D/DrmWidevineDash(  272): OEMCrypto_CloseSession returns 0
,W/Settings( 5039): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,I/Adreno-EGL( 5039): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5039): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5039): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5039): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5039): Remote Branch: 
I/Adreno-EGL( 5039): Local Patches: 
I/Adreno-EGL( 5039): Reconstruct Branch: 
,I/Adreno-EGL( 5039): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5039): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5039): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5039): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5039): Remote Branch: 
I/Adreno-EGL( 5039): Local Patches: 
I/Adreno-EGL( 5039): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1921): Classify the device as Phone.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  967): RunningState
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/CheckinTask( 1921): Sending checkin request (11468 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1921): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1921): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x42985258: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1921): awaiting user notification for token
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1921): Classify the device as Phone.
,I/CheckinTask( 1921): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1921): Checking schedule, now: 1452269604520 next: 1452847000516
,I/CheckinService( 1921): active receiver: disabled
,D/GCM     ( 1551): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4066): onReceive
,D/AppUp4:CustFacade( 4066): Context : android.app.ReceiverRestrictedContext@42817340
D/AppUp4:CustFacade( 4066): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4066): isOpenOperator : true
,D/AppUp4:CustFacade( 4066): isPhone : true
,I/LicenseContentProvider( 3011): start selecting data
,D/SIMObserver( 3011): simInfo1
,I/AppUp4:EulaManager( 4066): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4066): begin check event
I/AppUp4:CustModeStarterReceiver( 4066): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4066): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4066): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4066): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4066): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4066): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4644): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4886): DownloadService onCreate
,D/EAS     ( 4644): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4644): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4374): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4374): action = android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 4644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4886): in removeSpuriousFiles
,V/DownloadManager( 4886): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@428482d0 on behalf of 4886
,I/DownloadManager( 4886): in trimDatabase
,V/DownloadManager( 4886): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@428493a0 on behalf of 4886
,V/DownloadManager( 4886): DownloadService onStartCommand
,I/LgeMiscReceiver( 4374): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4915): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4915): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4886): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@4284be78 on behalf of 4886
,V/DownloadManager( 4886): DownloadService onDestroy
,D/LGDMClient( 2896): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2896): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2896): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2896): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2896): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2896): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMSGCM( 4956): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2896): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/NFS     ( 4986): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4986): CONNECT : WIFI_CONNECT
W/ContextImpl( 4956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4066): onReceive
D/AppUp4:CustFacade( 4066): Context : android.app.ReceiverRestrictedContext@42817340
D/AppUp4:CustFacade( 4066): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4066): isOpenOperator : true
,D/AppUp4:CustFacade( 4066): isPhone : true
,I/LicenseContentProvider( 3011): start selecting data
,D/SIMObserver( 3011): simInfo1
,I/AppUp4:EulaManager( 4066): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4066): begin check event
,I/AppUp4:CustModeStarterReceiver( 4066): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4886): DownloadService onCreate
D/EAS     ( 4644): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4644): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4886): in removeSpuriousFiles
,V/DownloadManager( 4886): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@42850220 on behalf of 4886
I/LgeMiscReceiver( 4374): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4374): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4374): networkInfo.isConnected() = true
D/PhoneState( 4374): setPdpRejectCasuse : false
,W/Settings( 4644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4886): in trimDatabase
,V/DownloadManager( 4886): DownloadService onStartCommand
D/MobileConnectivityChangeReceiver( 4915): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4915): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4886): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4886): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@42853700 on behalf of 4886
,V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@428523e8 on behalf of 4886
,V/DownloadManager( 4886): DownloadService onDestroy
,D/LGDMClient( 2896): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4956): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2896): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2896): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2896): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
I/NFS     ( 4986): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4986): CONNECT : WIFI_CONNECT
D/LGDMClient( 2896): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2896): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2896): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm(  967): GC_EXPLICIT freed 2159K, 49% free 29672K/57864K, paused 3ms+6ms, total 84ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4736): Test app app.js loaded
I/jxcore-log( 4736): 
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/chromium( 4736): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4066): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4066): onReceive
,D/AppUp4:CustFacade( 4066): Context : android.app.ReceiverRestrictedContext@42817340
,D/AppUp4:CustFacade( 4066): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4066): isOpenOperator : true
,D/AppUp4:CustFacade( 4066): isPhone : true
,I/LicenseContentProvider( 3011): start selecting data
,D/SIMObserver( 3011): simInfo1
,I/AppUp4:EulaManager( 4066): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4066): begin check event
,I/AppUp4:CustModeStarterReceiver( 4066): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4644): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4886): DownloadService onCreate
,D/EAS     ( 4644): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4374): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4374): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4374): networkInfo.isConnected() = true
,D/PhoneState( 4374): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4915): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4915): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2896): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4956): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2896): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2896): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ContextImpl( 4956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/NFS     ( 4986): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4986): CONNECT : WIFI_CONNECT
I/DownloadManager( 4886): in removeSpuriousFiles
,V/DownloadManager( 4886): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@42857e20 on behalf of 4886
,W/Settings( 4644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/LGDMClient( 2896): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
I/DownloadManager( 4886): in trimDatabase
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGDMClient( 2896): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2896): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 4886): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@42859c90 on behalf of 4886
V/DownloadManager( 4886): DownloadService onStartCommand
V/DownloadManager( 4886): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2896): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@4285b988 on behalf of 4886
V/DownloadManager( 4886): DownloadService onDestroy
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/GAV2    ( 5006): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Killing 4265:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  967): Killing 4665:com.google.android.apps.docs/u0a73 (adj 15): empty #18
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5178 uid=10050 gids={50050, 3003, 1028, 1015}
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 3ms+11ms, total 79ms
,D/HyLog   ( 5178): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5178): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5178): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+10ms, total 49ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 5ms+2ms, total 21ms
,I/dalvikvm( 5178): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5178): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5178): VFY: replacing opcode 0x6e at 0x000b
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5178): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/HeadsetStateMachine( 1226): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.457108 Y: -0.441696 Z: 9.778336 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457108 .y:-0.441696 .z:9.778336
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
I/dalvikvm( 5178): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5178): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5178): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5178): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5178): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5178): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5178): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/Finsky  ( 5178): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5178): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5178): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5178): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 5178): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5178): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 5178): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5178): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5178): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5178): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5178): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5178): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 4886): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@42860bf0 on behalf of 5178
,I/dalvikvm( 5178): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5178): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5178): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5178): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 5178): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5178): VFY: replacing opcode 0x6e at 0x0049
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.459274 Y: -0.439667 Z: 9.780060 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459274 .y:-0.439667 .z:9.780060
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/Finsky  ( 5178): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5178): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5178): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5178): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm( 5178): Total arena pages for JIT: 11
,I/dalvikvm( 5178): Total arena pages for JIT: 12
I/dalvikvm( 5178): Total arena pages for JIT: 13
,I/dalvikvm( 5178): Total arena pages for JIT: 14
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5178): [456] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5178): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  967): Killing 4823:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5178): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5178): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5178): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5178): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Finsky  ( 5178): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5178): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1226): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1551): GC_EXPLICIT freed 1314K, 29% free 17810K/24832K, paused 1ms+2ms, total 22ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5178): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5178): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/Finsky  ( 5178): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5178): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1427): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0,
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5275 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/administrator(  967): Handling package changes for user 0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,E/SlideAside( 3798): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/SlideAside( 3798): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5275): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5275): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5275): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5275): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5275): MmsConfig.loadMmsSettings
,I/Babel   ( 5275): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 5275): MmsConfig.loadFromDatabase
I/MediaCodecList( 5275): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5275): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5275): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5275): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5275): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5275): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5275): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5275): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 5275): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5275): MmsConfig.loadFromResources
,W/Settings( 5275): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 5275): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5275): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5275): [loadRssi] File not exist 
V/LGRssiData( 5275): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5275): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5275): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5275): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5275): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:Utils( 4066): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 4066): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4066): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4066): onReceive
,D/AppUp4:CustFacade( 4066): Context : android.app.ReceiverRestrictedContext@42817340
D/AppUp4:CustFacade( 4066): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4066): isOpenOperator : true
,D/AppUp4:CustFacade( 4066): isPhone : true
,I/LicenseContentProvider( 3011): start selecting data
,D/SIMObserver( 3011): simInfo1
,I/AppUp4:EulaManager( 4066): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4066): begin check event
D/AppUp4:Utils( 4066): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4066): Event For Nothing, skip.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5321 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1226): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,V/GmsNetworkLocationProvi( 1427): DISABLE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HyLog   ( 5321): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5321): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5321): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/SystemConfig( 5321): BUILD Country: EU
,I/SystemConfig( 5321): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 4860:com.lge.qremote/u0a96 (adj 15): empty #17
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5337 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
,I/SystemConfig( 5321): systemFeature RCS result false
,D/SystemConfig( 5321): refreshRcsSupport() :false
I/ActivityManager(  967): Killing 4644:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 5337): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5337): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5337): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  967): Killing 4915:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/IcingCorporaProvider( 2702): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1921): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1921): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  967): Delaying start of: ServiceRecord{4332fff8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1921): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1921): GC_CONCURRENT freed 1844K, 22% free 19571K/24832K, paused 3ms+2ms, total 31ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  967): GC_EXPLICIT freed 1820K, 49% free 29863K/57864K, paused 2ms+9ms, total 92ms
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/IcingCorporaProvider( 2702): UpdateCorporaTask done [took 318 ms] updated apps [took 318 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-5ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  967): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV4    ( 5275): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.454254 Y: -0.435501 Z: 9.808655 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454254 .y:-0.435501 .z:9.808655
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.441788 Y: -0.439285 Z: 9.806747 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441788 .y:-0.439285 .z:9.806747
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
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
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9005 usec
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
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.443329 Y: -0.431717 Z: 9.807632 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443329 .y:-0.431717 .z:9.807632
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.453995 Y: -0.432007 Z: 9.799927 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453995 .y:-0.432007 .z:9.799927
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  370): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  967): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  967): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  967): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  967): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  967): proximitySensorChanged  positive = true
I/KnockOnPowerController(  967): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.439438 Y: -0.427811 Z: 9.802963 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.439438 .y:-0.427811 .z:9.802963
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.440201 Y: -0.424759 Z: 9.810989 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440201 .y:-0.424759 .z:9.810989
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.453156 Y: -0.426254 Z: 9.813919 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453156 .y:-0.426254 .z:9.813919
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.458862 Y: -0.430237 Z: 9.802780 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458862 .y:-0.430237 .z:9.802780
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@430128f0)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1142): notifyScreenOnLocked
D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
I/WindowManager(  967): No lock screen! windowToken=null
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb83e9450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.454910 Y: -0.430695 Z: 9.795868 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454910 .y:-0.430695 .z:9.795868
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132097
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2019): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2019): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
,V/SRS_Proc(  272): ParamSet string: screen_state=on
D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=on
V/voice   (  272): voice_set_parameters: enter: screen_state=on
,V/voice   (  272): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  272): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  272): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1158): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433029b0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1158): enqueuing start. mLedList.size()=2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1158): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1824): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 17:13:42
E/SlideAside( 3798): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3798): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
D/WeatherAncestor( 1824): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 17:13:42
D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
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
,D/qdlights( 1158): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1158): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 411ms
,D/qdlights( 1158): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1158): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1158): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1158): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1158): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 171, B = 171
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1158): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1158): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1158): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 147, B = 147
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1158): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1158): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1158): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1158): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1158): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 111, B = 111
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
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/qdlights( 1158): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 57, B = 57
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269622799, nextTick: 17234, mDrawingTime: 0
,D/qdlights( 1158): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1158): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1158): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1158): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 33, B = 33
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269622844, nextTick: 17188, mDrawingTime: 0
,D/qdlights( 1158): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 27, B = 27
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/qdlights( 1158): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 21, B = 21
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1158): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 15, B = 15
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
,D/GsmSST  ( 1452): Emergency Service
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WeatherService( 1824): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:13:42
,D/WeatherService( 1824): 2 : ACTION screen on
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1824): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:13:42
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1142): notifyScreenOffLocked
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3}
,D/qcom_sensors_hal(  967): hal_acquire_resources
,D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
,D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,I/LGImmersionVibrator(  967): Vibrator off
D/UsbSettings( 2632): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
,D/KeyguardViewManager( 1142): onScreenTurnedOff()
V/UsbSettings( 2632): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2632): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2632): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/WifiStateMachine(  967): handleScreenStateChanged: false
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
V/SRS_Proc(  272): ParamSet string: screen_state=off
,D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  272): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{42c50ec0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  967): CMD_SCREEN_OFF 
,D/WifiController(  967): shouldWifiStayAwake TRUE
V/audio_hw_primary(  272): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1158): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{42c50ec0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/EmotionalLed( 1158): RESTART MSG
,D/VolumeVibrator( 1158): clear
E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=2
D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
I/[LGHome]EVENT( 1490): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1824): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:13:43
,D/WeatherService( 1824): 2 : ACTION screen off
,D/WeatherService( 1824): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:13:43
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/NfcService( 1477): NFC-C OFF
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1465): [TangibleIO] LCD is off. Remove tangible if exist.
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,I/Sensors (  370): sns_pwr.c(320):releasing wakelock
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1452): getIsInUseVoLTE : false
D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1551): Vacuum at: now=1452269631456 tag=VacuumService
,I/GoogleURLConnFactory( 1551): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1551): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1551): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1551): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1551): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1551): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/Finsky  ( 5178): [456] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5178): [1] 5.onFinished: Installation state replication succeeded.
,W/Uploader( 1551):  no longer exists, so no auth token.
,W/Uploader( 1551): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ProcessCpuTracker(  967): Skipping unknown process pid 5492
,W/ProcessCpuTracker(  967): Skipping unknown process pid 5493
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269640041, nextTick: 59985, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269640059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269640377019847; DSPS: 5275938; Offset: 1452269479368169750
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269660378736818; DSPS: 5931355; Offset: 1452269479368147219
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269680380412070; DSPS: 6586770; Offset: 1452269479368144004
,D/wpa_supplicant( 2019): wlan0: BSS: Remove id 6 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 dc:4a:3e:0f:c2:f1]
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269700051, nextTick: 59981, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269700052, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269700382320605; DSPS: 7242192; Offset: 1452269479368160449
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269720383916274; DSPS: 7897604; Offset: 1452269479368169204
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269740385617360; DSPS: 8553020; Offset: 1452269479368161306
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269760033, nextTick: 59998, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269760034, nextTick: 59998, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269760387313186; DSPS: 9208436; Offset: 1452269479368148147
,I/jxcore-log( 4736): TAP version 13
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # multiplex can send data
I/jxcore-log( 4736): 
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269780388971043; DSPS: 9863850; Offset: 1452269479368158055
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 1 String should be length:200
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # basic
I/jxcore-log( 4736): 
,D/wpa_supplicant( 2019): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 7 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 8 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 38:f8:89:11:e9:11]
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269800390393275; DSPS: 10519257; Offset: 1452269479368145961
,D/dalvikvm( 2689): GC_CONCURRENT freed 7709K, 32% free 16981K/24832K, paused 3ms+4ms, total 59ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 2 sane
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # another
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 3 sane
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 4 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 5 null
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 6 (unnamed assert)
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 7 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 8 should not throw
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269820038, nextTick: 59966, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269820058, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269820392016861; DSPS: 11174670; Offset: 1452269479368152115
,I/LocationManagerService(  967): remove 433b6918
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/jxcore-log( 4736): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,D/dalvikvm( 2689): GC_CONCURRENT freed 1718K, 31% free 17311K/24832K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 2689): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/Mlt MonitorService( 2689): parseLastkmsg to dump
,I/jxcore-log( 4736): ok 9 (unnamed assert)
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 10 (unnamed assert)
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 11 should not throw
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 12 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 13 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 14 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # failed to get mobile documents path
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269840393697061; DSPS: 11830085; Offset: 1452269479368153849
,I/jxcore-log( 4736): ok 15 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4736): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 16 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 17 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 18 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #init should register the networkChanged event
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 19 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #startBroadcasting should throw on null device name
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 20 should throw
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 21 should throw
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 22 should throw
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #startBroadcasting should throw on NaN port
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 23 should throw
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #startBroadcasting should throw on negative port
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 24 should throw
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #startBroadcasting should throw on too large port
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 25 should throw
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4736): 
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269860395094293; DSPS: 12485491; Offset: 1452269479368147272
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 26 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 27 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 28 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 29 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 30 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 31 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269880025, nextTick: 60000, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269880070, nextTick: 59963, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269880396687254; DSPS: 13140903; Offset: 1452269479368153319
,I/jxcore-log( 4736): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 32 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 33 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 34 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 35 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269900398637612; DSPS: 13796327; Offset: 1452269479368150552
,I/jxcore-log( 4736): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x432b6b80: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5178): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5178): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5178): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5178): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5178): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5178): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5178): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5178): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 5178): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5178): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/jxcore-log( 4736): ok 36 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 37 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 38 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 39 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 40 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269920400289948; DSPS: 14451741; Offset: 1452269479368154939
,I/jxcore-log( 4736): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 41 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 42 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269940039, nextTick: 59981, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452269940047, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269940402267336; DSPS: 15107166; Offset: 1452269479368148684
,I/jxcore-log( 4736): ok 43 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ok 44 should be equal
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # setup
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 4736): 
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269960404158995; DSPS: 15762588; Offset: 1452269479368148253
,I/jxcore-log( 4736): # teardown
I/jxcore-log( 4736): 
,I/dalvikvm( 4736): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4736): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4736): Shutting down VM
,W/dalvikvm( 4736): threadid=1: thread exiting with uncaught exception (group=0x417c0e48)
E/AndroidRuntime( 4736): FATAL EXCEPTION: main
E/AndroidRuntime( 4736): Process: com.test.thalitest, PID: 4736
E/AndroidRuntime( 4736): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4736): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4736): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4736): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4736): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4736): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 4736): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/AndroidRuntime( 4736): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4736): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4736): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4736): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4736): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4736): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4736): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4736): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4736): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4736): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4736): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4736): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  967):   Force finishing activity com.test.thalitest/.MainActivity
,V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3 f}
,I/ActivityManager(  967): Killing 4930:com.android.chrome/u0a63 (adj 15): empty #17
,V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/Process ( 4736): Sending signal. PID: 4736 SIG: 9
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43316298 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  967): moveHomeStack:
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{43009af8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{43009af8 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{43009af8 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  967): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43009af8 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43009af8 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1490): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1490): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1452): getIsInUseVoLTE : false
D/WifiService(  967): Client connection lost with reason: 4
I/WindowState(  967): WIN DEATH: Window{44e166b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  967): Process com.test.thalitest (pid 4736) has died.
,I/[LGHome]LGActivityUtil( 1490): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1490): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1824): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 17:19:23
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{44f7a7e8 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43009af8 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43009af8 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1490): [Launcher.java:894:onPause()]onPause
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{43009af8 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{43009af8 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/WeatherAncestor( 1824): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 17:19:23
,D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
I/[LGHome]EVENT( 1490): [Launcher.java:4955:onStop()]onStop
,I/[LGHome]EVENT( 1490): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,W/Binder  ( 1301): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1301): java.lang.NullPointerException
W/Binder  ( 1301): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1301): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1301): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1301): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  967): IME STATUS OFF
W/InputMethodManagerService(  967): Got RemoteException sending setActive(false) notification to pid 4736 uid 10304
,D/dalvikvm( 2689): GC_CONCURRENT freed 2380K, 33% free 16852K/24832K, paused 8ms+1ms, total 19ms
,D/dalvikvm( 1142): GC_CONCURRENT freed 8310K, 11% free 70075K/78572K, paused 2ms+8ms, total 53ms
,D/dalvikvm( 1142): WAIT_FOR_CONCURRENT_GC blocked 55ms
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{43009af8 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{43009af8 u0 com.lge.launcher2/.Launcher t1} time:479476
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1490): GC_CONCURRENT freed 5637K, 9% free 60779K/66612K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 1490): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  967): Start proc com.lge.email for content provider com.lge.email/.providers.LGEmailContentProvider: pid=5851 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,D/HyLog   ( 5851): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 5851): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5851): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/LGEmail ( 5851): EmailContentProvider.query: uri=content://com.lge.providers.lgemail/account, projection=[accountID, userName, mailAddress, accountName, InboxID], selection=null, selectionArgs=null sortOrder=null, TABLE_NAMES=EAccountmatch is 0 (at LGEmailContentProvider.java query 492)[v:null]
,E/LGEmail ( 5851): Email Not Started (at LGEmailContentProvider.java query 509)[v:null]
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/LGEmail ( 5851): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,D/LGEmail ( 5851): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@427fe0f0 time:479800
,W/BaseRuntimeLoader( 5851): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5851): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5851): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5851): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1490): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452269980405059681; DSPS: 16417977; Offset: 1452269479368163930
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270000028, nextTick: 59996, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270000052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270000406439527; DSPS: 17073382; Offset: 1452269479368170485
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270020408324248; DSPS: 17728804; Offset: 1452269479368163116
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270040408750882; DSPS: 18384178; Offset: 1452269479368162504
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270060045, nextTick: 59983, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270060048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270060409669979; DSPS: 19039568; Offset: 1452269479368166073
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270080410975715; DSPS: 19694971; Offset: 1452269479368159553
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270100411843560; DSPS: 20350359; Offset: 1452269479368172906
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270120059, nextTick: 59971, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270120060, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270120412513787; DSPS: 21005741; Offset: 1452269479368171746
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270140413846315; DSPS: 21661145; Offset: 1452269479368161501
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270160414730795; DSPS: 22316534; Offset: 1452269479368160971
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270180035, nextTick: 59993, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270180038, nextTick: 59994, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270180415725576; DSPS: 22971927; Offset: 1452269479368148672
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270200417626392; DSPS: 23627349; Offset: 1452269479368157398
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270220418491006; DSPS: 24282737; Offset: 1452269479368167520
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270240032, nextTick: 59987, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270240042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270240419412326; DSPS: 24938128; Offset: 1452269479368142795
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270260420760236; DSPS: 25593532; Offset: 1452269479368147932
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270280421621657; DSPS: 26248920; Offset: 1452269479368154861
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,E/Ads     ( 1921): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6189 uid=10068 gids={50068, 3003, 1028, 1015}
,D/HyLog   ( 6189): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6189): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6189): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GoogleURLConnFactory( 1921): Using platform SSLCertificateSocketFactory
,D/ActivityThread( 6189): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1551): GC_CONCURRENT freed 1708K, 28% free 18100K/24832K, paused 3ms+4ms, total 40ms
,D/dalvikvm( 1551): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm(  967): GC_EXPLICIT freed 2943K, 48% free 30242K/57864K, paused 5ms+13ms, total 160ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 127ms
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43d00858: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/SubscribedFeeds( 1921): Hard error
,D/SyncManager(  967): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, latestRunTime 805438, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  967): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, latestRunTime 805991, reason: Periodic
,W/GAV2    ( 6189): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  967): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6210 uid=10072 gids={50072, 3003}
,D/HyLog   ( 6210): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6210): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6210): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/AbstractGoogleClient( 6210): Application name is not set. Call Builder#setApplicationName.
,I/ActivityManager(  967): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6235 uid=10016 gids={50016, 3003, 1028, 1015}
,D/HyLog   ( 6235): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6235): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6235): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CalendarProvider2( 6235): Created com.android.providers.calendar.CalendarAlarmManager@4281c8a8(com.android.providers.calendar.CalendarProvider2@42813810)
,I/Gmail   ( 6189): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6189): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6189): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6189): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5341, normalSync: true
,I/Gmail   ( 6189): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x44a00430: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/CalendarSyncAdapter( 6210): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 6210): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 6210): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 6210): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 6210): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:836)
E/CalendarSyncAdapter( 6210): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:412)
E/CalendarSyncAdapter( 6210): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:345)
E/CalendarSyncAdapter( 6210): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:463)
E/CalendarSyncAdapter( 6210): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 6210): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 6210): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 6210): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 6210): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 6210): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 6210): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 6210): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 6210): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 6210): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 6210): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 6210): 	... 12 more
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x431812f8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/SyncManager(  967): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, latestRunTime 805549, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  967): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, latestRunTime 806397, reason: Periodic
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x4302c3d0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/SyncManager(  967): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, latestRunTime 805540, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  967): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, latestRunTime 806501, reason: Periodic
I/ActivityManager(  967): Killing 4956:com.lge.lgdmsgcm/1000 (adj 15): empty #17
I/ActivityManager(  967): Killing 4943:com.lge.drmservice/u0a66 (adj 15): empty #18
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/SyncAdapterService( 5006): Ignoring sync request for non-current account
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x4480f008: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/PeopleSync( 1921): onPerformSync() [5005f081]
D/ContactsSyncAdapter( 1551): innerSync failed
D/ContactsSyncAdapter( 1551): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1551): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1551): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1551): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1551): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1551): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1551): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1551): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
D/ContactsSyncAdapter( 1551): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1551): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
D/ContactsSyncAdapter( 1551): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
D/ContactsSyncAdapter( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,D/SyncManager(  967): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, latestRunTime 805563, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  967): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, latestRunTime 806649, reason: Periodic
,I/ActivityManager(  967): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6268 uid=10107 gids={50107, 3003, 1028, 1015}
,D/HyLog   ( 6268): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6268): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6268): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/MusicStore( 6268): Database version: 91
,W/ContextImpl( 6268): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/BaseRuntimeLoader( 6268): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6268): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6268): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6268): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/ContextImpl( 6268): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PeopleDatabaseHelper( 1921): cleanUpNonGplusAccounts done.
,D/dalvikvm(  967): GC_EXPLICIT freed 3664K, 49% free 29811K/57864K, paused 4ms+11ms, total 150ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/MediaRouter( 6268): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/dalvikvm( 1551): GC_EXPLICIT freed 1547K, 28% free 18000K/24832K, paused 11ms+12ms, total 63ms
,I/CalendarProvider2( 6235): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6235): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  967): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6300 uid=10015 gids={50015, 3003, 1028, 1015}
,I/PeopleSync( 1921): Setting subscription: result=true [5005f081]
,D/HyLog   ( 6300): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6300): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6300): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PeopleSync( 1921): Starting sync, feed=null [5005f081]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Config  ( 6300): LGCalendar ver.4.2.6
,I/Config  ( 6300): start check model
,I/Config  ( 6300): start check native_ca
,E/Config  ( 6300): [setCountryAndOperator] Operator=OPEN, Country=EU
,I/ConfigStore( 6268): Config Database version: 1
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/BaseAppContext( 1921): Using Auth Proxy for data requests.
,W/BaseAppContext( 1921): Using Auth Proxy for data requests.
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x44e0f9a0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/MusicSyncAdapter( 6268): Sync failed due to an authentication issue.
,D/SyncManager(  967): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, latestRunTime 805577, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/AlertReceiver( 6300): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/SyncManager(  967): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, latestRunTime 807459, reason: Periodic
I/ActivityManager(  967): Killing 4986:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/InitNotificationRingtoneService( 6300): Start InitializeAlertRingtoneService.onHandleIntent
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/AlertUtils( 6300): Flushing old alerts from shared prefs table
,W/BaseAppContext( 1921): Using Auth Proxy for data requests.
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0,
,D/AlertService( 6300): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/AlertService( 6300): Beginning updateAlertNotification
,D/CalendarWidget( 6300): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,I/PeopleSync( 1921): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
I/ActivityManager(  967): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6332 uid=10063 gids={50063, 3003, 1028, 1015}
,I/InitNotificationRingtoneService( 6300): internal content query returns 1 results.
,I/InitNotificationRingtoneService( 6300): Found default schedule notification : Schedule.ogg(id:42)
,I/InitNotificationRingtoneService( 6300): set default noti to content://media/internal/audio/media/42
,I/InitNotificationRingtoneService( 6300): End InitializeAlertRingtoneService.onHandleIntent
,D/AlertService( 6300): No fired or scheduled alerts
D/HyLog   ( 6332): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6332): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6332): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/ContextImpl( 6268): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/DelayedSyncController( 6332): Delaying sync.
,W/ContextImpl( 6268): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/ActivityManager(  967): Killing 5039:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CalendarWidget( 6300): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 6300): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,W/ContextImpl( 6268): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ArtDownloadService( 6268): Setting cache size 0
,W/ArtDownloadService( 6268): Setting cache size 0
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/CacheService( 6268): onCreate
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/CacheService( 6268): onBind
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/ContextImpl( 6268): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/MusicLeanback( 6268): Conditions not met for autocaching.
,I/MusicLeanback( 6268): Stop autocaching.
,I/PeopleSync( 1921): Sync finished, successful=false, took 148ms
,D/CacheService( 6268): onDestroy
,W/BaseAppContext( 1921): Using Auth Proxy for data requests.
,W/BaseAppContext( 1921): Using Auth Proxy for data requests.
,I/PeopleSync( 1921): Cannot authenticate [5005f081]
I/PeopleSync( 1921): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 1921): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 1921): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 1921): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 1921): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 1921): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 1921): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 1921): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 1921): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 1921): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 1921): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 1921): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 1921): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 1921): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 1921): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 1921): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 1921): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 1921): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 1921): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
I/ActivityManager(  967): Killing 3011:com.lge.eula/1000 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityThread( 4066): Removing dead content provider:android.content.ContentProviderProxy@4281da40
,W/BaseAppContext( 1921): Using Auth Proxy for data requests.
,W/BaseAppContext( 1921): Using Auth Proxy for data requests.
,W/BaseAppContext( 1921): Using Auth Proxy for data requests.
,W/BaseAppContext( 1921): Using Auth Proxy for data requests.
,I/PeopleSync( 1921): ***Sync finished***, duration: 1085 [5005f081]
,D/SyncManager(  967): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, latestRunTime 805572, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,W/BaseAppContext( 1921): Using Auth Proxy for data requests.
,D/SyncManager(  967): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, latestRunTime 807743, reason: Periodic
,I/ActivityManager(  967): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6363 uid=10073 gids={50073, 3003, 1028, 1015}
,D/HyLog   ( 6363): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6363): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6363): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 42K, 34% free 16472K/24832K, paused 2ms+3ms, total 31ms
,I/ActivityManager(  967): Killing 5275:com.google.android.talk/u0a77 (adj 15): empty #17
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 26ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 25ms
,I/ActivityManager(  967): Start proc com.lge.app.richnote for service com.lge.app.richnote/.sync.syncadapter.GoogleDriveSyncService: pid=6378 uid=10034 gids={50034, 3003, 1028, 1015}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6378): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6378): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6378): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/SyncAdapter( 6378): onPerformSync in richnote account name thalitester@gmail.com
,I/ActivityManager(  967): Killing 4066:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager(  967): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=6392 uid=10124 gids={50124, 3003, 1028, 1015, 3002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6392): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6392): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6392): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/CalendarWidget( 6300): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 6300): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/GAV2    ( 6363): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/WifiService(  967): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@4310b010}
,D/dalvikvm( 1551): GC_EXPLICIT freed 648K, 28% free 18004K/24832K, paused 2ms+5ms, total 42ms
,W/BaseRuntimeLoader( 6392): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6392): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6392): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6392): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/dalvikvm(  967): GC_EXPLICIT freed 1643K, 49% free 29826K/57864K, paused 4ms+11ms, total 150ms
,D/PlayMovies( 6392): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,E/DataScheduler( 6363): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/MediaRouter( 6392): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PlayMovies( 6392): MediaRouteManager.maybeRestoreRoute:188 sessionRestore routeId: 
,D/PlayMovies( 6392): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PlayMovies( 6392): TransferService.onCreate:52 creating transfer service
,D/PlayMovies( 6392): MediaRouteManager.onRouteAdded:140 new route added android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE
,D/PlayMovies( 6392): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1921): GC_EXPLICIT freed 1457K, 21% free 19677K/24832K, paused 2ms+4ms, total 47ms
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.videos, service: oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x430b6b00: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,E/PlayMovies( 6392): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:70 Cannot get user auth
E/PlayMovies( 6392): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 6392): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 6392): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 6392): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:60)
E/PlayMovies( 6392): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:183)
E/PlayMovies( 6392): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 6392): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:223)
E/PlayMovies( 6392): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,E/PlayMovies( 6392): AccountManagerWrapper.blockingAuthenticate:165 Authentication failed
E/PlayMovies( 6392): com.google.android.videos.accounts.AccountManagerWrapper$AuthTokenException: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 6392): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:71)
E/PlayMovies( 6392): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:183)
E/PlayMovies( 6392): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 6392): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:223)
E/PlayMovies( 6392): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/PlayMovies( 6392): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 6392): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 6392): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 6392): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:60)
E/PlayMovies( 6392): 	... 4 more
,D/SyncManager(  967): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, latestRunTime 805609, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  967): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, latestRunTime 808681, reason: Periodic
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/ActivityManager(  967): Killing 5321:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/GCoreUlr( 1427): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1427): Using Auth Proxy for data requests.
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,E/GCoreUlr( 1427): 
E/GCoreUlr( 1427): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1427): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1427): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1427): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1427): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1427): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1427): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1427): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1427): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1427): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1427): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1427): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1427): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1427): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1427): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1427): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/SyncManager(  967): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, latestRunTime 805614, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  967): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, latestRunTime 808854, reason: Periodic
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: writely
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> writely without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,E/HttpIssuerBase( 6363): Attempt to consume entity of HttpIssuer when no request is executing.
,E/HttpIssuerBase( 6363): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 6363): java.io.IOException
E/HttpIssuerBase( 6363): 	at Eo.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 6363): 	at DS.b(DefaultAuthenticatedHttpIssuer.java:148)
E/HttpIssuerBase( 6363): 	at Pm.a(AccountMetadataUpdater.java:226)
E/HttpIssuerBase( 6363): 	at Pm.a(AccountMetadataUpdater.java:139)
E/HttpIssuerBase( 6363): 	at Qr.a(LegacySyncManager.java:776)
E/HttpIssuerBase( 6363): 	at Qr.a(LegacySyncManager.java:541)
E/HttpIssuerBase( 6363): 	at Qr.a(LegacySyncManager.java:95)
E/HttpIssuerBase( 6363): 	at Qt.run(LegacySyncManager.java:396)
E/HttpIssuerBase( 6363): 	at Vu.a(NetworkUtilitiesImpl.java:30)
E/HttpIssuerBase( 6363): 	at Qs.run(LegacySyncManager.java:393)
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43083478: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
E/SyncManager( 6363): AuthenticatorException
E/SyncManager( 6363): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 6363): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/SyncManager( 6363): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 6363): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/SyncManager( 6363): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 6363): 	at android.os.Binder.execTransact(Binder.java:407)
E/SyncManager( 6363): 	at dalvik.system.NativeStart.run(Native Method)
,W/GAV2    ( 6363): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiService(  967): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@4310b010}
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,E/ReminderSync( 1921): AuthError [T SyncAdapterThread-1:id=233:priority=5:group=main]
,E/Auth.Api.Credentials( 1921): [CredentialSyncAdapter] Unknown sync event.
,D/SyncManager(  967): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, latestRunTime 805620, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  967): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, latestRunTime 809093, reason: Periodic
,I/ActivityManager(  967): Killing 3954:com.google.android.apps.plus/u0a112 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 6189): Thread[GAThread,5,main]: No campaign data found.
,V/NativeCrypto( 1921): SSL shutdown failed: ssl=0x6c79c1d8: I/O error during system call, Connection timed out
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/ContextImpl( 6268): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 6268): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/CacheService( 6268): onCreate
,D/CacheService( 6268): onBind
,I/MusicLeanback( 6268): Conditions not met for autocaching.
,I/MusicLeanback( 6268): Stop autocaching.
,D/CacheService( 6268): onDestroy
,I/GAV2    ( 6363): Thread[GAThread,5,main]: No campaign data found.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270300049, nextTick: 59964, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270300061, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270300422568004; DSPS: 26904311; Offset: 1452269479368155163
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "smsto"
,I/ActivityManager(  967): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6492 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,D/administrator(  967): Handling package changes for user 0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
E/SlideAside( 3798): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3798): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.videos
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HyLog   ( 6492): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6492): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6492): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm( 1142): GC_FOR_ALLOC freed 8623K, 14% free 68182K/78568K, paused 25ms, total 29ms
I/AppUp4  ( 6492):  AppBoxContentProvider onCreate
,W/AppUp4  ( 6492):  [AppBoxDatabaseHelper] construct
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/AppUp4  ( 6492):  setFingerPrint start
,I/AppUp4  ( 6492):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 6492):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 6492):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6492): AppBoxApplication onCreate()
,D/AppBoxBlacklist( 6492): ConfigFile is not exist. /cust/config/appmanager.cfg
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
D/PackageParser( 6492): Added overlay pkg for /system/apps/bootup/LGTaskManager.apk
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/AppUp4:Utils( 6492): [getPackageName] uri : package:com.google.android.videos
,D/AppUp4  ( 6492): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 6492): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.videos
,D/PackageParser( 6492): Added overlay pkg for /system/apps/bootup/LGHome_Theme_Marshmallow.apk
I/AppUp4:CustModeStarterReceiver( 6492): onReceive
D/AppUp4:CustFacade( 6492): Context : android.app.ReceiverRestrictedContext@428112b0
D/AppUp4:CustFacade( 6492): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6492): isOpenOperator : true
D/AppUp4:CustFacade( 6492): isPhone : true
,I/ActivityManager(  967): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=6525 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 6525): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6525): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6525): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/LicenseContentProvider( 6525): start selecting data
,W/BaseRuntimeLoader( 6525): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6525): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6525): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6525): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/SIMObserver( 6525): simInfo1
,I/AppUp4:EulaManager( 6492): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 6492): begin check event
D/AppUp4:Utils( 6492): [getPackageName] uri : package:com.google.android.videos
,I/AppUp4:CustModeStarterReceiver( 6492): Event For Nothing, skip.
,I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6538 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  967): Killing 5178:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  967): Killing 1753:com.google.android.gms.wearable/u0a6 (adj 15): empty #18
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/HyLog   ( 6538): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6538): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6538): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/SystemConfig( 6538): BUILD Country: EU
,I/SystemConfig( 6538): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 5851:com.lge.email/u0a24 (adj 15): empty #17
,I/SystemConfig( 6538): systemFeature RCS result false
,D/SystemConfig( 6538): refreshRcsSupport() :false
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/IcingCorporaProvider( 2702): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,I/ActivityManager(  967): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6555 uid=10112 gids={50112, 3003, 3002, 1028, 1015}
,D/HyLog   ( 6555): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6555): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6555): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2702): UpdateCorporaTask done [took 82 ms] updated apps [took 82 ms] 
,I/ActivityManager(  967): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6572 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 6572): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6572): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6572): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): Killing 6210:com.google.android.syncadapters.calendar/u0a72 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/dalvikvm( 6572): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6572): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6572): VFY: replacing opcode 0x6e at 0x000b
,D/dalvikvm(  967): GC_EXPLICIT freed 2735K, 49% free 29948K/57864K, paused 4ms+9ms, total 97ms
,D/Finsky  ( 6572): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6572): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 6572): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6572): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6572): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6572): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6572): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6572): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6572): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6572): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6572): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6572): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6572): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6572): VFY: replacing opcode 0x6e at 0x011e
,V/DownloadManager( 4886): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4886): created cursor android.database.sqlite.SQLiteCursor@42876358 on behalf of 6572
I/dalvikvm( 6572): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6572): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6572): VFY: replacing opcode 0x6e at 0x0292
,I/dalvikvm( 6572): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6572): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6572): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 6572): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 6572): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6572): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 6572): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 6572): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6572): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6572): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6572): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6572): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6572): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1921): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/ActivityManager(  967): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=6616 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PeopleContactsSync( 1921): CP2 sync disabled
,D/HyLog   ( 6616): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6616): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6616): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): Killing 6189:com.google.android.gm/u0a68 (adj 15): empty #17
,W/dalvikvm( 6616): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6616): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 6616): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6616): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6616): VFY: replacing opcode 0x62 at 0x005e
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/MultiDex( 6616): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6616): install
,I/MultiDex( 6616): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6616): loading existing secondary dex files
,I/MultiDex( 6616): load found 3 secondary dex files
,I/MultiDex( 6616): install done
,D/dalvikvm( 6616): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6616): VFY: unable to resolve instance field 61
,D/dalvikvm( 6616): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6616): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6616): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6616): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 6616): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6616): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6616): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 6616): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6616): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6616): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428065a8
D/dalvikvm( 6616): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428065a8
,D/dalvikvm( 6616): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428065a8, skipping init
,D/dalvikvm( 6616): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428065a8
,D/dalvikvm( 6616): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428065a8
,V/JNIHelp ( 6616): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 6616): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428065a8
,D/dalvikvm( 6616): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428065a8
D/dalvikvm( 6616): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428065a8
,D/dalvikvm( 6616): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428065a8
,I/ProviderInstaller( 6616): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1551): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1551): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1551): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1921): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/LocationInitializer( 1921): Restart initialization of location
,I/dalvikvm( 6616): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
,W/dalvikvm( 6616): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 6616): VFY: replacing opcode 0x6e at 0x003f
,D/WearableService( 6616): callingUid 10006, callindPid: 6616
,E/dalvikvm( 6616): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 6616): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 6616): VFY: replacing opcode 0x1f at 0x0054
,W/dalvikvm( 6616): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 6616): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6616): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6616): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6616): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6616): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6616): VFY: replacing opcode 0x6e at 0x0201
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1551): GC_EXPLICIT freed 987K, 28% free 18026K/24832K, paused 3ms+6ms, total 65ms
,E/MDM     ( 1427): [65] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6572): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6572): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6572): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6572): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6572): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6572): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6572): Total arena pages for JIT: 11
,I/dalvikvm( 6572): Total arena pages for JIT: 12
I/dalvikvm( 6572): Total arena pages for JIT: 13
,I/dalvikvm( 6572): Total arena pages for JIT: 14
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6572): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6572): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6572): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6572): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/DeviceConnectionService( 1427): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Killing 5006:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb92b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270320423542645; DSPS: 27559703; Offset: 1452269479368153241
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6572): [510] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6572): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/.AppDataSearchProvider( 6268): Couldn't find corpus 'songs'
,E/.AppDataSearchProvider( 6268): Couldn't find corpus 'albums'
,E/.AppDataSearchProvider( 6268): Couldn't find corpus 'artists'
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/.AppDataSearchProvider( 6268): Couldn't find corpus 'playlists'
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270340424436376; DSPS: 28215092; Offset: 1452269479368161962
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270360047, nextTick: 59966, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270360058, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270360425075990; DSPS: 28870473; Offset: 1452269479368160707
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270380426384564; DSPS: 29525876; Offset: 1452269479368157025
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270400428426548; DSPS: 30181303; Offset: 1452269479368154332
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270420038, nextTick: 59989, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270420051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270420429781115; DSPS: 30836707; Offset: 1452269479368166125
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270440431094238; DSPS: 31492110; Offset: 1452269479368166992
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270460431990472; DSPS: 32147500; Offset: 1452269479368147699
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270480050, nextTick: 59978, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270480059, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270480432930415; DSPS: 32802891; Offset: 1452269479368141597
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270500434232889; DSPS: 33458293; Offset: 1452269479368162333
,D/GCM     ( 1551): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/EventLogService( 1921): Aggregate from 1452269602122 (log), 1452268618391 (data)
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270520435577882; DSPS: 34113697; Offset: 1452269479368164552
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270540052, nextTick: 59977, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270540055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270540436475127; DSPS: 34769087; Offset: 1452269479368146270
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270560438357371; DSPS: 35424508; Offset: 1452269479368166942
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270580439228324; DSPS: 36079897; Offset: 1452269479368152885
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270600037, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270600040, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270600440227173; DSPS: 36735290; Offset: 1452269479368144654
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43138fc0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 6572): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6572): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6572): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6572): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6572): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6572): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6572): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6572): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 6572): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6572): isDataSchedulerEnabled():false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270620441101326; DSPS: 37390678; Offset: 1452269479368164315
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270640441992223; DSPS: 38046067; Offset: 1452269479368170202
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270660034, nextTick: 59994, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270660038, nextTick: 59994, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270660442933679; DSPS: 38701458; Offset: 1452269479368165613
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270680444288134; DSPS: 39356863; Offset: 1452269479368146777
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270700445176023; DSPS: 40012252; Offset: 1452269479368149656
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270720042, nextTick: 59986, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270720045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270720446094041; DSPS: 40667642; Offset: 1452269479368152147
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270740447445555; DSPS: 41323046; Offset: 1452269479368160888
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270760448298923; DSPS: 41978434; Offset: 1452269479368159763
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270780038, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270780040, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270780448703368; DSPS: 42633808; Offset: 1452269479368136962
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270800450015176; DSPS: 43289210; Offset: 1452269479368167032
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270820450482159; DSPS: 43944585; Offset: 1452269479368176251
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270840037, nextTick: 59992, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270840040, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270840451396745; DSPS: 44599976; Offset: 1452269479368144792
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270860452713850; DSPS: 45255379; Offset: 1452269479368149642
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270880453604240; DSPS: 45910768; Offset: 1452269479368155022
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270900037, nextTick: 59985, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270900046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270900454519685; DSPS: 46566158; Offset: 1452269479368154939
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270920454948508; DSPS: 47221532; Offset: 1452269479368156516
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270940455829709; DSPS: 47876921; Offset: 1452269479368152708
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270960036, nextTick: 59982, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452270960045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270960456768466; DSPS: 48532312; Offset: 1452269479368145420
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452270980458071119; DSPS: 49187714; Offset: 1452269479368166334
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271000458944471; DSPS: 49843103; Offset: 1452269479368154677
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271020038, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271020041, nextTick: 59991, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271020459921067; DSPS: 50498495; Offset: 1452269479368154710
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271040461378546; DSPS: 51153903; Offset: 1452269479368147345
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/Finsky  ( 6572): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,D/dalvikvm(  967): GC_EXPLICIT freed 1976K, 49% free 29858K/57864K, paused 4ms+12ms, total 169ms
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6572): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6572): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6572): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6572): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6572): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6572): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1427): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6572): [510] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6572): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271060462277954; DSPS: 51809292; Offset: 1452269479368161744
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271080033, nextTick: 59974, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271080050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271080463213391; DSPS: 52464683; Offset: 1452269479368151136
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271100464578965; DSPS: 53120087; Offset: 1452269479368173936
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271120465447641; DSPS: 53775476; Offset: 1452269479368157602
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271140037, nextTick: 59988, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271140040, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271140466383517; DSPS: 54430867; Offset: 1452269479368147434
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271160470388704; DSPS: 55086358; Offset: 1452269479368154818
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271180471246114; DSPS: 55741746; Offset: 1452269479368157736
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271200030, nextTick: 59990, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271200052, nextTick: 59980, mDrawingTime: 0,
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271200472168259; DSPS: 56397136; Offset: 1452269479368164353
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271220473478425; DSPS: 57052539; Offset: 1452269479368162263
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271240473931173; DSPS: 57707914; Offset: 1452269479368157248
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271260040, nextTick: 59987, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271260043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271260474852958; DSPS: 58363304; Offset: 1452269479368163505
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271280476116853; DSPS: 59018706; Offset: 1452269479368145662
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271300477031654; DSPS: 59674095; Offset: 1452269479368175453
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  967): Prepared write state in 43ms
D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271320076, nextTick: 59955, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271320086, nextTick: 59946, mDrawingTime: 0
,I/ProcessStatsService(  967): Prepared write state in 36ms
,I/ProcessStatsService(  967): Pruning old procstats: /data/system/procstats/state-2016-01-07-23-26-00.bin
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271320477814257; DSPS: 60329481; Offset: 1452269479368164599
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271340479138831; DSPS: 60984885; Offset: 1452269479368146400
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271360479573245; DSPS: 61640259; Offset: 1452269479368153568
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271380032, nextTick: 59973, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452271380051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271380480519397; DSPS: 62295650; Offset: 1452269479368153675
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452271400481816590; DSPS: 62951052; Offset: 1452269479368169130
,TIME-OUT KILL (timeout was 1800000ms)
```
