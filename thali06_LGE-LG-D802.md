#### Test 50650278b28a87a_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4026): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  965): Killing 3356:com.google.android.music:main/u0a107 (adj 15): empty #17
F/ActivityManager(  965): Service ServiceRecord{43298b48 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{4324cc10 3356:com.google.android.music:main/u0a107} not same as in map: null
F/ActivityManager(  965): Service ServiceRecord{431c4ff8 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{4324cc10 3356:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{431fd8c0 u0 com.android.settings/.UsbSettings t2}
,D/ChimeraCfgMgr( 1853): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1853): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1853): GC_CONCURRENT freed 1686K, 26% free 18440K/24832K, paused 4ms+5ms, total 46ms
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Icing   ( 1853): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1853): Loaded CLD2 Version V2.0 - 20141016
D/AndroidRuntime( 4069): 
D/AndroidRuntime( 4069): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4069): CheckJNI is OFF
D/dalvikvm( 4069): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4069): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4069): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4069): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4069): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/Icing   ( 1853): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/dalvikvm( 4069): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4069): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4069): failed to load memtrack module: -2
D/AndroidRuntime( 4069): Calling main entry com.android.commands.am.Am
I/ActivityManager(  965): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4069
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (115 us)
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{431fd8c0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  965): GC_FOR_ALLOC freed 22187K, 51% free 27965K/56664K, paused 113ms, total 113ms
D/ActivityManager(  965): resumeTopActivityLocked: Pausing null
V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  965): setFocusedStack: mFocusedStack=ActivityStack{43235e00 stackId=1, 2 tasks}
D/AndroidRuntime( 4069): Shutting down VM
D/UsbSettingsControl( 2563): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2563): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4069): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{431fd8c0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  965): startService SlideAside
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{431fd8c0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Restarting ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/ActivityManager(  965): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4088 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/SlideAside( 3521): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/SlideAside( 3521): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3521): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4088): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4088): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4088): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/WebViewChromium( 4088): Binding Chromium to the background looper Looper (main, tid 1) {42832538}
I/chromium( 4088): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4088): Initializing chromium process, renderers=0
W/chromium( 4088): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4088): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4088): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4088): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4088): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4088): Remote Branch: 
I/Adreno-EGL( 4088): Local Patches: 
I/Adreno-EGL( 4088): Reconstruct Branch: 
I/dalvikvm( 4088): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4088): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4088): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4088): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4088): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4088): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4088): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4088): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4088): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4088): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4088): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4088): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4088): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4088): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4088): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4088): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4088): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4088): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4088): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4088): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4088): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4088): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4088): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4088): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4088): Enabling debug mode 0
W/AwContents( 4088): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  965): IME STATUS OFF
W/AwContents( 4088): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  965): Displayed com.test.thalitest/.MainActivity: +361ms
I/ActivityManager( 4088): Timeline: Activity_idle id: android.os.BinderProxy@42833df8 time:112453
D/JsMessageQueue( 4088): Set native->JS mode to OnlineEventsBridgeMode
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4088): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42838868
D/dalvikvm( 4088): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42838868
D/jxcore_app_log( 4088): JniHelper::setJavaVM(0x416fe838), pthread_self() = 1636703552
D/JX-Cordova( 4088): jxcore cordova android initializing
I/dalvikvm( 4088): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4088): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4088): VFY: replacing opcode 0x6e at 0x0045
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.461258 Y: -0.385284 Z: 9.777664 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461258 .y:-0.385284 .z:9.777664
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/ActivityManager(  965): no-history finish of ActivityRecord{431fd8c0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  965): Finishing activity token=Token{42c5aa98 ActivityRecord{431fd8c0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3} time:112860
D/UsbSettings( 2563): [AUTORUN] onStop()
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{431fd8c0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{431fd8c0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{431fd8c0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.455261 Y: -0.390930 Z: 9.759705 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455261 .y:-0.390930 .z:9.759705
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4088): GC_CONCURRENT freed 2769K, 12% free 21929K/24832K, paused 3ms+3ms, total 50ms
,D/dalvikvm( 4088): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 4088): GC_FOR_ALLOC freed 216K, 12% free 21862K/24832K, paused 21ms, total 21ms
,D/dalvikvm( 4088): GC_FOR_ALLOC freed 188K, 12% free 21891K/24832K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4088): Grow heap (frag case) to 23.690MB for 144892-byte allocation
,D/dalvikvm( 4088): GC_FOR_ALLOC freed 258K, 13% free 21936K/24976K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4088): Grow heap (frag case) to 23.802MB for 217334-byte allocation
,D/dalvikvm( 4088): GC_FOR_ALLOC freed 367K, 13% free 22009K/25192K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4088): Grow heap (frag case) to 23.978MB for 325996-byte allocation
,D/dalvikvm( 4088): GC_FOR_ALLOC freed 568K, 14% free 22131K/25512K, paused 29ms, total 29ms
I/dalvikvm-heap( 4088): Grow heap (frag case) to 24.252MB for 488990-byte allocation
D/dalvikvm( 4088): GC_FOR_ALLOC freed 865K, 15% free 22308K/25992K, paused 34ms, total 34ms
I/dalvikvm-heap( 4088): Grow heap (frag case) to 24.658MB for 733480-byte allocation
D/dalvikvm( 4088): GC_FOR_ALLOC freed 1284K, 16% free 22566K/26712K, paused 22ms, total 23ms
D/dalvikvm( 4088): GC_CONCURRENT freed 1675K, 15% free 22938K/26712K, paused 2ms+2ms, total 27ms
D/dalvikvm( 4088): WAIT_FOR_CONCURRENT_GC blocked 8ms
D/dalvikvm( 4088): GC_FOR_ALLOC freed 370K, 15% free 22895K/26712K, paused 36ms, total 36ms
I/dalvikvm-heap( 4088): Grow heap (frag case) to 26.106MB for 1650320-byte allocation
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4088): GC_CONCURRENT freed 1719K, 18% free 23466K/28324K, paused 1ms+2ms, total 25ms
D/dalvikvm( 4088): GC_FOR_ALLOC freed 1331K, 17% free 23544K/28324K, paused 24ms, total 24ms
I/dalvikvm-heap( 4088): Grow heap (frag case) to 27.526MB for 2475476-byte allocation
D/dalvikvm( 4088): GC_CONCURRENT freed 172K, 16% free 25840K/30744K, paused 2ms+2ms, total 25ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4088): GC_CONCURRENT freed 4417K, 21% free 24534K/30744K, paused 1ms+5ms, total 38ms
,D/dalvikvm( 4088): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/dalvikvm-heap( 4088): Grow heap (frag case) to 29.673MB for 3713210-byte allocation
,D/dalvikvm( 4088): GC_CONCURRENT freed 2593K, 26% free 25658K/34372K, paused 1ms+3ms, total 27ms
,D/dalvikvm( 4088): GC_FOR_ALLOC freed 909K, 26% free 25483K/34372K, paused 23ms, total 23ms
,W/jxcore-log( 4088): Initializing JXcore engine
,W/jxcore-log( 4088): JXcore engine is ready
,D/dalvikvm( 4088): GC_CONCURRENT freed 332K, 19% free 28152K/34372K, paused 1ms+2ms, total 35ms
,D/dalvikvm( 4088): WAIT_FOR_CONCURRENT_GC blocked 33ms
,W/jxcore-log( 4088): Starting JXcore engine
,W/jxcore-log( 4088): Platform android
W/jxcore-log( 4088): 
,W/jxcore-log( 4088): Process ARCH arm
W/jxcore-log( 4088): 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4088): JXcore Cordova bridge is ready!
I/jxcore-log( 4088): 
,W/jxcore-log( 4088): JXcore engine is started
,I/chromium( 4088): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4088): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4088): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  965): Killing 3039:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/GAV2    ( 4026): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1540): onDestroy
,I/jxcore-log( 4088): Toggling radios to true
I/jxcore-log( 4088): 
D/BluetoothManagerService(  965): Message: 20
,D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@430ad230:true
D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  965): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  965): Message: 1
,D/BluetoothManagerService(  965): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  965): New client listening to asynchronous messages
,D/WifiService(  965): setWifiEnabled: true pid=4088, uid=10304
E/WifiService(  965): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  965): setWifiEnabled startWifiDelaySendMsg true
,D/BluetoothAdapterService( 1222): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(1116087104)( 1222): onCreate
,D/BluetoothManagerService(  965): Message: 20
,D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@430b24c8:true
D/BluetoothAdapterState( 1222): make
D/WifiStateMachine(  965): setting operational mode to 1
D/WifiStateMachine(  965): handleMessage: E msg.what=131083
,D/WifiStateMachine(  965): processMsg: InitialState
D/WifiService(  965): disconnect pid=4088, uid=10304
,D/WifiService(  965): reconnect pid=4088, uid=10304
I/bluedroid( 1222): init ready=0,
D/bt-btif ( 1222): in initialized:0
D/bt-btif ( 1222): root, p->name:Bluedroid, child/value:0x6063b648, bytes:160
D/bt-btif ( 1222): p->used:0, type:0, p->flag:0
I/BluetoothAdapterState( 1222): Entering OffState
I/jxcore-log( 4088): Radios toggled
I/jxcore-log( 4088): 
E/WifiHW  (  965): Wifi MAC Address = 34:fc:ef:de:0a:e2
E/WifiHW  (  965): wifi_check_config compare "cur_etheraddr=34:fc:ef:de:0a:e2
E/WifiHW  (  965): ": cur_etheraddr=34:fc:ef:de:0a:e2
D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/SoftapController(  271): Softap fwReload - Ok
I/jxcore-log( 4088): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4088): 
I/bte_conf( 1222): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
W/BT_PROF ( 1222): set profile trace flags 0x0
D/BTIF_CORE( 1222): [BTUI] lge_load_bluetooth_address
D/btif_config_util( 1222): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/bt-btif ( 1222):  [BTUI] Load_abtddress
D/bt-btif ( 1222): PERSIST_BDADDR_PROPERTY is  34:FC:EF:9D:93:0B
D/bt-btif ( 1222): Got prior random BDA 34:FC:EF:9D:93:0B
I/jxcore-log( 4088): Perf Test app loaded loaded
I/jxcore-log( 4088): 
D/lge_bdaddr_loader( 4161): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 4161): [BTUI] bluetooth_load_bdaddress
D/lge_bdaddr_loader( 4161): [BTUI] bdaddr to set in property : 34:FC:EF:9D:93:0B
D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring down wlan0
I/Choreographer( 4088): Skipped 66 frames!  The application may be doing too much work on its main thread.
,D/WifiMonitor(  965): WifiMonitorSingleton gotten
,I/chromium( 4088): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4088): check test folder
I/jxcore-log( 4088): 
,I/jxcore-log( 4088): found test : ./testFindPeers.js
I/jxcore-log( 4088): 
,I/jxcore-log( 4088): found test : ./testSendData.js
I/jxcore-log( 4088): 
,E/lge_bdaddr_loader( 4161): [BTUI] bluetooth_load_bdaddress : OK => 34:FC:EF:9D:93:0B
,D/lge_bdaddr_loader( 4161): [BTUI] bdaddr_loader ::: END
,D/WifiStateMachine(  965): setWifiState: enabling
E/WifiStateMachine(  965): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  965): useWiFiOffloading() : false
E/WifiStateMachine(  965): CONFIG_LGE_WLAN_PATH : true
,D/WifiStateMachine(  965): Supplicant start successful
,V/WfdStateTracker( 1156): WfdStateTracker handleDirectStateChangedEvent: 1
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiMonitor(  965): WifiMonitorSingleton gotten
,D/WifiMonitor(  965): startMonitoring(wlan0) with mConnected = false
,D/WifiMonitor(  965): connecting to supplicant
,I/WifiServiceExtension(  965): WIFI_STATE_CHANGED_ACTION [2]
,D/wpa_supplicant( 4164): wpa_supplicant v2.1-devel-4.4.2
D/wpa_supplicant( 4164): random: Invalid entropy file /data/misc/wifi/entropy.bin
D/wpa_supplicant( 4164): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4164): Get randomness: len=20 entropy=0
,D/wpa_supplicant( 4164): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=0)
D/wpa_supplicant( 4164): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4164): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4164): Successfully initialized wpa_supplicant
D/wpa_supplicant( 4164): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4164): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4164): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 4164): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4164): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4164): disable_scan_offload=1
D/wpa_supplicant( 4164): driver_param='use_multi_chan_concurrent=1'
,D/wpa_supplicant( 4164): update_config=1
D/wpa_supplicant( 4164): device_name='g2_open_com'
,I/ActivityManager(  965): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4165 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/wpa_supplicant( 4164): manufacturer='LGE'
D/wpa_supplicant( 4164): model_name='LG-D802'
D/wpa_supplicant( 4164): model_number='LG-D802'
D/wpa_supplicant( 4164): serial_number='022678fb504e29b0'
D/wpa_supplicant( 4164): config_methods='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4164): p2p_disabled=1
D/wpa_supplicant( 4164): p2p_no_group_iface=1
D/wpa_supplicant( 4164): Line: 15 - start of a new network block
D/wpa_supplicant( 4164): ssid - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4164): PSK (ASCII passphrase) - hexdump(len=10): [REMOVED]
D/wpa_supplicant( 4164): key_mgmt: 0x2
D/wpa_supplicant( 4164): priority=1 (0x1)
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
,I/bluedroid( 1222): get_profile_interface socket
,I/bt-btif ( 1222): btif_get_adapter_property 2
I/bt-btif ( 1222): btif_get_adapter_property 1
,D/BluetoothAdapterService(1116087104)( 1222): onBind
,D/BluetoothManagerService(  965): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  965): Message: 40
,D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 1222): config_hci_snoop_log
,D/BluetoothManagerService(  965): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  965): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/wpa_supplicant( 4164): PSK (from passphrase) - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4164): Priority group 1
D/wpa_supplicant( 4164):    id=0 ssid='NG700'
,D/wpa_supplicant( 4164): Reading configuration file '/system/etc/wifi/wpa_supplicant_overlay.conf'
I/GKI_LINUX( 1222): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/bt-btif ( 1222): btif task starting
D/bt-btif ( 1222): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 1222): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 1222): execute storage request event : 3
D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:2 
,I/bt-btif ( 1222): HAL bt_hal_cbacks->adapter_properties_cb
D/wpa_supplicant( 4164): disable_scan_offload=1
D/wpa_supplicant( 4164): Priority group 1
D/wpa_supplicant( 4164):    id=0 ssid='NG700'
I/wpa_supplicant( 4164): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4164): nl80211: RFKILL status not available
D/wpa_supplicant( 4164): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4164): nl80211: TDLS supported
D/wpa_supplicant( 4164): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4164): nl80211: Enable multi-channel concurrent (driver advertised support)
I/wpa_supplicant( 4164): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/wpa_supplicant( 4164): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4164): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4164): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4164): nl80211: Subscribe to mgmt frames with non-AP handle 0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
,D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 0a 11
I/bt-btif ( 1222): execute storage request event : 3
D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1222): in, bd addr:, prop type:1, len:512
I/bt-btif ( 1222): HAL bt_hal_cbacks->adapter_properties_cb
,D/dalvikvm( 1222): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,D/BluetoothManagerService(  965): Bluetooth Adapter name changed to Thali Test's G2
,D/BluetoothManagerService(  965): Stored Bluetooth name: Thali Test's G2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BluetoothAdapterService(1116087104)( 1222): Enable called with quiet mode status =  false
D/BluetoothAdapterState( 1222): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
I/BluetoothAdapterState( 1222): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 1222): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  965): Message: 60
D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothAdapterService(1116087104)( 1222): processStart()
,D/BluetoothManagerService(  965): Bluetooth State Change Intent: 10 -> 11
,D/LGBluetoothAPIService( 1156): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(1116087104)( 1222): processStart(): Make Bond State Machine
,D/BluetoothBondStateMachine( 1222): make
,I/BluetoothBondStateMachine( 1222): StableState(): Entering Off State
D/BluetoothAdapterService( 1222): setAdapterService(): set to: null
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
D/LGBluetoothServiceAdapter( 1222): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
,D/LGBluetoothServiceAdapter( 1222): [BTUI] check adapter is available - true : set adapter available.
,D/LGBluetoothSettingsDBObserver( 1222): [BTUI] register observer for LG device name DB
,E/BluetoothAdapterService( 1222): File transfer profiels supported!!
,W/BluetoothAdapterService( 1222): Starting service com.broadcom.bt.service.hfp.BrcmHeadsetService
D/HyLog   ( 4165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4165): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/BluetoothHeadset(  965): Proxy object connected
,D/BluetoothHeadset( 1450): Proxy object connected
,D/BluetoothHeadset( 1450): Proxy object connected
D/BluetoothHeadset( 1450): Proxy object connected
,D/BrcmHeadsetService( 1222): Received start request. Starting profile...
,I/Brcm_BluetoothHeadsetServiceJni( 1222): classInitNative: succeeds
D/HeadsetStateMachine( 1222): make
,E/BluetoothAdapterService( 1222): File transfer profiels supported!!
,I/LGBluetoothHeadsetServiceJni( 1222): classInitNative: succeeds
,D/LGBluetoothHfpAdapter( 1222): Version 1.5
,W/BluetoothAdapterService( 1222): Starting service com.android.bluetooth.a2dp.A2dpService
I/bluedroid( 1222): get_profile_interface handsfree
I/bt-btif ( 1222): btif_hf_get_interface
I/bt-btif ( 1222): init
,D/bt-btif ( 1222): btif_enable_service: current services:0x40
V/AudioPolicyService(  277): getOutput()
V/AudioPolicyManagerBase(  277): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,V/AudioPolicyManagerBase(  277): getOutput() returns output 2
,V/AudioSystem( 1222): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  277): registerClient() client 0xb6fc8810, pid 1222
V/AudioFlinger(  277): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  277): thread 0xb2696008 type 0 TID 872 waking up
V/AudioFlinger(  277): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  277): thread 0xb252b008 type 0 TID 1002 waking up
,E/BluetoothAdapterService( 1222): File transfer profiels supported!!
V/AudioFlinger(  277): acquireWakeLock_l() AudioOut_3 status 0
,V/AudioFlinger(  277): processConfigEvents() remaining events 1
V/AudioFlinger(  277): acquireWakeLock_l() AudioOut_2 status 0
V/AudioFlinger(  277): processConfigEvents() remaining events 1
V/AudioFlinger(  277): PlaybackThread::audioConfigChanged_l, thread 0xb252b008, event 0, param 0
V/AudioSystem(  277): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  277): ioConfigChanged() opening already existing output! 3
V/AudioSystem(  965): ioConfigChanged() event 0, ioHandle 3
,V/AudioSystem(  965): ioConfigChanged() opening already existing output! 3
V/AudioFlinger(  277): PlaybackThread::audioConfigChanged_l, thread 0xb2696008, event 0, param 0
V/AudioSystem(  277): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  277): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  277): acquireWakeLock_l() AudioOut_3 status 0
V/AudioSystem( 1450): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1450): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1608): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1608): ioConfigChanged() opening already existing output! 3
V/AudioSystem(  965): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  965): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1450): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1450): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1222): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1222): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1222): ioConfigChanged() event 0, ioHandle 2
,V/AudioSystem( 1222): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 160
V/AudioSystem( 1608): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1608): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  277): acquireWakeLock_l() AudioOut_2 status 0
V/AudioSystem( 1222): getSamplingRate() streamType 8, output 2, sampling rate 48000
V/AudioTrack( 1222): sampleRate 0, channelMask 0x1, format 1
V/AudioTrack( 1222): streamType 8
V/AudioTrack( 1222): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyService(  277): checkPlayCondition().. streamType = 8
,V/AudioPolicyManagerBase(  277): checkPlayCondition()... stream = 8, bResult = 0
V/AudioTrack( 1222): set() checkPlaycondition!!!! streamType 8 return NO_INIT.
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
,W/BluetoothAdapterService( 1222): Starting service com.android.bluetooth.hid.HidService
D/HeadsetStateMachine( 1222): Enter Disconnected: -2
,D/HeadsetPhoneState( 1222): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1222): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1222): [BTUI] change sampling rate to 8000 when device is disconnected
,E/AudioSystem( 1222): AudioSystem::setParameters()...keyValue bt_samplerate=8000
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
V/AudioFlinger(  277): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1222
,D/HeadsetStateMachine( 1222): Proxy object connected
V/SRS_Proc(  277): ParamSet string: bt_samplerate=8000
D/audio_hw_primary(  277): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  277): voice_set_parameters: enter: bt_samplerate=8000
,V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
,E/BluetoothAdapterService( 1222): File transfer profiels supported!!
,D/BluetoothA2dp(  965): Proxy object connected
,W/BluetoothAdapterService( 1222): Starting service com.android.bluetooth.hdp.HealthService
D/A2dpService( 1222): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 1222): classInitNative: succeeds
,D/A2dpStateMachine( 1222): make
I/bluedroid( 1222): get_profile_interface a2dp
I/bt-btif ( 1222): btif_av_get_interface
I/bt-btif ( 1222): init
I/bt-btif ( 1222): ## A2DP START MEDIA TASK ##
I/GKI_LINUX( 1222): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/bt-btif ( 1222): UIPC_Init
I/bt-btif ( 1222): ### uipc_main_init ###
D/bt-btif ( 1222): UIPC_Open : ch_id 0, p_cback 60ad4b25
I/bt-btif ( 1222): SETUP CHANNEL SERVER 0
I/bt-btif ( 1222): create_server_socket /data/misc/bluedroid/.a2dp_ctrl
,I/bt-btif ( 1222): created socket fd 69
I/bt-btif ( 1222): ADD SERVER FD TO ACTIVE SET 69
I/bt-btif ( 1222): UIPC SEND WAKE UP
I/bt-btif ( 1222): ## A2DP MEDIA TASK STARTED ##
E/bt-btif ( 1222): warning : media task started media_task_refcnt 1 
D/bt-btif ( 1222): btif_enable_service: current services:0x48
D/bt-btif ( 1222): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/bt-btif ( 1222): ## ON A2DP IDLE ##
D/bt-btif ( 1222): UIPC_Close : ch_id 1
,I/bt-btif ( 1222): CHANNEL 1 ALREADY CLOSED
I/LGBluetoothA2dpServiceJni( 1222): classInitNative: succeeds
,I/LGBluetoothA2dpAdapter( 1222): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/A2dpStateMachine( 1222): Enter Disconnected: -2
I/BluetoothAVRCP1.3ServiceJni( 1222): classInitNativeAVRCP
,V/Avrcp   ( 1222): make
,E/BluetoothAdapterService( 1222): File transfer profiels supported!!
,W/BluetoothAdapterService( 1222): Starting service com.android.bluetooth.pan.PanService
,D/LGBluetoothAvrcpManager( 1222): [BTUI] initAvcrpManager
,D/PCSuite ( 4165): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/LGBluetoothAvrcpManager( 1222): [BTUI] initPlayStatus() : isMusicActive = false
,E/BluetoothAdapterService( 1222): File transfer profiels supported!!
,W/BluetoothAdapterService( 1222): Starting service com.android.bluetooth.map.BluetoothMapService
D/LGBluetoothAvrcpAdapter( 1222): [BTUI] Use LG AVRCP : init jni
I/BluetoothAVRCP1.3ServiceJni( 1222): initNativeAVRCP
I/bluedroid( 1222): get_profile_interface avrcp
,I/bt-btif ( 1222): btif_rc_get_interface
I/bt-btif ( 1222): ## init ##
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
,I/ActivityManager(  965): Killing 3211:com.android.mms/u0a35 (adj 15): empty #17
D/BluetoothAdapterService(1116087104)( 1222): Message: 1
D/BluetoothAdapterService(1116087104)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 12, doUpdate = true
E/BluetoothAdapterService( 1222): File transfer profiels supported!!
D/BluetoothAdapterService( 1222): Profile still not running:com.broadcom.bt.service.sap.SapService
I/BluetoothHidServiceJni( 1222): classInitNative: succeeds
D/LGBluetoothXmlHandler( 2563): dvice configuraion start
D/LGBluetoothXmlHandler( 2563): startDocument!
W/BluetoothAdapterService( 1222): Starting service com.android.bluetooth.gatt.GattService
D/HidService( 1222): Received start request. Starting profile...
I/bluedroid( 1222): get_profile_interface hidhost
I/bt-btif ( 1222): btif_hh_get_interface
I/bt-btif ( 1222): init
D/bt-btif ( 1222): btif_enable_service: current services:0x100048
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
D/LGBluetoothXmlHandler( 2563): startElement - elet = Device
D/LGBluetoothXmlHandler( 2563): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2563): startElement - elet = OLDHELP
,I/BluetoothHealthServiceJni( 1222): classInitNative: succeeds
,D/LGBluetoothXmlHandler( 2563): startElement - elet = OPPDIRECTORYBLUETOOTH
D/HealthService( 1222): Received start request. Starting profile...
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/HeadsetPhoneState( 1222): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
I/bluedroid( 1222): get_profile_interface health
I/bt-btif ( 1222): btif_hl_get_interface
I/bt-btif ( 1222): init
D/bt-btif ( 1222): Process name (droid.bluetooth)
D/bt-btif ( 1222): btif_hl_soc_thread_init
D/bt-btif ( 1222): create_thread: entered
D/HeadsetStateMachine( 1222): Disconnected process message: 11
D/bt-btif ( 1222): create_thread: thread created successfully
I/LGBluetoothHealthServiceJni( 1222): classInitNative: succeeds
D/bt-btif ( 1222): entered btif_hl_select_thread
D/bt-btif ( 1222): btif_hl_select_wakeup_init
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
D/bt-btif ( 1222): btif_hl_select_wakeup_init signal_fds[0]=79 signal_fds[1]=80
D/bt-btif ( 1222): max_s=79 
,D/bt-btif ( 1222): set curr_set = org_set 
,I/BluetoothPanServiceJni( 1222): classInitNative(L105): succeeds
D/CountryDetector(  965): No listener is left
,E/BluetoothAdapterService( 1222): File transfer profiels supported!!
,D/BluetoothPan(  965): BluetoothPAN Proxy object connected
I/LocationManagerService(  965): remove 430a2d98
,W/BluetoothAdapterService( 1222): Starting service com.broadcom.bt.service.sap.SapService
D/PanService( 1222): Received start request. Starting profile...
,D/LocationManagerService(  965): provider request: passive ProviderRequest[ON interval=0]
,D/LGBluetoothXmlHandler( 2563): startElement - elet = OPP_DIRECTORY_BLUETOOTH
D/LGBluetoothXmlHandler( 2563): endDocument!
,D/BluetoothPanServiceJni( 1222): initializeNative(L110): pan
I/bluedroid( 1222): get_profile_interface pan
,D/bt-btif ( 1222): stack_initialized = 0, btpan_cb.enabled:0
,D/BluetoothTethering(  965): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
,E/BluetoothAdapterService( 1222): File transfer profiels supported!!
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
W/BluetoothAdapterService( 1222): Starting service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
I/LGBluetoothMapAdapter( 1222): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1222): BluetoothMapBinder()
D/BluetoothMapService( 1222): Received start request. Starting profile...
D/BluetoothMapService( 1222): start()
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
D/BluetoothAdapterService(1116087104)( 1222): Message: 1
D/BluetoothAdapterService(1116087104)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 12, doUpdate = true
D/dalvikvm( 1222): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
D/BluetoothAdapterService( 1222): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116087104)( 1222): Message: 1
D/BluetoothAdapterService(1116087104)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still not running:com.broadcom.bt.service.sap.SapService
I/BtGatt.JNI( 1222): classInitNative(L685): classInitNative: Success!
I/BluetoothAdapterState( 1222): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BtGatt.DebugUtils( 1222): handleDebugAction() action=null
D/BtGatt.GattService( 1222): Received start request. Starting profile...
D/BtGatt.GattService( 1222): start()
I/bluedroid( 1222): get_profile_interface gatt
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
D/BluetoothAdapterService(1116087104)( 1222): Message: 1
D/BluetoothAdapterService(1116087104)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still not running:com.broadcom.bt.service.sap.SapService
I/BluetoothSAPServiceJni( 1222): classInitNative(L170): succeeds
D/SapService( 1222): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1222): initializeNative(L175): sap
I/bluedroid( 1222): get_profile_interface sap
I/bt-btif ( 1222): btif_sc_get_interface
I/bt-btif ( 1222): init
D/bt-btif ( 1222): btif_enable_service: current services:0x120048
I/LGBluetoothSapAdapter( 1222): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1222): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1222): [BTUI] initSapManager
D/LgeBluetoothSimManager( 1450): [BTUI] SAP_ENABLE_EVT
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
V/BluetoothPbapReceiver( 1222): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1222): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1222): ***********state = 11
D/BluetoothAdapterService(1116087104)( 1222): Message: 1
D/BluetoothAdapterService(1116087104)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 12, doUpdate = true
D/BluetoothPermissionRequest( 2563): onReceive
D/BluetoothAdapterService( 1222): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothManagerService(  965): Message: 20
D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$P,roxy@431d6720:true
D/LGBluetoothResetSettingReceiver( 2563): [BTUI] Loading JNI Library
E/BluetoothSettings_JNI( 2563): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
V/BluetoothFTPServiceJni( 1222): classInitNative
I/BluetoothFTPServiceJni( 1222): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
D/BluetoothFTPService( 1222): BluetoothFtpBinder()
D/LGBluetoothResetSettingReceiver( 2563): return without doing reset settings.
D/**BluetoothFTPService( 1222): Received start request. Starting profile...
V/BluetoothFTPService( 1222): FTP-Server Service start
D/BluetoothFTPServiceJni( 1222): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1222): get_profile_interface ftp
I/bt-btif ( 1222): btif_fts_get_interface
I/bt-btif ( 1222): init
D/bt-btif ( 1222): btif_enable_service: current services:0x120148
D/BluetoothFTPServiceJni( 1222): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
V/BluetoothMapService( 1222): Handler(): got msg=1
D/BluetoothAdapterService(1116087104)( 1222): Message: 1
D/BluetoothAdapterService(1116087104)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116087104)( 1222): Message: 1
D/BluetoothAdapterService(1116087104)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116087104)( 1222): Message: 1
D/BluetoothAdapterService(1116087104)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still not running:com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1116087104)( 1222): Message: 1
D/BluetoothAdapterService(1116087104)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1222): All profile services started.
D/BluetoothAdapterState( 1222): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1222): enable 1
I/bt-btif ( 1222): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1222): VERSION G2-AFBT-440-21_MI_00.02_OPP10 (BTE: BCM1200_PI_10.3.20.55)
I/GKI_LINUX( 1222): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 1222): init
I/bt_vendor( 1222): init
I/bt_vnd_conf( 1222): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1222): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1222): libbt-hci init returns 0
I/bt_hci_bdroid( 1222): bt_hc_worker_thread started
I/ActivityManager(  965): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4208 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/HyLog   ( 4208): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4208): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4208): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/AuthorizationBluetoothService( 1540): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  965): Killing 3791:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,I/bt_userial_vendor( 1222): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1222): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 1222): device fd = 84 open
,D/bt_hwcfg( 1222): Chipset BCM4335A0
,D/bt_hwcfg( 1222): Target name = [BCM4335A0]
D/bt_hwcfg( 1222): Target name = [BCM4335]
I/bt_hwcfg( 1222): Found patchfile: /system/bin//BCM4335B0_002.001.006.0191.0201_ORC.hcd
,I/bt_hwcfg( 1222): Applying 4335 AXI BRIDGE patch...
,I/bt_hwcfg( 1222): bt vendor lib: set UART baud 4000000
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4164): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4164): nl80211: driver param='use_multi_chan_concurrent=1'
,D/wpa_supplicant( 4164): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4164): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4164): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4164): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4164): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4164): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4164): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4164): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4164): wlan0: Own MAC address: 34:fc:ef:de:0a:e2
,D/wpa_supplicant( 4164): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4164): wlan0: RSN: flushing PMKID list in the driver
,D/wpa_supplicant( 4164): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4164): wlan0: Setting scan request: 0 sec 100000 usec
,D/Tethering(  965): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering(  965): sendTetherStateChangedBroadcast 1, 0, 0
,D/libc    (  271): _dns_getaddrinfo: iptype =0
D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2563): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2563): [AUTORUN] sys.usb.state = boot,adb
,D/UsbSettingsReceiver( 2563): [AUTORUN] persist.sys.usb.config = boot,adb
,D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/Config  ( 2563): getOperator() : OPEN
,D/UsbSettingsControl( 2563): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2563): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 2563): [AUTORUN] setTetherStatus() : status=false
D/wpa_supplicant( 4164): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4164): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4164): WPS: Set UUID for interface wlan0
,D/wpa_supplicant( 4164): WPS: UUID based on MAC address - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4164): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4164): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4164): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4164): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4164): Using existing control interface directory.
I/wpa_supplicant( 4164): 0xb72e2cc8 HY init priv-sock 18 p2p_disabled: 0 path: /data/misc/wifi/sockets/wlan0 name:/data/misc/wifi/sockets/wlan0 ctrl_interface: /data/misc/wifi/sockets, ifname: wlan0
I/wpa_supplicant( 4164): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4164): [ITEC] ASSIGN CALL BACK A1 6
D/wpa_supplicant( 4164): lge_eap_carrier_var_init
D/wpa_supplicant( 4164): realm format : @wlan.mnc<MNC>.mcc<MCC>.3gppnetwork.org 
D/wpa_supplicant( 4164): wlan0: Added interface wlan0
D/wpa_supplicant( 4164): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4164): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4164): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4164): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4164): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4164): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4164): driver_param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4164): update_config=1
D/wpa_supplicant( 4164): device_name='Thali Test's G2'
D/wpa_supplicant( 4164): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4164): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4164): persistent_reconnect=1
,D/wpa_supplicant( 4164): Reading configuration file '/system/etc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4164): update_config=1
D/wpa_supplicant( 4164): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4164): driver_param='use_p2p_group_interface=1 use_multi_chan_concurrent=1'
,D/wpa_supplicant( 4164): eapol_version=1
D/wpa_supplicant( 4164): ap_scan=1
D/wpa_supplicant( 4164): fast_reauth=1
D/wpa_supplicant( 4164): p2p_disabled=0
D/wpa_supplicant( 4164): p2p_no_group_iface=0
I/wpa_supplicant( 4164): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4164): nl80211: RFKILL status not available
D/wpa_supplicant( 4164): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4164): nl80211: TDLS supported
D/wpa_supplicant( 4164): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4164): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4164): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4164): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4164): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 4164): nl80211: Subscribe to mgmt frames with non-AP handle 0xb72f2c28
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72f2c28
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72f2c28
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72f2c28
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72f2c28
,D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72f2c28
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72f2c28
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72f2c28
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72f2c28
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72f2c28
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72f2c28
,D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 0a 11
,D/wpa_supplicant( 4164): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4164): nl80211: driver param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4164): nl80211: Use separate P2P group interface
D/wpa_supplicant( 4164): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4164): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4164): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4164): nl80211: 2457-2482 @ 20 MHz
,D/wpa_supplicant( 4164): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4164): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4164): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4164): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4164): p2p0: Own MAC address: 36:fc:ef:de:0a:e2
,D/wpa_supplicant( 4164): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4164): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 4164): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4164): p2p0: State: DISCONNECTED -> INACTIVE
,D/wpa_supplicant( 4164): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4164): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4164): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 4164): WPS: UUID from the first interface - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4164): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4164): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4164): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4164): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4164): Using existing control interface directory.
I/wpa_supplicant( 4164): 0xb72f2098 HY init priv-sock 23 p2p_disabled: 0 path: /data/misc/wifi/sockets/p2p0 name:/data/misc/wifi/sockets/p2p0 ctrl_interface: /data/misc/wifi/sockets, ifname: p2p0
I/wpa_supplicant( 4164): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4164): [ITEC] ASSIGN CALL BACK A1 6
I/wpa_supplicant( 4164): [ITEC] sizeof wpa_ssid: 544 / wpa_config: 504 / wpa_supplicant: 1456 / wpa_global: 208 in module
I/wpa_supplicant( 4164): [ITEC] Open WIFLUS socket interface - START
I/wpa_supplicant( 4164): [ITEC] SHARED LIBRARY INITIALIZED Ver: ITEC-LIB-VER-0.98 Tested @: JB44 Build Date Oct 16 2013 19:28:22
I/wpa_supplicant( 4164): [ITEC] USE NON-INET
I/wpa_supplicant( 4164): [ITEC] Open WIFLUS socket interface - DONE 24
,I/wpa_supplicant( 4164): HY wiflus comm channel initialized
D/wpa_supplicant( 4164): P2P: Own listen channel: 6
I/wpa_supplicant( 4164): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/wpa_supplicant( 4164): P2P: Random operating channel: 81:6
D/wpa_supplicant( 4164): P2P: Add operating class 81
D/wpa_supplicant( 4164): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 4164): P2P: Add operating class 115
,D/wpa_supplicant( 4164): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 4164): P2P: wpas_p2p_pre_check_prefered_channel() - Invalid parameter. Just Initialized
D/wpa_supplicant( 4164): p2p0: Added interface p2p0
D/wpa_supplicant( 4164): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4164): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 4164): Get randomness: len=20 entropy=0
D/wpa_supplicant( 4164): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,D/wpa_supplicant( 4164): CTRL_IFACE monitor attached - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4164): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4164): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4164): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4164): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4164): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4164): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  965): transitionTo: destState=SupplicantStartingState
,D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  965): invokeExitMethods: InitialState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine(  965): invokeEnterMethods: SupplicantStartingState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131144
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
,D/WifiStateMachine(  965): deferMessage: msg=131144
D/WifiStateMachine(  965): handleMessage: X
I/bt_hwcfg( 1222): Releasing 4335 AXI BRIDGE lock
D/WifiStateMachine(  965): handleMessage: E msg.what=131085
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): deferMessage: msg=131085
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131149
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): setSuspendOptimizations: 2 true
D/WifiStateMachine(  965): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131145
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131146
,D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131101
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147457
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): Supplicant connection established
,D/WifiNative-wlan0(  965): doString: DRIVER MACADDR
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=14): 44 52 49 56 45 52 20 4d 41 43 41 44 44 52
,D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER MACADDR'
D/WifiNative-wlan0(  965):    returned Macaddr = 34:fc:ef:de:0a:e2
,D/WifiStateMachine(  965): MAC Addr from driver = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  965): setWifiState: enabled
D/WifiOffDelayIfNotUsed(  965): setPowerSaveActivated(false)
,D/WifiActivationWhileCharging(  965): unregister : we don't need to unregister
E/WifiStateMachine(  965): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  965): useWiFiOffloading() : false
E/WifiStateMachine(  965): CONFIG_LGE_WLAN_PATH : true
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiConfigStore(  965): Loading config and enabling all networks
,D/WifiNative-wlan0(  965): doString: LIST_NETWORKS
,D/WfdService( 1156): Waiting for WifiP2p enabling
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/WifiServiceExtension(  965): WIFI_STATE_CHANGED_ACTION [3]
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
,D/wpa_supplicant( 4164): wlan0: Control interface command 'LIST_NETWORKS'
D/WifiNative-wlan0(  965):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  965): 0	NG700	any	
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 ssid
,I/WifiServiceExtension(  965): batteryPsActivateMsgHandler : state:0 event:3
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=18): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 73 69 64
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 bssid
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 62 73 73 69 64
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
,D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'bssid'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 priority
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 6f 72 69 74 79
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 scan_ssid
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 63 61 6e 5f 73 73 69 64
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
,D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_tx_keyidx
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 74 78 5f 6b 65 79 69 64 78
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key0
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 30
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'wep_key0'
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key1
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 31
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
,D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'wep_key1'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key2
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 32
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'wep_key2'
,D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key3
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 33
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'wep_key3'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 psk
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 73 6b
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4164): Do not allow key_data field to be exposed
,D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 proto
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 6f 74 6f
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 key_mgmt
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 6d 67 6d 74
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
,D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 auth_alg
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 75 74 68 5f 61 6c 67
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 pairwise
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 69 72 77 69 73 65
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
,D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 group
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 67 72 6f 75 70
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 eap
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 61 70
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='eap'
,D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'eap'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 phase2
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 32
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'phase2'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 identity
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'identity'
,D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 anonymous_identity
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=32): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 6e 6f 6e 79 6d 6f 75 73 5f 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 password
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 73 73 77 6f 72 64
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='password'
,D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'password'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 client_cert
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 6c 69 65 6e 74 5f 63 65 72 74
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'client_cert'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 ca_cert
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=21): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 61 5f 63 65 72 74
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
,D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'ca_cert'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 subject_match
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 75 62 6a 65 63 74 5f 6d 61 74 63 68
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'subject_match'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 engine
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 engine'
,D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 engine_id
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65 5f 69 64
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'engine_id'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 key_id
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 69 64
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
,D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'key_id'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 phase1
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 31
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 phase1'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='phase1'
D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'phase1'
D/WifiConfigStore(  965): ***WAPI : not WAPI
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 private_key
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 76 61 74 65 5f 6b 65 79
D/wpa_supplicant( 4164): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 4164): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
,D/wpa_supplicant( 4164): CTRL_IFACE: Failed to get network variable 'private_key'
E/WifiConfigStore(  965): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  965): doBoolean: SET device_name g2_open_com
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=27): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 67 32 5f 6f 70 65 6e 5f 63 6f 6d
D/wpa_supplicant( 4164): wlan0: Control interface command 'SET device_name g2_open_com'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'device_name'='g2_open_com'
D/wpa_supplicant( 4164): device_name='g2_open_com'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET manufacturer LGE
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=20): 53 45 54 20 6d 61 6e 75 66 61 63 74 75 72 65 72 20 4c 47 45
D/wpa_supplicant( 4164): wlan0: Control interface command 'SET manufacturer LGE'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'manufacturer'='LGE'
D/wpa_supplicant( 4164): manufacturer='LGE'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET model_name LG-D802
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 53 45 54 20 6d 6f 64 65 6c 5f 6e 61 6d 65 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4164): wlan0: Control interface command 'SET model_name LG-D802'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'model_name'='LG-D802'
D/wpa_supplicant( 4164): model_name='LG-D802'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET model_number LG-D802
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=24): 53 45 54 20 6d 6f 64 65 6c 5f 6e 75 6d 62 65 72 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4164): wlan0: Control interface command 'SET model_number LG-D802'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'model_number'='LG-D802'
D/wpa_supplicant( 4164): model_number='LG-D802'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET serial_number 022678fb504e29b0
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=34): 53 45 54 20 73 65 72 69 61 6c 5f 6e 75 6d 62 65 72 20 30 32 32 36 37 38 66 62 35 30 34 65 32 39 ...
D/wpa_supplicant( 4164): wlan0: Control interface command 'SET serial_number 022678fb504e29b0'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'serial_number'='022678fb504e29b0'
,D/wpa_supplicant( 4164): serial_number='022678fb504e29b0'
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: SET config_methods physical_display virtual_push_button keypad
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 70 68 79 73 69 63 61 6c 5f 64 69 73 70 ...
D/wpa_supplicant( 4164): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button keypad'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4164): config_methods='physical_display virtual_push_button keypad'
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4164): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): transitionTo: destState=DriverStartedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=3,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  965): invokeExitMethods: SupplicantStartingState
,D/WifiStateMachine(  965): moveTempStackToStateStack: i=2,j=1
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=2
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=3
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=3,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine(  965): invokeEnterMethods: SupplicantStartedState
,D/WifiNative-wlan0(  965): doBoolean: SCAN_INTERVAL 15
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=16): 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c 20 31 35
D/wpa_supplicant( 4164): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 4164): wlan0: Setting scan interval: 15 sec
,D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): invokeEnterMethods: DriverStartedStateExt
D/WifiStateMachine(  965): invokeEnterMethods: DriverStartedState
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXSCAN-STOP
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=22): 44 52 49 56 45 52 20 42 54 43 4f 45 58 53 43 41 4e 2d 53 54 4f 50
D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setDetailed state, old =IDLE and new state=DISCONNECTED
,D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-REMOVE 3
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 33
D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 3'
,D/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd  len = 0, 0
W/Settings( 3279): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/PCSuite ( 4165): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
,D/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-REMOVE 2
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 32
D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): Attempting to reconnect to wifi network ..
D/LGDMClient( 2818): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiNative-wlan0(  965): doBoolean: RECONNECT
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
,D/wpa_supplicant( 4164): wlan0: Control interface command 'RECONNECT'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doString: STATUS
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4164): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiNative-wlan0(  965):    returned wpa_state=DISCONNECTED
D/WifiNative-wlan0(  965): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  965): address=34:fc:ef:de:0a:e2
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  965): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  965): handleScreenStateChanged: true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4164): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4164): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  965):    returned true
,D/LGDMClient( 2818): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/WifiP2pService(  965): P2pDisabledState{ when=-3ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine(  965): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/wpa_supplicant( 4164): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 4164): wlan0: nl80211: scan request
D/wpa_supplicant( 4164): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=DriverStartedStateExt
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectModeState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131144
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131085
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/CommandListener(  271): Setting iface cfg
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=132106
D/CommandListener(  271): Trying to bring up p2p0
D/wpa_supplicant( 4164): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 4164): nl80211: Event message available
D/wpa_supplicant( 4164): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 4164): wlan0: nl80211: Scan trigger
D/WifiMonitor(  965): WifiMonitorSingleton gotten
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiMonitor(  965): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  965): setWifiDualbandAPConnection band : 1
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=21): 44 55 41 4c 42 41 4e 44 5f 41 50 5f 43 4f 4e 4e 45 43 54 20 31
D/wpa_supplicant( 4164): wlan0: Control interface command 'DUALBAND_AP_CONNECT 1'
E/wpa_supplicant( 4164): nWIFIDualbandAPConnection: 1
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=132096
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  965): set CMD_DISCONNECT_RSSI_LVL : -100
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=24): 44 49 53 43 4f 4e 4e 45 43 54 5f 52 53 53 49 5f 4c 56 4c 20 2d 31 30 30
D/wpa_supplicant( 4164): wlan0: Control interface command 'DISCONNECT_RSSI_LVL -100'
I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4233 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiP2pService(  965): P2pEnablingState
D/WifiP2pService(  965): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2p socket connection successful
D/WifiP2pService(  965): P2pEnabledState
E/wpa_supplicant( 4164): disconnect_rssi_lvl: -100
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131127
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  965): processMsg: ConnectModeState
V/WfdStateTracker( 1156): WfdStateTracker handleDirectStateChangedEvent: 2
D/WifiNative-p2p0(  965): doBoolean: SET persistent_reconnect 1
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=143371
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 4164): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4164): persistent_reconnect=1
D/wpa_supplicant( 4164): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  965):    returned true
D/WifiP2pService(  965): sending p2p connection changed broadcast
D/WifiNative-p2p0(  965): doBoolean: SET device_name Thali Test's G2
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=31): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 54 68 61 6c 69 20 54 65 73 74 27 73 20 47 32
D/wpa_supplicant( 4164): p2p0: Control interface command 'SET device_name Thali Test's G2'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'device_name'='Thali Test's G2'
D/wpa_supplicant( 4164): device_name='Thali Test's G2'
D/WifiNative-p2p0(  965):    returned true
D/WifiServiceExtension(  965): postfix byte check : 15
D/WifiNative-p2p0(  965): doBoolean: SET p2p_ssid_postfix -Thali Test's G2
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=37): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 54 68 61 6c 69 20 54 65 73 74 ...
D/wpa_supplicant( 4164): p2p0: Control interface command 'SET p2p_ssid_postfix -Thali Test's G2'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'p2p_ssid_postfix'='-Thali Test's G2'
D/wpa_supplicant( 4164): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4164): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4164): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 4164): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4164): config_methods='virtual_push_button physical_display keypad'
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: P2P_SET conc_pref sta
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=21): 50 32 50 5f 53 45 54 20 63 6f 6e 63 5f 70 72 65 66 20 73 74 61
D/wpa_supplicant( 4164): p2p0: Control interface command 'P2P_SET conc_pref sta'
D/wpa_supplicant( 4164): Single channel concurrency preference: sta
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doString: STATUS
D/wpa_supplicant( 4164): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-p2p0(  965):    returned p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  965): p2p_state=IDLE
D/WifiNative-p2p0(  965): wifi_display=1
D/WifiNative-p2p0(  965): ifname=p2p0
D/WifiNative-p2p0(  965): address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  965): ifname=wlan0
D/WifiNative-p2p0(  965): address=34:fc:ef:de:0a:e2
D/WifiNative-p2p0(  965): doBoolean: P2P_FLUSH
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=9): 50 32 50 5f 46 4c 55 53 48
D/wpa_supplicant( 4164): p2p0: Control interface command 'P2P_FLUSH'
D/wpa_supplicant( 4164): P2P: Stopping find
D/wpa_supplicant( 4164): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 4164): P2P: State IDLE -> IDLE
D/wpa_supplicant( 4164): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: P2P_SERVICE_FLUSH
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=17): 50 32 50 5f 53 45 52 56 49 43 45 5f 46 4c 55 53 48
D/wpa_supplicant( 4164): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doString: LIST_NETWORKS
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4164): p2p0: Control interface command 'LIST_NETWORKS'
D/WifiNative-p2p0(  965):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  965): doBoolean: SAVE_CONFIG
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 4164): p2p0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 4164): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf.tmp'
D/WifiP2pService(  965): [LGE_P2P] initializeP2pSettings() check postfix
D/WifiP2pService(  965): before postfix = Thali Test's G2
D/WifiP2pService(  965): after postfix = Thali Test's G2
D/WifiP2pService(  965): DeviceAddress: 36:fc:ef:de:0a:e2
I/WfdStateTracker( 1156): handleP2pThisDeviceChanged
D/HyLog   ( 4233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4233): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 4164): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4164): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiNative-p2p0(  965):    returned true
,E/WifiServiceExtension(  965): No p2p device connected
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiP2pService(  965): sending p2p persistent groups changed broadcast
D/WifiP2pService(  965): InactiveState
D/WifiP2pService(  965): InactiveState{ when=-12ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-12ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): DefaultState{ when=-12ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): InactiveState{ when=-12ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-12ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): DefaultState{ when=-12ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGDMSGCM( 4233): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
,I/bt_hwcfg( 1222): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 1222): Settlement delay -- 100 ms
W/ContextImpl( 4233): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/ActivityManager(  965): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4257 uid=10101 gids={50101, 1028, 1015, 3003}
I/ActivityManager(  965): Killing 3279:com.google.android.talk/u0a77 (adj 15): empty #17
,D/HyLog   ( 4257): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4257): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4257): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/Wireless_Storage( 4257): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
V/[BNRBootReceiver]( 3995): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 3995): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,I/ActivityManager(  965): Killing 3932:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/bt_hwcfg( 1222): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 1222): Setting local bd addr to 34:FC:EF:9D:93:0B
,I/bt_hwcfg( 1222): vendor lib fwcfg completed
,I/bt-btif ( 1222): HC preload_cb 0 [0:SUCCESS 1:FAIL]
,I/        ( 1222): BTE_InitTraceLevels -- TRC_HCI
I/        ( 1222): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 1222): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 1222): BTE_InitTraceLevels -- TRC_OBEX
I/        ( 1222): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 1222): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 1222): BTE_InitTraceLevels -- TRC_A2D
I/        ( 1222): BTE_InitTraceLevels -- TRC_BNEP
,I/        ( 1222): BTE_InitTraceLevels -- TRC_BTM
I/        ( 1222): BTE_InitTraceLevels -- TRC_GAP
I/        ( 1222): BTE_InitTraceLevels -- TRC_PAN
I/        ( 1222): BTE_InitTraceLevels -- TRC_SAP
I/        ( 1222): BTE_InitTraceLevels -- TRC_SDP
I/        ( 1222): BTE_InitTraceLevels -- TRC_GATT
I/        ( 1222): BTE_InitTraceLevels -- TRC_SMP
I/        ( 1222): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 1222): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 1222): BTE_InitTraceLevels -- TRC_PROTOCOL
D/bt-btif ( 1222): btif_task(): received trigger stack init event, state: 1, radio_ref_count: 1, is_radio_req 0, dut_mode: 0
D/bt-btif ( 1222): btif_dm_load_ble_local_keys BLE ER key loaded
D/bt-btif ( 1222): btif_dm_load_ble_local_keys BLE ID keys loaded
I/bt-btif ( 1222): bta_dm_sm_execute event:0x0
I/bt-btif ( 1222): bta_sys_sm_execute state:0, event:0x0
I/bt-btif ( 1222): bta_sys_hw_api_enable for 0, active modules 0x0001
I/bt-btif ( 1222): bta_sys_sm_execute state:1, event:0x1
,I/bt-btif ( 1222): bta_sys_hw_evt_enabled for 0
,D/bt-btif ( 1222):  bta_sys_hw_btm_cback was called with parameter: 0
,I/bt-btif ( 1222): bta_sys_sm_execute state:1, event:0x2
D/bt-btif ( 1222):  bta_sys_hw_evt_stack_enabled!notify the callers
D/bt-btif ( 1222):  bta_dm_sys_hw_cback with event: 1
D/bt-btif ( 1222): ##################################
D/bt-btif ( 1222): bta_dm_co_ble_load_local_keys:  Load local keys if any are persisted
D/bt-btif ( 1222): ##################################
D/bt-btif ( 1222): btif_dm_get_ble_local_keys  *p_key_mask=0x03
E/bt-btm  ( 1222): BTM_SecRegister:p_cb_info->p_le_callback == 0x60b294c5 
I/bt-smp  ( 1222): SMP_Register state=0
E/bt-btm  ( 1222): BTM_SecRegister: btm_cb.api.p_le_callback = 0x60b294c5 
D/bt-btif ( 1222): bta_gattc_register state 0
D/bt-btif ( 1222): bta_gattc_enable
,I/bt-att  ( 1222): GATT_Register
D/bt-att  ( 1222): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 1222): allocated gatt_if=3
D/bt-btif ( 1222): bta_dm_gattc_callback event = 0
D/bt-btif ( 1222): BTA_GATTC_REG_EVT client_if = 3
I/bt-att  ( 1222): GATT_StartIf gatt_if=3
D/bt-att  ( 1222): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 1222): gatt_find_the_connected_bda found=0 found_idx=7
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt-btif ( 1222): btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
,D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1222): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1222): bta_dm_sm_execute event:0x2
D/bt-btif ( 1222): BTA is generating EIR
,D/bt-sdp  ( 1222): SDP_CreateRecord ok, num_records:3
I/bt-btif ( 1222): Adding UUID=0x110C into EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001000
D/bt-btif ( 1222): nsc_mask: 0x6
D/bt-btif ( 1222): bta_av_co_audio_init
D/bt-btif ( 1222): bta_av_co_audio_init: 0
,D/bt-btif ( 1222): audio[0] av_handle: 1 codec_type: 0
D/bt-btif ( 1222): bta_av_co_audio_init
D/bt-btif ( 1222): bta_av_co_audio_init: 1
D/bt-btif ( 1222): BTIF_APTX_CODEC_ID:6
D/bt-btif ( 1222): audio[1] av_handle: 2 codec_type: 255
D/bt-sdp  ( 1222): SDP_CreateRecord ok, num_records:4
,I/bt-a2d  ( 1222): A2D_AddRecord uuid: 110a
I/bt-btif ( 1222): Adding UUID=0x110A into EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001400
D/bt-btif ( 1222): rc_acp_handle:0 idx:1
,D/bt-btif ( 1222): create 0, role: 1, shdl:0, rc_handle:0, lidx:3, status:0x10
D/bt-btif ( 1222): reg_audio: 0x1
D/bt-btif ( 1222): bta_ag_scb_alloc 1
,I/bt-btif ( 1222): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 1222): SDP_CreateRecord ok, num_records:5
D/bt-btif ( 1222): bta_ag_add_record uuid: 1112
I/bt-btif ( 1222): Adding UUID=0x1112 into EIR
,D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00011400
D/bt-sdp  ( 1222): SDP_CreateRecord ok, num_records:6
D/bt-btif ( 1222): bta_ag_add_record uuid: 111f
,I/bt-btif ( 1222): Adding UUID=0x111F into EIR
D/bt-btif ( 1222): BTA is generating EIR
,I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011400
D/bt-btif ( 1222): getAccess buffer->st_uid:1000 buffer->st_gid:1028
D/bt-btif ( 1222): bta_fts_api_enable srm:1
D/bt-sdp  ( 1222): SDP_CreateRecord ok, num_records:7
,I/bt-btif ( 1222): Adding UUID=0x1106 into EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011440
D/bt-btif ( 1222): FTS:  SDP Registered (handle 0x00010006)
,I/bt-btif ( 1222): bta_fts_ci_resume status:1
I/bt-btif ( 1222): FTP SERVER enabled with Root Path [/storage]
D/bt-sdp  ( 1222): SDP_CreateRecord ok, num_records:8
I/bt-btif ( 1222): Adding UUID=0x112D into EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04011440
D/bt-btif ( 1222): bte_sap_evt: event=0
,E/bt-btif ( 1222): Calling BTA_HhEnable
D/bt-btif ( 1222): bta_gattc_register state 2
,I/bt-att  ( 1222): GATT_Register
D/bt-att  ( 1222): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 1222): allocated gatt_if=4
D/bt-btif ( 1222): bta_hh_gattc_callback event = 0
I/bt-att  ( 1222): GATT_StartIf gatt_if=4
D/bt-att  ( 1222): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1222): gatt_find_the_connected_bda found=0 found_idx=7
,D/bt-btif ( 1222): in add:1
,D/bt-btif ( 1222): Remote device:00:f4:6f:30:e0:6c, size:18
,D/bt-btif ( 1222): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1222): Remote device:e0:db:10:1f:c9:5e, size:18
,D/bt-btif ( 1222): Remote device:b0:c5:59:3f:75:69, size:18
,D/bt-btif ( 1222): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1222): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1222): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1222): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1222): Remote device:b4:ce:f6:ab:a4:6a, size:18
,D/bt-btif ( 1222): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1222): Remote device:f8:cf:c5:d9:e5:61, size:18
,D/bt-btif ( 1222): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1222): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1222): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1222): Remote device:50:2e:6c:ac:21:50, size:18
,D/bt-btif ( 1222): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1222): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1222): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1222): Remote device:f8:95:c7:87:85:54, size:18
,D/bt-btif ( 1222): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1222): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1222): Remote device:34:fc:ef:11:b1:66, size:18
,D/bt-btif ( 1222): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1222): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1222): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1222): Remote device:38:94:96:b5:06:dc, size:18
I/bt-btif ( 1222): bta_dm_sm_execute event:0x9
,D/bt-btif ( 1222): Remote device:, size:128
E/bt-btif ( 1222): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
,E/bt-btif ( 1222): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1222): out
D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:2 
D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1222): in, bd addr:, prop type:1, len:249
,I/bt-btif ( 1222): btif_storage_load_bonded_devices  BT_PROPERTY_DEVICE_MODE
D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:16 
D/bt-btif ( 1222): in, bd addr:, prop type:16, len:4
E/bt-btif ( 1222): Unknow prop type:16
,I/bt-btif ( 1222): btif_dm_get_adapter_property: type=0x10
D/bt-btif ( 1222): btif_dm_get_adapter_property btif_device_mode 0
,D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:9 
D/bt-btif ( 1222): in, bd addr:, prop type:9, len:4
D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:3 
E/bt-btif ( 1222): btif_storage_get_adapter_property service_mask:0x120148
,D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:3 devicemode 0
,D/bt-btif ( 1222): btif_storage_get_adapter_property property->type:3 devicemode 0
,I/bt-btif ( 1222): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothManagerService(  965): Bluetooth Adapter name changed to Thali Test's G2
,D/BluetoothManagerService(  965): Stored Bluetooth name: Thali Test's G2
,E/BluetoothAdapterProperties( 1222): Property change not handled in Java land:16
,I/bt-btif ( 1222): btif_storage_load_bonded_devices: 1 bonded devices found
,D/bt-btif ( 1222): in, bd addr:38:94:96:b5:06:dc, prop type:1, len:249
D/bt-btif ( 1222): in, bd addr:38:94:96:b5:06:dc, prop type:10, len:249
D/bt-btif ( 1222): in, bd addr:38:94:96:b5:06:dc, prop type:4, len:4
D/bt-btif ( 1222): in, bd addr:38:94:96:b5:06:dc, prop type:5, len:4
,D/bt-btif ( 1222): in, bd addr:38:94:96:b5:06:dc, prop type:3, len:512
,I/bt-btif ( 1222): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1222): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
,I/LGRemoteDevicePropertySetting( 1222): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1222): [BTUI] Get BRCM HeadsetService
,D/bt-btif ( 1222): btif_enable_bluetooth_evt: status 0, local bd [34:fc:ef:9d:93:0b]
,E/bt_hwcfg( 1222): hw_sco_config...
,E/bt_hwcfg( 1222): SCO PCM configure {0, 4, 0, 0, 0}
,I/bt-btif ( 1222): HC lib lpm enable=1 return 0
I/bt-btif ( 1222): BTA_BrcmInit
,I/bt-btif ( 1222): HC lpm_result_cb 1
E/bt-gki  ( 1222): ### ERROR: incorrect Process context BTIF called function btu_start_timer() ###
,D/IOP_DB_BT( 1222): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 1222): db_open: db_open : handle 1623288364l, read 7547 bytes onto local cache
D/IOP_DB_BT( 1222): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1222): db_query: result 1
,I/        ( 1222): iop_db_open: iop_db_open status 0
D/bt-btif ( 1222): btsock initializing...
D/bt-btif ( 1222): in initialized:1
D/bt-btif ( 1222): ts[7].used:1
,D/bt-btif ( 1222): ts[6].used:0
D/bt-btif ( 1222): alloc_thread_slot ret:6
,D/bt-btif ( 1222): h:6, cmd_fdr:87, cmd_fdw:88
D/bt-btif ( 1222): h:6, thread id:1641281072
I/bt-btif ( 1222): BTA_JvEnable
,D/bt-btif ( 1222): jv_dm_cback: event:0, slot id:0
D/bt-btif ( 1222): unhandled event:0, slot id:0
D/bt-btif ( 1222): btsock successfully initialized
,D/bt-btif ( 1222): jni_initialized = 1, btpan_cb.enabled:0
,D/bt-btif ( 1222): Enabling PAN....
,I/bt-btif ( 1222): bta_pan_co_init
D/bt-btif ( 1222): local_role:3
,D/bt-btif ( 1222): btpan_role:0x3
D/bt-sdp  ( 1222): SDP_CreateRecord ok, num_records:9
I/bt-btif ( 1222): Adding UUID=0x1116 into EIR
,D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04051440
I/bt-btif ( 1222): Adding UUID=0x1115 into EIR
D/bt-btif ( 1222): BTA is generating EIR
,I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1222): Adding UUID=0x1116 into EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
,I/bt-btif ( 1222): Removing UUID=0x1117 from EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1222): Adding UUID=0x1115 into EIR
,D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
,I/bte_conf( 1222): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 1222): [1] primary_record=1 vendor_id=0x00C4 vendor_id_source=0x0001 product_id=0x13A1 version=0x1000
,I/bt-btif ( 1222): bta_dm_sm_execute event:0x31
D/bt-sdp  ( 1222): SDP_CreateRecord ok, num_records:10
I/bt-btif ( 1222): Adding UUID=0x1200 into EIR
D/bt-btif ( 1222): BTA is generating EIR
,I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000084 04071440
I/bt-btif ( 1222): bte did registered::handle: 0x10009, bta status: 0 (0==OK)
,I/bte_conf( 1222): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 1222): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/bt-btif ( 1222): btif_dm_load_local_oob prop_oob = 3
,I/bt-btif ( 1222): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothServiceJni( 1222): adapter_state_change_callback: Status is: 1
D/bt_h4   ( 1222): vendor lib postload completed
,I/bt-btif ( 1222): HC postload_cb 0
D/bt-btif ( 1222): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 1222): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
,D/bt-btif ( 1222): btif_av_state_idle_handler devicemode: 0
,D/bt-btif ( 1222): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 1222): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
,D/bt-btif ( 1222): btif_fts_upstreams_evt: event=BTA_FTS_ENABLE_EVT
,I/bt-btif ( 1222): File Transfer: Enable Complete
,I/bt-btif ( 1222): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1222): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1222): onFtpServerEnabled: /storage
D/bt-btif ( 1222): btif_sc_upstreams_evt: event=BTA_SC_ENABLE_EVT
D/bt-btif ( 1222): btif_hh_upstreams_evt: event=BTA_HH_ENABLE_EVT
,D/BluetoothAdapterState( 1222): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1222): ScanMode =  20
D/BluetoothAdapterProperties( 1222): State =  11
,D/BluetoothAdapterProperties( 1222): mDiscoverableTimeout =  120
I/bt-btif ( 1222): btif_set_adapter_property type: 7, len 4, 0x428c3bb8
I/bt-btif ( 1222): set property scan mode : 1
,I/bt-btif ( 1222): bta_dm_sm_execute event:0x3
I/bt-btif ( 1222): btif_in_storage_request_copy_cb
I/bt-btif ( 1222): btif_set_adapter_property type: 9, len 4, 0x428c3c10
I/bt-btif ( 1222): btif_in_storage_request_copy_cb
I/BluetoothAdapterState( 1222): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 1222): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  965): Message: 60
D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService(  965): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothPan(  965): onBluetoothStateChange(on) call bindService
,V/BluetoothAdapterService( 1222): startPbapService
W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:510 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1164 
,D/bt-btif ( 1222): btif_hh_upstreams_evt: BTA_HH_ENABLE_EVT: status =0
,D/bt-btif ( 1222): btif_hh_upstreams_evt--Loading added devices
,D/bt-btif ( 1222): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1222): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1222): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1222): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1222): Remote device:14:b4:84:21:3b:49, size:18
,D/bt-btif ( 1222): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1222): Remote device:58:3f:54:73:64:c0, size:18
,D/bt-btif ( 1222): Remote device:10:d3:8a:fb:85:d4, size:18
,D/bt-btif ( 1222): Remote device:b4:ce:f6:ab:a4:6a, size:18
,D/bt-btif ( 1222): Remote device:08:ec:a9:50:75:41, size:18
,D/bt-btif ( 1222): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1222): Remote device:08:ec:a9:50:76:27, size:18
,D/bt-btif ( 1222): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1222): Remote device:44:80:eb:7b:5a:05, size:18
,D/bt-btif ( 1222): Remote device:50:2e:6c:ac:21:50, size:18
,D/BluetoothHeadset( 1450): onBluetoothStateChange: up=true
D/bt-btif ( 1222): Remote device:7c:f9:0e:37:96:ab, size:18
,D/bt-btif ( 1222): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1222): Remote device:34:fc:ef:11:ae:67, size:18
,D/bt-btif ( 1222): Remote device:f8:95:c7:87:85:54, size:18
,D/BluetoothHeadset( 1450): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1450): onBluetoothStateChange: up=true
D/BluetoothA2dp(  965): onBluetoothStateChange: up=true
,D/bt-btif ( 1222): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1222): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1222): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1222): Remote device:90:e7:c4:f6:69:77, size:18
I/BluetoothAdapterState( 1222): Entering On State
,D/bt-btif ( 1222): Remote device:90:e7:c4:3c:62:6a, size:18
,D/LGBluetoothServiceAdapter( 1222): [BTUI] OnState
D/bt-btif ( 1222): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1222): Remote device:38:94:96:b5:06:dc, size:18
D/bt-btif ( 1222): Remote device:, size:18
D/BluetoothHeadset(  965): onBluetoothStateChange: up=true
,E/bt-btif ( 1222): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
,D/bt-btif ( 1222): BTA_PAN_ENABLE_EVT
,D/bt-btif ( 1222): bta_pan_role:0x5
D/BluetoothPanServiceJni( 1222): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/bt-btif ( 1222): execute storage request event : 2
,I/bt-btif ( 1222): type: 7, len 4, 0x60640376
D/bt-btif ( 1222): in, bd addr:, prop type:7, len:4
,I/bt-btif ( 1222): HAL bt_hal_cbacks->adapter_properties_cb
,D/LGBluetoothServiceAdapter( 1222): [BTUI]         global_name: Thali Test's G2
,D/BluetoothManagerService(  965): Bluetooth State Change Intent: 11 -> 12
I/bt-btif ( 1222): execute storage request event : 2
,I/bt-btif ( 1222): type: 9, len 4, 0x606403c2
D/bt-btif ( 1222): in, bd addr:, prop type:9, len:4
,I/bt-btif ( 1222): HAL bt_hal_cbacks->adapter_properties_cb
,D/LGBluetoothServiceAdapter( 1222): [BTUI]         local_name: Thali Test's G2
D/LGBluetoothAPIService( 1156): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(1116087104)( 1222): Get Bonded Devices being called
,D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42862340
,W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
V/BluetoothPbapService( 1222): Pbap Service onCreate
D/BluetoothAdapterService(1116087104)( 1222): Quiet mode Enabled = false
V/BluetoothPbapService( 1222): Starting PBAP service
D/BluetoothAdapterService(1116087104)( 1222): Initiate auto connection on BT on...
D/BluetoothAdapterService( 1222): [BTUI] autoConnect() : not allowed
D/LGBluetoothAPIService( 1156): Message: 1
D/LGBluetoothAPIService( 1156): MESSAGE_BOOT_COMPLETED
,I/LGBluetoothAPIService( 1156): [BTUI] LGBluetoothAPIService Binding Success
,D/LGBluetoothPbapAdapter( 1222): [BTUI] getInstance : create
V/BluetoothPbapService( 1222): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapService( 1222): state: 12
,D/BluetoothManagerService(  965): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  965): Message: 40
D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 1222): onReceive
,D/BluetoothMapService( 1222): STATE_ON
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/BluetoothPbapReceiver( 1222): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1222): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1222): ***********state = 12
,V/BluetoothPbapService( 1222): Handler(): got msg=1
,V/BluetoothPbapService( 1222): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 1222): Pbap Service initSocket
,D/LGBluetoothAPIServer( 1222): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1222): [BTUI] onBind()
,D/LocalBluetoothProfileManager( 2563): Adding local A2DP profile
D/LGBluetoothAPIService( 1156): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1156): Message: 100
D/LGBluetoothAPIService( 1156): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothMapService( 1222): Handler(): got msg=1
,D/BluetoothMapService( 1222): Map Service startRfcommSocketListener
,D/BluetoothMapService( 1222): Map Service initSocket
D/BluetoothManagerService(  965): Message: 30
,D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 1222): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1222): SOCK FLAG = 1 ***********************
D/bt-btif ( 1222): btsock_rfc_listen, service_name:OBEX Phonebook Access Server
D/bt-btif ( 1222): BTA_JvCreateRecordByUser:OBEX Phonebook Access Server
I/bt-btif ( 1222): BTA_JvCreateRecordByUser
D/bt-btif ( 1222): jv_dm_cback: event:11, slot id:1
D/bt-btif ( 1222): name:OBEX Phonebook Access Server, scn:19
D/bt-btif ( 1222): add_pbap_sdd:scn 19, service name OBEX Phonebook Access Server
D/bt-sdp  ( 1222): SDP_CreateRecord ok, num_records:11
I/bt-btif ( 1222): Adding UUID=0x112F into EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000094 04071440
D/bt-btif ( 1222): PBS:  SDP Registered (handle 0x0001000a)
I/bt-btif ( 1222): BTA_JvRfcommStartServer
D/bt-btif ( 1222): bta_jv_rfcomm_start_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1222): bta_jv_alloc_rfc_cb port_handle:6 handle:0x81
,D/LGBluetoothServiceAdapter( 1222): [BTUI] createSocketChannel FD=90 mFd=0
V/BluetoothPbapService( 1222): Succeed to create listening socket 
,V/BluetoothPbapService( 1222): Accepting socket connection...
,W/BluetoothAdapter( 1222): getBluetoothService() called with no BluetoothManagerCallback
E/BatteryObserver( 1156): usb Uevent not necessary.
,W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1207 
D/LocalBluetoothProfileManager( 2563): Adding local HEADSET profile
E/BluetoothServiceJni( 1222): SOCK FLAG = 1 ***********************
D/bt-btif ( 1222): btsock_rfc_listen, service_name:MAP SMS/MMS
D/bt-btif ( 1222): BTA_JvCreateRecordByUser:MAP SMS/MMS
I/bt-btif ( 1222): BTA_JvCreateRecordByUser
D/bt-btif ( 1222): jv_dm_cback: event:11, slot id:2
D/bt-btif ( 1222): name:MAP SMS/MMS, scn:6
D/bt-btif ( 1222): add_maps_sdd:scn 6, service name MAP SMS/MMS
D/bt-sdp  ( 1222): SDP_CreateRecord ok, num_records:12
D/BluetoothManagerService(  965): Message: 30
I/bt-btif ( 1222): Adding UUID=0x1132 into EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071440
D/bt-btif ( 1222): MAPSS:  SDP Registered (handle 0x0001000b)
I/bt-btif ( 1222): BTA_JvRfcommStartServer
D/bt-btif ( 1222): bta_jv_rfcomm_start_server: sec id in use:1, rfc_cb in use:1
D/bt-btif ( 1222): bta_jv_alloc_rfc_cb port_handle:7 handle:0x82
D/LGBluetoothServiceAdapter( 1222): [BTUI] createSocketChannel FD=92 mFd=90
V/BluetoothMapService( 1222): Succeed to create listening socket 
,D/BluetoothMapService( 1222): Accepting socket connection...
,D/BluetoothManagerService(  965): Message: 30
,D/BluetoothManagerService(  965): Message: 30
W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1204 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1210 
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/LocalBluetoothProfileManager( 2563): Adding local MAP profile
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/BluetoothMap( 2563): Create BluetoothMap proxy object
,D/BluetoothManagerService(  965): Message: 30
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/BluetoothManagerService(  965): Message: 30
,D/LocalBluetoothProfileManager( 2563): LocalBluetoothProfileManager construction complete
,V/BluetoothPbapService( 1222): Pbap Service onBind
W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1213 
D/WifiController(  965): battery changed pluggedType: 2
W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1219 
,W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:72 
,D/LGBluetoothUserBindClient( 2563): [BTUI] initUserBindClient
,D/DockEventReceiver( 2563): finishStartingService: stopping service
,D/BluetoothA2dp( 2563): Proxy object connected
,D/A2dpProfile( 2563): Bluetooth service connected
,W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/BluetoothHeadset( 2563): Proxy object connected
,D/HeadsetProfile( 2563): Bluetooth service connected
D/BluetoothInputDevice( 2563): Proxy object connected
,D/HidProfile( 2563): Bluetooth service connected
,D/BluetoothPan( 2563): BluetoothPAN Proxy object connected
,D/PanProfile( 2563): Bluetooth service connected
D/BluetoothMap( 2563): Proxy object connected
,D/MapProfile( 2563): Bluetooth service connected
D/BluetoothMap( 2563): getConnectedDevices()
,V/BluetoothMapService( 1222): getConnectedDevices()
D/BluetoothPbap( 2563): Proxy object connected
D/PbapServerProfile( 2563): Bluetooth service connected
,D/LGBluetoothUserBindClient( 2563): [BTUI] onServiceConnected
,D/BluetoothPermissionRequest( 2563): onReceive
,D/LGBluetoothFeatureConfig( 2563): isPrivacyLogsEnabled : true
,E/LGBluetoothUtils( 2563): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGBluetoothResetSettingReceiver( 2563): return without doing reset settings.
V/BluetoothOppReceiver( 1222): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 1222): [BTUI] startOppService()
,V/BluetoothOppManager( 1222): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 1222): isPrivacyLogsEnabled : true
,V/BtOppService( 1222): onCreate
,D/LGBluetoothOppAdapter( 1222): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothOppNotification( 1222): send message
,V/BtOppService( 1222): Starting RfcommListener
,D/BluetoothOppPreference( 1222): Dumping Names:  
D/BluetoothOppPreference( 1222): {}
D/BluetoothOppPreference( 1222): Dumping Channels:  
,D/BluetoothOppPreference( 1222): {}
V/BtOppService( 1222): onStartCommand
,V/BtOppService( 1222): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothOppNotification( 1222): new notify threadi!
,V/BluetoothOppNotification( 1222): send delay message
,V/BtOppService( 1222): start RfcommListener
V/BluetoothOppProvider( 1222): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1222): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,V/BtOppService( 1222): Deleted complete outbound shares, number =  0
V/BtOppService( 1222): RfcommListener started
,V/BtOppService( 1222): ContentObserver received notification
V/BluetoothOppProvider( 1222): created cursor android.database.sqlite.SQLiteCursor@428f5ec0 on behalf of 
V/BtOppRfcommListener( 1222): Starting RFCOMM listener....
,V/BluetoothOppNotification( 1222): mUpdateCompleteNotification = true
V/BtOppService( 1222): ContentObserver received notification
V/BluetoothOppProvider( 1222): created cursor android.database.sqlite.SQLiteCursor@428f5898 on behalf of 
V/BtOppService( 1222): Deleted complete inbound failed shares, number = 0
,V/BluetoothOppProvider( 1222): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1222): created cursor android.database.sqlite.SQLiteCursor@428f9028 on behalf of 
,V/BluetoothOppProvider( 1222): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BtOppService( 1222): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 1222): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/AuthorizationBluetoothService( 1540): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothOppProvider( 1222): created cursor android.database.sqlite.SQLiteCursor@428fa938 on behalf of 
,E/AuthorizationBluetoothService( 1540): Proximity feature is not enabled.
V/BluetoothOppProvider( 1222): created cursor android.database.sqlite.SQLiteCursor@428fb9c0 on behalf of 
,W/BluetoothAdapter( 1222): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 1222): outbound: succ-0  fail-0
E/BluetoothServiceJni( 1222): SOCK FLAG = 0 ***********************
D/bt-btif ( 1222): btsock_rfc_listen, service_name:OBEX Object Push
D/bt-btif ( 1222): BTA_JvCreateRecordByUser:OBEX Object Push
I/bt-btif ( 1222): BTA_JvCreateRecordByUser
D/bt-btif ( 1222): jv_dm_cback: event:11, slot id:3
D/bt-btif ( 1222): name:OBEX Object Push, scn:12
D/bt-btif ( 1222): scn 12, service name OBEX Object Push
D/bt-sdp  ( 1222): SDP_CreateRecord ok, num_records:13
D/LGBluetoothServiceAdapter( 1222): [BTUI] createSocketChannel FD=97 mFd=92
I/bt-btif ( 1222): Adding UUID=0x1105 into EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071460
I/bt-btif ( 1222): BTA_JvRfcommStartServer
D/bt-btif ( 1222): bta_jv_rfcomm_start_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1222): bta_jv_alloc_rfc_cb port_handle:8 handle:0x83
V/BtOppRfcommListener( 1222): Started RFCOMM listener....
I/BtOppRfcommListener( 1222): Accept thread started.
,V/BtOppRfcommListener( 1222): Accepting connection...
,V/BluetoothOppNotification( 1222): update too frequent, put in queue
V/BtOppService( 1222): pendingUpdate is false keepUpdateThread is false sListenStarted is true
,V/BluetoothOppNotification( 1222): outbound notification was removed.
,V/BluetoothOppProvider( 1222): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1222): created cursor android.database.sqlite.SQLiteCursor@428ff1f8 on behalf of 
,V/BluetoothOppNotification( 1222): inbound: succ-0  fail-0
V/BluetoothOppNotification( 1222): inbound notification was removed.
,V/BluetoothOppProvider( 1222): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1222): created cursor android.database.sqlite.SQLiteCursor@429008e0 on behalf of 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4164): EAPOL: disable timer tick
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4164): EAPOL: disable timer tick
,D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671280035, nextTick: 59997, mDrawingTime: 0
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671280037, nextTick: 59996, mDrawingTime: 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/BluetoothOppNotification( 1222): new notify threadi!
,V/BluetoothOppNotification( 1222): send delay message
,V/BluetoothOppProvider( 1222): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1222): created cursor android.database.sqlite.SQLiteCursor@42902a50 on behalf of 
,V/BluetoothOppNotification( 1222): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1222): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1222): created cursor android.database.sqlite.SQLiteCursor@42904688 on behalf of 
,V/BluetoothOppNotification( 1222): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1222): outbound notification was removed.
,V/BluetoothOppProvider( 1222): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1222): created cursor android.database.sqlite.SQLiteCursor@42906218 on behalf of 
,V/BluetoothOppNotification( 1222): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1222): inbound notification was removed.
,V/BluetoothOppProvider( 1222): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1222): created cursor android.database.sqlite.SQLiteCursor@429077c0 on behalf of 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/AudioFlinger(  277): releaseWakeLock_l() AudioOut_2
,V/AudioFlinger(  277): releaseWakeLock_l() AudioOut_3
,V/AudioFlinger(  277): thread 0xb252b008 type 0 TID 1002 going to sleep
,V/AudioFlinger(  277): thread 0xb2696008 type 0 TID 872 going to sleep
,D/wpa_supplicant( 4164): nl80211: Event message available
D/wpa_supplicant( 4164): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 4164): wlan0: nl80211: New scan results available
D/wpa_supplicant( 4164): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 4164): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 4164): nl80211: Survey data missing
D/wpa_supplicant( 4164): wlan0: BSS: Start scan result update 1
D/wpa_supplicant( 4164): wlan0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: BSS: Add new id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: BSS: Add new id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: BSS: Add new id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: BSS: Add new id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: BSS: Add new id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: BSS: Add new id 6 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 4164): wlan0: New scan results available
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4164): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4164): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 4164): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 4164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4164): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4164): WPS: AP[3] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4164): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 4164): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-53 wps
D/wpa_supplicant( 4164): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4164): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-61
D/wpa_supplicant( 4164): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4164): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-61 wps
D/wpa_supplicant( 4164): wlan0:    selected based on RSN IE
D/wpa_supplicant( 4164): wlan0:  ,  selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 4164): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4164): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4164): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4164): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4164): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4164): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 4164): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb72e45a8  current_ssid=0x0
D/wpa_supplicant( 4164): wlan0: Selected network is configured to use SIM (sim=1 aka=1) - initialize PCSC
E/wpa_supplicant( 4164): USIM:  scard_init function
D/wpa_supplicant( 4164): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 4164): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4164): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4164): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 4164): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 4164): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 4164): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4164): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4164): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
,D/wpa_supplicant( 4164): TDLS: TDLS is allowed in the target BSS,
,I/wpa_supplicant( 4164): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 4164): wlan0: Cancelling scan request,
,D/wpa_supplicant( 4164): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
,D/wpa_supplicant( 4164): wlan0: WPA: clearing own WPA/RSN IE,
,D/wpa_supplicant( 4164): wlan0: Automatic auth_alg selection: 0x1,
,D/wpa_supplicant( 4164): RSN: PMKSA cache search - network_ctx=0xb72e45a8 try_opportunistic=0,
,D/wpa_supplicant( 4164): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
,D/wpa_supplicant( 4164): RSN: No PMKSA cache entry found,
D/wpa_supplicant( 4164): wlan0: RSN: using IEEE 802.11i/D9.0,
D/wpa_supplicant( 4164): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 4164): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4164): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4164): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 4164): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 4164): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 4164): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
,D/wpa_supplicant( 4164): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0,
,D/wpa_supplicant( 4164): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE,
D/wpa_supplicant( 4164): wlan0: No keys have been configured - skip key clearing,
,D/wpa_supplicant( 4164): wlan0: State: SCANNING -> ASSOCIATING
,D/wpa_supplicant( 4164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4164): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4164): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4164): nl80211: Set mode ifindex 23 iftype 2 (STATION),
D/wpa_supplicant( 4164): nl80211: Unsubscribe mgmt frames handle 0xb72e3590 (mode change),
D/wpa_supplicant( 4164): nl80211: Subscribe to mgmt frames with non-AP handle 0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0a
,D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0c
,D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590,
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
,D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4164): nl80211: Register frame type=0xd0 nl_handle=0xb72e3590,
D/wpa_supplicant( 4164): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4164): nl80211: Connect (ifindex=23),
D/wpa_supplicant( 4164):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4164):   * freq=2412
D/wpa_supplicant( 4164):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4164):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 4164):   * Auth Type 0,
,D/wpa_supplicant( 4164):   * WPA Versions 0x2
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 06:7c:34:12:7f:81],
D/wpa_supplicant( 4164): nl80211: Connect request send successfully
D/wpa_supplicant( 4164): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4164): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4164): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4164): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4164): RSN: Ignored PMKID candidate without preauth flag
D/wpa_supplicant( 4164): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 4164): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 64:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 9e:93:4e:3e:ba:c5],
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  965): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  965): handleMessage: E msg.what=147461
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState,
D/WifiStateMachine(  965): processMsg: DriverStartedState,
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt,
D/WifiStateMachine(  965): processMsg: SupplicantStartedState,
,D/WifiNative-wlan0(  965): doString: BSS RANGE=0- MASK=0x21987,
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 4164): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 4164): nl80211: Event message available
D/wpa_supplicant( 4164): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0,
D/wpa_supplicant( 4164): nl80211: Connect event
D/wpa_supplicant( 4164): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4164): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4164): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
,D/wpa_supplicant( 4164): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 4164): wlan0: Association info event
D/wpa_supplicant( 4164): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 4164): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4164): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 4164): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4164): wlan0: freq=2412 MHz
D/wpa_supplicant( 4164): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4164): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4164): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4164): wlan0: WPA: clearing AP WPA IE,
D/wpa_supplicant( 4164): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 4164): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): scard is not null..
,D/wpa_supplicant( 4164): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 4164): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 4164): TDLS: Remove peers on association
D/wpa_supplicant( 4164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 4164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4164): EAPOL: External notification - portEnabled=1
,D/wpa_supplicant( 4164): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4164): EAPOL: enable timer tick
D/wpa_supplicant( 4164): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4164): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4164): wlan0: Cancelling scan request
,D/wpa_supplicant( 4164): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4164): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4164): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 4164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 4164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4164): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4164): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 4164): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4164): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 27 3b 64 f1 02 da ea 52 7e a4 32 74 1f 3e 86 ...
D/wpa_supplicant( 4164): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4164): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 4164): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4164): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 4164): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 4164):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4164):   key_nonce - hexdump(len=32): 27 3b 64 f1 02 da ea 52 7e a4 32 74 1f 3e 86 fb d6 75 66 4e 3a 28 a7 56 1d 1a 84 1f 40 3e 51 20
D/wpa_supplicant( 4164):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4164):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4164):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4164):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4164): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 27 3b 64 f1 02 da ea 52 7e a4 32 74 1f 3e 86 ...
D/wpa_supplicant( 4164): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4164): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 4164): Get randomness: len=32 entropy=8
,D/wpa_supplicant( 4164): WPA: Renewed SNonce - hexdump(len=32): de ea ef 06 a2 18 83 c6 de 4b 46 cc a3 34 49 86 f1 c9 2a f1 96 13 ee 32 74 c1 28 bf 56 34 48 22
D/wpa_supplicant( 4164): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4164): WPA: Nonce1 - hexdump(len=32): de ea ef 06 a2 18 83 c6 de 4b 46 cc a3 34 49 86 f1 c9 2a f1 96 13 ee 32 74 c1 28 bf 56 34 48 22
D/wpa_supplicant( 4164): WPA: Nonce2 - hexdump(len=32): 27 3b 64 f1 02 da ea 52 7e a4 32 74 1f 3e 86 fb d6 75 66 4e 3a 28 a7 56 1d 1a 84 1f 40 3e 51 20
D/wpa_supplicant( 4164): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4164): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4164): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4164): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4164): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 4164): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4164): WPA: Derived Key MIC - hexdump(len=16): 04 dd b7 5f b5 4c 25 87 b8 ba 5c 7f 39 ed 03 36
,D/wpa_supplicant( 4164): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 de ea ef 06 a2 18 83 c6 de 4b 46 cc a3 34 49 ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  965): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 4164): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4164): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 27 3b 64 f1 02 da ea 52 7e a4 32 74 1f 3e 86 ...
D/wpa_supplicant( 4164): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 4164): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4164): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 4164): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 4164):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 4164):   key_nonce - hexdump(len=32): 27 3b 64 f1 02 da ea 52 7e a4 32 74 1f 3e 86 fb d6 75 66 4e 3a 28 a7 56 1d 1a 84 1f 40 3e 51 20
D/wpa_supplicant( 4164):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4164):   key_rsc - hexdump(len=8): 01 13 00 00 00 00 00 00
D/wpa_supplicant( 4164):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4164):   key_mic - hexdump(len=16): 8e 9a 8d 73 22 1e 39 ed 5e 5e f3 1a 79 3f e7 2a
D/wpa_supplicant( 4164): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 27 3b 64 f1 02 da ea 52 7e a4 32 74 1f 3e 86 ...
D/wpa_supplicant( 4164): RSN: encrypted key data - hexdump(len=56): 9d 29 b9 b0 71 2d ba 69 09 ac 89 27 21 d5 b4 02 9f 39 b6 46 88 1c 28 ce f0 9a 0d 8d 42 e5 8f ce ...
D/wpa_supplicant( 4164): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4164): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4164): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4164): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 01 ec ...
D/wpa_supplicant( 4164): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4164): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 4164): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 4164): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4164): WPA: Derived Key MIC - hexdump(len=16): 44 f1 01 47 c7 67 06 8a 06 85 81 c1 bb c6 47 a1
D/wpa_supplicant( 4164): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4164): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb72e3c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4164):    addr=c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 4164): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4164): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 4164): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4164): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 4164): WPA: RSC - hexdump(len=6): 01 13 00 00 00 00
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f1203a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 4164):    broadcast key
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 4164): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 4164): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4164): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4164): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 4164): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4164): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4164): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4164): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4164): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4164): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4164): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4164): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4164): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4164): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4164): EAPOL authentication completed successfully
D/wpa_supplicant( 4164): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4164): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  965): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,W/WifiMonitor(  965): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): Network connection established
,D/WifiNative-wlan0(  965): doString: STATUS
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4164): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  965):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  965): ssid=NG700
D/WifiNative-wlan0(  965): id=0
D/WifiNative-wlan0(  965): mode=station
D/WifiNative-wlan0(  965): pairwise_cipher=CCMP
D/WifiNative-wlan0(  965): group_cipher=CCMP
D/WifiNative-wlan0(  965): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  965): wpa_state=COMPLETED
D/WifiNative-wlan0(  965): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  965): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  965): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  965): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/WifiStateMachine(  965): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  965): invokeExitMethods: DisconnectedState
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=5
,D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  965): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  965): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
,D/WifiStateMachine(  965): ObtainingIpState{ when=-73ms what=147462 obj=android.net.wifi.StateChangeResult@433e7d50 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  965): StoppedState
,D/DhcpStateMachine(  965): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  965): WaitBeforeStartState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-67ms what=147462 obj=android.net.wifi.StateChangeResult@44368e78 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: ObtainingIpState
,D/WifiStateMachine(  965): ObtainingIpState{ when=-67ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ObtainingIpState
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiService(  965): New client listening to asynchronous messages
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  965): ObtainingIpState{ when=-27ms what=131155 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
,D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4164): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4164): nl80211: survey data missing!
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  965): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4352 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196612
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-24ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 4352): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4352): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4352): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/QRemote ( 4352): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4352): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4352): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4352): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4352): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4352): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4352): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/QRemote ( 4352): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4352): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/ActivityManager(  965): Killing 3967:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/WifiController(  965): battery changed pluggedType: 2
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4369 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  965): doBoolean: SET ps 0
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 4164): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 4164): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/HyLog   ( 4369): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4369): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4369): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/DhcpStateMachine(  965): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  965): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
,D/WifiStateMachine(  965): handleMessage: X
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@430cc000 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@430cc000 target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel   ( 4369): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4369): MmsConfig.loadMmsSettings
I/Babel   ( 4369): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 4369): MmsConfig.loadFromDatabase
,I/MediaCodecList( 4369): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 4369): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 4369): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4369): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 4369): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4369): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4369): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4369): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 4369): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4369): MmsConfig.loadFromResources
E/Babel   ( 4369): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4369): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 4369): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4369): [loadRssi] File not exist 
,V/LGRssiData( 4369): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4369): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 4369): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4369): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4369): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  965): Killing 3622:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  965): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  965): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  290): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): addressUpdated: 192.168.1.121/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
,D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=0 what=131212 obj=192.168.1.121/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  965): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/DhcpStateMachine(  965): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  965): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/LgDhcpStateMachineHelper(  965): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.121
,V/LgDhcpStateMachineHelper(  965): Add DhcpResults: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  965): bShouldSendDhcpAction Result: true
D/WifiStateMachine(  965): handleMessage: E msg.what=196613
,D/WifiStateMachine(  965): processMsg: ObtainingIpState
,D/WifiStateMachine(  965): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  965): doBoolean: SET ps 1
,D/DhcpStateMachine(  965): DHCP Start/Renew wake lock is released.
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4164): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4164): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 4164): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/DhcpStateMachine(  965): RunningState
,D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  965):    returned true
,D/WifiStateMachine(  965): DHCP successful
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  965): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState enter
D/WifiStateMachine(  965): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
W/WifiStateTracker(  965): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  965): 
W/WifiStateTracker(  965):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  965):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/dalvikvm(  965): Jit: resizing JitTable from 8192 to 16384
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: X
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  965): handleMessage: E msg.what=135190
D/WifiStateMachine(  965): processMsg: VerifyingLinkState
,D/WifiStateMachine(  965): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  965): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  965): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  965): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  965): CaptivePortalCheckState enter
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleConnectivityChange: preConnState=0 connState=2
D/libc    (  271): _dns_getaddrinfo: iptype =0
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  965): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,D/WifiStateMachine(  965): handleMessage: X
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/wpa_supplicant( 4164): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4164): EAPOL: disable timer tick
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,D/WifiStateMachine(  965): handleMessage: E msg.what=131092
D/WifiStateMachine(  965): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  965): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  965): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/WifiStateMachine(  965): transitionTo: destState=ConnectedState
D/QcConnectivityService(  965): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
,D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
D/WifiStateMachine(  965): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/QRemote ( 4352): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/QRemote ( 4352): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/ActivityThread(  965): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=2 connState=1
,D/QRemote ( 4352): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4352): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4165): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,V/        (  271): RouteController
,D/PCSuite ( 4165): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4352): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4352): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/QRemote ( 4352): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 4352): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/QCNEA   (  403): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  403): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  403): |CAC| updateNetCfgInfo
V/QCNEA   (  403): |CAC| *********************************************
V/QCNEA   (  403): |CAC|                   Netconfig               
V/QCNEA   (  403): |CAC| *********************************************
V/QCNEA   (  403): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  403): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  403): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  403): |CAC| 	NetConfig: ip4        =192.168.1.121
V/QCNEA   (  403): |CAC| 	NetConfig: ip6        =::
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
V/QCNEA   (  403): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  403): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  403): |CAC| *********************************************
D/QCNEA   (  403): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  403): |CAC| net type = 1
V/QCNEA   (  403): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  403): |CAC| Received ssid= NG700
V/QCNEA   (  403): |CAC| 	ssid           =NG700
V/QCNEA   (  403): |CAC| 	DNS v4        =192.168.1.1
,V/QCNEA   (  403): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  403): |CAC| *********************************************
D/QCNEA   (  403): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  403): |CAC| dispatching netcfgupdate for wlan
,D/QCNEA   (  403): |CAC| dispatchNetCfg: updating:0xb793c8dc
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/jxcore-log( 4088): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4088): 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GpsLocationProvider(  965): calling native_inject_xtra_data
E/LocSvc_afw(  965): V/Entering int loc_xtra_inject_data(char*, int) line 858 
E/LocSvc_eng(  965): V/length: 58777
E/LocSvc_eng(  965):   data: 0x6a48d008
E/LocSvc_utils_q(  965): D/msg_q_snd: Sending message with handle = 0x65E24AA0
E/LocSvc_utils_ll(  965): D/linked_list_add: Adding to list data_obj = 0x65E24AA0
E/LocSvc_utils_ll(  965): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  965): D/msg_q_rcv: Received message 0x65E24AA0 rv = 0
E/LocSvc_eng(  965): V/length: 58777
E/LocSvc_eng(  965):   data: 0x6a48d008
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1018]: xtra size = 58777
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 1/58, len = 1024, total injected = 0
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_utils_q(  965): D/msg_q_snd: Finished Sending message with handle = 0x65E24AA0
,E/LocSvc_afw(  965): V/Exiting int loc_xtra_inject_data(char*, int) line 861 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 45, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 1024
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 2/58, len = 1024, total injected = 1024
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 46, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 2048
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 3/58, len = 1024, total injected = 2048
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 47, status = 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 3072
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 4/58, len = 1024, total injected = 3072
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 48, status = 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 4096
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 5/58, len = 1024, total injected = 4096
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 49, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 5120
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 6/58, len = 1024, total injected = 5120
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 50, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 6144
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 7/58, len = 1024, total injected = 6144
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 51, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 7168
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 8/58, len = 1024, total injected = 7168
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 52, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 8192
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 9/58, len = 1024, total injected = 8192
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 53, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 9216
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 10/58, len = 1024, total injected = 9216
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 54, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 10240
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 11/58, len = 1024, total injected = 10240
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 55, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 11264
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 12/58, len = 1024, total injected = 11264
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 56, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 12288
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 13/58, len = 1024, total injected = 12288
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 57, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 13312
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 14/58, len = 1024, total injected = 13312
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 58, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 14336
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 15/58, len = 1024, total injected = 14336
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 59, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 15360
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 16/58, len = 1024, total injected = 15360
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 60, status = 0
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 16384
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 17/58, len = 1024, total injected = 16384
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 61, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 17408
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 18/58, len = 1024, total injected = 17408
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 62, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 18432
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 19/58, len = 1024, total injected = 18432
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 63, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 19456
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 20/58, len = 1024, total injected = 19456
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 64, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 20480
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 21/58, len = 1024, total injected = 20480
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 65, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 21504
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 22/58, len = 1024, total injected = 21504
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 66, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 22528
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 23/58, len = 1024, total injected = 22528
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 67, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 23552
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 24/58, len = 1024, total injected = 23552
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 68, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 24576
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 25/58, len = 1024, total injected = 24576
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 69, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 25600
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 26/58, len = 1024, total injected = 25600
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 70, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 26624
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 27/58, len = 1024, total injected = 26624
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 71, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 27648
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 28/58, len = 1024, total injected = 27648
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 72, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 28672
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 29/58, len = 1024, total injected = 28672
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 73, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 29696
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 30/58, len = 1024, total injected = 29696
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 74, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 30720
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 31/58, len = 1024, total injected = 30720
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 75, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 31744
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 32/58, len = 1024, total injected = 31744
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 76, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 32768
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 33/58, len = 1024, total injected = 32768
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 77, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 33792
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 34/58, len = 1024, total injected = 33792
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 78, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 34816
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 35/58, len = 1024, total injected = 34816
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 79, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 35840
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 36/58, len = 1024, total injected = 35840
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 80, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 36864
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 37/58, len = 1024, total injected = 36864
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 81, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 37888
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 38/58, len = 1024, total injected = 37888
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 82, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 38912
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 39/58, len = 1024, total injected = 38912
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 83, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 39936
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 40/58, len = 1024, total injected = 39936
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 84, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 40960
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 41/58, len = 1024, total injected = 40960
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 85, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 41984
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 42/58, len = 1024, total injected = 41984
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 86, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 43008
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 43/58, len = 1024, total injected = 43008
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 87, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 44032
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 44/58, len = 1024, total injected = 44032
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 88, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 45056
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 45/58, len = 1024, total injected = 45056
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 89, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 46080
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 46/58, len = 1024, total injected = 46080
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 90, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 47104
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 47/58, len = 1024, total injected = 47104
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 91, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 48128
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 48/58, len = 1024, total injected = 48128
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 92, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 49152
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 49/58, len = 1024, total injected = 49152
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 93, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 50176
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 50/58, len = 1024, total injected = 50176
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 94, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 51200
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 51/58, len = 1024, total injected = 51200
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 95, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 52224
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 52/58, len = 1024, total injected = 52224
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 96, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 53248
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 53/58, len = 1024, total injected = 53248
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 97, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 54272
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 54/58, len = 1024, total injected = 54272
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 98, status = 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 55296
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 55/58, len = 1024, total injected = 55296
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 99, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 56320
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 56/58, len = 1024, total injected = 56320
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 100, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 57344
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 57/58, len = 1024, total injected = 57344
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 101, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58368
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 58/58, len = 409, total injected = 58368
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x671cc768, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 102, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x671cc768
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x671cc768, resp id = 53, client cookie ptr = 0x671cc7f0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x671cc768 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58777
E/LocSvc_MsgTask(  965): D/MsgTask::loop() 26 listening ...,
,E/LocSvc_utils_q(  965): D/msg_q_rcv: Waiting on message
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/WifiStateMachine(  965): handleMessage: X
,D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  965): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  965):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  965): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  965): battery changed pluggedType: 2
D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/dalvikvm(  965): GC_CONCURRENT freed 1896K, 49% free 28935K/56664K, paused 23ms+10ms, total 230ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4164): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4164): nl80211: survey data missing!
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
,D/WifiStateMachine(  965): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-7ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        (  965): Setting time of day to sec=1449671286
,W/        (  965): Unable to set rtc to 1449671286: Invalid argument
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_SET
,I/SecureClockService( 1156): Intent.ACTION_TIME_CHANGED 
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_SET, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671286696, nextTick: 53336, mDrawingTime: 0
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671286698, nextTick: 53335, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/WeatherService( 1824): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:28:6
,I/MusicWidget( 2108): intentReceiver onReceive() action::android.intent.action.TIME_SET
,I/[LGHome]LGCalendarIcon( 1489): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 9
,I/MusicWidget( 2108): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2108): beingMusicWidget_Lock() result::false
,I/MusicWidget( 2108): beingMusicWidget_Quick() result::false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/MusicWidget( 2108): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2108): performViewUpdater handleMessage() msg.what::0
,I/MusicWidget( 2108): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2108): performUpdate()_4x1
,I/[LGHome]LGCalendarIcon( 1489): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 9
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/MusicWidget( 2108): status::mounted
,I/MusicWidget( 2108): defaultAppWidget()_4x1
,I/MusicWidget( 2108): 4x1_currentTheme :: com.lge.launcher2.theme.optimus
,I/MusicWidget( 2108): setDefaultViewLayoutId()_4x1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/MusicWidget( 2108): appWidgetViewUpdate()_4x1
,I/MusicWidget( 2108): linkButtons()_4x1
,D/WeatherService( 1824): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
D/WeatherService( 1824): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1824): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1824): 2 : Map key string is -2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/lim     ( 1824): 2 : time = 15:28
I/WeatherReflect( 1824): Model Name : LG-D802
D/WeatherTheme( 1824): 2 : Different view - status_min_formatted : 26 != 28
D/WeatherTheme( 1824): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1824): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1824): 2 : Fixed theme : optimus
D/WeatherTheme( 1824): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherService( 1824): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:28:6
I/MusicWidget( 2108): pushUpdate()_4x1
I/MusicWidget( 2108): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2108): beingMusicWidget_Quick() result::false
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/QCNEA   (  403): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/ActivityManager(  965): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4533 uid=10063 gids={50063, 3003, 1028, 1015}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/HyLog   ( 4533): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4533): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4533): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  965): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=4548 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/MusicWidget( 2108): performViewUpdater handleMessage() msg.what::1
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/MusicWidget( 2108): beingMusicWidget_4x2() result::false
,D/WifiController(  965): battery changed pluggedType: 2
I/MusicWidget( 2108): beingMusicWidget_Lock() result::false
I/GoogleURLConnFactory( 1540): Using platform SSLCertificateSocketFactory
,D/HyLog   ( 4548): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4548): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4548): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/AppUp4  ( 4548):  AppBoxContentProvider onCreate
,W/AppUp4  ( 4548):  [AppBoxDatabaseHelper] construct
,I/AppUp4  ( 4548):  setFingerPrint start
,I/AppUp4  ( 4548):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 4548):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 4548):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 4548): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 4548): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4548): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4548): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4548): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4548): onReceive
D/AppUp4:CustFacade( 4548): Context : android.app.ReceiverRestrictedContext@42851a90
D/AppUp4:CustFacade( 4548): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4548): isOpenOperator : true
,D/AppUp4:CustFacade( 4548): isPhone : true
,I/LicenseContentProvider( 2931): start selecting data
,D/SIMObserver( 2931): simInfo1
,I/AppUp4:EulaManager( 4548): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4548): begin check event
,I/AppUp4:CustModeStarterReceiver( 4548): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4548): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4548): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4548): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4548): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4548): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  965): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4570 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,E/Auth.Api.Credentials( 1853): [CredentialSyncAdapter] Unknown sync event.
,D/dalvikvm(  275): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
,D/HyLog   ( 4570): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4570): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4570): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,D/DelayedSyncController( 4533): Delaying sync.
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,I/ActivityManager(  965): Killing 3640:com.android.contacts/u0a21 (adj 15): empty #17
,W/DriveInitializer( 1853): Background init thread started
,I/ConfigFetchService( 1853): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigService( 1540): onCreate
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
I/ConfigFetchService( 1853): running network task: configservice_periodic
E/WakeLock( 1853): callingPackage is not supposed to be empty for wakelock Config Service fetch!
I/ConfigFetchService( 1853): launchTask
,I/ConfigFetchService( 1853): service connected
,D/ConfigFetchService( 1853): ConfigApi connection successful.
,V/ConfigFetchTask( 1853): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WBKaowq0FQEaVXefge7sPhlxoH22bRvVhQk5gJ6IGaZQxHwOTFmeJV_o7bjQpvB1bXmk8x7V06l2CcUyI5bxUE7bc6xOSbr_1B2zJ0GKzlBIuDlBJRRzKUHGlazvT_Ov9GGy4MaiedCHED-UxQVnfPbJbBtR-4sQKKuOFaqbOpY_DdBRmVNR2jAZgZieu1oJu_nu5A
,D/DelayedSyncController( 4533): Delaying sync.
,V/DownloadManager( 4570): DownloadService onCreate
,D/dalvikvm( 1540): GC_EXPLICIT freed 728K, 29% free 17877K/24832K, paused 2ms+3ms, total 28ms
,W/DriveInitializer( 1853): Awaiting to be initialized
,D/EAS     ( 4007): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4007): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4007): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4570): in removeSpuriousFiles
,W/DriveInitializer( 1853): Background init thread ended
,V/DownloadManager( 4570): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4570): created cursor android.database.sqlite.SQLiteCursor@4287f1d0 on behalf of 4570
,W/linker  ( 4007): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4007): JNI_OnLoad
,D/HtmlAPI v1.36.23.33395.LG_apps_master( 4007): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4007): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4007): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,V/DownloadManager( 4570): DownloadService onStartCommand
D/HtmlEditor( 4007): register_HtmlEditor, Success
D/HtmlEditor( 4007): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
,I/ActivityManager(  965): Start proc com.android.mms for broadcast com.android.mms/.transaction.LgeMiscReceiver: pid=4614 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
D/HtmlEditor( 4007): register_HtmlEditorTimer, Success
I/DownloadManager( 4570): in trimDatabase
V/DownloadManager( 4570): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/HtmlEditor( 4007): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4007): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4007): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4007): register_HtmlEditorFont, Success
D/HtmlEditor( 4007): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4007): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4007): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
V/DownloadManager( 4570): DownloadService onStartCommand
V/DownloadManager( 4570): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/HtmlEditor( 4007): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4007): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4007): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4007): JNI_OnLoad Success
V/DownloadManager( 4570): created cursor android.database.sqlite.SQLiteCursor@42881a28 on behalf of 4570
V/DownloadManager( 4570): created cursor android.database.sqlite.SQLiteCursor@428838d8 on behalf of 4570
,I/HubEmail( 4007): JNI_OnLoad()
I/HubEmail( 4007): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4007): registerNatives()
,I/HubEmail( 4007): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4007): registerNativeMethods()
,I/HubEmail( 4007): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,V/DownloadManager( 4570): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/Settings( 4007): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4570): created cursor android.database.sqlite.SQLiteCursor@42887e10 on behalf of 4570
D/HyLog   ( 4614): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4614): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4614): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4570): DownloadService onDestroy
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/ActivityManager(  965): Killing 4026:com.google.android.apps.docs/u0a73 (adj 15): empty #17
D/dalvikvm( 1853): GC_CONCURRENT freed 1036K, 22% free 19451K/24832K, paused 4ms+3ms, total 37ms
D/dalvikvm( 1853): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 1853): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 1853): WAIT_FOR_CONCURRENT_GC blocked 3ms
D/dalvikvm( 1853): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 1853): WAIT_FOR_CONCURRENT_GC blocked 11ms
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/GoogleURLConnFactory( 1853): Using platform SSLCertificateSocketFactory
,I/ConversationSkinProvider( 4614): skin provider oncreate
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/[MMS]   ( 4614): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
,I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
,W/BaseRuntimeLoader( 4614): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4614): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4614): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4614): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Ads     ( 1853): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,E/[MMS]   ( 4614): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 4614): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 4614): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4614): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
,D/[MMS]   ( 4614): MmsSettings: loadxmlstring=open_eu_mms_config
,D/[MMS]   ( 4614): MmsSettings: Matching Xml Data file name = 2131034168
,D/[MMS]   ( 4614): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 4614): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 4614): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 4614): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 4614): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 4614): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 4614): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 4614): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 4614): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 4614): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 4614): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 4614): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_creation_invisible = [0]
,D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   display_as_slide_layout = [1]
,D/[MMS]   ( 4614): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 4614): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   docomo_function_validity_period = [0]
,D/[MMS]   ( 4614): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 4614): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 4614): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   latin_america_fdn_check = [0]
,D/[MMS]   ( 4614): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 4614): MmsSettings: [LGE]   mms_callback = [0]
,D/[MMS]   ( 4614): MmsSettings: [LGE]   message_counters_key = [0]
,E/[MMS]   ( 4614): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
I/[MMS]   ( 4614): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 4614): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4614): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
,E/[MMS]   ( 4614): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
,D/MmsConfig( 4614): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
,I/[MMS]   ( 4614): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
,I/LGDrmService( 4614): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  281): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  281): qmi_init:  Created client handle b8d890a0
,E/Diag_Lib(  281): qmi_client [281] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  281): qmi_client [281] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  281): Sending signal ...... to read cmd data 
E/Diag_Lib(  281): qmi error code.........:0
E/Diag_Lib(  281): qmi sys error code.........:0
D/DRM_Adap(  281): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
,E/Diag_Lib(  281): Setting the api flag to : 1
,E/Diag_Lib(  281): qmi_client [281] 7: sending 47 bytes on fd = 16
,E/Diag_Lib(  281): qmi_client [281] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  281):  API Flag .............. 1 
E/Diag_Lib(  281):  Message ID ............... 37 
E/Diag_Lib(  281): qmi_service_release called, user_handle=20200
E/Diag_Lib(  281): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  281): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  281): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  281): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  281): qmi_client [281] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  281): qmi_client [281] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  281): Sending signal ...... to read cmd data 
E/Diag_Lib(  281): qmi error code.........:0
,E/Diag_Lib(  281): qmi sys error code.........:0
D/DRM_Adap(  281): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  281): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  281): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  281): qmi_init:  Created client handle b8d890b8
,E/Diag_Lib(  281): qmi_client [281] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  281): qmi_client [281] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  281): Sending signal ...... to read cmd data 
E/Diag_Lib(  281): qmi error code.........:0
E/Diag_Lib(  281): qmi sys error code.........:0
D/DRM_Adap(  281): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  281): Setting the api flag to : 1
,E/Diag_Lib(  281): qmi_client [281] 7: sending 47 bytes on fd = 16
,E/Diag_Lib(  281): qmi_client [281] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  281):  API Flag .............. 1 
E/Diag_Lib(  281):  Message ID ............... 37 
E/Diag_Lib(  281): qmi_service_release called, user_handle=20200
E/Diag_Lib(  281): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  281): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  281): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  281): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  281): qmi_client [281] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  281): qmi_client [281] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  281): Sending signal ...... to read cmd data 
E/Diag_Lib(  281): qmi error code.........:0
E/Diag_Lib(  281): qmi sys error code.........:0
D/DRM_Adap(  281): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  281): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
,I/DrmWrapper( 4614): isDrmV1 =true
,V/DrmWrapper( 4614): isDrmV2 =false
V/MmsConfig( 4614): [isMmsEnabledWhenDataDisabled]value=1
,V/MmsConfigStaticVar( 4614): [setMmsEnabledWhenDataDisabled]enabled=true
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.460037 Y: -0.391724 Z: 9.749008 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460037 .y:-0.391724 .z:9.749008
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/MmsConfigStaticVar( 4614): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,D/CmasFeatures( 4614): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 4614): Contact init()_Create new insatnce
,I/MessagingNotification( 4614): registerLEDObserver
,I/MessagingNotification( 4614): registerLEDObserver REGISTER
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/LocationManagerService(  965): getProviders()=[passive, gps]
D/LocationManagerService(  965): request 43ccf778 passive Request[POWER_NONE passive fastest=0] from android(1000)
D/LocationManagerService(  965): provider request: passive ProviderRequest[ON interval=0]
,V/MmsConfig( 4614): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
,I/LOG_TAG ( 4614): registerContactDBChangeObserver
I/LgeMiscReceiver( 4614): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4614): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4614): networkInfo.isConnected() = false
,V/LGRssiData( 4614): [loadRssi] File not exist 
V/LGRssiData( 4614): [loadRssi] File not exist 
D/CountryDetector(  965): The first listener is added
E/ActivityThread( 4614): Failed to find provider info for com.lge.ims.provider.uc
V/TelephonyAutoProfiling( 4614): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 4614): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4614): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4614): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  965): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4646 uid=10052 gids={50052, 3003}
I/ActivityManager(  965): Killing 3675:com.google.android.apps.plus/u0a112 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4646): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4646): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4646): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.458984 Y: -0.399551 Z: 9.752151 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458984 .y:-0.399551 .z:9.752151
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4646): [loadRssi] File not exist 
V/LGRssiData( 4646): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4646): [loadFeatureFromXml] *** start feature loading from xml
,D/MobileConnectivityChangeReceiver( 4646): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4646): onReceive CONNECTIVITY_CHANGE networkType=1
W/BaseRuntimeLoader( 4646): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4646): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4646): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4646): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4646): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4646): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4646): [getValue] FEATURE key : vzw_roaming_state, value : null
E/PhoneMonitor( 4646): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4646): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  965): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4660 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  965): Killing 3701:com.android.vending/u0a50 (adj 15): empty #17
,D/HyLog   ( 4660): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4660): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4660): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/ActivityManager(  965): Scheduling restart of crashed service com.android.vending/com.google.android.finsky.services.ContentSyncService in 1000ms
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,D/DrmBroadcastReceiver( 4660): Receive CONNECTIVITY_ACTION
I/ActivityManager(  965): Killing 1751:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,D/LGDMClient( 2818): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4233): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2818): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 4257): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4257): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2818): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4233): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  965): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4674 uid=10104 gids={50104, 3003, 1028, 1015}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
E/LGDMClient( 2818): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2818): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2818): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2818): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 4674): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4674): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4674): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/dalvikvm(  965): GC_EXPLICIT freed 1448K, 49% free 28939K/56664K, paused 3ms+7ms, total 100ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/CheckinService( 1853): Checking schedule, now: 1449671287605 next: 1449594714836
I/CheckinService( 1853): active receiver: enabled
,W/GAV2    ( 4674): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/CheckinService( 1853): Preparing to send checkin request
,I/EventLogService( 1853): Accumulating logs since 1449670585531
,I/ConfigFetchTask( 1853): updating config table for com.google.android.gms
,I/ConfigFetchService( 1853): fetch service done; releasing wakelock
,I/ConfigFetchService( 1853): stopping self
,V/WebViewChromium( 4674): Binding Chromium to the main looper Looper (main, tid 1) {42834308}
,I/chromium( 4674): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4674): Initializing chromium process, renderers=0
,W/chromium( 4674): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4674): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4674): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4674): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4674): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4674): Remote Branch: 
I/Adreno-EGL( 4674): Local Patches: 
I/Adreno-EGL( 4674): Reconstruct Branch: 
,I/NSApplication( 4674): Starting up...
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/ActivityManager(  965): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4710 uid=10112 gids={50112, 3003, 3002, 1028, 1015}
,I/ActivityManager(  965): Killing 3995:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/HyLog   ( 4710): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4710): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4710): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinRequestBuilder( 1853): Checkin reason type: 8 attempt count: 1
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
D/WifiService(  965): New client listening to asynchronous messages
E/ActivityThread( 1853): Failed to find provider info for com.google.android.wearable.settings
,W/BaseRuntimeLoader( 1853): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1853): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1853): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1853): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/ActivityManager(  965): Killing 4208:com.lge.settings.easy/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 4710): GC_FOR_ALLOC freed 438K, 16% free 20860K/24832K, paused 18ms, total 18ms
,I/dalvikvm-heap( 4710): Grow heap (frag case) to 26.454MB for 4099024-byte allocation
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.SyncManager( 1853): SYNC; picasa accounts
,D/dalvikvm( 4710): GC_CONCURRENT freed 8K, 14% free 24862K/28836K, paused 6ms+2ms, total 18ms
,D/NetworkLogImpl( 1853): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1853): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/iu.UploadsManager( 1853): num queued entries: 0
,I/iu.UploadsManager( 1853): num updated entries: 0
I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
,I/iu.SyncManager( 1853): NEXT; no task
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
I/ActivityManager(  965): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=4742 uid=10010 gids={50010, 3003, 1028, 4002}
,I/GcmGroups( 1853): Failed to subscribe to group.
I/GcmGroups( 1853): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1853): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1853): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1853): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1853): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1853): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1853): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1853): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1853): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1853): 	at android.os.Looper.loop(Looper.java:136)
I/GcmGroups( 1853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/GcmGroups( 1853): Groups upload failed, retrying in 24000:00:00
,D/HyLog   ( 4742): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4742): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4742): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 4710): GC_FOR_ALLOC freed 8K, 14% free 24864K/28836K, paused 13ms, total 13ms
,W/CheckinRequestBuilder( 1853): awaiting user notification for token
,I/dalvikvm-heap( 4710): Grow heap (frag case) to 30.364MB for 4099024-byte allocation
D/NotificationService(  965): updateLightListLocked :r=null, action=2
,E/OpenGL ES Test( 4742): getCurrentLocale == en_US
,E/OpenGL ES Test( 4742): localeFound retString == en_US
E/OpenGL ES Test( 4742): getCurrentLocale == en_US
,E/OpenGL ES Test( 4742): localeFound retString == en_US
,D/ALBootInit( 4742): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 4742): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 4742): [setNextAlert] start
D/dalvikvm( 4710): GC_CONCURRENT freed 3K, 13% free 28864K/32840K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 4710): WAIT_FOR_CONCURRENT_GC blocked 8ms
,I/dalvikvm-heap( 4710): Grow heap (frag case) to 34.270MB for 4099024-byte allocation
,D/Alarms  ( 4742): [setNextAlert] (1)
,D/Alarms  ( 4742):  minTime  = 0
,D/Alarms  ( 4742):  -- OK multi -- 0
,E/jeny.kim( 4742): [setNextAlert] setNextAlert  temp_Alarmlink + 
,E/jeny.kim( 4742): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,D/Alarms  ( 4742): setStatusBarIcon : false
,D/Alarms  ( 4742): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,D/WorldClockReceiver( 4742): ====action==>android.intent.action.TIME_SET
E/OpenGL ES Test( 4742): getCurrentLocale == en_US
E/OpenGL ES Test( 4742): localeFound retString == en_US
E/OpenGL ES Test( 4742): getCurrentLocale == en_US
,E/OpenGL ES Test( 4742): localeFound retString == en_US
E/OpenGL ES Test( 4742): getCurrentLocale == en_US
E/OpenGL ES Test( 4742): localeFound retString == en_US
E/OpenGL ES Test( 4742): getCurrentLocale == en_US
E/OpenGL ES Test( 4742): localeFound retString == en_US
,D/dalvikvm( 4710): GC_CONCURRENT freed 5K, 11% free 33023K/36844K, paused 1ms+0ms, total 13ms
,E/OpenGL ES Test( 4742): isExistDatabase = false
,I/ActivityManager(  965): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4756 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
I/CommonUtil( 4742): BUILD Country: EU
E/OpenGL ES Test( 4742): loadMapCityData() -- S
E/OpenGL ES Test( 4742): getCurrentLocale == en_US
E/OpenGL ES Test( 4742): localeFound retString == en_US
E/OpenGL ES Test( 4742): getCurrentLocale == en_US
E/OpenGL ES Test( 4742): localeFound retString == en_US
,D/HyLog   ( 4756): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4756): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4756): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/OpenGL ES Test( 4742): loadMapCityData() - While S
,W/dalvikvm( 4756): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4756): VFY: replacing opcode 0x60 at 0x000b
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/dalvikvm( 4756): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4756): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4756): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4756): VM with version 1.6.0 does not have multidex support
D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  965): MasterInitialState.processMessage what=3
,I/MultiDex( 4756): install
,I/MultiDex( 4756): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4756): loading existing secondary dex files
,I/MultiDex( 4756): load found 3 secondary dex files
,I/MultiDex( 4756): install done
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 4756): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4756): VFY: unable to resolve instance field 61
,D/dalvikvm( 4756): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4756): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4756): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4756): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4756): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4756): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4756): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4756): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4756): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4756): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283df80
,D/dalvikvm( 4756): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283df80
,D/dalvikvm( 4756): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283df80, skipping init
,D/dalvikvm( 4756): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283df80
D/dalvikvm( 4756): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283df80
,V/JNIHelp ( 4756): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/GCM     ( 1540): Connected
D/dalvikvm( 4756): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283df80
,D/dalvikvm( 4756): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4283df80
D/dalvikvm( 4756): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283df80
D/dalvikvm( 4756): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4283df80
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/VacuumService( 1540): Vacuum at: now=1449671288133 tag=VacuumService
,I/GoogleURLConnFactory( 1540): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1540): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1540): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1540): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1540): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1540): No account for auth token provided
,E/OpenGL ES Test( 4742): loadMapCityData() - While E
,E/OpenGL ES Test( 4742): loadMapCityData() -- E
E/OpenGL ES Test( 4742): getCurrentLocale == en_US
E/OpenGL ES Test( 4742): localeFound retString == en_US
E/OpenGL ES Test( 4742): getCurrentLocale == en_US
,E/OpenGL ES Test( 4742): localeFound retString == en_US
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,E/OpenGL ES Test( 4742): [updateWidgetDST] backup_cityInfoList is null >>>>
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1540): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/ProviderInstaller( 4756): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  965): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4778 uid=10015 gids={50015, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 4369:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/dalvikvm( 4756): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4756): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x000d
D/HyLog   ( 4778): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4778): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4778): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/dalvikvm( 4756): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4756): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x0201
,I/Config  ( 4778): LGCalendar ver.4.2.6
,I/Config  ( 4778): start check model
I/Config  ( 4778): start check native_ca
,E/Config  ( 4778): [setCountryAndOperator] Operator=OPEN, Country=EU
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
,D/dalvikvm( 1540): GC_CONCURRENT freed 1750K, 28% free 18092K/24832K, paused 2ms+2ms, total 23ms
I/dalvikvm( 4756): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.a.a
W/dalvikvm( 4756): VFY: unable to resolve virtual method 299: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x0013
,D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/QSEECOMAPI: (  277): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  277): App is not loaded in QSEE
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
,W/dalvikvm( 4756): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4756): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4756): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 4756): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4756): VFY: unable to resolve virtual method 727: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x00bb
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
,I/GoogleURLConnFactory( 4756): Using platform SSLCertificateSocketFactory
,D/CalendarWidget( 4778): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
,D/QSEECOMAPI: (  277): Loaded image: APP id = 2
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1da4000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1da4000
,I/InitNotificationRingtoneService( 4778): Start InitializeAlertRingtoneService.onHandleIntent
,D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
,E/DataScheduler( 4756): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ActivityManager(  965): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4807 uid=10016 gids={50016, 3003, 1028, 1015}
D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
D/HyLog   ( 4807): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4807): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4807): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,I/InitNotificationRingtoneService( 4778): internal content query returns 1 results.
,I/InitNotificationRingtoneService( 4778): Found default schedule notification : Schedule.ogg(id:42)
,I/InitNotificationRingtoneService( 4778): set default noti to content://media/internal/audio/media/42
,I/InitNotificationRingtoneService( 4778): End InitializeAlertRingtoneService.onHandleIntent
D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,W/Uploader( 1540): No account for auth token provided
D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=3630825202
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/CalendarProvider2( 4807): Created com.android.providers.calendar.CalendarAlarmManager@42857798(com.android.providers.calendar.CalendarProvider2@4284e700)
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/ActivityManager(  965): Start proc com.lge.task for broadcast com.lge.task/.widget.TasksWidgetProvider: pid=4826 uid=10043 gids={50043, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 4165:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,W/Uploader( 1540):  no longer exists, so no auth token.
,I/ActivityManager(  965): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=4840 uid=10050 gids={50050, 3003, 1028, 1015}
,D/dalvikvm(  275): GC_EXPLICIT freed 42K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 14ms
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,W/Uploader( 1540): No account for auth token provided
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 16ms
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/dalvikvm(  965): GC_EXPLICIT freed 922K, 49% free 29246K/56664K, paused 2ms+8ms, total 115ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/HyLog   ( 4826): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HyLog   ( 4826): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4826): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4840): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4840): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4840): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/WifiController(  965): battery changed pluggedType: 2
,D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Uploader( 1540): No account for auth token provided
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/dalvikvm( 4840): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 4840): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4840): VFY: replacing opcode 0x6e at 0x000b
,E/TASKS   ( 4826): init() PortStorageManger PRIMARY_STORAGE_PATH :/storage/emulated/0
,D/TASKS_APP_WIDGET( 4826): onReceive() #################################################
,I/TASKS   ( 4826): getCurrentThemeInfo START #############################
,W/Uploader( 1540): No account for auth token provided
I/TASKS   ( 4826): com.lge.launcher2.theme.optimus
I/TASKS   ( 4826): com.lge.task
,I/TASKS   ( 4826): getCurrentThemeInfo END #############################
I/TASKS   ( 4826): loadThemeResources packageName : com.lge.task
,I/TASKS   ( 4826): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4826): intentAction : android.intent.action.TIME_SET
,I/ActivityManager(  965): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4860 uid=10122 gids={50122}
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received.
I/ActivityManager(  965): Killing 4352:com.lge.qremote/u0a96 (adj 15): empty #17
W/ActivityThread(  965): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/Finsky  ( 4840): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4860): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 4860): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42837140, skipping init
D/TimeService( 4860): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449671288764
D/        ( 4860): TimeServiceNative: User Time to be set is 1449671288764
D/QC-time-services( 4860): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4860): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4860): Lib:time_genoff_operation: pargs->ts_val = 1449671288764
D/QC-time-services( 4860): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  412): Daemon: Connection accepted:time_genoff
D/QC-time-services(  412): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449671288764
D/QC-time-services(  412): Daemon:genoff_opr: Base = 2, val = 1449671288764, operation = 0
,D/QC-time-services(  412): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/16/70 2:13:1
D/QC-time-services(  412): Daemon:Value read from RTC seconds = 9079981000
D/QC-time-services(  412): Daemon:new time 1449671288764 
D/QC-time-services(  412): Daemon: delta 1440591307764 genoff 1440591307764 
D/QC-time-services(  412): Daemon:genoff_persistent_update: Writing genoff = 1440591307764 to memory
D/QC-time-services(  412): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  412): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/dalvikvm( 4840): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 4840): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4840): VFY: replacing opcode 0x6e at 0x004f
,D/QC-time-services(  412): Updating the TOD offset
D/QC-time-services(  412): Daemon:genoff_persistent_update: Writing genoff = 1440591307764 to memory
D/QC-time-services(  412): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  412): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  412): Daemon:Update to modem bit set
D/QC-time-services(  412): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  412): Daemon: Base = 2, Value being sent to MODEM = 1133706488764
,E/QC-time-services( 4860): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  412): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  412): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  965): Killing 4548:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,W/BaseRuntimeLoader( 4840): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4840): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4840): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4840): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,D/Finsky  ( 4840): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  965): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=4891 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,V/WifiServiceExtension(  965): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/HyLog   ( 4891): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4891): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4891): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/dalvikvm( 1853): GC_CONCURRENT freed 1783K, 22% free 19595K/24832K, paused 3ms+5ms, total 42ms
,D/dalvikvm( 4756): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42bbad98
D/dalvikvm( 4756): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42bbad98
,D/dalvikvm( 4756): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42bbad98, skipping init
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 4164): wlan0: Control interface command 'SIGNAL_POLL'
,I/AppUp4  ( 4891):  AppBoxContentProvider onCreate
,W/AppUp4  ( 4891):  [AppBoxDatabaseHelper] construct
,D/wpa_supplicant( 4164): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,W/Settings( 4840): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4840): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
,I/AppUp4  ( 4891):  setFingerPrint start
,I/AppUp4  ( 4891):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 4891):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 4891):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 4891): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 4891): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4891): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4891): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4891): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4891): onReceive
,W/GLSActivity( 1540): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1540): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1540): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1540): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1540): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1540): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1540): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1540): 	at dalvik.system.NativeStart.run(Native Method)
I/dalvikvm( 4840): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4840): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4840): VFY: replacing opcode 0x6e at 0x011e
D/AppUp4:CustFacade( 4891): Context : android.app.ReceiverRestrictedContext@42849268
,D/AppUp4:CustFacade( 4891): isCustomizationCompleted : false
E/PlayEventLogger( 4840): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4840): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4840): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4840): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4840): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4840): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4840): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4840): 	at dalvik.system.NativeStart.run(Native Method)
D/AppUp4:CustFacade( 4891): isOpenOperator : true
,D/AppUp4:CustFacade( 4891): isPhone : true
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x431fbee8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/LicenseContentProvider( 2931): start selecting data
D/SIMObserver( 2931): simInfo1
I/AppUp4:EulaManager( 4891): getAgreementForKK : Eula agreement is false
I/dalvikvm( 4840): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4840): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4840): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 4840): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4840): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
D/dalvikvm( 4840): VFY: replacing opcode 0x6e at 0x029a
D/AppUp4:CustModeStarterReceiver( 4891): begin check event
I/AppUp4:CustModeStarterReceiver( 4891): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4891): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4891): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4891): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4891): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4891): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4570): DownloadService onCreate
,D/EAS     ( 4007): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4007): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4570): in removeSpuriousFiles
,V/DownloadManager( 4570): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 4614): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4614): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4614): networkInfo.isConnected() = true
,D/PhoneState( 4614): setPdpRejectCasuse : false
V/DownloadManager( 4570): created cursor android.database.sqlite.SQLiteCursor@4289dce8 on behalf of 4570
,W/Settings( 4007): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4646): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4646): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4570): DownloadService onStartCommand
V/DownloadManager( 4570): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4570): in trimDatabase
,V/DownloadManager( 4570): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4570): created cursor android.database.sqlite.SQLiteCursor@428a0330 on behalf of 4570
,V/DownloadManager( 4570): created cursor android.database.sqlite.SQLiteCursor@428a0e50 on behalf of 4570
,D/DrmBroadcastReceiver( 4660): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 4660): 1  network is available. Sync DRM Time with NTP
,D/LGDMClient( 2818): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DrmService( 4660): Service onCreate
,D/DrmService( 4660): Received new request = 2
,D/LGDMClient( 2818): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2818): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMSGCM( 4233): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/DrmSntpClient( 4660): Start Sync process
,D/DrmSntpClient( 4660): Server : 0
,E/DataScheduler( 4660): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
E/LGDMClient( 2818): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2818): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2818): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2818): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,W/ContextImpl( 4233): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4257): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4257): CONNECT : WIFI_CONNECT
V/DownloadManager( 4570): DownloadService onDestroy
I/dalvikvm( 4840): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4840): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 4840): VFY: replacing opcode 0x6e at 0x001a
,V/DownloadManager( 4570): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/DownloadManager( 4570): created cursor android.database.sqlite.SQLiteCursor@428a6448 on behalf of 4840
,I/dalvikvm( 4840): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 4840): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4840): VFY: replacing opcode 0x6e at 0x0049
,I/ConfigFetchService( 1853): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1853): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1853): GmsCore config value changed; rescheduling
,W/ConfigFetchService( 1853): ConfigApi client is not connected. Falling back to defaultfetch interval.
,I/ConfigFetchService( 1853): service connected
,D/ConfigFetchService( 1853): ConfigApi connection successful.
,D/GCM     ( 1540): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,D/WeatherAncestor( 1824): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:28:9
,D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
,D/Weather_cast( 1824): 2 : Request from alarm is Canceled
,D/WeatherAncestor( 1824): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:28:9
,D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,I/ConfigFetchService( 1853): stopping self
,D/WeatherQuickCover( 1824): 2 : quick cover state : opened : 0
,I/NetworkStateForAutoUpdateMonitor( 4891): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4891): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4891): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4891): [onReceive] request level :IDLE....
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/Weather.Utils( 1824): 2 : Utils getTopActivity com.lge.launcher2 / false
,I/AppUp4:CustModeStarterReceiver( 4891): onReceive
D/Weather.Utils( 1824): 2 : Utils getTopActivity com.lge.easyhome / false
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/AppUp4:CustFacade( 4891): Context : android.app.ReceiverRestrictedContext@42849268
D/AppUp4:CustFacade( 4891): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4891): isOpenOperator : true
,D/AppUp4:CustFacade( 4891): isPhone : true
D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,I/LicenseContentProvider( 2931): start selecting data
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/SIMObserver( 2931): simInfo1
,I/AppUp4:EulaManager( 4891): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4891): begin check event
,I/AppUp4:CustModeStarterReceiver( 4891): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,V/DownloadManager( 4570): DownloadService onCreate
,D/Finsky  ( 4840): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/DownloadManager( 4570): in removeSpuriousFiles
,D/Finsky  ( 4840): [1] 2.run: Finished loading 1 libraries.
V/DownloadManager( 4570): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4007): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4007): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4570): created cursor android.database.sqlite.SQLiteCursor@428aa290 on behalf of 4570
,V/DownloadManager( 4570): DownloadService onStartCommand
,V/DownloadManager( 4570): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4570): in trimDatabase
,V/DownloadManager( 4570): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4614): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4614): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4614): networkInfo.isConnected() = true
D/PhoneState( 4614): setPdpRejectCasuse : false
,D/Finsky  ( 4840): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
I/LGDrmService( 4660): _DRM_ServiceGet() : Bind lgdrm service
,V/DownloadManager( 4570): created cursor android.database.sqlite.SQLiteCursor@428ad478 on behalf of 4570
I/LGDRM   (  281): [DRM] SET TIME : YR=2015, MON=12, DAY=9
,I/LGDRM   (  281): [DRM] SET TIME : HR=14, MIN=28, SEC=8
,D/MobileConnectivityChangeReceiver( 4646): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4646): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4570): created cursor android.database.sqlite.SQLiteCursor@428ad260 on behalf of 4570
I/DrmSntpClient( 4660): Synched
W/Settings( 4007): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DrmService( 4660): Completed !! request = 2
,D/DrmService( 4660): Request count = 0
D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=551396987
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,V/DrmService( 4660): Service onDestroy
,D/LGDMClient( 2818): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/LGDMClient( 2818): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 4570): DownloadService onDestroy
,D/LGDMSGCM( 4233): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/Finsky  ( 4840): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ContextImpl( 4233): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4257): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4257): CONNECT : WIFI_CONNECT
I/LGDMClient( 2818): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/System  ( 4840): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4840): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,E/LGDMClient( 2818): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2818): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2818): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2818): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  965): Killing 3659:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4931 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/HyLog   ( 4931): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4931): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4931): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/dalvikvm( 4840): Total arena pages for JIT: 11
,I/dalvikvm( 4840): Total arena pages for JIT: 12
I/dalvikvm( 4840): Total arena pages for JIT: 13
,I/dalvikvm( 4840): Total arena pages for JIT: 14
,I/MediaCodecList( 4931): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 4931): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 4931): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4931): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 4931): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4931): MmsConfig.loadMmsSettings
,I/Babel   ( 4931): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 4931): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 4931): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4931): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4931): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4931): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 4931): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4931): MmsConfig.loadFromResources
,W/Settings( 4931): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 4931): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4931): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4931): [loadRssi] File not exist 
V/LGRssiData( 4931): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4931): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 4931): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4931): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4931): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/GCM     ( 1540): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1540): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1540): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1853): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  965): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4957 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
D/CalendarWidget( 4778): Agenda AppWidgetService init broadcastReceiver
D/CalendarWidget( 4778): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
D/LocationInitializer( 1853): Restart initialization of location
,D/TASKS_APP_WIDGET( 4826): onReceive() #################################################
I/TASKS   ( 4826): getCurrentThemeInfo START #############################
I/TASKS   ( 4826): com.lge.launcher2.theme.optimus
I/TASKS   ( 4826): com.lge.task
I/TASKS   ( 4826): getCurrentThemeInfo END #############################
I/TASKS   ( 4826): loadThemeResources packageName : com.lge.task
I/TASKS   ( 4826): loadLocalResId #############################
D/TASKS_APP_WIDGET( 4826): intentAction : com.lge.task.APPWIDGET_UPDATE
D/HyLog   ( 4957): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4957): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4957): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/CalendarWidget( 4778): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4778): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,W/dalvikvm( 4957): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4957): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4957): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4957): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4957): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4957): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4957): install
,I/MultiDex( 4957): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4957): loading existing secondary dex files
,I/MultiDex( 4957): load found 3 secondary dex files
,I/MultiDex( 4957): install done
,D/dalvikvm( 4957): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4957): VFY: unable to resolve instance field 61
,D/dalvikvm( 4957): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4957): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4957): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4957): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4957): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4957): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4957): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4957): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4957): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4957): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283b1f0
D/dalvikvm( 4957): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283b1f0
,D/dalvikvm( 4957): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283b1f0, skipping init
,D/dalvikvm( 4957): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283b1f0
D/dalvikvm( 4957): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283b1f0
,V/JNIHelp ( 4957): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4957): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283b1f0
,D/dalvikvm( 4957): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4283b1f0
D/dalvikvm( 4957): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283b1f0
,D/dalvikvm( 4957): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4283b1f0
,D/Finsky  ( 4840): [423] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4840): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  965): Killing 4742:com.lge.clock/u0a10 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProviderInstaller( 4957): Installed default security provider GmsCore_OpenSSL
,I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
,D/GCM     ( 1540): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1540): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1540): Proximity feature is not enabled.
,E/Babel   ( 4931): UserRecoverableAuthException.
,E/Babel   ( 4931): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4931): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4931): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4931): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4931): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4931): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4931): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,V/GmsCoreStatsServiceLauncher( 1853): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/Babel   ( 4931): Error getting auth token
,E/Babel   ( 4931): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4931): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4931): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4931): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4931): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4931): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4931): Account registration failedRedacted-21
,E/Babel   ( 4931): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4931): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4931): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4931): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4931): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4931): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
I/Babel   ( 4931): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4931): Account sign in complete with state 106account: Redacted-21
,D/LocationInitializer( 1853): Restart initialization of location
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/CalendarProvider2( 4807): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4807): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AlertReceiver( 4778): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/CalendarWidget( 4778): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,D/AlertService( 4778): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/AlertService( 4778): Beginning updateAlertNotification
I/dalvikvm( 4957): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
W/dalvikvm( 4957): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x003f
,D/WearableService( 4957): callingUid 10006, callindPid: 4957
,D/dalvikvm( 4756): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
E/dalvikvm( 4957): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 4957): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 4957): VFY: replacing opcode 0x1f at 0x0054
,W/dalvikvm( 4957): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 4957): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4957): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x000d
,D/AlertService( 4778): No fired or scheduled alerts
I/dalvikvm( 4957): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
,W/dalvikvm( 4957): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x0201
,E/MDM     ( 1426): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/CalendarWidget( 4778): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4778): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,E/MDM     ( 1426): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/ActivityManager(  965): Killing 4860:com.qualcomm.timeservice/u0a122 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 4983): DexOpt: load 3ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4756): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4756): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 64ms
,I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4756): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4756): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4756): Remote Branch: 
I/Adreno-EGL( 4756): Local Patches: 
I/Adreno-EGL( 4756): Reconstruct Branch: 
,I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
,E/Babel   ( 4931): Unexpected exception while authenticating.
,E/Babel   ( 4931): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4931): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4931): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4931): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4931): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4931): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4931): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4931): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4931): 	at java.lang.Thread.run(Thread.java:841)
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x4318be68: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 8452K, 13% free 68600K/78364K, paused 31ms, total 31ms
,I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4756): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4756): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4756): Remote Branch: 
I/Adreno-EGL( 4756): Local Patches: 
I/Adreno-EGL( 4756): Reconstruct Branch: 
,I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4756): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4756): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4756): Remote Branch: 
I/Adreno-EGL( 4756): Local Patches: 
I/Adreno-EGL( 4756): Reconstruct Branch: 
,W/Settings( 4756): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1853): Classify the device as Phone.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/Finsky  ( 4840): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/dalvikvm( 4840): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4840): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4840): VFY: replacing opcode 0x62 at 0x0037
,D/dalvikvm(  965): GC_EXPLICIT freed 2111K, 49% free 29414K/56664K, paused 2ms+7ms, total 88ms
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4840): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/CheckinTask( 1853): Sending checkin request (11562 bytes)
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4840): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/dalvikvm( 1540): GC_CONCURRENT freed 1959K, 28% free 18063K/24832K, paused 2ms+1ms, total 23ms
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4840): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4840): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4840): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4840): [1] DailyHygiene.reschedule: Scheduling new run in 89 minutes (failures=3)
,D/DeviceConnectionService( 1426): client connected with version: 7571000
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1853): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1853): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x44d14538: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/CheckinRequestBuilder( 1853): awaiting user notification for token
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/CheckinRequestBuilder( 1853): Classify the device as Phone.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1853): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1853): Checking schedule, now: 1449671290721 next: 1450248686719
,I/CheckinService( 1853): active receiver: disabled
,I/CheckinService( 1853): Checking schedule, now: 1449671290765 next: 1450248686719
,I/CheckinService( 1853): active receiver: disabled
,D/GCM     ( 1540): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4164): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4164): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4674): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/GpsLocationProvider(  965): requestTime failed
,I/ConfigService( 1540): onDestroy
,I/ActivityManager(  965): Killing 4891:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager(  965): Killing 2931:com.lge.eula/1000 (adj 15): empty #18
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): Killing 4570:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  965): Killing 4007:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4164): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4164): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  965): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  965): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  965): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  965): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  965): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/ActivityManager(  965): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5046 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,D/administrator(  965): Handling package changes for user 0
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  965):   Scheme: "smsto"
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,E/SlideAside( 3521): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/SlideAside( 3521): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.talk
,E/SlideAside( 3521): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3521): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HyLog   ( 5046): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5046): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5046): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
,I/AppUp4  ( 5046):  AppBoxContentProvider onCreate
,W/AppUp4  ( 5046):  [AppBoxDatabaseHelper] construct
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/AppUp4  ( 5046):  setFingerPrint start
I/AppUp4  ( 5046):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 5046):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 5046):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5046): AppBoxApplication onCreate()
D/AppBoxBlacklist( 5046): ConfigFile is not exist. /cust/config/appmanager.cfg
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4164): wlan0: Control interface command 'SIGNAL_POLL'
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/wpa_supplicant( 4164): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
D/PackageParser( 5046): Added overlay pkg for /system/apps/bootup/LGTaskManager.apk
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/AppUp4:Utils( 5046): [getPackageName] uri : package:com.google.android.talk
D/AppUp4  ( 5046): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5046): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.talk
D/PackageParser( 5046): Added overlay pkg for /system/apps/bootup/LGHome_Theme_Marshmallow.apk
D/administrator(  965): Handling package changes for user 0
,I/AppUp4:CustModeStarterReceiver( 5046): onReceive
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
,D/AppUp4:CustFacade( 5046): Context : android.app.ReceiverRestrictedContext@4284c228
D/AppUp4:CustFacade( 5046): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5046): isOpenOperator : true
,D/AppUp4:CustFacade( 5046): isPhone : true
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/ActivityManager(  965): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=5079 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5079): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5079): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5079): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
,I/LicenseContentProvider( 5079): start selecting data
W/BaseRuntimeLoader( 5079): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5079): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5079): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5079): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/SIMObserver( 5079): simInfo1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/AppUp4:EulaManager( 5046): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 5046): begin check event
D/AppUp4:Utils( 5046): [getPackageName] uri : package:com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 5046): Event For Nothing, skip.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5095 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
I/ActivityManager(  965): Killing 4646:com.google.android.setupwizard/u0a52 (adj 15): empty #17
I/ActivityManager(  965): Killing 4614:com.android.mms/u0a35 (adj 15): empty #18
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,D/CountryDetector(  965): No listener is left
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/HyLog   ( 5095): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5095): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5095): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/SystemConfig( 5095): BUILD Country: EU
,I/SystemConfig( 5095): BUILD Operator: OPEN
I/SystemConfig( 5095): systemFeature RCS result false
,D/SystemConfig( 5095): refreshRcsSupport() :false
I/ActivityManager(  965): Killing 4533:com.android.chrome/u0a63 (adj 15): empty #17
,V/GmsNetworkLocationProvi( 1426): DISABLE
,I/GCoreNlp( 1426): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/ActivityManager(  965): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5111 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5111): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5111): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5111): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): Killing 4660:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/IcingCorporaProvider( 2633): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1853): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/ActivityManager(  965): Delaying start of: ServiceRecord{444d9cb0 u0 com.google.android.gms/.wearable.service.WearableControlService}
D/AppUp4:Utils( 5046): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 5046): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 5046): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
I/AppUp4:CustModeStarterReceiver( 5046): onReceive
I/PeopleContactsSync( 1853): CP2 sync disabled
D/AppUp4:CustFacade( 5046): Context : android.app.ReceiverRestrictedContext@4284c228
D/AppUp4:CustFacade( 5046): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5046): isOpenOperator : true
D/AppUp4:CustFacade( 5046): isPhone : true
I/LicenseContentProvider( 5079): start selecting data
D/SIMObserver( 5079): simInfo1
I/AppUp4:EulaManager( 5046): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 5046): begin check event
D/AppUp4:Utils( 5046): [getPackageName] uri : package:com.google.android.gms
I/AppUp4:CustModeStarterReceiver( 5046): Event For Nothing, skip.
,I/IcingCorporaProvider( 2633): UpdateCorporaTask done [took 48 ms] updated apps [took 48 ms] 
,I/IcingCorporaProvider( 2633): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1853): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1853): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  965): Delaying start of: ServiceRecord{44d295f8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/LocationManagerService(  965): remove 43ccf778
,D/LocationManagerService(  965): provider request: passive ProviderRequest[ON interval=0]
D/LocationProviderProxy(  965): applying state to connected service
,D/LocationProviderProxy(  965): applying state to connected service
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  965): GC_EXPLICIT freed 2887K, 47% free 29612K/55428K, paused 3ms+7ms, total 89ms
,I/Icing   ( 1853): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1853): GC_CONCURRENT freed 2071K, 22% free 19509K/24832K, paused 3ms+3ms, total 41ms
,I/IcingCorporaProvider( 2633): UpdateCorporaTask done [took 288 ms] updated apps [took 288 ms] 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PowerManagerService(  965): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  965): [updateScreenState] screen on = false
D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  965): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9092 usec
,D/qcom_sensors_hal(  965): hal_acquire_resources
,I/qcom_sensors_hal(  965): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
,D/qcom_sensors_hal(  965): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  965): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  965): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  965): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  965): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  965): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  965): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.452911 Y: -0.393570 Z: 9.761993 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452911 .y:-0.393570 .z:9.761993
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.470444 Y: -0.391434 Z: 9.748734 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470444 .y:-0.391434 .z:9.748734
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Sensors (  380): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  965): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  965): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  965): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  965): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  965): proximitySensorChanged  positive = true
I/KnockOnPowerController(  965): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.481873 Y: -0.393188 Z: 9.762878 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.481873 .y:-0.393188 .z:9.762878
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.479721 Y: -0.380829 Z: 9.744492 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.479721 .y:-0.380829 .z:9.744492
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.449631 Y: -0.385818 Z: 9.737808 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449631 .y:-0.385818 .z:9.737808
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.469162 Y: -0.393616 Z: 9.749283 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.469162 .y:-0.393616 .z:9.749283
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  965): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@42b4ed08)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  965): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
I/WindowManager(  965): No lock screen! windowToken=null
,D/SurfaceFlinger(  274): Screen released, type=0 flinger=0xb82ac450
,D/qdhwcomposer(  274): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.483246 Y: -0.401123 Z: 9.775528 
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.463272 Y: -0.384491 Z: 9.764435 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.483246 .y:-0.401123 .z:9.775528
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/WifiStateMachine(  965): handleScreenStateChanged: true
,D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4164): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  965): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  965): stopMonitoring
,D/wpa_supplicant( 4164): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131127
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
,D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=132097
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  965): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 4164): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 4164): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  965): handleMessage: X
,E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 965
,V/SRS_Proc(  277): ParamSet string: screen_state=on
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: enter: screen_state=on
,V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433b2188 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3521): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/dalvikvm( 1156): GC_CONCURRENT freed 2870K, 11% free 25469K/28520K, paused 4ms+2ms, total 70ms
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1824): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:28:21
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SlideAside( 3521): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
D/WeatherAncestor( 1824): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:28:21
D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdhwcomposer(  274): hwc_blank: Done blanking display: 0
D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/SurfaceControl(  965): Excessive delay in blankDisplay() while turning screen off: 421ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671301325, nextTick: 38708, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671301386, nextTick: 38647, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
,D/WeatherService( 1824): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:28:21
,D/WeatherService( 1824): 2 : ACTION screen on
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1824): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:28:21
,D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0,
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_ON
,D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 93, B = 93
,I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 87, B = 87
,D/qcom_sensors_hal(  965): hal_acquire_resources
D/qcom_sensors_hal(  965): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  965): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3}
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  965): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  965): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  965): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1156): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 81, B = 81
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 75, B = 75
,I/LGImmersionVibrator(  965): Vibrator off
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{431fd8c0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{44df9128 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
D/KeyguardViewManager( 1142): onScreenTurnedOff()
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/UsbSettings( 2563): [AUTORUN] onDestroy() : getDefaultFunction =boot
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/UsbSettings( 2563): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
D/WifiStateMachine(  965): handleScreenStateChanged: false
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
V/UsbSettings( 2563): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 true
V/UsbSettings( 2563): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
D/qdlights( 1156): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 69, B = 69
D/wpa_supplicant( 4164): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 4164): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/WifiController(  965): battery changed pluggedType: 2
D/WifiController(  965): CMD_SCREEN_OFF 
,D/WifiController(  965): shouldWifiStayAwake TRUE
E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 965
V/SRS_Proc(  277): ParamSet string: screen_state=off
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1156): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 63, B = 63
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1156): clear
,D/wpa_supplicant( 4164): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  965):    returned true
,D/WifiStateMachine(  965): handleMessage: X
V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{431fd8c0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
D/qdlights( 1156): set_light_notifications: 2,ff003939,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 57, B = 57
I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1156): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 51, B = 51
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/qdlights( 1156): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 45, B = 45
D/WeatherService( 1824): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:28:21
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/WeatherService( 1824): 2 : ACTION screen off
,D/WeatherService( 1824): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:28:21
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
,D/NfcService( 1475): NFC-C OFF
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_OFF
D/qdlights( 1156): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 39, B = 39
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
,D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_OFF
D/qdlights( 1156): set_light_notifications: 2,ff002121,10,0,2
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
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  380): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  290): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,I/GAV4    ( 4931): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,D/Finsky  ( 4840): [423] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4840): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671319392977434; DSPS: 5282326; Offset: 1449671158189181048
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671339394647948; DSPS: 5937740; Offset: 1449671158189203613
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671340064, nextTick: 59965, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671340068, nextTick: 59965, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671359396708931; DSPS: 6593168; Offset: 1449671158189189400
,I/rmt_storage(  415): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb75f3178
I/rmt_storage(  415): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  415): wakelock acquired: 1, error no: 42
,I/rmt_storage(  415): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1218498840)
,I/rmt_storage(  415): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  415): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  415): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1218498840) wakelock released: 1, error no: 22
I/rmt_storage(  415): 
I/rmt_storage(  415): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb75f3178
,E/Diag_Lib(  718): [IMS_FATAL]| 2912 | 723 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671379398593141; DSPS: 7248590; Offset: 1449671158189181520
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671399400228342; DSPS: 7904003; Offset: 1449671158189199290
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671400052, nextTick: 59975, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671400057, nextTick: 59975, mDrawingTime: 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671419401805157; DSPS: 8559415; Offset: 1449671158189189191
,I/jxcore-log( 4088): Connected to the server!
I/jxcore-log( 4088): 
,I/chromium( 4088): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671439403147598; DSPS: 9214819; Offset: 1449671158189188858
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671459404716861; DSPS: 9870231; Offset: 1449671158189171207
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671460048, nextTick: 59983, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671460049, nextTick: 59984, mDrawingTime: 0
,D/wpa_supplicant( 4164): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: BSS: Remove id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4164): wlan0: BSS: Remove id 6 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 4164): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 9e:93:4e:3e:ba:c5]
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671479406370968; DSPS: 10525645; Offset: 1449671158189177365
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671499407975699; DSPS: 11181057; Offset: 1449671158189195182
,D/dalvikvm( 2621): GC_CONCURRENT freed 7707K, 32% free 16938K/24832K, paused 17ms+3ms, total 67ms
,D/dalvikvm( 2621): WAIT_FOR_CONCURRENT_GC blocked 48ms
,D/dalvikvm( 2621): GC_CONCURRENT freed 1831K, 31% free 17139K/24832K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 2621): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/Mlt MonitorService( 2621): parseLastkmsg to dump
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671519409576994; DSPS: 11836470; Offset: 1449671158189179045
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671520042, nextTick: 59971, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671520056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671539411367455; DSPS: 12491888; Offset: 1449671158189199487
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671559413054374; DSPS: 13147304; Offset: 1449671158189177421
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671579414921918; DSPS: 13802725; Offset: 1449671158189183393
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671580042, nextTick: 59980, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671580049, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671599417348058; DSPS: 14458164; Offset: 1449671158189198644
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671619418996956; DSPS: 15113578; Offset: 1449671158189199593
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671639420905959; DSPS: 15769001; Offset: 1449671158189185989
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671640041, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671640048, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671659422823191; DSPS: 16424424; Offset: 1449671158189180613
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671679424151881; DSPS: 17079827; Offset: 1449671158189197048
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671699426537030; DSPS: 17735265; Offset: 1449671158189201825
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671700039, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671700047, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671719428317230; DSPS: 18390684; Offset: 1449671158189181488
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671739430048004; DSPS: 19046100; Offset: 1449671158189203278
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671759431866278; DSPS: 19701520; Offset: 1449671158189190497
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671760047, nextTick: 59979, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671760051, nextTick: 59977, mDrawingTime: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671779433733197; DSPS: 20356941; Offset: 1449671158189195844
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671799435956054; DSPS: 21012374; Offset: 1449671158189190918
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671819437664848; DSPS: 21667790; Offset: 1449671158189190727
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671820053, nextTick: 59965, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671820062, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671839439168851; DSPS: 22323199; Offset: 1449671158189199369
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671859441102177; DSPS: 22978623; Offset: 1449671158189179570
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671879442655450; DSPS: 23634034; Offset: 1449671158189176447
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671880042, nextTick: 59972, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671880053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671899444525703; DSPS: 24289455; Offset: 1449671158189185127
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671919447029081; DSPS: 24944897; Offset: 1449671158189186064
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671939448586470; DSPS: 25600308; Offset: 1449671158189187056
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671940052, nextTick: 59967, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449671940060, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671959450193024; DSPS: 26255721; Offset: 1449671158189176179
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671979452005203; DSPS: 26911140; Offset: 1449671158189187821
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449671999453725040; DSPS: 27566556; Offset: 1449671158189198673
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672000044, nextTick: 59966, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672000057, nextTick: 59975, mDrawingTime: 0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  965): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  965): Done.
,D/QcConnectivityService(  965): Setting timer for 720seconds
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672019455610762; DSPS: 28221978; Offset: 1449671158189192305
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672039457074088; DSPS: 28877386; Offset: 1449671158189190788
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672059458742725; DSPS: 29532801; Offset: 1449671158189180958
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672060044, nextTick: 59975, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672060051, nextTick: 59969, mDrawingTime: 4
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672079460408291; DSPS: 30188215; Offset: 1449671158189198575
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672099462066617; DSPS: 30843630; Offset: 1449671158189178434
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672119463730983; DSPS: 31499044; Offset: 1449671158189194851
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672120047, nextTick: 59973, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672120054, nextTick: 59971, mDrawingTime: 4
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672139465775456; DSPS: 32154471; Offset: 1449671158189194646
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672159467684876; DSPS: 32809894; Offset: 1449671158189181459
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672179469339450; DSPS: 33465308; Offset: 1449671158189188083
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672180044, nextTick: 59977, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672180051, nextTick: 59980, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672199471319183; DSPS: 34120733; Offset: 1449671158189184174
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672219472990842; DSPS: 34776148; Offset: 1449671158189177366
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672239474404219; DSPS: 35431554; Offset: 1449671158189186934
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672240046, nextTick: 59965, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672240059, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672259476903640; DSPS: 36086996; Offset: 1449671158189183914
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672279478810193; DSPS: 36742418; Offset: 1449671158189198377
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672299480547322; DSPS: 37397835; Offset: 1449671158189196004
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672300024, nextTick: 60000, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672300062, nextTick: 59971, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672319482102262; DSPS: 38053246; Offset: 1449671158189194548
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672339483793921; DSPS: 38708662; Offset: 1449671158189177222
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672359485683705; DSPS: 39364084; Offset: 1449671158189174916
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672360042, nextTick: 59972, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672360053, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672379496167448; DSPS: 40019787; Offset: 1449671158189191130
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672399497664419; DSPS: 40675196; Offset: 1449671158189192740
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672419499296287; DSPS: 41330610; Offset: 1449671158189176659
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672420047, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672420050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672439501157633; DSPS: 41986031; Offset: 1449671158189176432
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672459502734448; DSPS: 42641442; Offset: 1449671158189196851
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672479504584336; DSPS: 43296863; Offset: 1449671158189185167
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672480057, nextTick: 59969, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672480061, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672499506568703; DSPS: 43952288; Offset: 1449671158189185891
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672519508199113; DSPS: 44607701; Offset: 1449671158189198869
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672539510010251; DSPS: 45263121; Offset: 1449671158189178953
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672540048, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672540051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672559512189514; DSPS: 45918552; Offset: 1449671158189191468
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672579514009297; DSPS: 46573972; Offset: 1449671158189180196
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672599516524656; DSPS: 47229414; Offset: 1449671158189193114
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672600042, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672600048, nextTick: 59980, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672619518500012; DSPS: 47884839; Offset: 1449671158189184827
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672639519782140; DSPS: 48540241; Offset: 1449671158189185217
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672659521615622; DSPS: 49195661; Offset: 1449671158189187644
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672660040, nextTick: 59985, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672660046, nextTick: 59982, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672679523527905; DSPS: 49851084; Offset: 1449671158189177320
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672699525721492; DSPS: 50506516; Offset: 1449671158189173641
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672719527289662; DSPS: 51161927; Offset: 1449671158189185414
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672720042, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672720050, nextTick: 59960, mDrawingTime: 8
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  965): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  965): Done.
,D/QcConnectivityService(  965): Setting timer for 720seconds
,I/GCM     ( 1853): Message from null null
,E/GCM     ( 1853): Dropping message from null
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1540): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/EventLogService( 1853): Aggregate from 1449671287708 (log), 1449670585531 (data)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672739529121321; DSPS: 51817347; Offset: 1449671158189186019
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672759530942979; DSPS: 52472767; Offset: 1449671158189176622
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672779532517034; DSPS: 53128178; Offset: 1449671158189194281
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672780048, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672780048, nextTick: 59981, mDrawingTime: 3
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672799534542807; DSPS: 53783605; Offset: 1449671158189175376
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672819536280509; DSPS: 54439022; Offset: 1449671158189173576
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672839541908001; DSPS: 55094566; Offset: 1449671158189185834
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672840043, nextTick: 59984, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672840048, nextTick: 59955, mDrawingTime: 11
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672859543538358; DSPS: 55749979; Offset: 1449671158189198759
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672879544917934; DSPS: 56405385; Offset: 1449671158189174526
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672899546916781; DSPS: 57060810; Offset: 1449671158189189731
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672900040, nextTick: 59980, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672900047, nextTick: 59982, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672919548763491; DSPS: 57716231; Offset: 1449671158189174868
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672939550284160; DSPS: 58371640; Offset: 1449671158189200176
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672959552184986; DSPS: 59027063; Offset: 1449671158189178395
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672960042, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449672960047, nextTick: 59981, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672979554159093; DSPS: 59682487; Offset: 1449671158189199377
,I/ProcessStatsService(  965): Prepared write state in 27ms
,D/LocationManagerService(  965): getAllProviders()=[passive, gps, network]
,I/ActivityManager(  965): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6793 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ProcessStatsService(  965): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-43-50.bin
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 6793): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6793): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6793): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1540): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1540): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1540): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1540): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1540): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1540): [DefaultAuthDelegateService] Use browser flow? false
,V/DownloadManager( 6793): DownloadService onCreate
,I/DownloadManager( 6793): in removeSpuriousFiles
,V/DownloadManager( 6793): DownloadService onStartCommand
,V/DownloadManager( 6793): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 6793): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6793): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6793): created cursor android.database.sqlite.SQLiteCursor@428823f8 on behalf of 1853
,V/DownloadManager( 6793): created cursor android.database.sqlite.SQLiteCursor@428826c0 on behalf of 6793
,I/DownloadManager( 6793): in trimDatabase
,V/DownloadManager( 6793): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6793): created cursor android.database.sqlite.SQLiteCursor@42885168 on behalf of 6793
,V/DownloadManager( 6793): created cursor android.database.sqlite.SQLiteCursor@42885480 on behalf of 6793
,V/DownloadManager( 6793): DownloadService onDestroy
,V/DownloadManager( 6793): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 6793): created cursor android.database.sqlite.SQLiteCursor@4288bdd8 on behalf of 1853
,V/DownloadManager( 6793): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 6793): created cursor android.database.sqlite.SQLiteCursor@4288f638 on behalf of 1853
,I/ActivityManager(  965): Killing 4233:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43235e00 stackId=1, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449672999555729607; DSPS: 60337899; Offset: 1449671158189182977
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449673019557671786; DSPS: 60993322; Offset: 1449671158189202548
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449673020037, nextTick: 59974, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449673020052, nextTick: 59976, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449673039559385945; DSPS: 61648739; Offset: 1449671158189177205
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449673059560939271; DSPS: 62304150; Offset: 1449671158189174135
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449673079566477233; DSPS: 62959691; Offset: 1449671158189188415
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449673080050, nextTick: 59979, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449673080053, nextTick: 59978, mDrawingTime: 1
,TIME-OUT KILL (timeout was 1800000ms)
```
