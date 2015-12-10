#### Test 5065027881383b1_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/PeopleContactsSync( 1959): CP2 sync disabled
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
I/dalvikvm( 1959): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1959): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1959): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/GAV2    ( 4619): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  965): Killing 4077:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c1f478 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2029): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
D/ChimeraCfgMgr( 1959): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1959): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1959): GC_CONCURRENT freed 1511K, 22% free 19523K/24832K, paused 5ms+3ms, total 33ms
D/dalvikvm( 1959): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/AndroidRuntime( 4666): 
D/AndroidRuntime( 4666): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4666): CheckJNI is OFF
D/dalvikvm( 4666): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4666): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4666): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4666): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4666): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4666): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/ConfigFetchService( 1959): fetch service done; releasing wakelock
I/ConfigFetchService( 1959): stopping self
E/memtrack( 4666): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4666): failed to load memtrack module: -2
D/AndroidRuntime( 4666): Calling main entry com.android.commands.am.Am
I/ActivityManager(  965): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4666
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (385 us)
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{42c1f478 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  965): resumeTopActivityLocked: Pausing null
V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  965): startService SlideAside
W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  965): setFocusedStack: mFocusedStack=ActivityStack{4327b618 stackId=1, 2 tasks}
D/UsbSettingsControl( 2636): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{42c1f478 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/AndroidRuntime( 4666): Shutting down VM
D/UsbSettings( 2636): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3780): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4666): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 3ms
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{42c1f478 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Restarting ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  965): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4691 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3780): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3780): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4691): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4691): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4691): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4691): Binding Chromium to the background looper Looper (main, tid 1) {427e2a58}
I/chromium( 4691): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4691): Initializing chromium process, renderers=0
W/chromium( 4691): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4691): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4691): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4691): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4691): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4691): Remote Branch: 
I/Adreno-EGL( 4691): Local Patches: 
I/Adreno-EGL( 4691): Reconstruct Branch: 
I/dalvikvm( 4691): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4691): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4691): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4691): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4691): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4691): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4691): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4691): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4691): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4691): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4691): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4691): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4691): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4691): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4691): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4691): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4691): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4691): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4691): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4691): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4691): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4691): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4691): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4691): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4691): Enabling debug mode 0
W/AwContents( 4691): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  965): IME STATUS OFF
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
W/AwContents( 4691): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  965): Displayed com.test.thalitest/.MainActivity: +508ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager( 4691): Timeline: Activity_idle id: android.os.BinderProxy@427e4228 time:109872
D/ActivityManager(  965): no-history finish of ActivityRecord{42c1f478 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  965): Finishing activity token=Token{42970a78 ActivityRecord{42c1f478 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3} time:110110
D/UsbSettings( 2636): [AUTORUN] onStop()
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{42c1f478 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{42c1f478 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{42c1f478 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/JsMessageQueue( 4691): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 4691): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/dalvikvm( 4691): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427e8830
D/dalvikvm( 4691): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427e8830
D/jxcore_app_log( 4691): JniHelper::setJavaVM(0x416ae838), pthread_self() = 1636379480
D/JX-Cordova( 4691): jxcore cordova android initializing
I/dalvikvm( 4691): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4691): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4691): VFY: replacing opcode 0x6e at 0x0045
I/chromium( 4691): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm( 4691): GC_CONCURRENT freed 2778K, 13% free 21833K/24832K, paused 3ms+1ms, total 51ms
,D/dalvikvm( 4691): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/dalvikvm( 4691): GC_FOR_ALLOC freed 113K, 13% free 21834K/24832K, paused 27ms, total 28ms
,D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 4691): GC_FOR_ALLOC freed 130K, 12% free 21855K/24832K, paused 24ms, total 24ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4691): GC_FOR_ALLOC freed 184K, 12% free 21889K/24832K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4691): Grow heap (frag case) to 23.688MB for 144892-byte allocation
,D/dalvikvm( 4691): GC_FOR_ALLOC freed 257K, 13% free 21936K/24976K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4691): Grow heap (frag case) to 23.803MB for 217334-byte allocation
,D/dalvikvm( 4691): GC_FOR_ALLOC freed 369K, 13% free 22010K/25192K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4691): Grow heap (frag case) to 23.979MB for 325996-byte allocation
,D/dalvikvm( 4691): GC_FOR_ALLOC freed 570K, 14% free 22132K/25512K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4691): Grow heap (frag case) to 24.253MB for 488990-byte allocation
,D/dalvikvm( 4691): GC_FOR_ALLOC freed 868K, 15% free 22309K/25992K, paused 23ms, total 24ms
,I/dalvikvm-heap( 4691): Grow heap (frag case) to 24.659MB for 733480-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4691): GC_FOR_ALLOC freed 1288K, 16% free 22567K/26712K, paused 24ms, total 25ms
,D/dalvikvm( 4691): GC_CONCURRENT freed 1676K, 15% free 22938K/26712K, paused 1ms+2ms, total 28ms
,D/dalvikvm( 4691): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 4691): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4691): GC_FOR_ALLOC freed 376K, 15% free 22896K/26712K, paused 35ms, total 35ms
I/dalvikvm-heap( 4691): Grow heap (frag case) to 26.107MB for 1650320-byte allocation
D/dalvikvm( 4691): GC_CONCURRENT freed 1716K, 18% free 23466K/28324K, paused 1ms+3ms, total 32ms
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/dalvikvm( 4691): GC_FOR_ALLOC freed 1349K, 17% free 23545K/28324K, paused 37ms, total 38ms
I/dalvikvm-heap( 4691): Grow heap (frag case) to 27.528MB for 2475476-byte allocation
D/dalvikvm( 4691): GC_CONCURRENT freed 1965K, 22% free 24243K/30744K, paused 2ms+3ms, total 34ms
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2029): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/dalvikvm( 4691): GC_CONCURRENT freed 2355K, 21% free 24481K/30744K, paused 1ms+11ms, total 52ms
D/dalvikvm( 4691): WAIT_FOR_CONCURRENT_GC blocked 40ms
D/dalvikvm( 4691): WAIT_FOR_CONCURRENT_GC blocked 36ms
D/dalvikvm( 4691): GC_FOR_ALLOC freed 470K, 21% free 24361K/30744K, paused 33ms, total 34ms
I/dalvikvm-heap( 4691): Grow heap (frag case) to 29.505MB for 3713210-byte allocation
D/dalvikvm( 4691): GC_CONCURRENT freed 2830K, 26% free 25442K/34372K, paused 2ms+3ms, total 32ms
,D/dalvikvm( 4691): GC_FOR_ALLOC freed 520K, 26% free 25467K/34372K, paused 23ms, total 23ms
,W/jxcore-log( 4691): Initializing JXcore engine
,W/jxcore-log( 4691): JXcore engine is ready
,D/dalvikvm( 4691): GC_CONCURRENT freed 353K, 19% free 28115K/34372K, paused 2ms+1ms, total 27ms
D/dalvikvm( 4691): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 4691): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4691): Starting JXcore engine
,W/jxcore-log( 4691): Platform android
W/jxcore-log( 4691): 
,W/jxcore-log( 4691): Process ARCH arm
W/jxcore-log( 4691): 
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.457199 Y: -0.385025 Z: 9.753754 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457199 .y:-0.385025 .z:9.753754
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.455017 Y: -0.381912 Z: 9.751785 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455017 .y:-0.381912 .z:9.751785
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/jxcore-log( 4691): JXcore Cordova bridge is ready!
I/jxcore-log( 4691): 
,W/jxcore-log( 4691): JXcore engine is started
,I/chromium( 4691): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4691): Skipped 164 frames!  The application may be doing too much work on its main thread.
,I/GAV2    ( 4619): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  965): battery changed pluggedType: 2
,I/jxcore-log( 4691): Toggling radios to true
I/jxcore-log( 4691): 
,D/BluetoothManagerService(  965): Message: 20
,D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@449592f8:true
,D/BluetoothAdapter( 4691): enable(): BT is already enabled..!
D/WifiService(  965): New client listening to asynchronous messages
D/WifiService(  965): setWifiEnabled: true pid=4691, uid=10304
E/WifiService(  965): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  965): setWifiEnabled startWifiDelaySendMsg true
,D/WifiStateMachine(  965): handleMessage: E msg.what=131145
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doBoolean: DISCONNECT
,I/jxcore-log( 4691): Radios toggled
I/jxcore-log( 4691): 
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2029): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2029): wlan0: Cancelling scan request
D/wpa_supplicant( 2029): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2029): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2029): TDLS: Tear down peers
,D/wpa_supplicant( 2029): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4691): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4691): 
,I/jxcore-log( 4691): Perf Test app loaded loaded
I/jxcore-log( 4691): 
,I/jxcore-log( 4691): check test folder
I/jxcore-log( 4691): 
D/WifiService(  965): disconnect pid=4691, uid=10304
,D/WifiService(  965): reconnect pid=4691, uid=10304
I/jxcore-log( 4691): found test : ./testFindPeers.js
I/jxcore-log( 4691): 
D/wpa_supplicant( 2029): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2029): wlan0: Deauthentication notification
D/wpa_supplicant( 2029): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2029): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2029): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2029): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2029): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2029): wlan0: Disconnect event - remove keys
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7175d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2029): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2029): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2029): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFL,A_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2029): nl80211: Event message available
D/wpa_supplicant( 2029): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2029): nl80211: Ignore disconnect event triggered during reassociation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: ConnectedState
W/Settings(  965): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  965): invokeExitMethods: L2ConnectedState
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131146
D/WifiStateMachine(  965): processMsg: DisconnectingState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiNative-wlan0(  965): doBoolean: RECONNECT
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2029): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2029): Fast associate: Old scan results
D/wpa_supplicant( 2029): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2029): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2029): wlan0: nl80211: scan request
D/wpa_supplicant( 2029): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147460
D/WifiStateMachine(  965): processMsg: DisconnectingState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection lost
D/WifiStateMachine(  965): Stopping DHCP and clearing IP
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 2029): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2029): nl80211: Event message available
D/wpa_supplicant( 2029): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2029): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2029): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2029): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2029): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  965):    returned true
,I/ConfigService( 1559): onDestroy
D/DhcpStateMachine(  965): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  965): addressRemoved: 192.168.1.121/24 on wlan0 flags 128 scope 0
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  965): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
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
D/QCNEA   (  391): |CAC| dispatchNetCfg: updating:0xb83418dc
,D/QCNEA   (  391): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
,I/jxcore-log( 4691): found test : ./testSendData.js
I/jxcore-log( 4691): 
,D/WifiStateMachine(  965): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiHS20(  965): hidePasspointNotification off =false
,D/QcConnectivityService(  965): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=SCANNING
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): handleMessage: X
D/QcConnectivityService(  965): Attempting to switch to mobile
D/QcConnectivityService(  965): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=1 connState=2
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  965): handleMessage: E msg.what=131213
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): processMsg: DriverStartedState
,D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): handleMessage: X
I/ActivityManager(  965): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4748 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 4748): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4748): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4748): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  264): RouteController
V/        (  264): RouteController
I/PCSuite ( 4748): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 4748): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4748): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/        (  264): RouteController
W/NetworkManagementService(  965): route cmd failed: 
W/NetworkManagementService(  965): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  965): '
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  965): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  965): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  965): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  965): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  965): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  965): android_net_utils_resetConnections in env=0x5e864b10 clazz=0x6c300001 iface=wlan0 mask=0x3
D/QcConnectivityService(  965): resetConnections(wlan0, 3)
,I/ActivityManager(  965): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4785 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,V/NativeCrypto( 1559): Read error: ssl=0x63ea4cb0: I/O error during system call, Connection timed out
,I/ActivityManager(  965): Killing 4184:com.google.android.talk/u0a77 (adj 15): empty #17
V/NativeCrypto( 1559): SSL shutdown failed: ssl=0x63ea4cb0: I/O error during system call, Broken pipe
,D/HyLog   ( 4785): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4785): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4785): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
,D/QRemote ( 4785): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,I/chromium( 4691): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/QRemote ( 4785): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4785): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4785): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4785): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4785): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4785): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4785): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4785): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  965): Killing 2139:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  965): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/WifiController(  965): battery changed pluggedType: 2
,D/wpa_supplicant( 2029): nl80211: Event message available
D/wpa_supplicant( 2029): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2029): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2029): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2029): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 2029): nl80211: Survey data missing
D/wpa_supplicant( 2029): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 7 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 8 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 2029): wlan0: New scan results available
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2029): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2029): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2029): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2029): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2029): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2029): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[4] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2029): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2029): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2029): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2029): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2029): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2029): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb71775a8  current_ssid=0x0
D/wpa_supplicant( 2029): scard is not null..
D/wpa_supplicant( 2029): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:0,0:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2029): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2029): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2029): wlan0: Cancelling scan request
D/wpa_supplicant( 2029): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2029): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2029): wlan0: Automatic auth_alg selection: 0x1,
,D/wpa_supplicant( 2029): RSN: PMKSA cache search - network_ctx=0xb71775a8 try_opportunistic=0,
,D/wpa_supplicant( 2029): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2029): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2029): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2029): wlan0: WPA: clearing AP WPA IE,
,D/wpa_supplicant( 2029): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2029): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2029): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2029): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2029): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
,D/wpa_supplicant( 2029): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2029): wlan0: No keys have been configured - skip key clearing,
D/wpa_supplicant( 2029): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2029): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2029): nl80211: Unsubscribe mgmt frames handle 0xb7176590 (mode change)
D/wpa_supplicant( 2029): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7176590
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7176590,
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7176590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0b,
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7176590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7176590,
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7176590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7176590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7176590,
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7176590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=1): 06
,D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7176590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 0a 07,
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7176590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2029): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2029):   * bssid=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2029):   * freq=2412
D/wpa_supplicant( 2029):   * SSID - hexdump(len=5): 4e 47 37 30 30,
D/wpa_supplicant( 2029):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029):   * Auth Type 0
D/wpa_supplicant( 2029):   * WPA Versions 0x2
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 a0:c5:62:7a:49:97],
D/wpa_supplicant( 2029): nl80211: Connect request send successfully
D/wpa_supplicant( 2029): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2029): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2029): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 a0:c5:62:7a:49:96]
D/WifiStateMachine(  965): handleMessage: E msg.what=147461
,D/WifiStateMachine(  965): processMsg: DisconnectedState,
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiNative-wlan0(  965): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2029): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  965): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/wpa_supplicant( 2029): nl80211: Event message available
D/wpa_supplicant( 2029): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2029): nl80211: Connect event
D/wpa_supplicant( 2029): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2029): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2029): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2029): wlan0: Association info event
D/wpa_supplicant( 2029): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2029): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2029): wlan0: freq=2412 MHz
D/wpa_supplicant( 2029): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2029): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2029): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2029): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): scard is not null..
D/wpa_supplicant( 2029): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2029): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2029): TDLS: Remove peers on association
D/wpa_supplicant( 2029): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2029): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2029): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2029): EAPOL: enable timer tick
D/wpa_supplicant( 2029): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2029): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2029): wlan0: Cancelling scan request
,D/wpa_supplicant( 2029): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  965): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiStateMachine(  965): processMsg: DisconnectedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 2029): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 a7 56 3b 04 00 f9 fa 21 15 4a fd 55 2c 47 f1 ...
D/wpa_supplicant( 2029): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2029): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2029): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2029): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2029): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2029):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2029):   key_nonce - hexdump(len=32): a7 56 3b 04 00 f9 fa 21 15 4a fd 55 2c 47 f1 a9 9d a8 c1 e0 1a dc 91 de ec 7c 97 20 9a aa 3c d2
D/wpa_supplicant( 2029):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 a7 56 3b 04 00 f9 fa 21 15 4a fd 55 2c 47 f1 ...
D/wpa_supplicant( 2029): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2029): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2029): Get randomness: len=32 entropy=10
D/wpa_supplicant( 2029): WPA: Renewed SNonce - hexdump(len=32): 3d 33 d9 e9 6b 20 87 e1 d4 7c f9 c1 91 3d 63 ca dc e5 25 1b ab f0 70 18 dc 51 b8 e2 5c 90 7b 0d
D/wpa_supplicant( 2029): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): WPA: Nonce1 - hexdump(len=32): 3d 33 d9 e9 6b 20 87 e1 d4 7c f9 c1 91 3d 63 ca dc e5 25 1b ab f0 70 18 dc 51 b8 e2 5c 90 7b 0d
D/wpa_supplicant( 2029): WPA: Nonce2 - hexdump(len=32): a7 56 3b 04 00 f9 fa 21 15 4a fd 55 2c 47 f1 a9 9d a8 c1 e0 1a dc 91 de ec 7c 97 20 9a aa 3c d2
D/wpa_supplicant( 2029): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2029): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2029): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2029): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2029): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2029): WPA: Derived Key MIC - hexdump(len=16): e1 a2 05 77 88 55 a0 d7 95 1f 24 b0 4e 9f 08 f0
D/wpa_supplicant( 2029): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 3d 33 d9 e9 6b 20 87 e1 d4 7c f9 c1 91 3d 63 ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPower,UI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/wpa_supplicant( 2029): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 a7 56 3b 04 00 f9 fa 21 15 4a fd 55 2c 47 f1 ...
D/wpa_supplicant( 2029): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2029): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2029): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2029): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2029):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2029):   key_nonce - hexdump(len=32): a7 56 3b 04 00 f9 fa 21 15 4a fd 55 2c 47 f1 a9 9d a8 c1 e0 1a dc 91 de ec 7c 97 20 9a aa 3c d2
D/wpa_supplicant( 2029):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_rsc - hexdump(len=8): b9 09 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_mic - hexdump(len=16): 8f e8 fd 09 e7 57 8b 71 76 69 ac e3 1e c9 5d b9
D/wpa_supplicant( 2029): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 a7 56 3b 04 00 f9 fa 21 15 4a fd 55 2c 47 f1 ...
D/wpa_supplicant( 2029): RSN: encrypted key data - hexdump(len=56): 93 37 b0 f0 03 4a f8 93 74 5f 86 06 b9 d2 e7 39 b3 0b a9 ac c7 d8 a0 52 d4 fb 77 d5 fc 57 78 f0 ...
D/wpa_supplicant( 2029): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2029): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2029): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2029): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 9f 9f ...
D/wpa_supplicant( 2029): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2029): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2029): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2029): WPA: Derived Key MIC - hexdump(len=16): 0d 85 41 74 df bf 22 36 d5 93 8f 10 8b 3e 61 6e
D/wpa_supplicant( 2029): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2029): wlan0: WPA: Installing PTK to the driver
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7176c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2029):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2029): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2029): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2029): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2029): WPA: RSC - hexdump(len=6): b9 09 00 00 00 00
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f1703a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2029):    broadcast key
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2029): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2029): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2029): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2029): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2029): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2029): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2029): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2029): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2029): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2029): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2029): EAPOL authentication completed successfully
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  965): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection established
D/WifiNative-wlan0(  965): doString: STATUS
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2029): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  965):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  965): ssid=NG700
D/WifiNative-wlan0(  965): id=0
D/WifiNative-wlan0(  965): mode=station
D/WifiNative-wlan0(  965): pairwise_cipher=CCMP
D/WifiNative-wlan0(  965): group_cipher=CCMP
D/WifiNative-wlan0(  965): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  965): wpa_state=COMPLETED
D/WifiNative-wlan0(  965): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  965): address=34:fc:ef:de:0a:e2
I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] connect :false
I/WifiServiceExtension(  965): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  965): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
I/AppUp4:CustModeStarterReceiver( 4045): onReceive
D/WifiStateMachine(  965): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: DisconnectedState
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  965): invokeEnterMethods: L2ConnectedState
E/Parcel  (  391): Reading a NULL string not supported here.
D/WifiStateMachine(  965): invokeEnterMethods: ObtainingIpState
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
D/DhcpStateMachine(  965): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
D/DhcpStateMachine(  965): WaitBeforeStartState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-8ms what=147462 obj=android.net.wifi.StateChangeResult@44db61d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/AppUp4:CustFacade( 4045): Context : android.app.ReceiverRestrictedContext@42801530
D/AppUp4:CustFacade( 4045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4045): isOpenOperator : true
D/AppUp4:CustFacade( 4045): isPhone : true
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-6ms what=147462 obj=android.net.wifi.StateChangeResult@44dc42a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-6ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/LicenseContentProvider( 3023): start selecting data
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
D/SIMObserver( 3023): simInfo1
D/wpa_supplicant( 2029): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196612
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/AppUp4:EulaManager( 4045): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4045): begin check event
I/AppUp4:CustModeStarterReceiver( 4045): Event For GoodConnectivity
,I/ActivityManager(  965): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4833 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/HyLog   ( 4833): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4833): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4833): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4833): DownloadService onCreate
,D/EAS     ( 4602): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4602): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4833): in removeSpuriousFiles
,D/eas_req ( 4602): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  965): doBoolean: SET ps 0
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2029): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2029): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2029): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd: failed to issue private commands
V/DownloadManager( 4833): DownloadService onStartCommand
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/DownloadManager( 4833): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/DhcpStateMachine(  965): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  965): DHCP Start wake lock is acquired.
,V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@42829c68 on behalf of 4833
,V/DownloadManager( 4833): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/WifiP2pService(  965): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431bba20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431bba20 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Setting iface cfg
I/DownloadManager( 4833): in trimDatabase
V/DownloadManager( 4833): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4356): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4356): action = android.net.conn.CONNECTIVITY_CHANGE
D/CommandListener(  264): Trying to bring up wlan0
I/LgeMiscReceiver( 4356): networkInfo.isConnected() = false
V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@4282bb18 on behalf of 4833
V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@4282cdc0 on behalf of 4833
D/WifiStateMachine(  965): addressUpdated: 192.168.1.121/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  965): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  965): handleMessage: X
W/linker  ( 4602): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4602): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4602): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4602): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4602): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4602): register_HtmlEditor, Success
D/HtmlEditor( 4602): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4602): register_HtmlEditorTimer, Success
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
,W/Settings( 4602): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
,D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-19ms what=131212 obj=192.168.1.121/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196613
,D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-19ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  965): doBoolean: SET ps 1
,V/DownloadManager( 4833): DownloadService onDestroy
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2029): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2029): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2029): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
I/ActivityManager(  965): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4854 uid=10052 gids={50052, 3003}
D/WifiP2pService(  965): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): DHCP successful
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  965): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState enter
,D/WifiStateMachine(  965): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  391): Reading a NULL string not supported here.
,E/Parcel  (  391): Reading a NULL string not supported here.
,D/WifiStateMachine(  965): handleMessage: X
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
I/ActivityManager(  965): Killing 3958:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,W/WifiStateTracker(  965): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  965): 
W/WifiStateTracker(  965):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  965):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  965): handleMessage: E msg.what=135190
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  965): processMsg: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
E/Parcel  (  391): Reading a NULL string not supported here.
D/WifiStateMachine(  965): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  965): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): CaptivePortalCheckState enter
D/WifiStateMachine(  965): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,D/WifiStateMachine(  965): handleMessage: E msg.what=131092
D/WifiStateMachine(  965): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  965): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  391): Reading a NULL string not supported here.
,E/Parcel  (  391): Reading a NULL string not supported here.
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  965): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
,E/Parcel  (  391): Reading a NULL string not supported here.
,D/WifiStateMachine(  965): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  965): transitionTo: destState=ConnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/HyLog   ( 4854): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4854): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4854): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,E/ActivityThread(  965): Failed to find provider info for com.lge.ims.provisioning
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/Parcel  (  391): Reading a NULL string not supported here.
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=2 connState=1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/LGRssiData( 4854): [loadRssi] File not exist 
V/LGRssiData( 4854): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4854): [loadFeatureFromXml] *** start feature loading from xml
,D/MobileConnectivityChangeReceiver( 4854): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4854): onReceive CONNECTIVITY_CHANGE networkType=1
W/BaseRuntimeLoader( 4854): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4854): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4854): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4854): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4854): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4854): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4854): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  965): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4876 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  965): Killing 4327:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,E/PhoneMonitor( 4854): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4854): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/CheckinService( 1959): Checking schedule, now: 1449752969095 next: 1449752912903
,I/CheckinService( 1959): active receiver: enabled
,V/        (  264): RouteController
D/HyLog   ( 4876): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4876): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4876): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  391): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  391): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  391): |CAC| updateNetCfgInfo
V/QCNEA   (  391): |CAC| *********************************************
V/QCNEA   (  391): |CAC|                   Netconfig               
V/QCNEA   (  391): |CAC| *********************************************
V/QCNEA   (  391): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  391): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  391): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  391): |CAC| 	NetConfig: ip4        =192.168.1.121
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
D/QCNEA   (  391): |CAC| dispatchNetCfg: updating:0xb83418dc
,D/QCNEA   (  391): |CAC| readCallback: read len:0, ret:-1, errno:11
I/CheckinService( 1959): Preparing to send checkin request
,I/EventLogService( 1959): Accumulating logs since 1449752880461
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/DhcpStateMachine(  965): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  965): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinRequestBuilder( 1959): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  965): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4903 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  965): Killing 4528:com.android.defcontainer/u0a4 (adj 15): empty #17
E/ActivityThread( 1959): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4903): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4903): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4903): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2886): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2886): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  965): Killing 4561:com.google.android.partnersetup/u0a9 (adj 15): empty #17
I/LGDMClient( 2886): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4921 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
,E/LGDMClient( 2886): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2886): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2886): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2886): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4921): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4921): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4921): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4921): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4921): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  965): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4935 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  965): Killing 4589:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4935): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4935): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4935): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 4935): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4935): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4935): intf.getDisplayName() = lo
I/Wireless_Storage( 4935): intf.getDisplayName() = sit0
I/Wireless_Storage( 4935): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4935): intf.getDisplayName() = teql0
,I/Wireless_Storage( 4935): intf.getDisplayName() = wlan0
D/NFS     ( 4935): interface name:wlan0 name:wlan0
D/NFS     ( 4935): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4935): interface name:wlan0 name:wlan0
D/NFS     ( 4935): addr:192.168.1.121 broadcast:192.168.1.255
,I/Wireless_Storage( 4935): CONNECT : WIFI_CONNECT
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  965): GC_EXPLICIT freed 23447K, 49% free 29649K/57596K, paused 3ms+8ms, total 155ms
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  965): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4947 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 4220:com.android.contacts/u0a21 (adj 15): empty #17
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HyLog   ( 4947): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4947): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4947): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
D/WifiController(  965): battery changed pluggedType: 2
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
,W/GAV2    ( 4947): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 1559): GC_EXPLICIT freed 1203K, 29% free 17812K/24832K, paused 1ms+2ms, total 25ms
,I/GLSUser ( 1559): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1559): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1559): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1559): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1559): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1959): awaiting user notification for token
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x43174c78: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,V/WebViewChromium( 4947): Binding Chromium to the main looper Looper (main, tid 1) {427ec4f8}
,I/chromium( 4947): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4947): Initializing chromium process, renderers=0
,W/chromium( 4947): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4947): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4947): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4947): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4947): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4947): Remote Branch: 
I/Adreno-EGL( 4947): Local Patches: 
I/Adreno-EGL( 4947): Reconstruct Branch: 
I/ActivityManager(  965): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4978 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/NSApplication( 4947): Starting up...
D/HyLog   ( 4978): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4978): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4978): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): Killing 4236:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
,W/dalvikvm( 4978): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4978): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4978): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4978): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4978): VFY: replacing opcode 0x62 at 0x005e
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,I/MultiDex( 4978): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4978): install
,D/QRemote ( 4785): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4785): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/MultiDex( 4978): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4978): loading existing secondary dex files
,D/QRemote ( 4785): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/MultiDex( 4978): load found 3 secondary dex files
,I/QRemote ( 4785): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/MultiDex( 4978): install done
,D/QRemote ( 4785): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4785): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4748): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4748): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4785): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4785): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4785): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 4785): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/dalvikvm( 4978): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4978): VFY: unable to resolve instance field 61
,D/dalvikvm( 4978): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4978): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4978): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4978): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4978): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4978): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4978): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4978): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4978): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4978): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427e8390
,D/dalvikvm( 4978): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427e8390
,D/dalvikvm( 4978): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427e8390, skipping init
,D/dalvikvm( 4978): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427e8390
D/dalvikvm( 4978): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427e8390
,V/JNIHelp ( 4978): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4978): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427e8390
,D/dalvikvm( 4978): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x427e8390
D/dalvikvm( 4978): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427e8390
,D/dalvikvm( 4978): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427e8390
,I/ProviderInstaller( 4978): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1559): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1559): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1559): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1959): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1755): callingUid 10006, callindPid: 1755
,E/MDM     ( 1425): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1959): Restart initialization of location
,I/dalvikvm( 4978): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4978): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4978): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4978): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4978): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4978): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fa4000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fa4000
,D/wpa_supplicant( 2029): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2029): EAPOL: disable timer tick
D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=1990698610
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4978): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4298e0f8
D/dalvikvm( 4978): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4298e0f8
,D/dalvikvm( 4978): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4298e0f8, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Settings( 4978): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  965): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4978): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm( 4999): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4978): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4978): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 80ms
,I/Adreno-EGL( 4978): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4978): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4978): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4978): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4978): Remote Branch: 
I/Adreno-EGL( 4978): Local Patches: 
I/Adreno-EGL( 4978): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  965): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  965): handleMessage: X
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  965):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  965): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,I/Adreno-EGL( 4978): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4978): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4978): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4978): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4978): Remote Branch: 
I/Adreno-EGL( 4978): Local Patches: 
I/Adreno-EGL( 4978): Reconstruct Branch: 
,I/Adreno-EGL( 4978): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4978): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4978): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4978): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4978): Remote Branch: 
I/Adreno-EGL( 4978): Local Patches: 
I/Adreno-EGL( 4978): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4691): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4691): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DhcpStateMachine(  965): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  965): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  965): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.121
V/LgDhcpStateMachineHelper(  965): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  965): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  965): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  965): RunningState
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=3008630695
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1959): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1959): Sending checkin request (11604 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1959): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1959): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1559): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1559): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1559): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1559): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1559): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1959): awaiting user notification for token
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x4298cf88: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1959): Classify the device as Phone.
,I/CheckinTask( 1959): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinService( 1959): Checking schedule, now: 1449752971725 next: 1450330367718
,I/CheckinService( 1959): active receiver: disabled
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/GCM     ( 1559): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  391): Reading a NULL string not supported here.
,E/Parcel  (  391): Reading a NULL string not supported here.
,D/WifiStateMachine(  965): handleMessage: X
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/GCM     ( 1559): Connected
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] request level :IDLE....
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/AppUp4:CustModeStarterReceiver( 4045): onReceive
,D/AppUp4:CustFacade( 4045): Context : android.app.ReceiverRestrictedContext@42801530
D/AppUp4:CustFacade( 4045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4045): isOpenOperator : true
,D/AppUp4:CustFacade( 4045): isPhone : true
,I/LicenseContentProvider( 3023): start selecting data
,D/SIMObserver( 3023): simInfo1
,I/AppUp4:EulaManager( 4045): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4045): begin check event
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/AppUp4:CustModeStarterReceiver( 4045): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4045): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4045): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4045): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4045): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4045): handleAsyncCustNotification do not startCustService
,D/GCM     ( 1559): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/EAS     ( 4602): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4833): DownloadService onCreate
,D/EAS     ( 4602): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4833): in removeSpuriousFiles
,V/DownloadManager( 4833): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/eas_req ( 4602): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@428330f8 on behalf of 4833
I/DownloadManager( 4833): in trimDatabase
V/DownloadManager( 4833): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@42834f68 on behalf of 4833
V/DownloadManager( 4833): DownloadService onStartCommand
V/DownloadManager( 4833): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@42836c38 on behalf of 4833
I/LgeMiscReceiver( 4356): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4356): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4356): networkInfo.isConnected() = false
W/Settings( 4602): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4833): DownloadService onDestroy
D/MobileConnectivityChangeReceiver( 4854): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4854): onReceive CONNECTIVITY_CHANGE networkType=1
D/LGDMClient( 2886): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2886): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4921): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2886): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4935): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4935): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4921): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2886): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2886): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2886): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2886): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4045): onReceive
D/AppUp4:CustFacade( 4045): Context : android.app.ReceiverRestrictedContext@42801530
D/AppUp4:CustFacade( 4045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4045): isOpenOperator : true
,D/AppUp4:CustFacade( 4045): isPhone : true
,I/LicenseContentProvider( 3023): start selecting data
,D/SIMObserver( 3023): simInfo1
,I/AppUp4:EulaManager( 4045): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4045): begin check event
,I/AppUp4:CustModeStarterReceiver( 4045): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4833): DownloadService onCreate
,I/DownloadManager( 4833): in removeSpuriousFiles
,D/EAS     ( 4602): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4602): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4833): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@4283b808 on behalf of 4833
,V/DownloadManager( 4833): DownloadService onStartCommand
I/DownloadManager( 4833): in trimDatabase
,V/DownloadManager( 4833): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@4283cd90 on behalf of 4833
,V/DownloadManager( 4833): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 4356): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4356): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4356): networkInfo.isConnected() = true
,D/PhoneState( 4356): setPdpRejectCasuse : false
,W/Settings( 4602): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@4283ea60 on behalf of 4833
,D/MobileConnectivityChangeReceiver( 4854): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4854): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4833): DownloadService onDestroy
,D/LGDMClient( 2886): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2886): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4921): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2886): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4935): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4935): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4921): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2886): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2886): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2886): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2886): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4045): onReceive
,D/AppUp4:CustFacade( 4045): Context : android.app.ReceiverRestrictedContext@42801530
,D/AppUp4:CustFacade( 4045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4045): isOpenOperator : true
,D/AppUp4:CustFacade( 4045): isPhone : true
,I/LicenseContentProvider( 3023): start selecting data
,D/SIMObserver( 3023): simInfo1
,I/AppUp4:EulaManager( 4045): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4045): begin check event
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/AppUp4:CustModeStarterReceiver( 4045): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/DownloadManager( 4833): DownloadService onCreate
I/DownloadManager( 4833): in removeSpuriousFiles
V/DownloadManager( 4833): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4602): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@42843188 on behalf of 4833
D/EAS     ( 4602): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4833): in trimDatabase
V/DownloadManager( 4833): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4833): DownloadService onStartCommand
V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@42844af8 on behalf of 4833
V/DownloadManager( 4833): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4356): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4356): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4356): networkInfo.isConnected() = true
D/PhoneState( 4356): setPdpRejectCasuse : false
V/DownloadManager( 4833): created cursor android.database.sqlite.SQLiteCursor@428467c8 on behalf of 4833
W/Settings( 4602): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4854): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4854): onReceive CONNECTIVITY_CHANGE networkType=1
D/LGDMClient( 2886): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4833): DownloadService onDestroy
D/LGDMClient( 2886): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2886): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMSGCM( 4921): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,E/LGDMClient( 2886): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2886): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2886): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/NFS     ( 4935): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4935): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2886): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
W/ContextImpl( 4921): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/WifiServiceExtension(  965): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/dalvikvm(  965): GC_EXPLICIT freed 2332K, 49% free 29560K/57596K, paused 5ms+13ms, total 217ms
,I/GAV2    ( 4947): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/Finsky  ( 4253): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4253): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,W/ProcessCpuTracker(  965): Skipping unknown process pid 5131
,I/ActivityManager(  965): Killing 4619:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.471313 Y: -0.392929 Z: 9.755478 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471313 .y:-0.392929 .z:9.755478
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.468185 Y: -0.400696 Z: 9.753265 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.468185 .y:-0.400696 .z:9.753265
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,E/SlideAside( 3780): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 3780): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  965): Handling package changes for user 0
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5136 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5136): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/HyLog   ( 5136): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5136): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  965):   Scheme: "sms"
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5136): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5136): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5136): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5136): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5136): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5136): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5136): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5136): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5136): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5136): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5136): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5136): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5136): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5136): MmsConfig.loadFromResources
,E/Babel   ( 5136): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 5136): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5136): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4045): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4045): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 4045): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,V/LGRssiData( 5136): [loadRssi] File not exist 
V/LGRssiData( 5136): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5136): [loadFeatureFromXml] *** start feature loading from xml
,I/AppUp4:CustModeStarterReceiver( 4045): onReceive
D/AppUp4:CustFacade( 4045): Context : android.app.ReceiverRestrictedContext@42801530
D/AppUp4:CustFacade( 4045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4045): isOpenOperator : true
,D/AppUp4:CustFacade( 4045): isPhone : true
I/LicenseContentProvider( 3023): start selecting data
,V/TelephonyAutoProfiling( 5136): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/SIMObserver( 3023): simInfo1
V/TelephonyAutoProfiling( 5136): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5136): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:EulaManager( 4045): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4045): begin check event
D/AppUp4:Utils( 4045): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4045): Event For Nothing, skip.
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5184 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,V/GmsNetworkLocationProvi( 1425): DISABLE
,I/GCoreNlp( 1425): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/HyLog   ( 5184): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5184): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5184): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/WifiController(  965): battery changed pluggedType: 2
,I/SystemConfig( 5184): BUILD Country: EU
,I/SystemConfig( 5184): BUILD Operator: OPEN
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  965): Killing 4748:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  965): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5200 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
,D/LocationProviderProxy(  965): applying state to connected service
,I/SystemConfig( 5184): systemFeature RCS result false
,D/SystemConfig( 5184): refreshRcsSupport() :false
,D/LocationProviderProxy(  965): applying state to connected service
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): Killing 4785:com.lge.qremote/u0a96 (adj 15): empty #17
D/HyLog   ( 5200): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5200): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5200): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): Killing 4833:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2704): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1959): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1959): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  965): Delaying start of: ServiceRecord{431e9a18 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1959): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1959): GC_CONCURRENT freed 1936K, 22% free 19557K/24832K, paused 4ms+5ms, total 61ms
,I/IcingCorporaProvider( 2704): UpdateCorporaTask done [took 223 ms] updated apps [took 223 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  965): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  965): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  965): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  965): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  965): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/GAV4    ( 5136): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/PowerManagerService(  965): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  965): [updateScreenState] screen on = false
D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  965): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = true
D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8164 usec
,D/qcom_sensors_hal(  965): hal_acquire_resources
,I/qcom_sensors_hal(  965): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  965): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  965): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  965): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  965): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  965): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  965): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  965): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.458786 Y: -0.393646 Z: 9.758881 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458786 .y:-0.393646 .z:9.758881
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.470886 Y: -0.391296 Z: 9.772110 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470886 .y:-0.391296 .z:9.772110
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Sensors (  377): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  965): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  965): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  965): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  965): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  965): proximitySensorChanged  positive = true
I/KnockOnPowerController(  965): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.461639 Y: -0.403290 Z: 9.761017 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461639 .y:-0.403290 .z:9.761017
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.465607 Y: -0.388535 Z: 9.767273 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465607 .y:-0.388535 .z:9.767273
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.453644 Y: -0.393173 Z: 9.780365 
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.463638 Y: -0.414261 Z: 9.774811 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.453644 .y:-0.393173 .z:9.780365
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.451859 Y: -0.418762 Z: 9.750580 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451859 .y:-0.418762 .z:9.750580
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  965): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44db9410)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  965): **** SHOWN CALLED ****
I/WindowManager(  965): No lock screen! windowToken=null
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8cb0450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.473724 Y: -0.405930 Z: 9.737411 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.473724 .y:-0.405930 .z:9.737411
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  965): handleScreenStateChanged: true
,D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  965): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
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
,D/WifiStateMachine(  965): handleMessage: E msg.what=132097
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  965): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2029): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2029): initialize kt scan interval and do scan state=9
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiOffDelayIfNotUsed(  965): stopMonitoring
E/Parcel  (  391): Reading a NULL string not supported here.
,E/Parcel  (  391): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 965
,V/SRS_Proc(  270): ParamSet string: screen_state=on
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,E/SlideAside( 3780): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43336698 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1825): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:9:50
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SlideAside( 3780): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/UpdateThreadPoolManager( 1825): 2 : This is isUpdating : false
D/WeatherAncestor( 1825): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:9:50
D/WeatherService( 1825): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1825): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1825): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
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
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.457596 Y: -0.394333 Z: 9.781311 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457596 .y:-0.394333 .z:9.781311
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/qdlights( 1157): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1157): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1157): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  965): Excessive delay in blankDisplay() while turning screen off: 412ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.467361 Y: -0.393372 Z: 9.780548 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467361 .y:-0.393372 .z:9.780548
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449752990373, nextTick: 9659, mDrawingTime: 0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449752990416, nextTick: 9617, mDrawingTime: 0
D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
D/WeatherService( 1825): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:9:50
,D/WeatherService( 1825): 2 : ACTION screen on
,D/WeatherService( 1825): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1825): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:9:50
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
,E/Parcel  (  391): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_ON
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
,D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
D/qcom_sensors_hal(  965): hal_acquire_resources
D/qcom_sensors_hal(  965): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  965): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3}
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  965): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  965): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  965): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  965): Vibrator off
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{42c1f478 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/WifiStateMachine(  965): handleScreenStateChanged: false
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 true
D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,D/UsbSettings( 2636): [AUTORUN] onDestroy() : getDefaultFunction =boot
,V/UsbSettings( 2636): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{442d6548 u0 com.test.thalitest/.MainActivity t3} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiController(  965): CMD_SCREEN_OFF 
,D/WifiController(  965): shouldWifiStayAwake TRUE
V/UsbSettings( 2636): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2636): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 965
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
D/KeyguardViewManager( 1141): onScreenTurnedOff()
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1157): clear
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
,D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
,D/WifiStateMachine(  965): handleMessage: X
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{42c1f478 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327b618 stackId=1, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
E/Parcel  (  391): Reading a NULL string not supported here.
,E/Parcel  (  391): Reading a NULL string not supported here.
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
D/WeatherService( 1825): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:9:50
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/WeatherService( 1825): 2 : ACTION screen off
,D/WeatherService( 1825): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:9:50
D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
,D/NfcService( 1474): NFC-C OFF
,D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
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
,I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  377): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1559): Vacuum at: now=1449752999750 tag=VacuumService
,I/GoogleURLConnFactory( 1559): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1559): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449753000033, nextTick: 59999, mDrawingTime: 0
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449753000034, nextTick: 59999, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1559):  no longer exists, so no auth token.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1559): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449753008377601982; DSPS: 5290946; Offset: 1449752846910744072
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449753028383524474; DSPS: 5946500; Offset: 1449752846910746154
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449753048385371237; DSPS: 6601920; Offset: 1449752846910761862
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449753060041, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449753060054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449753068386564303; DSPS: 7257319; Offset: 1449752846910764743
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449753088388420284; DSPS: 7912740; Offset: 1449752846910759152
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449753108390071528; DSPS: 8568154; Offset: 1449752846910762446
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449753120030, nextTick: 59994, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449753120072, nextTick: 59960, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449753128391816676; DSPS: 9223572; Offset: 1449752846910737575
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449753148393389116; DSPS: 9878983; Offset: 1449752846910753618
,D/wpa_supplicant( 2029): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 7 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 3 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 5 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2029): wlan0: BSS: Remove id 8 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 a0:c5:62:7a:49:97]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 a0:c5:62:7a:49:96]

```
