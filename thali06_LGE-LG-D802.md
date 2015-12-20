#### Test 50650278bb431e6_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/wpa_supplicant( 2022): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
I/ConfigFetchService( 1874): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1874): launchTask
W/dalvikvm( 1874): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/ConfigFetchTask( 1874): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XHx4UKKY7IJGO9REgZwSzEh1WkbQAVM5BJpre2PvIFF9qV0LxguHUWeyGXclHTK6n8-xb377bkmeX1qtdWuF999XKCWOm6mYTiv6Bni-xqMvK2OH890QoiEXhQocQLrflWzYulRzn_4xmYgEvOEgaOHfCLVDOvp2pA7fiRwUBujdumsJUR7ZAMwaHDHDikePcWUfxE
I/GoogleURLConnFactory( 1874): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1874): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1874): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1874): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1874): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1874): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1874): No vision deps
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/BaseAppContext( 1874): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1874): CP2 sync disabled
I/dalvikvm( 1874): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1874): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1874): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1874): Using Auth Proxy for data requests.
,W/BaseAppContext( 1874): Using Auth Proxy for data requests.
W/BaseAppContext( 1874): Using Auth Proxy for data requests.
W/BaseAppContext( 1874): Using Auth Proxy for data requests.
W/BaseAppContext( 1874): Using Auth Proxy for data requests.
W/GAV2    ( 4686): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  967): Killing 4119:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{432ab6c0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
D/dalvikvm( 1874): GC_CONCURRENT freed 1675K, 22% free 19417K/24832K, paused 3ms+3ms, total 37ms
D/dalvikvm( 1874): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 1874): WAIT_FOR_CONCURRENT_GC blocked 17ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/HeadsetStateMachine( 1225): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4735): 
D/AndroidRuntime( 4735): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4735): CheckJNI is OFF
D/dalvikvm( 4735): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4735): Added shared lib libjavacore.so 0x0
I/ConfigFetchService( 1874): fetch service done; releasing wakelock
I/ConfigFetchService( 1874): stopping self
D/dalvikvm( 4735): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4735): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4735): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4735): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/ChimeraCfgMgr( 1874): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1874): Module APK com.google.android.play.games already loaded
E/memtrack( 4735): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4735): failed to load memtrack module: -2
D/AndroidRuntime( 4735): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4735
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (121 us)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{432ab6c0 u0 com.android.settings/.UsbSettings t2}
I/Icing   ( 1874): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{432dc7a0 stackId=1, 2 tasks}
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{432ab6c0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/UsbSettingsControl( 2628): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2628): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4735): Shutting down VM
I/SlideAside( 4085): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4735): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 4085): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4085): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{432ab6c0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4760 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/Icing   ( 1874): Loaded CLD2 Version V2.0 - 20141016
D/HyLog   ( 4760): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4760): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4760): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4760): Binding Chromium to the background looper Looper (main, tid 1) {42810c60}
I/chromium( 4760): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4760): Initializing chromium process, renderers=0
I/Icing   ( 1874): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
W/chromium( 4760): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4760): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4760): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4760): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4760): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4760): Remote Branch: 
I/Adreno-EGL( 4760): Local Patches: 
I/Adreno-EGL( 4760): Reconstruct Branch: 
I/dalvikvm( 4760): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4760): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4760): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4760): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4760): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4760): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4760): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4760): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4760): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4760): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4760): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4760): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4760): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4760): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4760): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4760): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4760): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4760): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4760): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4760): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4760): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4760): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4760): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4760): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4760): Enabling debug mode 0
W/AwContents( 4760): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +326ms
I/InputMethodManagerService(  967): IME STATUS OFF
W/AwContents( 4760): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 4760): Timeline: Activity_idle id: android.os.BinderProxy@42812430 time:118385
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/JsMessageQueue( 4760): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4760): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42818800
D/dalvikvm( 4760): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42818800
D/jxcore_app_log( 4760): JniHelper::setJavaVM(0x416dd838), pthread_self() = 1630806728
D/JX-Cordova( 4760): jxcore cordova android initializing
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3} time:118789
D/ActivityManager(  967): no-history finish of ActivityRecord{432ab6c0 u0 com.android.settings/.UsbSettings t2}
D/UsbSettings( 2628): [AUTORUN] onStop()
V/ActivityManager(  967): Finishing activity token=Token{431c86a0 ActivityRecord{432ab6c0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{432ab6c0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{432ab6c0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{432ab6c0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4760): GC_CONCURRENT freed 2816K, 13% free 21836K/24832K, paused 3ms+3ms, total 48ms
,D/dalvikvm( 4760): GC_FOR_ALLOC freed 155K, 13% free 21847K/24832K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4760): Grow heap (frag case) to 23.601MB for 96598-byte allocation
,D/dalvikvm( 4760): GC_FOR_ALLOC freed 199K, 13% free 21863K/24928K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4760): Grow heap (frag case) to 23.663MB for 144892-byte allocation
,D/dalvikvm( 4760): GC_FOR_ALLOC freed 257K, 13% free 21907K/25072K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4760): Grow heap (frag case) to 23.775MB for 217334-byte allocation
,D/dalvikvm( 4760): GC_FOR_ALLOC freed 374K, 14% free 21978K/25288K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4760): Grow heap (frag case) to 23.947MB for 325996-byte allocation
,D/dalvikvm( 4760): GC_FOR_ALLOC freed 571K, 14% free 22099K/25608K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4760): Grow heap (frag case) to 24.221MB for 488990-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4760): GC_FOR_ALLOC freed 870K, 15% free 22276K/26088K, paused 24ms, total 24ms
,D/dalvikvm( 4760): GC_FOR_ALLOC freed 1290K, 14% free 22534K/26088K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4760): Grow heap (frag case) to 25.228MB for 1100216-byte allocation
,D/dalvikvm( 4760): GC_CONCURRENT freed 1807K, 16% free 22924K/27164K, paused 2ms+2ms, total 37ms
,D/dalvikvm( 4760): GC_FOR_ALLOC freed 262K, 16% free 22846K/27164K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4760): Grow heap (frag case) to 26.058MB for 1650320-byte allocation
,D/dalvikvm( 4760): GC_CONCURRENT freed 1613K, 19% free 23428K/28776K, paused 1ms+3ms, total 29ms
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4760): GC_FOR_ALLOC freed 1431K, 19% free 23521K/28776K, paused 26ms, total 28ms
,I/dalvikvm-heap( 4760): Grow heap (frag case) to 27.504MB for 2475476-byte allocation
,D/dalvikvm( 4760): GC_CONCURRENT freed 270K, 18% free 25813K/31196K, paused 1ms+3ms, total 28ms
,D/dalvikvm( 4760): GC_CONCURRENT freed 4351K, 22% free 24493K/31196K, paused 2ms+4ms, total 41ms
,D/dalvikvm( 4760): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/dalvikvm-heap( 4760): Grow heap (frag case) to 29.634MB for 3713210-byte allocation
,D/dalvikvm( 4760): GC_CONCURRENT freed 2688K, 27% free 25619K/34824K, paused 2ms+4ms, total 37ms
,D/dalvikvm( 4760): GC_FOR_ALLOC freed 770K, 27% free 25438K/34824K, paused 31ms, total 31ms
,W/jxcore-log( 4760): Initializing JXcore engine
,W/jxcore-log( 4760): JXcore engine is ready
,D/dalvikvm( 4760): GC_CONCURRENT freed 359K, 20% free 28067K/34824K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 4760): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/jxcore-log( 4760): Starting JXcore engine
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,W/jxcore-log( 4760): Platform android
W/jxcore-log( 4760): 
,W/jxcore-log( 4760): Process ARCH arm
W/jxcore-log( 4760): 
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4760): JXcore Cordova bridge is ready!
I/jxcore-log( 4760): 
,W/jxcore-log( 4760): JXcore engine is started
,I/chromium( 4760): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4760): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4760): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1225): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/jxcore-log( 4760): Toggling radios to true
I/jxcore-log( 4760): 
,D/BluetoothManagerService(  967): Message: 20
D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@449b2910:true
,D/BluetoothAdapter( 4760): enable(): BT is already enabled..!
,D/WifiStateMachine(  967): handleMessage: E msg.what=131145
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doBoolean: DISCONNECT
,I/jxcore-log( 4760): Radios toggled
I/jxcore-log( 4760): 
D/WifiService(  967): New client listening to asynchronous messages
D/WifiService(  967): setWifiEnabled: true pid=4760, uid=10304
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  967): disconnect pid=4760, uid=10304
,D/WifiService(  967): reconnect pid=4760, uid=10304
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2022): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2022): wlan0: Cancelling scan request
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2022): TDLS: Tear down peers
D/wpa_supplicant( 2022): wpa_driver_nl80211_disconnect(reason_code=3)
D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4760): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4760): 
I/jxcore-log( 4760): Perf Test app loaded loaded
I/jxcore-log( 4760): 
,I/Choreographer( 4760): Skipped 59 frames!  The application may be doing too much work on its main thread.
D/wpa_supplicant( 2022): wlan0: Event DEAUTH (12) received
,D/wpa_supplicant( 2022): wlan0: Deauthentication notification
D/wpa_supplicant( 2022): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2022): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2022): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2022): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2022): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2022): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7902d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5
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
,D/wpa_supplicant( 2022): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
W/Settings(  967): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131146
D/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiNative-wlan0(  967): doBoolean: RECONNECT
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2022): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2022): Fast associate: Old scan results
D/wpa_supplicant( 2022): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2022): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2022): wlan0: nl80211: scan request
D/wpa_supplicant( 2022): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2022): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2022): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147460
D/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection lost
D/WifiStateMachine(  967): Stopping DHCP and clearing IP
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
,D/DhcpStateMachine(  967): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  967): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
I/jxcore-log( 4760): check test folder
I/jxcore-log( 4760): 
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
I/jxcore-log( 4760): found test : ./testFindPeers.js
I/jxcore-log( 4760): 
,D/WifiStateMachine(  967): handleMessage: X
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiHS20(  967): hidePasspointNotification off =false
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
D/QCNEA   (  477): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  477): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  477): |CAC| updateNetCfgInfo
V/QCNEA   (  477): |CAC| *********************************************
V/QCNEA   (  477): |CAC|                   Netconfig               
V/QCNEA   (  477): |CAC| *********************************************
V/QCNEA   (  477): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  477): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  477): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  477): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  477): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  477): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  477): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  477): |CAC| *********************************************
D/QCNEA   (  477): |CAC| Received bssid= 
D/QCNEA   (  477): |CAC| net type = 3
V/QCNEA   (  477): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  477): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  477): |CAC| 	ssid           =NG700
V/QCNEA   (  477): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  477): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  477): |CAC| *********************************************
D/QCNEA   (  477): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  477): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  477): |CAC| dispatchNetCfg: updating:0xb77eb8dc
D/QCNEA   (  477): |CAC| readCallback: read len:0, ret:-1, errno:11
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
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
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  967): Attempting to switch to mobile
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4827 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
V/        (  264): RouteController
I/jxcore-log( 4760): found test : ./testSendData.js
I/jxcore-log( 4760): 
V/        (  264): RouteController
D/HyLog   ( 4827): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4827): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4827): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/GAV2    ( 4686): Thread[GAThread,5,main]: No campaign data found.
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 4827): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 4827): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4827): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
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
,D/NetUtils(  967): android_net_utils_resetConnections in env=0x62946a60 clazz=0x6d200001 iface=wlan0 mask=0x3
,I/jxcore-log( 4760): found test : ./testSendData2.js
I/jxcore-log( 4760): 
,E/jxcore  ( 4760): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 4760): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/chromium( 4760): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
,V/NativeCrypto( 1552): Read error: ssl=0x63aad6a0: I/O error during system call, Connection timed out
I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4856 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  967): Killing 4220:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
,V/NativeCrypto( 1552): SSL shutdown failed: ssl=0x63aad6a0: I/O error during system call, Broken pipe
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4856): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4856): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4856): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/QRemote ( 4856): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 4856): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4856): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4856): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4856): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4856): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4856): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4856): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4856): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  967): Killing 2174:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  967): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1552): onDestroy
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.476151 Y: -0.395981 Z: 9.751587 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.476151 .y:-0.395981 .z:9.751587
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.474350 Y: -0.383240 Z: 9.742493 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.474350 .y:-0.383240 .z:9.742493
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] connect :false
,D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2022): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2022): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2022): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 2022): nl80211: Survey data missing
D/wpa_supplicant( 2022): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 6 BSSID 34:36:3b:bd:89:28 SSID 'andilabs'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 7 BSSID 06:7c:34:11:b3:cb SSID 'UPC Wi-Free'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 8 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 2022): wlan0: New scan results available
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2022): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2022): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2022): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2022): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2022): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2022): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2022): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59
D/wpa_supplicant( 2022): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2022): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-65 wps
D/wpa_supplicant( 2022): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2022): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2022): wlan0: Con,sidering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb79045a8  current_ssid=0x0
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
D/wpa_supplicant( 2022): RSN: PMKSA cache search - network_ctx=0xb79045a8 try_opportunistic=0
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
D/wpa_supplicant( 2022): nl80211: Unsubscribe mgmt frames handle 0xb7903590 (mode change)
D/wpa_supplicant( 2022): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7903590
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7903590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7903590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7903590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7903590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7903590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7903590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7903590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7903590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7903590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7903590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2022): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2022):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022):   * freq=2412
D/wpa_supplicant( 2022):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2022):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022):   * Auth Type 0
D/wpa_supplicant( 2022):   * WPA Versions 0x2
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 a0:c5:62:7a:49:97]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 34:36:3b:bd:89:28]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 06:7c:34:11:b3:cb]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 44:e9:dd:10:c0:ad]
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
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
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
,D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2022): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
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
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/wpa_supplicant( 2022): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c8 cf d1 4a 2e 48 29 dc 44 54 ce 90 85 c1 e0 ...
D/wpa_supplicant( 2022): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2022): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2022): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2022): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2022): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2022):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2022):   key_nonce - hexdump(len=32): c8 cf d1 4a 2e 48 29 dc 44 54 ce 90 85 c1 e0 83 bb e4 56 53 82 44 3a 04 98 13 24 71 a2 c3 71 4c
D/wpa_supplicant( 2022):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c8 cf d1 4a 2e 48 29 dc 44 54 ce 90 85 c1 e0 ...
D/wpa_supplicant( 2022): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2022): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2022): Get randomness: len=32 entropy=10
D/wpa_supplicant( 2022): WPA: Renewed SNonce - hexdump(len=32): 84 4e 27 19 08 5d 8b e0 eb 04 e6 3f 32 34 99 a5 fc 31 f2 7a d1 0b c3 b1 ac d9 ee 95 6a c3 73 95
D/wpa_supplicant( 2022): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): WPA: Nonce1 - hexdump(len=32): 84 4e 27 19 08 5d 8b e0 eb 04 e6 3f 32 34 99 a5 fc 31 f2 7a d1 0b c3 b1 ac d9 ee 95 6a c3 73 95
D/wpa_supplicant( 2022): WPA: Nonce2 - hexdump(len=32): c8 cf d1 4a 2e 48 29 dc 44 54 ce 90 85 c1 e0 83 bb e4 56 53 82 44 3a 04 98 13 24 71 a2 c3 71 4c
D/wpa_supplicant( 2022): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2022): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2022): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2022): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2022): WPA: KCK - hexdump(len=16): [REMOVED]
,D/wpa_supplicant( 2022): WPA: Derived Key MIC - hexdump(len=16): 09 73 d0 a3 2f e2 bd c8 42 0e 8f cf 98 1c 5c b8
D/wpa_supplicant( 2022): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 84 4e 27 19 08 5d 8b e0 eb 04 e6 3f 32 34 99 ...,
W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2022): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c8 cf d1 4a 2e 48 29 dc 44 54 ce 90 85 c1 e0 ...
D/wpa_supplicant( 2022): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2022): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2022): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2022): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2022):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2022):   key_nonce - hexdump(len=32): c8 cf d1 4a 2e 48 29 dc 44 54 ce 90 85 c1 e0 83 bb e4 56 53 82 44 3a 04 98 13 24 71 a2 c3 71 4c
D/wpa_supplicant( 2022):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_rsc - hexdump(len=8): 78 61 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_mic - hexdump(len=16): 63 65 81 d3 bb f0 7e 92 9b eb e3 22 3f 1d 19 07
D/wpa_supplicant( 2022): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c8 cf d1 4a 2e 48 29 dc 44 54 ce 90 85 c1 e0 ...
D/wpa_supplicant( 2022): RSN: encrypted key data - hexdump(len=56): a0 70 67 c1 ae 06 b6 e7 18 17 1b 60 43 7d e7 3b 8a 8f 91 dc 6d f1 5f d8 2c 05 07 68 5b 25 e6 7f ...
D/wpa_supplicant( 2022): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2022): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2022): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2022): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 4b 0f ...
D/wpa_supplicant( 2022): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2022): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2022): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2022): WPA: Derived Key MIC - hexdump(len=16): d9 dd 99 14 1c f8 7f 66 9d 68 df ad 89 8b 59 db
,D/wpa_supplicant( 2022): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2022): wlan0: WPA: Installing PTK to the driver
,D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7903c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2022):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2022): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2022): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2022): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2022): WPA: RSC - hexdump(len=6): 78 61 00 00 00 00
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ee103a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2022):    broadcast key
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
,D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
I/AppUp4:CustModeStarterReceiver( 4059): onReceive
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection established
D/AppUp4:CustFacade( 4059): Context : android.app.ReceiverRestrictedContext@428302c8
D/AppUp4:CustFacade( 4059): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4059): isOpenOperator : true
D/AppUp4:CustFacade( 4059): isPhone : true
,D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2022): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  967):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  967): ssid=NG700
D/WifiNative-wlan0(  967): id=0
D/WifiNative-wlan0(  967): mode=station
D/WifiNative-wlan0(  967): pairwise_cipher=CCMP
D/WifiNative-wlan0(  967): group_cipher=CCMP
D/WifiNative-wlan0(  967): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  967): wpa_state=COMPLETED
D/WifiNative-wlan0(  967): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  967): address=34:fc:ef:de:0a:e2
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/WifiServiceExtension(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
I/AppUp4:EulaManager( 4059): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4059): begin check event
I/AppUp4:CustModeStarterReceiver( 4059): Event For GoodConnectivity
D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  967): handleMessage: X
D/DhcpStateMachine(  967): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-25ms what=147462 obj=android.net.wifi.StateChangeResult@44e019c0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,I/ActivityManager(  967): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4906 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-23ms what=147462 obj=android.net.wifi.StateChangeResult@44e02ff8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-24ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-14ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2022): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196612
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-15ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/HyLog   ( 4906): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/HyLog   ( 4906): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/HyLog   ( 4906): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4906): DownloadService onCreate
,D/EAS     ( 4667): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4667): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4906): in removeSpuriousFiles
,D/eas_req ( 4667): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4906): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4906): DownloadService onStartCommand
,V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@428596f0 on behalf of 4906
,V/DownloadManager( 4906): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4906): in trimDatabase
,V/DownloadManager( 4906): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4404): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4404): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4404): networkInfo.isConnected() = false
,V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@4285ce50 on behalf of 4906
,V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@4285bc28 on behalf of 4906
,W/linker  ( 4667): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4667): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4667): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4667): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4667): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4667): register_HtmlEditor, Success
D/HtmlEditor( 4667): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4667): register_HtmlEditorTimer, Success
D/HtmlEditor( 4667): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4667): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4667): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4667): register_HtmlEditorFont, Success
D/HtmlEditor( 4667): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4667): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4667): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4667): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4667): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4667): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4667): JNI_OnLoad Success
,I/HubEmail( 4667): JNI_OnLoad()
I/HubEmail( 4667): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4667): registerNatives()
I/HubEmail( 4667): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4667): registerNativeMethods()
,I/HubEmail( 4667): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4667): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  967):    returned null
,V/DownloadManager( 4906): DownloadService onDestroy
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4929 uid=10052 gids={50052, 3003}
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4320a410 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4320a410 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Setting iface cfg
D/WifiStateMachine(  967): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-4ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,I/ActivityManager(  967): Killing 3927:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): DHCP successful
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  967): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState enter
,D/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/HyLog   ( 4929): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4929): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4929): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
,D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,E/Parcel  (  477): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
,E/Parcel  (  477): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  967): handleMessage: E msg.what=131092
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
E/Parcel  (  477): Reading a NULL string not supported here.
,E/Parcel  (  477): Reading a NULL string not supported here.
,E/Parcel  (  477): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3}
,E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4929): [loadRssi] File not exist 
V/LGRssiData( 4929): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4929): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 4929): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4929): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
W/BaseRuntimeLoader( 4929): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4929): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4929): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4929): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4929): [getValue] FEATURE key : vzw_roaming_state, value : null
V/        (  264): RouteController
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
V/        (  264): RouteController
D/MobileConnectivityChangeReceiver( 4929): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4929): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4929): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4929): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4953 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  967): Killing 4382:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3}
I/CheckinService( 1874): Checking schedule, now: 1450653106182 next: 1450653042374
,I/CheckinService( 1874): active receiver: enabled
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,D/HyLog   ( 4953): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4953): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/CheckinService( 1874): Preparing to send checkin request
,I/EventLogService( 1874): Accumulating logs since 1450653009117
D/QCNEA   (  477): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  477): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  477): |CAC| updateNetCfgInfo
V/QCNEA   (  477): |CAC| *********************************************
V/QCNEA   (  477): |CAC|                   Netconfig               
V/QCNEA   (  477): |CAC| *********************************************
V/QCNEA   (  477): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  477): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  477): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  477): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  477): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  477): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  477): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  477): |CAC| *********************************************
,D/QCNEA   (  477): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  477): |CAC| net type = 1
V/QCNEA   (  477): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  477): |CAC| Received ssid= NG700
V/QCNEA   (  477): |CAC| 	ssid           =NG700
V/QCNEA   (  477): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  477): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  477): |CAC| *********************************************
D/QCNEA   (  477): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  477): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  477): |CAC| dispatchNetCfg: updating:0xb77eb8dc
D/QCNEA   (  477): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/HyLog   ( 4953): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinRequestBuilder( 1874): Checkin reason type: 8 attempt count: 1
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  967): GC_EXPLICIT freed 23390K, 49% free 29707K/57512K, paused 3ms+8ms, total 127ms
E/ActivityThread( 1874): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4982 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  967): Killing 4591:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4982): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4982): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4982): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2922): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  967): Killing 4623:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/LGDMClient( 2922): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2922): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4998 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3}
E/LGDMClient( 2922): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2922): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2922): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2922): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 4998): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4998): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4998): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4998): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4998): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5012 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  967): Killing 4653:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
D/HyLog   ( 5012): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5012): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5012): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NFS     ( 5012): connectivityManager.getNetworkInfo = TYPE_WIFI
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,I/Wireless_Storage( 5012): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5012): intf.getDisplayName() = lo
I/Wireless_Storage( 5012): intf.getDisplayName() = sit0
I/Wireless_Storage( 5012): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5012): intf.getDisplayName() = teql0
I/Wireless_Storage( 5012): intf.getDisplayName() = wlan0
,D/NFS     ( 5012): interface name:wlan0 name:wlan0
D/NFS     ( 5012): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5012): interface name:wlan0 name:wlan0
D/NFS     ( 5012): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 5012): CONNECT : WIFI_CONNECT
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 13ms
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5030 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4268:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5030): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5030): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5030): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1874): awaiting user notification for token
,W/GAV2    ( 5030): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x4313ef78: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5047 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5047): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5047): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5047): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 5047): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5047): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5047): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 5047): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5047): install
,I/MultiDex( 5047): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5047): loading existing secondary dex files
,I/MultiDex( 5047): load found 3 secondary dex files
,I/MultiDex( 5047): install done
,D/dalvikvm( 5047): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 5047): VFY: unable to resolve instance field 61
D/dalvikvm( 5047): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5047): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5047): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5047): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5047): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5047): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5047): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5047): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5047): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5047): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42818388
,D/dalvikvm( 5047): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42818388
,D/dalvikvm( 5047): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42818388, skipping init
D/dalvikvm( 5047): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42818388
,D/dalvikvm( 5047): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42818388
,V/JNIHelp ( 5047): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 5030): Binding Chromium to the main looper Looper (main, tid 1) {4280ec28}
,I/chromium( 5030): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5030): Initializing chromium process, renderers=0
,W/chromium( 5030): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5030): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5030): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5030): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5030): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5030): Remote Branch: 
I/Adreno-EGL( 5030): Local Patches: 
I/Adreno-EGL( 5030): Reconstruct Branch: 
,D/dalvikvm( 5047): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42818388
,D/dalvikvm( 5047): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42818388
D/dalvikvm( 5047): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42818388
,D/dalvikvm( 5047): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42818388
,I/NSApplication( 5030): Starting up...
,I/ActivityManager(  967): Killing 4284:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4856): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4856): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4856): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/ProviderInstaller( 5047): Installed default security provider GmsCore_OpenSSL
,I/QRemote ( 4856): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4856): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4856): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4827): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4827): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4856): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4856): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4856): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4856): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1552): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/dalvikvm( 5047): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5047): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5047): VFY: replacing opcode 0x6e at 0x000d
,D/AuthorizationBluetoothService( 1552): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1552): Proximity feature is not enabled.
I/dalvikvm( 5047): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5047): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5047): VFY: replacing opcode 0x6e at 0x0201
,V/GmsCoreStatsServiceLauncher( 1874): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3455): callingUid 10006, callindPid: 3455
,E/MDM     ( 1427): [66] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1874): Restart initialization of location
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ed1000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ed1000
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
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/wpa_supplicant( 2022): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2022): EAPOL: disable timer tick
D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=975283405
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5047): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429fabc8
D/dalvikvm( 5047): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429fabc8
,D/dalvikvm( 5047): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429fabc8, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 5047): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 5087): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 5047): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5047): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 76ms
,I/Adreno-EGL( 5047): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5047): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5047): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5047): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5047): Remote Branch: 
I/Adreno-EGL( 5047): Local Patches: 
I/Adreno-EGL( 5047): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Adreno-EGL( 5047): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5047): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5047): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5047): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5047): Remote Branch: 
I/Adreno-EGL( 5047): Local Patches: 
I/Adreno-EGL( 5047): Reconstruct Branch: 
,I/Adreno-EGL( 5047): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5047): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5047): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5047): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5047): Remote Branch: 
I/Adreno-EGL( 5047): Local Patches: 
I/Adreno-EGL( 5047): Reconstruct Branch: 
,W/Settings( 5047): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
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
,D/WVCdm   (  270): PrepareKeyRequest: nonce=1807257528
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
I/dalvikvm( 4760): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4760): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4760): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4760): Shutting down VM
,W/dalvikvm( 4760): threadid=1: thread exiting with uncaught exception (group=0x417d8e48)
E/AndroidRuntime( 4760): FATAL EXCEPTION: main
E/AndroidRuntime( 4760): Process: com.test.thalitest, PID: 4760
E/AndroidRuntime( 4760): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4760): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4760): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4760): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4760): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4760): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4760): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4760): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4760): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4760): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4760): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4760): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4760): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4760): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4760): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4760): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4760): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4760): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4760): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  967):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3 f}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/CheckinRequestBuilder( 1874): Classify the device as Phone.
D/WifiController(  967): battery changed pluggedType: 2
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/WifiStateMachine(  967): handleMessage: X
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1874): Sending checkin request (11589 bytes)
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  967): RunningState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  967): Activity pause timeout for ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
,V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432dc7a0 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  967): moveHomeStack:
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1490): [Launcher.java:4947:onStart()]onStart
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1490): [Launcher.java:717:onResume()]onResume
I/[LGHome]EVENT( 1490): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1490): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1490): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1825): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 0:11:48
,D/UpdateThreadPoolManager( 1825): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1825): 2 : quick cover state : opened : 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WeatherService( 1825): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1825): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1825): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1825): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1825): 2 : TimeTick Receiver Register
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherAncestor( 1825): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 0:11:48
D/WeatherService( 1825): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1825): 2 : quick cover state : opened : 0
D/Weather.Utils( 1825): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1825): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1825): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1825): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1825): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1825): 2 : This is isUpdating : false
D/WeatherService( 1825): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1825): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1825): 2 : Map key string is -2
D/lim     ( 1825): 2 : time = 00:11
I/WeatherReflect( 1825): Model Name : LG-D802
D/WeatherTheme( 1825): 2 : Different view - status_min_formatted : 10 != 11
D/WeatherTheme( 1825): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1825): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1825): 2 : Fixed theme : optimus
D/WeatherTheme( 1825): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1825): 2 : quick cover state : opened : 0
D/Weather.Utils( 1825): 2 : Utils getTopActivity com.lge.launcher2 / true
I/CheckinRequestBuilder( 1874): Checkin reason type: 8 attempt count: 1
D/WeatherService( 1825): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1825): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
E/ActivityThread( 1874): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
D/dalvikvm( 1142): GC_FOR_ALLOC freed 6941K, 11% free 70967K/78888K, paused 36ms, total 36ms
D/dalvikvm( 1490): GC_CONCURRENT freed 5521K, 9% free 60855K/66560K, paused 4ms+5ms, total 42ms
D/dalvikvm( 1490): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/dalvikvm( 1552): GC_EXPLICIT freed 551K, 29% free 17839K/24832K, paused 5ms+4ms, total 49ms
I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
W/CheckinRequestBuilder( 1874): awaiting user notification for token
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
I/CheckinRequestBuilder( 1874): Classify the device as Phone.
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
I/CheckinTask( 1874): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
I/CheckinService( 1874): Checking schedule, now: 1450653108751 next: 1451230504743
I/CheckinService( 1874): active receiver: disabled
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
D/dalvikvm( 1874): GC_CONCURRENT freed 1894K, 22% free 19549K/24832K, paused 4ms+4ms, total 53ms
D/dalvikvm(  967): GC_CONCURRENT freed 2176K, 47% free 30841K/57512K, paused 3ms+6ms, total 119ms
D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 112ms
D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 61ms
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x4298ca20: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
D/GCM     ( 1552): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1} time:128408
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
D/dalvikvm( 1490): GC_FOR_ALLOC freed 6991K, 12% free 59786K/67500K, paused 20ms, total 20ms
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2022): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@42815f78 time:128546
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{432ab6c0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/UsbSettings( 2628): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2628): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2628): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2628): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{432ab6c0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1}
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/Tethering(  967): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 4059): onReceive
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/AppUp4:CustFacade( 4059): Context : android.app.ReceiverRestrictedContext@428302c8
D/AppUp4:CustFacade( 4059): isCustomizationCompleted : false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/AppUp4:CustFacade( 4059): isOpenOperator : true
D/AppUp4:CustFacade( 4059): isPhone : true
I/LicenseContentProvider( 3056): start selecting data
D/SIMObserver( 3056): simInfo1
I/AppUp4:EulaManager( 4059): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4059): begin check event
I/AppUp4:CustModeStarterReceiver( 4059): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4059): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4059): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4059): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4059): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4059): handleAsyncCustNotification do not startCustService
V/DownloadManager( 4906): DownloadService onCreate
I/DownloadManager( 4906): in removeSpuriousFiles
D/EAS     ( 4667): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4667): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4906): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/eas_req ( 4667): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@42863790 on behalf of 4906
I/DownloadManager( 4906): in trimDatabase
V/DownloadManager( 4906): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4404): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4404): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4404): networkInfo.isConnected() = false
V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@42864bf0 on behalf of 4906
V/DownloadManager( 4906): DownloadService onStartCommand
V/DownloadManager( 4906): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/MobileConnectivityChangeReceiver( 4929): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4929): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@42866da0 on behalf of 4906
W/Settings( 4667): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4906): DownloadService onDestroy
D/LGDMClient( 2922): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMSGCM( 4998): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2922): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2922): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5012): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5012): CONNECT : WIFI_CONNECT
D/GCM     ( 1552): Connected
W/ContextImpl( 4998): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2922): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2922): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2922): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/LGDMClient( 2922): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/GCM     ( 1874): Message from null null
E/GCM     ( 1874): Dropping message from null
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/GCM     ( 1552): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/Tethering(  967): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 4059): onReceive
D/AppUp4:CustFacade( 4059): Context : android.app.ReceiverRestrictedContext@428302c8
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/AppUp4:CustFacade( 4059): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4059): isOpenOperator : true
D/AppUp4:CustFacade( 4059): isPhone : true
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/LicenseContentProvider( 3056): start selecting data
D/SIMObserver( 3056): simInfo1
I/AppUp4:EulaManager( 4059): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4059): begin check event
I/AppUp4:CustModeStarterReceiver( 4059): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/DownloadManager( 4906): DownloadService onCreate
I/DownloadManager( 4906): in removeSpuriousFiles
D/EAS     ( 4667): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4667): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4906): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@4286b428 on behalf of 4906
I/DownloadManager( 4906): in trimDatabase
V/DownloadManager( 4906): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4906): DownloadService onStartCommand
V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@4286cd98 on behalf of 4906
V/DownloadManager( 4906): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4404): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4404): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4404): networkInfo.isConnected() = true
D/PhoneState( 4404): setPdpRejectCasuse : false
V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@4286ead0 on behalf of 4906
W/Settings( 4667): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4929): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4929): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4906): DownloadService onDestroy
D/LGDMClient( 2922): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2922): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/LGDMSGCM( 4998): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 2922): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5012): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5012): CONNECT : WIFI_CONNECT
W/ContextImpl( 4998): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2922): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2922): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2922): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2922): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1490): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4059): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4059): onReceive
,D/AppUp4:CustFacade( 4059): Context : android.app.ReceiverRestrictedContext@428302c8
D/AppUp4:CustFacade( 4059): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4059): isOpenOperator : true
,D/AppUp4:CustFacade( 4059): isPhone : true
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
,I/AppUp4:EulaManager( 4059): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4059): begin check event
,I/AppUp4:CustModeStarterReceiver( 4059): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4667): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4906): DownloadService onCreate
,D/EAS     ( 4667): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4404): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4404): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4404): networkInfo.isConnected() = true
,D/PhoneState( 4404): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4929): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4929): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4667): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4906): in removeSpuriousFiles
,V/DownloadManager( 4906): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2922): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4998): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4998): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@42872c58 on behalf of 4906
I/DownloadManager( 4906): in trimDatabase
V/DownloadManager( 4906): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@42874650 on behalf of 4906
D/LGDMClient( 2922): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2922): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2922): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2922): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2922): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 4906): DownloadService onStartCommand
,I/NFS     ( 5012): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5012): CONNECT : WIFI_CONNECT
I/LGDMClient( 2922): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 4906): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@42876800 on behalf of 4906
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4906): DownloadService onDestroy
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV2    ( 5030): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/ActivityManager(  967): Killing 4686:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1}
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  967): Killing 4308:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  967): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5246 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5246): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5246): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5246): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5246): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5246): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5246): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5246): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5246): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5246): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5246): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5246): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5246): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5246): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5246): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5246): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5246): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 5246): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 5246): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5246): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x0292
,I/dalvikvm( 5246): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5246): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x029a
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/DownloadManager( 4906): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4906): created cursor android.database.sqlite.SQLiteCursor@4287ba28 on behalf of 5246
,I/dalvikvm( 5246): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5246): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5246): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5246): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5246): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5246): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5246): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5246): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm( 5246): Total arena pages for JIT: 11
,I/dalvikvm( 5246): Total arena pages for JIT: 12
I/dalvikvm( 5246): Total arena pages for JIT: 13
,I/dalvikvm( 5246): Total arena pages for JIT: 14
,D/Finsky  ( 5246): [465] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5246): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  967): Killing 4827:com.lge.sync/1000 (adj 15): empty #17
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5246): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5246): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5246): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5246): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5246): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5246): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5246): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5246): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5246): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5246): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/DeviceConnectionService( 1427): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "sms"
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5310 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 4085): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 4085): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  967): Handling package changes for user 0
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5310): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5310): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5310): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
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
,I/MediaCodecList( 5310): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/Babel   ( 5310): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5310): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5310): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5310): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/Babel   ( 5310): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5310): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5310): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5310): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5310): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5310): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5310): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5310): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5310): MmsConfig.loadFromResources
E/Babel   ( 5310): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5310): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5310): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/GmsNetworkLocationProvi( 1427): DISABLE
,V/LGRssiData( 5310): [loadRssi] File not exist 
V/LGRssiData( 5310): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5310): [loadFeatureFromXml] *** start feature loading from xml
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/TelephonyAutoProfiling( 5310): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5310): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5310): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4059): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4059): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4059): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4059): onReceive
D/AppUp4:CustFacade( 4059): Context : android.app.ReceiverRestrictedContext@428302c8
D/AppUp4:CustFacade( 4059): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4059): isOpenOperator : true
,D/AppUp4:CustFacade( 4059): isPhone : true
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
,D/dalvikvm(  967): GC_EXPLICIT freed 2427K, 47% free 30701K/57316K, paused 3ms+8ms, total 98ms
,I/AppUp4:EulaManager( 4059): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4059): begin check event
D/AppUp4:Utils( 4059): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4059): Event For Nothing, skip.
,I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5361 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  967): Killing 4856:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/HyLog   ( 5361): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5361): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5361): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1}
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
,I/SystemConfig( 5361): BUILD Country: EU
,I/SystemConfig( 5361): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 4760:com.test.thalitest/u0a304 (adj 15): empty #17
,I/SystemConfig( 5361): systemFeature RCS result false
,D/SystemConfig( 5361): refreshRcsSupport() :false
I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5376 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,D/WifiService(  967): Client connection lost with reason: 4
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
D/HyLog   ( 5376): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5376): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5376): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/WindowState(  967): WIN DEATH: Window{43c53f80 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{44df8dd0 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1490): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1}
I/InputMethodManagerService(  967): IME STATUS OFF
,W/InputMethodManagerService(  967): Got RemoteException sending setActive(false) notification to pid 4760 uid 10304
W/Binder  ( 1311): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1311): java.lang.NullPointerException
W/Binder  ( 1311): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1311): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1311): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1311): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/IcingCorporaProvider( 2705): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  967): Killing 4667:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1874): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1874): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  967): Delaying start of: ServiceRecord{448d3fe0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1874): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2705): UpdateCorporaTask done [took 185 ms] updated apps [took 185 ms] 
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.470276 Y: -0.385529 Z: 9.765060 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470276 .y:-0.385529 .z:9.765060
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/PowerManagerService(  967): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  967): [updateScreenState] screen on = false
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
D/qcom_sensors_hal(  967): _hal_sensors_batch: sample_rate=20 report_rate=0 curr sample rate:0 cur rpt rate:0 max:20.000000 min:1.000000
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,I/qcom_sensors_hal(  967): _hal_sensors_flush: handle=35
D/qcom_sensors_hal(  967): _hal_sensors_flush: handle 35 is inactive
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8944 usec
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  967): hal_acquire_resources
I/qcom_sensors_hal(  967): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  967): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  967): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  967): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  967): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  967): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  967): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  967): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.475189 Y: -0.391220 Z: 9.771057 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.475189 .y:-0.391220 .z:9.771057
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.459442 Y: -0.400589 Z: 9.757538 
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.457245 Y: -0.375061 Z: 9.795273 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.459442 .y:-0.400589 .z:9.757538
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  454): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  967): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  967): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  967): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  967): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  967): proximitySensorChanged  positive = true
I/KnockOnPowerController(  967): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.461349 Y: -0.384338 Z: 9.778183 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461349 .y:-0.384338 .z:9.778183
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.451248 Y: -0.380890 Z: 9.775635 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451248 .y:-0.380890 .z:9.775635
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.452271 Y: -0.385925 Z: 9.766815 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452271 .y:-0.385925 .z:9.766815
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.444031 Y: -0.397644 Z: 9.767639 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444031 .y:-0.397644 .z:9.767639
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4306c348)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.447662 Y: -0.407440 Z: 9.774612 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447662 .y:-0.407440 .z:9.774612
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/WindowManager(  967): No lock screen! windowToken=null
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8ead450
D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,E/SlideAside( 4085): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132097
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2022): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2022): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  967): handleMessage: X
E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
,V/EmotionalLed( 1158): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43155f10 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1158): enqueuing start. mLedList.size()=2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1158): enqueuing end. mLedList.size()=3
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1825): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 0:11:59
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,I/SlideAside( 4085): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1825): 2 : This is isUpdating : false
,D/WeatherAncestor( 1825): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 0:11:59
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1825): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1825): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1825): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1825): 2 : shouldTimeTickRegistered : false
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  967): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
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
,D/qdlights( 1158): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1158): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 195, B = 195
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 410ms
,D/qdlights( 1158): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 189, B = 189
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1158): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1158): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1158): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 165, B = 165,
,D/qdlights( 1158): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 159, B = 159
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 153, B = 153
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,D/qdlights( 1158): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1158): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 141, B = 141
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1158): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 135, B = 135
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1158): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1158): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1158): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 117, B = 117
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
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
,D/qdlights( 1158): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1158): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1158): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 45, B = 45
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/qdlights( 1158): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 39, B = 39
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653119739, nextTick: 292, mDrawingTime: 1
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
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653119796, nextTick: 237, mDrawingTime: 0
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/WeatherService( 1825): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 0:11:59
,D/WeatherService( 1825): 2 : ACTION screen on
,D/WeatherService( 1825): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1825): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 0:11:59
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
,E/Parcel  (  477): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1142): notifyScreenOffLocked
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,I/[LGHome]EVENT( 1490): [Launcher.java:894:onPause()]onPause
,I/LGImmersionVibrator(  967): Vibrator off
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
,D/KeyguardViewManager( 1142): onScreenTurnedOff()
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,I/[LGHome]EVENT( 1490): [Launcher.java:4955:onStop()]onStop
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/WifiStateMachine(  967): handleScreenStateChanged: false
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/SRS_Proc(  270): ParamSet string: screen_state=off
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
D/WifiController(  967): CMD_SCREEN_OFF 
D/WifiController(  967): shouldWifiStayAwake TRUE
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{4313c158 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1158): set_light_notifications: 1,ff00ff00,500,2000,1
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=2
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/EmotionalLed( 1158): RESTART MSG
,D/VolumeVibrator( 1158): clear
D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
I/[LGHome]EVENT( 1490): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1825): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 0:11:59
D/WeatherService( 1825): 2 : ACTION screen off
,D/WeatherService( 1825): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 0:11:59
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
,E/Parcel  (  477): Reading a NULL string not supported here.
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1465): [TangibleIO] LCD is off. Remove tangible if exist.
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/NfcService( 1477): NFC-C OFF
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653120033, nextTick: 60000, mDrawingTime: 0
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653120050, nextTick: 59983, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  454): sns_pwr.c(320):releasing wakelock
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,I/GAV4    ( 5310): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1552): Vacuum at: now=1450653129629 tag=VacuumService
,I/GoogleURLConnFactory( 1552): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1552): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5246): [465] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5246): [1] 5.onFinished: Installation state replication succeeded.
,D/dalvikvm( 1552): GC_CONCURRENT freed 1834K, 28% free 18029K/24832K, paused 2ms+2ms, total 24ms
,W/Uploader( 1552): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Uploader( 1552):  no longer exists, so no auth token.
,W/Uploader( 1552): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653137209900801; DSPS: 5275520; Offset: 1450652976213807051
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653157215511271; DSPS: 5931064; Offset: 1450652976213802287
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653177221190025; DSPS: 6586610; Offset: 1450652976213804772
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653180044, nextTick: 59986, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653180058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653197228770466; DSPS: 7242219; Offset: 1450652976213786336
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653217230763113; DSPS: 7897644; Offset: 1450652976213795340
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653237232928340; DSPS: 8553075; Offset: 1450652976213793819
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653240050, nextTick: 59972, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653240057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653257234824226; DSPS: 9208497; Offset: 1450652976213797615
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653277238461127; DSPS: 9863976; Offset: 1450652976213802924
,D/wpa_supplicant( 2022): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 6 BSSID 34:36:3b:bd:89:28 SSID 'andilabs' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 3 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 2 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 7 BSSID 06:7c:34:11:b3:cb SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 8 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a],
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:97]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 34:36:3b:bd:89:28]
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 06:7c:34:11:b3:cb]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 44:e9:dd:10:c0:ad]
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653297241782383; DSPS: 10519445; Offset: 1450652976213797764
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653300046, nextTick: 59970, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653300064, nextTick: 59968, mDrawingTime: 0
,D/dalvikvm( 2693): GC_CONCURRENT freed 7765K, 32% free 16888K/24832K, paused 4ms+2ms, total 69ms
,D/dalvikvm( 2693): WAIT_FOR_CONCURRENT_GC blocked 53ms
,I/ActivityManager(  967): Killing 4929:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653317249792424; DSPS: 11175067; Offset: 1450652976213812200
,I/LocationManagerService(  967): remove 43339020
D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2693): GC_CONCURRENT freed 1788K, 31% free 17147K/24832K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 2693): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2693): GC_CONCURRENT freed 1964K, 31% free 17230K/24832K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2693): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2693): GC_FOR_ALLOC freed 1368K, 30% free 17410K/24832K, paused 19ms, total 19ms
,I/Mlt MonitorService( 2693): parseLastkmsg to dump
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653337254940357; DSPS: 11830596; Offset: 1450652976213802662
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653357263102183; DSPS: 12486223; Offset: 1450652976213816295
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653360049, nextTick: 59970, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653360056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653377266723158; DSPS: 13141702; Offset: 1450652976213805678
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653397273693051; DSPS: 13797290; Offset: 1450652976213817563
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43c4d348: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1552): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1552): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1552): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1552): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1552): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5246): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5246): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5246): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5246): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5246): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5246): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5246): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5246): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 5246): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5246): isDataSchedulerEnabled():false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653417277592284; DSPS: 14452778; Offset: 1450652976213810546
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653420048, nextTick: 59968, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653420058, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653437283526053; DSPS: 15108333; Offset: 1450652976213793387
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653457288319425; DSPS: 15763850; Offset: 1450652976213795500
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653477295440504; DSPS: 16419443; Offset: 1450652976213805983
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653480040, nextTick: 59988, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653480046, nextTick: 59972, mDrawingTime: 5
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653497298282643; DSPS: 17074896; Offset: 1450652976213809987
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653517303678382; DSPS: 17730433; Offset: 1450652976213804115
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653537307811067; DSPS: 18385928; Offset: 1450652976213816927
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653540044, nextTick: 59984, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653540046, nextTick: 59982, mDrawingTime: 3
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653557314425278; DSPS: 19041505; Offset: 1450652976213808823
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653577321460804; DSPS: 19697096; Offset: 1450652976213794789
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653597324128305; DSPS: 20352543; Offset: 1450652976213807261
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653600045, nextTick: 59985, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653600047, nextTick: 59982, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653617329807835; DSPS: 21008089; Offset: 1450652976213810521
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653637331597016; DSPS: 21663508; Offset: 1450652976213799165
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653657335441601; DSPS: 22318994; Offset: 1450652976213798535
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653660045, nextTick: 59984, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653660048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653677343091679; DSPS: 22974605; Offset: 1450652976213788701
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653697346297729; DSPS: 23630070; Offset: 1450652976213790405
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653717352902367; DSPS: 24285646; Offset: 1450652976213803246
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653720037, nextTick: 59992, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653720039, nextTick: 59992, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653737358924091; DSPS: 24941203; Offset: 1450652976213813008
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653757364409241; DSPS: 25596743; Offset: 1450652976213804993
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653777370518755; DSPS: 26252303; Offset: 1450652976213810992
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653780076, nextTick: 59955, mDrawingTime: 1
D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653780077, nextTick: 59954, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653797374797933; DSPS: 26907804; Offset: 1450652976213787191
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653817377804867; DSPS: 27563262; Offset: 1450652976213803403
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653837380879976; DSPS: 28218723; Offset: 1450652976213796236
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653840046, nextTick: 59972, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653840056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653857386528175; DSPS: 28874268; Offset: 1450652976213798683
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653877389118819; DSPS: 29529713; Offset: 1450652976213795333
,D/Finsky  ( 5246): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Finsky  ( 5246): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/EventLogService( 1874): Aggregate from 1450653106224 (log), 1450651729211 (data)
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  967): GC_EXPLICIT freed 2393K, 47% free 30692K/57316K, paused 4ms+11ms, total 130ms
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5246): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5246): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5246): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5246): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5246): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/DeviceConnectionService( 1427): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653897394810037; DSPS: 30185259; Offset: 1450652976213810282
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653900059, nextTick: 59969, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653900064, nextTick: 59969, mDrawingTime: 0
,D/Finsky  ( 5246): [465] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5246): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653917396469791; DSPS: 30840674; Offset: 1450652976213791569
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653937402064741; DSPS: 31496217; Offset: 1450652976213801802
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653957406780939; DSPS: 32151732; Offset: 1450652976213787775
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653960033, nextTick: 59991, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450653960038, nextTick: 59994, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653977411272015; DSPS: 32807239; Offset: 1450652976213792767
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450653997417066264; DSPS: 33462789; Offset: 1450652976213788677
,D/GCM     ( 1552): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654017421198530; DSPS: 34118284; Offset: 1450652976213801070
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654020039, nextTick: 59985, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654020045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654037429447180; DSPS: 34773914; Offset: 1450652976213809973
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654057433406665; DSPS: 35429404; Offset: 1450652976213802173
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654077440411792; DSPS: 36084993; Offset: 1450652976213818775
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654080046, nextTick: 59982, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654080049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654097447246740; DSPS: 36740578; Offset: 1450652976213787268
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654117452339443; DSPS: 37396104; Offset: 1450652976213814053
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654137455343098; DSPS: 38051563; Offset: 1450652976213796468
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654140036, nextTick: 59982, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654140045, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654157462191842; DSPS: 38707147; Offset: 1450652976213809274
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654177468488763; DSPS: 39362714; Offset: 1450652976213789056
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654197474150856; DSPS: 40018259; Offset: 1450652976213805398
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654200040, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654200045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654217479982301; DSPS: 40673810; Offset: 1450652976213807985
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654237484360868; DSPS: 41329314; Offset: 1450652976213792021
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654257490960380; DSPS: 41984890; Offset: 1450652976213799736
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654260043, nextTick: 59982, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654260056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654277497077718; DSPS: 42640450; Offset: 1450652976213813558
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654297504302221; DSPS: 43296047; Offset: 1450652976213805395
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654317508641786; DSPS: 43951549; Offset: 1450652976213811464
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654320039, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654320042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654337517097622; DSPS: 44607186; Offset: 1450652976213813931
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654357520343983; DSPS: 45262653; Offset: 1450652976213794911
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654377525434790; DSPS: 45918179; Offset: 1450652976213819800
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654380038, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654380040, nextTick: 59991, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654397530327060; DSPS: 46573700; Offset: 1450652976213798740
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654417536166470; DSPS: 47229251; Offset: 1450652976213809293
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654437538958001; DSPS: 47884702; Offset: 1450652976213823724
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654440049, nextTick: 59974, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654440056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654457544300491; DSPS: 48540238; Offset: 1450652976213795120
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654477550133099; DSPS: 49195789; Offset: 1450652976213798871
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654497553840482; DSPS: 49851270; Offset: 1450652976213813627
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654500044, nextTick: 59984, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654500047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654517558476556; DSPS: 50506782; Offset: 1450652976213811029
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654537560650864; DSPS: 51162213; Offset: 1450652976213818589
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654557563807645; DSPS: 51817677; Offset: 1450652976213801542
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654560039, nextTick: 59985, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654560055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654577570184537; DSPS: 52473246; Offset: 1450652976213800260
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654597578562369; DSPS: 53128881; Offset: 1450652976213785758
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654617583810623; DSPS: 53784412; Offset: 1450652976213815506
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654620044, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654620054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654637591052048; DSPS: 54440010; Offset: 1450652976213793748
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654657595478164; DSPS: 55095515; Offset: 1450652976213794815
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654677599622743; DSPS: 55751010; Offset: 1450652976213819521
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654680027, nextTick: 60001, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654680046, nextTick: 59987, mDrawingTime: 0
,W/ProcessCpuTracker(  967): Skipping unknown process pid 6962
,W/ProcessCpuTracker(  967): Skipping unknown process pid 6964
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654697608283420; DSPS: 56406654; Offset: 1450652976213813206
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654717616027156; DSPS: 57062268; Offset: 1450652976213805477
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654737620684011; DSPS: 57717781; Offset: 1450652976213793142
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654740041, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654740062, nextTick: 59971, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654757629217422; DSPS: 58373420; Offset: 1450652976213812149
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654777633458008; DSPS: 59028919; Offset: 1450652976213810792
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654797638140866; DSPS: 59684433; Offset: 1450652976213793943
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  967): Prepared write state in 60ms
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654800093, nextTick: 59929, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654800101, nextTick: 59932, mDrawingTime: 0
,I/ProcessStatsService(  967): Prepared write state in 27ms
,I/ProcessStatsService(  967): Pruning old procstats: /data/system/procstats/state-2015-12-20-00-18-53.bin
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654817643721618; DSPS: 60339975; Offset: 1450652976213820495
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654837650836192; DSPS: 60995569; Offset: 1450652976213793956
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654857655497131; DSPS: 61651081; Offset: 1450652976213816223
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654860042, nextTick: 59981, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654860047, nextTick: 59985, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654877663732123; DSPS: 62306711; Offset: 1450652976213811469
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654897666433554; DSPS: 62962160; Offset: 1450652976213796836
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1552): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/ActivityManager(  967): Killing 5047:com.google.android.gms.unstable/u0a6 (adj 15): empty for 1802s
,I/ActivityManager(  967): Killing 5030:com.google.android.apps.magazines/u0a104 (adj 15): empty for 1803s
,I/ActivityManager(  967): Killing 5012:com.lge.wireless_storage/u0a101 (adj 15): empty for 1803s
I/ActivityManager(  967): Killing 4998:com.lge.lgdmsgcm/1000 (adj 15): empty for 1803s
,I/ActivityManager(  967): Killing 4982:com.lge.drmservice/u0a66 (adj 15): empty for 1803s
,I/ActivityManager(  967): Killing 4953:com.android.chrome/u0a63 (adj 15): empty for 1803s
,I/ActivityManager(  967): Killing 4906:android.process.media/u0a23 (adj 15): empty for 1801s
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450654917673410964; DSPS: 63617748; Offset: 1450652976213816238
,TIME-OUT KILL (timeout was 1800000ms),D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654920027, nextTick: 60002, mDrawingTime: 3
D/Clock   ( 1142): Clock updated, drawingStartTime : 1450654920047, nextTick: 59985, mDrawingTime: 0
D/AndroidRuntime( 7204): 
D/AndroidRuntime( 7204): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7204): CheckJNI is OFF
D/dalvikvm( 7204): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7204): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7204): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7204): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7204): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 7204): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 7204): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7204): failed to load memtrack module: -2
D/AndroidRuntime( 7204): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/PackageSettings(  967): Skipping PackageSetting{42cd96a8 com.example.hello/10312} due to missing metadata
I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/dalvikvm( 1490): GC_EXPLICIT freed 1732K, 11% free 60355K/67476K, paused 1ms+2ms, total 25ms
D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
E/SlideAside( 4085): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/SlideAside( 4085): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AppUp4:Utils( 4059): [getPackageName] uri : package:com.test.thalitest
D/AppUp4  ( 4059): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 4059):  isExcludedPackage  packagename = com.test.thalitest
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "sms"
D/AppUp4  ( 4059):  isExcludedPackage TRUE : com.test.thalitest
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm( 2705): GC_EXPLICIT freed 4823K, 27% free 18172K/24832K, paused 4ms+6ms, total 85ms
W/GeofencerStateMachine( 1427): Ignoring removeGeofence because network location is disabled.
W/System.err( 2693): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 2693): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2693): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2693): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2693): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2693): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2693): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2693): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2693): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2693): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2693): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2693): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2693): 	at dalvik.system.NativeStart.main(Native Method)
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  967): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7233 uid=10090 gids={50090}
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  967): GC_EXPLICIT freed 2387K, 47% free 30774K/57316K, paused 4ms+19ms, total 140ms
D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 44ms
I/ActivityManager(  967): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=7245 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
D/HyLog   ( 7233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7233): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/LockScreenSettings( 7233): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1142): changeTargets() succeeded. size: 20
D/HyLog   ( 7245): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7245): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7245): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1142): createShortcutInfo...
D/administrator(  967): Handling package changes for user 0
D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1142): createShortcutInfo...
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1142): createShortcutInfo...
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1142): createShortcutInfo...
D/[BNRAppListMgrReceiver]( 7245): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  967): Killing 5310:com.google.android.talk/u0a77 (adj 15): empty for 1807s
D/KeyguardModel( 1142): handleShortcutListChanged...
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1142): createShortcutInfo...
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1142): createShortcutInfo...
D/VoicemailCleanupService( 1735): Cleaning up data for package: com.test.thalitest
D/dalvikvm(  967): GC_EXPLICIT freed 449K, 47% free 30761K/57316K, paused 3ms+11ms, total 156ms
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1142): createShortcutInfo...
D/BackupManagerService(  967): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/InteractionManagerConfigurator(  967): updateIntentFilterConfig
I/InteractionManagerConfigurator(  967): com.test.thalitest isn't inclued in dragdropPackageList
D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1142): createShortcutInfo...
V/BackupManagerService(  967): removePackageParticipantsLocked: uid=10304 #1
I/ActivityManager(  967): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7260 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
D/KeyguardModel( 1142): handleShortcutListChanged...
I/ActivityManager(  967): Killing 5376:com.android.gallery3d/u0a27 (adj 15): empty for 1807s
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
D/HyLog   ( 7260): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7260): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7260): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/LGEmail ( 7260): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/AndroidRuntime( 7204): Shutting down VM
D/dalvikvm( 7204): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+1ms, total 2ms
D/LGEmail ( 7260): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
W/BaseRuntimeLoader( 7260): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7260): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7260): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7260): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/PackageChangeReceiver( 7260): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7277 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): Killing 3955:com.google.android.apps.plus/u0a112 (adj 15): empty for 1807s
D/HyLog   ( 7277): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7277): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7277): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/PackageIntentReceiver( 2628): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 2628): Receive package name : com.test.thalitest
D/HideNavigationAppsReceiver( 2628): Delete mPackageMame : com.test.thalitest
I/ActivityManager(  967): Killing 3455:com.google.android.gms.wearable/u0a6 (adj 15): empty for 1807s
I/IcingCorporaProvider( 2705): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  967): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7293 uid=10073 gids={50073, 3003, 1028, 1015}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42be9eb8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
D/HyLog   ( 7293): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7293): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7293): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
I/IcingCorporaProvider( 2705): UpdateCorporaTask done [took 90 ms] updated apps [took 90 ms] 

```
