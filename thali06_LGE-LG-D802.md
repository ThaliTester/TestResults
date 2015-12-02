#### Test 52383621d5a0cb8_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4600): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  959): Killing 3527:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d7aad8 stackId=1, 1 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{4308f448 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1849): GC_CONCURRENT freed 1729K, 22% free 19423K/24832K, paused 2ms+4ms, total 45ms
D/dalvikvm( 1849): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 1849): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ConfigFetchService( 1849): fetch service done; releasing wakelock
I/ConfigFetchService( 1849): stopping self
D/ChimeraCfgMgr( 1849): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1849): Module APK com.google.android.play.games already loaded
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1849): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1849): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1849): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4661): 
D/AndroidRuntime( 4661): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4661): CheckJNI is OFF
D/dalvikvm( 4661): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4661): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4661): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4661): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4661): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4661): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/WifiStateMachine(  959): handleMessage: E msg.what=131155
D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
D/WifiNative-wlan0(  959): doString: SIGNAL_POLL
D/wpa_supplicant( 2003): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2003): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2003): nl80211: survey data missing!
D/WifiStateMachine(  959): handleMessage: X
E/memtrack( 4661): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4661): failed to load memtrack module: -2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4661): Calling main entry com.android.commands.am.Am
I/ActivityManager(  959): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4661
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d7aad8 stackId=1, 2 tasks}
D/PermissionCache(  273): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (123 us)
V/ActivityManager(  959): Moving to PAUSING: ActivityRecord{4308f448 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  959): resumeTopActivityLocked: Pausing null
V/ActivityManager(  959): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  959): startService SlideAside
W/ContextImpl(  959): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  959): setFocusedStack: mFocusedStack=ActivityStack{42d7aad8 stackId=1, 2 tasks}
D/AndroidRuntime( 4661): Shutting down VM
D/ActivityManager(  959): allPausedActivitiesComplete: r=ActivityRecord{4308f448 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/dalvikvm( 4661): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 5ms
D/UsbSettingsControl( 2552): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2552): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3709): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  959): Moving to PAUSED: ActivityRecord{4308f448 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d7aad8 stackId=1, 2 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Restarting ActivityRecord{430277f8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  959): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4678 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3709): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3709): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  959): Moving to RESUMED: ActivityRecord{430277f8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4678): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4678): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4678): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4678): Binding Chromium to the background looper Looper (main, tid 1) {42809b48}
I/chromium( 4678): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4678): Initializing chromium process, renderers=0
W/chromium( 4678): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4678): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4678): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4678): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4678): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4678): Remote Branch: 
I/Adreno-EGL( 4678): Local Patches: 
I/Adreno-EGL( 4678): Reconstruct Branch: 
I/dalvikvm( 4678): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4678): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4678): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4678): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4678): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4678): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4678): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4678): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4678): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4678): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4678): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4678): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4678): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4678): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4678): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4678): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4678): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4678): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4678): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4678): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4678): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4678): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4678): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4678): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4678): Enabling debug mode 0
,W/AwContents( 4678): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  959): Displayed com.test.thalitest/.MainActivity: +359ms
,I/ActivityManager( 4678): Timeline: Activity_idle id: android.os.BinderProxy@4280b318 time:115152
,D/JsMessageQueue( 4678): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4678): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4280f830
,D/dalvikvm( 4678): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4280f830
,D/jxcore_app_log( 4678): JniHelper::setJavaVM(0x416d5838), pthread_self() = 1638700664
,D/JX-Cordova( 4678): jxcore cordova android initializing
,I/dalvikvm( 4678): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 4678): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4678): VFY: replacing opcode 0x6e at 0x0045
,I/ActivityManager(  959): Timeline: Activity_windows_visible id: ActivityRecord{430277f8 u0 com.test.thalitest/.MainActivity t3} time:115551
D/ActivityManager(  959): no-history finish of ActivityRecord{4308f448 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  959): Finishing activity token=Token{4291cf18 ActivityRecord{4308f448 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  959): Moving to FINISHING: ActivityRecord{4308f448 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430277f8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  959): Moving to STOPPING: ActivityRecord{4308f448 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,D/UsbSettings( 2552): [AUTORUN] onStop()
,V/ActivityManager(  959): Moving to STOPPED: ActivityRecord{4308f448 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4678): GC_CONCURRENT freed 2757K, 12% free 21852K/24832K, paused 2ms+1ms, total 44ms
,D/dalvikvm( 4678): GC_FOR_ALLOC freed 224K, 13% free 21835K/24832K, paused 22ms, total 22ms
,D/dalvikvm( 4678): GC_FOR_ALLOC freed 174K, 12% free 21879K/24832K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 23.679MB for 146998-byte allocation
,D/dalvikvm( 4678): GC_FOR_ALLOC freed 275K, 13% free 21909K/24976K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 23.780MB for 220492-byte allocation
,D/dalvikvm( 4678): GC_FOR_ALLOC freed 374K, 13% free 21984K/25192K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 23.958MB for 330734-byte allocation
,D/dalvikvm( 4678): GC_FOR_ALLOC freed 576K, 14% free 22108K/25516K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 24.236MB for 496096-byte allocation
,D/dalvikvm( 4678): GC_FOR_ALLOC freed 879K, 15% free 22287K/26004K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 24.648MB for 744140-byte allocation
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  959): battery changed pluggedType: 2
,W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  959): battery changed pluggedType: 2
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/dalvikvm( 4678): GC_FOR_ALLOC freed 1303K, 16% free 22548K/26732K, paused 23ms, total 24ms
,D/dalvikvm( 4678): GC_CONCURRENT freed 1671K, 15% free 22925K/26732K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 4678): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4678): GC_FOR_ALLOC freed 401K, 15% free 22885K/26732K, paused 38ms, total 39ms
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 26.120MB for 1674304-byte allocation
,D/dalvikvm( 4678): GC_CONCURRENT freed 1679K, 18% free 23454K/28368K, paused 1ms+2ms, total 26ms
,D/dalvikvm( 4678): GC_FOR_ALLOC freed 1419K, 17% free 23550K/28368K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 27.567MB for 2511452-byte allocation
,D/dalvikvm( 4678): GC_CONCURRENT freed 322K, 16% free 25966K/30824K, paused 2ms+7ms, total 43ms
,D/dalvikvm( 4678): GC_FOR_ALLOC freed 4360K, 21% free 24515K/30824K, paused 34ms, total 34ms
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 29.707MB for 3767174-byte allocation
,D/dalvikvm( 4678): GC_CONCURRENT freed 2799K, 26% free 25607K/34504K, paused 1ms+4ms, total 29ms
,I/GAV2    ( 4600): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/WifiController(  959): battery changed pluggedType: 2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/dalvikvm( 4678): GC_FOR_ALLOC freed 535K, 27% free 25508K/34504K, paused 25ms, total 25ms
,W/jxcore-log( 4678): Initializing JXcore engine
,W/jxcore-log( 4678): JXcore engine is ready
,W/jxcore-log( 4678): Starting JXcore engine
,D/dalvikvm( 4678): GC_CONCURRENT freed 371K, 19% free 28150K/34504K, paused 1ms+1ms, total 25ms
,W/jxcore-log( 4678): Platform android
W/jxcore-log( 4678): 
,W/jxcore-log( 4678): Process ARCH arm
W/jxcore-log( 4678): 
,D/WifiStateMachine(  959): handleMessage: E msg.what=131155
,D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
D/WifiNative-wlan0(  959): doString: SIGNAL_POLL
D/wpa_supplicant( 2003): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2003): wlan0: Control interface command 'SIGNAL_POLL'
,I/ConfigService( 1536): onDestroy
,D/wpa_supplicant( 2003): nl80211: survey data missing!
,D/WifiStateMachine(  959): handleMessage: X
,I/jxcore-log( 4678): JXcore Cordova bridge is ready!
I/jxcore-log( 4678): 
,W/jxcore-log( 4678): JXcore engine is started
,I/chromium( 4678): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 4678): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 4678): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,V/ActivityManager(  959): Finishing activity token=Token{4317dd48 ActivityRecord{430277f8 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
,V/ActivityManager(  959): Moving to PAUSING: ActivityRecord{430277f8 u0 com.test.thalitest/.MainActivity t3 f}
,I/chromium( 4678): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4678): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4678): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
,D/dalvikvm(  959): GC_FOR_ALLOC freed 646K, 49% free 29583K/57512K, paused 83ms, total 88ms
,W/PluginManager( 4678): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 102ms. Plugin should use CordovaInterface.getThreadPool().
,V/ActivityManager(  959): Moving to PAUSED: ActivityRecord{430277f8 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  959): Moving to STOPPING: ActivityRecord{430277f8 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d7aad8 stackId=1, 2 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  959): moveHomeStack:
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
,V/ActivityManager(  959): Moving to RESUMED: ActivityRecord{430c4c58 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  959): resumeTopActivityLocked: Resumed ActivityRecord{430c4c58 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1490): [Launcher.java:4947:onStart()]onStart
I/ActivityManager(  959): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c4c58 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1490): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1490): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1490): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1817): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:41:56
,D/UpdateThreadPoolManager( 1817): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1817): 2 : quick cover state : opened : 0
,D/WeatherService( 1817): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1817): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1817): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1817): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1817): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1817): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:41:56
,D/WeatherService( 1817): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1817): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1817): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1817): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1817): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1817): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1817): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1817): 2 : This is isUpdating : false
D/WeatherService( 1817): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1817): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1817): 2 : Map key string is -2
,D/lim     ( 1817): 2 : time = 12:41
,I/WeatherReflect( 1817): Model Name : LG-D802
D/WeatherTheme( 1817): 2 : Different view - status_min_formatted : 40 != 41
D/WeatherTheme( 1817): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
,D/WeatherTheme( 1817): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1817): 2 : Fixed theme : optimus
,D/WeatherTheme( 1817): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherQuickCover( 1817): 2 : quick cover state : opened : 0
D/Weather.Utils( 1817): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1817): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1817): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/WifiController(  959): battery changed pluggedType: 2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1490): GC_CONCURRENT freed 5407K, 9% free 60914K/66508K, paused 2ms+3ms, total 28ms
,D/dalvikvm( 1490): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 5868K, 10% free 71736K/78860K, paused 29ms, total 30ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1490): GC_FOR_ALLOC freed 5013K, 9% free 61982K/67896K, paused 20ms, total 20ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@4280dea8 time:118432
,D/UsbSettings( 2552): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2552): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2552): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2552): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  959): Moving to DESTROYING: ActivityRecord{4308f448 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  959): Moving to DESTROYED: ActivityRecord{4308f448 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c4c58 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  959): Timeline: Activity_windows_visible id: ActivityRecord{430c4c58 u0 com.lge.launcher2/.Launcher t1} time:118468
V/ActivityManager(  959): Moving to FINISHING: ActivityRecord{430277f8 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  959): Killing 4155:com.google.android.talk/u0a77 (adj 15): empty #17
V/ActivityManager(  959): Moving to DESTROYING: ActivityRecord{430277f8 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4678): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c4c58 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  959): Moving to DESTROYED: ActivityRecord{430277f8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c4c58 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  959): battery changed pluggedType: 2
W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  959): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1226): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  959): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1226): Disconnected process message: 10
W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1490): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  959): handleMessage: E msg.what=131155
,D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  959): doString: SIGNAL_POLL
D/wpa_supplicant( 2003): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2003): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2003): nl80211: survey data missing!
,D/WifiStateMachine(  959): handleMessage: X
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056520038, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056520041, nextTick: 59991, mDrawingTime: 0
,E/ThermalEngine(  291): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/WeatherService( 1817): 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:42:0
,D/WeatherService( 1817): 2 : TimeTick Intent And Screen On
D/WeatherService( 1817): 2 : SDK version : 19
,D/WeatherQuickCover( 1817): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1817): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1817): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1817): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1817): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1817): 2 : This is isUpdating : false
D/WeatherService( 1817): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1817): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1817): 2 : Map key string is -2
,D/lim     ( 1817): 2 : time = 12:42
,I/WeatherReflect( 1817): Model Name : LG-D802
D/WeatherTheme( 1817): 2 : Different view - status_min_formatted : 41 != 42
,D/WeatherTheme( 1817): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1817): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1817): 2 : Fixed theme : optimus
,D/WeatherTheme( 1817): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1817): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:42:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  959): handleMessage: E msg.what=131155
,D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
D/WifiNative-wlan0(  959): doString: SIGNAL_POLL
D/wpa_supplicant( 2003): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2003): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2003): nl80211: survey data missing!
,D/WifiStateMachine(  959): handleMessage: X
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.560196 Y: -0.395111 Z: 9.769684 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.560196 .y:-0.395111 .z:9.769684
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.557678 Y: -0.385803 Z: 9.751236 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.557678 .y:-0.385803 .z:9.751236
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  959): handleMessage: E msg.what=131155
,D/WifiStateMachine(  959): processMsg: ConnectedState
,D/WifiStateMachine(  959): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  959): doString: SIGNAL_POLL
D/wpa_supplicant( 2003): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2003): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2003): nl80211: survey data missing!
,D/WifiStateMachine(  959): handleMessage: X
,D/Finsky  ( 4238): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4238): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  959): battery changed pluggedType: 2
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  959): handleMessage: E msg.what=131155
,D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  959): doString: SIGNAL_POLL
D/wpa_supplicant( 2003): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2003): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2003): nl80211: survey data missing!
,D/WifiStateMachine(  959): handleMessage: X
,D/WifiStateMachine(  959): handleMessage: E msg.what=131155
,D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  959): doString: SIGNAL_POLL
D/wpa_supplicant( 2003): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2003): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2003): nl80211: survey data missing!
,D/WifiStateMachine(  959): handleMessage: X
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  959): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  959): handleMessage: E msg.what=131155
,D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  959): doString: SIGNAL_POLL
D/wpa_supplicant( 2003): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2003): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2003): nl80211: survey data missing!
,D/WifiStateMachine(  959): handleMessage: X
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.557693 Y: -0.365082 Z: 9.783676 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.557693 .y:-0.365082 .z:9.783676
I/PowerManagerService(  959): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  959): [updateScreenState] screen on = false
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,I/qcom_sensors_hal(  959): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  959): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,D/qcom_sensors_hal(  959): _hal_sensors_batch: sample_rate=20 report_rate=0 curr sample rate:0 cur rpt rate:0 max:20.000000 min:1.000000
D/qcom_sensors_hal(  959): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,I/qcom_sensors_hal(  959): _hal_sensors_flush: handle=35
D/KnockOnPowerController(  959): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  959): [setProximitySensorEnabled] enable = true
D/qcom_sensors_hal(  959): _hal_sensors_flush: handle 35 is inactive
I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  959): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  959): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 6179 usec
,D/qcom_sensors_hal(  959): hal_acquire_resources
,I/qcom_sensors_hal(  959): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
,D/qcom_sensors_hal(  959): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,I/qcom_sensors_hal(  959): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  959): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  959): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  959): hal_sam_send_cancel: Sending cancel to 21
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  959): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  959): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.560165 Y: -0.378601 Z: 9.772430 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.560165 .y:-0.378601 .z:9.772430
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.554871 Y: -0.386597 Z: 9.792831 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.554871 .y:-0.386597 .z:9.792831
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,I/Sensors (  426): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  959): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  959): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  959): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  959): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  959): proximitySensorChanged  positive = true
I/KnockOnPowerController(  959): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.550446 Y: -0.382141 Z: 9.800735 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.550446 .y:-0.382141 .z:9.800735
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.548569 Y: -0.378723 Z: 9.787781 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.548569 .y:-0.378723 .z:9.787781
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.548828 Y: -0.388107 Z: 9.793228 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.548828 .y:-0.388107 .z:9.793228
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.554840 Y: -0.392792 Z: 9.798416 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.554840 .y:-0.392792 .z:9.798416
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  959): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@431cc7e8)
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  959): **** SHOWN CALLED ****
,D/SurfaceFlinger(  273): Screen released, type=0 flinger=0xb7e29450
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,I/WindowManager(  959): No lock screen! windowToken=null
D/qdhwcomposer(  273): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.572495 Y: -0.380661 Z: 9.779419 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.572495 .y:-0.380661 .z:9.779419
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,D/NfcServiceBRCM( 1475): NFC is already turned off.
,D/WifiStateMachine(  959): handleScreenStateChanged: true
,D/WifiStateMachine(  959): handleMessage: E msg.what=131154
D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  959): doString: SIGNAL_POLL
D/wpa_supplicant( 2003): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2003): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2003): nl80211: survey data missing!
D/WifiStateMachine(  959): handleMessage: X
,D/WifiStateMachine(  959): handleMessage: E msg.what=131127
D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
,D/WifiStateMachine(  959): processMsg: ConnectModeState
D/WifiStateMachine(  959): handleMessage: X
,D/WifiStateMachine(  959): handleMessage: E msg.what=131158
D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
,D/WifiStateMachine(  959): processMsg: ConnectModeState
D/WifiStateMachine(  959): processMsg: DriverStartedState
D/WifiStateMachine(  959): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  959): handleMessage: X
,D/WifiServiceExtension(  959): sendKtScanInterval  mRtspPlay : false
,D/WifiStateMachine(  959): handleMessage: E msg.what=132097
D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
,D/WifiStateMachine(  959): processMsg: ConnectModeState
D/WifiStateMachine(  959): processMsg: DriverStartedState
D/WifiStateMachine(  959): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  959): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2003): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2003): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2003): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  959): handleMessage: X
,D/WifiOffDelayIfNotUsed(  959): stopMonitoring
,E/AudioSystem(  959): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 959
V/SRS_Proc(  276): ParamSet string: screen_state=on
,D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
,I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=2
,V/EmotionalLed( 1159): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{432d55b0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1159): enqueuing start. mLedList.size()=2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1159): enqueuing end. mLedList.size()=3
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1817): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:42:17,
,I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/SlideAside( 3709): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
I/SlideAside( 3709): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1817): 2 : This is isUpdating : false
D/WeatherAncestor( 1817): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:42:17
,D/WeatherService( 1817): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1817): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1817): 2 : TimeTick Receiver Unregister
D/WifiStateMachine(  959): handleMessage: E msg.what=131155
D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
,D/WifiStateMachine(  959): handleMessage: X
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1817): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
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
,D/qdhwcomposer(  273): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  959): Excessive delay in blankDisplay() while turning screen off: 421ms
D/qdlights( 1159): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 195, B = 195
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1159): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1159): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 177, B = 177
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056538034, nextTick: 41997, mDrawingTime: 1
D/qdlights( 1159): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1159): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 165, B = 165
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
,D/qdlights( 1159): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056538056, nextTick: 41977, mDrawingTime: 0
,D/NfcServiceBRCM( 1475): NFC is already turned off.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1159): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 153, B = 153
D/WeatherService( 1817): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:42:18
D/WeatherService( 1817): 2 : ACTION screen on
D/WeatherService( 1817): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1817): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:42:18
,D/qdlights( 1159): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 147, B = 147
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  959): ACTION_SCREEN_ON
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/qdlights( 1159): set_light_notifications: 2,ff008d8d,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 141, B = 141
I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  959): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  959): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1143): notifyScreenOffLocked
V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
I/[LGHome]EVENT( 1490): [Launcher.java:894:onPause()]onPause
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.546524 Y: -0.387131 Z: 9.796616 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.546524 .y:-0.387131 .z:9.796616
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/ActivityManager(  959): Moving to PAUSING: ActivityRecord{430c4c58 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  959): hal_acquire_resources
D/qcom_sensors_hal(  959): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  959): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=1000
D/qdlights( 1159): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 135, B = 135
V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  959): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  959): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  959): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1159): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 129, B = 129
,D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/ActivityManager(  959): Moving to PAUSED: ActivityRecord{430c4c58 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  959): Moving to STOPPING: ActivityRecord{430c4c58 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/LGImmersionVibrator(  959): Vibrator off
I/[LGHome]EVENT( 1490): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  959): handleScreenStateChanged: false
D/WifiStateMachine(  959): handleMessage: E msg.what=131154
D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
D/WifiStateMachine(  959): handleMessage: X
D/WifiStateMachine(  959): handleMessage: E msg.what=131158
,D/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiStateMachine(  959): processMsg: L2ConnectedState
D/WifiStateMachine(  959): processMsg: ConnectModeState
D/WifiStateMachine(  959): processMsg: DriverStartedState
D/WifiStateMachine(  959): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  959): doBoolean: DRIVER SETSUSPENDMODE 1
D/KeyguardViewMediator( 1143): handleNotifyScreenOff
D/qdlights( 1159): set_light_notifications: 2,ff007b7b,10,0,2
D/KeyguardViewManager( 1143): onScreenTurnedOff()
D/qdlights( 1159): [Current] = 255, R = 0, G = 123, B = 123
D/wpa_supplicant( 2003): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2003): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/WifiController(  959): CMD_SCREEN_OFF 
D/WifiController(  959): shouldWifiStayAwake TRUE
,V/ActivityManager(  959): Moving to STOPPED: ActivityRecord{430c4c58 u0 com.lge.launcher2/.Launcher t1} (stop complete)
E/AudioSystem(  959): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 959
V/SRS_Proc(  276): ParamSet string: screen_state=off
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
,D/qdlights( 1159): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 117, B = 117
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1159): clear
D/wpa_supplicant( 2003): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  959):    returned true
D/WifiStateMachine(  959): handleMessage: X
,E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NfcServiceBRCM( 1475): NFC is already turned off.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 111, B = 111
V/TelephonyAutoProfiling(  959): [getValue] FEATURE key : trf_based_vzw, value : null
,V/LGRssiData(  959): [loadRssi] File not exist 
E/Parcel  (  469): Reading a NULL string not supported here.
,E/Parcel  (  469): Reading a NULL string not supported here.
E/Parcel  (  469): Reading a NULL string not supported here.
E/Parcel  (  469): Reading a NULL string not supported here.
,I/[LGHome]EVENT( 1490): [Launcher.java:1567:onReceive()]Screen Off
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 0
,D/WeatherService( 1817): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:42:18
D/WeatherService( 1817): 2 : ACTION screen off
,D/WeatherService( 1817): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:42:18
,D/qdlights( 1159): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 105, B = 105
I/rmt_storage(  486): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb852a178
I/rmt_storage(  486): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  486): wakelock acquired: 1, error no: 42
,I/rmt_storage(  486): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1202544072)
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  959): ACTION_SCREEN_OFF
,D/qdlights( 1159): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 99, B = 99
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/qdlights( 1159): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1159): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1159): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1159): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1159): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1159): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1159): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1159): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1159): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1159): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1159): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 33, B = 33
,I/rmt_storage(  486): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  486): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  486): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1202544072) wakelock released: 1, error no: 0
I/rmt_storage(  486): 
,E/Diag_Lib(  711): [IMS_FATAL]| 2912 | 715 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,I/rmt_storage(  486): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb852a178
D/qdlights( 1159): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1159): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1159): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1159): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Sensors (  426): sns_pwr.c(320):releasing wakelock
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  291): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  959): handleMessage: E msg.what=131155
,D/WifiStateMachine(  959): processMsg: ConnectedState
,D/WifiStateMachine(  959): processMsg: L2ConnectedState
,D/WifiStateMachine(  959): handleMessage: X
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056555798732711; DSPS: 5278057; Offset: 1449056394725215866
,I/GoogleURLConnFactory( 1536): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1536): No account for auth token provided
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536):  no longer exists, so no auth token.
,W/Uploader( 1536): No account for auth token provided
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056575800184578; DSPS: 5933464; Offset: 1449056394725233407
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  959): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056580038, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056580041, nextTick: 59991, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056595801503164; DSPS: 6588868; Offset: 1449056394725209219
,D/wpa_supplicant( 2003): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2003): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2003): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2003): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2003): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2003): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2003): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2003): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2003): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2003): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
,D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
,D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056615802382688; DSPS: 7244256; Offset: 1449056394725234251
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056635803242888; DSPS: 7899645; Offset: 1449056394725209441
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056640040, nextTick: 59989, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056640058, nextTick: 59974, mDrawingTime: 0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  959): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056655804551264; DSPS: 8555048; Offset: 1449056394725205561
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056675804983029; DSPS: 9210422; Offset: 1449056394725210080
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056695805428334; DSPS: 9865796; Offset: 1449056394725228139
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056700032, nextTick: 59976, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056700052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056715805876191; DSPS: 10521171; Offset: 1449056394725218233
,I/EventLogService( 1849): Aggregate from 1449056427519 (log), 1449054908584 (data)
,D/dalvikvm( 2604): GC_CONCURRENT freed 7894K, 33% free 16758K/24832K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 2604): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  959): updateLightListLocked :r=NotificationRecord(0x42b820f8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  959): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1536): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1536): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4238): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4238): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4238): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4238): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4238): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4238): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4238): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4238): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4238): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4238): isDataSchedulerEnabled():false
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056735807363788; DSPS: 11176580; Offset: 1449056394725210468
,D/dalvikvm( 2604): GC_FOR_ALLOC freed 1578K, 32% free 17028K/24832K, paused 21ms, total 23ms
,D/dalvikvm( 2604): GC_FOR_ALLOC freed 1487K, 31% free 17201K/24832K, paused 22ms, total 22ms
,D/dalvikvm( 2604): GC_FOR_ALLOC freed 1327K, 31% free 17365K/24832K, paused 19ms, total 19ms
,I/Mlt MonitorService( 2604): parseLastkmsg to dump
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056755808271437; DSPS: 11831969; Offset: 1449056394725233107
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056760050, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056760054, nextTick: 59978, mDrawingTime: 0,
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  959): GC_CONCURRENT freed 2335K, 48% free 30407K/57512K, paused 5ms+13ms, total 148ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056775809584867; DSPS: 12487372; Offset: 1449056394725234282,
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056795812689494; DSPS: 13142834; Offset: 1449056394725226116
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056815813996830; DSPS: 13798237; Offset: 1449056394725221196
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056820035, nextTick: 59976, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056820050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056835815317500; DSPS: 14453640; Offset: 1449056394725229610
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056855816699470; DSPS: 15109046; Offset: 1449056394725207771
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056875818639933; DSPS: 15764469; Offset: 1449056394725225627
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056880040, nextTick: 59981, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056880045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056895820130498; DSPS: 16419878; Offset: 1449056394725220831
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056915821467469; DSPS: 17075282; Offset: 1449056394725215028
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056935822795847; DSPS: 17730685; Offset: 1449056394725231150
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056940050, nextTick: 59968, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449056940059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056955824147402; DSPS: 18386090; Offset: 1449056394725209414
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056975825481196; DSPS: 19041493; Offset: 1449056394725230952
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449056995826821397; DSPS: 19696897; Offset: 1449056394725228380
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057000051, nextTick: 59971, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057000056, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057015828785765; DSPS: 20352322; Offset: 1449056394725209105
,I/ActivityManager(  959): Killing 2113:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057035830137268; DSPS: 21007726; Offset: 1449056394725217835
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057055831416478; DSPS: 21663128; Offset: 1449056394725215307
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057060035, nextTick: 59982, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057060044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057075832810637; DSPS: 22318533; Offset: 1449056394725236175
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057095834118911; DSPS: 22973936; Offset: 1449056394725232193
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057115834974372; DSPS: 23629324; Offset: 1449056394725233162
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057120043, nextTick: 59970, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057120055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057135836309781; DSPS: 24284728; Offset: 1449056394725225797
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  959): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  959): Done.
,D/QcConnectivityService(  959): Setting timer for 720seconds
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057155838500711; DSPS: 24940160; Offset: 1449056394725219461
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057175839779297; DSPS: 25595562; Offset: 1449056394725216309
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057180048, nextTick: 59963, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057180060, nextTick: 59971, mDrawingTime: 1
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  959): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  959): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  959): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057195841294185; DSPS: 26250971; Offset: 1449056394725235836
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057215842717771; DSPS: 26906378; Offset: 1449056394725225096
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057235844144378; DSPS: 27561785; Offset: 1449056394725217377
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057240039, nextTick: 59970, mDrawingTime: 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057240052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057255845504006; DSPS: 28217189; Offset: 1449056394725234231
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057275847637645; DSPS: 28872619; Offset: 1449056394725231640
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057295848986335; DSPS: 29528024; Offset: 1449056394725207039
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057300039, nextTick: 59984, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057300055, nextTick: 59973, mDrawingTime: 2
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057315850310963; DSPS: 30183427; Offset: 1449056394725219411
,I/GCM     ( 1849): Message from null null
,E/GCM     ( 1849): Dropping message from null
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1536): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  959): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057335851660642; DSPS: 30838831; Offset: 1449056394725226316
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057355852996832; DSPS: 31494235; Offset: 1449056394725219733
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057360059, nextTick: 59969, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057360060, nextTick: 59972, mDrawingTime: 1,
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057375854679794; DSPS: 32149650; Offset: 1449056394725224228
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057395856002650; DSPS: 32805053; Offset: 1449056394725234828
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057415857341081; DSPS: 33460457; Offset: 1449056394725230486
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057420056, nextTick: 59972, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057420059, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057435858770084; DSPS: 34115864; Offset: 1449056394725225163
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057455860088513; DSPS: 34771267; Offset: 1449056394725231336
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057475860937620; DSPS: 35426655; Offset: 1449056394725225951
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057480048, nextTick: 59964, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057480061, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057495862339279; DSPS: 36082061; Offset: 1449056394725223801
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057515863225677; DSPS: 36737450; Offset: 1449056394725225189
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057535864511451; DSPS: 37392852; Offset: 1449056394725229225
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057540050, nextTick: 59976, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057540060, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057555865961443; DSPS: 38048260; Offset: 1449056394725214373
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057575867909874; DSPS: 38703684; Offset: 1449056394725209679
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057595868775596; DSPS: 39359072; Offset: 1449056394725220909
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057600040, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057600045, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057615870140379; DSPS: 40014477; Offset: 1449056394725212401
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057635871760268; DSPS: 40669890; Offset: 1449056394725214858
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057655872594739; DSPS: 41325277; Offset: 1449056394725225355
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057660048, nextTick: 59966, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057660059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057675873944106; DSPS: 41980681; Offset: 1449056394725231948
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057695875272380; DSPS: 42636085; Offset: 1449056394725217449
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057715876802111; DSPS: 43291495; Offset: 1449056394725221301
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057720044, nextTick: 59972, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057720054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057735878992781; DSPS: 43946927; Offset: 1449056394725214705
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057755880432721; DSPS: 44602334; Offset: 1449056394725220319
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057775881763391; DSPS: 45257738; Offset: 1449056394725208216
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057780048, nextTick: 59962, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057780061, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057795883110415; DSPS: 45913142; Offset: 1449056394725212466
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057815884408219; DSPS: 46568544; Offset: 1449056394725228532
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057835885265451; DSPS: 47223932; Offset: 1449056394725231272
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057840043, nextTick: 59967, mDrawingTime: 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057840056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057855886641849; DSPS: 47879337; Offset: 1449056394725234379
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057875888111895; DSPS: 48534745; Offset: 1449056394725239581
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057895889030585; DSPS: 49190136; Offset: 1449056394725212226
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057900040, nextTick: 59959, mDrawingTime: 15
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057900059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057915890452452; DSPS: 49845542; Offset: 1449056394725230285
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057935891777184; DSPS: 50500946; Offset: 1449056394725212243
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057955892198791; DSPS: 51156319; Offset: 1449056394725237122
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057960041, nextTick: 59967, mDrawingTime: 13
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449057960054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057975893555034; DSPS: 51811724; Offset: 1449056394725220074
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449057995894964088; DSPS: 52467130; Offset: 1449056394725225319
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058015896228247; DSPS: 53122532; Offset: 1449056394725207740
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058020038, nextTick: 59974, mDrawingTime: 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058020056, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058035897572250; DSPS: 53777936; Offset: 1449056394725208969
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058055899028128; DSPS: 54433343; Offset: 1449056394725230521
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058075900304996; DSPS: 55088745; Offset: 1449056394725225651
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058080029, nextTick: 59996, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058080052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058095901631237; DSPS: 55744149; Offset: 1449056394725209118
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058115902536282; DSPS: 56399538; Offset: 1449056394725229154
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058135904161847; DSPS: 57054951; Offset: 1449056394725237287
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058140053, nextTick: 59968, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058140059, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058155905501631; DSPS: 57710355; Offset: 1449056394725234298
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2,
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058175906369384; DSPS: 58365744; Offset: 1449056394725217041
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058195908062710; DSPS: 59021159; Offset: 1449056394725231900
,W/ProcessCpuTracker(  959): Skipping unknown process pid 6356
,W/ProcessCpuTracker(  959): Skipping unknown process pid 6358
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058200040, nextTick: 59980, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058200049, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058215909419265; DSPS: 59676564; Offset: 1449056394725215164
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  959): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  959): Done.
,I/ProcessStatsService(  959): Prepared write state in 57ms
,D/QcConnectivityService(  959): Setting timer for 720seconds
,I/ProcessStatsService(  959): Pruning old procstats: /data/system/procstats/state-2015-12-01-12-20-01.bin
,D/LocationManagerService(  959): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1536): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  959): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058235910766914; DSPS: 60331968; Offset: 1449056394725220039
,I/ActivityManager(  959): Killing 3893:com.google.android.gms.unstable/u0a6 (adj 15): empty for 1801s
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058255911612895; DSPS: 60987356; Offset: 1449056394725211528
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
I/ActivityManager(  959): Killing 4359:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty for 1821s
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058260032, nextTick: 59970, mDrawingTime: 12
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058260059, nextTick: 59972, mDrawingTime: 1
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058275913021585; DSPS: 61642762; Offset: 1449056394725216410
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058295914552672; DSPS: 62298172; Offset: 1449056394725221618
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449058315915822872; DSPS: 62953574; Offset: 1449056394725210080
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
I/ActivityManager(  959): Killing 4203:com.android.contacts/u0a21 (adj 15): empty for 1809s
I/ActivityManager(  959): Killing 4570:com.lge.bnr/1000 (adj 15): empty for 1809s
I/ActivityManager(  959): Killing 4015:com.lge.appbox.client/u0a11 (adj 15): empty for 1809s
I/ActivityManager(  959): Killing 4541:com.google.android.partnersetup/u0a9 (adj 15): empty for 1809s
I/ActivityManager(  959): Killing 4502:com.android.defcontainer/u0a4 (adj 15): empty for 1809s
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058320021, nextTick: 59999, mDrawingTime: 8
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449058320060, nextTick: 59973, mDrawingTime: 0
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf1338 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,TIME-OUT KILL (timeout was 1800000ms)
```
