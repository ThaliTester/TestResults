#### Test 50650278d76d9c3_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1963): launchTask
W/dalvikvm( 1963): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1963): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1963): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1963): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1963): No vision deps
V/ConfigFetchTask( 1963): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1U3wG54Py9a8AR8aBRdKH4j9OfCag4SXZmVm6Re1UpLXrBicaOPSaeAOJ5_qo-SQmJISbvZbHb4FH2Z-DI0QqlxagDDNSW7Uzq9iUJcSx2TJJ5Jo7P1a07v2DsTxkS_z7JsT92FFHcd8QL5q4yLeDrLDdh1jLgr_RriuIKJStz9yEFk3zYlVf3lJUGhXw695M5d7Jci
I/GoogleURLConnFactory( 1963): Using platform SSLCertificateSocketFactory
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/PeopleContactsSync( 1963): CP2 sync disabled
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
I/dalvikvm( 1963): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1963): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1963): VFY: replacing opcode 0x6e at 0x000e
D/dalvikvm( 1963): GC_EXPLICIT freed 511K, 23% free 19144K/24832K, paused 1ms+4ms, total 35ms
,W/BaseAppContext( 1963): Using Auth Proxy for data requests.
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/GAV2    ( 4592): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiController(  955): battery changed pluggedType: 2
I/ActivityManager(  955): Killing 4026:com.google.android.gm/u0a68 (adj 15): empty #17
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 1 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ff4050 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1534): GC_EXPLICIT freed 1029K, 29% free 17821K/24832K, paused 1ms+3ms, total 23ms
I/ConfigFetchService( 1963): fetch service done; releasing wakelock
I/ConfigFetchService( 1963): stopping self
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1963): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4631): 
D/AndroidRuntime( 4631): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4631): CheckJNI is OFF
D/dalvikvm( 4631): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4631): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4631): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4631): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4631): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4631): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4631): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4631): failed to load memtrack module: -2
I/Icing   ( 1963): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4631): Calling main entry com.android.commands.am.Am
D/Icing   ( 1963): Loaded CLD2 Version V2.0 - 20141016
I/ActivityManager(  955): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4631
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 2 tasks}
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (105 us)
V/ActivityManager(  955): Moving to PAUSING: ActivityRecord{42ff4050 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  955): resumeTopActivityLocked: Pausing null
V/ActivityManager(  955): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  955): setFocusedStack: mFocusedStack=ActivityStack{4323c2d8 stackId=1, 2 tasks}
I/ActivityManager(  955): startService SlideAside
W/ContextImpl(  955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  955): allPausedActivitiesComplete: r=ActivityRecord{42ff4050 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/UsbSettingsControl( 2581): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2581): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4631): Shutting down VM
I/SlideAside( 3731): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4631): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 2ms
V/ActivityManager(  955): Moving to PAUSED: ActivityRecord{42ff4050 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 2 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Restarting ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  955): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4652 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3731): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3731): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  955): Moving to RESUMED: ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4652): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4652): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4652): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Icing   ( 1963): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
V/WebViewChromium( 4652): Binding Chromium to the background looper Looper (main, tid 1) {427fa8a8}
I/chromium( 4652): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4652): Initializing chromium process, renderers=0
W/chromium( 4652): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4652): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4652): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4652): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4652): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4652): Remote Branch: 
I/Adreno-EGL( 4652): Local Patches: 
I/Adreno-EGL( 4652): Reconstruct Branch: 
I/dalvikvm( 4652): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4652): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4652): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4652): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4652): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4652): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4652): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4652): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4652): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4652): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4652): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4652): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4652): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4652): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4652): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4652): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4652): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4652): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4652): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4652): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4652): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4652): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4652): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4652): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/OpenGLRenderer( 4652): Enabling debug mode 0
,W/AwContents( 4652): nativeOnDraw failed; clearing to background color.
,W/AwContents( 4652): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  955): IME STATUS OFF
,I/ActivityManager( 4652): Timeline: Activity_idle id: android.os.BinderProxy@427fbf88 time:107717
,I/ActivityManager(  955): Displayed com.test.thalitest/.MainActivity: +466ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/JsMessageQueue( 4652): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4652): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428008e0
,D/dalvikvm( 4652): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428008e0
,D/jxcore_app_log( 4652): JniHelper::setJavaVM(0x416c6838), pthread_self() = 1638719704
,D/JX-Cordova( 4652): jxcore cordova android initializing
,I/ActivityManager(  955): Timeline: Activity_windows_visible id: ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3} time:108002
D/UsbSettings( 2581): [AUTORUN] onStop()
D/ActivityManager(  955): no-history finish of ActivityRecord{42ff4050 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  955): Finishing activity token=Token{42a1a478 ActivityRecord{42ff4050 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  955): Moving to FINISHING: ActivityRecord{42ff4050 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  955): Moving to STOPPING: ActivityRecord{42ff4050 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  955): Moving to STOPPED: ActivityRecord{42ff4050 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/dalvikvm( 4652): GC_CONCURRENT freed 2794K, 12% free 21854K/24832K, paused 2ms+1ms, total 37ms
D/dalvikvm( 4652): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/dalvikvm( 4652): GC_FOR_ALLOC freed 156K, 13% free 21843K/24832K, paused 24ms, total 24ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 23.597MB for 96598-byte allocation
D/dalvikvm( 4652): GC_FOR_ALLOC freed 190K, 13% free 21867K/24928K, paused 23ms, total 23ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 23.666MB for 144892-byte allocation
D/dalvikvm( 4652): GC_FOR_ALLOC freed 265K, 13% free 21902K/25072K, paused 21ms, total 22ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 23.769MB for 217334-byte allocation
D/dalvikvm( 4652): GC_FOR_ALLOC freed 369K, 14% free 21976K/25288K, paused 23ms, total 23ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 23.946MB for 325996-byte allocation
D/dalvikvm( 4652): GC_FOR_ALLOC freed 568K, 14% free 22098K/25608K, paused 22ms, total 23ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 24.220MB for 488990-byte allocation
D/dalvikvm( 4652): GC_FOR_ALLOC freed 866K, 15% free 22275K/26088K, paused 22ms, total 23ms
D/dalvikvm( 4652): GC_FOR_ALLOC freed 1284K, 14% free 22532K/26088K, paused 23ms, total 24ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 25.227MB for 1100216-byte allocation
,D/dalvikvm( 4652): GC_CONCURRENT freed 1757K, 16% free 22915K/27164K, paused 2ms+3ms, total 30ms
,D/dalvikvm( 4652): GC_FOR_ALLOC freed 295K, 16% free 22851K/27164K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4652): Grow heap (frag case) to 26.063MB for 1650320-byte allocation
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4652): GC_CONCURRENT freed 1639K, 19% free 23428K/28776K, paused 2ms+3ms, total 36ms
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
,D/dalvikvm( 4652): GC_FOR_ALLOC freed 1400K, 19% free 23518K/28776K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4652): Grow heap (frag case) to 27.500MB for 2475476-byte allocation
,D/dalvikvm( 4652): GC_CONCURRENT freed 320K, 18% free 25856K/31196K, paused 2ms+2ms, total 35ms
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 4652): GC_FOR_ALLOC freed 4297K, 22% free 24479K/31196K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4652): Grow heap (frag case) to 29.621MB for 3713210-byte allocation
,D/dalvikvm( 4652): GC_CONCURRENT freed 456K, 20% free 27948K/34824K, paused 2ms+2ms, total 43ms
,D/dalvikvm( 4652): GC_FOR_ALLOC freed 2986K, 27% free 25436K/34824K, paused 23ms, total 23ms
,W/jxcore-log( 4652): Initializing JXcore engine
,W/jxcore-log( 4652): JXcore engine is ready
,D/dalvikvm( 4652): GC_CONCURRENT freed 319K, 20% free 28103K/34824K, paused 3ms+3ms, total 44ms
,D/dalvikvm( 4652): WAIT_FOR_CONCURRENT_GC blocked 39ms
,W/jxcore-log( 4652): Starting JXcore engine
,W/jxcore-log( 4652): Platform android
W/jxcore-log( 4652): 
,W/jxcore-log( 4652): Process ARCH arm
W/jxcore-log( 4652): 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4652): JXcore Cordova bridge is ready!
I/jxcore-log( 4652): 
,W/jxcore-log( 4652): JXcore engine is started
,I/chromium( 4652): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4652): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4652): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  955): Killing 4135:com.google.android.talk/u0a77 (adj 15): empty #17
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 2 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3}
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/GAV2    ( 4592): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4652): Toggling radios to true
I/jxcore-log( 4652): 
,D/BluetoothManagerService(  955): Message: 20
,D/BluetoothManagerService(  955): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44872cd0:true
,D/BluetoothAdapter( 4652): enable(): BT is already enabled..!
D/WifiService(  955): New client listening to asynchronous messages
D/WifiStateMachine(  955): handleMessage: E msg.what=131145
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doBoolean: DISCONNECT
,I/jxcore-log( 4652): Radios toggled
I/jxcore-log( 4652): 
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2016): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2016): wlan0: Cancelling scan request
D/wpa_supplicant( 2016): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2016): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2016): TDLS: Tear down peers
,D/wpa_supplicant( 2016): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  955): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4652): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4652): 
D/WifiService(  955): setWifiEnabled: true pid=4652, uid=10304
E/WifiService(  955): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  955): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  955): disconnect pid=4652, uid=10304
,D/WifiService(  955): reconnect pid=4652, uid=10304
I/jxcore-log( 4652): Perf Test app loaded loaded
I/jxcore-log( 4652): 
I/jxcore-log( 4652): check test folder
I/jxcore-log( 4652): 
I/jxcore-log( 4652): found test : ./testFindPeers.js
I/jxcore-log( 4652): 
D/wpa_supplicant( 2016): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2016): wlan0: Deauthentication notification
D/wpa_supplicant( 2016): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2016): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2016): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2016): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2016): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2016): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb875dd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2016):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2016): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2016): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2016): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2016): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2016): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant(, 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2016): nl80211: Event message available
D/wpa_supplicant( 2016): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2016): nl80211: Ignore disconnect event triggered during reassociation
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  955):    returned true
D/WifiStateMachine(  955): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  955): invokeExitMethods: ConnectedState
W/Settings(  955): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  955): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  955): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131146
D/WifiStateMachine(  955): processMsg: DisconnectingState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiNative-wlan0(  955): doBoolean: RECONNECT
,I/jxcore-log( 4652): found test : ./testSendData.js
I/jxcore-log( 4652): 
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2016): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2016): Fast associate: Old scan results
D/wpa_supplicant( 2016): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2016): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2016): wlan0: nl80211: scan request
,D/wpa_supplicant( 2016): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2016): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2016): nl80211: Event message available
D/wpa_supplicant( 2016): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2016): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  955):    returned true
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147460
D/WifiStateMachine(  955): processMsg: DisconnectingState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): Network connection lost
D/WifiStateMachine(  955): Stopping DHCP and clearing IP
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  955): doBoolean: SET ps 1
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2016): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2016): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2016): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  955):    returned true
D/WifiNative-wlan0(  955): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  955):    returned true
D/WifiP2pService(  955): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  955): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  955): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  955): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  955): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  955): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  955): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  955): invokeExitMethods: DisconnectingState
,D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  955): invokeEnterMethods: DisconnectedState
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  457): Reading a NULL string not supported here.
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
D/QCNEA   (  457): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  457): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  457): |CAC| updateNetCfgInfo
V/QCNEA   (  457): |CAC| *********************************************
V/QCNEA   (  457): |CAC|                   Netconfig               
V/QCNEA   (  457): |CAC| *********************************************
V/QCNEA   (  457): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  457): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  457): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  457): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  457): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  457): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  457): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  457): |CAC| *********************************************
D/QCNEA   (  457): |CAC| Received bssid= 
D/QCNEA   (  457): |CAC| net type = 3
V/QCNEA   (  457): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  457): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  457): |CAC| 	ssid           =NG700
V/QCNEA   (  457): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  457): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  457): |CAC| *********************************************
D/QCNEA   (  457): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  457): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  457): |CAC| dispatchNetCfg: updating:0xb7a098dc
D/QCNEA   (  457): |CAC| readCallback: read len:0, ret:-1, errno:11
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  955): handleMessage: E msg.what=131213
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
D/WifiStateMachine(  955): processMsg: DefaultState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131213
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
D/WifiStateMachine(  955): processMsg: DefaultState
,D/WifiStateMachine(  955): handleMessage: X
D/WifiHS20(  955): hidePasspointNotification off =false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  955): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4703 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/QcConnectivityService(  955): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/NetworkManagementService(  955): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  955): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  955): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  271): RouteController
D/QcConnectivityService(  955): Attempting to switch to mobile
D/QcConnectivityService(  955): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  955): handleConnectivityChange: preConnState=1 connState=2
,D/HyLog   ( 4703): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4703): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4703): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/PCSuite ( 4703): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  271): RouteController
,D/PCSuite ( 4703): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4703): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,W/NetworkManagementService(  955): route cmd failed: 
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
,D/NetUtils(  955): android_net_utils_resetConnections in env=0x609df6a0 clazz=0x6ca00001 iface=wlan0 mask=0x3
I/ActivityManager(  955): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4739 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  955): Killing 3901:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/QcConnectivityService(  955): resetConnections(wlan0, 3)
I/chromium( 4652): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/Choreographer( 4652): Skipped 66 frames!  The application may be doing too much work on its main thread.
V/NativeCrypto( 1534): Read error: ssl=0x638fb900: I/O error during system call, Connection timed out
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 2 tasks}
,V/NativeCrypto( 1534): SSL shutdown failed: ssl=0x638fb900: I/O error during system call, Broken pipe
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4739): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4739): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4739): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/LocSvc_java(  955): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  955): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  955): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QRemote ( 4739): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
,D/QRemote ( 4739): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4739): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4739): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4739): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4739): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4739): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4739): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4739): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  955): Killing 4321:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 2 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  955): StoppedState
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
D/WifiStateMachine(  955): processMsg: DefaultState
,D/WifiStateMachine(  955): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1534): onDestroy
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.472992 Y: -0.390244 Z: 9.743118 
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.472992 .y:-0.390244 .z:9.743118
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.477509 Y: -0.368896 Z: 9.766510 
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.477509 .y:-0.368896 .z:9.766510
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  955): handleInetConditionChange: no active default network - ignore
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  955): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  955): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  955): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4000): onReceive
,D/AppUp4:CustFacade( 4000): Context : android.app.ReceiverRestrictedContext@42818358
D/AppUp4:CustFacade( 4000): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4000): isOpenOperator : true
,D/AppUp4:CustFacade( 4000): isPhone : true
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 4000): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4000): begin check event
,I/AppUp4:CustModeStarterReceiver( 4000): Event For GoodConnectivity
,D/EAS     ( 4572): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4572): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4572): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4341): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4341): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4341): networkInfo.isConnected() = false
,I/ActivityManager(  955): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4770 uid=10052 gids={50052, 3003}
,D/wpa_supplicant( 2016): nl80211: Event message available
D/wpa_supplicant( 2016): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2016): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2016): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2016): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 2016): nl80211: Survey data missing
D/wpa_supplicant( 2016): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2016): wlan0: BSS: Add new id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Add new id 6 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Add new id 7 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Add new id 8 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Add new id 9 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Add new id 10 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 2016): wlan0: New scan results available
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2016): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2016): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2016): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2016): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2016): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2016): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2016): WPS: AP[3] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2016): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2016): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2016): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2016): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56
D/wpa_supplicant( 2016): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2016): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2016): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2016): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2016): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2016): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2016): wlan0: [MDM] lg_mdm_auto_connect_poli,cy 1
D/wpa_supplicant( 2016): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2016): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2016): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2016): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb875f5a8  current_ssid=0x0
D/wpa_supplicant( 2016): scard is not null..
D/wpa_supplicant( 2016): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2016): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2016): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2016): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2016): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2016): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2016): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2016): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2016): wlan0: Cancelling scan request
D/wpa_supplicant( 2016): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2016): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2016): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2016): RSN: PMKSA cache search - network_ctx=0xb875f5a8 try_opportunistic=0
D/wpa_supplicant( 2016): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2016): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2016): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2016): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2016): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2016): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2016): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2016): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2016): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2016): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2016): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2016): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2016): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2016): nl80211: Unsubscribe mgmt frames handle 0xb875e590 (mode change)
D/wpa_supplicant( 2016): nl80211: Subscribe to mgmt frames with non-AP handle 0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2016): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2016):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016):   * freq=2412
D/wpa_supplicant( 2016):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2016):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016):   * Auth Type 0
D/wpa_supplicant( 2016):   * WPA Versions 0x2
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 fc:94:e3:11:35:3a]
D/wpa_supplicant( 2016): nl80211: Connect request send successfully
D/wpa_supplicant( 2016): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2016): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 a0:c5:62:7a:49:97]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 fe:94:e3:11:35:3c]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 44:e9:dd:10:c0:ab]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 44:e9:dd:10:c0:ad]
D/WifiStateMachine(  955): handleMessage: E msg.what=147461
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  955): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2016): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  955): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  955): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
W/linker  ( 4572): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4572): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4572): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4572): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4572): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HtmlEditor( 4572): register_HtmlEditor, Success
D/HtmlEditor( 4572): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4572): register_HtmlEditorTimer, Success
D/HtmlEditor( 4572): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4572): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4572): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4572): register_HtmlEditorFont, Success
D/HtmlEditor( 4572): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4572): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4572): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HyLog   ( 4770): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4770): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4770): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HtmlEditor( 4572): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4572): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4572): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4572): JNI_OnLoad Success
I/HubEmail( 4572): JNI_OnLoad()
I/HubEmail( 4572): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4572): registerNatives()
I/HubEmail( 4572): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4572): registerNativeMethods()
I/HubEmail( 4572): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4572): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4770): [loadRssi] File not exist 
V/LGRssiData( 4770): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4770): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4770): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4770): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4770): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4770): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 4770): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4770): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 4770): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4770): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4770): [getValue] FEATURE key : vzw_roaming_state, value : null
E/PhoneMonitor( 4770): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4770): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  955): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4800 uid=10063 gids={50063, 3003, 1028, 1015}
D/wpa_supplicant( 2016): nl80211: Event message available
D/wpa_supplicant( 2016): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2016): nl80211: Connect event
D/wpa_supplicant( 2016): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2016): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2016): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2016): wlan0: Association info event
D/wpa_supplicant( 2016): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2016): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2016): wlan0: freq=2412 MHz
D/wpa_supplicant( 2016): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2016): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2016): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2016): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2016): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): scard is not null..
D/wpa_supplicant( 2016): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2016): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2016): TDLS: Remove peers on association
D/wpa_supplicant( 2016): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2016): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2016): EAPOL: enable timer tick
D/wpa_supplicant( 2016): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2016): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2016): wlan0: Cancelling scan request
D/wpa_supplicant( 2016): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  955): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
W/WifiMonitor(  955): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
I/ActivityManager(  955): Killing 4497:com.android.defcontainer/u0a4 (adj 15): empty #17
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 2 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4800): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4800): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4800): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2016): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e1 85 3a fe 93 b9 25 64 26 6b 29 4b 5a ea c2 ...
D/wpa_supplicant( 2016): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2016): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2016): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2016): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2016): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2016):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2016):   key_nonce - hexdump(len=32): e1 85 3a fe 93 b9 25 64 26 6b 29 4b 5a ea c2 c6 48 68 21 b2 d8 02 36 3c ef 74 9b 49 49 c5 c6 db
D/wpa_supplicant( 2016):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 2016):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e1 85 3a fe 93 b9 25 64 26 6b 29 4b 5a ea c2 ...
D/wpa_supplicant( 2016): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2016): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2016): Get randomness: len=32 entropy=11
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/wpa_supplicant( 2016): WPA: Renewed SNonce - hexdump(len=32): e5 97 0f 0e 52 e9 c9 33 58 60 94 a1 b8 de b1 e8 44 1f 75 47 51 c5 5c e0 50 32 75 04 ab b7 3e 89
D/wpa_supplicant( 2016): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): WPA: Nonce1 - hexdump(len=32): e5 97 0f 0e 52 e9 c9 33 58 60 94 a1 b8 de b1 e8 44 1f 75 47 51 c5 5c e0 50 32 75 04 ab b7 3e 89
D/wpa_supplicant( 2016): WPA: Nonce2 - hexdump(len=32): e1 85 3a fe 93 b9 25 64 26 6b 29 4b 5a ea c2 c6 48 68 21 b2 d8 02 36 3c ef 74 9b 49 49 c5 c6 db
D/wpa_supplicant( 2016): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2016): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2016): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2016): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2016): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2016): WPA: Derived Key MIC - hexdump(len=16): 8f e1 15 fd 47 e4 8f 92 65 26 dd a8 95 6c 75 d2
,D/wpa_supplicant( 2016): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 e5 97 0f 0e 52 e9 c9 33 58 60 94 a1 b8 de b1 ...
,D/wpa_supplicant( 2016): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e1 85 3a fe 93 b9 25 64 26 6b 29 4b 5a ea c2 ...
,D/wpa_supplicant( 2016): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2016): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2016): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2016): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2016):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2016):   key_nonce - hexdump(len=32): e1 85 3a fe 93 b9 25 64 26 6b 29 4b 5a ea c2 c6 48 68 21 b2 d8 02 36 3c ef 74 9b 49 49 c5 c6 db
D/wpa_supplicant( 2016):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016):   key_rsc - hexdump(len=8): 7f 4d 00 00 00 00 00 00
D/wpa_supplicant( 2016):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016):   key_mic - hexdump(len=16): de d9 4a ec f9 d4 5e 95 1b 8d 0c 5b e3 64 6f fb
D/wpa_supplicant( 2016): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e1 85 3a fe 93 b9 25 64 26 6b 29 4b 5a ea c2 ...
D/wpa_supplicant( 2016): RSN: encrypted key data - hexdump(len=56): 95 62 b8 ce 4a d5 b4 ff 19 4a d7 07 cc d0 74 53 de b3 d2 c5 9c 58 bb 3b 55 03 31 4c 07 86 fe d9 ...
D/wpa_supplicant( 2016): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2016): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2016): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2016): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 1e 1b ...
D/wpa_supplicant( 2016): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2016): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2016): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2016): WPA: Derived Key MIC - hexdump(len=16): 19 42 28 38 0a 64 66 83 89 6a 12 c6 51 b9 d2 6c
D/wpa_supplicant( 2016): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2016): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb875ec54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2016):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2016): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2016): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2016): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2016): WPA: RSC - hexdump(len=6): 7f 4d 00 00 00 00
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6efe03a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2016):    broadcast key
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2016): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2016): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2016): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2016): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2016): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2016): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2016): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2016): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2016): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2016): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2016): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2016): EAPOL authentication completed successfully
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiMonitor(  955): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  955): processMsg: ConnectModeState
W/WifiMonitor(  955): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiStateMachine(  955): handleMessage: X
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  955): handleMessage: E msg.what=147459
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): Network connection established
D/WifiNative-wlan0(  955): doString: STATUS
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2016): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
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
I/WifiServiceExtension(  955): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  955): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  955): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/ActivityManager(  955): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4816 uid=10066 gids={50066, 4002, 3003, 1028}
,D/WifiStateMachine(  955): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  955): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,I/ActivityManager(  955): Killing 4527:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  955): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  955): invokeEnterMethods: L2ConnectedState
E/Parcel  (  457): Reading a NULL string not supported here.
D/WifiStateMachine(  955): invokeEnterMethods: ObtainingIpState
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
D/WifiStateMachine(  955): handleMessage: X
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-25ms what=147462 obj=android.net.wifi.StateChangeResult@44e65a58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/DhcpStateMachine(  955): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  955): WaitBeforeStartState
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-23ms what=147462 obj=android.net.wifi.StateChangeResult@44ea32f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147459
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/WifiStateMachine(  955): ObtainingIpState{ when=-24ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131155
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2016): nl80211: survey data missing!
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=196612
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiNative-wlan0(  955): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2016): wlan0: Control, interface command 'DRIVER BTCOEXMODE 1'
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 2 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4816): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4816): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4816): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2827): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  955): Killing 4559:com.lge.bnr/1000 (adj 15): empty #17
,D/LGDMClient( 2827): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/ActivityManager(  955): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4831 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 2 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4831): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4831): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4831): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4831): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  955): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4844 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  955): Killing 4182:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 2 tasks}
,D/HyLog   ( 4844): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4844): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4844): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  955):    returned true
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  955): doBoolean: SET ps 0
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2016): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2016): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2016): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  955):    returned true
,D/WifiNative-wlan0(  955): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  955):    returned null
E/WifiStateMachine(  955): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  955): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  955):    returned null
E/WifiStateMachine(  955): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  955): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  955): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  955): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  955): DHCP Start wake lock is acquired.
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3}
D/WifiP2pService(  955): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431de410 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  955): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431de410 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  271): Setting iface cfg
D/WifiStateMachine(  955): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/CommandListener(  271): Trying to bring up wlan0
I/NFS     ( 4844): connectivityManager.getNetworkInfo = TYPE_WIFI
V/LgDhcpStateMachineHelper(  955): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131212
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
D/WifiStateMachine(  955): processMsg: DefaultState
D/WifiStateMachine(  955): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=196613
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  955): doBoolean: SET ps 1
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2016): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2016): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2016): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  955):    returned true
D/WifiNative-wlan0(  955): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  955): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  955): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  955):    returned true
D/WifiStateMachine(  955): DHCP successful
D/WifiStateMachine(  955): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  955): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  955): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  955): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  955): VerifyingLinkState enter
I/Wireless_Storage( 4844): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4844): intf.getDisplayName() = lo
I/Wireless_Storage( 4844): intf.getDisplayName() = sit0
I/Wireless_Storage( 4844): intf.getDisplayName() = p2p0
D/WifiStateMachine(  955): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/Wireless_Storage( 4844): intf.getDisplayName() = teql0
I/Wireless_Storage( 4844): intf.getDisplayName() = wlan0
D/NFS     ( 4844): interface name:wlan0 name:wlan0
,D/NFS     ( 4844): addr:192.168.1.144 broadcast:192.168.1.255
,D/WifiStateMachine(  955): handleMessage: X
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  955): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  955): handleMessage: E msg.what=135190
D/WifiStateMachine(  955): processMsg: VerifyingLinkState
D/WifiStateMachine(  955): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  955): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  955): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  955): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  955): CaptivePortalCheckState enter
,D/WifiStateMachine(  955): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
W/WifiStateTracker(  955): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  955): 
W/WifiStateTracker(  955):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  955):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  955): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  955): handleMessage: E msg.what=131092
D/WifiStateMachine(  955): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  955): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
I/ActivityManager(  955): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4856 uid=10104 gids={50104, 3003, 1028, 1015}
I/ActivityManager(  955): Killing 4199:com.android.gallery3d/u0a27 (adj 15): empty #17
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  955): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  955): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  955): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  955): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
D/WifiStateMachine(  955): transitionTo: destState=ConnectedState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  955): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
,D/WifiStateMachine(  955): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  955): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 2 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: CONNECTED/CONNECTED
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiController(  955): battery changed pluggedType: 2
E/ActivityThread(  955): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  955): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  955): handleConnectivityChange: preConnState=2 connState=1
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HyLog   ( 4856): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4856): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4856): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,W/GAV2    ( 4856): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/LocSvc_java(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  457): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  457): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  457): |CAC| updateNetCfgInfo
V/QCNEA   (  457): |CAC| *********************************************
V/QCNEA   (  457): |CAC|                   Netconfig               
V/QCNEA   (  457): |CAC| *********************************************
V/QCNEA   (  457): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  457): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  457): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  457): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  457): |CAC| 	NetConfig: ip6        =::
D/GpsLocationProvider(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/QCNEA   (  457): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  457): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  457): |CAC| *********************************************
D/QCNEA   (  457): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  457): |CAC| net type = 1
V/QCNEA   (  457): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  457): |CAC| Received ssid= NG700
V/QCNEA   (  457): |CAC| 	ssid           =NG700
V/QCNEA   (  457): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  457): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  457): |CAC| *********************************************
D/QCNEA   (  457): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  457): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  457): |CAC| dispatchNetCfg: updating:0xb7a098dc
,D/QCNEA   (  457): |CAC| readCallback: read len:0, ret:-1, errno:11
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=true
,D/DhcpStateMachine(  955): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  955): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  955): GC_EXPLICIT freed 23537K, 49% free 29704K/57536K, paused 3ms+11ms, total 134ms
,D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinService( 1963): Checking schedule, now: 1450463694450 next: 1450463640458
,I/CheckinService( 1963): active receiver: enabled
,I/CheckinService( 1963): Preparing to send checkin request
,I/EventLogService( 1963): Accumulating logs since 1450463607792
,I/CheckinRequestBuilder( 1963): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1963): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromium( 4856): Binding Chromium to the main looper Looper (main, tid 1) {42803340}
,I/chromium( 4856): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4856): Initializing chromium process, renderers=0
,W/chromium( 4856): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4856): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4856): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4856): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4856): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4856): Remote Branch: 
I/Adreno-EGL( 4856): Local Patches: 
I/Adreno-EGL( 4856): Reconstruct Branch: 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NSApplication( 4856): Starting up...
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QRemote ( 4739): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4739): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4739): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4739): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,D/QRemote ( 4739): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4739): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4703): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4703): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4739): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4739): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4739): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4739): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,W/CheckinRequestBuilder( 1963): awaiting user notification for token
D/NotificationService(  955): updateLightListLocked :r=NotificationRecord(0x431f34a0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  955): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ActivityManager(  955): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4924 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/dalvikvm(  275): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+1ms, total 18ms
,D/HyLog   ( 4924): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4924): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4924): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,W/dalvikvm( 4924): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4924): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4924): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4924): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4924): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4924): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4924): install
,I/MultiDex( 4924): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
,I/MultiDex( 4924): loading existing secondary dex files
,I/MultiDex( 4924): load found 3 secondary dex files
,I/MultiDex( 4924): install done
,D/dalvikvm( 4924): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 4924): VFY: unable to resolve instance field 61
,D/dalvikvm( 4924): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4924): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4924): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4924): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4924): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4924): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4924): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4924): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4924): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4924): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4280a5e0
D/dalvikvm( 4924): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4280a5e0
,D/dalvikvm( 4924): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4280a5e0, skipping init
,D/dalvikvm( 4924): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4280a5e0
D/dalvikvm( 4924): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4280a5e0
,V/JNIHelp ( 4924): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4924): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4280a5e0
,D/dalvikvm( 4924): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4280a5e0
D/dalvikvm( 4924): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4280a5e0
,D/dalvikvm( 4924): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4280a5e0
,I/ProviderInstaller( 4924): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1534): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1534): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1534): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1963): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1871): callingUid 10006, callindPid: 1871
,D/LocationInitializer( 1963): Restart initialization of location
,E/MDM     ( 1424): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/dalvikvm( 4924): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4924): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4924): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4924): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4924): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4924): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e3f000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e3f000
,D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/GCM     ( 1534): Connected
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1534): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=1425834649
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4924): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429d7b10
,D/dalvikvm( 4924): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429d7b10
,D/dalvikvm( 4924): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429d7b10, skipping init
,D/DhcpStateMachine(  955): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  955): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  955): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  955): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  955): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  955): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  955): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  955): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  955): RunningState
,D/wpa_supplicant( 2016): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2016): EAPOL: disable timer tick
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=1357792036
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  955): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
D/ConnectivityServiceHSM(  955): NetTransition Wakelock for ConnectedState released by timeout
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiController(  955): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  955): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/Settings( 4924): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4924): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4977): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4924): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4924): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 72ms
,I/Adreno-EGL( 4924): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4924): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4924): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4924): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4924): Remote Branch: 
I/Adreno-EGL( 4924): Local Patches: 
I/Adreno-EGL( 4924): Reconstruct Branch: 
,I/Adreno-EGL( 4924): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4924): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4924): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4924): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4924): Remote Branch: 
I/Adreno-EGL( 4924): Local Patches: 
I/Adreno-EGL( 4924): Reconstruct Branch: 
,I/Adreno-EGL( 4924): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4924): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4924): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4924): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4924): Remote Branch: 
I/Adreno-EGL( 4924): Local Patches: 
I/Adreno-EGL( 4924): Reconstruct Branch: 
I/dalvikvm( 4652): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4652): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4652): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4652): Shutting down VM
,W/dalvikvm( 4652): threadid=1: thread exiting with uncaught exception (group=0x417c1e48)
E/AndroidRuntime( 4652): FATAL EXCEPTION: main
E/AndroidRuntime( 4652): Process: com.test.thalitest, PID: 4652
E/AndroidRuntime( 4652): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4652): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4652): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4652): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4652): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4652): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4652): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4652): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4652): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4652): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4652): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4652): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4652): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4652): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4652): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4652): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4652): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4652): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4652): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  955):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  955): Moving to PAUSING: ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3 f}
,I/CheckinRequestBuilder( 1963): Classify the device as Phone.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1963): GC_CONCURRENT freed 1533K, 22% free 19535K/24832K, paused 4ms+3ms, total 63ms
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
D/WifiStateMachine(  955): handleMessage: X
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  955): send additional Connectivity Action
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/GpsLocationProvider(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
,D/QcConnectivityService(  955): handleConnectivityChange:1 is conntected
D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
I/CheckinTask( 1963): Sending checkin request (11462 bytes)
,D/QcConnectivityService(  955): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  955):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  955): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=true
,W/ActivityManager(  955): Activity pause timeout for ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  955): Moving to PAUSED: ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  955): Moving to STOPPING: ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323c2d8 stackId=1, 2 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  955): moveHomeStack:
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,V/ActivityManager(  955): Moving to RESUMED: ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  955): resumeTopActivityLocked: Resumed ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  955): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
I/[LGHome]EVENT( 1500): [Launcher.java:4947:onStart()]onStart
I/[LGHome]EVENT( 1500): [Launcher.java:717:onResume()]onResume
I/[LGHome]EVENT( 1500): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1500): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PhoneApp( 1461): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1500): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1500): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1835): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:34:56
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  955): battery changed pluggedType: 2
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1835): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1835): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1835): 2 : TimeTick Receiver Register
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WeatherAncestor( 1835): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:34:56
D/WeatherService( 1835): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
D/Weather.Utils( 1835): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/WifiController(  955): battery changed pluggedType: 2
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WeatherService( 1835): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1835): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1835): 2 : Map key string is -2
D/lim     ( 1835): 2 : time = 19:34
I/WeatherReflect( 1835): Model Name : LG-D802
D/WeatherTheme( 1835): 2 : Different view - status_min_formatted : 33 != 34
D/WeatherTheme( 1835): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1835): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1835): 2 : Fixed theme : optimus
D/WeatherTheme( 1835): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
D/Weather.Utils( 1835): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1500): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1500): GC_CONCURRENT freed 5548K, 9% free 60933K/66676K, paused 1ms+2ms, total 23ms
,D/dalvikvm( 1500): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 1140): GC_FOR_ALLOC freed 3479K, 10% free 71339K/78452K, paused 32ms, total 32ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1500): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1500): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1500): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1500): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1500): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1500): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1500): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1500): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/CheckinRequestBuilder( 1963): Checkin reason type: 8 attempt count: 1
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
E/ActivityThread( 1963): Failed to find provider info for com.google.android.wearable.settings
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1500): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1500): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1500): GC_FOR_ALLOC freed 4876K, 9% free 61906K/67532K, paused 22ms, total 23ms
,W/CheckinRequestBuilder( 1963): awaiting user notification for token
,I/CheckinRequestBuilder( 1963): Classify the device as Phone.
,I/CheckinTask( 1963): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1963): Checking schedule, now: 1450463696706 next: 1451041092703
,I/CheckinService( 1963): active receiver: disabled
,D/dalvikvm(  955): GC_CONCURRENT freed 2239K, 47% free 30779K/57536K, paused 6ms+5ms, total 119ms
,D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 111ms
D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 55ms
D/dalvikvm(  955): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/ActivityManager(  955): Timeline: Activity_windows_visible id: ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1} time:117503
D/NotificationService(  955): updateLightListLocked :r=NotificationRecord(0x44e4d630: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  955): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/GCM     ( 1534): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager( 1500): Timeline: Activity_idle id: android.os.BinderProxy@428000c0 time:117551
,D/UsbSettings( 2581): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2581): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2581): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2581): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  955): Moving to FINISHING: ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  955): Moving to DESTROYING: ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
V/ActivityManager(  955): Moving to DESTROYING: ActivityRecord{42ff4050 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  955): Moving to DESTROYED: ActivityRecord{42ff4050 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
,D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
,D/WifiStateMachine(  955): handleMessage: X
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  955): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  955): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  955): battery changed pluggedType: 2
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  955): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  955): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4000): onReceive
,D/AppUp4:CustFacade( 4000): Context : android.app.ReceiverRestrictedContext@42818358
D/AppUp4:CustFacade( 4000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4000): isOpenOperator : true
,D/AppUp4:CustFacade( 4000): isPhone : true
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 4000): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4000): begin check event
I/AppUp4:CustModeStarterReceiver( 4000): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4000): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4000): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4000): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4000): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4000): handleAsyncCustNotification do not startCustService
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4256): DownloadService onCreate
,D/EAS     ( 4572): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4572): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
D/eas_req ( 4572): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4256): in removeSpuriousFiles
,V/DownloadManager( 4256): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@42852470 on behalf of 4256
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4256): DownloadService onStartCommand
I/DownloadManager( 4256): in trimDatabase
V/DownloadManager( 4256): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@42854338 on behalf of 4256
V/DownloadManager( 4256): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@42856070 on behalf of 4256
I/LgeMiscReceiver( 4341): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4341): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4341): networkInfo.isConnected() = false
W/Settings( 4572): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4770): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4770): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4256): DownloadService onDestroy
D/LGDMClient( 2827): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2827): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/LGDMSGCM( 4831): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2827): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2827): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2827): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
I/NFS     ( 4844): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4844): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2827): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/ContextImpl( 4831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2827): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4000): onReceive
D/AppUp4:CustFacade( 4000): Context : android.app.ReceiverRestrictedContext@42818358
D/AppUp4:CustFacade( 4000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4000): isOpenOperator : true
,D/AppUp4:CustFacade( 4000): isPhone : true
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 4000): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4000): begin check event
,I/AppUp4:CustModeStarterReceiver( 4000): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4256): DownloadService onCreate
,I/DownloadManager( 4256): in removeSpuriousFiles
,V/DownloadManager( 4256): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4572): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@4285aa28 on behalf of 4256
,D/EAS     ( 4572): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4256): in trimDatabase
V/DownloadManager( 4256): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4256): DownloadService onStartCommand
,V/DownloadManager( 4256): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@4285c090 on behalf of 4256
,V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@4285dda8 on behalf of 4256
I/LgeMiscReceiver( 4341): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4341): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4341): networkInfo.isConnected() = true
,D/PhoneState( 4341): setPdpRejectCasuse : false
,W/Settings( 4572): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4770): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4770): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4256): DownloadService onDestroy
,D/LGDMClient( 2827): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4831): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2827): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 4831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2827): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4844): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4844): CONNECT : WIFI_CONNECT
E/LGDMClient( 2827): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2827): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2827): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2827): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  955): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1500): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1500): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1500): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1500): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  955): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  955): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4000): onReceive
,D/AppUp4:CustFacade( 4000): Context : android.app.ReceiverRestrictedContext@42818358
D/AppUp4:CustFacade( 4000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4000): isOpenOperator : true
,D/AppUp4:CustFacade( 4000): isPhone : true
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 4000): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4000): begin check event
,I/AppUp4:CustModeStarterReceiver( 4000): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4572): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4256): DownloadService onCreate
,D/EAS     ( 4572): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4341): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4341): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4341): networkInfo.isConnected() = true
,D/PhoneState( 4341): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4770): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4770): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2827): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/DownloadManager( 4256): in removeSpuriousFiles
,V/DownloadManager( 4256): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMSGCM( 4831): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 4572): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 4831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/WifiServiceExtension(  955): MESSAGE_INTERNET_CHECK msg is received.
,I/NFS     ( 4844): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4844): CONNECT : WIFI_CONNECT
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@42862050 on behalf of 4256
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/DownloadManager( 4256): in trimDatabase
V/DownloadManager( 4256): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/LGDMClient( 2827): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
V/DownloadManager( 4256): DownloadService onStartCommand
V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@42863a60 on behalf of 4256
V/DownloadManager( 4256): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2827): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@42865ba8 on behalf of 4256
,E/LGDMClient( 2827): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2827): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2827): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2827): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 4256): DownloadService onDestroy
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/GAV2    ( 4856): Thread[GAThread,5,main]: No campaign data found.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  955): battery changed pluggedType: 2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/WifiServiceExtension(  955): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  955): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  955): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/ActivityManager(  955): Killing 4592:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  955): Killing 4703:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  955): Killing 4219:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1}
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  955): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/WeatherService( 1835): 2 : TimeTick Intent has been received, Time(hour:min:sec) 19:35:0
,D/WeatherService( 1835): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1835): 2 : SDK version : 19
,E/ThermalEngine(  291): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1835): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1835): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1835): 2 : Map key string is -2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463700041, nextTick: 59987, mDrawingTime: 2
,D/lim     ( 1835): 2 : time = 19:35
,I/WeatherReflect( 1835): Model Name : LG-D802
,D/WeatherTheme( 1835): 2 : Different view - status_min_formatted : 34 != 35
,D/WeatherTheme( 1835): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1835): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463700050, nextTick: 59982, mDrawingTime: 0
,D/WeatherTheme( 1835): 2 : Fixed theme : optimus
,D/WeatherTheme( 1835): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WeatherService( 1835): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 19:35:0
,D/WifiController(  955): battery changed pluggedType: 2
,D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,D/WifiController(  955): battery changed pluggedType: 2
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  955): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5141 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5141): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5141): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5141): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5141): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5141): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5141): VFY: replacing opcode 0x6e at 0x000b
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5141): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5141): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5141): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5141): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5141): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5141): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5141): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5141): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5141): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5141): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5141): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/DownloadManager( 4256): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@4286a8e0 on behalf of 5141
I/dalvikvm( 5141): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5141): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5141): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5141): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5141): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5141): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5141): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5141): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5141): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 5141): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5141): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5141): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5141): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5141): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5141): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5141): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5141): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5141): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5141): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm( 5141): Total arena pages for JIT: 11
,I/dalvikvm( 5141): Total arena pages for JIT: 12
I/dalvikvm( 5141): Total arena pages for JIT: 13
,I/dalvikvm( 5141): Total arena pages for JIT: 14
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/Finsky  ( 5141): [459] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/Finsky  ( 5141): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  955): Killing 4739:com.lge.qremote/u0a96 (adj 15): empty #17
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1}
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  955): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1218): Disconnected process message: 10
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5141): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5141): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5141): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5141): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5141): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1534): GC_EXPLICIT freed 1210K, 29% free 17816K/24832K, paused 2ms+5ms, total 38ms
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5141): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5141): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5141): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5141): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5141): [1] DailyHygiene.reschedule: Scheduling new run in 98 minutes (failures=3)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiNative-wlan0(  955): doString: SIGNAL_POLL,
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1500): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1500): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1500): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3731): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3731): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,D/administrator(  955): Handling package changes for user 0
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.463867 Y: -0.405777 Z: 9.758438 
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463867 .y:-0.405777 .z:9.758438
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,I/InputReader(  955): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  955): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5219 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "sms"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.472122 Y: -0.394363 Z: 9.761597 
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.472122 .y:-0.394363 .z:9.761597
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "smsto"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "mms"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/HyLog   ( 5219): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5219): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5219): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "mmsto"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "sms"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "smsto"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "mms"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  955):   Scheme: "mmsto"
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/WifiController(  955): battery changed pluggedType: 2
,I/Babel   ( 5219): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5219): MmsConfig.loadMmsSettings
,I/Babel   ( 5219): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5219): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5219): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5219): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5219): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5219): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5219): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5219): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5219): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5219): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5219): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5219): MmsConfig.loadFromResources
E/Babel   ( 5219): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5219): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5219): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5219): [loadRssi] File not exist 
V/LGRssiData( 5219): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5219): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:Utils( 4000): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4000): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4000): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4000): onReceive
D/AppUp4:CustFacade( 4000): Context : android.app.ReceiverRestrictedContext@42818358
D/AppUp4:CustFacade( 4000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4000): isOpenOperator : true
D/AppUp4:CustFacade( 4000): isPhone : true
,V/TelephonyAutoProfiling( 5219): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5219): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5219): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 4000): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4000): begin check event
D/AppUp4:Utils( 4000): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4000): Event For Nothing, skip.
,I/ActivityManager(  955): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5266 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/[LGHome]EVENT( 1500): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1424): DISABLE
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/HyLog   ( 5266): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5266): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5266): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  955): applying state to connected service
,D/dalvikvm(  955): GC_EXPLICIT freed 2476K, 47% free 30677K/57536K, paused 3ms+9ms, total 97ms
,I/ActivityManager(  955): Killing 4652:com.test.thalitest/u0a304 (adj 15): empty #17
,D/LocationProviderProxy(  955): applying state to connected service
,I/SystemConfig( 5266): BUILD Country: EU
,I/SystemConfig( 5266): BUILD Operator: OPEN
,I/SystemConfig( 5266): systemFeature RCS result false
,D/SystemConfig( 5266): refreshRcsSupport() :false
I/ActivityManager(  955): Killing 4572:com.lge.email/u0a24 (adj 15): empty #17
D/WifiService(  955): Client connection lost with reason: 4
I/WindowState(  955): WIN DEATH: Window{44b91918 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  955): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5284 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,V/ActivityManager(  955): Moving to DESTROYED: ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  955): Moving to DESTROYED: ActivityRecord{44e93988 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1500): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1}
I/InputMethodManagerService(  955): IME STATUS OFF
,W/InputMethodManagerService(  955): Got RemoteException sending setActive(false) notification to pid 4652 uid 10304
W/Binder  ( 1304): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1304): java.lang.NullPointerException
W/Binder  ( 1304): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1304): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1304): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1304): 	at dalvik.system.NativeStart.run(Native Method)
,D/HyLog   ( 5284): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5284): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5284): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2649): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  955): Killing 4770:com.google.android.setupwizard/u0a52 (adj 15): empty #17
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1963): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  955): Delaying start of: ServiceRecord{4492dbb8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1963): updateResources: need to parse f{com.google.android.gms}
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/IcingCorporaProvider( 2649): UpdateCorporaTask done [took 206 ms] updated apps [took 206 ms] 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/WifiController(  955): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  955): battery changed pluggedType: 2
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/CaptivePortalTracker(  955): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  271): _dns_getaddrinfo: iptype =1
D/QcConnectivityService(  955): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  955): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  955): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  955): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  955): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  955): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  955): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
,D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/GAV4    ( 5219): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/PowerManagerService(  955): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  955): [updateScreenState] screen on = false
D/KnockOnPowerController(  955): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  955): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  955): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  955): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  955): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  955): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  955): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  955): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8458 usec
D/KnockOnPowerController(  955): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  955): hal_acquire_resources
,I/qcom_sensors_hal(  955): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  955): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  955): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  955): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  955): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  955): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  955): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.457306 Y: -0.390213 Z: 9.762787 
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457306 .y:-0.390213 .z:9.762787
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.459320 Y: -0.376831 Z: 9.769501 
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459320 .y:-0.376831 .z:9.769501
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,I/Sensors (  447): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  955): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  955): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  955): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  955): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  955): proximitySensorChanged  positive = true
I/KnockOnPowerController(  955): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.460373 Y: -0.376877 Z: 9.782471 
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460373 .y:-0.376877 .z:9.782471
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.452271 Y: -0.394226 Z: 9.767807 
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452271 .y:-0.394226 .z:9.767807
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.473343 Y: -0.382706 Z: 9.764938 
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.473343 .y:-0.382706 .z:9.764938
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.475586 Y: -0.404175 Z: 9.776047 
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.475586 .y:-0.404175 .z:9.776047
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  955): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4321f088)
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1140): notifyScreenOnLocked
,D/KeyguardViewMediator( 1140): handleNotifyScreenOn
,D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  955): **** SHOWN CALLED ****
I/WindowManager(  955): No lock screen! windowToken=null
,D/SurfaceFlinger(  274): Screen released, type=0 flinger=0xb8329450
V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  955): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.469833 Y: -0.389389 Z: 9.778336 
V/qcom_sensors_hal(  955): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  955): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  955): hal_process_report_ind: X: -0.459854 Y: -0.390488 Z: 9.758392 
,D/qcom_sensors_hal(  955): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.469833 .y:-0.389389 .z:9.778336
D/qcom_sensors_hal(  955): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=0
,D/qdhwcomposer(  274): hwc_blank: Blanking display: 0
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/WifiStateMachine(  955): handleScreenStateChanged: true
,D/WifiStateMachine(  955): handleMessage: E msg.what=131154
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  955): handleMessage: X
,D/WifiStateMachine(  955): handleMessage: E msg.what=131127
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/NativeNfcBrcmPowerMode( 1485): setPowerMode; state=4
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131158
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  955): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiServiceExtension(  955): sendKtScanInterval  mRtspPlay : false
,D/WifiStateMachine(  955): handleMessage: E msg.what=132097
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  955): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2016): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2016): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  955): handleMessage: X
E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  955): stopMonitoring
,E/AudioSystem(  955): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 955
V/SRS_Proc(  277): ParamSet string: screen_state=on
,D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4336a4f0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
D/WeatherAncestor( 1835): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 19:35:17
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/SlideAside( 3731): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
I/SlideAside( 3731): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
,D/WeatherAncestor( 1835): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 19:35:17
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1835): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1835): 2 : TimeTick Receiver Unregister
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1154): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1154): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1154): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1154): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1154): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
,D/qdhwcomposer(  274): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  955): Excessive delay in blankDisplay() while turning screen off: 441ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463718216, nextTick: 41816, mDrawingTime: 1
D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463718235, nextTick: 41797, mDrawingTime: 0
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiStateMachine(  955): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
D/NativeNfcBrcmPowerMode( 1485): setPowerMode; state=4
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/WeatherService( 1835): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:35:18
,D/WeatherService( 1835): 2 : ACTION screen on
D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
,V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WeatherService( 1835): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:35:18
D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/GsmSST  ( 1461): Emergency Service
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1461): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1461): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1461): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1461): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
V/PhoneApp( 1461): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  955): ACTION_SCREEN_ON
,D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  955): _hal_sensors_activate: handle=0, enabled=0
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1140): notifyScreenOffLocked
I/qcom_sensors_hal(  955): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  955): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  955): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,I/[LGHome]EVENT( 1500): [Launcher.java:894:onPause()]onPause
,D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
,V/ActivityManager(  955): Moving to PAUSING: ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  955): hal_acquire_resources
D/qcom_sensors_hal(  955): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  955): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  955): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  955): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  955): hal_process_smgr_resp: 33
,D/qcom_sensors_hal(  955): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
,D/qcom_sensors_hal(  955): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
W/ProcessCpuTracker(  955): Skipping unknown process pid 5340
W/ProcessCpuTracker(  955): Skipping unknown process pid 5341
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ProcessCpuTracker(  955): Skipping unknown process pid 5357
W/ProcessCpuTracker(  955): Skipping unknown process pid 5358
W/ProcessCpuTracker(  955): Skipping unknown process pid 5359
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/[LGHome]EVENT( 1500): [Launcher.java:4955:onStop()]onStop
,I/LGImmersionVibrator(  955): Vibrator off
V/ActivityManager(  955): Moving to PAUSED: ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  955): Moving to STOPPING: ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
,D/WifiStateMachine(  955): handleScreenStateChanged: false
D/WifiStateMachine(  955): handleMessage: E msg.what=131154
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131158
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  955): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/AudioSystem(  955): AudioSystem::setParameters()...keyValue screen_state=off
V/ActivityManager(  955): Moving to STOPPED: ActivityRecord{42c64450 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  955): CMD_SCREEN_OFF 
,D/WifiController(  955): shouldWifiStayAwake TRUE
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 955
V/SRS_Proc(  277): ParamSet string: screen_state=off
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
D/qdlights( 1154): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 87, B = 87
,D/KeyguardViewMediator( 1140): handleNotifyScreenOff
,D/KeyguardViewManager( 1140): onScreenTurnedOff()
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1154): clear
D/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/qdlights( 1154): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 81, B = 81
D/WifiNative-wlan0(  955):    returned true
D/WifiStateMachine(  955): handleMessage: X
D/NativeNfcBrcmPowerMode( 1485): setPowerMode; state=2
I/[LGHome]EVENT( 1500): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1154): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 75, B = 75
,D/WeatherService( 1835): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:35:18
,D/WeatherService( 1835): 2 : ACTION screen off
D/WeatherService( 1835): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:35:18
,V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : trf_based_vzw, value : null
,E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1154): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 69, B = 69
,V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1461): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1461): Emergency Service
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1461): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/BrcmNfcJni( 1485): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1485): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1461): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1461): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
D/NfcService( 1485): NFC-C OFF
V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1461): [getValue] FEATURE key : vzw_gfit, value : null
D/qdlights( 1154): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 63, B = 63
,V/PhoneApp( 1461): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  955): ACTION_SCREEN_OFF
D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1473): [TangibleIO] LCD is off. Remove tangible if exist.
,D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1154): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1154): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1154): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1154): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1154): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1154): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1154): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1154): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  447): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  291): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  955): handleMessage: E msg.what=131155
,D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiStateMachine(  955): handleMessage: X
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1461): getIsInUseVoLTE : false
,D/PhoneApp( 1461): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1534): Vacuum at: now=1450463727296 tag=VacuumService
,I/GoogleURLConnFactory( 1534): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1534): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1534): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1534): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1534): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1534): No account for auth token provided
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/Finsky  ( 5141): [459] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5141): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1154): GC_CONCURRENT freed 2896K, 11% free 25450K/28524K, paused 3ms+2ms, total 25ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1534):  no longer exists, so no auth token.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Uploader( 1534): No account for auth token provided
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463736136307074; DSPS: 5279809; Offset: 1450463575009323432
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  955): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463756136746055; DSPS: 5935183; Offset: 1450463575009335167
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463760041, nextTick: 59989, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463760044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463776137676071; DSPS: 6590574; Offset: 1450463575009319138
,D/wpa_supplicant( 2016): wlan0: BSS: Remove id 2 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81]
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463796138592305; DSPS: 7245963; Offset: 1450463575009350362
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463816139029655; DSPS: 7901338; Offset: 1450463575009329948
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463820035, nextTick: 59995, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463820038, nextTick: 59994, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463836139507048; DSPS: 8556714; Offset: 1450463575009319060
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463856139945796; DSPS: 9212088; Offset: 1450463575009330562
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463876140844080; DSPS: 9867478; Offset: 1450463575009313319
,D/wpa_supplicant( 2016): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Remove id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Remove id 6 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Remove id 7 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Remove id 8 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Remove id 9 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Remove id 10 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 fc:94:e3:11:35:3a],
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 a0:c5:62:7a:49:97]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 fe:94:e3:11:35:3c]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 44:e9:dd:10:c0:ab]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 44:e9:dd:10:c0:ad]
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463880036, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463880042, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463896141300033; DSPS: 10522852; Offset: 1450463575009342026
,D/dalvikvm( 2637): GC_CONCURRENT freed 7759K, 32% free 16894K/24832K, paused 3ms+1ms, total 40ms
,D/dalvikvm( 2637): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463916141755856; DSPS: 11178227; Offset: 1450463575009340085
,I/LocationManagerService(  955): remove 43121348
D/LocationManagerService(  955): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  955): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  955): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  955): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  955): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2637): GC_CONCURRENT freed 1762K, 31% free 17179K/24832K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2637): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2637): GC_CONCURRENT freed 1879K, 31% free 17272K/24832K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 2637): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/Mlt MonitorService( 2637): parseLastkmsg to dump
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463936142669238; DSPS: 11833617; Offset: 1450463575009337940
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463940042, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450463940045, nextTick: 59986, mDrawingTime: 1
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  955): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463956143578549; DSPS: 12489007; Offset: 1450463575009331723
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463976144023859; DSPS: 13144381; Offset: 1450463575009349787
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450463996144467319; DSPS: 13799756; Offset: 1450463575009335484
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464000033, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464000041, nextTick: 59990, mDrawingTime: 1
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  955): updateLightListLocked :r=NotificationRecord(0x432fbd78: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  955): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1534): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1534): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1534): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1534): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1534): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1534): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1534): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1534): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5141): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5141): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5141): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5141): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5141): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5141): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5141): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5141): 	at dalvik.system.NativeStart.run(Native Method)
,D/dalvikvm( 1140): GC_FOR_ALLOC freed 7370K, 14% free 68686K/79644K, paused 61ms, total 66ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 5141): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5141): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464016145362657; DSPS: 14455145; Offset: 1450463575009345812
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464036145832137; DSPS: 15110521; Offset: 1450463575009327011
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464056146269452; DSPS: 15765895; Offset: 1450463575009337079
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464060046, nextTick: 59985, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464060048, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464076147160904; DSPS: 16421284; Offset: 1450463575009343522
,D/wpa_supplicant( 2016): nl80211: Event message available
D/wpa_supplicant( 2016): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2016): nl80211: Disconnect event
D/wpa_supplicant( 2016): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2016): wlan0: Deauthentication notification
D/wpa_supplicant( 2016): wlan0:  * reason 0
D/wpa_supplicant( 2016): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2016): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2016): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2016): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2016): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2016): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2016): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2016): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2016): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  955): handleMessage: E msg.what=147460
D/WifiStateMachine(  955): processMsg: ConnectedState
,D/WifiStateMachine(  955): processMsg: L2ConnectedState,
,D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): Network connection lost,
D/WifiStateMachine(  955): Stopping DHCP and clearing IP,
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  955): doBoolean: SET ps 1
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb875dd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2016):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2016): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2016): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2016): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2016): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2016): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2016): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  955):    returned true
D/WifiNative-wlan0(  955): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiP2pService(  955): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  955): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  955):    returned true
,D/DhcpStateMachine(  955): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  955): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  955): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  955): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
,D/WifiHS20(  955): hidePasspointNotification off =false
D/wpa_supplicant( 2016): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2016): wlan0: nl80211: scan request
D/wpa_supplicant( 2016): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2016): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2016): nl80211: Event message available
D/wpa_supplicant( 2016): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2016): wlan0: nl80211: Scan trigger
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
D/QCNEA   (  457): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  457): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  457): |CAC| updateNetCfgInfo
V/QCNEA   (  457): |CAC| *********************************************
V/QCNEA   (  457): |CAC|                   Netconfig               
V/QCNEA   (  457): |CAC| *********************************************
V/QCNEA   (  457): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  457): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  457): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  457): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  457): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  457): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  457): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  457): |CAC| *********************************************
D/QCNEA   (  457): |CAC| Received bssid= 
D/QCNEA   (  457): |CAC| net type = 3
V/QCNEA   (  457): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  457): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  457): |CAC| 	ssid           =NG700
,V/QCNEA   (  457): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  457): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  457): |CAC| *********************************************
D/QCNEA   (  457): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  457): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  457): |CAC| dispatchNetCfg: updating:0xb7a098dc
,D/QCNEA   (  457): |CAC| readCallback: read len:0, ret:-1, errno:11
D/QcConnectivityService(  955): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  955): Attempting to switch to mobile
D/QcConnectivityService(  955): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  955): handleConnectivityChange: preConnState=1 connState=2
,I/ActivityManager(  955): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5794 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  955): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  955): invokeExitMethods: ConnectedState
D/WifiStateMachine(  955): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  955): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131213
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/NetworkManagementService(  955): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
D/WifiStateMachine(  955): processMsg: DefaultState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=131213
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
D/WifiStateMachine(  955): processMsg: DefaultState
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
D/NetworkManagementService(  955): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  955): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 5794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5794): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/PCSuite ( 5794): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  271): RouteController
D/PCSuite ( 5794): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5794): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/NetworkManagementService(  955): route cmd failed: 
W/NetworkManagementService(  955): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,D/NetUtils(  955): android_net_utils_resetConnections in env=0x609df6a0 clazz=0xb7c00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  955): resetConnections(wlan0, 3)
,I/ActivityManager(  955): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5834 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  955): Killing 4800:com.android.chrome/u0a63 (adj 15): empty #17
,V/NativeCrypto( 1534): Read error: ssl=0x63e699b0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1534): SSL shutdown failed: ssl=0x63e699b0: I/O error during system call, Broken pipe
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5834): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5834): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5834): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DhcpStateMachine(  955): StoppedState
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/LocSvc_java(  955): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  955): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
,D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  955): handleInetConditionChange: no active default network - ignore
D/QRemote ( 5834): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 5834): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 5834): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 5834): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 5834): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 5834): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 5834): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5834): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5834): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  955): Killing 4816:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2016): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  955): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  955): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  955): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/wpa_supplicant( 2016): nl80211: Event message available
D/wpa_supplicant( 2016): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2016): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2016): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2016): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 2016): nl80211: Survey data missing
D/wpa_supplicant( 2016): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2016): wlan0: BSS: Add new id 11 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Add new id 12 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2016): wlan0: New scan results available
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2016): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2016): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2016): WPS: AP[1] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2016): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2016): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2016): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2016): wlan0: 1: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-88 wps
D/wpa_supplicant( 2016): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2016): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2016): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2016): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2016): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2016): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2016): wlan0: 1: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-88 wps
D/wpa_supplicant( 2016): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2016): wlan0: No suitable network found
I/wpa_supplicant( 2016): [LGE_PATCH]scan interval[0] = 0 sec.
D/wpa_supplicant( 2016): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2016): wlan0: Checking for other virtual interfaces sharing same radio (phy0) in event_scan_results
D/wpa_supplicant( 2016): p2p0: Updating scan results from sibling
D/wpa_supplicant( 2016): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 2016): nl80211: Survey data missing
D/wpa_supplicant( 2016): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 2016): p2p0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): p2p0: BSS: Add new id 1 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2016): p2p0: New scan results, available
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2016): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2016): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2016): WPS: AP[1] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2016): p2p0: No suitable network found
D/wpa_supplicant( 2016): [LGE_WLAN]p2p scan delay set 250ms
D/wpa_supplicant( 2016): p2p0: Short-circuit new scan request since there are no enabled networks
D/wpa_supplicant( 2016): p2p0: State: DISCONNECTED -> INACTIVE
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2016): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2016): wlan0: nl80211: scan request
,D/wpa_supplicant( 2016): nl80211: Scan SSID - hexdump(len=0): [NULL],
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 2016): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2016): nl80211: Event message available
D/wpa_supplicant( 2016): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 2016): wlan0: nl80211: Scan trigger,
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 a0:c5:62:7a:49:97]
D/WifiMonitor(  955): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/WifiStateMachine(  955): handleMessage: E msg.what=147461
,D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
,D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
,D/WifiNative-wlan0(  955): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2016): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,W/WifiMonitor(  955): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  955): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  955): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 1 a0:c5:62:7a:49:97]
,D/WifiMonitor(  955): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
D/WifiP2pService(  955): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  955): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  955): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiMonitor(  955): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  955): Event [IFNAME=p2p0 CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  955): handleMessage: X
D/WifiP2pService(  955): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44e646a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  955): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44e646a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  955): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44e646a0 target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4000): onReceive
,D/AppUp4:CustFacade( 4000): Context : android.app.ReceiverRestrictedContext@42818358
D/AppUp4:CustFacade( 4000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4000): isOpenOperator : true
,D/AppUp4:CustFacade( 4000): isPhone : true
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 4000): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4000): begin check event
,I/AppUp4:CustModeStarterReceiver( 4000): Event For GoodConnectivity
,I/ActivityManager(  955): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=5868 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/HyLog   ( 5868): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5868): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5868): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1534): GC_CONCURRENT freed 1733K, 28% free 18005K/24832K, paused 33ms+7ms, total 142ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LGEmail ( 5868): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 5868): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,W/BaseRuntimeLoader( 5868): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5868): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5868): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5868): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 5868): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 5868): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 5868): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4341): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4341): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4341): networkInfo.isConnected() = false
,I/ActivityManager(  955): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5901 uid=10052 gids={50052, 3003}
,D/HyLog   ( 5901): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5901): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5901): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 5901): [loadRssi] File not exist 
V/LGRssiData( 5901): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5901): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 5901): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5901): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5901): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5901): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 5901): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5901): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5901): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 5901): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5901): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 5901): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5901): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  955): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5917 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  955): Killing 4831:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5917): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5917): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5917): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  955): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5930 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  955): Killing 4844:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm(  955): GC_EXPLICIT freed 2462K, 47% free 30650K/57536K, paused 5ms+14ms, total 171ms
D/HyLog   ( 5930): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5930): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5930): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/linker  ( 5868): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 5868): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 5868): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 5868): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 5868): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,D/HtmlEditor( 5868): register_HtmlEditor, Success
D/HtmlEditor( 5868): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 5868): register_HtmlEditorTimer, Success
D/HtmlEditor( 5868): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
,D/HtmlEditor( 5868): register_HtmlEditorDownloader, Success
D/HtmlEditor( 5868): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5868): register_HtmlEditorFont, Success
,D/HtmlEditor( 5868): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5868): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 5868): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5868): register_HtmlEditorDrawImage, Success
,D/HtmlEditor( 5868): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5868): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 5868): JNI_OnLoad Success
,D/LGDMClient( 2827): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/HubEmail( 5868): JNI_OnLoad()
,I/HubEmail( 5868): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5868): registerNatives()
I/HubEmail( 5868): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5868): registerNativeMethods()
,I/HubEmail( 5868): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 5868): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2827): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/ActivityManager(  955): Killing 4856:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  955): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5945 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm(  275): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
I/ActivityManager(  955): Killing 4924:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/HyLog   ( 5945): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5945): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5945): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
,D/LGDMSGCM( 5945): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,I/ActivityManager(  955): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5958 uid=10101 gids={50101, 1028, 1015, 3003}
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  955): Killing 5219:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/HyLog   ( 5958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5958): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,I/NFS     ( 5958): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5958): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 5958): intf.getDisplayName() = lo
I/Wireless_Storage( 5958): intf.getDisplayName() = sit0
,I/Wireless_Storage( 5958): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5958): intf.getDisplayName() = teql0
I/Wireless_Storage( 5958): intf.getDisplayName() = wlan0
I/Wireless_Storage( 5958): intf.getDisplayName() = rev_rmnet8
I/Wireless_Storage( 5958): intf.getDisplayName() = rev_rmnet2
I/Wireless_Storage( 5958): intf.getDisplayName() = rev_rmnet3
I/Wireless_Storage( 5958): intf.getDisplayName() = rev_rmnet4
I/Wireless_Storage( 5958): intf.getDisplayName() = rev_rmnet5
I/Wireless_Storage( 5958): intf.getDisplayName() = rev_rmnet6
I/Wireless_Storage( 5958): intf.getDisplayName() = rev_rmnet7
I/Wireless_Storage( 5958): intf.getDisplayName() = rev_rmnet0
I/Wireless_Storage( 5958): intf.getDisplayName() = rev_rmnet1
I/Wireless_Storage( 5958): intf.getDisplayName() = rmnet0
,I/Wireless_Storage( 5958): intf.getDisplayName() = rmnet1
I/Wireless_Storage( 5958): intf.getDisplayName() = rmnet2
I/Wireless_Storage( 5958): intf.getDisplayName() = rmnet3
I/Wireless_Storage( 5958): intf.getDisplayName() = rmnet4
I/Wireless_Storage( 5958): intf.getDisplayName() = rmnet5
I/Wireless_Storage( 5958): intf.getDisplayName() = rmnet6
I/Wireless_Storage( 5958): intf.getDisplayName() = rmnet7
,I/Wireless_Storage( 5958): CONNECT : WIFI_DISCONNECT
,I/ActivityManager(  955): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5970 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  955): Killing 5266:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5970): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5970): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5970): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 5970): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WebViewChromium( 5970): Binding Chromium to the main looper Looper (main, tid 1) {427fb030}
,I/chromium( 5970): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5970): Initializing chromium process, renderers=0
,W/chromium( 5970): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5970): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5970): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5970): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5970): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5970): Remote Branch: 
I/Adreno-EGL( 5970): Local Patches: 
I/Adreno-EGL( 5970): Reconstruct Branch: 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NSApplication( 5970): Starting up...
,I/ActivityManager(  955): Killing 5284:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/iu.Environment( 1963): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,I/iu.UploadsManager( 1963): num queued entries: 0
,I/iu.UploadsManager( 1963): num updated entries: 0
,I/iu.SyncManager( 1963): NEXT; no task
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2016): nl80211: Event message available
D/wpa_supplicant( 2016): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2016): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2016): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2016): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2016): nl80211: Survey data missing
D/wpa_supplicant( 2016): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 2016): wlan0: BSS: Add new id 13 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 2016): wlan0: New scan results available
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2016): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2016): WPS: AP[1] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2016): WPS: AP[2] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2016): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2016): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2016): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2016): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2016): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2016): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2016): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2016): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2016): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2016): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2016): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2016): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2016): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb875f5a8  current_ssid=0x0
D/wpa_supplicant( 2016): scard is not null..
D/wpa_supplicant( 2016): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2016): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2016): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2016): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2016): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2016): wlan0: Cancelling scan request
D/wpa_supplicant( 2016): wlan0: P2P: S,tation mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2016): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2016): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2016): RSN: PMKSA cache search - network_ctx=0xb875f5a8 try_opportunistic=0
D/wpa_supplicant( 2016): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2016): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2016): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2016): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2016): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2016): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2016): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2016): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2016): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2016): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2016): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2016): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2016): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2016): nl80211: Unsubscribe mgmt frames handle 0xb875e590 (mode change),
,D/wpa_supplicant( 2016): nl80211: Subscribe to mgmt frames with non-AP handle 0xb875e590
,D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590,
,D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 04 0a
,D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590,
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 04 0b,
,D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590,
,D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 04 0c,
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 c0:ff:d4:d3:aa:48],
,D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590,
,D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 04 0d,
,D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2016): nl80211: Register frame type=0xd0 nl_handle=0xb875e590
D/wpa_supplicant( 2016): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2016): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2016):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016):   * freq=2412
D/wpa_supplicant( 2016):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2016):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016):   * Auth Type 0
D/wpa_supplicant( 2016):   * WPA Versions 0x2
D/WifiMonitor(  955): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  955): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  955): handleMessage: E msg.what=147461
D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
,D/WifiNative-wlan0(  955): doString: BSS RANGE=0- MASK=0x21987,
D/wpa_supplicant( 2016): nl80211: Connect request send successfully
D/wpa_supplicant( 2016): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2016): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2016): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987',
D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
,D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): handleMessage: X
,D/wpa_supplicant( 2016): nl80211: Event message available
D/wpa_supplicant( 2016): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2016): nl80211: Connect event
D/wpa_supplicant( 2016): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2016): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2016): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2016): wlan0: Association info event
D/wpa_supplicant( 2016): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2016): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2016): wlan0: freq=2412 MHz
D/wpa_supplicant( 2016): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2016): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2016): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2016): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2016): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): scard is not null..
D/wpa_supplicant( 2016): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2016): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2016): TDLS: Remove peers on association
D/wpa_supplicant( 2016): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2016): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2016): EAPOL: enable timer tick
D/wpa_supplicant( 2016): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2016): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2016): wlan0: Cancelling scan request
,D/wpa_supplicant( 2016): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  955): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  955): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
,D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): handleMessage: X
,D/wpa_supplicant( 2016): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e9 b3 f2 27 ef ed 32 7a 3d 39 83 22 0f d6 83 ...
D/wpa_supplicant( 2016): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2016): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2016): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2016): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2016): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2016):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2016):   key_nonce - hexdump(len=32): e9 b3 f2 27 ef ed 32 7a 3d 39 83 22 0f d6 83 71 62 09 57 42 8a d5 83 37 24 82 57 a0 b3 bf 93 6a
D/wpa_supplicant( 2016):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e9 b3 f2 27 ef ed 32 7a 3d 39 83 22 0f d6 83 ...
D/wpa_supplicant( 2016): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2016): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2016): Get randomness: len=32 entropy=8
,D/wpa_supplicant( 2016): WPA: Renewed SNonce - hexdump(len=32): 56 ee 54 58 f4 b8 56 8d 96 41 9a c0 04 69 13 15 b4 18 d4 6d f3 a7 20 82 af 2f 81 98 f7 9b 43 e4
D/wpa_supplicant( 2016): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): WPA: Nonce1 - hexdump(len=32): 56 ee 54 58 f4 b8 56 8d 96 41 9a c0 04 69 13 15 b4 18 d4 6d f3 a7 20 82 af 2f 81 98 f7 9b 43 e4
D/wpa_supplicant( 2016): WPA: Nonce2 - hexdump(len=32): e9 b3 f2 27 ef ed 32 7a 3d 39 83 22 0f d6 83 71 62 09 57 42 8a d5 83 37 24 82 57 a0 b3 bf 93 6a
D/wpa_supplicant( 2016): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2016): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2016): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2016): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2016): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2016): WPA: Derived Key MIC - hexdump(len=16): f7 ff 8d 62 71 0b 4b e7 d6 17 56 48 42 4a dd ea
,D/wpa_supplicant( 2016): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 56 ee 54 58 f4 b8 56 8d 96 41 9a c0 04 69 13 ...
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  955): handleMessage: E msg.what=147462
,D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): handleMessage: X
,D/wpa_supplicant( 2016): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e9 b3 f2 27 ef ed 32 7a 3d 39 83 22 0f d6 83 ...
D/wpa_supplicant( 2016): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2016): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2016): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2016): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2016):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2016):   key_nonce - hexdump(len=32): e9 b3 f2 27 ef ed 32 7a 3d 39 83 22 0f d6 83 71 62 09 57 42 8a d5 83 37 24 82 57 a0 b3 bf 93 6a
D/wpa_supplicant( 2016):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016):   key_rsc - hexdump(len=8): ff 4e 00 00 00 00 00 00
D/wpa_supplicant( 2016):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2016):   key_mic - hexdump(len=16): b9 53 8a 92 ea a9 3e bd e7 cf 36 eb 4f 82 a6 0e
D/wpa_supplicant( 2016): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e9 b3 f2 27 ef ed 32 7a 3d 39 83 22 0f d6 83 ...
D/wpa_supplicant( 2016): RSN: encrypted key data - hexdump(len=56): 73 3e 5a 82 c5 2a bb 62 2f 51 fc 63 4c c8 ed 3f cf 0f 8b 80 09 3b 1f 6c d6 ba 3c f6 6d 23 72 7c ...
D/wpa_supplicant( 2016): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2016): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2016): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2016): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 1e 1b ...
D/wpa_supplicant( 2016): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2016): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2016): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2016): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2016): WPA: Derived Key MIC - hexdump(len=16): 5b 41 24 d5 b0 8f 9d fe 60 63 cf 99 0f d5 86 d5
D/wpa_supplicant( 2016): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2016): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb875ec54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2016):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2016): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2016): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2016): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2016): WPA: RSC - hexdump(len=6): ff 4e 00 00 00 00
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6efe03a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2016):    broadcast key
I/wpa_supplicant( 2016): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2016): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2016): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2016): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2016): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2016): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2016): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2016): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2016): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2016): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2016): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2016): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2016): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2016): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2016): EAPOL authentication completed successfully
D/wpa_supplicant( 2016): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2016): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2016): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: DisconnectedState
,D/WifiStateMachine(  955): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): handleMessage: X
,D/WifiMonitor(  955): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,W/WifiMonitor(  955): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  955): handleMessage: E msg.what=147459
,D/WifiStateMachine(  955): processMsg: DisconnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): Network connection established
,D/WifiNative-wlan0(  955): doString: STATUS
,D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2016): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  955):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  955): ssid=NG700
D/WifiNative-wlan0(  955): id=0
D/WifiNative-wlan0(  955): mode=station
D/WifiNative-wlan0(  955): pairwise_cipher=CCMP
D/WifiNative-wlan0(  955): group_cipher=CCMP
D/WifiNative-wlan0(  955): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  955): wpa_state=COMPLETED
D/WifiNative-wlan0(  955): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  955): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  955): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  955): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  955): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  955): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  955): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  955): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
,D/WifiStateMachine(  955): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  955): invokeEnterMethods: ObtainingIpState
,D/DhcpStateMachine(  955): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  955): WaitBeforeStartState
D/WifiStateMachine(  955): handleMessage: X
,D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-51ms what=147462 obj=android.net.wifi.StateChangeResult@42d86190 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): handleMessage: X
,D/WifiStateMachine(  955): handleMessage: E msg.what=147462
D/WifiStateMachine(  955): processMsg: ObtainingIpState
,D/WifiStateMachine(  955): ObtainingIpState{ when=-43ms what=147462 obj=android.net.wifi.StateChangeResult@42bd2fd0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=147459
,D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-43ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiStateMachine(  955): handleMessage: X
D/WifiStateMachine(  955): handleMessage: E msg.what=196612
,D/WifiStateMachine(  955): processMsg: ObtainingIpState
D/WifiStateMachine(  955): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  955): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,D/QRemote ( 5834): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5834): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  955):    returned true
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  955): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  955):    returned true
,D/WifiNative-wlan0(  955): doBoolean: SET ps 0
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2016): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2016): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2016): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  955):    returned true
,D/WifiNative-wlan0(  955): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  955):    returned null
E/WifiStateMachine(  955): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  955): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  955):    returned null
E/WifiStateMachine(  955): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  955): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  955): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring up wlan0
,D/WifiP2pService(  955): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431de410 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  955): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/DhcpStateMachine(  955): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  955): DHCP Start wake lock is acquired.
,D/WifiP2pService(  955): P2pEnabledState{ when=-14ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431de410 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  955): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  955): handleMessage: X
,D/WifiStateMachine(  955): handleMessage: E msg.what=131212
,D/WifiStateMachine(  955): processMsg: ObtainingIpState
,D/WifiStateMachine(  955): ObtainingIpState{ when=-17ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): processMsg: ConnectModeState
,D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  955): processMsg: SupplicantStartedState
,D/WifiStateMachine(  955): processMsg: DefaultState
,D/WifiStateMachine(  955): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  955): handleMessage: X
,D/WifiStateMachine(  955): handleMessage: E msg.what=196613
,D/WifiStateMachine(  955): processMsg: ObtainingIpState
,D/WifiStateMachine(  955): ObtainingIpState{ when=-15ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  955): processMsg: L2ConnectedState
D/WifiStateMachine(  955): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  955): doBoolean: DRIVER SETSUSPENDMODE 1
,D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  955):    returned true
,D/WifiNative-wlan0(  955): doBoolean: SET ps 1
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2016): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2016): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2016): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  955):    returned true
D/WifiP2pService(  955): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  955): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  955): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  955):    returned true
D/WifiStateMachine(  955): DHCP successful
D/WifiStateMachine(  955): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  955): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  955): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  955): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  955): VerifyingLinkState enter
,D/WifiStateMachine(  955): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  955): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
W/WifiStateTracker(  955): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  955): 
W/WifiStateTracker(  955):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  955):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
,E/Parcel  (  457): Reading a NULL string not supported here.
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  955): handleMessage: X
,D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=true
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
D/WifiStateMachine(  955): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/LocSvc_java(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
,D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiStateMachine(  955): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/QcConnectivityService(  955): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  955): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  955): handleInetConditionChange: no active default network - ignore
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
D/WifiStateMachine(  955): handleMessage: E msg.what=131092
D/WifiStateMachine(  955): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  955): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/GpsLocationProvider(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  955): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  955): transitionTo: destState=ConnectedState
D/WifiStateMachine(  955): handleMessage: new destination call exit/enter
D/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  955): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  955): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  955): handleMessage: X
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  955): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
E/Parcel  (  457): Reading a NULL string not supported here.
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  955): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QRemote ( 5834): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5834): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
E/ActivityThread(  955): Failed to find provider info for com.lge.ims.provisioning
,D/QRemote ( 5834): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5834): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/QcConnectivityService(  955): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  955): handleConnectivityChange: preConnState=2 connState=1
,I/PCSuite ( 5794): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5794): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  271): RouteController
,D/QRemote ( 5834): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5834): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5834): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5834): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,V/        (  271): RouteController
,D/DhcpStateMachine(  955): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  955): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,D/QCNEA   (  457): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  457): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  457): |CAC| updateNetCfgInfo
,V/QCNEA   (  457): |CAC| *********************************************
V/QCNEA   (  457): |CAC|                   Netconfig               
V/QCNEA   (  457): |CAC| *********************************************
V/QCNEA   (  457): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  457): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  457): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  457): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  457): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  457): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  457): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  457): |CAC| *********************************************
D/QCNEA   (  457): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  457): |CAC| net type = 1
V/QCNEA   (  457): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  457): |CAC| Received ssid= NG700
V/QCNEA   (  457): |CAC| 	ssid           =NG700
V/QCNEA   (  457): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  457): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  457): |CAC| *********************************************
D/QCNEA   (  457): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  457): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  457): |CAC| dispatchNetCfg: updating:0xb7a098dc
D/QCNEA   (  457): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
I/CheckinService( 1963): Checking schedule, now: 1450464092036 next: 1450463726703
I/CheckinService( 1963): active receiver: enabled
I/CheckinService( 1963): Preparing to send checkin request
I/EventLogService( 1963): Accumulating logs since 1450463694468
,I/CheckinRequestBuilder( 1963): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1963): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/CheckinRequestBuilder( 1963): awaiting user notification for token
,D/NotificationService(  955): updateLightListLocked :r=NotificationRecord(0x43218cb8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  955): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  955): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6072 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6072): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6072): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6072): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6072): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6072): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 6072): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6072): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6072): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 6072): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6072): install
,I/MultiDex( 6072): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6072): loading existing secondary dex files
,I/MultiDex( 6072): load found 3 secondary dex files
,I/MultiDex( 6072): install done
,D/dalvikvm( 6072): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6072): VFY: unable to resolve instance field 61
,D/dalvikvm( 6072): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6072): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6072): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6072): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 6072): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6072): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6072): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6072): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6072): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6072): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42802328
D/dalvikvm( 6072): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42802328
,D/dalvikvm( 6072): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42802328, skipping init
,D/dalvikvm( 6072): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42802328
D/dalvikvm( 6072): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42802328
,V/JNIHelp ( 6072): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 6072): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42802328
,D/dalvikvm( 6072): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42802328
D/dalvikvm( 6072): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42802328
,D/dalvikvm( 6072): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42802328
,I/ProviderInstaller( 6072): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1534): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1534): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1534): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1963): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1871): callingUid 10006, callindPid: 1871
,E/MDM     ( 1424): [73] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/dalvikvm( 6072): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6072): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6072): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1963): Restart initialization of location
I/dalvikvm( 6072): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6072): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6072): VFY: replacing opcode 0x6e at 0x0201
,D/wpa_supplicant( 2016): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2016): EAPOL: disable timer tick
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e3f000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e3f000
,D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
,D/dalvikvm( 1963): GC_CONCURRENT freed 1881K, 22% free 19574K/24832K, paused 6ms+13ms, total 84ms
D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=1282921611
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 6072): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a0ee90
,D/dalvikvm( 6072): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a0ee90
,D/dalvikvm( 6072): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a0ee90, skipping init
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  955): NetTransition Wakelock for ConnectedState released by timeout
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  277): PrepareKeyRequest: nonce=2263813523
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WifiStateMachine(  955): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  955): handleMessage: E msg.what=131212
D/WifiStateMachine(  955): processMsg: ConnectedState
D/WifiStateMachine(  955): processMsg: L2ConnectedState
,D/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiStateMachine(  955): processMsg: DriverStartedStateExt
D/WifiStateMachine(  955): processMsg: SupplicantStartedState
,D/WifiStateMachine(  955): processMsg: DefaultState
,D/WifiStateMachine(  955): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  955): send additional Connectivity Action
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  955): handleMessage: X
,D/LocSvc_java(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
,D/LocSvc_java(  955): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  955): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  955): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  955): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  955):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  955): Exception while trying to add src route: java.lang.NullPointerException
,D/GpsLocationProvider(  955): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  955): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1461): getPreferredApnId: subscription=0
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 6072): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 6072): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/DhcpStateMachine(  955): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  955): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  955): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  955): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  955): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  955): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  955): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  955): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  955): RunningState
,D/dalvikvm( 6135): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 6072): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6072): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 78ms
,I/Adreno-EGL( 6072): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6072): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6072): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6072): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6072): Remote Branch: 
I/Adreno-EGL( 6072): Local Patches: 
I/Adreno-EGL( 6072): Reconstruct Branch: 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 6072): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6072): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6072): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6072): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6072): Remote Branch: 
I/Adreno-EGL( 6072): Local Patches: 
I/Adreno-EGL( 6072): Reconstruct Branch: 
,I/Adreno-EGL( 6072): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6072): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6072): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6072): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6072): Remote Branch: 
I/Adreno-EGL( 6072): Local Patches: 
I/Adreno-EGL( 6072): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1963): Classify the device as Phone.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/NativeCrypto( 1963): SSL shutdown failed: ssl=0x6b3af7b8: I/O error during system call, Connection timed out
,I/GAV2    ( 5970): Thread[GAThread,5,main]: No campaign data found.
,V/NativeCrypto( 1963): SSL shutdown failed: ssl=0x6b392b58: I/O error during system call, Connection timed out
,I/CheckinTask( 1963): Sending checkin request (11469 bytes)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  955): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  955): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4000): onReceive
,D/AppUp4:CustFacade( 4000): Context : android.app.ReceiverRestrictedContext@42818358
,D/AppUp4:CustFacade( 4000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4000): isOpenOperator : true
,D/AppUp4:CustFacade( 4000): isPhone : true
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 4000): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4000): begin check event
,I/AppUp4:CustModeStarterReceiver( 4000): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4000): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4000): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4000): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4000): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4000): handleAsyncCustNotification do not startCustService
,D/EAS     ( 5868): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4256): DownloadService onCreate
,D/EAS     ( 5868): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 5868): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4341): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4341): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4341): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 5901): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5901): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2827): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5945): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5958): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5958): CONNECT : WIFI_CONNECT
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  955): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  955): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/DownloadManager( 4256): in removeSpuriousFiles
,V/DownloadManager( 4256): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGDMClient( 2827): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2827): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@4286f2e0 on behalf of 4256
V/DownloadManager( 4256): DownloadService onStartCommand
V/DownloadManager( 4256): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4256): in trimDatabase
V/DownloadManager( 4256): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/Settings( 5868): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 2827): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2827): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@428728b0 on behalf of 4256
D/LGDMClient( 2827): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2827): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@42872ed8 on behalf of 4256
,V/DownloadManager( 4256): DownloadService onDestroy
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/iu.Environment( 1963): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1963): num queued entries: 0
,I/iu.UploadsManager( 1963): num updated entries: 0
,I/iu.SyncManager( 1963): NEXT; no task
I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4000): onReceive
,D/AppUp4:CustFacade( 4000): Context : android.app.ReceiverRestrictedContext@42818358
D/AppUp4:CustFacade( 4000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4000): isOpenOperator : true
,D/AppUp4:CustFacade( 4000): isPhone : true
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 4000): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4000): begin check event
,I/AppUp4:CustModeStarterReceiver( 4000): Event For GoodConnectivity, noConnectivity : false, but skip! 
,I/CheckinRequestBuilder( 1963): Checkin reason type: 8 attempt count: 1
,V/DownloadManager( 4256): DownloadService onCreate
,I/DownloadManager( 4256): in removeSpuriousFiles
D/EAS     ( 5868): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 5868): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4256): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,E/ActivityThread( 1963): Failed to find provider info for com.google.android.wearable.settings
V/DownloadManager( 4256): DownloadService onStartCommand
V/DownloadManager( 4256): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@42879470 on behalf of 4256
V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@42879a68 on behalf of 4256
I/LgeMiscReceiver( 4341): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4341): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4341): networkInfo.isConnected() = true
D/PhoneState( 4341): setPdpRejectCasuse : false
I/DownloadManager( 4256): in trimDatabase
V/DownloadManager( 4256): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/Settings( 5868): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 5901): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5901): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@4287af10 on behalf of 4256
,D/LGDMClient( 2827): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4256): DownloadService onDestroy
,D/LGDMClient( 2827): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5945): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2827): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 5958): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5958): CONNECT : WIFI_CONNECT
W/ContextImpl( 5945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2827): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2827): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2827): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2827): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm(  955): GC_EXPLICIT freed 1999K, 47% free 30561K/57536K, paused 3ms+7ms, total 93ms
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,D/GCM     ( 1534): Connected
,W/CheckinRequestBuilder( 1963): awaiting user notification for token
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/NotificationService(  955): updateLightListLocked :r=NotificationRecord(0x4318ad30: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  955): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1534): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CheckinRequestBuilder( 1963): Classify the device as Phone.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1963): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1963): Checking schedule, now: 1450464095415 next: 1451041491411
,I/CheckinService( 1963): active receiver: disabled
,I/CheckinService( 1963): Checking schedule, now: 1450464095446 next: 1451041491411
,I/CheckinService( 1963): active receiver: disabled
,D/GCM     ( 1534): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  955): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  955): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  955): DelayedCaptiveCheckState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464096148907833; DSPS: 17076702; Offset: 1450463575009320431
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4000): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4000): onReceive
,D/AppUp4:CustFacade( 4000): Context : android.app.ReceiverRestrictedContext@42818358
D/AppUp4:CustFacade( 4000): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4000): isOpenOperator : true
,D/AppUp4:CustFacade( 4000): isPhone : true
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 4000): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4000): begin check event
,I/AppUp4:CustModeStarterReceiver( 4000): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 5868): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4256): DownloadService onCreate
,D/EAS     ( 5868): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4341): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4341): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4341): networkInfo.isConnected() = true
,D/PhoneState( 4341): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5901): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5901): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2827): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5945): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5958): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5958): CONNECT : WIFI_CONNECT
,W/Settings( 5868): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/DownloadManager( 4256): in removeSpuriousFiles
,V/DownloadManager( 4256): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@4287eff0 on behalf of 4256
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 4256): in trimDatabase
,V/DownloadManager( 4256): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@428802e0 on behalf of 4256
,V/DownloadManager( 4256): DownloadService onStartCommand
V/DownloadManager( 4256): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2827): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 4256): created cursor android.database.sqlite.SQLiteCursor@42882bb0 on behalf of 4256
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LGDMClient( 2827): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 4256): DownloadService onDestroy
,E/LGDMClient( 2827): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2827): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2827): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2827): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  955): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/WifiServiceExtension(  955): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  955): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  955): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/ActivityManager(  955): Killing 5141:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1500): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1500): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1500): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  955): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3731): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3731): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  955): Handling package changes for user 0
,I/ActivityManager(  955): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6246 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/[LGHome]Launcher( 1500): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
W/ActivityManager(  955): getAssistContextExtras failed: no resumed activity
W/ActivityManager(  955): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "sms"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "smsto"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "mms"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 6246): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6246): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6246): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  955):   Scheme: "mmsto"
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "sms"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "smsto"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "mms"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  955):   Action: "android.intent.action.SENDTO"
I/PackageManager(  955):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  955):   Scheme: "mmsto"
I/PackageManager(  955): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 6246): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6246): MmsConfig.loadMmsSettings
I/Babel   ( 6246): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6246): MmsConfig.loadFromDatabase
,I/MediaCodecList( 6246): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 6246): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 6246): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6246): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 6246): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6246): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6246): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6246): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 6246): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6246): MmsConfig.loadFromResources
E/Babel   ( 6246): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6246): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 6246): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[LGHome]EVENT( 1500): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1424): DISABLE
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  955): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6246): [loadRssi] File not exist 
V/LGRssiData( 6246): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6246): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 6246): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6246): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6246): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4000): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4000): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4000): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4000): onReceive
D/AppUp4:CustFacade( 4000): Context : android.app.ReceiverRestrictedContext@42818358
D/AppUp4:CustFacade( 4000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4000): isOpenOperator : true
,D/AppUp4:CustFacade( 4000): isPhone : true
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 4000): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4000): begin check event
D/AppUp4:Utils( 4000): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4000): Event For Nothing, skip.
,D/LocationProviderProxy(  955): applying state to connected service
,D/LocationProviderProxy(  955): applying state to connected service
,I/ActivityManager(  955): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6295 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 6295): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6295): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6295): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6295): BUILD Country: EU
,I/SystemConfig( 6295): BUILD Operator: OPEN
I/SystemConfig( 6295): systemFeature RCS result false
,D/SystemConfig( 6295): refreshRcsSupport() :false
I/ActivityManager(  955): Killing 5794:com.lge.sync/1000 (adj 15): empty #17
I/ActivityManager(  955): Killing 5834:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  955): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6309 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6309): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6309): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6309): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2649): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  955): Killing 4256:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  955): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6326 uid=10050 gids={50050, 3003, 1028, 1015}
I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6326): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6326): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6326): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6326): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6326): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6326): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6326): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6326): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 6326): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6326): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6326): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6326): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6326): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6326): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6326): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6326): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6326): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/IcingCorporaProvider( 2649): UpdateCorporaTask done [took 247 ms] updated apps [took 247 ms] 
,I/dalvikvm( 6326): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6326): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6326): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 6326): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 6326): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6326): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6326): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6326): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6326): VFY: replacing opcode 0x6e at 0x029a
,I/ActivityManager(  955): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6360 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/dalvikvm( 6326): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 6326): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6326): VFY: replacing opcode 0x6e at 0x001a
,D/HyLog   ( 6360): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6360): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6360): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 6326): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 6326): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6326): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6326): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6326): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1963): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1963): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 6360): DownloadService onCreate
,I/DownloadManager( 6360): in removeSpuriousFiles
,V/DownloadManager( 6360): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6360): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6360): created cursor android.database.sqlite.SQLiteCursor@42841a60 on behalf of 6360
,V/DownloadManager( 6360): created cursor android.database.sqlite.SQLiteCursor@42844db0 on behalf of 6326
,I/DownloadManager( 6360): in trimDatabase
,V/DownloadManager( 6360): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6360): created cursor android.database.sqlite.SQLiteCursor@42847618 on behalf of 6360
,D/Finsky  ( 6326): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 6360): DownloadService onStartCommand
,V/DownloadManager( 6360): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6360): created cursor android.database.sqlite.SQLiteCursor@4284b6e0 on behalf of 6360
,D/Finsky  ( 6326): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/DownloadManager( 6360): DownloadService onDestroy
I/ActivityManager(  955): Killing 5868:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6326): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6326): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6326): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6326): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6326): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/dalvikvm(  955): GC_EXPLICIT freed 2172K, 47% free 30675K/57536K, paused 4ms+11ms, total 153ms
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1534): GC_EXPLICIT freed 1155K, 28% free 17998K/24832K, paused 2ms+4ms, total 42ms
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Finsky  ( 6326): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6326): Total arena pages for JIT: 11
,I/dalvikvm( 6326): Total arena pages for JIT: 12
I/dalvikvm( 6326): Total arena pages for JIT: 13
,I/dalvikvm( 6326): Total arena pages for JIT: 14
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6326): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6326): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6326): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6326): [1] DailyHygiene.reschedule: Scheduling new run in 265 minutes (failures=4),
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,D/CaptivePortalTracker(  955): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  955): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  955): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/CaptivePortalTracker(  955): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  955): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  955): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  955): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  955): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GAV4    ( 6246): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  955): Killing 5901:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  955): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bd7068 stackId=0, 1 tasks}
,D/ActivityManager(  955): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464116150364244; DSPS: 17732109; Offset: 1450463575009342516
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6326): [510] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6326): [1] 5.onFinished: Installation state replication succeeded.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464120031, nextTick: 60001, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464120049, nextTick: 59983, mDrawingTime: 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464136150820743; DSPS: 18387484; Offset: 1450463575009341251
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464156151743300; DSPS: 19042874; Offset: 1450463575009348281
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464176152171151; DSPS: 19698248; Offset: 1450463575009348886
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464180050, nextTick: 59980, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464180053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464196153115225; DSPS: 20353639; Offset: 1450463575009346915
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464216154020774; DSPS: 21009029; Offset: 1450463575009336937
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464236154462231; DSPS: 21664404; Offset: 1450463575009320630
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464240050, nextTick: 59972, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464240058, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464256154930502; DSPS: 22319779; Offset: 1450463575009331137
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464276155820585; DSPS: 22975168; Offset: 1450463575009336210
,D/wpa_supplicant( 2016): wlan0: BSS: Remove id 11 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): wlan0: BSS: Remove id 12 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): p2p0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2016): p2p0: BSS: Remove id 1 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2016): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 a0:c5:62:7a:49:97]
D/WifiMonitor(  955): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  955): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 1 a0:c5:62:7a:49:97]
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464296156263389; DSPS: 23630543; Offset: 1450463575009321251
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464300040, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464300042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464316157631459; DSPS: 24285947; Offset: 1450463575009346547
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464336158538600; DSPS: 24941337; Offset: 1450463575009338161
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464356160390424; DSPS: 25596758; Offset: 1450463575009328413
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464360043, nextTick: 59971, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464360055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464376169753006; DSPS: 26252425; Offset: 1450463575009322098
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464396170216681; DSPS: 26907800; Offset: 1450463575009328010
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  955): updateLightListLocked :r=NotificationRecord(0x431768d8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1534): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1534): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1534): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1534): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1534): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1534): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1534): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1534): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  955): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 6326): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6326): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6326): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6326): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6326): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6326): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6326): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6326): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 6326): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6326): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464416170672781; DSPS: 27563175; Offset: 1450463575009326346
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464420042, nextTick: 59974, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464420052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464436171127073; DSPS: 28218550; Offset: 1450463575009322874
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464456172974578; DSPS: 28873970; Offset: 1450463575009339325
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464476173877262; DSPS: 29529360; Offset: 1450463575009326481
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464480045, nextTick: 59972, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464480054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464496174326861; DSPS: 30184734; Offset: 1450463575009348834
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464516174779528; DSPS: 30840109; Offset: 1450463575009343737
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464536175225105; DSPS: 31495484; Offset: 1450463575009331551
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464540035, nextTick: 59990, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464540038, nextTick: 59993, mDrawingTime: 1
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  955): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,W/Settings(  955): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  955): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1473): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1473): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1473): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1473): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464556175682502; DSPS: 32150859; Offset: 1450463575009331184
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464576176133186; DSPS: 32806234; Offset: 1450463575009324104
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464596181217787; DSPS: 33461760; Offset: 1450463575009342787
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464600055, nextTick: 59973, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464600057, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464616182145652; DSPS: 34117151; Offset: 1450463575009324608
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464636182597214; DSPS: 34772525; Offset: 1450463575009348923
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464656183044701; DSPS: 35427900; Offset: 1450463575009338647
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464660040, nextTick: 59989, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464660042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464676183992552; DSPS: 36083291; Offset: 1450463575009340453
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464696184434974; DSPS: 36738666; Offset: 1450463575009325111
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464716184868262; DSPS: 37394040; Offset: 1450463575009331153
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464720042, nextTick: 59980, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464720050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464736185322483; DSPS: 38049415; Offset: 1450463575009327610
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464756186265527; DSPS: 38704806; Offset: 1450463575009324610
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464776186691603; DSPS: 39360180; Offset: 1450463575009323439
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464780039, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464780042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464796187619122; DSPS: 40015570; Offset: 1450463575009335431
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464816188583799; DSPS: 40670962; Offset: 1450463575009323546
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464836189006692; DSPS: 41326335; Offset: 1450463575009349710
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464840030, nextTick: 59999, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464840053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464856190541444; DSPS: 41981746; Offset: 1450463575009328066
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464876191462077; DSPS: 42637136; Offset: 1450463575009333171
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464896191909924; DSPS: 43292511; Offset: 1450463575009323255
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464900041, nextTick: 59976, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464900052, nextTick: 59979, mDrawingTime: 1,
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464916192851169; DSPS: 43947902; Offset: 1450463575009318455
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464936193769410; DSPS: 44603292; Offset: 1450463575009321168
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464956194224978; DSPS: 45258667; Offset: 1450463575009318973
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464960027, nextTick: 59999, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450464960050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464976195178874; DSPS: 45914058; Offset: 1450463575009326824
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  955): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  955): Done.
,D/QcConnectivityService(  955): Setting timer for 720seconds
,D/GCM     ( 1534): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  955): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  955): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450464996195658533; DSPS: 46569433; Offset: 1450463575009348719
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465016196543842; DSPS: 47224823; Offset: 1450463575009318501
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465020045, nextTick: 59976, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465020052, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465036197981309; DSPS: 47880230; Offset: 1450463575009321642
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465056199931388; DSPS: 48535654; Offset: 1450463575009318596
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465076200187188; DSPS: 49191022; Offset: 1450463575009330255
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465080047, nextTick: 59981, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465080050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465096201616452; DSPS: 49846429; Offset: 1450463575009325193
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465116202537050; DSPS: 50501819; Offset: 1450463575009330263
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465136202958426; DSPS: 51157193; Offset: 1450463575009324393
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465140043, nextTick: 59977, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465140052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465156204355526; DSPS: 51812599; Offset: 1450463575009317685
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465176205287436; DSPS: 52467989; Offset: 1450463575009334067
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465196206146423; DSPS: 53123377; Offset: 1450463575009338562
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465200040, nextTick: 59974, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465200052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465216207062202; DSPS: 53778767; Offset: 1450463575009338814
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465236208037685; DSPS: 54434159; Offset: 1450463575009337734
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465256208906203; DSPS: 55089548; Offset: 1450463575009321243
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465260038, nextTick: 59970, mDrawingTime: 11
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465260053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465276210865802; DSPS: 55744972; Offset: 1450463575009327717
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465296211750321; DSPS: 56400361; Offset: 1450463575009327226
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465316212215018; DSPS: 57055736; Offset: 1450463575009334159
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465320029, nextTick: 59994, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465320057, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465336213128776; DSPS: 57711126; Offset: 1450463575009332390
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465356214037726; DSPS: 58366516; Offset: 1450463575009325812
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465376214477700; DSPS: 59021890; Offset: 1450463575009338540
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465380042, nextTick: 59976, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465380050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465396215881104; DSPS: 59677296; Offset: 1450463575009338136
,I/ProcessStatsService(  955): Prepared write state in 19ms
,I/ProcessStatsService(  955): Prepared write state in 28ms
,D/LocationManagerService(  955): getAllProviders()=[passive, gps, network]
,I/ProcessStatsService(  955): Pruning old procstats: /data/system/procstats/state-2015-12-18-06-56-00.bin
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1963): Aggregate from 1450464092071 (log), 1450463603363 (data)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465416217259528; DSPS: 60332701; Offset: 1450463575009343269
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465436217687137; DSPS: 60988075; Offset: 1450463575009343632
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465440040, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465440045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465456218695674; DSPS: 61643468; Offset: 1450463575009345089
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465476220315882; DSPS: 62298881; Offset: 1450463575009347865
,D/qcom_sensors_hal(  955): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  955): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  955): hal_ts_offset_is: Apps: 1450465496220741935; DSPS: 62954255; Offset: 1450463575009346672
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465500032, nextTick: 59996, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450465500035, nextTick: 59996, mDrawingTime: 1
,TIME-OUT KILL (timeout was 1800000ms)
```
