#### Test 50650278d1b06e8_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1975): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1975): launchTask
W/dalvikvm( 1975): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1975): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1975): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1975): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WZggJdH4P4gArFoL941_q7liCjNc3gbBAait3yuNii9OqvoeZwCGY7WeZM5igX6JcaflWjmOLmX-f541x8DPl337mCEeVlCD76U_TCiJTIqgcnfonm-YzjMMFBuZAMBibUdWGLVTfXwVXZoYzCuAHwkJ7vL2761xoY25Fj5K5LiMzSz2Ys9Wgue_leOgUZEGOlNsK8
I/GoogleURLConnFactory( 1975): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1975): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1975): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1975): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1975): No vision deps
D/libc    (  265): _dns_getaddrinfo: iptype =1
D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
--------- beginning of /dev/log/system
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/BaseAppContext( 1975): Using Auth Proxy for data requests.
W/BaseAppContext( 1975): Using Auth Proxy for data requests.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PeopleContactsSync( 1975): CP2 sync disabled
W/BaseAppContext( 1975): Using Auth Proxy for data requests.
I/dalvikvm( 1975): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1975): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1975): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1975): Using Auth Proxy for data requests.
W/BaseAppContext( 1975): Using Auth Proxy for data requests.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/BaseAppContext( 1975): Using Auth Proxy for data requests.
W/GAV2    ( 4576): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  964): Killing 4062:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4317da30 u0 com.android.settings/.UsbSettings t2}
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/dalvikvm( 1975): GC_CONCURRENT freed 1570K, 22% free 19443K/24832K, paused 3ms+3ms, total 41ms
D/dalvikvm( 1975): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/dalvikvm( 1975): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/ChimeraCfgMgr( 1975): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1975): Module APK com.google.android.play.games already loaded
I/ConfigFetchService( 1975): fetch service done; releasing wakelock
I/ConfigFetchService( 1975): stopping self
D/AndroidRuntime( 4630): 
D/AndroidRuntime( 4630): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4630): CheckJNI is OFF
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4630): Trying to load lib libjavacore.so 0x0
E/BatteryObserver( 1157): usb Uevent not necessary.
D/dalvikvm( 4630): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4630): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4630): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4630): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/dalvikvm( 4630): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4630): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4630): failed to load memtrack module: -2
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2029): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/AndroidRuntime( 4630): Calling main entry com.android.commands.am.Am
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4630
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
D/PermissionCache(  268): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (116 us)
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{4317da30 u0 com.android.settings/.UsbSettings t2}
I/Icing   ( 1975): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/ActivityManager(  964): resumeTopActivityLocked: Pausing null
D/UsbSettingsControl( 2603): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2603): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4630): Shutting down VM
I/SlideAside( 3763): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4630): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 2ms
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  964): startService SlideAside
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  964): setFocusedStack: mFocusedStack=ActivityStack{432f68b8 stackId=1, 2 tasks}
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{4317da30 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{4317da30 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Restarting ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4652 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3763): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3763): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/dalvikvm(  269): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
D/HyLog   ( 4652): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4652): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4652): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 16ms
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
D/Icing   ( 1975): Loaded CLD2 Version V2.0 - 20141016
V/WebViewChromium( 4652): Binding Chromium to the background looper Looper (main, tid 1) {42854e38}
I/chromium( 4652): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/BrowserProcessMain( 4652): Initializing chromium process, renderers=0
W/chromium( 4652): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4652): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4652): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4652): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4652): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4652): Remote Branch: 
I/Adreno-EGL( 4652): Local Patches: 
I/Adreno-EGL( 4652): Reconstruct Branch: 
I/Icing   ( 1975): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
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
,D/OpenGLRenderer( 4652): Enabling debug mode 0
,W/AwContents( 4652): nativeOnDraw failed; clearing to background color.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +325ms
,W/AwContents( 4652): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  964): IME STATUS OFF
,I/ActivityManager( 4652): Timeline: Activity_idle id: android.os.BinderProxy@428566f8 time:109668
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/JsMessageQueue( 4652): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4652): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4285a7d8
,D/dalvikvm( 4652): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4285a7d8
,D/jxcore_app_log( 4652): JniHelper::setJavaVM(0x41801808), pthread_self() = 1631647248
,D/JX-Cordova( 4652): jxcore cordova android initializing
,I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3} time:110084
D/ActivityManager(  964): no-history finish of ActivityRecord{4317da30 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  964): Finishing activity token=Token{42c5f640 ActivityRecord{4317da30 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{4317da30 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{4317da30 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2603): [AUTORUN] onStop()
,V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{4317da30 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4652): GC_CONCURRENT freed 2794K, 13% free 21848K/24832K, paused 3ms+1ms, total 36ms
D/dalvikvm( 4652): GC_FOR_ALLOC freed 210K, 13% free 21826K/24832K, paused 20ms, total 20ms
D/dalvikvm( 4652): GC_FOR_ALLOC freed 184K, 12% free 21855K/24832K, paused 21ms, total 21ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 23.655MB for 144892-byte allocation
D/dalvikvm( 4652): GC_FOR_ALLOC freed 253K, 13% free 21903K/24976K, paused 36ms, total 36ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 23.770MB for 217334-byte allocation
D/dalvikvm( 4652): GC_FOR_ALLOC freed 369K, 13% free 21977K/25192K, paused 33ms, total 33ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 23.947MB for 325996-byte allocation
D/dalvikvm( 4652): GC_FOR_ALLOC freed 568K, 14% free 22099K/25512K, paused 31ms, total 32ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 24.221MB for 488990-byte allocation
D/dalvikvm( 4652): GC_FOR_ALLOC freed 867K, 15% free 22276K/25992K, paused 27ms, total 28ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 24.626MB for 733480-byte allocation
D/dalvikvm( 4652): GC_FOR_ALLOC freed 1284K, 16% free 22533K/26712K, paused 26ms, total 27ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/dalvikvm( 4652): GC_CONCURRENT freed 1675K, 15% free 22906K/26712K, paused 2ms+2ms, total 36ms
D/dalvikvm( 4652): WAIT_FOR_CONCURRENT_GC blocked 23ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4652): GC_FOR_ALLOC freed 369K, 15% free 22862K/26712K, paused 21ms, total 22ms
I/dalvikvm-heap( 4652): Grow heap (frag case) to 26.074MB for 1650320-byte allocation
,D/dalvikvm( 4652): GC_CONCURRENT freed 1653K, 18% free 23432K/28324K, paused 2ms+2ms, total 30ms
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/dalvikvm( 4652): GC_FOR_ALLOC freed 1397K, 17% free 23518K/28324K, paused 34ms, total 34ms
,I/dalvikvm-heap( 4652): Grow heap (frag case) to 27.501MB for 2475476-byte allocation
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,D/dalvikvm( 4652): GC_CONCURRENT freed 419K, 16% free 25842K/30744K, paused 2ms+3ms, total 48ms
,D/dalvikvm( 4652): GC_FOR_ALLOC freed 4207K, 21% free 24471K/30744K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4652): Grow heap (frag case) to 29.613MB for 3713210-byte allocation
,D/dalvikvm( 4652): GC_CONCURRENT freed 283K, 19% free 28116K/34372K, paused 4ms+10ms, total 58ms
,D/dalvikvm( 4652): GC_FOR_ALLOC freed 3159K, 27% free 25432K/34372K, paused 24ms, total 24ms
,W/jxcore-log( 4652): Initializing JXcore engine
,W/jxcore-log( 4652): JXcore engine is ready
,D/dalvikvm( 4652): GC_CONCURRENT freed 352K, 19% free 28066K/34372K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 4652): WAIT_FOR_CONCURRENT_GC blocked 14ms
,W/jxcore-log( 4652): Starting JXcore engine
,W/jxcore-log( 4652): Platform android
W/jxcore-log( 4652): 
,W/jxcore-log( 4652): Process ARCH arm
W/jxcore-log( 4652): 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/jxcore-log( 4652): JXcore Cordova bridge is ready!
I/jxcore-log( 4652): 
,W/jxcore-log( 4652): JXcore engine is started
,I/chromium( 4652): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.457779 Y: -0.393204 Z: 9.751144 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457779 .y:-0.393204 .z:9.751144
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.457016 Y: -0.402664 Z: 9.735992 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457016 .y:-0.402664 .z:9.735992
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/ActivityManager(  964): Killing 4153:com.google.android.talk/u0a77 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3}
I/jxcore-log( 4652): Toggling radios to true
I/jxcore-log( 4652): 
D/BluetoothManagerService(  964): Message: 20
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43f020f8:true
D/BluetoothAdapter( 4652): enable(): BT is already enabled..!
D/WifiStateMachine(  964): handleMessage: E msg.what=131145
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DISCONNECT
D/WifiService(  964): New client listening to asynchronous messages
D/WifiService(  964): setWifiEnabled: true pid=4652, uid=10304
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  964): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  964): disconnect pid=4652, uid=10304
D/WifiService(  964): reconnect pid=4652, uid=10304
I/jxcore-log( 4652): Radios toggled
I/jxcore-log( 4652): 
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2029): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2029): wlan0: Cancelling scan request
D/wpa_supplicant( 2029): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2029): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2029): TDLS: Tear down peers
D/wpa_supplicant( 2029): wpa_driver_nl80211_disconnect(reason_code=3)
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4652): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4652): 
I/jxcore-log( 4652): Perf Test app loaded loaded
I/jxcore-log( 4652): 
I/Choreographer( 4652): Skipped 58 frames!  The application may be doing too much work on its main thread.
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
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb73ccd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2029): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2029): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2029): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2029): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2029): nl80211: Event message available
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2029): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2029): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
W/Settings(  964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131146
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiNative-wlan0(  964): doBoolean: RECONNECT
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2029): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2029): Fast associate: Old scan results
D/wpa_supplicant( 2029): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2029): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2029): wlan0: nl80211: scan request
D/wpa_supplicant( 2029): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147460
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection lost
D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2029): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2029): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2029): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2029): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/wpa_supplicant( 2029): nl80211: Event message available
D/wpa_supplicant( 2029): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2029): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/DhcpStateMachine(  964): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  265): Clearing all IP addresses on wlan0
D/WifiStateMachine(  964): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
I/chromium( 4652): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
D/QCNEA   (  404): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  404): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  404): |CAC| updateNetCfgInfo
V/QCNEA   (  404): |CAC| *********************************************
V/QCNEA   (  404): |CAC|                   Netconfig               
V/QCNEA   (  404): |CAC| *********************************************
V/QCNEA   (  404): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  404): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  404): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  404): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  404): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  404): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  404): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  404): |CAC| *********************************************
D/QCNEA   (  404): |CAC| Received bssid= 
D/QCNEA   (  404): |CAC| net type = 3
V/QCNEA   (  404): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  404): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  404): |CAC| 	ssid           =NG700
V/QCNEA   (  404): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  404): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  404): |CAC| *********************************************
D/QCNEA   (  404): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  404): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  404): |CAC| dispatchNetCfg: updating:0xb86a08dc
D/QCNEA   (  404): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  404): Reading a NULL string not supported here.
,E/Parcel  (  404): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  964): hidePasspointNotification off =false
D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
I/chromium( 4652): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4712 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  265): RouteController
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 4712): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4712): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4712): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,I/jxcore-log( 4652): check test folder
I/jxcore-log( 4652): 
,I/jxcore-log( 4652): found test : ./testFindPeers.js
I/jxcore-log( 4652): 
,V/        (  265): RouteController
,I/GAV2    ( 4576): Thread[GAThread,5,main]: No campaign data found.
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
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
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x61e89ed8 clazz=0x6b900001 iface=wlan0 mask=0x3
,I/PCSuite ( 4712): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 4712): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4712): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
,V/NativeCrypto( 1564): Read error: ssl=0x63da3e70: I/O error during system call, Connection timed out
,V/NativeCrypto( 1564): SSL shutdown failed: ssl=0x63da3e70: I/O error during system call, Broken pipe
,I/jxcore-log( 4652): found test : ./testSendData.js
I/jxcore-log( 4652): 
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4750 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  964): Killing 2144:android.process.media/u0a23 (adj 15): empty #17
,D/HyLog   ( 4750): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4750): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4750): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
,W/ActivityManager(  964): Failed to clear dns cache for: android.process.media
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,I/jxcore-log( 4652): found test : ./testSendData2.js
I/jxcore-log( 4652): 
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3}
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/QRemote ( 4750): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
E/jxcore  ( 4652): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 4652): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/chromium( 4652): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/QRemote ( 4750): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4750): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4750): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4750): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4750): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4750): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4750): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4750): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 3976:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  964): StoppedState
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1564): onDestroy
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1223): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4038): onReceive
,D/AppUp4:CustFacade( 4038): Context : android.app.ReceiverRestrictedContext@428692c8
D/AppUp4:CustFacade( 4038): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4038): isOpenOperator : true
,D/AppUp4:CustFacade( 4038): isPhone : true
,I/LicenseContentProvider( 2991): start selecting data
,D/SIMObserver( 2991): simInfo1
,I/AppUp4:EulaManager( 4038): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4038): begin check event
,I/AppUp4:CustModeStarterReceiver( 4038): Event For GoodConnectivity
,D/wpa_supplicant( 2029): nl80211: Event message available
D/wpa_supplicant( 2029): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2029): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2029): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2029): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 2029): nl80211: Survey data missing
D/wpa_supplicant( 2029): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 5 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 6 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 7 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 2029): wlan0: New scan results available
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2029): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2029): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2029): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2029): WPS: AP 64:7c:34:38:27:cc type 0 added
,D/wpa_supplicant( 2029): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2029): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[3] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[5] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): wlan0: Selecting BSS from priority group 1
,D/wpa_supplicant( 2029): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2029): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2029): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2029): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2029): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg_mdm_auto_connect_policy 0
,D/wpa_supplicant( 2029): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2029): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb73ce5a8  current_ssid=0x0
D/wpa_supplicant( 2029): scard is not null..
D/wpa_supplicant( 2029): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING,
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
,D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2029): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): TDLS: TDLS is allowed in the target BSS
,I/wpa_supplicant( 2029): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2029): wlan0: Cancelling scan request
D/wpa_supplicant( 2029): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2029): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2029): wlan0: Automatic auth_alg selection: 0x1
,D/wpa_supplicant( 2029): RSN: PMKSA cache search - network_ctx=0xb73ce5a8 try_opportunistic=0,
D/wpa_supplicant( 2029): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2029): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2029): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2029): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2029): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2029): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2029): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2029): wlan0: WPA: using KEY_MGMT WPA-PSK
,D/wpa_supplicant( 2029): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2029): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2029): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2029): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2029): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2029): nl80211: Unsubscribe mgmt frames handle 0xb73cd590 (mode change)
D/wpa_supplicant( 2029): nl80211: Subscribe to mgmt frames with non-AP handle 0xb73cd590
,D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb73cd590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb73cd590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb73cd590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb73cd590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0d
,D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb73cd590,
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb73cd590,
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb73cd590
,D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb73cd590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb73cd590,
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb73cd590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 0a 11,
D/wpa_supplicant( 2029): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2029):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029):   * freq=2412
D/wpa_supplicant( 2029):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2029):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029):   * Auth Type 0,
D/wpa_supplicant( 2029):   * WPA Versions 0x2,
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 a0:c5:62:7a:49:97]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 9e:93:4e:3e:ba:c5]
D/wpa_supplicant( 2029): nl80211: Connect request send successfully
D/wpa_supplicant( 2029): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2029): EAPOL: External notification - EAP success=0,
,D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
,I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4781 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 64:7c:34:38:27:cc]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 06:7c:34:38:27:cc]
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2029): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  964): handleMessage: X
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
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
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
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2029): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2029): EAPOL: enable timer tick
D/wpa_supplicant( 2029): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2029): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2029): wlan0: Cancelling scan request
D/wpa_supplicant( 2029): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0,x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2029): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ac fb 3a 98 af d0 8c 82 66 a5 ff cb 3b f9 21 ...
D/wpa_supplicant( 2029): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2029): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2029): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2029): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2029): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2029):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2029):   key_nonce - hexdump(len=32): ac fb 3a 98 af d0 8c 82 66 a5 ff cb 3b f9 21 c0 05 b3 ca c3 d7 fd d7 54 3a ae b4 02 14 92 5c ba
D/wpa_supplicant( 2029):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ac fb 3a 98 af d0 8c 82 66 a5 ff cb 3b f9 21 ...
D/wpa_supplicant( 2029): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2029): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2029): Get randomness: len=32 entropy=9
D/wpa_supplicant( 2029): WPA: Renewed SNonce - hexdump(len=32): b1 7f 4e 77 92 a8 40 38 51 25 95 a1 09 a8 89 04 ce 9c e2 1b ae 7f b2 d1 07 9c a9 fa 52 0b b5 55
D/wpa_supplicant( 2029): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): WPA: Nonce1 - hexdump(len=32): b1 7f 4e 77 92 a8 40 38 51 25 95 a1 09 a8 89 04 ce 9c e2 1b ae 7f b2 d1 07 9c a9 fa 52 0b b5 55
D/wpa_supplicant( 2029): WPA: Nonce2 - hexdump(len=32): ac fb 3a 98 af d0 8c 82 66 a5 ff cb 3b f9 21 c0 05 b3 ca c3 d7 fd d7 54 3a ae b4 02 14 92 5c ba
D/wpa_supplicant( 2029): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2029): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2029): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2029): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2029): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2029): WPA: Derived Key MIC - hexdump(len=16): ad 62 e7 81 95 ef d0 4d 73 a6 a1 c0 75 43 0c 46
D/wpa_supplicant( 2029): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 b1 7f 4e 77 92 a8 40 38 51 25 95 a1 09 a8 89 ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 4781): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4781): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4781): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2029): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ac fb 3a 98 af d0 8c 82 66 a5 ff cb 3b f9 21 ...
D/wpa_supplicant( 2029): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2029): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2029): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2029): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2029):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2029):   key_nonce - hexdump(len=32): ac fb 3a 98 af d0 8c 82 66 a5 ff cb 3b f9 21 c0 05 b3 ca c3 d7 fd d7 54 3a ae b4 02 14 92 5c ba
D/wpa_supplicant( 2029):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_rsc - hexdump(len=8): c0 6a 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_mic - hexdump(len=16): 1c 2c e8 30 b0 1f cc 5c 00 95 10 16 e8 f4 fe 2d
D/wpa_supplicant( 2029): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ac fb 3a 98 af d0 8c 82 66 a5 ff cb 3b f9 21 ...
D/wpa_supplicant( 2029): RSN: encrypted key data - hexdump(len=56): e2 f5 8a 6a b3 48 b4 8f b6 ad ba a1 bb bb ec 7c 8e 92 43 8a 58 d9 f8 cb 3a 5b 76 6a 06 32 40 cb ...
D/wpa_supplicant( 2029): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2029): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2029): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2029): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 4b 0f ...
D/wpa_supplicant( 2029): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2029): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2029): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2029): WPA: Derived Key MIC - hexdump(len=16): 0f 80 8d 98 bd a0 ea 3b d1 b3 10 4d 38 5e 1e ff
D/wpa_supplicant( 2029): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2029): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb73cdc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2029):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2029): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2029): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2029): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2029): WPA: RSC - hexdump(len=6): c0 6a 00 00 00 00
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ecf03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2029):    broadcast key
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
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
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection established
D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2029): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  964):    returned bssid=c0:ff:d4:d3:aa:48
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
I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/DhcpStateMachine(  964): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-10ms what=147462 obj=android.net.wifi.StateChangeResult@44ef40f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-8ms what=147462 obj=android.net.wifi.StateChangeResult@442aec68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-8ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2029): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,V/DownloadManager( 4781): DownloadService onCreate
,D/EAS     ( 4557): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4557): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4557): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4781): in removeSpuriousFiles
I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4327): networkInfo.isConnected() = false
,V/DownloadManager( 4781): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@428904f0 on behalf of 4781
,I/DownloadManager( 4781): in trimDatabase
,V/DownloadManager( 4781): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@42892060 on behalf of 4781
,V/DownloadManager( 4781): DownloadService onStartCommand
,V/DownloadManager( 4781): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/linker  ( 4557): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@42894490 on behalf of 4781
D/HtmlEditor( 4557): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4557): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4557): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4557): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4557): register_HtmlEditor, Success
D/HtmlEditor( 4557): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4557): register_HtmlEditorTimer, Success
D/HtmlEditor( 4557): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4557): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4557): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4557): register_HtmlEditorFont, Success
,D/HtmlEditor( 4557): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4557): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4557): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4557): register_HtmlEditorDrawImage, Success
,D/HtmlEditor( 4557): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4557): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4557): JNI_OnLoad Success
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4821 uid=10052 gids={50052, 3003}
I/HubEmail( 4557): JNI_OnLoad()
I/HubEmail( 4557): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4557): registerNatives()
I/HubEmail( 4557): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4557): registerNativeMethods()
I/HubEmail( 4557): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
V/DownloadManager( 4781): DownloadService onDestroy
W/Settings( 4557): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 4821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4821): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): Killing 4313:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3}
V/LGRssiData( 4821): [loadRssi] File not exist 
V/LGRssiData( 4821): [loadRssi] File not exist 
D/MobileConnectivityChangeReceiver( 4821): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/TelephonyAutoProfiling( 4821): [loadFeatureFromXml] *** start feature loading from xml
D/MobileConnectivityChangeReceiver( 4821): onReceive CONNECTIVITY_CHANGE networkType=1
D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd OK len = 0, 2
W/BaseRuntimeLoader( 4821): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4821): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  964): doBoolean: SET ps 0
W/BaseRuntimeLoader( 4821): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4821): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2029): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2029): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2029): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd: failed to issue private commands
V/TelephonyAutoProfiling( 4821): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
V/TelephonyAutoProfiling( 4821): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4821): [getValue] FEATURE key : vzw_roaming_state, value : null
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/PhoneMonitor( 4821): onOtaspChanged old =0, new =3
E/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd: failed to issue private commands
V/PhoneMonitor( 4821): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
D/WifiP2pService(  964): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4320f990 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4320f990 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  265): Setting iface cfg
D/WifiStateMachine(  964): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/CommandListener(  265): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4836 uid=10063 gids={50063, 3003, 1028, 1015}
,D/WifiStateMachine(  964): handleMessage: E msg.what=131212
,D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-10ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
,D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-10ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2029): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2029): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2029): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): DHCP successful
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
,D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
,D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/ActivityManager(  964): Killing 4482:com.android.defcontainer/u0a4 (adj 15): empty #17
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
E/Parcel  (  404): Reading a NULL string not supported here.
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
,D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
,D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3}
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/WifiStateMachine(  964): handleMessage: X
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/HyLog   ( 4836): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4836): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4836): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
,E/Parcel  (  404): Reading a NULL string not supported here.
,D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
E/Parcel  (  404): Reading a NULL string not supported here.
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4860 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  964): Killing 4516:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
,V/        (  265): RouteController
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4860): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  404): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  404): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  404): |CAC| updateNetCfgInfo
V/QCNEA   (  404): |CAC| *********************************************
V/QCNEA   (  404): |CAC|                   Netconfig               
V/QCNEA   (  404): |CAC| *********************************************
V/QCNEA   (  404): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  404): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  404): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  404): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  404): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  404): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  404): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  404): |CAC| *********************************************
D/QCNEA   (  404): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  404): |CAC| net type = 1
V/QCNEA   (  404): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  404): |CAC| Received ssid= NG700
V/QCNEA   (  404): |CAC| 	ssid           =NG700
V/QCNEA   (  404): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  404): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  404): |CAC| *********************************************
D/QCNEA   (  404): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  404): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  404): |CAC| dispatchNetCfg: updating:0xb86a08dc
D/QCNEA   (  404): |CAC| readCallback: read len:0, ret:-1, errno:11
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/DhcpStateMachine(  964): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  964): GC_EXPLICIT freed 23682K, 49% free 29706K/57520K, paused 4ms+8ms, total 123ms
,D/LGDMClient( 2868): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2868): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2868): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/CheckinService( 1975): Checking schedule, now: 1450655552394 next: 1450655496899
,I/CheckinService( 1975): active receiver: enabled
,E/LGDMClient( 2868): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2868): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2868): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4888 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/LGDMClient( 2868): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinService( 1975): Preparing to send checkin request
,I/EventLogService( 1975): Accumulating logs since 1450655463806
,D/HyLog   ( 4888): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4888): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4888): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4888): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4888): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/CheckinRequestBuilder( 1975): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4902 uid=10101 gids={50101, 1028, 1015, 3003}
E/ActivityThread( 1975): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  964): Killing 4544:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
,D/HyLog   ( 4902): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4902): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4902): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 4902): connectivityManager.getNetworkInfo = TYPE_WIFI
,D/dalvikvm( 1564): GC_EXPLICIT freed 1201K, 29% free 17823K/24832K, paused 2ms+3ms, total 28ms
I/Wireless_Storage( 4902): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4902): intf.getDisplayName() = lo
I/Wireless_Storage( 4902): intf.getDisplayName() = sit0
I/Wireless_Storage( 4902): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4902): intf.getDisplayName() = teql0
,I/Wireless_Storage( 4902): intf.getDisplayName() = wlan0
D/NFS     ( 4902): interface name:wlan0 name:wlan0
D/NFS     ( 4902): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4902): interface name:wlan0 name:wlan0
,D/NFS     ( 4902): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 4902): CONNECT : WIFI_CONNECT
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4919 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 4203:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4919): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4919): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4919): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/GAV2    ( 4919): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1564): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1564): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1564): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1564): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1564): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1975): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x431e9190: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4937 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4937): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4937): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4937): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4937): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4937): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4937): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4937): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4937): VFY: replacing opcode 0x62 at 0x005e
,V/WebViewChromium( 4919): Binding Chromium to the main looper Looper (main, tid 1) {42853550}
,I/chromium( 4919): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/MultiDex( 4937): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4937): install
,I/BrowserProcessMain( 4919): Initializing chromium process, renderers=0
,I/MultiDex( 4937): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4937): loading existing secondary dex files
,I/MultiDex( 4937): load found 3 secondary dex files
,I/MultiDex( 4937): install done
,W/chromium( 4919): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4919): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4919): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4919): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4919): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4919): Remote Branch: 
I/Adreno-EGL( 4919): Local Patches: 
I/Adreno-EGL( 4919): Reconstruct Branch: 
,D/dalvikvm( 4937): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4937): VFY: unable to resolve instance field 61
,D/dalvikvm( 4937): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4937): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4937): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4937): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4937): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4937): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4937): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4937): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4937): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4937): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285a7f8
,D/dalvikvm( 4937): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285a7f8
,D/dalvikvm( 4937): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285a7f8, skipping init
,D/dalvikvm( 4937): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4285a7f8
D/dalvikvm( 4937): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4285a7f8
,V/JNIHelp ( 4937): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 4919): Starting up...
,I/ActivityManager(  964): Killing 4218:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4750): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4750): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/QRemote ( 4750): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4750): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/dalvikvm( 4937): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285a7f8
,D/dalvikvm( 4937): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4285a7f8
D/dalvikvm( 4937): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4285a7f8
,D/dalvikvm( 4937): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4285a7f8
,D/QRemote ( 4750): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4750): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4712): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4712): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4750): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4750): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4750): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4750): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 4937): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1564): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1564): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1564): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1975): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1864): callingUid 10006, callindPid: 1864
,E/MDM     ( 1425): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1975): Restart initialization of location
,I/dalvikvm( 4937): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4937): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4937): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4937): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4937): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4937): VFY: replacing opcode 0x6e at 0x0201
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f82000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f82000
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
D/wpa_supplicant( 2029): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2029): EAPOL: disable timer tick
D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=2209947232
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4937): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a782b8
D/dalvikvm( 4937): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a782b8
,D/dalvikvm( 4937): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a782b8, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/dalvikvm( 4937): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5000): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4937): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4937): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 60ms
,I/Adreno-EGL( 4937): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4937): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4937): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4937): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4937): Remote Branch: 
I/Adreno-EGL( 4937): Local Patches: 
I/Adreno-EGL( 4937): Reconstruct Branch: 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 4937): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4937): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4937): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4937): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4937): Remote Branch: 
I/Adreno-EGL( 4937): Local Patches: 
I/Adreno-EGL( 4937): Reconstruct Branch: 
,I/Adreno-EGL( 4937): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4937): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4937): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4937): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4937): Remote Branch: 
I/Adreno-EGL( 4937): Local Patches: 
I/Adreno-EGL( 4937): Reconstruct Branch: 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/dalvikvm( 4652): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4652): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4652): VFY: replacing opcode 0x6e at 0x0002
W/Settings( 4937): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/AndroidRuntime( 4652): Shutting down VM
,W/dalvikvm( 4652): threadid=1: thread exiting with uncaught exception (group=0x41812e48)
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
W/ActivityManager(  964):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3 f}
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=3721285963
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1975): Classify the device as Phone.
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1975): Sending checkin request (11574 bytes)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/WifiStateMachine(  964): handleMessage: X
,D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,W/ActivityManager(  964): Activity pause timeout for ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
,V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f68b8 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  964): moveHomeStack:
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bff6d8 stackId=0, 1 tasks}
,V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  964): resumeTopActivityLocked: Resumed ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1490): [Launcher.java:4947:onStart()]onStart
I/ActivityManager(  964): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42bff6d8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1490): [Launcher.java:717:onResume()]onResume
I/[LGHome]EVENT( 1490): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/PhoneApp( 1450): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1490): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1490): [Launcher.java:868:onResume()]onResume end
D/WeatherAncestor( 1877): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 0:52:34
,D/UpdateThreadPoolManager( 1877): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1877): 2 : quick cover state : opened : 0
D/WeatherService( 1877): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1877): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1877): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1877): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1877): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1877): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 0:52:34
,D/WeatherService( 1877): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1877): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1877): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1877): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1877): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1877): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1877): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1877): 2 : This is isUpdating : false
D/WeatherService( 1877): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1877): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1877): 2 : Map key string is -2
,D/lim     ( 1877): 2 : time = 00:52
,I/WeatherReflect( 1877): Model Name : LG-D802
,D/WeatherTheme( 1877): 2 : Different view - status_min_formatted : 51 != 52
,D/WeatherTheme( 1877): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1877): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1877): 2 : Fixed theme : optimus
,D/WeatherTheme( 1877): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1877): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1877): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1877): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1877): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 3396K, 9% free 71336K/78308K, paused 39ms, total 39ms
,D/dalvikvm( 1490): GC_CONCURRENT freed 5513K, 9% free 60928K/66632K, paused 3ms+3ms, total 38ms
,D/dalvikvm( 1490): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/CheckinRequestBuilder( 1975): Checkin reason type: 8 attempt count: 1
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ActivityThread( 1975): Failed to find provider info for com.google.android.wearable.settings
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,I/GLSUser ( 1564): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1564): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1564): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1564): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1564): [DefaultAuthDelegateService] Use browser flow? false
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,W/CheckinRequestBuilder( 1975): awaiting user notification for token
,I/CheckinRequestBuilder( 1975): Classify the device as Phone.
,D/dalvikvm( 1490): GC_FOR_ALLOC freed 4867K, 9% free 61911K/67344K, paused 20ms, total 20ms
,I/CheckinTask( 1975): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1975): Checking schedule, now: 1450655554770 next: 1451232950768
,I/CheckinService( 1975): active receiver: disabled
,D/dalvikvm(  964): GC_CONCURRENT freed 2232K, 47% free 30790K/57520K, paused 5ms+5ms, total 114ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 102ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 61ms
D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 62ms
,I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1} time:119563
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x44e22e50: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/GCM     ( 1564): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@4284ffd0 time:119600
,D/UsbSettings( 2603): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2603): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2603): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2603): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{4317da30 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{4317da30 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bff6d8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1}
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,E/Parcel  (  404): Reading a NULL string not supported here.
,E/Parcel  (  404): Reading a NULL string not supported here.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1564): Connected
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1564): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4038): onReceive
,D/AppUp4:CustFacade( 4038): Context : android.app.ReceiverRestrictedContext@428692c8
D/AppUp4:CustFacade( 4038): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4038): isOpenOperator : true
,D/AppUp4:CustFacade( 4038): isPhone : true
,I/LicenseContentProvider( 2991): start selecting data
,D/SIMObserver( 2991): simInfo1
,I/AppUp4:EulaManager( 4038): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4038): begin check event
,I/AppUp4:CustModeStarterReceiver( 4038): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4038): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4038): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4038): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4038): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4038): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4781): DownloadService onCreate
,I/DownloadManager( 4781): in removeSpuriousFiles
,V/DownloadManager( 4781): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@4289a580 on behalf of 4781
,D/EAS     ( 4557): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 4781): in trimDatabase
V/DownloadManager( 4781): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/EAS     ( 4557): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@4289ba28 on behalf of 4781
D/eas_req ( 4557): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
V/DownloadManager( 4781): DownloadService onStartCommand
V/DownloadManager( 4781): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@4289dfc0 on behalf of 4781
D/Tethering(  964): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
V/DownloadManager( 4781): DownloadService onDestroy
I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4327): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 4821): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/Settings( 4557): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4821): onReceive CONNECTIVITY_CHANGE networkType=1
D/LGDMClient( 2868): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/LGDMClient( 2868): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/LGDMSGCM( 4888): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2868): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4902): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4902): CONNECT : WIFI_CONNECT
E/LGDMClient( 2868): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,W/ContextImpl( 4888): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2868): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2868): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2868): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4038): onReceive
,D/AppUp4:CustFacade( 4038): Context : android.app.ReceiverRestrictedContext@428692c8
D/AppUp4:CustFacade( 4038): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4038): isOpenOperator : true
,D/AppUp4:CustFacade( 4038): isPhone : true
I/LicenseContentProvider( 2991): start selecting data
,D/SIMObserver( 2991): simInfo1
,I/AppUp4:EulaManager( 4038): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4038): begin check event
,I/AppUp4:CustModeStarterReceiver( 4038): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4781): DownloadService onCreate
,D/EAS     ( 4557): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4557): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4781): in removeSpuriousFiles
,V/DownloadManager( 4781): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@428a2648 on behalf of 4781
,I/DownloadManager( 4781): in trimDatabase
I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4327): networkInfo.isConnected() = true
W/Settings( 4557): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/PhoneState( 4327): setPdpRejectCasuse : false
V/DownloadManager( 4781): DownloadService onStartCommand
,V/DownloadManager( 4781): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/MobileConnectivityChangeReceiver( 4821): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4821): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4781): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@428a5848 on behalf of 4781
,V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@428a42d8 on behalf of 4781
,D/LGDMClient( 2868): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4781): DownloadService onDestroy
D/LGDMClient( 2868): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4888): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2868): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4902): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4902): CONNECT : WIFI_CONNECT
W/ContextImpl( 4888): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2868): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2868): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2868): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2868): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1223): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1490): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email,
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1223): Disconnected process message: 10
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/WifiController(  964): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] BroadcastReceiver onReceive
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4038): [onReceive] request level :IDLE....
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/AppUp4:CustModeStarterReceiver( 4038): onReceive
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/AppUp4:CustFacade( 4038): Context : android.app.ReceiverRestrictedContext@428692c8
,D/AppUp4:CustFacade( 4038): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4038): isOpenOperator : true
,D/AppUp4:CustFacade( 4038): isPhone : true
,I/LicenseContentProvider( 2991): start selecting data
,D/SIMObserver( 2991): simInfo1
,I/AppUp4:EulaManager( 4038): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4038): begin check event
,I/AppUp4:CustModeStarterReceiver( 4038): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4557): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4781): DownloadService onCreate
,D/EAS     ( 4557): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4327): networkInfo.isConnected() = true
,D/PhoneState( 4327): setPdpRejectCasuse : false
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/MobileConnectivityChangeReceiver( 4821): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4821): onReceive CONNECTIVITY_CHANGE networkType=1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,D/HeadsetStateMachine( 1223): Disconnected process message: 10,
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/LGDMClient( 2868): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMSGCM( 4888): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 4781): in removeSpuriousFiles
,V/DownloadManager( 4781): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/Settings( 4557): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2868): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@428a9ef8 on behalf of 4781
I/DownloadManager( 4781): in trimDatabase
,V/DownloadManager( 4781): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@428ab508 on behalf of 4781
I/NFS     ( 4902): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4902): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4888): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2868): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
E/LGDMClient( 2868): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2868): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2868): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2868): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4781): DownloadService onStartCommand
V/DownloadManager( 4781): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@428adaa0 on behalf of 4781
V/DownloadManager( 4781): DownloadService onDestroy
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4919): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/ActivityManager(  964): Killing 4576:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/ActivityManager(  964): Killing 4712:com.lge.sync/1000 (adj 15): empty #17
I/ActivityManager(  964): Killing 4240:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bff6d8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bff6d8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bff6d8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  964): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5138 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5138): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5138): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5138): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  269): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+3ms, total 65ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+1ms, total 31ms
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 14ms
,I/dalvikvm( 5138): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 5138): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5138): VFY: replacing opcode 0x6e at 0x000b
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5138): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5138): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5138): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5138): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5138): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5138): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5138): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5138): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5138): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5138): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5138): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5138): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 5138): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5138): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5138): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5138): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5138): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5138): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5138): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5138): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 4781): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4781): created cursor android.database.sqlite.SQLiteCursor@428b2c40 on behalf of 5138
,I/dalvikvm( 5138): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5138): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5138): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5138): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5138): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5138): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5138): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5138): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5138): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5138): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/dalvikvm( 5138): Total arena pages for JIT: 11
,I/dalvikvm( 5138): Total arena pages for JIT: 12
I/dalvikvm( 5138): Total arena pages for JIT: 13
,I/dalvikvm( 5138): Total arena pages for JIT: 14
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5138): [456] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5138): [1] 5.onFinished: Installation state replication succeeded.
E/BatteryObserver( 1157): usb Uevent not necessary.
I/ActivityManager(  964): Killing 4750:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bff6d8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5138): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5138): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5138): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5138): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1564): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1564): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1564): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1564): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1564): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5138): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1564): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1564): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1564): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1564): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1564): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GLSUser ( 1564): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1564): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1564): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1564): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1564): GC_EXPLICIT freed 1269K, 29% free 17815K/24832K, paused 1ms+4ms, total 28ms
,I/Auth    ( 1564): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5138): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1564): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1564): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1564): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1564): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1564): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5138): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5138): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5138): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5138): [1] DailyHygiene.reschedule: Scheduling new run in 833 minutes (failures=5)
,D/DeviceConnectionService( 1425): client connected with version: 7571000
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.483459 Y: -0.399567 Z: 9.750961 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.483459 .y:-0.399567 .z:9.750961
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.458893 Y: -0.402756 Z: 9.753723 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458893 .y:-0.402756 .z:9.753723
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3763): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3763): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  964): Handling package changes for user 0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5214 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "mmsto"
D/HyLog   ( 5214): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5214): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5214): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Babel   ( 5214): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5214): MmsConfig.loadMmsSettings
I/Babel   ( 5214): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5214): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5214): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5214): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5214): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5214): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5214): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5214): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5214): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5214): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5214): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5214): MmsConfig.loadFromResources
,E/Babel   ( 5214): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5214): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings( 5214): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/GmsNetworkLocationProvi( 1425): DISABLE
,I/GCoreNlp( 1425): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/LGRssiData( 5214): [loadRssi] File not exist 
V/LGRssiData( 5214): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5214): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5214): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/AppUp4:Utils( 4038): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4038): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
V/TelephonyAutoProfiling( 5214): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5214): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4  ( 4038): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4038): onReceive
D/AppUp4:CustFacade( 4038): Context : android.app.ReceiverRestrictedContext@428692c8
D/AppUp4:CustFacade( 4038): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4038): isOpenOperator : true
D/AppUp4:CustFacade( 4038): isPhone : true
,I/LicenseContentProvider( 2991): start selecting data
,D/SIMObserver( 2991): simInfo1
,I/AppUp4:EulaManager( 4038): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4038): begin check event
D/AppUp4:Utils( 4038): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4038): Event For Nothing, skip.
,D/dalvikvm(  964): GC_EXPLICIT freed 2511K, 47% free 30666K/57520K, paused 3ms+8ms, total 88ms
,D/LocationProviderProxy(  964): applying state to connected service
I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5264 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  964): Killing 4652:com.test.thalitest/u0a304 (adj 15): empty #17
,D/LocationProviderProxy(  964): applying state to connected service
,D/HyLog   ( 5264): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5264): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5264): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WindowState(  964): WIN DEATH: Window{450154a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  964): Client connection lost with reason: 4
,I/[LGHome]EVENT( 1490): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{4502a740 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bff6d8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1}
,I/InputMethodManagerService(  964): IME STATUS OFF
,W/Binder  ( 1310): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1310): java.lang.NullPointerException
W/Binder  ( 1310): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1310): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1310): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1310): 	at dalvik.system.NativeStart.run(Native Method)
,W/InputMethodManagerService(  964): Got RemoteException sending setActive(false) notification to pid 4652 uid 10304
I/SystemConfig( 5264): BUILD Country: EU
,I/SystemConfig( 5264): BUILD Operator: OPEN
,I/SystemConfig( 5264): systemFeature RCS result false
I/ActivityManager(  964): Killing 4557:com.lge.email/u0a24 (adj 15): empty #17
,D/SystemConfig( 5264): refreshRcsSupport() :false
I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5282 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bff6d8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 5282): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5282): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5282): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2671): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  964): Killing 4821:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bff6d8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1975): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1975): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  964): Delaying start of: ServiceRecord{433b6b18 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1975): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1975): GC_CONCURRENT freed 1880K, 22% free 19549K/24832K, paused 5ms+4ms, total 37ms
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/IcingCorporaProvider( 2671): UpdateCorporaTask done [took 234 ms] updated apps [took 234 ms] 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/GAV4    ( 5214): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/PowerManagerService(  964): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  964): [updateScreenState] screen on = false
,D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  964): _hal_sensors_flush: handle=35
,I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 6337 usec
,D/qcom_sensors_hal(  964): hal_acquire_resources
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
I/qcom_sensors_hal(  964): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,D/qcom_sensors_hal(  964): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,I/qcom_sensors_hal(  964): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  964): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.449539 Y: -0.399811 Z: 9.782288 
,D/qcom_sensors_hal(  964): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  964): hal_sam_send_cancel: Sending cancel to 21,
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449539 .y:-0.399811 .z:9.782288
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0,
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  964): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.449707 Y: -0.392014 Z: 9.772583 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449707 .y:-0.392014 .z:9.772583
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Sensors (  365): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  964): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  964): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  964): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.458618 Y: -0.404938 Z: 9.767059 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458618 .y:-0.404938 .z:9.767059
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  964): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  964): proximitySensorChanged  positive = true
I/KnockOnPowerController(  964): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.455658 Y: -0.395248 Z: 9.774658 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455658 .y:-0.395248 .z:9.774658
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.453033 Y: -0.386246 Z: 9.763962 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453033 .y:-0.386246 .z:9.763962
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.454742 Y: -0.394257 Z: 9.760803 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454742 .y:-0.394257 .z:9.760803
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.452271 Y: -0.391541 Z: 9.773163 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452271 .y:-0.391541 .z:9.773163
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  964): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4331f9a0)
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
,D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/SurfaceFlinger(  268): Screen released, type=0 flinger=0xb892f450
D/qdhwcomposer(  268): hwc_blank: Blanking display: 0
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  964): **** SHOWN CALLED ****
I/WindowManager(  964): No lock screen! windowToken=null
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,E/SlideAside( 3763): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WifiStateMachine(  964): handleScreenStateChanged: true
,D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  964): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131127
D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=132097
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  964): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2029): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2029): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  964): stopMonitoring
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
V/SRS_Proc(  271): ParamSet string: screen_state=on
,D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433b13f0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WeatherAncestor( 1877): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 0:52:53
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,I/SlideAside( 3763): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1877): 2 : This is isUpdating : false
D/WeatherAncestor( 1877): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 0:52:53
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
D/WeatherService( 1877): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
D/WeatherService( 1877): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1877): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1877): 2 : shouldTimeTickRegistered : false
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
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.449997 Y: -0.397552 Z: 9.783188 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449997 .y:-0.397552 .z:9.783188
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
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
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.463943 Y: -0.403076 Z: 9.751495 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463943 .y:-0.403076 .z:9.751495
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/qdlights( 1157): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1157): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1157): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/qdhwcomposer(  268): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  964): Excessive delay in blankDisplay() while turning screen off: 420ms
,D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 6487K, 14% free 68563K/79640K, paused 23ms, total 23ms
D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655574304, nextTick: 5728, mDrawingTime: 1
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655574323, nextTick: 5710, mDrawingTime: 0
D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
,D/WeatherService( 1877): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 0:52:54
,D/WeatherService( 1877): 2 : ACTION screen on
,D/WeatherService( 1877): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1877): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 0:52:54
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/KeyguardViewMediator( 1143): notifyScreenOffLocked
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,I/[LGHome]EVENT( 1490): [Launcher.java:894:onPause()]onPause
,V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  964): hal_acquire_resources
D/qcom_sensors_hal(  964): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  964): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  964): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: Rcvd success response from request
,D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  964): Vibrator off
D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
,I/[LGHome]EVENT( 1490): [Launcher.java:4955:onStop()]onStop
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/KeyguardViewMediator( 1143): handleNotifyScreenOff
D/WifiStateMachine(  964): handleScreenStateChanged: false
,D/KeyguardViewManager( 1143): onScreenTurnedOff()
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
,D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{42c3cb38 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  964): CMD_SCREEN_OFF 
,D/WifiController(  964): shouldWifiStayAwake TRUE
E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
,D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1157): clear
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): handleMessage: X
D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
,I/[LGHome]EVENT( 1490): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
,D/WeatherService( 1877): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 0:52:54
D/WeatherService( 1877): 2 : ACTION screen off
,D/WeatherService( 1877): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 0:52:54
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
,E/Parcel  (  404): Reading a NULL string not supported here.
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_OFF
D/NfcService( 1475): NFC-C OFF
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
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
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1157): GC_CONCURRENT freed 2877K, 11% free 25450K/28504K, paused 15ms+2ms, total 55ms
,I/Sensors (  365): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655580048, nextTick: 59983, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655580053, nextTick: 59979, mDrawingTime: 0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigFetchService( 1975): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1975): running network task: configservice_periodic
,E/WakeLock( 1975): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1975): launchTask
,I/ConfigService( 1564): onCreate
,I/ConfigFetchService( 1975): service connected
,I/VacuumService( 1564): Vacuum at: now=1450655583337 tag=VacuumService
,D/ConfigFetchService( 1975): ConfigApi connection successful.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5138): [456] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5138): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655592248511676; DSPS: 5283122; Offset: 1450655431020423298
,V/ConfigFetchTask( 1975): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XXDGO401dUYWybOvIMJY35-jhtK2VRjXlplQcswlNqEBENZohTbbGNyq0j--ceIwZ6xiFrWPehapiN1kNOgJ9CYqq7cUizH1wWBEUGO6XA-004JWDSvvIkgla_ohLWSKdPpjpiGkSyFhS_bSoLB-6I14szxtZ4_C_uRa_j06Un2ZhIzDyHQ0x40dgDGqvmQFk8aeBI
,I/GoogleURLConnFactory( 1975): Using platform SSLCertificateSocketFactory
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ConfigFetchTask( 1975): updating config table for com.google.android.gms
,I/ConfigFetchService( 1975): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1975): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1975): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1975): fetch service done; releasing wakelock
,I/ConfigFetchService( 1975): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1975): stopping self
,I/GoogleURLConnFactory( 1564): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1564): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1564): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1564): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1564): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1564): No account for auth token provided
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1564): No account for auth token provided
,W/Uploader( 1564): No account for auth token provided
,W/Uploader( 1564):  no longer exists, so no auth token.
,W/Uploader( 1564): No account for auth token provided
,I/ConfigService( 1564): onDestroy
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655612249853218; DSPS: 5938526; Offset: 1450655431020422066
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655632251263979; DSPS: 6593932; Offset: 1450655431020429019
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655640039, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655640044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655652253235053; DSPS: 7249357; Offset: 1450655431020416450
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655672254102421; DSPS: 7904745; Offset: 1450655431020429326
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655692255016162; DSPS: 8560135; Offset: 1450655431020427539
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655700041, nextTick: 59988, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655700043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655712256396893; DSPS: 9215540; Offset: 1450655431020434979
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655732257254868; DSPS: 9870928; Offset: 1450655431020438462
,D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 5 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 6 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 7 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 2 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a],
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48],
,D/wpa_supplicant( 2029): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 64:7c:34:38:27:cc]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 06:7c:34:38:27:cc]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81]
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655752258612510; DSPS: 10526333; Offset: 1450655431020422813
,I/EventLogService( 1975): Aggregate from 1450655552426 (log), 1450653889277 (data)
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655760031, nextTick: 60001, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655760049, nextTick: 59984, mDrawingTime: 0
,D/dalvikvm( 2658): GC_CONCURRENT freed 7734K, 32% free 16918K/24832K, paused 2ms+2ms, total 36ms
,D/dalvikvm( 2658): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655772259993207; DSPS: 11181738; Offset: 1450655431020430219
,I/LocationManagerService(  964): remove 43150738
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2658): GC_CONCURRENT freed 1929K, 32% free 17001K/24832K, paused 3ms+1ms, total 29ms
,D/dalvikvm( 2658): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2658): GC_CONCURRENT freed 1776K, 31% free 17272K/24832K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2658): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/Mlt MonitorService( 2658): parseLastkmsg to dump
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655792261372926; DSPS: 11837143; Offset: 1450655431020436647
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655812262828354; DSPS: 12492551; Offset: 1450655431020427231
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655820043, nextTick: 59987, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655820047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655832264224352; DSPS: 13147957; Offset: 1450655431020419421
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655852265540245; DSPS: 13803360; Offset: 1450655431020423058
,I/GLSUser ( 1564): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1564): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1564): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1564): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1564): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x443f4e20: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1564): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1564): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1564): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1564): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1564): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1564): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1564): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1564): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 5138): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5138): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5138): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5138): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5138): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5138): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5138): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5138): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 5138): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5138): isDataSchedulerEnabled():false
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655872266873981; DSPS: 14458764; Offset: 1450655431020414021
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655880043, nextTick: 59985, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655880047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655892268259711; DSPS: 15114169; Offset: 1450655431020426460
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655912269114279; DSPS: 15769557; Offset: 1450655431020426535
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655932269988710; DSPS: 16424946; Offset: 1450655431020415957
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655940039, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450655940048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655952271364241; DSPS: 17080351; Offset: 1450655431020418197
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655972272924231; DSPS: 17735762; Offset: 1450655431020421790
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450655992273789996; DSPS: 18391150; Offset: 1450655431020433063
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656000039, nextTick: 59968, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656000055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656012275148887; DSPS: 19046555; Offset: 1450655431020418663
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656032276007871; DSPS: 19701943; Offset: 1450655431020423155,
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656052276928383; DSPS: 20357333; Offset: 1450655431020428139
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656060032, nextTick: 59992, mDrawingTime: 6
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656060064, nextTick: 59968, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656072278317906; DSPS: 21012738; Offset: 1450655431020444371
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656092279170902; DSPS: 21668126; Offset: 1450655431020442875
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656112280580869; DSPS: 22323533; Offset: 1450655431020418516
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656120039, nextTick: 59975, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656120050, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656132282694463; DSPS: 22978962; Offset: 1450655431020426397
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656152283565297; DSPS: 23634350; Offset: 1450655431020442739
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656172284454274; DSPS: 24289739; Offset: 1450655431020446706
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656180037, nextTick: 59986, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656180042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656192285902544; DSPS: 24945147; Offset: 1450655431020430132
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656212286751897; DSPS: 25600535; Offset: 1450655431020424993
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656232287624036; DSPS: 26255924; Offset: 1450655431020412122
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656240043, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656240049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656252289072582; DSPS: 26911331; Offset: 1450655431020426342
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  964): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  964): Done.
,D/QcConnectivityService(  964): Setting timer for 720seconds
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656272289938351; DSPS: 27566719; Offset: 1450655431020437619
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656292290811680; DSPS: 28222108; Offset: 1450655431020425938
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656300037, nextTick: 59987, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656300043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656312292874082; DSPS: 28877536; Offset: 1450655431020413145
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656332293780436; DSPS: 29532925; Offset: 1450655431020434489
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656352294649251; DSPS: 30188314; Offset: 1450655431020418294
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656360037, nextTick: 59988, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656360042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656372296026921; DSPS: 30843719; Offset: 1450655431020422673
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656392296889786; DSPS: 31499107; Offset: 1450655431020431046
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656412297751344; DSPS: 32154495; Offset: 1450655431020438112
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656420037, nextTick: 59991, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656420039, nextTick: 59992, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656432299169542; DSPS: 32809902; Offset: 1450655431020421984
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656452300003819; DSPS: 33465289; Offset: 1450655431020432286
,D/GCM     ( 1564): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656472300991708; DSPS: 34120681; Offset: 1450655431020443613
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656480039, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656480055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656492303030188; DSPS: 34776108; Offset: 1450655431020437415
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656512303870258; DSPS: 35431496; Offset: 1450655431020422993
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656532304727980; DSPS: 36086884; Offset: 1450655431020426223
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656540042, nextTick: 59976, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656540053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656552306116670; DSPS: 36742289; Offset: 1450655431020441622
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656572306957077; DSPS: 37397677; Offset: 1450655431020427536
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656592307828585; DSPS: 38053066; Offset: 1450655431020414035
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656600041, nextTick: 59971, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656600054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656612309283102; DSPS: 38708473; Offset: 1450655431020434226
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656632310133745; DSPS: 39363861; Offset: 1450655431020430376
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656652311019633; DSPS: 40019250; Offset: 1450655431020431255
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656660039, nextTick: 59984, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656660044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656672313157095; DSPS: 40674679; Offset: 1450655431020463004
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656692314448925; DSPS: 41330082; Offset: 1450655431020442578
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656712315297312; DSPS: 41985471; Offset: 1450655431020405955
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656720027, nextTick: 60002, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656720046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656732316709525; DSPS: 42640876; Offset: 1450655431020444877
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656752317616752; DSPS: 43296266; Offset: 1450655431020436577
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656772318484933; DSPS: 43951655; Offset: 1450655431020419748
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656780043, nextTick: 59983, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656780056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656792319893345; DSPS: 44607061; Offset: 1450655431020424351
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656812320741252; DSPS: 45262448; Offset: 1450655431020448284
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656832321622756; DSPS: 45917837; Offset: 1450655431020444778
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656840043, nextTick: 59986, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656840055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656852323728286; DSPS: 46573267; Offset: 1450655431020414078
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656872324584893; DSPS: 47228655; Offset: 1450655431020416192
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656892325509636; DSPS: 47884045; Offset: 1450655431020425408
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656900042, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656900054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656912326910799; DSPS: 48539451; Offset: 1450655431020422762
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656932327772518; DSPS: 49194839; Offset: 1450655431020429989
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656952329134000; DSPS: 49850244; Offset: 1450655431020418180
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656960046, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450656960049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656972330486864; DSPS: 50505648; Offset: 1450655431020428271
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450656992331338317; DSPS: 51161036; Offset: 1450655431020425232
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657012332864700; DSPS: 51816446; Offset: 1450655431020425736
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657020049, nextTick: 59976, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657020054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657032334302418; DSPS: 52471853; Offset: 1450655431020429127
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657052335594770; DSPS: 53127256; Offset: 1450655431020409224
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657072336458883; DSPS: 53782644; Offset: 1450655431020418844
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657080030, nextTick: 60001, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657080048, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657092337909035; DSPS: 54438051; Offset: 1450655431020434670
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657112338774908; DSPS: 55093440; Offset: 1450655431020415533
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657132340085868; DSPS: 55748843; Offset: 1450655431020414238
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657140041, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657140050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657152341473290; DSPS: 56404248; Offset: 1450655431020428369
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657172343014155; DSPS: 57059658; Offset: 1450655431020443355
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657192343881724; DSPS: 57715047; Offset: 1450655431020425914
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657200050, nextTick: 59975, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657200054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657212345281404; DSPS: 58370453; Offset: 1450655431020421785
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657232346166951; DSPS: 59025842; Offset: 1450655431020422323
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657252347528108; DSPS: 59681246; Offset: 1450655431020440706
,I/ProcessStatsService(  964): Prepared write state in 49ms
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657260081, nextTick: 59949, mDrawingTime: 2
D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657260082, nextTick: 59950, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  964): Pruning old procstats: /data/system/procstats/state-2015-12-20-03-40-01.bin
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657272347966552; DSPS: 60336621; Offset: 1450655431020421386
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657292348847765; DSPS: 60992010; Offset: 1450655431020417590
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657312349779562; DSPS: 61647400; Offset: 1450655431020433859
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657320034, nextTick: 59986, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450657320042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657332350230549; DSPS: 62302775; Offset: 1450655431020427083
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450657352351112680; DSPS: 62958164; Offset: 1450655431020424204
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  964): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  964): Done.
,D/QcConnectivityService(  964): Setting timer for 720seconds
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1564): GC_CONCURRENT freed 1650K, 28% free 18090K/24832K, paused 3ms+4ms, total 156ms
,D/dalvikvm(  964): GC_EXPLICIT freed 3326K, 47% free 30694K/57520K, paused 4ms+10ms, total 161ms
,I/GoogleURLConnFactory( 1564): Using platform SSLCertificateSocketFactory
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1564): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1564): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1564): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1564): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1564): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1564): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,TIME-OUT KILL (timeout was 1800000ms)
```
