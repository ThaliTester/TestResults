#### Test 54312298239818e_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1964): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1964): launchTask
W/dalvikvm( 1964): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1964): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1964): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1964): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Ww8EDf4_tQxHzr4mr_7lCUiSA0IqGHRyBdfZhsY_DJO-_t0mNh92QlC9iO3eV8iivY59IAoLn2CqKrh1VgzGVJdv8JM5mTE7vEf8TbRYc9HT7n73MWhS83Qi0m5RVfG6WGzYSZel-zyejyuaZjcoZNcWoAAH_CiWlL_Y08yEcX4wujF9zXlVCYGPS1pE4LvnZB-A3h
D/ChimeraCfgMgr( 1964): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1964): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1964): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1964): No vision deps
I/GoogleURLConnFactory( 1964): Using platform SSLCertificateSocketFactory
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/PeopleContactsSync( 1964): CP2 sync disabled
W/BaseAppContext( 1964): Using Auth Proxy for data requests.
W/BaseAppContext( 1964): Using Auth Proxy for data requests.
W/GAV2    ( 4603): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/dalvikvm( 1964): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1964): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1964): VFY: replacing opcode 0x6e at 0x000e
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  964): Killing 3522:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c87db8 u0 com.android.settings/.UsbSettings t2}
W/BaseAppContext( 1964): Using Auth Proxy for data requests.
W/BaseAppContext( 1964): Using Auth Proxy for data requests.
W/BaseAppContext( 1964): Using Auth Proxy for data requests.
W/BaseAppContext( 1964): Using Auth Proxy for data requests.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1964): GC_CONCURRENT freed 1588K, 22% free 19487K/24832K, paused 3ms+6ms, total 54ms
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/dalvikvm( 1547): GC_EXPLICIT freed 899K, 29% free 17834K/24832K, paused 1ms+3ms, total 24ms
D/ChimeraCfgMgr( 1964): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1964): Module APK com.google.android.play.games already loaded
I/ConfigFetchService( 1964): fetch service done; releasing wakelock
I/ConfigFetchService( 1964): stopping self
D/AndroidRuntime( 4660): 
D/AndroidRuntime( 4660): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4660): CheckJNI is OFF
D/dalvikvm( 4660): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4660): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4660): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4660): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4660): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4660): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1964): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1964): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1964): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4660): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4660): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4660): Calling main entry com.android.commands.am.Am
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4660
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (122 us)
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{42c87db8 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  964): resumeTopActivityLocked: Pausing null
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  964): startService SlideAside
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  964): setFocusedStack: mFocusedStack=ActivityStack{43175308 stackId=1, 2 tasks}
D/UsbSettingsControl( 2583): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2583): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4660): Shutting down VM
I/SlideAside( 3674): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{42c87db8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{42c87db8 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Restarting ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4660): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 8ms
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4683 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3674): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3674): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4683): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4683): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4683): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
V/WebViewChromium( 4683): Binding Chromium to the background looper Looper (main, tid 1) {42834ce0}
I/chromium( 4683): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4683): Initializing chromium process, renderers=0
I/Adreno-EGL( 4683): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4683): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4683): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4683): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4683): Remote Branch: 
I/Adreno-EGL( 4683): Local Patches: 
I/Adreno-EGL( 4683): Reconstruct Branch: 
W/chromium( 4683): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/dalvikvm( 4683): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4683): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4683): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4683): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4683): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4683): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4683): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4683): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4683): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4683): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4683): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4683): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4683): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4683): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4683): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4683): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4683): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4683): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4683): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4683): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4683): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4683): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4683): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4683): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2017): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2017): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/OpenGLRenderer( 4683): Enabling debug mode 0
W/AwContents( 4683): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  964): IME STATUS OFF
W/AwContents( 4683): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +387ms
I/ActivityManager( 4683): Timeline: Activity_idle id: android.os.BinderProxy@428363c0 time:108741
D/JsMessageQueue( 4683): Set native->JS mode to OnlineEventsBridgeMode
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4683): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4283a8d8
D/dalvikvm( 4683): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4283a8d8
D/jxcore_app_log( 4683): JniHelper::setJavaVM(0x416ff838), pthread_self() = 1638967008
D/JX-Cordova( 4683): jxcore cordova android initializing
I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3} time:109118
D/ActivityManager(  964): no-history finish of ActivityRecord{42c87db8 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  964): Finishing activity token=Token{433e3a30 ActivityRecord{42c87db8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2583): [AUTORUN] onStop()
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{42c87db8 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{42c87db8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{42c87db8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/dalvikvm( 4683): GC_CONCURRENT freed 2790K, 12% free 21853K/24832K, paused 3ms+2ms, total 41ms
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 187K, 13% free 21822K/24832K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 23.576MB for 96598-byte allocation
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 177K, 13% free 21858K/24928K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 23.658MB for 144892-byte allocation
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 256K, 13% free 21903K/25072K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 23.770MB for 217334-byte allocation
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 369K, 14% free 21977K/25288K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 23.947MB for 325996-byte allocation
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 568K, 14% free 22099K/25608K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 24.221MB for 488990-byte allocation
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 867K, 15% free 22276K/26088K, paused 23ms, total 24ms
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 1284K, 14% free 22533K/26088K, paused 38ms, total 38ms
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 25.228MB for 1100216-byte allocation
,D/dalvikvm( 4683): GC_CONCURRENT freed 1809K, 16% free 22928K/27164K, paused 1ms+5ms, total 42ms
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 180K, 16% free 22917K/27164K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 26.126MB for 1650320-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4683): GC_CONCURRENT freed 1870K, 19% free 23486K/28776K, paused 1ms+8ms, total 46ms
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 1252K, 19% free 23501K/28776K, paused 37ms, total 37ms
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 27.484MB for 2475476-byte allocation
,D/dalvikvm( 4683): GC_CONCURRENT freed 389K, 18% free 25811K/31196K, paused 2ms+3ms, total 37ms
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 4215K, 22% free 24476K/31196K, paused 29ms, total 33ms
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 29.618MB for 3713210-byte allocation
,D/dalvikvm( 4683): GC_CONCURRENT freed 420K, 20% free 28031K/34824K, paused 2ms+4ms, total 41ms
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 3036K, 28% free 25421K/34824K, paused 38ms, total 39ms
,W/jxcore-log( 4683): Initializing JXcore engine
,W/jxcore-log( 4683): JXcore engine is ready
,D/dalvikvm( 4683): GC_CONCURRENT freed 340K, 20% free 28067K/34824K, paused 4ms+1ms, total 29ms
,D/dalvikvm( 4683): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4683): Starting JXcore engine
,W/jxcore-log( 4683): Platform android
W/jxcore-log( 4683): 
,W/jxcore-log( 4683): Process ARCH arm
W/jxcore-log( 4683): 
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/jxcore-log( 4683): JXcore Cordova bridge is ready!
I/jxcore-log( 4683): 
,W/jxcore-log( 4683): JXcore engine is started
,I/chromium( 4683): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4683): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4683): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2017): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2017): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1214): Disconnected process message: 10
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743060033, nextTick: 59998, mDrawingTime: 1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743060034, nextTick: 59999, mDrawingTime: 0
,I/jxcore-log( 4683): Toggling radios to true
I/jxcore-log( 4683): 
,D/BluetoothManagerService(  964): Message: 20
,D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44bd79b8:true
,D/BluetoothAdapter( 4683): enable(): BT is already enabled..!
,D/WifiStateMachine(  964): handleMessage: E msg.what=131145
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doBoolean: DISCONNECT
,I/jxcore-log( 4683): Radios toggled
I/jxcore-log( 4683): 
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  964): New client listening to asynchronous messages
D/WifiService(  964): setWifiEnabled: true pid=4683, uid=10304
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  964): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  964): disconnect pid=4683, uid=10304
D/WifiService(  964): reconnect pid=4683, uid=10304
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2017): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2017): wlan0: Cancelling scan request
D/wpa_supplicant( 2017): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2017): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2017): TDLS: Tear down peers
D/wpa_supplicant( 2017): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4683): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4683): 
I/GAV2    ( 4603): Thread[GAThread,5,main]: No campaign data found.
I/jxcore-log( 4683): Perf Test app loaded loaded
I/jxcore-log( 4683): 
I/Choreographer( 4683): Skipped 62 frames!  The application may be doing too much work on its main thread.
,D/wpa_supplicant( 2017): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2017): wlan0: Deauthentication notification
D/wpa_supplicant( 2017): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2017): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2017): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2017): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2017): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2017): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb892dd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2017):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2017): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2017): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2017): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2017): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2017): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2017): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2017): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2017): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2017): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2017): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2017): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2017): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2017): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2017): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2017): RTM_NEWLINK, IFLA_I,FNAME: Interface 'wlan0' added
D/wpa_supplicant( 2017): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2017): nl80211: Event message available
D/wpa_supplicant( 2017): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2017): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
W/Settings(  964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131146
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiNative-wlan0(  964): doBoolean: RECONNECT
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
I/jxcore-log( 4683): check test folder
I/jxcore-log( 4683): 
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2017): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2017): Fast associate: Old scan results
D/wpa_supplicant( 2017): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2017): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2017): wlan0: nl80211: scan request
D/wpa_supplicant( 2017): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147460
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/wpa_supplicant( 2017): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2017): nl80211: Event message available
D/wpa_supplicant( 2017): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2017): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection lost
D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
I/jxcore-log( 4683): found test : ./testFindPeers.js
I/jxcore-log( 4683): 
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2017): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2017): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2017): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2017): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2017): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
,D/DhcpStateMachine(  964): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
D/QCNEA   (  564): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  564): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  564): |CAC| updateNetCfgInfo
V/QCNEA   (  564): |CAC| *********************************************
V/QCNEA   (  564): |CAC|                   Netconfig               
V/QCNEA   (  564): |CAC| *********************************************
V/QCNEA   (  564): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  564): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  564): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  564): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  564): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  564): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  564): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  564): |CAC| *********************************************
D/QCNEA   (  564): |CAC| Received bssid= 
D/QCNEA   (  564): |CAC| net type = 3
V/QCNEA   (  564): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  564): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  564): |CAC| 	ssid           =NG700
V/QCNEA   (  564): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  564): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  564): |CAC| *********************************************
D/QCNEA   (  564): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  564): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  564): |CAC| dispatchNetCfg: updating:0xb77ea8dc
,D/QCNEA   (  564): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  564): Reading a NULL string not supported here.
,E/Parcel  (  564): Reading a NULL string not supported here.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 0
D/WifiHS20(  964): hidePasspointNotification off =false
,D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiStateMachine(  964): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
I/jxcore-log( 4683): found test : ./testSendData.js
I/jxcore-log( 4683): 
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4731 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  264): RouteController
V/        (  264): RouteController
D/HyLog   ( 4731): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4731): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4731): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
,V/        (  264): RouteController
,I/jxcore-log( 4683): found test : ./testSendData2.js
I/jxcore-log( 4683): 
,I/PCSuite ( 4731): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  264): RouteController
,V/        (  264): RouteController
D/PCSuite ( 4731): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4731): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,E/jxcore  ( 4683): Error!: missing ) after argument list
E/jxcore  ( 4683): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/chromium( 4683): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/        (  264): RouteController
,W/NetworkManagementService(  964): route cmd failed: 
W/NetworkManagementService(  964): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  964): '
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  964): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  964): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  964): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  964): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x6285c150 clazz=0x68d00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4766 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  964): Killing 3861:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,V/NativeCrypto( 1547): Read error: ssl=0x63907680: I/O error during system call, Connection timed out
,V/NativeCrypto( 1547): SSL shutdown failed: ssl=0x63907680: I/O error during system call, Broken pipe
,D/HyLog   ( 4766): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4766): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4766): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3}
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/QRemote ( 4766): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 4766): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4766): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4766): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4766): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4766): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4766): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 4766): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4766): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 2132:android.process.media/u0a23 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3}
D/DhcpStateMachine(  964): StoppedState
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1214): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  964): battery changed pluggedType: 2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1214): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/ConfigService( 1547): onDestroy
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.446762 Y: -0.396439 Z: 9.751389 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446762 .y:-0.396439 .z:9.751389
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.450577 Y: -0.410446 Z: 9.754684 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450577 .y:-0.410446 .z:9.754684
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1214): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1214): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4191): onReceive
,D/AppUp4:CustFacade( 4191): Context : android.app.ReceiverRestrictedContext@4284b170
D/AppUp4:CustFacade( 4191): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4191): isOpenOperator : true
,D/AppUp4:CustFacade( 4191): isPhone : true
,I/LicenseContentProvider( 4219): start selecting data
,D/SIMObserver( 4219): simInfo1
,I/AppUp4:EulaManager( 4191): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4191): begin check event
,I/AppUp4:CustModeStarterReceiver( 4191): Event For GoodConnectivity, noConnectivity : true, but skip! 
,I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4794 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/wpa_supplicant( 2017): nl80211: Event message available
D/wpa_supplicant( 2017): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2017): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2017): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2017): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 2017): nl80211: Survey data missing
D/wpa_supplicant( 2017): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2017): wlan0: BSS: Add new id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: BSS: Add new id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: BSS: Add new id 6 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600'
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: BSS: Add new id 7 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free'
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 2017): wlan0: New scan results available
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2017): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2017): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2017): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2017): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2017): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2017): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2017): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 2017): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2017): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2017): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2017): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2017): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2017): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-65 wps
D/wpa_supplicant( 2017): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2017): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
,D/wpa_supplicant( 2017): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2017): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2017): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2017): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2017): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2017): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2017): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb892f5a8  current_ssid=0x0
,D/wpa_supplicant( 2017): scard is not null..
D/wpa_supplicant( 2017): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2017): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2017): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2017): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2017): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2017): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2017): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2017): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2017): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2017): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2017): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00,
D/wpa_supplicant( 2017): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2017): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2017): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2017): wlan0: Cancelling scan request
D/wpa_supplicant( 2017): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2017): wlan0: WPA: clearing own WPA/RSN IE
,D/wpa_supplicant( 2017): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2017): RSN: PMKSA cache search - network_ctx=0xb892f5a8 try_opportunistic=0
D/wpa_supplicant( 2017): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): RSN: No PMKSA cache entry found
,D/wpa_supplicant( 2017): wlan0: RSN: using IEEE 802.11i/D9.0,
D/wpa_supplicant( 2017): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2017): wlan0: WPA: clearing AP WPA IE,
D/wpa_supplicant( 2017): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2017): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2017): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2017): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2017): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2017): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2017): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2017): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2017): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 2017): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2017): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2017): nl80211: Unsubscribe mgmt frames handle 0xb892e590 (mode change)
D/wpa_supplicant( 2017): nl80211: Subscribe to mgmt frames with non-AP handle 0xb892e590
,D/wpa_supplicant( 2017): nl80211: Register frame type=0xd0 nl_handle=0xb892e590
D/wpa_supplicant( 2017): nl80211: Register frame match - hexdump(len=2): 04 0a,
D/wpa_supplicant( 2017): nl80211: Register frame type=0xd0 nl_handle=0xb892e590
D/wpa_supplicant( 2017): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2017): nl80211: Register frame type=0xd0 nl_handle=0xb892e590
D/wpa_supplicant( 2017): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2017): nl80211: Register frame type=0xd0 nl_handle=0xb892e590
D/wpa_supplicant( 2017): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2017): nl80211: Register frame type=0xd0 nl_handle=0xb892e590
D/wpa_supplicant( 2017): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2017): nl80211: Register frame type=0xd0 nl_handle=0xb892e590
D/wpa_supplicant( 2017): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
,D/wpa_supplicant( 2017): nl80211: Register frame type=0xd0 nl_handle=0xb892e590
D/wpa_supplicant( 2017): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2017): nl80211: Register frame type=0xd0 nl_handle=0xb892e590
D/wpa_supplicant( 2017): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2017): nl80211: Register frame type=0xd0 nl_handle=0xb892e590
D/wpa_supplicant( 2017): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2017): nl80211: Register frame type=0xd0 nl_handle=0xb892e590
D/wpa_supplicant( 2017): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2017): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2017):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017):   * freq=2412
D/wpa_supplicant( 2017):   * SSID - hexdump(len=5): 4e 47 37 30 30
,D/wpa_supplicant( 2017):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2017):   * Auth Type 0
D/wpa_supplicant( 2017):   * WPA Versions 0x2
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 a0:c5:62:7a:49:97]
D/wpa_supplicant( 2017): nl80211: Connect request send successfully
D/wpa_supplicant( 2017): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2017): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2017): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2017): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2017): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2017): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2017): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 a0:c5:62:7a:49:96]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 fe:94:e3:11:35:3c]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2017): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/HyLog   ( 4794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4794): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2017): nl80211: Event message available
D/wpa_supplicant( 2017): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
,D/wpa_supplicant( 2017): nl80211: Connect event
D/wpa_supplicant( 2017): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2017): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2017): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2017): wlan0: Association info event
D/wpa_supplicant( 2017): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2017): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2017): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2017): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2017): wlan0: freq=2412 MHz
D/wpa_supplicant( 2017): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2017): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2017): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): wlan0: No keys have been configured - skip key clearing
,D/wpa_supplicant( 2017): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2017): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2017): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): scard is not null..
D/wpa_supplicant( 2017): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2017): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2017): TDLS: Remove peers on association
D/wpa_supplicant( 2017): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/wpa_supplicant( 2017): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2017): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2017): EAPOL: enable timer tick
W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): EAPOL: SUPP_BE entering state IDLE
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/wpa_supplicant( 2017): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2017): wlan0: Cancelling scan request
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/wpa_supplicant( 2017): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
D/wpa_supplicant( 2017): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2017): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/wpa_supplicant( 2017): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2017): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2017): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2017): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2017): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2017): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2017): nl80211: if_removed already cleared - ignore event
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2017): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c2 c9 72 41 05 48 32 c4 07 b7 50 d3 ed 8d b3 ...
D/wpa_supplicant( 2017): wlan0: Setting authentication timeout: 10 sec 0 usec
,D/wpa_supplicant( 2017): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2017): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2017): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2017): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2017):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2017):   key_nonce - hexdump(len=32): c2 c9 72 41 05 48 32 c4 07 b7 50 d3 ed 8d b3 99 94 25 5f 1c 12 0f 1b 31 03 fd eb a1 4e 8f bd 36
D/wpa_supplicant( 2017):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2017):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2017):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2017):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 2017): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c2 c9 72 41 05 48 32 c4 07 b7 50 d3 ed 8d b3 ...
D/wpa_supplicant( 2017): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2017): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2017): Get randomness: len=32 entropy=9
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2017): WPA: Renewed SNonce - hexdump(len=32): 84 ff 8d b4 93 8d 36 aa 38 34 f3 9c 40 0f 90 b5 8e a0 08 4c c7 75 7f 1e e0 41 a4 9e 7e b6 df a2
D/wpa_supplicant( 2017): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): WPA: Nonce1 - hexdump(len=32): 84 ff 8d b4 93 8d 36 aa 38 34 f3 9c 40 0f 90 b5 8e a0 08 4c c7 75 7f 1e e0 41 a4 9e 7e b6 df a2
,D/wpa_supplicant( 2017): WPA: Nonce2 - hexdump(len=32): c2 c9 72 41 05 48 32 c4 07 b7 50 d3 ed 8d b3 99 94 25 5f 1c 12 0f 1b 31 03 fd eb a1 4e 8f bd 36
D/wpa_supplicant( 2017): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2017): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2017): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2017): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2017): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2017): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2017): WPA: Derived Key MIC - hexdump(len=16): ba f1 78 81 7d 07 54 95 07 13 ff 4d 07 4f f4 a2
,D/wpa_supplicant( 2017): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 84 ff 8d b4 93 8d 36 aa 38 34 f3 9c 40 0f 90 ...
,D/wpa_supplicant( 2017): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c2 c9 72 41 05 48 32 c4 07 b7 50 d3 ed 8d b3 ...
D/wpa_supplicant( 2017): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2017): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2017): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2017): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2017):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2017):   key_nonce - hexdump(len=32): c2 c9 72 41 05 48 32 c4 07 b7 50 d3 ed 8d b3 99 94 25 5f 1c 12 0f 1b 31 03 fd eb a1 4e 8f bd 36
D/wpa_supplicant( 2017):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2017):   key_rsc - hexdump(len=8): a7 6e 00 00 00 00 00 00
D/wpa_supplicant( 2017):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2017):   key_mic - hexdump(len=16): 50 a5 55 41 ae 3a 3b 7c 18 14 e9 1a 6d 43 c7 f8
D/wpa_supplicant( 2017): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c2 c9 72 41 05 48 32 c4 07 b7 50 d3 ed 8d b3 ...
D/wpa_supplicant( 2017): RSN: encrypted key data - hexdump(len=56): 70 d6 a3 dd b8 6f f4 ea 97 62 bc b6 0b 2c c3 fd bd 52 9d 22 0a 9a c8 d4 4b 61 e8 00 7e 47 3b 95 ...
D/wpa_supplicant( 2017): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2017): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2017): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2017): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 81 f8 ...
D/wpa_supplicant( 2017): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2017): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2017): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2017): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2017): WPA: Derived Key MIC - hexdump(len=16): d3 27 7b 59 c4 fd ce 1e 10 a3 b5 d6 aa 53 76 2f
D/wpa_supplicant( 2017): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2017): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb892ec54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2017):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2017): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2017): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2017): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2017): WPA: RSC - hexdump(len=6): a7 6e 00 00 00 00
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6fb903a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2017):    broadcast key
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
I/wpa_supplicant( 2017): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2017): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2017): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2017): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2017): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2017): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2017): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2017): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2017): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2017): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2017): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2017): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2017): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2017): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2017): EAPOL authentication completed successfully
D/wpa_supplicant( 2017): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2017): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2017): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): Network connection established
,D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
,D/wpa_supplicant( 2017): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  964):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  964): ssid=NG700
D/WifiNative-wlan0(  964): id=0
D/WifiNative-wlan0(  964): mode=station
D/WifiNative-wlan0(  964): pairwise_cipher=CCMP
D/WifiNative-wlan0(  964): group_cipher=CCMP
D/WifiNative-wlan0(  964): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  964): wpa_state=COMPLETED
D/WifiNative-wlan0(  964): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  964): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
V/DownloadManager( 4794): DownloadService onCreate
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,I/DownloadManager( 4794): in removeSpuriousFiles
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
,E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
V/DownloadManager( 4794): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4586): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4586): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@42879c78 on behalf of 4794
,I/DownloadManager( 4794): in trimDatabase
,V/DownloadManager( 4794): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  964): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
,D/WifiStateMachine(  964): handleMessage: X
V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@4287b4e8 on behalf of 4794
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-21ms what=147462 obj=android.net.wifi.StateChangeResult@43d37540 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
,D/WifiStateMachine(  964): ObtainingIpState{ when=-16ms what=147462 obj=android.net.wifi.StateChangeResult@444a2698 target=com.android.internal.util.StateMachine$SmHandler }
D/eas_req ( 4586): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-16ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2017): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2017): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2017): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,V/DownloadManager( 4794): DownloadService onStartCommand
,V/DownloadManager( 4794): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4322): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4322): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4322): networkInfo.isConnected() = false
,V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@4287f410 on behalf of 4794
,W/linker  ( 4586): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4586): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4586): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4586): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4586): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4586): register_HtmlEditor, Success
,D/HtmlEditor( 4586): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4586): register_HtmlEditorTimer, Success
D/HtmlEditor( 4586): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4586): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4586): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4586): register_HtmlEditorFont, Success
D/HtmlEditor( 4586): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4586): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4586): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4586): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4586): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4586): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4586): JNI_OnLoad Success
,I/HubEmail( 4586): JNI_OnLoad()
I/HubEmail( 4586): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4586): registerNatives()
I/HubEmail( 4586): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4586): registerNativeMethods()
,I/HubEmail( 4586): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4586): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4794): DownloadService onDestroy
I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4837 uid=10052 gids={50052, 3003}
,I/ActivityManager(  964): Killing 4308:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/HyLog   ( 4837): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4837): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4837): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3}
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4837): [loadRssi] File not exist 
V/LGRssiData( 4837): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4837): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4837): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4837): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4837): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4837): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 4837): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4837): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 4837): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4837): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4837): [getValue] FEATURE key : vzw_roaming_state, value : null
E/PhoneMonitor( 4837): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4837): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4852 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 4142:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
,D/HyLog   ( 4852): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4852): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4852): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3}
,D/wpa_supplicant( 2017): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2017): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2017): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2017): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2017): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2017): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2017): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2017): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
,D/WifiStateMachine(  964): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4314d718 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4314d718 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2017): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2017): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2017): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2017): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2017): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): DHCP successful
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
,D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
,D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
E/Parcel  (  564): Reading a NULL string not supported here.
D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
,D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  564): Reading a NULL string not supported here.
,E/Parcel  (  564): Reading a NULL string not supported here.
D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
E/Parcel  (  564): Reading a NULL string not supported here.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4866 uid=10066 gids={50066, 4002, 3003, 1028}
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 1
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  964): Killing 4511:com.android.defcontainer/u0a4 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3}
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
,E/Parcel  (  564): Reading a NULL string not supported here.
,D/HyLog   ( 4866): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4866): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4866): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/        (  264): RouteController
,D/LGDMClient( 2828): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  964): Killing 4543:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/LGDMClient( 2828): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2828): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4884 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3}
E/LGDMClient( 2828): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
V/        (  264): RouteController
D/LGDMClient( 2828): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2828): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2828): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/        (  264): RouteController
V/        (  264): RouteController
D/HyLog   ( 4884): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4884): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4884): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
,D/LGDMSGCM( 4884): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
D/QCNEA   (  564): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  564): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  564): |CAC| updateNetCfgInfo
V/QCNEA   (  564): |CAC| *********************************************
V/QCNEA   (  564): |CAC|                   Netconfig               
V/QCNEA   (  564): |CAC| *********************************************
V/QCNEA   (  564): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  564): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  564): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  564): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  564): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  564): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  564): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  564): |CAC| *********************************************
D/QCNEA   (  564): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  564): |CAC| net type = 1
V/QCNEA   (  564): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  564): |CAC| Received ssid= NG700
V/QCNEA   (  564): |CAC| 	ssid           =NG700
V/QCNEA   (  564): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  564): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  564): |CAC| *********************************************
D/QCNEA   (  564): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  564): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  564): |CAC| dispatchNetCfg: updating:0xb77ea8dc
,D/QCNEA   (  564): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
W/ContextImpl( 4884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4907 uid=10101 gids={50101, 1028, 1015, 3003}
D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/ActivityManager(  964): Killing 4573:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3}
D/WifiController(  964): battery changed pluggedType: 2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1214): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 16ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DhcpStateMachine(  964): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  964): GC_EXPLICIT freed 23424K, 49% free 29750K/57548K, paused 4ms+8ms, total 132ms
,I/CheckinService( 1964): Checking schedule, now: 1450743063825 next: 1450743008167
,I/CheckinService( 1964): active receiver: enabled
,D/HyLog   ( 4907): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4907): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4907): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1964): Preparing to send checkin request
,I/EventLogService( 1964): Accumulating logs since 1450742975363
,I/NFS     ( 4907): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4907): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4907): intf.getDisplayName() = lo
I/Wireless_Storage( 4907): intf.getDisplayName() = sit0
I/Wireless_Storage( 4907): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4907): intf.getDisplayName() = teql0
I/Wireless_Storage( 4907): intf.getDisplayName() = wlan0
,D/NFS     ( 4907): interface name:wlan0 name:wlan0
D/NFS     ( 4907): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4907): interface name:wlan0 name:wlan0
D/NFS     ( 4907): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 4907): CONNECT : WIFI_CONNECT
,I/CheckinRequestBuilder( 1964): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4928 uid=10104 gids={50104, 3003, 1028, 1015}
I/ActivityManager(  964): Killing 4243:com.android.contacts/u0a21 (adj 15): empty #17
E/ActivityThread( 1964): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4928): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4928): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4928): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 4928): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1964): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x43265720: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4946 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4946): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4946): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4946): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4946): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4946): VFY: replacing opcode 0x60 at 0x000b
,V/WebViewChromium( 4928): Binding Chromium to the main looper Looper (main, tid 1) {428328d8}
D/dalvikvm( 4946): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4946): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4946): VFY: replacing opcode 0x62 at 0x005e
,I/chromium( 4928): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4928): Initializing chromium process, renderers=0
I/MultiDex( 4946): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4946): install
,I/MultiDex( 4946): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4946): loading existing secondary dex files
,I/MultiDex( 4946): load found 3 secondary dex files
,W/chromium( 4928): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/MultiDex( 4946): install done
,I/Adreno-EGL( 4928): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4928): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4928): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4928): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4928): Remote Branch: 
I/Adreno-EGL( 4928): Local Patches: 
I/Adreno-EGL( 4928): Reconstruct Branch: 
,D/dalvikvm( 4946): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 4946): VFY: unable to resolve instance field 61
,D/dalvikvm( 4946): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4946): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4946): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4946): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4946): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4946): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4946): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4946): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4946): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4946): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283a300
D/dalvikvm( 4946): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283a300
,D/dalvikvm( 4946): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283a300, skipping init
,D/dalvikvm( 4946): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283a300
D/dalvikvm( 4946): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283a300
,V/JNIHelp ( 4946): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 4928): Starting up...
,I/ActivityManager(  964): Killing 4265:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4766): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4766): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4766): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/dalvikvm( 4946): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283a300
,D/dalvikvm( 4946): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4283a300
D/dalvikvm( 4946): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283a300
,D/dalvikvm( 4946): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4283a300
,I/QRemote ( 4766): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4766): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4766): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4731): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/PCSuite ( 4731): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4766): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4766): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4766): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4766): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 4946): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1547): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1547): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1547): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1964): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1869): callingUid 10006, callindPid: 1869
,E/MDM     ( 1423): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1964): Restart initialization of location
,I/dalvikvm( 4946): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4946): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4946): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4946): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4946): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4946): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1eb6000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1eb6000
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
D/WVCdm   (  271): PrepareKeyRequest: nonce=1751376838
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/GCM     ( 1547): Connected
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1547): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 4946): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a291c8
D/dalvikvm( 4946): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a291c8
,D/dalvikvm( 4946): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a291c8, skipping init
,D/wpa_supplicant( 2017): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2017): EAPOL: disable timer tick
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=122626663
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1,
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4946): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState,
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
I/dalvikvm( 4683): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/dalvikvm( 4683): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4683): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4683): Shutting down VM
,W/dalvikvm( 4683): threadid=1: thread exiting with uncaught exception (group=0x417fae48)
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
E/AndroidRuntime( 4683): FATAL EXCEPTION: main
E/AndroidRuntime( 4683): Process: com.test.thalitest, PID: 4683
E/AndroidRuntime( 4683): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4683): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4683): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4683): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4683): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4683): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4683): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4683): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4683): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4683): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4683): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4683): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4683): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4683): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4683): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4683): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4683): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4683): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4683): 	at dalvik.system.NativeStart.main(Native Method)
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
W/ActivityManager(  964):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm( 4993): DexOpt: load 2ms, verify+opt 4ms, 128132 bytes
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4946): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4946): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 110ms
,I/Adreno-EGL( 4946): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4946): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4946): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4946): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4946): Remote Branch: 
I/Adreno-EGL( 4946): Local Patches: 
I/Adreno-EGL( 4946): Reconstruct Branch: 
,W/Settings( 4946): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4946): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4946): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4946): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4946): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4946): Remote Branch: 
I/Adreno-EGL( 4946): Local Patches: 
I/Adreno-EGL( 4946): Reconstruct Branch: 
,I/Adreno-EGL( 4946): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4946): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4946): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4946): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4946): Remote Branch: 
I/Adreno-EGL( 4946): Local Patches: 
I/Adreno-EGL( 4946): Reconstruct Branch: 
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,I/CheckinRequestBuilder( 1964): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1964): Sending checkin request (11458 bytes)
,D/dalvikvm( 1964): GC_CONCURRENT freed 1891K, 22% free 19545K/24832K, paused 3ms+2ms, total 29ms
,W/ActivityManager(  964): Activity pause timeout for ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43175308 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  964): moveHomeStack:
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c30288 stackId=0, 1 tasks}
,V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  964): resumeTopActivityLocked: Resumed ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c30288 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1484): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1484): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1484): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1484): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1484): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1855): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:11:5
,I/[LGHome]Launcher.Model( 1484): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/UpdateThreadPoolManager( 1855): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1855): 2 : quick cover state : opened : 0
,D/WeatherService( 1855): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1855): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1855): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1855): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1855): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1855): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:11:5
,D/WeatherService( 1855): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1855): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1855): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1855): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1855): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1855): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1855): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1855): 2 : This is isUpdating : false
D/WeatherService( 1855): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1855): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1855): 2 : Map key string is -2
,D/lim     ( 1855): 2 : time = 01:11
I/WeatherReflect( 1855): Model Name : LG-D802
D/WeatherTheme( 1855): 2 : Different view - status_min_formatted : 09 != 11
D/WeatherTheme( 1855): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
,D/WeatherTheme( 1855): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1855): 2 : Fixed theme : optimus
,D/WeatherTheme( 1855): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1855): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1855): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1855): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1855): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1214): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,I/[LGHome]Launcher.Model( 1484): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1484): GC_CONCURRENT freed 5557K, 9% free 61073K/66668K, paused 2ms+3ms, total 23ms
,D/dalvikvm( 1141): GC_CONCURRENT freed 4312K, 7% free 71020K/76148K, paused 3ms+4ms, total 36ms
,D/dalvikvm( 1141): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1484): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1484): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1484): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1484): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher.Model( 1484): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1484): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1484): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/[LGHome]LauncherAppWidgetHostView( 1484): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1484): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/ActivityManager( 1484): Timeline: Activity_idle id: android.os.BinderProxy@42837f10 time:118365
,D/UsbSettings( 2583): [AUTORUN] onDestroy() : getDefaultFunction =boot
,V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{42c87db8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/UsbSettings( 2583): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2583): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2583): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{42c87db8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c30288 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1}
,I/CheckinRequestBuilder( 1964): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1964): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1} time:118451
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1964): awaiting user notification for token
,I/CheckinRequestBuilder( 1964): Classify the device as Phone.
,I/CheckinTask( 1964): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1964): Checking schedule, now: 1450743066273 next: 1451320462271
,I/CheckinService( 1964): active receiver: disabled
,D/dalvikvm(  964): GC_CONCURRENT freed 2258K, 47% free 30815K/57548K, paused 3ms+5ms, total 94ms
D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 89ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 36ms
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x42c48668: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/GCM     ( 1547): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2017): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2017): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  564): Reading a NULL string not supported here.
,E/Parcel  (  564): Reading a NULL string not supported here.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4191): onReceive
,D/AppUp4:CustFacade( 4191): Context : android.app.ReceiverRestrictedContext@4284b170
D/AppUp4:CustFacade( 4191): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4191): isOpenOperator : true
,D/AppUp4:CustFacade( 4191): isPhone : true
,I/LicenseContentProvider( 4219): start selecting data
,D/SIMObserver( 4219): simInfo1
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/AppUp4:EulaManager( 4191): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4191): begin check event
I/AppUp4:CustModeStarterReceiver( 4191): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4191): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4191): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4191): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4191): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4191): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4794): DownloadService onCreate
,I/DownloadManager( 4794): in removeSpuriousFiles
D/EAS     ( 4586): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4794): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4586): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@428851e8 on behalf of 4794
,I/DownloadManager( 4794): in trimDatabase
,V/DownloadManager( 4794): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/eas_req ( 4586): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@42886be0 on behalf of 4794
,V/DownloadManager( 4794): DownloadService onStartCommand
,V/DownloadManager( 4794): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 4322): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4322): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@42888d90 on behalf of 4794
,I/LgeMiscReceiver( 4322): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4837): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4837): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4586): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4794): DownloadService onDestroy
,D/LGDMClient( 2828): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4884): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2828): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2828): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4907): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4907): CONNECT : WIFI_CONNECT
W/ContextImpl( 4884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,E/LGDMClient( 2828): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2828): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2828): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2828): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4191): onReceive
,D/AppUp4:CustFacade( 4191): Context : android.app.ReceiverRestrictedContext@4284b170
D/AppUp4:CustFacade( 4191): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4191): isOpenOperator : true
,D/AppUp4:CustFacade( 4191): isPhone : true
I/LicenseContentProvider( 4219): start selecting data
,D/SIMObserver( 4219): simInfo1
,I/AppUp4:EulaManager( 4191): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4191): begin check event
,I/AppUp4:CustModeStarterReceiver( 4191): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4794): DownloadService onCreate
D/EAS     ( 4586): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4586): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4794): in removeSpuriousFiles
,V/DownloadManager( 4794): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@4288d580 on behalf of 4794
,V/DownloadManager( 4794): DownloadService onStartCommand
I/DownloadManager( 4794): in trimDatabase
,V/DownloadManager( 4794): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4794): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@42890698 on behalf of 4794
I/LgeMiscReceiver( 4322): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4322): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4322): networkInfo.isConnected() = true
,D/PhoneState( 4322): setPdpRejectCasuse : false
V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@42890480 on behalf of 4794
,W/Settings( 4586): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4837): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4837): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4794): DownloadService onDestroy
,D/LGDMClient( 2828): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2828): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4884): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2828): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4907): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4907): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2828): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2828): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,W/ContextImpl( 4884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2828): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2828): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/HeadsetStateMachine( 1214): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1484): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1484): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1484): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1484): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4191): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4191): onReceive
,D/AppUp4:CustFacade( 4191): Context : android.app.ReceiverRestrictedContext@4284b170
D/AppUp4:CustFacade( 4191): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4191): isOpenOperator : true
,D/AppUp4:CustFacade( 4191): isPhone : true
,I/LicenseContentProvider( 4219): start selecting data
,D/SIMObserver( 4219): simInfo1
,I/AppUp4:EulaManager( 4191): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4191): begin check event
,I/AppUp4:CustModeStarterReceiver( 4191): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4586): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4794): DownloadService onCreate
,D/EAS     ( 4586): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4322): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4322): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4322): networkInfo.isConnected() = true
,D/PhoneState( 4322): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4837): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4837): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2828): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4884): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4907): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4907): CONNECT : WIFI_CONNECT
,I/DownloadManager( 4794): in removeSpuriousFiles
,V/DownloadManager( 4794): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 4586): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGDMClient( 2828): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@42894cc8 on behalf of 4794
I/LGDMClient( 2828): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 4794): in trimDatabase
V/DownloadManager( 4794): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4794): DownloadService onStartCommand
V/DownloadManager( 4794): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@42896b38 on behalf of 4794
V/DownloadManager( 4794): created cursor android.database.sqlite.SQLiteCursor@42898808 on behalf of 4794
E/LGDMClient( 2828): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2828): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
V/DownloadManager( 4794): DownloadService onDestroy
D/LGDMClient( 2828): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2828): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/GAV2    ( 4928): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  964): Killing 4603:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c30288 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2017): wlan0: Control interface command 'SIGNAL_POLL'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 2017): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4119): [393] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4119): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  964): Killing 4731:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c30288 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1}
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2017): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2017): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1484): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1484): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1484): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3674): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3674): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  964): Handling package changes for user 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.471191 Y: -0.407166 Z: 9.762787 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471191 .y:-0.407166 .z:9.762787
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5171 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.466202 Y: -0.418427 Z: 9.774368 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466202 .y:-0.418427 .z:9.774368
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  964):   Scheme: "mmsto"
,D/dalvikvm( 1484): GC_FOR_ALLOC freed 7037K, 11% free 61843K/69388K, paused 80ms, total 80ms
,D/HyLog   ( 5171): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5171): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5171): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1214): Disconnected process message: 10
,I/Babel   ( 5171): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5171): MmsConfig.loadMmsSettings
I/Babel   ( 5171): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5171): MmsConfig.loadFromDatabase
I/MediaCodecList( 5171): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5171): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5171): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5171): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/[LGHome]EVENT( 1484): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5171): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5171): MmsConfig.loadFromResources
,E/Babel   ( 5171): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5171): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1423): DISABLE
,I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 5171): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5171): [loadRssi] File not exist 
V/LGRssiData( 5171): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5171): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5171): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5171): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5171): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:Utils( 4191): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4191): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4191): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4191): onReceive
,D/AppUp4:CustFacade( 4191): Context : android.app.ReceiverRestrictedContext@4284b170
D/AppUp4:CustFacade( 4191): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4191): isOpenOperator : true
,D/AppUp4:CustFacade( 4191): isPhone : true
,I/LicenseContentProvider( 4219): start selecting data
,D/SIMObserver( 4219): simInfo1
,D/LocationProviderProxy(  964): applying state to connected service
,I/AppUp4:EulaManager( 4191): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4191): begin check event
D/AppUp4:Utils( 4191): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4191): Event For Nothing, skip.
,D/LocationProviderProxy(  964): applying state to connected service
I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5221 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5221): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5221): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5221): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5221): BUILD Country: EU
,I/SystemConfig( 5221): BUILD Operator: OPEN
I/SystemConfig( 5221): systemFeature RCS result false
,D/SystemConfig( 5221): refreshRcsSupport() :false
I/ActivityManager(  964): Killing 4766:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5235 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c30288 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  964): Killing 4683:com.test.thalitest/u0a304 (adj 15): empty #17
D/HyLog   ( 5235): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5235): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5235): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/WindowState(  964): WIN DEATH: Window{44e0d0d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  964): Client connection lost with reason: 4
,V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{43dab4a8 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
,I/[LGHome]EVENT( 1484): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c30288 stackId=0, 1 tasks}
,W/Binder  ( 1311): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1311): java.lang.NullPointerException
W/Binder  ( 1311): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1311): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1311): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1311): 	at dalvik.system.NativeStart.run(Native Method)
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1}
I/InputMethodManagerService(  964): IME STATUS OFF
W/InputMethodManagerService(  964): Got RemoteException sending setActive(false) notification to pid 4683 uid 10304
,I/IcingCorporaProvider( 2651): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  964): Killing 4794:android.process.media/u0a23 (adj 15): empty #17
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c30288 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/PackageBroadcastService( 1964): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1964): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  964): Delaying start of: ServiceRecord{433dc738 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1964): updateResources: need to parse f{com.google.android.gms}
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2651): UpdateCorporaTask done [took 231 ms] updated apps [took 231 ms] 
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2017): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2017): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2017): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2017): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/GAV4    ( 5171): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2017): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2017): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2017): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2017): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/PowerManagerService(  964): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  964): [updateScreenState] screen on = false
,D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  964): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 7600 usec
D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  964): hal_acquire_resources
,I/qcom_sensors_hal(  964): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  964): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  964): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  964): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  964): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  964): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  964): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  964): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.465652 Y: -0.401031 Z: 9.770432 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465652 .y:-0.401031 .z:9.770432
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.456009 Y: -0.382492 Z: 9.763657 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456009 .y:-0.382492 .z:9.763657
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Sensors (  540): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  964): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  964): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  964): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  964): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  964): proximitySensorChanged  positive = true
I/KnockOnPowerController(  964): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.467773 Y: -0.386047 Z: 9.774063 
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.463333 Y: -0.397141 Z: 9.759628 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.467773 .y:-0.386047 .z:9.774063
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.462051 Y: -0.419769 Z: 9.775696 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462051 .y:-0.419769 .z:9.775696
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.450333 Y: -0.402573 Z: 9.791550 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450333 .y:-0.402573 .z:9.791550
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.463379 Y: -0.399460 Z: 9.771057 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463379 .y:-0.399460 .z:9.771057
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  964): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43d5b5c8)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1141): notifyScreenOnLocked
D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
V/KeyguardServiceDelegate(  964): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
I/WindowManager(  964): No lock screen! windowToken=null
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb74ee450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.455612 Y: -0.387421 Z: 9.760101 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455612 .y:-0.387421 .z:9.760101
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/WifiStateMachine(  964): handleScreenStateChanged: true
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2017): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  964): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2017): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131127
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=132097
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  964): set CMD_KT_SCAN_INTERVAL
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2017): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2017): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiOffDelayIfNotUsed(  964): stopMonitoring
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
,V/SRS_Proc(  271): ParamSet string: screen_state=on
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4334cec0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3674): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WeatherAncestor( 1855): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:11:26
,I/SlideAside( 3674): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1855): 2 : This is isUpdating : false
,D/WeatherAncestor( 1855): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:11:26
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/WeatherService( 1855): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1855): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1855): 2 : TimeTick Receiver Unregister
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1855): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
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
,D/SurfaceControl(  964): Excessive delay in blankDisplay() while turning screen off: 411ms
D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/WifiController(  964): battery changed pluggedType: 2
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743086414, nextTick: 33619, mDrawingTime: 0
D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743086438, nextTick: 33595, mDrawingTime: 0
D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
D/WeatherService( 1855): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:11:26
D/WeatherService( 1855): 2 : ACTION screen on
,D/WeatherService( 1855): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1855): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:11:26
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
,E/Parcel  (  564): Reading a NULL string not supported here.
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
,I/[LGHome]EVENT( 1484): [Launcher.java:894:onPause()]onPause
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1}
,D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
D/qcom_sensors_hal(  964): hal_acquire_resources
D/qcom_sensors_hal(  964): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  964): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  964): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  964): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,I/[LGHome]EVENT( 1484): [Launcher.java:4955:onStop()]onStop
D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,I/LGImmersionVibrator(  964): Vibrator off
D/WifiStateMachine(  964): handleScreenStateChanged: false
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
,D/WifiStateMachine(  964): processMsg: DriverStartedState
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{4315a778 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1155): clear
D/wpa_supplicant( 2017): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2017): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
,I/[LGHome]EVENT( 1484): [Launcher.java:1567:onReceive()]Screen Off
,D/wpa_supplicant( 2017): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1855): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:11:26
D/WeatherService( 1855): 2 : ACTION screen off
D/WeatherService( 1855): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:11:26
D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
E/Parcel  (  564): Reading a NULL string not supported here.
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/NfcService( 1473): NFC-C OFF
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
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
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  540): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743094406200992; DSPS: 4946535; Offset: 1450742943449932682
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1547): Vacuum at: now=1450743094834 tag=VacuumService
,I/GoogleURLConnFactory( 1547): Using platform SSLCertificateSocketFactory
,D/dalvikvm(  964): GC_EXPLICIT freed 2923K, 47% free 30712K/57536K, paused 3ms+11ms, total 132ms
,I/GoogleURLConnFactory( 1547): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1547): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1547): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1547): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1547): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1547): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1547): GC_CONCURRENT freed 1768K, 28% free 18067K/24832K, paused 4ms+10ms, total 62ms
,W/Uploader( 1547): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Uploader( 1547): No account for auth token provided
,W/Uploader( 1547):  no longer exists, so no auth token.
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743114407551947; DSPS: 5601939; Offset: 1450742943449940864
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743120044, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743120055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743134408451374; DSPS: 6257328; Offset: 1450742943449955281
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743154409378077; DSPS: 6912719; Offset: 1450742943449935939
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743174409798027; DSPS: 7568092; Offset: 1450742943449959160
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743180031, nextTick: 59977, mDrawingTime: 10
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743180057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743194410253440; DSPS: 8223467; Offset: 1450742943449956810
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743214410699075; DSPS: 8878842; Offset: 1450742943449944681
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743234412025477; DSPS: 9534245; Offset: 1450742943449958827
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743240035, nextTick: 59986, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743240054, nextTick: 59978, mDrawingTime: 0
,D/wpa_supplicant( 2017): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: BSS: Remove id 2 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: BSS: Remove id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: BSS: Remove id 6 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: BSS: Remove id 7 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2017): wlan0: BSS: Remove id 3 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2017): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:97]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 a0:c5:62:7a:49:96]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 fe:94:e3:11:35:3c]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81]
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743254413524401; DSPS: 10189654; Offset: 1450742943449962390
,D/dalvikvm( 2638): GC_CONCURRENT freed 7759K, 32% free 16894K/24832K, paused 3ms+2ms, total 41ms
,D/dalvikvm( 2638): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743274413973139; DSPS: 10845029; Offset: 1450742943449953364
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x432153b0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1547): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1547): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1547): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1547): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1547): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1547): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4119): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4119): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4119): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4119): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4119): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4119): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4119): 	,at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4119): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4119): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4119): isDataSchedulerEnabled():false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/LocationManagerService(  964): remove 428544d8
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2638): GC_CONCURRENT freed 1873K, 32% free 17062K/24832K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 2638): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2638): GC_CONCURRENT freed 1747K, 31% free 17273K/24832K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 2638): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/Mlt MonitorService( 2638): parseLastkmsg to dump
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743294414925391; DSPS: 11500420; Offset: 1450742943449959571
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743300038, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743300052, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743314416318608; DSPS: 12155826; Offset: 1450742943449948980
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743334416744128; DSPS: 12811200; Offset: 1450742943449947253
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743354417199664; DSPS: 13466575; Offset: 1450742943449945026
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743360049, nextTick: 59979, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743360052, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743374419250838; DSPS: 14122002; Offset: 1450742943449951522
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743394420113960; DSPS: 14777390; Offset: 1450742943449960152
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743414420555612; DSPS: 15432765; Offset: 1450742943449944040
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743420034, nextTick: 59995, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743420038, nextTick: 59993, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743434425019615; DSPS: 16088271; Offset: 1450742943449952477
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743454425868356; DSPS: 16743659; Offset: 1450742943449946726
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743474426330387; DSPS: 17399034; Offset: 1450742943449950993
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743480034, nextTick: 59985, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743480044, nextTick: 59986, mDrawingTime: 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743494426794782; DSPS: 18054409; Offset: 1450742943449957624
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743514427684326; DSPS: 18709798; Offset: 1450742943449962159
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743534429023238; DSPS: 19365202; Offset: 1450742943449958297
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743540031, nextTick: 59974, mDrawingTime: 11
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743540049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743554430429741; DSPS: 20020608; Offset: 1450742943449960991
,I/ActivityManager(  964): Killing 4586:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c30288 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743574431373681; DSPS: 20675999; Offset: 1450742943449958887
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743594431824826; DSPS: 21331374; Offset: 1450742943449952268
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743600023, nextTick: 60002, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743600058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743614432737253; DSPS: 21986764; Offset: 1450742943449949168
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743634433635427; DSPS: 22642153; Offset: 1450742943449962332
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743654434533270; DSPS: 23297543; Offset: 1450742943449944647
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743660031, nextTick: 59996, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743660055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743674435449012; DSPS: 23952933; Offset: 1450742943449944862
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743694436790570; DSPS: 24608337; Offset: 1450742943449943647
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743714437715945; DSPS: 25263727; Offset: 1450742943449953494
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743720045, nextTick: 59970, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743720056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743734439077714; DSPS: 25919132; Offset: 1450742943449941972
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743754439530112; DSPS: 26574506; Offset: 1450742943449967124
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743774440447868; DSPS: 27229897; Offset: 1450742943449938835
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743780048, nextTick: 59971, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743780056, nextTick: 59977, mDrawingTime: 0,
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743794441847033; DSPS: 27885303; Offset: 1450742943449934192
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743814442730125; DSPS: 28540691; Offset: 1450742943449962792
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743834443200723; DSPS: 29196067; Offset: 1450742943449945108
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743840034, nextTick: 59982, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743840045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743854444682586; DSPS: 29851475; Offset: 1450742943449962128
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743874445558934; DSPS: 30506864; Offset: 1450742943449953466
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  964): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  964): Done.
,D/QcConnectivityService(  964): Setting timer for 720seconds
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743894446919280; DSPS: 31162269; Offset: 1450742943449940521
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743900040, nextTick: 59985, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743900055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743914448014450; DSPS: 31817664; Offset: 1450742943449967575
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743934449348500; DSPS: 32473069; Offset: 1450742943449928334
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743954450231030; DSPS: 33128457; Offset: 1450742943449956372
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743960043, nextTick: 59968, mDrawingTime: 9
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450743960056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743974451140767; DSPS: 33783847; Offset: 1450742943449950582
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450743994452078352; DSPS: 34439238; Offset: 1450742943449942122
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744014453750164; DSPS: 35094652; Offset: 1450742943449965985
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744020057, nextTick: 59972, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744020057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744034455138097; DSPS: 35750058; Offset: 1450742943449950109
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744054456017560; DSPS: 36405447; Offset: 1450742943449944562
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744074457363859; DSPS: 37060851; Offset: 1450742943449948088
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744080045, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744080054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744094458752413; DSPS: 37716256; Offset: 1450742943449963351
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744114459617278; DSPS: 38371645; Offset: 1450742943449943206
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744134460566971; DSPS: 39027036; Offset: 1450742943449946854
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744140027, nextTick: 60002, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744140046, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744154462127054; DSPS: 39682447; Offset: 1450742943449950541
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744174463808634; DSPS: 40337862; Offset: 1450742943449953654
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744194465193975; DSPS: 40993267; Offset: 1450742943449965704
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744200040, nextTick: 59978, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744200050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744214466431068; DSPS: 41648668; Offset: 1450742943449951576
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744234467314925; DSPS: 42304057; Offset: 1450742943449950424
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744254468193759; DSPS: 42959446; Offset: 1450742943449944248
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744260048, nextTick: 59969, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744260057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744274469118676; DSPS: 43614836; Offset: 1450742943449953637
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744294470470333; DSPS: 44270241; Offset: 1450742943449932003
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744314471351595; DSPS: 44925629; Offset: 1450742943449958773
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744320046, nextTick: 59969, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744320056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744334472312848; DSPS: 45581021; Offset: 1450742943449943464
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744354473853806; DSPS: 46236431; Offset: 1450742943449958543
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744374474743644; DSPS: 46891821; Offset: 1450742943449932853
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744380041, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744380045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744394476104424; DSPS: 47547225; Offset: 1450742943449950860
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744414477027011; DSPS: 48202615; Offset: 1450742943449957920
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744434478366655; DSPS: 48858019; Offset: 1450742943449954790
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744440040, nextTick: 59965, mDrawingTime: 11
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744440058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744454479750191; DSPS: 49513424; Offset: 1450742943449965035
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744474480651305; DSPS: 50168814; Offset: 1450742943449950622
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744494481111494; DSPS: 50824189; Offset: 1450742943449953047
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744500034, nextTick: 59974, mDrawingTime: 12
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744500048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744514482517319; DSPS: 51479595; Offset: 1450742943449955064
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744534483969108; DSPS: 52135003; Offset: 1450742943449942009
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744554484878527; DSPS: 52790393; Offset: 1450742943449935901
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744560032, nextTick: 59992, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744560057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744574486228329; DSPS: 53445797; Offset: 1450742943449942929
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744594487109103; DSPS: 54101186; Offset: 1450742943449938693
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  964): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  964): Done.
,D/QcConnectivityService(  964): Setting timer for 720seconds
,I/EventLogService( 1964): Aggregate from 1450743063854 (log), 1450742571303 (data)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1547): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744614488090962; DSPS: 54756578; Offset: 1450742943449943990
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744620035, nextTick: 59987, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744620040, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744634488991830; DSPS: 55411967; Offset: 1450742943449959848
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744654490325737; DSPS: 56067371; Offset: 1450742943449950982
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744674491661177; DSPS: 56722775; Offset: 1450742943449943648
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744680052, nextTick: 59974, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744680055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744694493679731; DSPS: 57378201; Offset: 1450742943449948042
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744714494567264; DSPS: 58033590; Offset: 1450742943449950565
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744734495921968; DSPS: 58688994; Offset: 1450742943449962496
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744740044, nextTick: 59984, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744740047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744754497323280; DSPS: 59344401; Offset: 1450742943449929482
,I/ProcessStatsService(  964): Prepared write state in 22ms
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,I/ProcessStatsService(  964): Pruning old procstats: /data/system/procstats/state-2015-12-21-05-07-00.bin
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744774498695558; DSPS: 59999805; Offset: 1450742943449958986
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744794500030520; DSPS: 60655209; Offset: 1450742943449951175
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744800031, nextTick: 59999, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744800032, nextTick: 59999, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744814501425397; DSPS: 61310615; Offset: 1450742943449942243
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744834502361850; DSPS: 61966006; Offset: 1450742943449932651
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450744854503830392; DSPS: 62621414; Offset: 1450742943449936350
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744860047, nextTick: 59972, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450744860056, nextTick: 59977, mDrawingTime: 0
,TIME-OUT KILL (timeout was 1800000ms)
```
