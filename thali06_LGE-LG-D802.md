#### Test 575312430087a60_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1943): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1943): launchTask
W/dalvikvm( 1943): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1943): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1943): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1943): No vision deps
V/ConfigFetchTask( 1943): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1X5-Fqf1fhwWENiclSV71ixoSodvFdwGJqBmYItzwDGBd_S4na5Rq3qI5K0YkJhk7k4mREejfOvAt3jwl8sVY_kI3b6-NZ2hPbSPAoHoiolfa-2mRlqAxJms8o6FfgrgJusB93uWBH8XgRdptO4ep_AB3nPAynwFddVo2xQglnkXR5dTMxzmnR6no9EGnMDCxs3a4sP0cguBPBVBE1_dq7VUSDlo7FNAy7bWjwUfmJvK60fpyc
,I/PeopleContactsSync( 1943): CP2 sync disabled
I/GoogleURLConnFactory( 1943): Using platform SSLCertificateSocketFactory
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
I/dalvikvm( 1943): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1943): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1943): VFY: replacing opcode 0x6e at 0x000e
W/GAV2    ( 4559): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  968): Killing 4021:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330d8c0 stackId=1, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{43040ad8 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/libc    (  266): _dns_getaddrinfo: iptype =1
D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
I/ConfigFetchService( 1943): fetch service done; releasing wakelock
I/ConfigFetchService( 1943): stopping self
D/AndroidRuntime( 4613): 
D/AndroidRuntime( 4613): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4613): CheckJNI is OFF
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
D/dalvikvm( 4613): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4613): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4613): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4613): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4613): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 1943): GC_CONCURRENT freed 1531K, 22% free 19472K/24832K, paused 4ms+5ms, total 49ms
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/dalvikvm( 4613): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1943): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1943): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1943): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4613): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4613): failed to load memtrack module: -2
D/AndroidRuntime( 4613): Calling main entry com.android.commands.am.Am
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4613
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330d8c0 stackId=1, 2 tasks}
D/PermissionCache(  269): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (121 us)
V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{43040ad8 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  968): resumeTopActivityLocked: Pausing null
V/ActivityManager(  968): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  968): startService SlideAside
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  968): setFocusedStack: mFocusedStack=ActivityStack{4330d8c0 stackId=1, 2 tasks}
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{43040ad8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/AndroidRuntime( 4613): Shutting down VM
D/UsbSettingsControl( 2602): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2602): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3998): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4613): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{43040ad8 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330d8c0 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Restarting ActivityRecord{43ea7480 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  968): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4637 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3998): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3998): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  968): Moving to RESUMED: ActivityRecord{43ea7480 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/dalvikvm(  270): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+3ms, total 18ms
D/HyLog   ( 4637): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4637): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4637): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  270): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
D/dalvikvm(  270): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
V/WebViewChromium( 4637): Binding Chromium to the background looper Looper (main, tid 1) {42803ee8}
I/chromium( 4637): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4637): Initializing chromium process, renderers=0
W/chromium( 4637): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4637): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4637): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4637): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4637): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4637): Remote Branch: 
I/Adreno-EGL( 4637): Local Patches: 
I/Adreno-EGL( 4637): Reconstruct Branch: 
D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2020): nl80211: survey data missing!
D/WifiStateMachine(  968): handleMessage: X
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
I/dalvikvm( 4637): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4637): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4637): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4637): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4637): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4637): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4637): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4637): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4637): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4637): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4637): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4637): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4637): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4637): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4637): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4637): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4637): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4637): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4637): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4637): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4637): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4637): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4637): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4637): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/WifiController(  968): battery changed pluggedType: 2
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
D/OpenGLRenderer( 4637): Enabling debug mode 0
W/AwContents( 4637): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  968): IME STATUS OFF
W/AwContents( 4637): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 4637): Timeline: Activity_idle id: android.os.BinderProxy@428056b8 time:93753
I/ActivityManager(  968): Displayed com.test.thalitest/.MainActivity: +489ms
D/JsMessageQueue( 4637): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4637): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42809888
D/dalvikvm( 4637): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42809888
D/jxcore_app_log( 4637): JniHelper::setJavaVM(0x416c6838), pthread_self() = 1630966816
I/chromium( 4637): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  968): Timeline: Activity_windows_visible id: ActivityRecord{43ea7480 u0 com.test.thalitest/.MainActivity t3} time:94033
D/UsbSettings( 2602): [AUTORUN] onStop()
D/ActivityManager(  968): no-history finish of ActivityRecord{43040ad8 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  968): Finishing activity token=Token{4300a2f0 ActivityRecord{43040ad8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  968): Moving to FINISHING: ActivityRecord{43040ad8 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ea7480 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{43040ad8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/chromium( 4637): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4637): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  968): Moving to STOPPED: ActivityRecord{43040ad8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4637): GC_CONCURRENT freed 3352K, 15% free 21300K/24832K, paused 2ms+1ms, total 36ms
D/dalvikvm( 4637): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/dalvikvm( 4637): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4637): GC_FOR_ALLOC freed 56K, 15% free 21295K/24832K, paused 24ms, total 24ms
I/dalvikvm-heap( 4637): Grow heap (frag case) to 23.279MB for 323830-byte allocation
D/dalvikvm( 4637): GC_FOR_ALLOC freed 626K, 16% free 21356K/25152K, paused 21ms, total 21ms
I/dalvikvm-heap( 4637): Grow heap (frag case) to 23.493MB for 485740-byte allocation
D/dalvikvm( 4637): GC_FOR_ALLOC freed 863K, 16% free 21532K/25628K, paused 23ms, total 23ms
I/dalvikvm-heap( 4637): Grow heap (frag case) to 23.896MB for 728606-byte allocation
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
D/dalvikvm( 4637): GC_FOR_ALLOC freed 1281K, 18% free 21788K/26340K, paused 22ms, total 22ms
I/dalvikvm-heap( 4637): Grow heap (frag case) to 24.494MB for 1092904-byte allocation
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4637): GC_CONCURRENT freed 1886K, 19% free 22206K/27408K, paused 2ms+2ms, total 49ms
D/dalvikvm( 4637): GC_FOR_ALLOC freed 181K, 20% free 22086K/27408K, paused 21ms, total 21ms
I/dalvikvm-heap( 4637): Grow heap (frag case) to 25.306MB for 1639352-byte allocation
D/dalvikvm( 4637): GC_CONCURRENT freed 1522K, 22% free 22666K/29012K, paused 0ms+2ms, total 25ms
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/dalvikvm( 4637): GC_FOR_ALLOC freed 1520K, 22% free 22795K/29012K, paused 36ms, total 37ms
,I/dalvikvm-heap( 4637): Grow heap (frag case) to 26.779MB for 2459024-byte allocation
,D/dalvikvm( 4637): GC_CONCURRENT freed 255K, 14% free 25050K/29012K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 4637): GC_FOR_ALLOC freed 3802K, 19% free 23673K/29012K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4637): Grow heap (frag case) to 27.474MB for 2288606-byte allocation
,W/jxcore-log( 4637): Initializing JXcore engine
,W/jxcore-log( 4637): JXcore engine is ready
,W/jxcore-log( 4637): Starting JXcore engine
,D/dalvikvm( 4637): GC_CONCURRENT freed 550K, 18% free 25761K/31248K, paused 1ms+3ms, total 28ms
,W/jxcore-log( 4637): Platform android
W/jxcore-log( 4637): 
,W/jxcore-log( 4637): Process ARCH arm
W/jxcore-log( 4637): 
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4637): JXcore Cordova bridge is ready!
I/jxcore-log( 4637): 
,W/jxcore-log( 4637): JXcore engine is started
,E/jxcore  ( 4637): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4637): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4637): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  968): Finishing activity token=Token{43b99c40 ActivityRecord{43ea7480 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{43ea7480 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm(  968): GC_FOR_ALLOC freed 19844K, 45% free 29691K/53812K, paused 156ms, total 156ms
,V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{43ea7480 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
,V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{43ea7480 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330d8c0 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  968): moveHomeStack:
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,W/PluginManager( 4637): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 182ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  968): Moving to RESUMED: ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  968): resumeTopActivityLocked: Resumed ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  968): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1835): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:26:28
,D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
,I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,W/IInputConnectionWrapper( 4637): showStatusIcon on inactive InputConnection
I/InputMethodManagerService(  968): IME STATUS OFF
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1835): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1835): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1835): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1835): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:26:28
D/WeatherService( 1835): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
D/Weather.Utils( 1835): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1835): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1835): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1835): 2 : Map key string is -2
D/lim     ( 1835): 2 : time = 19:26
I/WeatherReflect( 1835): Model Name : LG-D802
D/WeatherTheme( 1835): 2 : Different view - status_min_formatted : 25 != 26
D/WeatherTheme( 1835): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1835): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1835): 2 : Fixed theme : optimus
,D/WeatherTheme( 1835): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1835): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1489): GC_CONCURRENT freed 5526K, 9% free 60858K/66628K, paused 4ms+3ms, total 28ms
,D/dalvikvm( 1489): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 1144): GC_FOR_ALLOC freed 3160K, 9% free 71208K/78232K, paused 43ms, total 44ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1489): GC_FOR_ALLOC freed 4800K, 9% free 61906K/67496K, paused 16ms, total 17ms
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@427ff058 time:96571
,D/UsbSettings( 2602): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2602): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2602): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2602): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  968): Moving to DESTROYING: ActivityRecord{43040ad8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{43040ad8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  968): Timeline: Activity_windows_visible id: ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1} time:96634
V/ActivityManager(  968): Moving to FINISHING: ActivityRecord{43ea7480 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  968): Killing 4129:com.google.android.talk/u0a77 (adj 15): empty #17
V/ActivityManager(  968): Moving to DESTROYING: ActivityRecord{43ea7480 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4637): call to OpenGL ES API with no current context (logged once per thread)
,V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{43ea7480 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/rmt_storage(  407): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb7e20178
I/rmt_storage(  407): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  407): wakelock acquired: 1, error no: 42
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1209925064)
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1209925064) wakelock released: 1, error no: 22
I/rmt_storage(  407): 
,I/rmt_storage(  407): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb7e20178
,E/Diag_Lib(  659): [IMS_FATAL]| 2912 | 664 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  968): Killing 2134:android.process.media/u0a23 (adj 15): empty #17
,W/ProcessCpuTracker(  968): Skipping unknown process pid 4728
,W/ProcessCpuTracker(  968): Skipping unknown process pid 4729
,W/ProcessCpuTracker(  968): Skipping unknown process pid 4731
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1}
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4559): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  968): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/WifiController(  968): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1216): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/WifiController(  968): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/ConfigService( 1531): onDestroy
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/WifiController(  968): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
D/WifiController(  968): battery changed pluggedType: 2
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiController(  968): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1489): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.577576 Y: -0.362320 Z: 9.782059 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.577576 .y:-0.362320 .z:9.782059
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.585846 Y: -0.375916 Z: 9.782349 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.585846 .y:-0.375916 .z:9.782349
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4211): [399] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4211): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/WifiController(  968): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED,
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/WifiController(  968): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.578964 Y: -0.328445 Z: 9.807785 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.578964 .y:-0.328445 .z:9.807785
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.581543 Y: -0.343430 Z: 9.810379 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.581543 .y:-0.343430 .z:9.810379
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.575043 Y: -0.348206 Z: 9.807968 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.575043 .y:-0.348206 .z:9.807968
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.573334 Y: -0.351685 Z: 9.818619 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.573334 .y:-0.351685 .z:9.818619
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092020053, nextTick: 59975, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092020057, nextTick: 59975, mDrawingTime: 0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WeatherService( 1835): 2 : TimeTick Intent has been received, Time(hour:min:sec) 19:27:0
,D/WeatherService( 1835): 2 : TimeTick Intent And Screen On
D/WeatherService( 1835): 2 : SDK version : 19
,D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1835): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1835): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1835): 2 : Map key string is -2
,D/lim     ( 1835): 2 : time = 19:27
I/WeatherReflect( 1835): Model Name : LG-D802
D/WeatherTheme( 1835): 2 : Different view - status_min_formatted : 26 != 27
,D/WeatherTheme( 1835): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1835): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1835): 2 : Fixed theme : optimus
,D/WeatherTheme( 1835): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1835): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 19:27:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,I/PowerManagerService(  968): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  968): [updateScreenState] screen on = false
,D/KnockOnPowerController(  968): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  968): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  968): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  968): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  968): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  968): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  968): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8871 usec
,D/qcom_sensors_hal(  968): hal_acquire_resources
,I/qcom_sensors_hal(  968): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  968): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  968): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  968): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  968): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  968): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  968): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  968): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.561432 Y: -0.359711 Z: 9.803986 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.561432 .y:-0.359711 .z:9.803986
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.571869 Y: -0.341980 Z: 9.805222 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.571869 .y:-0.341980 .z:9.805222
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,I/Sensors (  345): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  968): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  968): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  968): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  968): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  968): proximitySensorChanged  positive = true
I/KnockOnPowerController(  968): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.570572 Y: -0.319519 Z: 9.806778 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.570572 .y:-0.319519 .z:9.806778
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0,
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.578995 Y: -0.350739 Z: 9.816315 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.578995 .y:-0.350739 .z:9.816315
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.576813 Y: -0.348648 Z: 9.815704 
,V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.557938 Y: -0.348648 Z: 9.805725 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.576813 .y:-0.348648 .z:9.815704
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.586014 Y: -0.350845 Z: 9.820831 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.586014 .y:-0.350845 .z:9.820831
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  968): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43f0c380)
,D/KeyguardViewMediator( 1144): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1144): notifyScreenOnLocked
,D/SurfaceFlinger(  269): Screen released, type=0 flinger=0xb86c9450
,D/qdhwcomposer(  269): hwc_blank: Blanking display: 0
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/KeyguardViewMediator( 1144): handleNotifyScreenOn
,D/KeyguardViewManager( 1144): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  968): **** SHOWN CALLED ****
I/WindowManager(  968): No lock screen! windowToken=null
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.584717 Y: -0.353058 Z: 9.820297 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.584717 .y:-0.353058 .z:9.820297
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,E/SlideAside( 3998): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  968): handleScreenStateChanged: true
,D/WifiStateMachine(  968): handleMessage: E msg.what=131154
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2020): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  968): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  968): stopMonitoring
,D/wpa_supplicant( 2020): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131127
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131158
D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
,D/WifiStateMachine(  968): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=132097
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
,D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  968): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2020): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2020): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  968): handleMessage: X
,E/AudioSystem(  968): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=on, calling pid 968
V/SRS_Proc(  272): ParamSet string: screen_state=on
,D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=on
V/voice   (  272): voice_set_parameters: enter: screen_state=on
,V/voice   (  272): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  272): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  272): adev_set_parameters: exit with code(-2)
,I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
,V/EmotionalLed( 1158): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4326c790 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1158): enqueuing start. mLedList.size()=2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1158): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1835): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 19:27:10
,I/SlideAside( 3998): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
,D/WeatherAncestor( 1835): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 19:27:10
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/WeatherService( 1835): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1835): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.572845 Y: -0.355743 Z: 9.796921 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.572845 .y:-0.355743 .z:9.796921
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1158): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 243, B = 243
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1158): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 237, B = 237
E/BatteryObserver( 1158): usb Uevent not necessary.
,D/qdlights( 1158): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 231, B = 231
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.569534 Y: -0.350067 Z: 9.792450 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.569534 .y:-0.350067 .z:9.792450
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
D/qdhwcomposer(  269): hwc_blank: Done blanking display: 0
D/SurfaceControl(  968): Excessive delay in blankDisplay() while turning screen off: 381ms
D/qdlights( 1158): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 225, B = 225
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
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
,D/qdlights( 1158): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 189, B = 189
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
,D/qdlights( 1158): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092031173, nextTick: 48859, mDrawingTime: 1
,D/qdlights( 1158): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1158): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1158): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092031224, nextTick: 48809, mDrawingTime: 0
,D/qdlights( 1158): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1158): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 147, B = 147
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
D/qdlights( 1158): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 141, B = 141
,D/WeatherService( 1835): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:27:11
,D/WeatherService( 1835): 2 : ACTION screen on
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1835): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:27:11
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1158): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 135, B = 135
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/qdlights( 1158): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 129, B = 129
,D/WifiOffDelayIfNotUsed(  968): ACTION_SCREEN_ON
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=0, enabled=0
D/KeyguardViewMediator( 1144): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1144): notifyScreenOffLocked
,I/qcom_sensors_hal(  968): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  968): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1144): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/KeyguardViewMediator( 1144): handleNotifyScreenOff
,D/KeyguardViewManager( 1144): onScreenTurnedOff()
D/qdlights( 1158): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 123, B = 123
,I/[LGHome]EVENT( 1489): [Launcher.java:894:onPause()]onPause
,D/qcom_sensors_hal(  968): hal_acquire_resources
D/qcom_sensors_hal(  968): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  968): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=1000
V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1}
V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  968): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  968): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  968): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1158): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 117, B = 117
,V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,D/qdlights( 1158): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 111, B = 111
,I/[LGHome]EVENT( 1489): [Launcher.java:4955:onStop()]onStop
,I/LGImmersionVibrator(  968): Vibrator off
V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,D/WifiStateMachine(  968): handleScreenStateChanged: false
D/WifiStateMachine(  968): handleMessage: E msg.what=131154
D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131158
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 1
,E/AudioSystem(  968): AudioSystem::setParameters()...keyValue screen_state=off
,D/qdlights( 1158): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 105, B = 105
,V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=off, calling pid 968
V/SRS_Proc(  272): ParamSet string: screen_state=off
D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  272): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  272): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/ActivityManager(  968): Moving to STOPPED: ActivityRecord{4300a478 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  968): CMD_SCREEN_OFF 
D/WifiController(  968): shouldWifiStayAwake TRUE
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/qdlights( 1158): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 99, B = 99
D/VolumeVibrator( 1158): clear
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  968):    returned true
,D/WifiStateMachine(  968): handleMessage: X
,I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/qdlights( 1158): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 93, B = 93
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/qdlights( 1158): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 87, B = 87
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1835): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:27:11
D/WeatherService( 1835): 2 : ACTION screen off
D/WeatherService( 1835): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:27:11
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/qdlights( 1158): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 81, B = 81
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
D/NfcService( 1474): NFC-C OFF
V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): ACTION_SCREEN_OFF
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1158): set_light_notifications: 2,ff004b4b,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1158): set_light_notifications: 2,ff004545,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 69, B = 69
D/qdlights( 1158): set_light_notifications: 2,ff003f3f,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 63, B = 63
D/qdlights( 1158): set_light_notifications: 2,ff003939,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 57, B = 57
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1158): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 51, B = 51
E/BatteryObserver( 1158): usb Uevent not necessary.
,D/qdlights( 1158): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 45, B = 45
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
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
,D/qdlights( 1158): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  345): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): handleMessage: X
,D/KeyguardViewMediator( 1144): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1144): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/KeyguardViewMediator( 1144): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1144): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092049184009429; DSPS: 5275792; Offset: 1454091888179614898
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092069185331557; DSPS: 5931195; Offset: 1454091888179624770
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092080049, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092080062, nextTick: 59970, mDrawingTime: 0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092089186273372; DSPS: 6586586; Offset: 1454091888179620540
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1531): Vacuum at: now=1454092093875 tag=VacuumService
,I/GoogleURLConnFactory( 1531): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1531): No account for auth token provided
,D/dalvikvm( 1531): GC_EXPLICIT freed 1424K, 29% free 17868K/24832K, paused 3ms+3ms, total 31ms
,D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0,
,W/Uploader( 1531): No account for auth token provided
,W/Uploader( 1531):  no longer exists, so no auth token.
,W/Uploader( 1531): No account for auth token provided
,D/wpa_supplicant( 2020): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: BSS: Remove id 3 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:37:b7:9d:3e:73]
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092109187638781; DSPS: 7241991; Offset: 1454091888179612658
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092129188920492; DSPS: 7897392; Offset: 1454091888179643149
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092140045, nextTick: 59984, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092140059, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092149190894964; DSPS: 8552817; Offset: 1454091888179633978
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092169192220112; DSPS: 9208221; Offset: 1454091888179616353
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092189193512501; DSPS: 9863623; Offset: 1454091888179627003
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092200041, nextTick: 59973, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092200053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092209194864211; DSPS: 10519027; Offset: 1454091888179635940
,D/dalvikvm( 2658): GC_CONCURRENT freed 7769K, 33% free 16864K/24832K, paused 2ms+1ms, total 38ms
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x42d801d0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1531): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1531): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1531): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1531): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1531): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1531): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1531): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1531): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4211): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4211): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4211): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4211): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4211): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4211): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4211): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4211): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4211): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4211): isDataSchedulerEnabled():false
D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092229196272069; DSPS: 11174433; Offset: 1454091888179639989
,I/LocationManagerService(  968): remove 4330a348
,D/LocationManagerService(  968): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  968): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  968): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  968): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  968): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2658): GC_CONCURRENT freed 1601K, 31% free 17310K/24832K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 2658): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/Mlt MonitorService( 2658): parseLastkmsg to dump
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092249197612738; DSPS: 11829837; Offset: 1454091888179637885
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092260050, nextTick: 59977, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092260053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092269198900646; DSPS: 12485239; Offset: 1454091888179644055
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092289200800328; DSPS: 13140662; Offset: 1454091888179621129
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092309201676778; DSPS: 13796051; Offset: 1454091888179612570
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092320035, nextTick: 59993, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092320038, nextTick: 59993, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092329202107759; DSPS: 14451425; Offset: 1454091888179616304
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092349203437023; DSPS: 15106828; Offset: 1454091888179633313
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092369203859567; DSPS: 15762202; Offset: 1454091888179628610
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092380043, nextTick: 59986, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092380056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092389204348674; DSPS: 16417578; Offset: 1454091888179629436
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092409205249760; DSPS: 17072968; Offset: 1454091888179614995
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092429205677045; DSPS: 17728342; Offset: 1454091888179615034
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092440036, nextTick: 59992, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092440039, nextTick: 59992, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092449206564745; DSPS: 18383731; Offset: 1454091888179617724
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092469207856143; DSPS: 19039133; Offset: 1454091888179627384
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092489208707906; DSPS: 19694521; Offset: 1454091888179624655
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092500043, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092500062, nextTick: 59971, mDrawingTime: 0
,D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2020): nl80211: Disconnect event
D/wpa_supplicant( 2020): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2020): wlan0: Deauthentication notification
D/wpa_supplicant( 2020): wlan0:  * reason 0
D/wpa_supplicant( 2020): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2020): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2020): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2020): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2020): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2020): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2020): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,D/WifiStateMachine(  968): handleMessage: E msg.what=147460
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb80e2d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP]),
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): Network connection lost
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  968): Stopping DHCP and clearing IP
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  968): doBoolean: SET ps 1
,D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
D/CommandListener(  266): Clearing all IP addresses on wlan0
D/DhcpStateMachine(  968): RunningState{ when=-6ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  968): addressRemoved: 192.168.1.160/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  968): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/wpa_supplicant( 2020): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2020): wlan0: nl80211: scan request
,D/wpa_supplicant( 2020): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2020): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2020): wlan0: nl80211: Scan trigger
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/WifiHS20(  968): hidePasspointNotification off =false
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
D/QCNEA   (  395): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  395): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  395): |CAC| updateNetCfgInfo
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC|                   Netconfig               
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  395): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  395): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  395): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  395): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  395): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  395): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| Received bssid= 
D/QCNEA   (  395): |CAC| net type = 3
V/QCNEA   (  395): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  395): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  395): |CAC| 	ssid           =NG700
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  395): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  395): |CAC| dispatchNetCfg: updating:0xb782f8dc
D/QCNEA   (  395): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
,D/QcConnectivityService(  968): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/QcConnectivityService(  968): Attempting to switch to mobile
D/QcConnectivityService(  968): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  968): handleConnectivityChange: preConnState=1 connState=2
,I/ActivityManager(  968): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5369 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  968): invokeExitMethods: ConnectedState
D/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131213
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131213
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  968): handleMessage: X
,D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5369): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5369): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5369): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,I/PCSuite ( 5369): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5369): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5369): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  266): RouteController
,W/NetworkManagementService(  968): route cmd failed: 
W/NetworkManagementService(  968): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  968): '
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  968): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  968): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  968): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  968): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  968): android_net_utils_resetConnections in env=0x62821170 clazz=0x69f00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  968): resetConnections(wlan0, 3)
,I/ActivityManager(  968): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5412 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  968): Killing 3866:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,V/NativeCrypto( 1531): Read error: ssl=0x62726098: I/O error during system call, Connection timed out
,V/NativeCrypto( 1531): SSL shutdown failed: ssl=0x62726098: I/O error during system call, Broken pipe
,D/DhcpStateMachine(  968): StoppedState
,D/HyLog   ( 5412): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5412): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5412): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/GpsLocationProvider(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 5412): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 5412): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 5412): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 5412): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 5412): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 5412): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 5412): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5412): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5412): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  968): Killing 4306:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2020): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2020): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2020): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 2020): nl80211: Survey data missing
D/wpa_supplicant( 2020): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2020): wlan0: BSS: Add new id 4 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: BSS: Add new id 5 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: BSS: Add new id 6 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 2020): wlan0: New scan results available
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2020): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2020): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2020): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2020): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2020): WPS: AP[2] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2020): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2020): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-55 wps
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2020): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2020): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-74
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: 3: 00:37:b7:9d:3e:73 ssid='FunBox2-3E72' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-89 wps
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2020): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2020): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2020): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-55 wps
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2020): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2020): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg m,dm allow/disallow auto connect is not set 
D/wpa_supplicant( 2020): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb80e45a8  current_ssid=0x0
D/wpa_supplicant( 2020): scard is not null..
D/wpa_supplicant( 2020): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
,D/wpa_supplicant( 2020): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
,D/wpa_supplicant( 2020): TDLS: TDLS is allowed in the target BSS,
,I/wpa_supplicant( 2020): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 2020): wlan0: Cancelling scan request
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): wlan0: WPA: clearing own WPA/RSN IE
,D/wpa_supplicant( 2020): wlan0: Automatic auth_alg selection: 0x1,
D/wpa_supplicant( 2020): RSN: PMKSA cache search - network_ctx=0xb80e45a8 try_opportunistic=0
D/wpa_supplicant( 2020): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2020): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2020): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2020): wlan0: WPA: clearing AP WPA IE
,D/wpa_supplicant( 2020): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): wlan0: WPA: using GTK CCMP,
D/wpa_supplicant( 2020): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2020): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2020): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2020): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
,D/wpa_supplicant( 2020): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2020): wlan0: State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2020): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2020): nl80211: Set mode ifindex 23 iftype 2 (STATION),
D/wpa_supplicant( 2020): nl80211: Unsubscribe mgmt frames handle 0xb80e3590 (mode change),
D/wpa_supplicant( 2020): nl80211: Subscribe to mgmt frames with non-AP handle 0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
,D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590,
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0e,
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=1): 06
,D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 0a 07
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 38:f8:89:11:e9:11]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 00:37:b7:9d:3e:73]
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2020): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2020):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020):   * freq=2412
D/wpa_supplicant( 2020):   * SSID - hexdump(len=5): 4e 47 37 30 30,
D/wpa_supplicant( 2020):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020):   * Auth Type 0
D/wpa_supplicant( 2020):   * WPA Versions 0x2
,D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/wpa_supplicant( 2020): nl80211: Connect request send successfully
D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  968): handleMessage: E msg.what=147461
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  968): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2020): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
,D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2020): nl80211: Connect event
D/wpa_supplicant( 2020): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2020): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2020): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2020): wlan0: Association info event
D/wpa_supplicant( 2020): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2020): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2020): wlan0: freq=2412 MHz
D/wpa_supplicant( 2020): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2020): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2020): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2020): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): scard is not null..
D/wpa_supplicant( 2020): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2020): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2020): TDLS: Remove peers on association
D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2020): EAPOL: enable timer tick
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): wlan0: Cancelling scan request
,D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  968): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
,D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/wpa_supplicant( 2020): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 8f af 2d c0 29 ba cf e6 33 fe b6 55 89 20 48 ...
D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2020): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2020): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2020): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2020):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2020):   key_nonce - hexdump(len=32): 8f af 2d c0 29 ba cf e6 33 fe b6 55 89 20 48 86 7f d3 7f e1 62 c3 99 50 d8 eb 97 4f 01 05 91 ac
D/wpa_supplicant( 2020):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 8f af 2d c0 29 ba cf e6 33 fe b6 55 89 20 48 ...
D/wpa_supplicant( 2020): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2020): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2020): Get randomness: len=32 entropy=5
,D/wpa_supplicant( 2020): WPA: Renewed SNonce - hexdump(len=32): c5 32 42 f5 41 ec 09 35 5c 1c 9f 78 bc 1f 1d a4 62 2e 63 23 3b bc 4c 21 5d 87 89 86 10 00 26 e3
D/wpa_supplicant( 2020): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): WPA: Nonce1 - hexdump(len=32): c5 32 42 f5 41 ec 09 35 5c 1c 9f 78 bc 1f 1d a4 62 2e 63 23 3b bc 4c 21 5d 87 89 86 10 00 26 e3
D/wpa_supplicant( 2020): WPA: Nonce2 - hexdump(len=32): 8f af 2d c0 29 ba cf e6 33 fe b6 55 89 20 48 86 7f d3 7f e1 62 c3 99 50 d8 eb 97 4f 01 05 91 ac
D/wpa_supplicant( 2020): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2020): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2020): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2020): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2020): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2020): WPA: Derived Key MIC - hexdump(len=16): 40 07 4b 26 67 aa 28 4e e8 08 a4 48 68 37 ad 86
,D/wpa_supplicant( 2020): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 c5 32 42 f5 41 ec 09 35 5c 1c 9f 78 bc 1f 1d ...
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
,D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,D/wpa_supplicant( 2020): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 8f af 2d c0 29 ba cf e6 33 fe b6 55 89 20 48 ...
D/wpa_supplicant( 2020): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2020): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2020): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2020): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2020):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2020):   key_nonce - hexdump(len=32): 8f af 2d c0 29 ba cf e6 33 fe b6 55 89 20 48 86 7f d3 7f e1 62 c3 99 50 d8 eb 97 4f 01 05 91 ac
D/wpa_supplicant( 2020):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_rsc - hexdump(len=8): 7c 59 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_mic - hexdump(len=16): 08 db 05 d8 11 ed c6 1c c9 2f 46 67 88 35 47 77
D/wpa_supplicant( 2020): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 8f af 2d c0 29 ba cf e6 33 fe b6 55 89 20 48 ...
D/wpa_supplicant( 2020): RSN: encrypted key data - hexdump(len=56): ef 3c 8a 1e fd a1 c6 8a 54 62 53 e0 33 59 13 44 a6 99 66 f9 53 5d ed ac fa 21 e9 be 14 11 36 99 ...
D/wpa_supplicant( 2020): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2020): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2020): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2020): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 fc e6 ...
D/wpa_supplicant( 2020): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2020): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2020): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2020): WPA: Derived Key MIC - hexdump(len=16): 77 4f 44 e0 4e 64 45 c0 d2 7b b3 53 39 be 5a ce
,D/wpa_supplicant( 2020): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2020): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb80e3c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2020):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2020): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2020): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED],
,D/wpa_supplicant( 2020): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2020): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2020): WPA: RSC - hexdump(len=6): 7c 59 00 00 00 00
,D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f2d03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2020):    broadcast key
I/wpa_supplicant( 2020): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2020): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2020): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2020): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2020): EAPOL authentication completed successfully
,D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X,
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): Network connection established
,D/WifiNative-wlan0(  968): doString: STATUS
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2020): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  968):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  968): ssid=NG700
D/WifiNative-wlan0(  968): id=0
D/WifiNative-wlan0(  968): mode=station
D/WifiNative-wlan0(  968): pairwise_cipher=CCMP
D/WifiNative-wlan0(  968): group_cipher=CCMP
D/WifiNative-wlan0(  968): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  968): wpa_state=COMPLETED
D/WifiNative-wlan0(  968): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  968): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  968): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  968): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :false
D/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
D/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  968): handleMessage: X
D/DhcpStateMachine(  968): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/DhcpStateMachine(  968): WaitBeforeStartState
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-39ms what=147462 obj=android.net.wifi.StateChangeResult@438201b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WifiStateMachine(  968): ObtainingIpState{ when=-32ms what=147462 obj=android.net.wifi.StateChangeResult@44567230 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: ObtainingIpState
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  968): ObtainingIpState{ when=-26ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196612
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/AppUp4:CustModeStarterReceiver( 3975): onReceive
D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
D/AppUp4:CustFacade( 3975): isPhone : true
I/LicenseContentProvider( 2986): start selecting data
D/SIMObserver( 2986): simInfo1
I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3975): begin check event
I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity
,I/ActivityManager(  968): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5456 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 5456): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5456): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5456): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doBoolean: SET ps 0
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  968):    returned null
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  968):    returned null
D/DhcpStateMachine(  968): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  968): DHCP Start wake lock is acquired.
E/WifiStateMachine(  968): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  266): Setting iface cfg,
D/CommandListener(  266): Trying to bring up wlan0
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43040798 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43040798 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): addressUpdated: 192.168.1.160/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  968): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ObtainingIpState
,D/dalvikvm(  968): GC_CONCURRENT freed 2398K, 44% free 30608K/53812K, paused 11ms+13ms, total 183ms
D/dalvikvm(  968): WAIT_FOR_CONCURRENT_GC blocked 34ms
D/WifiStateMachine(  968): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.160/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
,D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196613
,D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-37ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,V/DownloadManager( 5456): DownloadService onCreate
,I/DownloadManager( 5456): in removeSpuriousFiles
D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doBoolean: SET ps 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/EAS     ( 4542): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4542): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/eas_req ( 4542): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): DHCP successful
,V/DownloadManager( 5456): DownloadService onStartCommand
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  968): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
,D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  968): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  968): VerifyingLinkState enter
D/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  968): handleMessage: X
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  968): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
D/WifiStateMachine(  968): handleMessage: E msg.what=135190
D/WifiStateMachine(  968): processMsg: VerifyingLinkState
E/Parcel  (  395): Reading a NULL string not supported here.
,W/WifiStateTracker(  968): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  968): 
W/WifiStateTracker(  968):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  968):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  968): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WifiStateMachine(  968): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  968): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): CaptivePortalCheckState enter
D/WifiStateMachine(  968): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/WifiStateMachine(  968): handleMessage: X
V/DownloadManager( 5456): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5456): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  968): handleMessage: E msg.what=131092
D/WifiStateMachine(  968): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  968): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  968): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
E/Parcel  (  395): Reading a NULL string not supported here.
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@42840280 on behalf of 5456
D/WifiStateMachine(  968): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/LgeMiscReceiver( 4329): networkInfo.isConnected() = false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  968): transitionTo: destState=ConnectedState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  968): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
I/DownloadManager( 5456): in trimDatabase
V/DownloadManager( 5456): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@428430a8 on behalf of 5456
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@428419b0 on behalf of 5456
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/linker  ( 4542): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4542): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4542): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4542): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4542): threadid=1: recursive native library load attempt (/system/lib/lib,HtmlEditor.so)
D/HtmlEditor( 4542): register_HtmlEditor, Success
D/HtmlEditor( 4542): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4542): register_HtmlEditorTimer, Success
D/HtmlEditor( 4542): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4542): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4542): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4542): register_HtmlEditorFont, Success
D/HtmlEditor( 4542): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4542): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4542): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4542): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4542): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4542): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4542): JNI_OnLoad Success
I/HubEmail( 4542): JNI_OnLoad()
I/HubEmail( 4542): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4542): registerNatives()
I/HubEmail( 4542): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4542): registerNativeMethods()
I/HubEmail( 4542): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5479 uid=10052 gids={50052, 3003}
V/DownloadManager( 5456): DownloadService onDestroy
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
E/ActivityThread(  968): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  968): handleConnectivityChange: preConnState=2 connState=1
W/Settings( 4542): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/        (  266): RouteController
D/HyLog   ( 5479): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5479): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5479): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  266): RouteController
I/ActivityManager(  968): Killing 4451:com.android.defcontainer/u0a4 (adj 15): empty #17
,V/        (  266): RouteController
,V/        (  266): RouteController
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  266): RouteController
,V/LGRssiData( 5479): [loadRssi] File not exist 
D/MobileConnectivityChangeReceiver( 5479): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,V/LGRssiData( 5479): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5479): [loadFeatureFromXml] *** start feature loading from xml
,D/MobileConnectivityChangeReceiver( 5479): onReceive CONNECTIVITY_CHANGE networkType=1
,W/BaseRuntimeLoader( 5479): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5479): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5479): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
V/        (  266): RouteController
,W/BaseRuntimeLoader( 5479): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 5479): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5479): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5479): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/DhcpStateMachine(  968): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  968): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,V/        (  266): RouteController
,V/        (  266): RouteController
,I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5508 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  968): Killing 4501:com.google.android.partnersetup/u0a9 (adj 15): empty #17
V/        (  266): RouteController
,E/PhoneMonitor( 5479): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5479): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/QCNEA   (  395): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  395): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  395): |CAC| updateNetCfgInfo
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC|                   Netconfig               
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  395): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  395): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  395): |CAC| 	NetConfig: ip4        =192.168.1.160
V/QCNEA   (  395): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  395): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  395): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  395): |CAC| net type = 1
V/QCNEA   (  395): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  395): |CAC| Received ssid= NG700
V/QCNEA   (  395): |CAC| 	ssid           =NG700
V/QCNEA   (  395): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  395): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  395): |CAC| dispatchNetCfg: updating:0xb782f8dc
,D/QCNEA   (  395): |CAC| readCallback: read len:0, ret:-1, errno:11
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/HyLog   ( 5508): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
D/HyLog   ( 5508): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5508): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/CheckinService( 1943): Checking schedule, now: 1454092507739 next: 1454091953837
,I/CheckinService( 1943): active receiver: enabled
,I/CheckinService( 1943): Preparing to send checkin request
,I/EventLogService( 1943): Accumulating logs since 1454091920512
,I/CheckinRequestBuilder( 1943): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  968): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5534 uid=10066 gids={50066, 4002, 3003, 1028}
,E/ActivityThread( 1943): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 5534): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5534): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5534): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  968): Killing 4527:com.lge.bnr/1000 (adj 15): empty #17
D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  968): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5547 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 5547): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5547): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5547): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5547): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  968): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5561 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  968): Killing 4179:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5561): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5561): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5561): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 5561): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5561): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5561): intf.getDisplayName() = lo
I/Wireless_Storage( 5561): intf.getDisplayName() = sit0
I/Wireless_Storage( 5561): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5561): intf.getDisplayName() = teql0
I/Wireless_Storage( 5561): intf.getDisplayName() = wlan0
,D/NFS     ( 5561): interface name:wlan0 name:wlan0
,D/NFS     ( 5561): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
,D/NFS     ( 5561): interface name:wlan0 name:wlan0
D/NFS     ( 5561): addr:192.168.1.160 broadcast:192.168.1.255
,I/Wireless_Storage( 5561): CONNECT : WIFI_CONNECT
,I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5573 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  968): Killing 4195:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 5573): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5573): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5573): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x43ede1c8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1943): awaiting user notification for token
D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GAV2    ( 5573): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  968): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5590 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5590): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5590): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5590): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5590): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5590): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 5590): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5590): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5590): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 5590): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5590): install
,I/MultiDex( 5590): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5590): loading existing secondary dex files
,I/MultiDex( 5590): load found 3 secondary dex files
,I/MultiDex( 5590): install done
,D/dalvikvm( 5590): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 5590): VFY: unable to resolve instance field 61
,D/dalvikvm( 5590): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5590): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5590): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5590): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5590): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5590): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5590): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 5590): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5590): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5590): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42809850
,D/dalvikvm( 5590): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42809850
,D/dalvikvm( 5590): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42809850, skipping init
,D/dalvikvm( 5590): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42809850
,D/dalvikvm( 5590): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42809850
,V/JNIHelp ( 5590): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/wpa_supplicant( 2020): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2020): EAPOL: disable timer tick
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WebViewChromium( 5573): Binding Chromium to the main looper Looper (main, tid 1) {428026a0}
,I/chromium( 5573): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5573): Initializing chromium process, renderers=0
,D/dalvikvm( 5590): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42809850
D/dalvikvm( 5590): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42809850
D/dalvikvm( 5590): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42809850
,D/dalvikvm( 5590): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42809850
,W/chromium( 5573): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5573): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5573): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5573): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5573): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5573): Remote Branch: 
I/Adreno-EGL( 5573): Local Patches: 
I/Adreno-EGL( 5573): Reconstruct Branch: 
,I/NSApplication( 5573): Starting up...
,I/ProviderInstaller( 5590): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  968): Killing 4559:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 5412): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5412): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5412): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/dalvikvm( 5590): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5590): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5590): VFY: replacing opcode 0x6e at 0x000d
,I/QRemote ( 5412): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/dalvikvm( 5590): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5590): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5590): VFY: replacing opcode 0x6e at 0x0201
,D/QRemote ( 5412): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5412): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5369): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5369): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5412): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5412): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5412): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5412): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1531): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AuthorizationBluetoothService( 1531): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1531): Proximity feature is not enabled.
,D/WVCdm   (  272): Instantiating CDM.
,I/WVCdm   (  272): Level3 Library Nov 20 2013 18:09:31
,V/GmsCoreStatsServiceLauncher( 1943): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DrmWidevineDash(  272): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  272): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  272): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f66000
,E/DrmWidevineDash(  272): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f66000
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  968): NetTransition Wakelock for ConnectedState released by timeout
D/DrmWidevineDash(  272): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_APIVersion...
,D/WearableService( 1870): callingUid 10006, callindPid: 1870
,E/MDM     ( 1424): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DrmWidevineDash(  272): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  272): calling OEMCrypto_IsKeyboxValid...
,D/LocationInitializer( 1943): Restart initialization of location
,D/DrmWidevineDash(  272): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  272): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  272): CdmEngine::OpenSession
,D/DrmWidevineDash(  272): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  272): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  272): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  272): PrepareKeyRequest: nonce=2144265091
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5590): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/lib/libd317EF1D9D4A2.so 0x429d5e50
D/dalvikvm( 5590): Added shared lib /data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/lib/libd317EF1D9D4A2.so 0x429d5e50
,D/dalvikvm( 5590): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/lib/libd317EF1D9D4A2.so 0x429d5e50, skipping init
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  272): CdmEngine::CloseSession
,D/DrmWidevineDash(  272): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5590): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  968): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
,D/WifiStateMachine(  968): processMsg: DefaultState
,D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): handleMessage: X
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  968): send additional Connectivity Action
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/QcConnectivityService(  968): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  968):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  968): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 5638): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 5590): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5590): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 115ms
,I/Adreno-EGL( 5590): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5590): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5590): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5590): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5590): Remote Branch: 
I/Adreno-EGL( 5590): Local Patches: 
I/Adreno-EGL( 5590): Reconstruct Branch: 
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092509209896441; DSPS: 20349920; Offset: 1454091888179623004
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 5590): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/WVCdm   (  272): CdmEngine::OpenSession
,D/DrmWidevineDash(  272): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession returns 0
I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  272): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  272): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  272): PrepareKeyRequest: nonce=3954898548
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  272): CdmEngine::CloseSession
,D/DrmWidevineDash(  272): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 5590): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5590): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5590): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5590): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5590): Remote Branch: 
I/Adreno-EGL( 5590): Local Patches: 
I/Adreno-EGL( 5590): Reconstruct Branch: 
,I/Adreno-EGL( 5590): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5590): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5590): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5590): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5590): Remote Branch: 
I/Adreno-EGL( 5590): Local Patches: 
I/Adreno-EGL( 5590): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1943): Classify the device as Phone.
,V/NativeCrypto( 1943): SSL shutdown failed: ssl=0x6b73e738: I/O error during system call, Connection timed out
,D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1943): Sending checkin request (11631 bytes)
,D/DhcpStateMachine(  968): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  968): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  968): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.160
V/LgDhcpStateMachineHelper(  968): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  968): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  968): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  968): RunningState
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=-6ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
,D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 2986): start selecting data
,D/SIMObserver( 2986): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3975): begin check event
I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3975): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 3975): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3975): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3975): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3975): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4542): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5456): DownloadService onCreate
,D/EAS     ( 4542): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4542): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4329): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 5479): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5479): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 5456): in removeSpuriousFiles
,V/DownloadManager( 5456): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@42849360 on behalf of 5456
,I/DownloadManager( 5456): in trimDatabase
,V/DownloadManager( 5456): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@4284ad18 on behalf of 5456
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/DownloadManager( 5456): DownloadService onStartCommand
,V/DownloadManager( 5456): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Settings( 4542): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMSGCM( 5547): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 5547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@4284cec8 on behalf of 5456
D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 5456): DownloadService onDestroy
I/NFS     ( 5561): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5561): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 2986): start selecting data
,D/SIMObserver( 2986): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5456): DownloadService onCreate
,I/DownloadManager( 5456): in removeSpuriousFiles
,D/EAS     ( 4542): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 5456): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4542): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@42851ac0 on behalf of 5456
,V/DownloadManager( 5456): DownloadService onStartCommand
,V/DownloadManager( 5456): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5456): in trimDatabase
V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@42853b68 on behalf of 5456
,V/DownloadManager( 5456): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@42854bc0 on behalf of 5456
I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 4542): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4329): networkInfo.isConnected() = true
,D/PhoneState( 4329): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5479): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5479): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5456): DownloadService onDestroy
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  968): GC_EXPLICIT freed 1858K, 44% free 30540K/53812K, paused 4ms+16ms, total 182ms
,D/LGDMSGCM( 5547): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 5547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 5561): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5561): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1943): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1943): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,D/GCM     ( 1531): Connected
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1531): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x43341560: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1943): awaiting user notification for token
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1943): Classify the device as Phone.
,D/dalvikvm( 1144): GC_FOR_ALLOC freed 6989K, 13% free 69340K/79572K, paused 54ms, total 54ms
,I/CheckinTask( 1943): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1943): Checking schedule, now: 1454092511774 next: 1454669907768
,I/CheckinService( 1943): active receiver: disabled
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinService( 1943): Checking schedule, now: 1454092511822 next: 1454669907768
,I/CheckinService( 1943): active receiver: disabled
,D/GCM     ( 1531): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1531): GC_CONCURRENT freed 1764K, 28% free 18031K/24832K, paused 3ms+4ms, total 43ms
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 2986): start selecting data
,D/SIMObserver( 2986): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5456): DownloadService onCreate
,I/DownloadManager( 5456): in removeSpuriousFiles
D/EAS     ( 4542): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5456): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4542): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@42859340 on behalf of 5456
,I/DownloadManager( 5456): in trimDatabase
,V/DownloadManager( 5456): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@4285a940 on behalf of 5456
,V/DownloadManager( 5456): DownloadService onStartCommand
I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4329): networkInfo.isConnected() = true
,D/PhoneState( 4329): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5479): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5479): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4542): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5456): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5456): created cursor android.database.sqlite.SQLiteCursor@4285c9a8 on behalf of 5456
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 5456): DownloadService onDestroy
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMSGCM( 5547): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 5547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5561): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5561): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ProcessCpuTracker(  968): Skipping unknown process pid 5716
,W/ProcessCpuTracker(  968): Skipping unknown process pid 5719
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received.
W/ProcessCpuTracker(  968): Skipping unknown process pid 5742
D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/ProcessCpuTracker(  968): Skipping unknown process pid 5745
W/ProcessCpuTracker(  968): Skipping unknown process pid 5747
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,V/WifiServiceExtension(  968): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 5573): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  968): Killing 5369:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  968): Killing 4211:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3998): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3998): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  968): Handling package changes for user 0
,I/InputReader(  968): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5765 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,W/ActivityManager(  968): getAssistContextExtras failed: no resumed activity
,W/ActivityManager(  968): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "sms"
,D/dalvikvm(  270): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 3ms+3ms, total 65ms
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  270): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 7ms+3ms, total 48ms
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  270): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 23ms
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
,D/HyLog   ( 5765): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5765): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5765): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm( 2658): GC_CONCURRENT freed 2502K, 33% free 16731K/24832K, paused 19ms+1ms, total 55ms
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "sms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5765): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5765): MmsConfig.loadMmsSettings
,I/Babel   ( 5765): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5765): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5765): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 5765): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5765): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5765): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5765): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5765): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5765): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5765): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5765): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5765): MmsConfig.loadFromResources
,E/Babel   ( 5765): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5765): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1424): DISABLE
,W/Settings( 5765): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5765): [loadRssi] File not exist 
V/LGRssiData( 5765): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5765): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5765): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5765): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5765): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 3975): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 3975): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3975): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
,D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 2986): start selecting data
,D/SIMObserver( 2986): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3975): begin check event
D/AppUp4:Utils( 3975): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3975): Event For Nothing, skip.
,I/ActivityManager(  968): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5817 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5817): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5817): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5817): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  968): applying state to connected service
,D/LocationProviderProxy(  968): applying state to connected service
,I/SystemConfig( 5817): BUILD Country: EU
,I/SystemConfig( 5817): BUILD Operator: OPEN
I/ActivityManager(  968): Killing 5412:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  968): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5832 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,I/SystemConfig( 5817): systemFeature RCS result false
,D/SystemConfig( 5817): refreshRcsSupport() :false
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  968): Killing 5456:android.process.media/u0a23 (adj 15): empty #17
,D/HyLog   ( 5832): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5832): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5832): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  968): Killing 4542:com.lge.email/u0a24 (adj 15): empty #17
,I/IcingCorporaProvider( 2672): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  968): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5848 uid=10050 gids={50050, 3003, 1028, 1015}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5848): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5848): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5848): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5848): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 5848): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5848): VFY: replacing opcode 0x6e at 0x000b
,D/dalvikvm( 1943): GC_CONCURRENT freed 1915K, 22% free 19562K/24832K, paused 3ms+8ms, total 66ms
,D/Finsky  ( 5848): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5848): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5848): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5848): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5848): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5848): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5848): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5848): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5848): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5848): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5848): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5848): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 5848): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5848): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 5848): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5848): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5848): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5848): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5848): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5848): VFY: replacing opcode 0x6e at 0x029a
,I/ActivityManager(  968): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=5882 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/IcingCorporaProvider( 2672): UpdateCorporaTask done [took 326 ms] updated apps [took 326 ms] 
I/dalvikvm( 5848): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5848): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5848): VFY: replacing opcode 0x6e at 0x001a
,D/HyLog   ( 5882): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5882): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5882): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5848): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 5848): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5848): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5848): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5848): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1943): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1943): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 5882): DownloadService onCreate
,I/DownloadManager( 5882): in removeSpuriousFiles
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@4283cf80 on behalf of 5882
,I/DownloadManager( 5882): in trimDatabase
V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42842d20 on behalf of 5848
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  968): GC_EXPLICIT freed 2200K, 43% free 30706K/53756K, paused 4ms+15ms, total 161ms
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42843098 on behalf of 5882
D/Finsky  ( 5848): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 5882): DownloadService onStartCommand
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@428477c0 on behalf of 5882
,V/DownloadManager( 5882): DownloadService onDestroy
,D/Finsky  ( 5848): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  968): Killing 5479:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5848): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5848): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5848): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5848): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5848): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5848): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5848): Total arena pages for JIT: 11
,I/dalvikvm( 5848): Total arena pages for JIT: 12
I/dalvikvm( 5848): Total arena pages for JIT: 13
,I/dalvikvm( 5848): Total arena pages for JIT: 14
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5848): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5848): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  968): Checking http://216.58.209.46/generate_204
,D/Finsky  ( 5848): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5848): [1] DailyHygiene.reschedule: Giving up. (failures=6)
D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,D/CaptivePortalTracker(  968): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  968): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  968): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  968): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 5765): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  968): Killing 5508:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092529210897007; DSPS: 21005313; Offset: 1454091888179616490
,D/Finsky  ( 5848): [465] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5848): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092549211807624; DSPS: 21660702; Offset: 1454091888179642097
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092560050, nextTick: 59977, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092560063, nextTick: 59970, mDrawingTime: 0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092569212804491; DSPS: 22316095; Offset: 1454091888179631884
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092589214101202; DSPS: 22971498; Offset: 1454091888179616339
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092609214949424; DSPS: 23626885; Offset: 1454091888179640587
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092620052, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092620054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092629216239415; DSPS: 24282288; Offset: 1454091888179618322
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092649217135345; DSPS: 24937677; Offset: 1454091888179629242
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092669217554765; DSPS: 25593051; Offset: 1454091888179621416
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092680043, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092680057, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092689217999132; DSPS: 26248425; Offset: 1454091888179638537
,D/wpa_supplicant( 2020): wlan0: BSS: Remove id 4 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: BSS: Remove id 5 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: BSS: Remove id 6 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 38:f8:89:11:e9:11]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:37:b7:9d:3e:73]
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092709218887354; DSPS: 26903814; Offset: 1454091888179641749
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092729220327712; DSPS: 27559222; Offset: 1454091888179617263
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092740042, nextTick: 59976, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092740051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092749222652755; DSPS: 28214658; Offset: 1454091888179622970
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092769223987799; DSPS: 28870062; Offset: 1454091888179615241
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092789224850761; DSPS: 29525450; Offset: 1454091888179623711
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092800043, nextTick: 59976, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092800052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092809225280545; DSPS: 30180824; Offset: 1454091888179626249
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x429254a0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1531): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1531): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1531): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1531): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1531): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1531): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1531): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1531): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5848): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5848): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5848): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5848): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5848): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5848): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5848): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5848): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 5848): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5848): isDataSchedulerEnabled():false
D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092829226225225; DSPS: 30836215; Offset: 1454091888179624884
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092849227750374; DSPS: 31491625; Offset: 1454091888179624154
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092860062, nextTick: 59966, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092860063, nextTick: 59970, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2020): nl80211: Disconnect event
D/wpa_supplicant( 2020): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2020): wlan0: Deauthentication notification
D/wpa_supplicant( 2020): wlan0:  * reason 0
D/wpa_supplicant( 2020): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2020): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2020): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2020): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2020): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2020): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2020): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,D/WifiStateMachine(  968): handleMessage: E msg.what=147460,
D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState,
D/WifiStateMachine(  968): processMsg: ConnectModeState,
D/WifiStateMachine(  968): Network connection lost
,D/WifiStateMachine(  968): Stopping DHCP and clearing IP,
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  968): doBoolean: SET ps 1
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb80e2d6c key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2020):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): wlan0: State: COMPLETED -> DISCONNECTED
,D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state INITIALIZE,
,D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  968):    returned true
,D/DhcpStateMachine(  968): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  266): Clearing all IP addresses on wlan0
D/WifiStateMachine(  968): addressRemoved: 192.168.1.160/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  968): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
D/QCNEA   (  395): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  395): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  395): |CAC| updateNetCfgInfo
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC|                   Netconfig               
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  395): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  395): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  395): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  395): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  395): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  395): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| Received bssid= 
D/QCNEA   (  395): |CAC| net type = 3
V/QCNEA   (  395): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  395): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  395): |CAC| 	ssid           =NG700
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  395): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  395): |CAC| dispatchNetCfg: updating:0xb782f8dc
,D/QCNEA   (  395): |CAC| readCallback: read len:0, ret:-1, errno:11
D/wpa_supplicant( 2020): wlan0: State: DISCONNECTED -> SCANNING
,D/WifiHS20(  968): hidePasspointNotification off =false
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2020): wlan0: nl80211: scan request
D/wpa_supplicant( 2020): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2020): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2020): wlan0: nl80211: Scan trigger
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
D/QcConnectivityService(  968): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/QcConnectivityService(  968): Attempting to switch to mobile
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/QcConnectivityService(  968): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  968): handleConnectivityChange: preConnState=1 connState=2
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  968): invokeExitMethods: ConnectedState
D/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131213
D/WifiStateMachine(  968): processMsg: DisconnectedState
,D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
,D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=131213
,I/ActivityManager(  968): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6274 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  968): handleMessage: X
,D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  266): RouteController
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 6274): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6274): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6274): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,I/PCSuite ( 6274): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
W/NetworkManagementService(  968): route cmd failed: 
W/NetworkManagementService(  968): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  968): '
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  968): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  968): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  968): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  968): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  968): android_net_utils_resetConnections in env=0x62821170 clazz=0xb2d00001 iface=wlan0 mask=0x3
D/PCSuite ( 6274): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6274): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QcConnectivityService(  968): resetConnections(wlan0, 3)
,I/ActivityManager(  968): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6316 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,V/NativeCrypto( 1531): Read error: ssl=0x63fb6e58: I/O error during system call, Connection timed out
I/ActivityManager(  968): Killing 5534:com.lge.drmservice/u0a66 (adj 15): empty #17
,V/NativeCrypto( 1531): SSL shutdown failed: ssl=0x63fb6e58: I/O error during system call, Broken pipe
,D/DhcpStateMachine(  968): StoppedState
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6316): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6316): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6316): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=false
D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
,D/GpsLocationProvider(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QRemote ( 6316): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QRemote ( 6316): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 6316): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6316): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6316): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6316): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6316): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6316): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6316): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  968): Killing 5547:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2020): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2020): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2020): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 2020): nl80211: Survey data missing
D/wpa_supplicant( 2020): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2020): wlan0: BSS: Add new id 7 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: BSS: Add new id 8 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: BSS: Add new id 9 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 2020): wlan0: New scan results available
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2020): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2020): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2020): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2020): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2020): WPS: AP[2] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2020): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2020): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-55 wps
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2020): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2020): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-74
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: 3: 00:37:b7:9d:3e:73 ssid='FunBox2-3E72' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-90 wps
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2020): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2020): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2020): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-55 wps
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2020): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2020): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_po,licy policy: 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2020): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb80e45a8  current_ssid=0x0
D/wpa_supplicant( 2020): scard is not null..
D/wpa_supplicant( 2020): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2020): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2020): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2020): wlan0: Cancelling scan request
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
,D/wpa_supplicant( 2020): wlan0: WPA: clearing own WPA/RSN IE,
D/wpa_supplicant( 2020): wlan0: Automatic auth_alg selection: 0x1,
D/wpa_supplicant( 2020): RSN: PMKSA cache search - network_ctx=0xb80e45a8 try_opportunistic=0
D/wpa_supplicant( 2020): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): RSN: No PMKSA cache entry found
,D/wpa_supplicant( 2020): wlan0: RSN: using IEEE 802.11i/D9.0,
D/wpa_supplicant( 2020): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2020): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2020): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2020): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2020): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2020): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0,
D/wpa_supplicant( 2020): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2020): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2020): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2020): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2020): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2020): nl80211: Unsubscribe mgmt frames handle 0xb80e3590 (mode change)
D/wpa_supplicant( 2020): nl80211: Subscribe to mgmt frames with non-AP handle 0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
,D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0a
,D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590,
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0d,
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590,
,D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 0a 07
,D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 0a 11
,D/wpa_supplicant( 2020): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2020):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020):   * freq=2412
D/wpa_supplicant( 2020):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2020):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
,D/wpa_supplicant( 2020):   * Auth Type 0
D/wpa_supplicant( 2020):   * WPA Versions 0x2
D/wpa_supplicant( 2020): nl80211: Connect request send successfully
D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - EAP fail=0,
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - portControl=Auto,
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 c0:ff:d4:d3:aa:4a],
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 38:f8:89:11:e9:11]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 00:37:b7:9d:3e:73],
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/WifiStateMachine(  968): handleMessage: E msg.what=147461
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState,
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt,
D/WifiStateMachine(  968): processMsg: SupplicantStartedState,
D/WifiNative-wlan0(  968): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2020): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987',
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2020): nl80211: Connect event
D/wpa_supplicant( 2020): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2020): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2020): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2020): wlan0: Association info event
D/wpa_supplicant( 2020): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2020): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2020): wlan0: freq=2412 MHz
D/wpa_supplicant( 2020): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2020): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2020): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2020): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): scard is not null..
D/wpa_supplicant( 2020): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2020): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2020): TDLS: Remove peers on association
D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2020): EAPOL: enable timer tick
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): wlan0: Cancelling scan request
,D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event,
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
,D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,W/WifiMonitor(  968): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2020): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 0a 8e fd a7 56 94 40 76 bf d1 8c c3 a1 fd f0 ...
D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2020): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2020): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2020): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2020):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2020):   key_nonce - hexdump(len=32): 0a 8e fd a7 56 94 40 76 bf d1 8c c3 a1 fd f0 26 e7 12 4f 90 ed 58 54 6f b9 c7 7e 33 1c ca 49 26
D/wpa_supplicant( 2020):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 0a 8e fd a7 56 94 40 76 bf d1 8c c3 a1 fd f0 ...
D/wpa_supplicant( 2020): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2020): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2020): Get randomness: len=32 entropy=5
D/wpa_supplicant( 2020): WPA: Renewed SNonce - hexdump(len=32): b3 61 c4 fa 32 fb 01 c4 61 53 4f 42 30 7b a4 93 c1 7f 0d 88 bf b7 bf 34 a6 14 02 61 a5 4c 50 95
D/wpa_supplicant( 2020): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): WPA: Nonce1 - hexdump(len=32): b3 61 c4 fa 32 fb 01 c4 61 53 4f 42 30 7b a4 93 c1 7f 0d 88 bf b7 bf 34 a6 14 02 61 a5 4c 50 95
D/wpa_supplicant( 2020): WPA: Nonce2 - hexdump(len=32): 0a 8e fd a7 56 94 40 76 bf d1 8c c3 a1 fd f0 26 e7 12 4f 90 ed 58 54 6f b9 c7 7e 33 1c ca 49 26
D/wpa_supplicant( 2020): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2020): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2020): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2020): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2020): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2020): WPA: Derived Key MIC - hexdump(len=16): 18 02 26 ab 56 c6 9d e2 5d 62 3c 11 3e d5 35 7c
,D/wpa_supplicant( 2020): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 b3 61 c4 fa 32 fb 01 c4 61 53 4f 42 30 7b a4 ...
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
,D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
D/wpa_supplicant( 2020): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 0a 8e fd a7 56 94 40 76 bf d1 8c c3 a1 fd f0 ...
D/wpa_supplicant( 2020): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2020): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2020): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2020): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2020):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2020):   key_nonce - hexdump(len=32): 0a 8e fd a7 56 94 40 76 bf d1 8c c3 a1 fd f0 26 e7 12 4f 90 ed 58 54 6f b9 c7 7e 33 1c ca 49 26
D/wpa_supplicant( 2020):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_rsc - hexdump(len=8): 6c 5a 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_mic - hexdump(len=16): 66 4a 1b fc 23 6e e1 49 c5 a0 f9 ff 26 3f f7 c9
D/wpa_supplicant( 2020): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 0a 8e fd a7 56 94 40 76 bf d1 8c c3 a1 fd f0 ...
D/wpa_supplicant( 2020): RSN: encrypted key data - hexdump(len=56): 8f f5 10 83 2f 10 2a 83 2a 63 26 2b bd c0 14 bc 42 8e bc c1 61 6e 79 d3 fe af 72 fc 1f dc 7a bd ...
D/wpa_supplicant( 2020): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2020): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2020): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2020): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 fc e6 ...
D/wpa_supplicant( 2020): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2020): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2020): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2020): WPA: Derived Key MIC - hexdump(len=16): fa 16 90 64 2a 4f 8a 94 34 28 7b 36 ba c0 f1 c0
,D/wpa_supplicant( 2020): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2020): wlan0: WPA: Installing PTK to the driver
,D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb80e3c54 key_idx=0 set_tx=1 seq_len=6 key_len=16,
D/wpa_supplicant( 2020):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2020): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2020): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2020): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
,D/wpa_supplicant( 2020): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2020): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
,D/wpa_supplicant( 2020): WPA: RSC - hexdump(len=6): 6c 5a 00 00 00 00
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f2d03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2020):    broadcast key,
,I/wpa_supplicant( 2020): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2020): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2020): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): wpa_supplicant_set_state, isWPS : 0
,D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2020): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state IDLE,
D/wpa_supplicant( 2020): EAPOL authentication completed successfully
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP]),
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700],
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :false
D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): Network connection established
,D/WifiNative-wlan0(  968): doString: STATUS
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
,D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AppUp4:CustFacade( 3975): isOpenOperator : true
D/AppUp4:CustFacade( 3975): isPhone : true
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2020): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/LicenseContentProvider( 2986): start selecting data
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/SIMObserver( 2986): simInfo1
D/WifiNative-wlan0(  968):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  968): ssid=NG700
D/WifiNative-wlan0(  968): id=0
D/WifiNative-wlan0(  968): mode=station
D/WifiNative-wlan0(  968): pairwise_cipher=CCMP
D/WifiNative-wlan0(  968): group_cipher=CCMP
D/WifiNative-wlan0(  968): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  968): wpa_state=COMPLETED
D/WifiNative-wlan0(  968): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  968): address=34:fc:ef:de:0a:e2
I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3975): begin check event
I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity
I/WifiServiceExtension(  968): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  968): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
D/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
D/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  968): handleMessage: X
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/DhcpStateMachine(  968): Stoppe,dState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  968): WaitBeforeStartState
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-24ms what=147462 obj=android.net.wifi.StateChangeResult@4478d9d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-15ms what=147462 obj=android.net.wifi.StateChangeResult@446a6268 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-13ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196612
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/ActivityManager(  968): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6369 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
D/HyLog   ( 6369): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6369): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6369): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd  len = 0, 0
I/LGEmail ( 6369): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: SET ps 0
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  968):    returned null
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  968):    returned null
E/WifiStateMachine(  968): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  968): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  968): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  266): Setting iface cfg
,D/CommandListener(  266): Trying to bring up wlan0
,D/WifiStateMachine(  968): addressUpdated: 192.168.1.160/24 on wlan0 flags 128 scope 0
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43040798 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43040798 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  968): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.160/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196613
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: SET ps 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
,D/WifiStateMachine(  968): DHCP successful
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  968): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  968): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  968): VerifyingLinkState enter
D/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  968): handleMessage: X
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  968): send additional Connectivity Action
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  968): handleMessage: E msg.what=135190
D/WifiStateMachine(  968): processMsg: VerifyingLinkState
D/WifiStateMachine(  968): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  968): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
W/WifiStateTracker(  968): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  968): 
W/WifiStateTracker(  968):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  968):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  968): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): CaptivePortalCheckState enter
D/WifiStateMachine(  968): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/WifiStateMachine(  968): handleMessage: X
D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  968): handleMessage: E msg.what=131092
D/WifiStateMachine(  968): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  968): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
,D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiStateMachine(  968): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/QcConnectivityService(  968): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  968): transitionTo: destState=ConnectedState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  968): invokeEnterMethods: ConnectedState
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/WifiStateMachine(  968): handleMessage: X
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
E/ActivityThread(  968): Failed to find provider info for com.lge.ims.provisioning
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/LGEmail ( 6369): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  968): handleConnectivityChange: preConnState=2 connState=1
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,W/BaseRuntimeLoader( 6369): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6369): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6369): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6369): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/        (  266): RouteController
,D/EAS     ( 6369): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6369): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/eas_req ( 6369): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/QCNEA   (  395): |CAC| readCallback: read len:492, ret:0, errno:0
,D/QCNEA   (  395): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  395): |CAC| updateNetCfgInfo
,V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC|                   Netconfig               
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  395): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  395): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  395): |CAC| 	NetConfig: ip4        =192.168.1.160
V/QCNEA   (  395): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  395): |CAC| 	NetConfig: mtu        =1500
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
V/QCNEA   (  395): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  395): |CAC| net type = 1
V/QCNEA   (  395): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  395): |CAC| Received ssid= NG700
V/QCNEA   (  395): |CAC| 	ssid           =NG700
V/QCNEA   (  395): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  395): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  395): |CAC| dispatchNetCfg: updating:0xb782f8dc
D/QCNEA   (  395): |CAC| readCallback: read len:0, ret:-1, errno:11
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4329): networkInfo.isConnected() = false
,W/linker  ( 6369): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 6369): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 6369): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 6369): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 6369): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,D/HtmlEditor( 6369): register_HtmlEditor, Success
D/HtmlEditor( 6369): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 6369): register_HtmlEditorTimer, Success
,D/HtmlEditor( 6369): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 6369): register_HtmlEditorDownloader, Success
D/HtmlEditor( 6369): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 6369): register_HtmlEditorFont, Success
D/HtmlEditor( 6369): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6369): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 6369): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6369): register_HtmlEditorDrawImage, Success
,D/HtmlEditor( 6369): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6369): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 6369): JNI_OnLoad Success
,I/HubEmail( 6369): JNI_OnLoad()
I/HubEmail( 6369): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6369): registerNatives()
I/HubEmail( 6369): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6369): registerNativeMethods()
,I/HubEmail( 6369): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 6369): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DhcpStateMachine(  968): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  968): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6403 uid=10052 gids={50052, 3003}
,I/ActivityManager(  968): Killing 5561:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,D/HyLog   ( 6403): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6403): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6403): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6403): [loadRssi] File not exist 
,V/LGRssiData( 6403): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6403): [loadFeatureFromXml] *** start feature loading from xml
,D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/BaseRuntimeLoader( 6403): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,W/BaseRuntimeLoader( 6403): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6403): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6403): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 6403): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6403): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6403): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6424 uid=10063 gids={50063, 3003, 1028, 1015}
,E/PhoneMonitor( 6403): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 6403): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  968): Killing 5573:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/CheckinService( 1943): Checking schedule, now: 1454092865118 next: 1454092541768
,I/CheckinService( 1943): active receiver: enabled
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6424): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6424): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6424): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1943): Preparing to send checkin request
,I/EventLogService( 1943): Accumulating logs since 1454092507772
,D/dalvikvm(  968): GC_EXPLICIT freed 2642K, 44% free 30630K/53756K, paused 5ms+11ms, total 180ms
,I/CheckinRequestBuilder( 1943): Checkin reason type: 8 attempt count: 1
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  968): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6441 uid=10066 gids={50066, 4002, 3003, 1028}
E/ActivityThread( 1943): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 6441): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6441): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6441): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  968): Killing 5590:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  968): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6454 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 6454): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6454): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6454): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  270): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 3ms+4ms, total 41ms
,D/LGDMSGCM( 6454): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/dalvikvm(  270): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 27ms
,D/dalvikvm(  270): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 26ms
,I/ActivityManager(  968): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6474 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  968): Killing 4637:com.test.thalitest/u0a304 (adj 15): empty #17
,D/HyLog   ( 6474): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6474): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6474): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/NFS     ( 6474): connectivityManager.getNetworkInfo = TYPE_WIFI
,D/wpa_supplicant( 2020): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2020): EAPOL: disable timer tick
,I/Wireless_Storage( 6474): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 6474): intf.getDisplayName() = lo
I/Wireless_Storage( 6474): intf.getDisplayName() = sit0
I/Wireless_Storage( 6474): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6474): intf.getDisplayName() = teql0
,I/Wireless_Storage( 6474): intf.getDisplayName() = wlan0
D/NFS     ( 6474): interface name:wlan0 name:wlan0
D/NFS     ( 6474): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
,D/NFS     ( 6474): interface name:wlan0 name:wlan0
D/NFS     ( 6474): addr:192.168.1.160 broadcast:192.168.1.255
,I/Wireless_Storage( 6474): CONNECT : WIFI_CONNECT
,I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6487 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  968): Killing 5765:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6487): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6487): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6487): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,W/GAV2    ( 6487): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x4324efb0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1943): awaiting user notification for token
,I/ActivityManager(  968): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6505 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6505): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6505): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6505): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6505): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6505): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 6505): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6505): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6505): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 6505): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6505): install
,I/MultiDex( 6505): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6505): loading existing secondary dex files
,I/MultiDex( 6505): load found 3 secondary dex files
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  968): NetTransition Wakelock for ConnectedState released by timeout
,I/MultiDex( 6505): install done
,D/WifiStateMachine(  968): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
,D/WifiStateMachine(  968): processMsg: DefaultState
,D/dalvikvm( 6505): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6505): VFY: unable to resolve instance field 61
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/dalvikvm( 6505): VFY: replacing opcode 0x54 at 0x0054
D/WifiStateMachine(  968): handleMessage: X
D/dalvikvm( 6505): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6505): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6505): VFY: replacing opcode 0x62 at 0x0067
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  968): send additional Connectivity Action
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
D/dalvikvm( 6505): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6505): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 6505): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 6505): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6505): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6505): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42802338
D/QcConnectivityService(  968): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  968):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  968): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 6505): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42802338
,D/dalvikvm( 6505): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42802338, skipping init
,D/dalvikvm( 6505): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42802338
D/dalvikvm( 6505): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42802338
,V/JNIHelp ( 6505): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 6487): Binding Chromium to the main looper Looper (main, tid 1) {427face0}
,I/chromium( 6487): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6487): Initializing chromium process, renderers=0
,W/chromium( 6487): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6487): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6487): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6487): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6487): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6487): Remote Branch: 
I/Adreno-EGL( 6487): Local Patches: 
I/Adreno-EGL( 6487): Reconstruct Branch: 
,D/dalvikvm( 6505): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42802338
,D/dalvikvm( 6505): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42802338
D/dalvikvm( 6505): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42802338
,D/dalvikvm( 6505): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42802338
,I/NSApplication( 6487): Starting up...
,I/ActivityManager(  968): Killing 5817:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  968): Start proc com.test.thalitest for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener: pid=6538 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
,D/HyLog   ( 6538): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6538): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6538): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ProviderInstaller( 6505): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 6505): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6505): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6505): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 6505): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6505): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6505): VFY: replacing opcode 0x6e at 0x0201
,D/dalvikvm( 6538): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428027f0
,D/dalvikvm( 6538): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428027f0
,D/jxcore_app_log( 6538): JniHelper::setJavaVM(0x416c6838), pthread_self() = 1073955156
,E/JX-Cordova( 6538): JXcore wasn't initialized yet
,D/QRemote ( 6316): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6316): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6316): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6316): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6316): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6316): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6274): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6274): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6316): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6316): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6316): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6316): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
I/ActivityManager(  968): Killing 5832:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1531): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/AuthorizationBluetoothService( 1531): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1531): Proximity feature is not enabled.
D/WVCdm   (  272): Instantiating CDM.
,I/WVCdm   (  272): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  272): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  272): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  272): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f66000
,E/DrmWidevineDash(  272): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f66000
,V/GmsCoreStatsServiceLauncher( 1943): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/DrmWidevineDash(  272): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  272): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  272): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  272): OEMCrypto_IsKeyboxValid returns 0
D/WVCdm   (  272): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  272): CdmEngine::OpenSession
,D/DrmWidevineDash(  272): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  272): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
,D/WearableService( 1870): callingUid 10006, callindPid: 1870
,I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  272): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,E/MDM     ( 1424): [75] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1943): Restart initialization of location
,D/DrmWidevineDash(  272): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  272): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  272): PrepareKeyRequest: nonce=3945552452
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DhcpStateMachine(  968): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  968): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  968): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.160
V/LgDhcpStateMachineHelper(  968): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  968): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  968): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  968): RunningState
,D/dalvikvm( 6505): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/lib/libd317EF1D9D4A2.so 0x429be890
D/dalvikvm( 6505): Added shared lib /data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/lib/libd317EF1D9D4A2.so 0x429be890
,D/dalvikvm( 6505): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/lib/libd317EF1D9D4A2.so 0x429be890, skipping init
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  272): CdmEngine::CloseSession
,D/DrmWidevineDash(  272): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 1531): GC_EXPLICIT freed 1602K, 28% free 17990K/24832K, paused 2ms+5ms, total 38ms
,D/GCM     ( 1531): Connected
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1531): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 6505): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 6582): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 6505): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6505): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 93ms
,I/Adreno-EGL( 6505): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6505): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6505): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6505): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6505): Remote Branch: 
I/Adreno-EGL( 6505): Local Patches: 
I/Adreno-EGL( 6505): Reconstruct Branch: 
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/Settings( 6505): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/WVCdm   (  272): CdmEngine::OpenSession
,D/DrmWidevineDash(  272): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  272): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  272): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  272): PrepareKeyRequest: nonce=135543844
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  272): CdmEngine::CloseSession
,D/DrmWidevineDash(  272): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 6505): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6505): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6505): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6505): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6505): Remote Branch: 
I/Adreno-EGL( 6505): Local Patches: 
I/Adreno-EGL( 6505): Reconstruct Branch: 
,I/Adreno-EGL( 6505): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6505): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6505): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6505): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6505): Remote Branch: 
I/Adreno-EGL( 6505): Local Patches: 
I/Adreno-EGL( 6505): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1943): Classify the device as Phone.
,V/NativeCrypto( 1943): SSL shutdown failed: ssl=0x6b73e738: I/O error during system call, Connection timed out
,D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1943): Sending checkin request (11633 bytes)
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
,D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 2986): start selecting data
,D/SIMObserver( 2986): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3975): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 3975): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3975): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3975): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3975): handleAsyncCustNotification do not startCustService
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/EAS     ( 6369): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5882): DownloadService onCreate
,D/EAS     ( 6369): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 6369): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=-21ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4329): networkInfo.isConnected() = false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6454): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6474): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6474): CONNECT : WIFI_CONNECT
,I/DownloadManager( 5882): in removeSpuriousFiles
,W/Settings( 6369): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@4284f538 on behalf of 5882
,I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 5882): DownloadService onStartCommand
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42851a50 on behalf of 5882
I/DownloadManager( 5882): in trimDatabase
V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5882): DownloadService onDestroy
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42853268 on behalf of 5882
,D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 2986): start selecting data
,D/SIMObserver( 2986): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5882): DownloadService onCreate
,I/DownloadManager( 5882): in removeSpuriousFiles
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 6369): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6369): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42857a30 on behalf of 5882
,V/DownloadManager( 5882): DownloadService onStartCommand
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5882): in trimDatabase
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42859910 on behalf of 5882
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@4285a760 on behalf of 5882
I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4329): networkInfo.isConnected() = true
,D/PhoneState( 4329): setPdpRejectCasuse : false
,W/Settings( 6369): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5882): DownloadService onDestroy
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 6454): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 6474): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6474): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/ContextImpl( 6454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
,D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 2986): start selecting data
,D/SIMObserver( 2986): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5882): DownloadService onCreate
,D/EAS     ( 6369): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6369): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 5882): in removeSpuriousFiles
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4329): networkInfo.isConnected() = true
,D/PhoneState( 4329): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6454): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6454): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6474): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6474): CONNECT : WIFI_CONNECT
,W/Settings( 6369): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@4285ea90 on behalf of 5882
,I/DownloadManager( 5882): in trimDatabase
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@428604a0 on behalf of 5882
V/DownloadManager( 5882): DownloadService onStartCommand
V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42862650 on behalf of 5882
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 5882): DownloadService onDestroy
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/dalvikvm( 3853): GC_FOR_ALLOC freed 376K, 2% free 37783K/38444K, paused 51ms, total 52ms
,I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092869228148491; DSPS: 32146998; Offset: 1454091888179625542
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinResponseProcessor( 1943): From server: 2 gservices updates and 0 deletes
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CertBlacklister(  968): Certificate blacklist changed, updating...
,I/CertBlacklister(  968): Certificate blacklist updated
,I/GservicesProvider( 1531): main difference update completed
,I/ActivityManager(  968): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6674 uid=10003 gids={50003, 3003, 2001}
,I/CheckinRequestBuilder( 1943): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1943): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/HyLog   ( 6674): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6674): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6674): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/ContextImpl( 6674): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/UpdateFetcherService( 6674): Update started
,D/DownloadManager( 5882): DB Update : deleted 1
,E/UpdateRequestReceiver( 6674): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 6674): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 6674): Update started
,D/DownloadManager( 5882): DB Update : deleted 1
,E/UpdateRequestReceiver( 6674): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6674): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6674): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  968): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6715 uid=10009 gids={50009, 3003}
,D/HyLog   ( 6715): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  968): GC_EXPLICIT freed 1499K, 43% free 30684K/53756K, paused 7ms+8ms, total 113ms
D/HyLog   ( 6715): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6715): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 5882): DownloadService onCreate
,V/DownloadManager( 5882): initiating download with UID 10003
,V/DownloadManager( 5882): initiating download with UID 10003
,I/DownloadManager( 5882): in removeSpuriousFiles
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): DownloadService onStartCommand
V/DownloadManager( 5882): DownloadService onStartCommand
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): DownloadService onStartCommand
,W/BaseRuntimeLoader( 6715): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42872278 on behalf of 5882
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42873340 on behalf of 5882
,W/BaseRuntimeLoader( 6715): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6715): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6715): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/DownloadManager( 5882): DownloadService onStartCommand
,I/DownloadManager( 5882): in trimDatabase
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42875918 on behalf of 5882
,V/DownloadManager( 5882): processing inserted download 281
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=281:190
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42878b00 on behalf of 5882
,D/DownloadManager( 5882): DB Update : status 192
,I/ContactAccountLoggerTas( 2672): canRun() : Opted Out
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Search.GservicesUpdateTask( 2672): Updating Gservices keys
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@4287be88 on behalf of 5882
V/DownloadManager( 5882): processing inserted download 282
V/LFT     ( 5882): isReadyToDownload mId, mStatus=282:190
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@4287da08 on behalf of 5882
,W/GAV2    ( 2672): Thread[Thread-206,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/DownloadManager( 5882): DB Update : status 192
,I/DownloadManager( 5882): Download 281 starting
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,W/GAV2    ( 2672): Thread[Thread-206,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 2672): canRun() : Opted Out
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42881118 on behalf of 5882
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42883d18 on behalf of 5882
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/DownloadManager( 5882): fileSize : -1state.mContinuingDownload :false
,I/DownloadManager( 5882): Download 282 starting
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 5882): processing updated download 281, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=281:192
V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/DownloadManager( 5882): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42887a10 on behalf of 5882
,V/DownloadManager( 5882): processing updated download 282, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=282:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42892fa0 on behalf of 5882
,E/DataScheduler( 5882): isDataSchedulerEnabled():false
,E/DataScheduler( 5882): isDataSchedulerEnabled():false
D/libc    (  266): _dns_getaddrinfo: iptype =1
D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ContactAccountLoggerTas( 2672): canRun() : Opted Out
V/WifiServiceExtension(  968): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ContactAccountLoggerTas( 2672): canRun() : Opted Out
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ContactAccountLoggerTas( 2672): canRun() : Opted Out
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/DownloadManager( 5882): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 5882): Content-Disposition: null
V/DownloadManager( 5882): Content-Length: -1
V/DownloadManager( 5882): Content-Location: null
V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 5882): Content-Type: text/plain
V/DownloadManager( 5882): ETag: null
V/DownloadManager( 5882): Transfer-Encoding: chunked
,V/DownloadManager( 5882): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 5882): Min update size = 16384
V/DownloadManager( 5882): getting filename from uri
I/DownloadManager( 5882): in verifySpace, destination: 5, path: 10152015-sms-metadata.txt, length: 0
V/DownloadManager( 5882): keeping extension
,V/DownloadManager( 5882): target file: /cache/10152015-sms-metadata.txt
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@428b0518 on behalf of 5882
,I/SystemUpdateService( 1943): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1943): onCreate
D/DownloadManager( 5882): DB Update : title 10152015-sms-metadata.txt
D/DownloadManager( 5882): DB Update : mimetype text/plain
,D/DownloadManager( 5882): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 5882): DB Update : total_bytes -1
,D/SystemUpdateService( 1943): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@428c45f8 on behalf of 5882
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/LGDrmService( 5882): _DRM_ServiceGet() : Bind lgdrm service
,V/DownloadManager( 5882): processing updated download 281, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=281:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@428c99e8 on behalf of 5882
,D/SystemEventReceiver( 1943): Received GSERVICES_CHANGED broadcast
,V/DownloadManager( 5882): processing updated download 282, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=282:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@428cfa08 on behalf of 5882
,D/DownloadManager( 5882): transferData threadNum : -1
D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x42a4dde0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x433b2018: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/GCM     ( 1531): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/OcrUtils( 1943): Updating ocr activity enabled=false
,D/DownloadManager( 5882): transferData threadNum : -1
,D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
D/DownloadManager( 5882): DB Update : current_bytes 383
D/DownloadManager( 5882): DB Update : total_bytes 383
I/SystemUpdateService( 1943): cancelUpdate (empty URL)
I/SystemUpdateService( 1943): active receiver: disabled
I/GCoreUlr( 1424): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,D/SystemUpdateService( 1943): onDestroy
,W/CheckinRequestBuilder( 1943): awaiting user notification for token
,W/Search.LoginHelper( 2672): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 2672): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/CheckinRequestBuilder( 1943): Classify the device as Phone.
,I/ContactAccountLoggerTas( 2672): canRun() : Opted Out
,D/dalvikvm( 1531): GC_EXPLICIT freed 811K, 27% free 18351K/24832K, paused 3ms+3ms, total 28ms
,I/GCoreUlr( 1424): DispatchingService.onCreate()
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 5882): notifyThroughDatabase after updateDB  id :  282, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 5882): notifyThroughDatabase start id : 282 name : /cache/10152015-sms-metadata.txt status : 200
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42917580 on behalf of 5882
V/DownloadManager( 5882): processing updated download 281, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=281:192
V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/CheckinTask( 1943): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429203b0 on behalf of 5882
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42920038 on behalf of 5882
,D/DownloadManager( 5882): DB Update : numfailed 0
D/DownloadManager( 5882): DB Update : method 0
D/DownloadManager( 5882): DB Update : lastmod 1454092870193
D/DownloadManager( 5882): DB Update : mimetype text/plain
,D/DownloadManager( 5882): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 5882): DB Update : status 200
,V/DownloadManager( 5882): processing updated download 282, status: 192
V/LFT     ( 5882): isReadyToDownload mId, mStatus=282:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 1943): Checking schedule, now: 1454092870216 next: 1454670266200
,I/CheckinService( 1943): active receiver: disabled
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429279a0 on behalf of 5882
,D/DownloadManager( 5882): checkStatusUpdate current status 192 is changed to 200
,D/DownloadManager( 5882): checkStatusUpdate return true mID : mStatus = 282 : 200 => 200
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@4292a808 on behalf of 5882
,V/DownloadManager( 5882): processing updated download 281, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=281:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5882): Download 282 finished with status SUCCESS
,I/GCoreUlr( 1424): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@4292c478 on behalf of 5882
,W/ActivityThread( 5882): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/dalvikvm( 1943): GC_CONCURRENT freed 1925K, 21% free 19680K/24832K, paused 8ms+6ms, total 75ms
,D/dalvikvm( 1943): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/GCoreUlr( 1424): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/dalvikvm( 1943): GC_EXPLICIT freed 181K, 22% free 19499K/24832K, paused 4ms+3ms, total 43ms
,I/DownloadManager( 5882): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 5882): Content-Disposition: null
,V/DownloadManager( 5882): Content-Length: -1
V/DownloadManager( 5882): Content-Location: null
V/DownloadManager( 5882): Content-Type: text/plain
V/DownloadManager( 5882): ETag: null
V/DownloadManager( 5882): Transfer-Encoding: chunked
V/DownloadManager( 5882): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 5882): Min update size = 16384
V/DownloadManager( 5882): getting filename from uri
I/DownloadManager( 5882): in verifySpace, destination: 5, path: 08202014-metadata.txt, length: 0
V/DownloadManager( 5882): keeping extension
,V/DownloadManager( 5882): target file: /cache/08202014-metadata.txt
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,D/dalvikvm( 1531): GC_EXPLICIT freed 458K, 28% free 17989K/24832K, paused 1ms+3ms, total 21ms
,I/CheckinService( 1943): Checking schedule, now: 1454092870481 next: 1454670266200
,I/CheckinService( 1943): active receiver: disabled
,D/dalvikvm(  968): GC_EXPLICIT freed 1883K, 44% free 30632K/53756K, paused 5ms+11ms, total 153ms
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@4297ede8 on behalf of 5882
,D/DownloadManager( 5882): DB Update : title 08202014-metadata.txt
,D/DownloadManager( 5882): DB Update : mimetype text/plain
D/DownloadManager( 5882): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 5882): DB Update : total_bytes -1
,I/GCoreUlr( 1424): Unbound from all location providers
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42981d38 on behalf of 5882
,D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): DB Update : current_bytes 384
,D/DownloadManager( 5882): DB Update : total_bytes 384
,V/DownloadManager( 5882): processing updated download 281, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=281:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@4298df60 on behalf of 5882
,V/LFT     ( 5882): notifyThroughDatabase after updateDB  id :  281, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 5882): notifyThroughDatabase start id : 281 name : /cache/08202014-metadata.txt status : 200
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42990168 on behalf of 5882
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42992230 on behalf of 5882
,D/DownloadManager( 5882): DB Update : numfailed 0
D/DownloadManager( 5882): DB Update : method 0
D/DownloadManager( 5882): DB Update : lastmod 1454092870519
,D/DownloadManager( 5882): DB Update : mimetype text/plain
D/DownloadManager( 5882): DB Update : _data /cache/08202014-metadata.txt
D/DownloadManager( 5882): DB Update : status 200
V/DownloadManager( 5882): processing updated download 281, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=281:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42994980 on behalf of 5882
,D/DownloadManager( 5882): checkStatusUpdate current status 192 is changed to 200
,D/DownloadManager( 5882): checkStatusUpdate return true mID : mStatus = 281 : 200 => 200
,I/GCoreUlr( 1424): DispatchingService.onDestroy()
,I/DownloadManager( 5882): Download 281 finished with status SUCCESS
,V/DownloadManager( 5882): DownloadService onDestroy
I/ActivityManager(  968): Killing 5848:com.android.vending/u0a50 (adj 15): empty #17
,I/GCoreUlr( 1424): Unbound from all location providers
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 282; sort is lastmod DESC.
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42999940 on behalf of 6674
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 282; sort is lastmod DESC.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@4299d040 on behalf of 6674
,W/ContextImpl( 6674): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,V/DownloadManager( 5882): initiating download with UID 10003
,V/DownloadManager( 5882): DownloadService onCreate
,I/DownloadManager( 5882): in removeSpuriousFiles
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429a28a8 on behalf of 5882
,I/DownloadManager( 5882): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
,I/DownloadManager( 5882): in removeSpuriousFiles, preserving file /cache/10152015-sms-metadata.txt
I/DownloadManager( 5882): in trimDatabase
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429a40d0 on behalf of 5882
,V/DownloadManager( 5882): DownloadService onStartCommand
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429a6208 on behalf of 5882
,V/DownloadManager( 5882): processing inserted download 281
,V/DownloadManager( 5882): processing inserted download 282
,V/DownloadManager( 5882): processing inserted download 283
V/LFT     ( 5882): isReadyToDownload mId, mStatus=283:190
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429aad70 on behalf of 5882
,D/DownloadManager( 5882): DB Update : status 192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429acff0 on behalf of 5882
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5882): Download 283 starting
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429af418 on behalf of 5882
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/DownloadManager( 5882): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 5882): processing updated download 283, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=283:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429b53b8 on behalf of 5882
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 281; sort is lastmod DESC.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429b9460 on behalf of 6674
,D/GCM     ( 1531): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 281; sort is lastmod DESC.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429bcb60 on behalf of 6674
,W/ContextImpl( 6674): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,V/DownloadManager( 5882): initiating download with UID 10003
,I/DownloadManager( 5882): Ignoring Content-Length since Transfer-Encoding is also defined
,V/DownloadManager( 5882): Content-Disposition: null
V/DownloadManager( 5882): Content-Length: -1
V/DownloadManager( 5882): Content-Location: null
V/DownloadManager( 5882): Content-Type: text/plain
V/DownloadManager( 5882): ETag: null
,V/DownloadManager( 5882): Transfer-Encoding: chunked
V/DownloadManager( 5882): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 5882): Min update size = 16384
V/DownloadManager( 5882): getting filename from uri
I/DownloadManager( 5882): in verifySpace, destination: 5, path: 10152015-sms-blacklist.txt, length: 0
V/DownloadManager( 5882): keeping extension
,V/DownloadManager( 5882): target file: /cache/10152015-sms-blacklist.txt
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429c8df8 on behalf of 5882
,V/DownloadManager( 5882): DownloadService onStartCommand
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5882): DB Update : title 10152015-sms-blacklist.txt
D/DownloadManager( 5882): DB Update : mimetype text/plain
D/DownloadManager( 5882): DB Update : _data /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 5882): DB Update : total_bytes -1
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429cb3e0 on behalf of 5882
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/LGDRM   (  276): [DRM] Part_DetectType() : Buffer contains XML Prologue
V/DownloadManager( 5882): processing updated download 283, status: 192
V/LFT     ( 5882): isReadyToDownload mId, mStatus=283:192
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5882): transferData threadNum : -1
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429cf2f8 on behalf of 5882
V/DownloadManager( 5882): processing inserted download 284
V/LFT     ( 5882): isReadyToDownload mId, mStatus=284:190
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429d99d0 on behalf of 5882
,D/DownloadManager( 5882): DB Update : current_bytes 13383
,I/GAV2    ( 6487): Thread[GAThread,5,main]: No campaign data found.
,D/DownloadManager( 5882): DB Update : total_bytes 13383
,D/DownloadManager( 5882): DB Update : status 192
,V/LFT     ( 5882): notifyThroughDatabase after updateDB  id :  283, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 5882): notifyThroughDatabase start id : 283 name : /cache/10152015-sms-blacklist.txt status : 200
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429ddec0 on behalf of 5882
,D/DownloadManager( 5882): DB Update : numfailed 0
D/DownloadManager( 5882): DB Update : method 0
D/DownloadManager( 5882): DB Update : lastmod 1454092870759
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5882): DB Update : mimetype text/plain
D/DownloadManager( 5882): DB Update : _data /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 5882): DB Update : status 200
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429dfbc0 on behalf of 5882
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429e1f18 on behalf of 5882
,I/DownloadManager( 5882): Download 284 starting
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/DownloadManager( 5882): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 5882): processing updated download 284, status: 192
,I/DownloadManager( 5882): Download 283 finished with status SUCCESS
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=284:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429e8e48 on behalf of 5882
V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 283; sort is lastmod DESC.
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429ed768 on behalf of 6674
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429ee800 on behalf of 5882
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 283; sort is lastmod DESC.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429f3120 on behalf of 6674
,W/ContextImpl( 6674): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
V/DownloadManager( 5882): processing updated download 284, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=284:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@429fe928 on behalf of 5882
,I/UpdateFetcherService( 6674): Update downloaded, starting installation
,I/UpdateFetcherService( 6674): Started installation
,D/DownloadManager( 5882): DB Update : deleted 1
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): DownloadService onStartCommand
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a12828 on behalf of 5882
,D/DownloadManager( 5882): deleteFileIfExists() deleting /cache/10152015-sms-metadata.txt
,D/DownloadManager( 5882): deleteFileIfExists() deleting /cache/10152015-sms-blacklist.txt
,V/DownloadManager( 5882): processing updated download 284, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=284:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a54770 on behalf of 5882
,I/DownloadManager( 5882): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 5882): Content-Disposition: null
V/DownloadManager( 5882): Content-Length: -1
,V/DownloadManager( 5882): Content-Location: null
V/DownloadManager( 5882): Content-Type: text/plain
,V/DownloadManager( 5882): ETag: null
V/DownloadManager( 5882): Transfer-Encoding: chunked
V/DownloadManager( 5882): X-Oma-Drm-Separate-Delivery: null
,V/DownloadManager( 5882): Min update size = 16384
V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5882): getting filename from uri
I/DownloadManager( 5882): in verifySpace, destination: 5, path: 08202014-pins.txt, length: 0
V/DownloadManager( 5882): keeping extension
,V/DownloadManager( 5882): target file: /cache/08202014-pins.txt
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a59728 on behalf of 5882
,V/DownloadManager( 5882): processing updated download 284, status: 192
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a59bf8 on behalf of 5882
V/LFT     ( 5882): isReadyToDownload mId, mStatus=284:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5882): DB Update : title 08202014-pins.txt
D/DownloadManager( 5882): DB Update : mimetype text/plain
D/DownloadManager( 5882): DB Update : _data /cache/08202014-pins.txt
D/DownloadManager( 5882): DB Update : total_bytes -1
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a5c098 on behalf of 5882
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5882): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a5eef0 on behalf of 5882
,V/DownloadManager( 5882): processing updated download 284, status: 192
V/LFT     ( 5882): isReadyToDownload mId, mStatus=284:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5882): transferData threadNum : -1
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a62240 on behalf of 5882
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): DB Update : current_bytes 32768
,V/DownloadManager( 5882): downloaded 32768 for https://www.gstatic.com/android/config_update/08202014-pins.txt
D/DownloadManager( 5882): transferData threadNum : -1
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): transferData threadNum : -1
D/DownloadManager( 5882): transferData threadNum : -1
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a6f608 on behalf of 5882
,D/DownloadManager( 5882): transferData threadNum : -1
,D/DownloadManager( 5882): DB Update : current_bytes 39938
,D/DownloadManager( 5882): DB Update : total_bytes 39938
V/DownloadManager( 5882): processing updated download 284, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=284:192
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a73120 on behalf of 5882
,V/LFT     ( 5882): notifyThroughDatabase after updateDB  id :  284, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 5882): notifyThroughDatabase start id : 284 name : /cache/08202014-pins.txt status : 200
V/DownloadManager( 5882): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a759f8 on behalf of 5882
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a76ce8 on behalf of 5882
,D/DownloadManager( 5882): DB Update : numfailed 0
D/DownloadManager( 5882): DB Update : method 0
D/DownloadManager( 5882): DB Update : lastmod 1454092870894
D/DownloadManager( 5882): DB Update : mimetype text/plain
D/DownloadManager( 5882): DB Update : _data /cache/08202014-pins.txt
V/DownloadManager( 5882): processing updated download 284, status: 192
,V/LFT     ( 5882): isReadyToDownload mId, mStatus=284:192
V/DownloadManager( 5882): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 5882): DB Update : status 200
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a79c00 on behalf of 5882
D/DownloadManager( 5882): checkStatusUpdate current status 192 is changed to 200
,D/DownloadManager( 5882): checkStatusUpdate return true mID : mStatus = 284 : 200 => 200
,I/DownloadManager( 5882): Download 284 finished with status SUCCESS
,V/DownloadManager( 5882): DownloadService onDestroy
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 284; sort is lastmod DESC.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a7e8b0 on behalf of 6674
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 284; sort is lastmod DESC.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a81f70 on behalf of 6674
,W/ContextImpl( 6674): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/UpdateFetcherService( 6674): Update downloaded, starting installation
,I/UpdateFetcherService( 6674): Started installation
,D/DownloadManager( 5882): DB Update : deleted 1
,V/DownloadManager( 5882): DownloadService onCreate
,I/DownloadManager( 5882): in removeSpuriousFiles
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a86008 on behalf of 5882
,V/DownloadManager( 5882): DownloadService onStartCommand
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5882): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
I/DownloadManager( 5882): in removeSpuriousFiles, preserving file /cache/08202014-pins.txt
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a884c0 on behalf of 5882
I/DownloadManager( 5882): in trimDatabase
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a899b8 on behalf of 5882
,V/DownloadManager( 5882): processing inserted download 281
,D/DownloadManager( 5882): deleteFileIfExists() deleting /cache/08202014-metadata.txt
,V/DownloadManager( 5882): processing inserted download 284
,D/DownloadManager( 5882): deleteFileIfExists() deleting /cache/08202014-pins.txt
I/ConfigUpdateInstallReceiver(  968): Not installing, new version is <= current version
,V/DownloadManager( 5882): DownloadService onDestroy
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  968): Killing 6274:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  968): Killing 2986:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager(  968): Killing 6316:com.lge.qremote/u0a96 (adj 15): empty #18
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityThread( 3975): Removing dead content provider:android.content.ContentProviderProxy@4281c7c0
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/GAV2    ( 2672): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3853): Thread[GAThread,5,main]: No campaign data found.
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3998): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3998): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
D/administrator(  968): Handling package changes for user 0
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/InputReader(  968): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6828 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,W/ActivityManager(  968): getAssistContextExtras failed: no resumed activity
,W/ActivityManager(  968): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "sms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1144): changeTargets() succeeded. size: 20
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 6828): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6828): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6828): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "sms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 6828): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6828): MmsConfig.loadMmsSettings
,I/Babel   ( 6828): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6828): MmsConfig.loadFromDatabase
,I/MediaCodecList( 6828): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 6828): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 6828): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6828): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 6828): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6828): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6828): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6828): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 6828): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6828): MmsConfig.loadFromResources
,E/Babel   ( 6828): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6828): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1424): DISABLE
,W/Settings( 6828): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/LGRssiData( 6828): [loadRssi] File not exist 
V/LGRssiData( 6828): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6828): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:Utils( 3975): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3975): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 3975): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,V/TelephonyAutoProfiling( 6828): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6828): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6828): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/ActivityManager(  968): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=6877 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/LocationProviderProxy(  968): applying state to connected service
,D/LocationProviderProxy(  968): applying state to connected service
,D/dalvikvm(  968): GC_EXPLICIT freed 1508K, 43% free 30739K/53756K, paused 5ms+13ms, total 153ms
,D/HyLog   ( 6877): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6877): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6877): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/LicenseContentProvider( 6877): start selecting data
,W/BaseRuntimeLoader( 6877): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6877): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6877): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6877): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/SIMObserver( 6877): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3975): begin check event
D/AppUp4:Utils( 3975): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3975): Event For Nothing, skip.
,I/ActivityManager(  968): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6889 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  968): Killing 6369:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6889): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6889): BUILD Country: EU
,I/SystemConfig( 6889): BUILD Operator: OPEN
I/ActivityManager(  968): Killing 6424:com.android.chrome/u0a63 (adj 15): empty #17
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  968): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6906 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
I/SystemConfig( 6889): systemFeature RCS result false
D/SystemConfig( 6889): refreshRcsSupport() :false
,D/HyLog   ( 6906): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6906): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6906): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  968): Killing 6441:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/IcingCorporaProvider( 2672): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  968): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6922 uid=10050 gids={50050, 3003, 1028, 1015}
,D/dalvikvm(  270): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+1ms, total 16ms
,D/dalvikvm(  270): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
,D/dalvikvm(  270): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 13ms
,D/HyLog   ( 6922): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6922): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6922): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 6922): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6922): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6922): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6922): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6922): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 6922): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6922): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6922): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6922): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6922): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6922): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6922): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6922): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6922): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6922): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6922): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6922): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 6922): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6922): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6922): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6922): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6922): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6922): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a93820 on behalf of 6922
,I/IcingCorporaProvider( 2672): UpdateCorporaTask done [took 288 ms] updated apps [took 288 ms] 
,I/dalvikvm( 6922): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 6922): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6922): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 6922): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 6922): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6922): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6922): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6922): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6922): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6922): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/PackageBroadcastService( 1943): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  968): Killing 6454:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/Icing   ( 1943): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6922): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6922): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6922): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6922): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6922): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6922): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6922): Total arena pages for JIT: 11
,I/dalvikvm( 6922): Total arena pages for JIT: 12
,I/dalvikvm( 6922): Total arena pages for JIT: 13
,I/dalvikvm( 6922): Total arena pages for JIT: 14
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-5ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  968): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  968): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  968): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  968): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  968): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6922): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6922): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6922): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6922): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,D/dalvikvm( 1531): GC_EXPLICIT freed 713K, 28% free 17995K/24832K, paused 4ms+6ms, total 63ms
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/PackageSettings(  968): Skipping PackageSetting{42cf84a0 com.example.hello/10312} due to missing metadata
,I/GAV4    ( 6828): Thread[GAThread,5,main]: No campaign data found.
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092889230317659; DSPS: 32802429; Offset: 1454091888179627962
,D/Finsky  ( 6922): [522] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6922): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092909231696134; DSPS: 33457834; Offset: 1454091888179633146
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092920054, nextTick: 59974, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092920057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092929233087554; DSPS: 34113240; Offset: 1454091888179620758
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092949233529742; DSPS: 34768614; Offset: 1454091888179635700
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092969234388846; DSPS: 35424002; Offset: 1454091888179640311
,D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2020): nl80211: Disconnect event
D/wpa_supplicant( 2020): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2020): wlan0: Deauthentication notification
D/wpa_supplicant( 2020): wlan0:  * reason 0
D/wpa_supplicant( 2020): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2020): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2020): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2020): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2020): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2020): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2020): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  968): handleMessage: E msg.what=147460,
D/WifiStateMachine(  968): processMsg: ConnectedState,
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState,
D/WifiStateMachine(  968): Network connection lost,
D/WifiStateMachine(  968): Stopping DHCP and clearing IP
,D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  968): doBoolean: SET ps 1,
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb80e2d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2020): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=0,
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state INITIALIZE,
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
D/CommandListener(  266): Clearing all IP addresses on wlan0
D/WifiStateMachine(  968): addressRemoved: 192.168.1.160/24 on wlan0 flags 128 scope 0
D/DhcpStateMachine(  968): RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  968): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 2020): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2020): wlan0: nl80211: scan request
,D/wpa_supplicant( 2020): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2020): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2020): wlan0: nl80211: Scan trigger
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
D/QCNEA   (  395): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  395): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  395): |CAC| updateNetCfgInfo
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC|                   Netconfig               
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  395): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  395): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  395): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  395): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  395): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  395): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| Received bssid= 
D/QCNEA   (  395): |CAC| net type = 3
V/QCNEA   (  395): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  395): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  395): |CAC| 	ssid           =NG700
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  395): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  395): |CAC| dispatchNetCfg: updating:0xb782f8dc
,D/QCNEA   (  395): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/WifiHS20(  968): hidePasspointNotification off =false
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/QcConnectivityService(  968): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  968): Attempting to switch to mobile
,D/QcConnectivityService(  968): Attempting to switch to BLUETOOTH_TETHER
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
D/QcConnectivityService(  968): handleConnectivityChange: preConnState=1 connState=2
,D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  968): invokeExitMethods: ConnectedState
D/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  968): handleMessage: X
,I/ActivityManager(  968): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7090 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092980060, nextTick: 59970, mDrawingTime: 2
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '95 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 95 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/Clock   ( 1144): Clock updated, drawingStartTime : 1454092980077, nextTick: 59955, mDrawingTime: 0
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=131213
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
,D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131213
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
,D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
,D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '96 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 96 Failed to remove route from default table (No such process)'
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '97 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 97 Failed to remove route from default table (No such process)'
V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,D/HyLog   ( 7090): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7090): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7090): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  266): RouteController
,V/        (  266): RouteController
,I/PCSuite ( 7090): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7090): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7090): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
W/NetworkManagementService(  968): route cmd failed: 
W/NetworkManagementService(  968): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '99 route del src v6 2' failed with '400 99 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  968): '
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  968): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  968): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  968): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  968): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  968): android_net_utils_resetConnections in env=0x62821170 clazz=0xffa00001 iface=wlan0 mask=0x3
I/ActivityManager(  968): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7134 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  968): Killing 6474:com.lge.wireless_storage/u0a101 (adj 15): empty #17
D/QcConnectivityService(  968): resetConnections(wlan0, 3)
,D/DhcpStateMachine(  968): StoppedState
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,V/NativeCrypto( 1531): Read error: ssl=0x63fb62b8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1531): SSL shutdown failed: ssl=0x63fb62b8: I/O error during system call, Broken pipe
,D/HyLog   ( 7134): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7134): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7134): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 7134): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7134): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 7134): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7134): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 7134): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 7134): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 7134): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7134): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  968): Killing 6487:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/GpsLocationProvider(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2020): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2020): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2020): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 2020): nl80211: Survey data missing
D/wpa_supplicant( 2020): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 2020): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 2020): wlan0: New scan results available
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2020): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2020): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2020): WPS: AP 00:37:b7:9d:3e:73 type 0 added
,D/wpa_supplicant( 2020): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2020): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1,
,D/wpa_supplicant( 2020): WPS: AP[2] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 2020): wlan0: Selecting BSS from priority group 1
,D/wpa_supplicant( 2020): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-55 wps,
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps,
D/wpa_supplicant( 2020): wlan0:    skip - blacklisted (count=1 limit=0),
D/wpa_supplicant( 2020): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-74
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch,
,D/wpa_supplicant( 2020): wlan0: 3: 00:37:b7:9d:3e:73 ssid='FunBox2-3E72' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-88 wps
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
,D/wpa_supplicant( 2020): wlan0: No APs found - clear blacklist and try again,
D/wpa_supplicant( 2020): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2020): wlan0: Selecting BSS from priority group 1,
D/wpa_supplicant( 2020): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-55 wps,
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2020): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2020): wlan0:    selected based on RSN IE,
,D/wpa_supplicant( 2020): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700',
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
,D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
,D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
,D/wpa_supplicant( 2020): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb80e45a8  current_ssid=0x0
D/wpa_supplicant( 2020): scard is not null..,
D/wpa_supplicant( 2020): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
,D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01,
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
,D/wpa_supplicant( 2020): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2020): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2020): wlan0: Cancelling scan request
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2020): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2020): RSN: PMKSA cache search - network_ctx=0xb80e45a8 try_opportunistic=0
D/wpa_supplicant( 2020): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2020): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2020): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2020): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2020): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2020): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2020): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2020): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2020): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2020): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2020): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2020): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2020): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0),
D/wpa_supplicant( 2020): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2020): nl80211: Unsubscribe mgmt frames handle 0xb80e3590 (mode change)
D/wpa_supplicant( 2020): nl80211: Subscribe to mgmt frames with non-AP handle 0xb80e3590,
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0d
,D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09,
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590,
,D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2020): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2020):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020):   * freq=2412
D/wpa_supplicant( 2020):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2020):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020):   * Auth Type 0
D/wpa_supplicant( 2020):   * WPA Versions 0x2
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ],
W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  968): handleMessage: E msg.what=147461
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState,
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  968): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2020): nl80211: Connect request send successfully
,D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37,
D/wpa_supplicant( 2020): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2020): nl80211: Connect event
D/wpa_supplicant( 2020): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2020): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2020): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2020): wlan0: Association info event
D/wpa_supplicant( 2020): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2020): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2020): wlan0: freq=2412 MHz
D/wpa_supplicant( 2020): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2020): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2020): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2020): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): scard is not null..
D/wpa_supplicant( 2020): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2020): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2020): TDLS: Remove peers on association
D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2020): EAPOL: enable timer tick
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): wlan0: Cancelling scan request
,D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
,D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  968): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
,D/WifiStateMachine(  968): processMsg: DisconnectedState
D/wpa_supplicant( 2020): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 2c a3 c5 58 3b b4 2d a5 ec eb 51 07 92 4e e4 ...
D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2020): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2020): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2020): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2020):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2020):   key_nonce - hexdump(len=32): 2c a3 c5 58 3b b4 2d a5 ec eb 51 07 92 4e e4 f3 82 0f a0 8b 7d 90 4a 52 8e 37 e6 45 04 f9 a5 01
D/wpa_supplicant( 2020):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 2c a3 c5 58 3b b4 2d a5 ec eb 51 07 92 4e e4 ...
D/wpa_supplicant( 2020): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2020): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2020): Get randomness: len=32 entropy=5
D/wpa_supplicant( 2020): WPA: Renewed SNonce - hexdump(len=32): 82 79 fc 5c 0f dd 86 7e 88 c4 ea 1c 5c cd 29 ac b8 18 84 f8 e5 e7 bd 04 8b 70 54 30 51 18 dc b4
D/wpa_supplicant( 2020): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): WPA: Nonce1 - hexdump(len=32): 82 79 fc 5c 0f dd 86 7e 88 c4 ea 1c 5c cd 29 ac b8 18 84 f8 e5 e7 bd 04 8b 70 54 30 51 18 dc b4
D/wpa_supplicant( 2020): WPA: Nonce2 - hexdump(len=32): 2c a3 c5 58 3b b4 2d a5 ec eb 51 07 92 4e e4 f3 82 0f a0 8b 7d 90 4a 52 8e 37 e6 45 04 f9 a5 01,
D/wpa_supplicant( 2020): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2020): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2020): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2020): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2020): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2020): WPA: Derived Key MIC - hexdump(len=16): 02 20 5a 8a cc 80 ea 0c 2b cf e1 74 ba 39 19 1c
,D/wpa_supplicant( 2020): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 82 79 fc 5c 0f dd 86 7e 88 c4 ea 1c 5c cd 29 ...
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
,D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  968): processMsg: ConnectModeState
D/wpa_supplicant( 2020): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 2c a3 c5 58 3b b4 2d a5 ec eb 51 07 92 4e e4 ...
D/wpa_supplicant( 2020): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2020): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2020): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2020): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2020):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2020):   key_nonce - hexdump(len=32): 2c a3 c5 58 3b b4 2d a5 ec eb 51 07 92 4e e4 f3 82 0f a0 8b 7d 90 4a 52 8e 37 e6 45 04 f9 a5 01
D/wpa_supplicant( 2020):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_rsc - hexdump(len=8): 0a 5b 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_mic - hexdump(len=16): 3f cb 1f 8a 85 fb a0 78 39 69 44 eb 92 25 d5 4d
D/wpa_supplicant( 2020): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 2c a3 c5 58 3b b4 2d a5 ec eb 51 07 92 4e e4 ...
D/wpa_supplicant( 2020): RSN: encrypted key data - hexdump(len=56): c9 17 14 fd f2 31 63 af 69 11 3b 7c 0b 92 35 29 ee 56 48 ec cd 75 a3 a7 a0 e9 95 2c 95 66 4f 12 ...
D/wpa_supplicant( 2020): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2020): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2020): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2020): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 fc e6 ...
D/wpa_supplicant( 2020): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2020): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2020): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2020): WPA: Derived Key MIC - hexdump(len=16): df 7a e6 88 08 8b 05 c6 2d 01 d2 81 4b b3 db f7
D/wpa_supplicant( 2020): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2020): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb80e3c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2020):    addr=c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  968): handleMessage: X,
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2020): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2020): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2020): WPA: Group Key - hexdump(len=16): [REMOVED],
D/wpa_supplicant( 2020): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2020): WPA: RSC - hexdump(len=6): 0a 5b 00 00 00 00
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f2d03a key_idx=1 set_tx=0 seq_len=6 key_len=16,
D/wpa_supplicant( 2020):    broadcast key,
I/wpa_supplicant( 2020): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Cancelling authentication timeout
,D/wpa_supplicant( 2020): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2020): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2020): EAPOL: External notification - portValid=1,
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2020): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 2020): EAPOL authentication completed successfully
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): Network connection established
,D/WifiNative-wlan0(  968): doString: STATUS
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2020): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  968):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  968): ssid=NG700
D/WifiNative-wlan0(  968): id=0
D/WifiNative-wlan0(  968): mode=station
D/WifiNative-wlan0(  968): pairwise_cipher=CCMP
D/WifiNative-wlan0(  968): group_cipher=CCMP
D/WifiNative-wlan0(  968): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  968): wpa_state=COMPLETED
D/WifiNative-wlan0(  968): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  968): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  968): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  968): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
,D/DhcpStateMachine(  968): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  968): WaitBeforeStartState
D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-47ms what=147462 obj=android.net.wifi.StateChangeResult@43d6c9c0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-42ms what=147462 obj=android.net.wifi.StateChangeResult@43f7d208 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-42ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196612
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-15ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
,D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 6877): start selecting data
,D/SIMObserver( 6877): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity
,I/ActivityManager(  968): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7179 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/HyLog   ( 7179): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7179): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7179): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: SET ps 0
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  968):    returned null
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  968):    returned null
D/DhcpStateMachine(  968): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  968): DHCP Start wake lock is acquired.
E/WifiStateMachine(  968): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  266): Setting iface cfg
D/WifiP2pService(  968): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43040798 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43040798 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): addressUpdated: 192.168.1.160/24 on wlan0 flags 128 scope 0
D/CommandListener(  266): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  968): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-5ms what=131212 obj=192.168.1.160/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196613
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-5ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: SET ps 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): DHCP successful
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  968): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  968): VerifyingLinkState enter
D/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,W/WifiStateTracker(  968): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  968): 
W/WifiStateTracker(  968):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  968):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): handleMessage: X
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  968): send additional Connectivity Action
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
D/WifiStateMachine(  968): handleMessage: E msg.what=135190
D/WifiStateMachine(  968): processMsg: VerifyingLinkState
D/WifiStateMachine(  968): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  968): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/Parcel  (  395): Reading a NULL string not supported here.
,D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  968): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): CaptivePortalCheckState enter
,D/WifiStateMachine(  968): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  968): handleMessage: X
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  968): handleMessage: E msg.what=131092
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  968): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  968): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  968): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
E/Parcel  (  395): Reading a NULL string not supported here.
D/WifiStateMachine(  968): transitionTo: destState=ConnectedState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  968): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/DhcpStateMachine(  968): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  968): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  968): GC_EXPLICIT freed 2174K, 43% free 30761K/53756K, paused 5ms+13ms, total 162ms
,D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,E/Parcel  (  395): Reading a NULL string not supported here.
,E/ActivityThread(  968): Failed to find provider info for com.lge.ims.provisioning
I/LGEmail ( 7179): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  968): handleConnectivityChange: preConnState=2 connState=1
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,D/LGEmail ( 7179): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,D/QCNEA   (  395): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  395): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  395): |CAC| updateNetCfgInfo
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC|                   Netconfig               
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  395): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  395): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  395): |CAC| 	NetConfig: ip4        =192.168.1.160
V/QCNEA   (  395): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  395): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  395): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  395): |CAC| net type = 1
V/QCNEA   (  395): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  395): |CAC| Received ssid= NG700
V/QCNEA   (  395): |CAC| 	ssid           =NG700
V/QCNEA   (  395): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  395): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  395): |CAC| dispatchNetCfg: updating:0xb782f8dc
,D/QCNEA   (  395): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,W/BaseRuntimeLoader( 7179): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7179): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7179): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7179): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 7179): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4329): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,W/linker  ( 7179): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 7179): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 7179): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 7179): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 7179): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,D/HtmlEditor( 7179): register_HtmlEditor, Success
D/HtmlEditor( 7179): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 7179): register_HtmlEditorTimer, Success
,D/HtmlEditor( 7179): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 7179): register_HtmlEditorDownloader, Success
D/HtmlEditor( 7179): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 7179): register_HtmlEditorFont, Success
D/HtmlEditor( 7179): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 7179): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 7179): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7179): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 7179): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 7179): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 7179): JNI_OnLoad Success
,I/HubEmail( 7179): JNI_OnLoad()
I/HubEmail( 7179): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7179): registerNatives()
,I/HubEmail( 7179): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7179): registerNativeMethods()
,I/HubEmail( 7179): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 7179): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7220 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  968): Killing 6538:com.test.thalitest/u0a304 (adj 15): empty #17
,D/HyLog   ( 7220): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7220): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7220): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  968): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7233 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  968): Killing 6715:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7233): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  968): Killing 6505:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  968): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=7246 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7246): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7246): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7246): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 7246): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7246): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  968): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=7260 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  968): Killing 6674:com.google.android.configupdater/u0a3 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7260): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7260): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7260): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 7260): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7260): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 7260): intf.getDisplayName() = lo
I/Wireless_Storage( 7260): intf.getDisplayName() = sit0
I/Wireless_Storage( 7260): intf.getDisplayName() = p2p0
I/Wireless_Storage( 7260): intf.getDisplayName() = teql0
,I/Wireless_Storage( 7260): intf.getDisplayName() = wlan0
D/NFS     ( 7260): interface name:wlan0 name:wlan0
D/NFS     ( 7260): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 7260): interface name:wlan0 name:wlan0
D/NFS     ( 7260): addr:192.168.1.160 broadcast:192.168.1.255
,I/Wireless_Storage( 7260): CONNECT : WIFI_CONNECT
,I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7272 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  968): Killing 6828:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7272): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7272): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7272): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 7272): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/wpa_supplicant( 2020): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2020): EAPOL: disable timer tick
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WebViewChromium( 7272): Binding Chromium to the main looper Looper (main, tid 1) {428016e0}
,I/chromium( 7272): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7272): Initializing chromium process, renderers=0
,I/Adreno-EGL( 7272): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7272): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7272): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7272): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7272): Remote Branch: 
I/Adreno-EGL( 7272): Local Patches: 
I/Adreno-EGL( 7272): Reconstruct Branch: 
,W/chromium( 7272): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/NSApplication( 7272): Starting up...
,I/ActivityManager(  968): Killing 6889:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  968): Start proc com.test.thalitest for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener: pid=7311 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
,D/HyLog   ( 7311): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7311): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7311): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 7311): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42807cc0
,D/dalvikvm( 7311): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42807cc0
,D/jxcore_app_log( 7311): JniHelper::setJavaVM(0x416c6838), pthread_self() = 1073955156
,E/JX-Cordova( 7311): JXcore wasn't initialized yet
,D/QRemote ( 7134): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 7134): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 7134): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 7090): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7090): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 7134): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7134): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 7134): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 7134): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
I/ActivityManager(  968): Killing 6906:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6e068 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  968): NetTransition Wakelock for ConnectedState released by timeout
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  968): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  968): handleMessage: E msg.what=131212
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): processMsg: DriverStartedState
,D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  968): processMsg: SupplicantStartedState
,D/WifiStateMachine(  968): processMsg: DefaultState
,D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  968): send additional Connectivity Action
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
,D/WifiStateMachine(  968): handleMessage: X
,D/QcConnectivityService(  968): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  968):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  968): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/DhcpStateMachine(  968): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  968): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  968): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.160
V/LgDhcpStateMachineHelper(  968): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  968): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  968): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  968): RunningState
,D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
,D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
,D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 6877): start selecting data
,D/SIMObserver( 6877): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3975): begin check event
I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3975): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3975): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3975): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3975): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3975): handleAsyncCustNotification do not startCustService
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5882): DownloadService onCreate
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 7179): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4329): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 7246): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7246): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 7260): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7260): CONNECT : WIFI_CONNECT
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 5882): in removeSpuriousFiles
V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a97af0 on behalf of 5882
I/DownloadManager( 5882): in trimDatabase
E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 7179): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a99608 on behalf of 5882
V/DownloadManager( 5882): DownloadService onStartCommand
V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a9b630 on behalf of 5882
,V/DownloadManager( 5882): DownloadService onDestroy
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
D/AppUp4:CustFacade( 3975): isPhone : true
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/LicenseContentProvider( 6877): start selecting data
,D/SIMObserver( 6877): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5882): DownloadService onCreate
,I/DownloadManager( 5882): in removeSpuriousFiles
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 7179): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42a9fda0 on behalf of 5882
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5882): DownloadService onStartCommand
I/DownloadManager( 5882): in trimDatabase
V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42aa2e88 on behalf of 5882
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42aa2d40 on behalf of 5882
I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4329): networkInfo.isConnected() = true
,D/PhoneState( 4329): setPdpRejectCasuse : false
,W/Settings( 7179): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5882): DownloadService onDestroy
,D/GCM     ( 1531): Connected
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 7246): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1531): Message class com.google.f.a.a.p
I/NFS     ( 7260): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7260): CONNECT : WIFI_CONNECT
,W/ContextImpl( 7246): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
,D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 6877): start selecting data
,D/SIMObserver( 6877): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5882): DownloadService onCreate
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4329): networkInfo.isConnected() = true
,D/PhoneState( 4329): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 7246): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7246): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 7260): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7260): CONNECT : WIFI_CONNECT
,W/Settings( 7179): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 5882): in removeSpuriousFiles
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42aa75d0 on behalf of 5882
,I/DownloadManager( 5882): in trimDatabase
V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42aa8fe0 on behalf of 5882
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
V/DownloadManager( 5882): DownloadService onStartCommand
V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42aab190 on behalf of 5882
E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 5882): DownloadService onDestroy
I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  968): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454092989239876364; DSPS: 36079542; Offset: 1454091888179634665
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/GAV2    ( 7272): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  968): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  968): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  968): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  968): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  968): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454093009241276690; DSPS: 36734948; Offset: 1454091888179631183
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454093029242582301; DSPS: 37390351; Offset: 1454091888179624538
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454093040054, nextTick: 59975, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454093040056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454093049243453289; DSPS: 38045739; Offset: 1454091888179641034
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454093069244404365; DSPS: 38701131; Offset: 1454091888179615547
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454093089245710560; DSPS: 39356534; Offset: 1454091888179609486
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454093100048, nextTick: 59981, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454093100051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454093109247045213; DSPS: 40011937; Offset: 1454091888179631883
,D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2020): nl80211: Disconnect event
D/wpa_supplicant( 2020): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2020): wlan0: Deauthentication notification
D/wpa_supplicant( 2020): wlan0:  * reason 0
D/wpa_supplicant( 2020): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2020): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2020): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2020): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2020): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2020): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2020): wlan0: Disconnect event - remove keys,
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  968): handleMessage: E msg.what=147460,
D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState,
D/WifiStateMachine(  968): processMsg: ConnectModeState,
D/WifiStateMachine(  968): Network connection lost,
D/WifiStateMachine(  968): Stopping DHCP and clearing IP,
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  968): doBoolean: SET ps 1,
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb80e2d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2020):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2020): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  968): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
D/DhcpStateMachine(  968): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  266): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  968): addressRemoved: 192.168.1.160/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  968): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/wpa_supplicant( 2020): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2020): wlan0: nl80211: scan request
,D/wpa_supplicant( 2020): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2020): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2020): wlan0: nl80211: Scan trigger
,D/WifiHS20(  968): hidePasspointNotification off =false
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
D/QCNEA   (  395): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  395): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  395): |CAC| updateNetCfgInfo
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC|                   Netconfig               
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  395): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  395): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  395): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  395): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  395): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  395): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| Received bssid= 
D/QCNEA   (  395): |CAC| net type = 3
V/QCNEA   (  395): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  395): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  395): |CAC| 	ssid           =NG700
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  395): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  395): |CAC| dispatchNetCfg: updating:0xb782f8dc
D/QCNEA   (  395): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  968): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  968): Attempting to switch to mobile
D/QcConnectivityService(  968): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  968): handleConnectivityChange: preConnState=1 connState=2
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  968): invokeExitMethods: ConnectedState
D/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131213
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '124 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 124 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131213
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '125 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 125 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  968): handleMessage: X
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '126 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 126 Failed to remove route from default table (No such process)'
V/        (  266): RouteController
,I/PCSuite ( 7090): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7090): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7090): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 7134): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,W/NetworkManagementService(  968): route cmd failed: 
W/NetworkManagementService(  968): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '128 route del src v6 2' failed with '400 128 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  968): '
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  968): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  968): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  968): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  968): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  968): android_net_utils_resetConnections in env=0x62821170 clazz=0x48400001 iface=wlan0 mask=0x3
D/QcConnectivityService(  968): resetConnections(wlan0, 3)
,V/NativeCrypto( 1531): Read error: ssl=0x61264b20: I/O error during system call, Connection timed out
,V/NativeCrypto( 1531): SSL shutdown failed: ssl=0x61264b20: I/O error during system call, Broken pipe
,D/DhcpStateMachine(  968): StoppedState
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2020): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2020): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2020): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 2020): nl80211: Survey data missing
D/wpa_supplicant( 2020): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 2020): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 2020): wlan0: New scan results available
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2020): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2020): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2020): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2020): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2020): WPS: AP[2] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2020): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2020): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-55 wps
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2020): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2020): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-68
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: 3: 00:37:b7:9d:3e:73 ssid='FunBox2-3E72' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-90 wps
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2020): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2020): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2020): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-55 wps
D/wpa_supplicant( 2020): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2020): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2020): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2020): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2020): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb80e45a8  current_ssid=0x0
D/wpa_supplicant( 2020): scard is not null..
D/wpa_supplicant( 2020): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2020): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2020): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2020): WPA: Unrecognized ,EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2020): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2020): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2020): wlan0: Cancelling scan request
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): wlan0: WPA: clearing own WPA/RSN IE
,D/wpa_supplicant( 2020): wlan0: Automatic auth_alg selection: 0x1,
,D/wpa_supplicant( 2020): RSN: PMKSA cache search - network_ctx=0xb80e45a8 try_opportunistic=0
D/wpa_supplicant( 2020): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): RSN: No PMKSA cache entry found
,D/wpa_supplicant( 2020): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2020): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2020): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2020): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2020): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2020): wlan0: WPA: using KEY_MGMT WPA-PSK
,D/wpa_supplicant( 2020): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2020): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2020): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2020): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2020): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/Tethering(  968): MasterInitialState.processMessage what=3
D/wpa_supplicant( 2020): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2020): nl80211: Set mode ifindex 23 iftype 2 (STATION),
D/wpa_supplicant( 2020): nl80211: Unsubscribe mgmt frames handle 0xb80e3590 (mode change)
D/wpa_supplicant( 2020): nl80211: Subscribe to mgmt frames with non-AP handle 0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0c,
,D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 04 0e
,D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2020): nl80211: Register frame type=0xd0 nl_handle=0xb80e3590
D/wpa_supplicant( 2020): nl80211: Register frame match - hexdump(len=2): 0a 11,
D/wpa_supplicant( 2020): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2020):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020):   * freq=2412
D/wpa_supplicant( 2020):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2020):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2020):   * Auth Type 0
D/wpa_supplicant( 2020):   * WPA Versions 0x2
D/wpa_supplicant( 2020): nl80211: Connect request send successfully
D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2020): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/WifiStateMachine(  968): handleMessage: E msg.what=147461
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
,D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  968): doString: BSS RANGE=0- MASK=0x21987,
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2020): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/CaptivePortalTracker(  968): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE ,
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2020): nl80211: Event message available
D/wpa_supplicant( 2020): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2020): nl80211: Connect event
D/wpa_supplicant( 2020): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2020): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2020): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2020): wlan0: Association info event
D/wpa_supplicant( 2020): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2020): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2020): wlan0: freq=2412 MHz
D/wpa_supplicant( 2020): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2020): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2020): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2020): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): scard is not null..
D/wpa_supplicant( 2020): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2020): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2020): TDLS: Remove peers on association
D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2020): EAPOL: enable timer tick
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): wlan0: Cancelling scan request
,D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  968): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/wpa_supplicant( 2020): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ba db b6 fe 48 ed 11 f5 a8 ac 72 d8 bd a4 be ...
D/wpa_supplicant( 2020): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2020): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2020): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2020): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2020): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2020):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2020):   key_nonce - hexdump(len=32): ba db b6 fe 48 ed 11 f5 a8 ac 72 d8 bd a4 be fd 8f c9 0d 23 45 8b 0e d8 5c 2b 09 b1 e1 8c a9 b0
D/wpa_supplicant( 2020):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ba db b6 fe 48 ed 11 f5 a8 ac 72 d8 bd a4 be ...
D/wpa_supplicant( 2020): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2020): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2020): Get randomness: len=32 entropy=5,
D/wpa_supplicant( 2020): WPA: Renewed SNonce - hexdump(len=32): b1 d2 78 76 fa f6 98 81 f7 1b 62 56 58 ad d1 b5 04 45 a4 d8 e4 88 ab 25 92 fd 1b 3b 86 92 e2 b3
D/wpa_supplicant( 2020): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2020): WPA: Nonce1 - hexdump(len=32): b1 d2 78 76 fa f6 98 81 f7 1b 62 56 58 ad d1 b5 04 45 a4 d8 e4 88 ab 25 92 fd 1b 3b 86 92 e2 b3
D/wpa_supplicant( 2020): WPA: Nonce2 - hexdump(len=32): ba db b6 fe 48 ed 11 f5 a8 ac 72 d8 bd a4 be fd 8f c9 0d 23 45 8b 0e d8 5c 2b 09 b1 e1 8c a9 b0
D/wpa_supplicant( 2020): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2020): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2020): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2020): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2020): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2020): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2020): WPA: Derived Key MIC - hexdump(len=16): 18 08 9d d2 6a ff 20 dc 33 59 97 55 3f 40 f3 0f
,D/wpa_supplicant( 2020): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 b1 d2 78 76 fa f6 98 81 f7 1b 62 56 58 ad d1 ...
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  968): processMsg: DisconnectedState,
D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
,D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
D/wpa_supplicant( 2020): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ba db b6 fe 48 ed 11 f5 a8 ac 72 d8 bd a4 be ...
D/wpa_supplicant( 2020): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2020): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2020): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2020): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2020):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2020):   key_nonce - hexdump(len=32): ba db b6 fe 48 ed 11 f5 a8 ac 72 d8 bd a4 be fd 8f c9 0d 23 45 8b 0e d8 5c 2b 09 b1 e1 8c a9 b0
D/wpa_supplicant( 2020):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_rsc - hexdump(len=8): 93 5b 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2020):   key_mic - hexdump(len=16): a1 76 34 f1 a4 e0 99 45 2a 6c ee 6d 25 4c 37 6a
D/wpa_supplicant( 2020): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ba db b6 fe 48 ed 11 f5 a8 ac 72 d8 bd a4 be ...
D/wpa_supplicant( 2020): RSN: encrypted key data - hexdump(len=56): f4 43 0e b6 8a c0 f0 bb 95 a5 9e a6 08 5f e3 28 ea f0 2f 01 0d e8 18 24 96 67 2f 31 8f 11 f5 a7 ...
D/wpa_supplicant( 2020): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2020): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2020): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2020): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 fc e6 ...
D/wpa_supplicant( 2020): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2020): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2020): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2020): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2020): WPA: Derived Key MIC - hexdump(len=16): 8d f9 06 5d a7 97 57 19 75 57 f8 6f 06 f7 cf 1c
D/wpa_supplicant( 2020): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2020): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb80e3c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2020):    addr=c0:ff:d4:d3:aa:48
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2020): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2020): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2020): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2020): WPA: RSC - hexdump(len=6): 93 5b 00 00 00 00
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f2d03a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2020):    broadcast key
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2020): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2020): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2020): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2020): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2020): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2020): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2020): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2020): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2020): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2020): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2020): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2020): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2020): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2020): EAPOL authentication completed successfully
D/wpa_supplicant( 2020): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2020): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2020): nl80211: if_removed already cleared - ignore event,
,D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
,D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): Network connection established
,D/WifiNative-wlan0(  968): doString: STATUS
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2020): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2020): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  968):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  968): ssid=NG700
D/WifiNative-wlan0(  968): id=0
D/WifiNative-wlan0(  968): mode=station
D/WifiNative-wlan0(  968): pairwise_cipher=CCMP
D/WifiNative-wlan0(  968): group_cipher=CCMP
D/WifiNative-wlan0(  968): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  968): wpa_state=COMPLETED
D/WifiNative-wlan0(  968): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  968): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  968): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  968): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
,D/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
,D/DhcpStateMachine(  968): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  968): WaitBeforeStartState
D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: ObtainingIpState
,D/WifiStateMachine(  968): ObtainingIpState{ when=-36ms what=147462 obj=android.net.wifi.StateChangeResult@4338ca90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
,D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-31ms what=147462 obj=android.net.wifi.StateChangeResult@44591aa0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147459
,D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-32ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196612
,D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 6877): start selecting data
,D/SIMObserver( 6877): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 7179): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4329): networkInfo.isConnected() = false
,W/Settings( 7179): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 7246): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7246): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 7260): connectivityManager.getNetworkInfo = TYPE_WIFI
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doBoolean: SET ps 0
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  968):    returned null
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  968):    returned null
E/WifiStateMachine(  968): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  968): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  968): DHCP Start wake lock is acquired.
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43040798 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43040798 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  266): Setting iface cfg
D/CommandListener(  266): Trying to bring up wlan0
D/WifiStateMachine(  968): addressUpdated: 192.168.1.160/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  968): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.160/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196613
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: SET ps 1
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2020): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2020): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2020): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2020): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2020): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2020): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
,D/WifiStateMachine(  968): DHCP successful
I/Wireless_Storage( 7260): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 7260): intf.getDisplayName() = lo
I/Wireless_Storage( 7260): intf.getDisplayName() = sit0
I/Wireless_Storage( 7260): intf.getDisplayName() = p2p0
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  968): invokeEnterMethods: VerifyingLinkState
I/Wireless_Storage( 7260): intf.getDisplayName() = teql0
D/WifiStateMachine(  968): VerifyingLinkState enter
I/Wireless_Storage( 7260): intf.getDisplayName() = wlan0
D/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/Wireless_Storage( 7260): intf.getDisplayName() = rev_rmnet8
I/Wireless_Storage( 7260): intf.getDisplayName() = rev_rmnet2
I/Wireless_Storage( 7260): intf.getDisplayName() = rev_rmnet3
I/Wireless_Storage( 7260): intf.getDisplayName() = rev_rmnet4
I/Wireless_Storage( 7260): intf.getDisplayName() = rev_rmnet5
I/Wireless_Storage( 7260): intf.getDisplayName() = rev_rmnet6
I/Wireless_Storage( 7260): intf.getDisplayName() = rev_rmnet7
I/Wireless_Storage( 7260): intf.getDisplayName() = rev_rmnet0
I/Wireless_Storage( 7260): intf.getDisplayName() = rev_rmnet1
I/Wireless_Storage( 7260): intf.getDisplayName() = rmnet0
,I/Wireless_Storage( 7260): intf.getDisplayName() = rmnet1
I/Wireless_Storage( 7260): intf.getDisplayName() = rmnet2
I/Wireless_Storage( 7260): intf.getDisplayName() = rmnet3
I/Wireless_Storage( 7260): intf.getDisplayName() = rmnet4
I/Wireless_Storage( 7260): intf.getDisplayName() = rmnet5
I/Wireless_Storage( 7260): intf.getDisplayName() = rmnet6
,I/Wireless_Storage( 7260): intf.getDisplayName() = rmnet7
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/Wireless_Storage( 7260): CONNECT : WIFI_DISCONNECT
D/WifiStateMachine(  968): handleMessage: X
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  968): send additional Connectivity Action
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
D/WifiStateMachine(  968): handleMessage: E msg.what=135190
D/WifiStateMachine(  968): processMsg: VerifyingLinkState
D/WifiStateMachine(  968): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  968): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/Parcel  (  395): Reading a NULL string not supported here.
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/WifiStateTracker(  968): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  968): 
W/WifiStateTracker(  968):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  968):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  968): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): CaptivePortalCheckState enter
,D/WifiStateMachine(  968): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/WifiStateMachine(  968): handleMessage: X
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
E/Parcel  (  395): Reading a NULL string not supported here.
,D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  968): handleMessage: E msg.what=131092
D/WifiStateMachine(  968): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  968): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  968): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  968): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/WifiStateMachine(  968): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  968): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  968): handleMessage: X
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
,E/Parcel  (  395): Reading a NULL string not supported here.
E/ActivityThread(  968): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  968): handleConnectivityChange: preConnState=2 connState=1
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,V/        (  266): RouteController
,D/QRemote ( 7134): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/        (  266): RouteController
,D/QRemote ( 7134): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/        (  266): RouteController
,V/        (  266): RouteController
,D/QRemote ( 7134): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/        (  266): RouteController
,I/PCSuite ( 7090): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7090): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 7134): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7134): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 7134): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 7134): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  395): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  395): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  395): |CAC| updateNetCfgInfo
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC|                   Netconfig               
V/QCNEA   (  395): |CAC| *********************************************
V/QCNEA   (  395): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  395): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  395): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  395): |CAC| 	NetConfig: ip4        =192.168.1.160
V/QCNEA   (  395): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  395): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  395): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  395): |CAC| net type = 1
V/QCNEA   (  395): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  395): |CAC| Received ssid= NG700
V/QCNEA   (  395): |CAC| 	ssid           =NG700
V/QCNEA   (  395): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  395): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  395): |CAC| *********************************************
D/QCNEA   (  395): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  395): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  395): |CAC| dispatchNetCfg: updating:0xb782f8dc
D/QCNEA   (  395): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
D/DhcpStateMachine(  968): DHCP request on wlan0
D/LgDhcpStateMachineHelper(  968): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DhcpStateMachine(  968): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  968): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  968): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.160
,V/LgDhcpStateMachineHelper(  968): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  968): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  968): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  968): RunningState
,D/wpa_supplicant( 2020): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2020): EAPOL: disable timer tick
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  968): NetTransition Wakelock for ConnectedState released by timeout
,D/WifiStateMachine(  968): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  968): handleMessage: E msg.what=131212
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
,D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  968): processMsg: SupplicantStartedState
,D/WifiStateMachine(  968): processMsg: DefaultState
,D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.160/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  968): send additional Connectivity Action
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiStateMachine(  968): handleMessage: X
,D/QcConnectivityService(  968): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  968):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  968): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454093129248464334; DSPS: 40667344; Offset: 1454091888179616678
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
,D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
,D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 6877): start selecting data
,D/SIMObserver( 6877): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 3975): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3975): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 3975): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3975): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3975): handleAsyncCustNotification do not startCustService
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5882): DownloadService onCreate
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 7179): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4329): networkInfo.isConnected() = false
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 7246): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7246): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 7260): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7260): CONNECT : WIFI_CONNECT
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/DownloadManager( 5882): in removeSpuriousFiles
V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42ab0230 on behalf of 5882
,W/Settings( 7179): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 5882): DownloadService onStartCommand
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42ab2860 on behalf of 5882
,I/DownloadManager( 5882): in trimDatabase
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42ab41f8 on behalf of 5882
,V/DownloadManager( 5882): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 6877): start selecting data
,D/SIMObserver( 6877): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5882): DownloadService onCreate
,I/DownloadManager( 5882): in removeSpuriousFiles
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/dalvikvm(  968): GC_EXPLICIT freed 2710K, 43% free 30811K/53756K, paused 4ms+10ms, total 145ms
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42ab80e0 on behalf of 5882
,V/DownloadManager( 5882): DownloadService onStartCommand
,V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5882): in trimDatabase
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42abb220 on behalf of 5882
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42aba7c8 on behalf of 5882
I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4329): networkInfo.isConnected() = true
,D/PhoneState( 4329): setPdpRejectCasuse : false
,V/DownloadManager( 5882): DownloadService onDestroy
D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/Settings( 7179): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 7246): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7246): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 7260): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7260): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3975): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3975): onReceive
,D/AppUp4:CustFacade( 3975): Context : android.app.ReceiverRestrictedContext@428160c0
D/AppUp4:CustFacade( 3975): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3975): isOpenOperator : true
,D/AppUp4:CustFacade( 3975): isPhone : true
,I/LicenseContentProvider( 6877): start selecting data
,D/SIMObserver( 6877): simInfo1
,I/AppUp4:EulaManager( 3975): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3975): begin check event
,I/AppUp4:CustModeStarterReceiver( 3975): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5882): DownloadService onCreate
,D/EAS     ( 7179): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4329): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4329): networkInfo.isConnected() = true
,D/PhoneState( 4329): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6403): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6403): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2885): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 7246): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7246): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 7260): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7260): CONNECT : WIFI_CONNECT
,W/Settings( 7179): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 5882): in removeSpuriousFiles
,V/DownloadManager( 5882): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2885): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2885): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42abf860 on behalf of 5882
,I/DownloadManager( 5882): in trimDatabase
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5882): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42ac16a8 on behalf of 5882
V/DownloadManager( 5882): DownloadService onStartCommand
V/DownloadManager( 5882): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5882): created cursor android.database.sqlite.SQLiteCursor@42ac33a0 on behalf of 5882
,E/LGDMClient( 2885): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2885): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,V/DownloadManager( 5882): DownloadService onDestroy
,D/LGDMClient( 2885): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2885): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WifiServiceExtension(  968): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/GCM     ( 1531): Connected
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1531): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  968): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  968): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  968): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  968): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  968): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454093149250467166; DSPS: 41322769; Offset: 1454091888179635868
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454093160040, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1454093160054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454093169251338533; DSPS: 41978158; Offset: 1454091888179622225
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x4314fe40: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1531): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1531): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1531): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1531): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1531): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1531): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1531): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1531): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 6922): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6922): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6922): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6922): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6922): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6922): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6922): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6922): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 6922): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6922): isDataSchedulerEnabled():false
D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1454093189252737838; DSPS: 42633564; Offset: 1454091888179617721
,TIME-OUT KILL (timeout was 1200000ms)
```
