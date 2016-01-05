#### Test 54970261fc259e9_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/ChimeraCfgMgr( 1888): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1888): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1888): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1888): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1888): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1888): No vision deps
V/ConfigFetchTask( 1888): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1W9fNZkndPTLEURawSgh7EhG4xTmFfx7zT21aOcdrVeJToRAiXFeiQW0Ra10b9mLdBjvD96j_3NKjmRgK9s-Ik1eH-3Tg01sQAMXdaZDbiv8anB50GkawVJP2zSjrnhjs_tEYOGYeG-oOSJTtwocnPe4ErcApJ9WYpsPKK7oIbIRcnHSUcT_PCxx081k5wn2EQb4jY8
I/GoogleURLConnFactory( 1888): Using platform SSLCertificateSocketFactory
W/BaseAppContext( 1888): Using Auth Proxy for data requests.
W/BaseAppContext( 1888): Using Auth Proxy for data requests.
D/libc    (  270): _dns_getaddrinfo: iptype =1
D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/PeopleContactsSync( 1888): CP2 sync disabled
I/dalvikvm( 1888): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1888): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1888): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1888): Using Auth Proxy for data requests.
W/BaseAppContext( 1888): Using Auth Proxy for data requests.
W/BaseAppContext( 1888): Using Auth Proxy for data requests.
W/BaseAppContext( 1888): Using Auth Proxy for data requests.
,W/GAV2    ( 4596): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  960): Killing 3932:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{4362f1a0 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1545): GC_EXPLICIT freed 1203K, 29% free 17828K/24832K, paused 3ms+6ms, total 43ms
D/dalvikvm( 1888): GC_CONCURRENT freed 1575K, 22% free 19458K/24832K, paused 3ms+5ms, total 46ms
D/dalvikvm( 1888): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 1888): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/AndroidRuntime( 4636): 
D/AndroidRuntime( 4636): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4636): CheckJNI is OFF
D/dalvikvm( 4636): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4636): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4636): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4636): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4636): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/ChimeraCfgMgr( 1888): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1888): Module APK com.google.android.play.games already loaded
D/dalvikvm( 4636): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/ConfigFetchService( 1888): fetch service done; releasing wakelock
I/ConfigFetchService( 1888): stopping self
E/memtrack( 4636): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4636): failed to load memtrack module: -2
D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
D/AndroidRuntime( 4636): Calling main entry com.android.commands.am.Am
D/wpa_supplicant( 2039): nl80211: survey data missing!
D/WifiStateMachine(  960): handleMessage: X
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4636
I/Icing   ( 1888): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
D/PermissionCache(  273): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (128 us)
V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{4362f1a0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  960): resumeTopActivityLocked: Pausing null
V/ActivityManager(  960): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  960): startService SlideAside
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  960): setFocusedStack: mFocusedStack=ActivityStack{438b09d8 stackId=1, 2 tasks}
D/AndroidRuntime( 4636): Shutting down VM
D/UsbSettingsControl( 2594): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2594): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4636): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+1ms, total 4ms
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{4362f1a0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{4362f1a0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Restarting ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  960): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4650 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3698): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/SlideAside( 3698): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3698): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4650): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4650): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4650): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/Icing   ( 1888): Loaded CLD2 Version V2.0 - 20141016
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
V/WebViewChromium( 4650): Binding Chromium to the background looper Looper (main, tid 1) {42e17818}
I/chromium( 4650): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4650): Initializing chromium process, renderers=0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  960): battery changed pluggedType: 2
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
W/chromium( 4650): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Icing   ( 1888): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Adreno-EGL( 4650): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4650): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4650): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4650): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4650): Remote Branch: 
I/Adreno-EGL( 4650): Local Patches: 
I/Adreno-EGL( 4650): Reconstruct Branch: 
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/dalvikvm( 4650): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4650): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4650): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4650): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4650): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4650): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4650): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4650): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4650): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4650): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4650): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4650): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4650): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4650): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4650): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4650): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4650): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4650): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4650): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4650): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4650): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4650): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4650): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4650): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4650): Enabling debug mode 0
W/AwContents( 4650): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  960): IME STATUS OFF
W/AwContents( 4650): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  960): Displayed com.test.thalitest/.MainActivity: +556ms
I/ActivityManager( 4650): Timeline: Activity_idle id: android.os.BinderProxy@42e18fe8 time:109335
I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3} time:109535
D/ActivityManager(  960): no-history finish of ActivityRecord{4362f1a0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  960): Finishing activity token=Token{4325e088 ActivityRecord{4362f1a0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  960): Moving to FINISHING: ActivityRecord{4362f1a0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
D/UsbSettings( 2594): [AUTORUN] onStop()
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{4362f1a0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{4362f1a0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/JsMessageQueue( 4650): Set native->JS mode to OnlineEventsBridgeMode
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/chromium( 4650): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/dalvikvm( 4650): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42e1d0c8
,D/dalvikvm( 4650): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42e1d0c8
,D/jxcore_app_log( 4650): JniHelper::setJavaVM(0x41dcf808), pthread_self() = 1632227680
,D/JX-Cordova( 4650): jxcore cordova android initializing
,I/chromium( 4650): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4650): GC_CONCURRENT freed 2748K, 12% free 21893K/24832K, paused 2ms+1ms, total 53ms
,D/dalvikvm( 4650): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 165K, 12% free 21912K/24832K, paused 29ms, total 29ms
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 132K, 12% free 21926K/24832K, paused 36ms, total 37ms
,I/dalvikvm-heap( 4650): Grow heap (frag case) to 23.677MB for 95956-byte allocation
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 179K, 12% free 21961K/24928K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4650): Grow heap (frag case) to 23.757MB for 143930-byte allocation
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 253K, 13% free 22008K/25072K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4650): Grow heap (frag case) to 23.872MB for 215890-byte allocation
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 368K, 13% free 22082K/25284K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4650): Grow heap (frag case) to 24.047MB for 323830-byte allocation
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 566K, 14% free 22203K/25604K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4650): Grow heap (frag case) to 24.320MB for 485740-byte allocation
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 863K, 15% free 22378K/26080K, paused 26ms, total 26ms
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 1281K, 14% free 22634K/26080K, paused 23ms, total 24ms
,I/dalvikvm-heap( 4650): Grow heap (frag case) to 25.320MB for 1092904-byte allocation
,D/dalvikvm( 4650): GC_CONCURRENT freed 1748K, 16% free 23019K/27148K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 298K, 16% free 22953K/27148K, paused 23ms, total 24ms
,I/dalvikvm-heap( 4650): Grow heap (frag case) to 26.152MB for 1639352-byte allocation
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  960): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  960): battery changed pluggedType: 2
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/dalvikvm( 4650): GC_CONCURRENT freed 1736K, 19% free 23533K/28752K, paused 1ms+2ms, total 29ms
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 1263K, 18% free 23586K/28752K, paused 43ms, total 44ms
,I/dalvikvm-heap( 4650): Grow heap (frag case) to 27.551MB for 2459024-byte allocation
,D/dalvikvm( 4650): GC_CONCURRENT freed 313K, 17% free 25890K/31156K, paused 2ms+2ms, total 39ms
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 4296K, 22% free 24578K/31156K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4650): Grow heap (frag case) to 29.694MB for 3688532-byte allocation
,D/dalvikvm( 4650): GC_CONCURRENT freed 261K, 20% free 27987K/34760K, paused 4ms+3ms, total 32ms
,D/dalvikvm( 4650): GC_FOR_ALLOC freed 3434K, 27% free 25558K/34760K, paused 26ms, total 26ms
,W/jxcore-log( 4650): Initializing JXcore engine
,W/jxcore-log( 4650): JXcore engine is ready
,D/dalvikvm( 4650): GC_CONCURRENT freed 397K, 19% free 28183K/34760K, paused 1ms+3ms, total 31ms
,D/dalvikvm( 4650): WAIT_FOR_CONCURRENT_GC blocked 29ms
,W/jxcore-log( 4650): Starting JXcore engine
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,W/jxcore-log( 4650): Platform android
W/jxcore-log( 4650): 
,W/jxcore-log( 4650): Process ARCH arm
W/jxcore-log( 4650): 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  960): battery changed pluggedType: 2
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/jxcore-log( 4650): JXcore Cordova bridge is ready!
I/jxcore-log( 4650): 
,W/jxcore-log( 4650): JXcore engine is started
,I/chromium( 4650): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4650): Skipped 161 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4650): Toggling radios to true
I/jxcore-log( 4650): 
,D/BluetoothManagerService(  960): Message: 20
,D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44176e10:true
,D/BluetoothAdapter( 4650): enable(): BT is already enabled..!
D/WifiStateMachine(  960): handleMessage: E msg.what=131145
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doBoolean: DISCONNECT
D/WifiService(  960): New client listening to asynchronous messages
D/WifiService(  960): setWifiEnabled: true pid=4650, uid=10304
E/WifiService(  960): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  960): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  960): disconnect pid=4650, uid=10304
,D/WifiService(  960): reconnect pid=4650, uid=10304
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2039): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2039): wlan0: Cancelling scan request
D/wpa_supplicant( 2039): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2039): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2039): TDLS: Tear down peers
D/wpa_supplicant( 2039): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4650): Radios toggled
I/jxcore-log( 4650): 
,D/wpa_supplicant( 2039): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2039): wlan0: Deauthentication notification
D/wpa_supplicant( 2039): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2039): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2039): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2039): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2039): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2039): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7b00d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2039):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2039): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2039): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2039): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2039): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2039): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2039): nl80211: Event message available
D/wpa_supplicant( 2039): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2039): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: ConnectedState
W/Settings(  960): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  960): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  960): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131146
D/WifiStateMachine(  960): processMsg: DisconnectingState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiNative-wlan0(  960): doBoolean: RECONNECT
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2039): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2039): Fast associate: Old scan results
D/wpa_supplicant( 2039): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2039): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2039): wlan0: nl80211: scan request
D/wpa_supplicant( 2039): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): handleMessage: X
D/wpa_supplicant( 2039): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2039): nl80211: Event message available
D/wpa_supplicant( 2039): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2039): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  960): handleMessage: E msg.what=147460
D/WifiStateMachine(  960): processMsg: DisconnectingState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): Network connection lost
D/WifiStateMachine(  960): Stopping DHCP and clearing IP
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  960): doBoolean: SET ps 1
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2039): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2039): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2039): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/DhcpStateMachine(  960): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  270): Clearing all IP addresses on wlan0
D/WifiStateMachine(  960): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  960): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  960): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/WifiHS20(  960): hidePasspointNotification off =false
D/QcConnectivityService(  960): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
D/QCNEA   (  470): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  470): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  470): |CAC| updateNetCfgInfo
V/QCNEA   (  470): |CAC| *********************************************
V/QCNEA   (  470): |CAC|                   Netconfig               
V/QCNEA   (  470): |CAC| *********************************************
V/QCNEA   (  470): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  470): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  470): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  470): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  470): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  470): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  470): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  470): |CAC| *********************************************
D/QCNEA   (  470): |CAC| Received bssid= 
D/QCNEA   (  470): |CAC| net type = 3
V/QCNEA   (  470): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  470): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  470): |CAC| 	ssid           =NG700
V/QCNEA   (  470): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  470): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  470): |CAC| *********************************************
D/QCNEA   (  470): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  470): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  470): |CAC| dispatchNetCfg: updating:0xb7c128dc
D/QCNEA   (  470): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  960): Attempting to switch to mobile
D/QcConnectivityService(  960): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  960): handleConnectivityChange: preConnState=1 connState=2
I/ActivityManager(  960): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4720 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  960): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  960): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  270): RouteController
V/        (  270): RouteController
V/        (  270): RouteController
D/HyLog   ( 4720): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4720): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4720): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  270): RouteController
V/        (  270): RouteController
I/PCSuite ( 4720): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
V/        (  270): RouteController
V/        (  270): RouteController
V/        (  270): RouteController
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/PCSuite ( 4720): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4720): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/NetworkManagementService(  960): route cmd failed: 
W/NetworkManagementService(  960): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  960): '
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  960): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  960): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  960): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  960): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  960): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  960): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/NetUtils(  960): android_net_utils_resetConnections in env=0x6287e860 clazz=0x6d200001 iface=wlan0 mask=0x3
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.443253 Y: -0.423325 Z: 9.778290 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443253 .y:-0.423325 .z:9.778290
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
V/NativeCrypto( 1545): Read error: ssl=0x639b5918: I/O error during system call, Connection timed out
V/NativeCrypto( 1545): SSL shutdown failed: ssl=0x639b5918: I/O error during system call, Broken pipe
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QcConnectivityService(  960): resetConnections(wlan0, 3)
I/ActivityManager(  960): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4754 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  960): Killing 4126:com.google.android.talk/u0a77 (adj 15): empty #17
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/HyLog   ( 4754): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4754): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4754): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=false
D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
D/GpsLocationProvider(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
D/QRemote ( 4754): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  960): Killing 2145:android.process.media/u0a23 (adj 15): empty #17
D/QRemote ( 4754): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4754): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4754): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4754): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4754): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4754): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
D/QRemote ( 4754): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.435577 Y: -0.422455 Z: 9.784790 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.435577 .y:-0.422455 .z:9.784790
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
I/QRemote ( 4754): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  960): Killing 3875:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
D/DhcpStateMachine(  960): StoppedState
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/GAV2    ( 4596): Thread[GAThread,5,main]: No campaign data found.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1545): onDestroy
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): handleMessage: X
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  960): battery changed pluggedType: 2
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/WifiController(  960): battery changed pluggedType: 2
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3983): onReceive
,D/AppUp4:CustFacade( 3983): Context : android.app.ReceiverRestrictedContext@42e36eb0
D/AppUp4:CustFacade( 3983): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3983): isOpenOperator : true
,D/AppUp4:CustFacade( 3983): isPhone : true
,I/LicenseContentProvider( 2922): start selecting data
,D/SIMObserver( 2922): simInfo1
,I/AppUp4:EulaManager( 3983): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3983): begin check event
,I/AppUp4:CustModeStarterReceiver( 3983): Event For GoodConnectivity
,I/ActivityManager(  960): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4782 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002},
,D/HyLog   ( 4782): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4782): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4782): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2039): nl80211: Event message available
D/wpa_supplicant( 2039): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2039): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2039): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2039): nl80211: Received scan results (14 BSSes)
D/wpa_supplicant( 2039): nl80211: Survey data missing
D/wpa_supplicant( 2039): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 9 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 10 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 11 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 12 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 13 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): BSS: last_scan_res_used=14/32 last_scan_full=0
D/wpa_supplicant( 2039): wlan0: New scan results available
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2039): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2039): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2039): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2039): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2039): WPS: AP 44:e9:dd:10:c0:ac type 0 added
D/wpa_supplicant( 2039): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2039): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2039): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[4] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[5] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[6] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[7] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2039): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2039): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2039): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wp,s
D/wpa_supplicant( 2039): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2039): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2039): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7b025a8  current_ssid=0x0
D/wpa_supplicant( 2039): scard is not null..
D/wpa_supplicant( 2039): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2039): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2039): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2039): wlan0: Cancelling scan request
D/wpa_supplicant( 2039): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2039): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2039): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2039): RSN: PMKSA cache search - network_ctx=0xb7b025a8 try_opportunistic=0
D/wpa_supplicant( 2039): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2039): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2039): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2039): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2039): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2039): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2039): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2039): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2039): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2039): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2039): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2039): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2039): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2039): nl80211: Unsubscribe mgmt frames handle 0xb7b01590 (mode change)
D/wpa_supplicant( 2039): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7b01590
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb7b01590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb7b01590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb7b01590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb7b01590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb7b01590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb7b01590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb7b01590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb7b01590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb7b01590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb7b01590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2039): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2039):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039):   * freq=2412
D/wpa_supplicant( 2039):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2039):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039):   * Auth Type 0
D/wpa_supplicant( 2039):   * WPA Versions 0x2
D/wpa_supplicant( 2039): nl80211: Connect request send successfully
D/wpa_supplicant( 2039): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2039): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 06:7c:34:38:27:cc]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 44:e9:dd:10:c0:ac]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 64:7c:34:38:27:cc]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 10:9a:dd:8e:22:d9]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 44:e9:dd:10:c0:ad]
D/WifiStateMachine(  960): handleMessage: E msg.what=147461
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  960): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2039): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  960): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
,D/wpa_supplicant( 2039): nl80211: Event message available
D/wpa_supplicant( 2039): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2039): nl80211: Connect event
D/wpa_supplicant( 2039): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2039): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2039): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2039): wlan0: Association info event
D/wpa_supplicant( 2039): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2039): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2039): wlan0: freq=2412 MHz
D/wpa_supplicant( 2039): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2039): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2039): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2039): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2039): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/wpa_supplicant( 2039): scard is not null..
D/wpa_supplicant( 2039): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2039): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2039): TDLS: Remove peers on association
D/wpa_supplicant( 2039): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=CONNECTING
D/wpa_supplicant( 2039): EAPOL: External notification - portValid=0
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiStateMachine(  960): handleMessage: X
D/wpa_supplicant( 2039): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2039): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2039): EAPOL: enable timer tick
D/wpa_supplicant( 2039): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2039): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2039): wlan0: Cancelling scan request
D/wpa_supplicant( 2039): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  960): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
V/DownloadManager( 4782): DownloadService onCreate
D/EAS     ( 4576): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 4782): in removeSpuriousFiles
,D/EAS     ( 4576): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4576): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4782): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e5f690 on behalf of 4782
,V/DownloadManager( 4782): DownloadService onStartCommand
,V/DownloadManager( 4782): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4782): in trimDatabase
V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e62088 on behalf of 4782
,V/DownloadManager( 4782): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/wpa_supplicant( 2039): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 6b e2 ad 79 0f 8d c0 a9 c8 58 06 f7 6f 46 0b ...
D/wpa_supplicant( 2039): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2039): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2039): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2039): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2039): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2039):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2039):   key_nonce - hexdump(len=32): 6b e2 ad 79 0f 8d c0 a9 c8 58 06 f7 6f 46 0b 1c 58 c8 a0 62 99 27 ca ab 20 2e 16 4e 2b fb c5 32
D/wpa_supplicant( 2039):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 6b e2 ad 79 0f 8d c0 a9 c8 58 06 f7 6f 46 0b ...
D/wpa_supplicant( 2039): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2039): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2039): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2039): WPA: Renewed SNonce - hexdump(len=32): b0 82 24 f9 5a eb 6e ab bb 18 df d6 ed 6a c9 4d db 61 ca b2 79 3e 14 27 b5 45 af 6d db 94 4e ad
D/wpa_supplicant( 2039): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): WPA: Nonce1 - hexdump(len=32): b0 82 24 f9 5a eb 6e ab bb 18 df d6 ed 6a c9 4d db 61 ca b2 79 3e 14 27 b5 45 af 6d db 94 4e ad
D/wpa_supplicant( 2039): WPA: Nonce2 - hexdump(len=32): 6b e2 ad 79 0f 8d c0 a9 c8 58 06 f7 6f 46 0b 1c 58 c8 a0 62 99 27 ca ab 20 2e 16 4e 2b fb c5 32
D/wpa_supplicant( 2039): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2039): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2039): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2039): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2039): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2039): WPA: Derived Key MIC - hexdump(len=16): 97 47 2d ad 3f 8b b2 b4 5d 13 3a 24 51 65 39 b8
D/wpa_supplicant( 2039): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 b0 82 24 f9 5a eb 6e ab bb 18 df d6 ed 6a c9 ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
,V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e63540 on behalf of 4782
I/LgeMiscReceiver( 4301): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4301): action = android.net.conn.CONNECTIVITY_CHANGE
W/linker  ( 4576): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/LgeMiscReceiver( 4301): networkInfo.isConnected() = false
D/HtmlEditor( 4576): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4576): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4576): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
D/wpa_supplicant( 2039): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 6b e2 ad 79 0f 8d c0 a9 c8 58 06 f7 6f 46 0b ...
D/wpa_supplicant( 2039): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2039): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2039): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2039): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2039):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2039):   key_nonce - hexdump(len=32): 6b e2 ad 79 0f 8d c0 a9 c8 58 06 f7 6f 46 0b 1c 58 c8 a0 62 99 27 ca ab 20 2e 16 4e 2b fb c5 32
D/wpa_supplicant( 2039):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_rsc - hexdump(len=8): 95 2b 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_mic - hexdump(len=16): f4 f0 29 0a 3e ca 42 70 e9 e7 6e 89 45 1c 36 a6
D/wpa_supplicant( 2039): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 6b e2 ad 79 0f 8d c0 a9 c8 58 06 f7 6f 46 0b ...
D/wpa_supplicant( 2039): RSN: encrypted key data - hexdump(len=56): dc e3 47 b3 6b fc 75 35 1f 68 9a d2 4b 72 6d 75 9b 0f 0d 3d 28 84 37 ec c1 be 8c 5e 21 98 ee 67 ...
D/wpa_supplicant( 2039): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2039): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2039): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2039): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 28 ef ...
D/wpa_supplicant( 2039): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2039): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2039): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2039): WPA: Derived Key MIC - hexdump(len=16): 4b d9 e7 d4 53 d8 40 b8 76 9f cf 22 27 61 10 5c
D/wpa_supplicant( 2039): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2039): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7b01c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2039):    addr=c0:ff:d4:d3:aa:48
,I/dalvikvm( 4576): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/wpa_supplicant( 2039): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2039): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/HtmlEditor( 4576): register_HtmlEditor, Success
D/wpa_supplicant( 2039): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/HtmlEditor( 4576): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/wpa_supplicant( 2039): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2039): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2039): WPA: RSC - hexdump(len=6): 95 2b 00 00 00 00
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f7803a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2039):    broadcast key
D/HtmlEditor( 4576): register_HtmlEditorTimer, Success
D/HtmlEditor( 4576): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/HtmlEditor( 4576): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4576): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4576): register_HtmlEditorFont, Success
D/HtmlEditor( 4576): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
,D/HtmlEditor( 4576): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4576): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
I/wpa_supplicant( 2039): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2039): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2039): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2039): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2039): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2039): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 2039): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2039): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2039): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2039): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2039): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,W/WifiMonitor(  960): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2039): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2039): EAPOL authentication completed successfully
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/HtmlEditor( 4576): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4576): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4576): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4576): JNI_OnLoad Success
I/HubEmail( 4576): JNI_OnLoad()
,I/HubEmail( 4576): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4576): registerNatives()
I/HubEmail( 4576): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4576): registerNativeMethods()
,I/HubEmail( 4576): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4818 uid=10052 gids={50052, 3003}
D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): Network connection established
D/WifiNative-wlan0(  960): doString: STATUS
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2039): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  960):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  960): ssid=NG700
D/WifiNative-wlan0(  960): id=0
D/WifiNative-wlan0(  960): mode=station
D/WifiNative-wlan0(  960): pairwise_cipher=CCMP
D/WifiNative-wlan0(  960): group_cipher=CCMP
D/WifiNative-wlan0(  960): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  960): wpa_state=COMPLETED
D/WifiNative-wlan0(  960): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  960): address=34:fc:ef:de:0a:e2
V/DownloadManager( 4782): DownloadService onDestroy
I/WifiServiceExtension(  960): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  960): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  960): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  960): moveTempStackToStateStack: i=1,j=5
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  960): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ObtainingIpState
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
D/DhcpStateMachine(  960): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  960): WaitBeforeStartState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-18ms what=147462 obj=android.net.wifi.StateChangeResult@441c7210 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: ,X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-6ms what=147462 obj=android.net.wifi.StateChangeResult@441c8598 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-6ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  960): ObtainingIpState{ when=-1ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2039): nl80211: survey data missing!
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196612
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
W/Settings( 4576): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/HyLog   ( 4818): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4818): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4818): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  960): Killing 4278:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
V/LGRssiData( 4818): [loadRssi] File not exist 
V/LGRssiData( 4818): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4818): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4818): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4818): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4818): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4818): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 4818): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/TelephonyAutoProfiling( 4818): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4818): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4818): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 4818): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4818): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4818): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  960): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4833 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  960): Killing 4498:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4833): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4833): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4833): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  960): doBoolean: SET ps 0
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2039): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2039): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2039): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  960): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  960): DHCP Start wake lock is acquired.
,D/CommandListener(  270): Setting iface cfg
,D/CommandListener(  270): Trying to bring up wlan0
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4384e1a0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4384e1a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  960): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196613
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  960): doBoolean: SET ps 1
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2039): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2039): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2039): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): DHCP successful
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  960): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  960): VerifyingLinkState enter
D/WifiStateMachine(  960): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/ActivityManager(  960): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4848 uid=10066 gids={50066, 4002, 3003, 1028}
,D/WifiStateMachine(  960): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  960): send additional Connectivity Action
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
,E/Parcel  (  470): Reading a NULL string not supported here.
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  960): handleMessage: E msg.what=135190
D/WifiStateMachine(  960): processMsg: VerifyingLinkState
D/WifiStateMachine(  960): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  960): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  960): invokeEnterMethods: CaptivePortalCheckState
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
I/ActivityManager(  960): Killing 4533:com.google.android.partnersetup/u0a9 (adj 15): empty #17
W/WifiStateTracker(  960): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  960): 
W/WifiStateTracker(  960):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  960):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  960): CaptivePortalCheckState enter
D/WifiStateMachine(  960): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  960): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  960): handleMessage: E msg.what=131092
D/WifiStateMachine(  960): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  960): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiStateMachine(  960): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  960): transitionTo: destState=ConnectedState
D/HyLog   ( 4848): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4848): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4848): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
,E/Parcel  (  470): Reading a NULL string not supported here.
D/QcConnectivityService(  960): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/ActivityThread(  960): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  960): handleConnectivityChange: preConnState=2 connState=1
,V/        (  270): RouteController
,I/ActivityManager(  960): Killing 4562:com.lge.bnr/1000 (adj 15): empty #17
V/        (  270): RouteController
D/LGDMClient( 2826): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/        (  270): RouteController
V/        (  270): RouteController
D/LGDMClient( 2826): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2826): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2826): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2826): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2826): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/        (  270): RouteController
I/ActivityManager(  960): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4868 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
I/LGDMClient( 2826): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/        (  270): RouteController
V/        (  270): RouteController
V/        (  270): RouteController
,V/        (  270): RouteController
,D/QCNEA   (  470): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  470): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  470): |CAC| updateNetCfgInfo
V/QCNEA   (  470): |CAC| *********************************************
V/QCNEA   (  470): |CAC|                   Netconfig               
V/QCNEA   (  470): |CAC| *********************************************
V/QCNEA   (  470): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  470): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  470): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  470): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  470): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  470): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  470): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  470): |CAC| *********************************************
D/QCNEA   (  470): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  470): |CAC| net type = 1
V/QCNEA   (  470): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  470): |CAC| Received ssid= NG700
V/QCNEA   (  470): |CAC| 	ssid           =NG700
V/QCNEA   (  470): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  470): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  470): |CAC| *********************************************
D/QCNEA   (  470): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  470): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  470): |CAC| dispatchNetCfg: updating:0xb7c128dc
D/QCNEA   (  470): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
,D/DhcpStateMachine(  960): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  960): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  960): GC_EXPLICIT freed 23812K, 49% free 29743K/58004K, paused 2ms+8ms, total 132ms
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 4868): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4868): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4868): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1888): Checking schedule, now: 1452011214890 next: 1452011159775
,I/CheckinService( 1888): active receiver: enabled
,I/CheckinService( 1888): Preparing to send checkin request
,I/EventLogService( 1888): Accumulating logs since 1452011127039
,D/LGDMSGCM( 4868): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  960): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4900 uid=10101 gids={50101, 1028, 1015, 3003}
,D/HyLog   ( 4900): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4900): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4900): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinRequestBuilder( 1888): Checkin reason type: 8 attempt count: 1
,I/NFS     ( 4900): connectivityManager.getNetworkInfo = TYPE_WIFI
E/ActivityThread( 1888): Failed to find provider info for com.google.android.wearable.settings
,I/Wireless_Storage( 4900): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4900): intf.getDisplayName() = lo
I/Wireless_Storage( 4900): intf.getDisplayName() = sit0
I/Wireless_Storage( 4900): intf.getDisplayName() = p2p0
,I/Wireless_Storage( 4900): intf.getDisplayName() = teql0
I/Wireless_Storage( 4900): intf.getDisplayName() = wlan0
D/NFS     ( 4900): interface name:wlan0 name:wlan0
D/NFS     ( 4900): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4900): interface name:wlan0 name:wlan0
D/NFS     ( 4900): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4900): CONNECT : WIFI_CONNECT
,I/ActivityManager(  960): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4912 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  960): Killing 4175:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
,D/HyLog   ( 4912): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4912): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4912): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
,W/GAV2    ( 4912): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x438b9de8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1888): awaiting user notification for token
D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  960): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4951 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4951): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4951): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4951): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  274): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,W/dalvikvm( 4951): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4951): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4951): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
W/dalvikvm( 4951): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4951): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4951): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4951): install
,I/MultiDex( 4951): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,V/WebViewChromium( 4912): Binding Chromium to the main looper Looper (main, tid 1) {42e226b0}
,I/MultiDex( 4951): loading existing secondary dex files
,I/chromium( 4912): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4912): Initializing chromium process, renderers=0
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 15ms
,I/MultiDex( 4951): load found 3 secondary dex files
,I/MultiDex( 4951): install done
,W/chromium( 4912): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/dalvikvm( 4951): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4951): VFY: unable to resolve instance field 61
,D/dalvikvm( 4951): VFY: replacing opcode 0x54 at 0x0054
I/Adreno-EGL( 4912): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4912): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4912): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4912): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4912): Remote Branch: 
I/Adreno-EGL( 4912): Local Patches: 
I/Adreno-EGL( 4912): Reconstruct Branch: 
,D/dalvikvm( 4951): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4951): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4951): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4951): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4951): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4951): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4951): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4951): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
D/dalvikvm( 4951): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e29858
D/dalvikvm( 4951): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e29858
,D/dalvikvm( 4951): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e29858, skipping init
,D/dalvikvm( 4951): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42e29858
D/dalvikvm( 4951): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42e29858
,V/JNIHelp ( 4951): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 4912): Starting up...
,I/ActivityManager(  960): Killing 4190:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
,D/DhcpStateMachine(  960): DHCP succeeded on wlan0
D/dalvikvm( 4951): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e29858
,D/dalvikvm( 4951): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42e29858
D/dalvikvm( 4951): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42e29858
,D/dalvikvm( 4951): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42e29858
D/LgDhcpStateMachineHelper(  960): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  960): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  960): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  960): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  960): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  960): RunningState
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4754): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4754): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4754): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4754): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4754): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4754): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4720): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4720): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4754): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4754): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4754): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4754): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 4951): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1545): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1545): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1545): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1888): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1746): callingUid 10006, callindPid: 1746
,E/MDM     ( 1421): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1888): Restart initialization of location
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/dalvikvm( 4951): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4951): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4951): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4951): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4951): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4951): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e17000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e17000
,D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  276): PrepareKeyRequest: nonce=491522769
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2039): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2039): EAPOL: disable timer tick
,D/dalvikvm( 4951): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42fce998
D/dalvikvm( 4951): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42fce998
,D/dalvikvm( 4951): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42fce998, skipping init
,D/GCM     ( 1545): Connected
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/GCM     ( 1545): Ack for not saved message 147
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1545): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  960): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 4951): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4951): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4993): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4951): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4951): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 68ms
,I/Adreno-EGL( 4951): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4951): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4951): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4951): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4951): Remote Branch: 
I/Adreno-EGL( 4951): Local Patches: 
I/Adreno-EGL( 4951): Reconstruct Branch: 
,I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=1293928265
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WifiStateMachine(  960): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): handleMessage: X
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  960): send additional Connectivity Action
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
,D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  960): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  960):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  960): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4951): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4951): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4951): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4951): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4951): Remote Branch: 
I/Adreno-EGL( 4951): Local Patches: 
I/Adreno-EGL( 4951): Reconstruct Branch: 
,I/Adreno-EGL( 4951): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4951): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4951): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4951): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4951): Remote Branch: 
I/Adreno-EGL( 4951): Local Patches: 
I/Adreno-EGL( 4951): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1888): Classify the device as Phone.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1888): Sending checkin request (11468 bytes)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1888): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1888): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x44220f60: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1888): awaiting user notification for token
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1888): Classify the device as Phone.
,I/CheckinTask( 1888): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1888): Checking schedule, now: 1452011217167 next: 1452588613164
,I/CheckinService( 1888): active receiver: disabled
,D/GCM     ( 1545): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  470): Reading a NULL string not supported here.
,E/Parcel  (  470): Reading a NULL string not supported here.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3983): onReceive
D/AppUp4:CustFacade( 3983): Context : android.app.ReceiverRestrictedContext@42e36eb0
,D/AppUp4:CustFacade( 3983): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3983): isOpenOperator : true
D/AppUp4:CustFacade( 3983): isPhone : true
,I/LicenseContentProvider( 2922): start selecting data
,D/SIMObserver( 2922): simInfo1
,I/AppUp4:EulaManager( 3983): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3983): begin check event
I/AppUp4:CustModeStarterReceiver( 3983): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 3983): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 3983): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3983): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3983): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3983): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4576): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4782): DownloadService onCreate
,D/EAS     ( 4576): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4576): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4782): in removeSpuriousFiles
,V/DownloadManager( 4782): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e69428 on behalf of 4782
,I/DownloadManager( 4782): in trimDatabase
,V/DownloadManager( 4782): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e6a4f8 on behalf of 4782
,I/LgeMiscReceiver( 4301): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4301): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4301): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4818): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4818): onReceive CONNECTIVITY_CHANGE networkType=1
,I/jxcore-log( 4650): Test app app.js loaded
I/jxcore-log( 4650): 
,D/LGDMClient( 2826): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/LGDMSGCM( 4868): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2826): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2826): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Tethering(  960): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 4576): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NFS     ( 4900): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4900): CONNECT : WIFI_CONNECT
V/DownloadManager( 4782): DownloadService onStartCommand
V/DownloadManager( 4782): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/chromium( 4650): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e6cf90 on behalf of 4782
E/LGDMClient( 2826): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2826): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2826): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/LGDMClient( 2826): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 4782): DownloadService onDestroy
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3983): onReceive
D/AppUp4:CustFacade( 3983): Context : android.app.ReceiverRestrictedContext@42e36eb0
D/AppUp4:CustFacade( 3983): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3983): isOpenOperator : true
,D/AppUp4:CustFacade( 3983): isPhone : true
,I/LicenseContentProvider( 2922): start selecting data
,D/SIMObserver( 2922): simInfo1
,I/AppUp4:EulaManager( 3983): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3983): begin check event
,I/AppUp4:CustModeStarterReceiver( 3983): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4782): DownloadService onCreate
D/EAS     ( 4576): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4576): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4782): in removeSpuriousFiles
,V/DownloadManager( 4782): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e71218 on behalf of 4782
I/LgeMiscReceiver( 4301): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4301): action = android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4782): DownloadService onStartCommand
I/LgeMiscReceiver( 4301): networkInfo.isConnected() = true
D/PhoneState( 4301): setPdpRejectCasuse : false
V/DownloadManager( 4782): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/Settings( 4576): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e73cf0 on behalf of 4782
,I/DownloadManager( 4782): in trimDatabase
,D/MobileConnectivityChangeReceiver( 4818): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4818): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4782): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4782): DownloadService onDestroy
,V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e757d8 on behalf of 4782
,D/LGDMClient( 2826): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2826): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4868): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2826): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4900): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4900): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2826): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2826): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2826): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2826): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3983): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3983): onReceive
,D/AppUp4:CustFacade( 3983): Context : android.app.ReceiverRestrictedContext@42e36eb0
,D/AppUp4:CustFacade( 3983): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3983): isOpenOperator : true
,D/AppUp4:CustFacade( 3983): isPhone : true
,I/LicenseContentProvider( 2922): start selecting data
,D/SIMObserver( 2922): simInfo1
,I/AppUp4:EulaManager( 3983): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3983): begin check event
,I/AppUp4:CustModeStarterReceiver( 3983): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4576): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4782): DownloadService onCreate
,D/EAS     ( 4576): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4301): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4301): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4301): networkInfo.isConnected() = true
,D/PhoneState( 4301): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4818): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4818): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 4782): in removeSpuriousFiles
,V/DownloadManager( 4782): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e78f48 on behalf of 4782
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGDMClient( 2826): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 4576): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DownloadManager( 4782): in trimDatabase
V/DownloadManager( 4782): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMSGCM( 4868): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2826): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/LGDMClient( 2826): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/dalvikvm(  960): GC_EXPLICIT freed 2120K, 49% free 29661K/58004K, paused 4ms+6ms, total 87ms
,V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e7adb8 on behalf of 4782
,E/LGDMClient( 2826): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 4782): DownloadService onStartCommand
,V/DownloadManager( 4782): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2826): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e7cbe0 on behalf of 4782
,D/LGDMClient( 2826): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/NFS     ( 4900): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4900): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2826): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 4782): DownloadService onDestroy
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  290): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  960): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011220034, nextTick: 59998, mDrawingTime: 0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011220045, nextTick: 59987, mDrawingTime: 0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4912): Thread[GAThread,5,main]: No campaign data found.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  960): Killing 4207:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  960): Killing 4596:com.google.android.apps.docs/u0a73 (adj 15): empty #18
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  960): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5127 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5127): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5127): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5127): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5127): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5127): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5127): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5127): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5127): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5127): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5127): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5127): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5127): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5127): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5127): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5127): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5127): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5127): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5127): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 5127): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5127): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 5127): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5127): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5127): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5127): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5127): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5127): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 4782): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4782): created cursor android.database.sqlite.SQLiteCursor@42e81e40 on behalf of 5127
,I/dalvikvm( 5127): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5127): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5127): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5127): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5127): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5127): VFY: replacing opcode 0x6e at 0x0049
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/Finsky  ( 5127): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5127): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5127): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5127): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5127): Total arena pages for JIT: 11
,I/dalvikvm( 5127): Total arena pages for JIT: 12
I/dalvikvm( 5127): Total arena pages for JIT: 13
,I/dalvikvm( 5127): Total arena pages for JIT: 14
,D/Finsky  ( 5127): [459] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5127): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  960): Killing 4720:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5127): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5127): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5127): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5127): VFY: replacing opcode 0x62 at 0x0037
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Finsky  ( 5127): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1545): GC_EXPLICIT freed 1168K, 29% free 17822K/24832K, paused 2ms+4ms, total 31ms
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5127): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5127): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5127): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5127): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5127): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1421): client connected with version: 7571000
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.455276 Y: -0.424545 Z: 9.776611 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455276 .y:-0.424545 .z:9.776611
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.457565 Y: -0.415466 Z: 9.784897 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457565 .y:-0.415466 .z:9.784897
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3698): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1486): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1486): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1486): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 3698): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  960): Handling package changes for user 0
,I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5221 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher( 1486): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5221): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5221): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5221): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/WifiController(  960): battery changed pluggedType: 2
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5221): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5221): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5221): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5221): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5221): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/Babel   ( 5221): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 5221): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5221): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5221): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5221): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5221): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5221): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 5221): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5221): MmsConfig.loadFromResources
,E/Babel   ( 5221): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5221): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5221): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[LGHome]EVENT( 1486): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/GmsNetworkLocationProvi( 1421): DISABLE
,V/LGRssiData( 5221): [loadRssi] File not exist 
V/LGRssiData( 5221): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5221): [loadFeatureFromXml] *** start feature loading from xml
,I/GCoreNlp( 1421): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
V/TelephonyAutoProfiling( 5221): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5221): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5221): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 3983): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3983): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3983): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3983): onReceive
,D/AppUp4:CustFacade( 3983): Context : android.app.ReceiverRestrictedContext@42e36eb0
D/AppUp4:CustFacade( 3983): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3983): isOpenOperator : true
,D/AppUp4:CustFacade( 3983): isPhone : true
,I/LicenseContentProvider( 2922): start selecting data
,D/SIMObserver( 2922): simInfo1
,I/AppUp4:EulaManager( 3983): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3983): begin check event
D/AppUp4:Utils( 3983): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3983): Event For Nothing, skip.
,D/LocationProviderProxy(  960): applying state to connected service
,D/LocationProviderProxy(  960): applying state to connected service
I/ActivityManager(  960): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5268 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5268): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5268): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5268): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5268): BUILD Country: EU
,I/SystemConfig( 5268): BUILD Operator: OPEN
I/SystemConfig( 5268): systemFeature RCS result false
,D/SystemConfig( 5268): refreshRcsSupport() :false
I/ActivityManager(  960): Killing 4754:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  960): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5283 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5283): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5283): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5283): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  960): Killing 4576:com.lge.email/u0a24 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  960): Killing 4818:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/IcingCorporaProvider( 2662): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1888): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1888): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  960): Delaying start of: ServiceRecord{4416fcc0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,D/dalvikvm( 1888): GC_CONCURRENT freed 1882K, 22% free 19548K/24832K, paused 3ms+2ms, total 32ms
,I/Icing   ( 1888): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2662): UpdateCorporaTask done [took 215 ms] updated apps [took 215 ms] 
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  960): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
D/HeadsetStateMachine( 1213): Disconnected process message: 10
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-15ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  960): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  960): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  960): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  960): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  960): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm(  960): GC_EXPLICIT freed 1966K, 49% free 29863K/58004K, paused 25ms+20ms, total 246ms
,I/GAV4    ( 5221): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,I/PowerManagerService(  960): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  960): [updateScreenState] screen on = false
D/KnockOnPowerController(  960): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  960): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  960): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,D/KnockOnPowerController(  960): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  960): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  960): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  960): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8455 usec
,D/qcom_sensors_hal(  960): hal_acquire_resources
,I/qcom_sensors_hal(  960): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  960): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  960): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  960): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  960): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  960): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  960): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.435562 Y: -0.423859 Z: 9.790894 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.435562 .y:-0.423859 .z:9.790894
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.443008 Y: -0.433960 Z: 9.790588 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443008 .y:-0.433960 .z:9.790588
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,I/Sensors (  415): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  960): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  960): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  960): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  960): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  960): proximitySensorChanged  positive = true
I/KnockOnPowerController(  960): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.444992 Y: -0.432327 Z: 9.785324 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444992 .y:-0.432327 .z:9.785324
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.441132 Y: -0.424408 Z: 9.784439 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441132 .y:-0.424408 .z:9.784439
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.445267 Y: -0.426208 Z: 9.801483 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445267 .y:-0.426208 .z:9.801483
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.446320 Y: -0.424255 Z: 9.821671 
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.442993 Y: -0.444275 Z: 9.763824 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.446320 .y:-0.424255 .z:9.821671
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  960): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@441c8df8)
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1140): notifyScreenOnLocked
,D/KeyguardViewMediator( 1140): handleNotifyScreenOn
,D/KeyguardViewManager( 1140): onScreenTurnedOn()
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,V/KeyguardServiceDelegate(  960): **** SHOWN CALLED ****
I/WindowManager(  960): No lock screen! windowToken=null
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.450043 Y: -0.414413 Z: 9.819290 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450043 .y:-0.414413 .z:9.819290
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  273): Screen released, type=0 flinger=0xb8541450
,D/qdhwcomposer(  273): hwc_blank: Blanking display: 0
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,E/SlideAside( 3698): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WifiStateMachine(  960): handleScreenStateChanged: true
D/WifiStateMachine(  960): handleMessage: E msg.what=131154
D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  960): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131127
D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=131158
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=132097
D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  960): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2039): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2039): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  960): stopMonitoring
,E/AudioSystem(  960): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 960
V/SRS_Proc(  276): ParamSet string: screen_state=on
,D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{438fc9f8 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1819): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 17:27:17
,I/SlideAside( 3698): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1819): 2 : This is isUpdating : false
D/WeatherAncestor( 1819): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 17:27:17
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1819): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1819): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
D/WeatherService( 1819): 2 : shouldTimeTickRegistered : false
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
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 249, B = 249
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/qdlights( 1154): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 243, B = 243
D/WifiController(  960): battery changed pluggedType: 2
,D/qdlights( 1154): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1154): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1154): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 225, B = 225
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.448166 Y: -0.410919 Z: 9.790161 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448166 .y:-0.410919 .z:9.790161
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/qdlights( 1154): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  273): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  960): Excessive delay in blankDisplay() while turning screen off: 401ms
D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011237434, nextTick: 42598, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.446152 Y: -0.414978 Z: 9.797958 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446152 .y:-0.414978 .z:9.797958
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011237455, nextTick: 42578, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
D/WeatherService( 1819): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:27:17
D/WeatherService( 1819): 2 : ACTION screen on
,D/WeatherService( 1819): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1819): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:27:17
,D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
,E/Parcel  (  470): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/PhoneApp( 1446): Action intent recieved:android.intent.action.SCREEN_ON
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1446): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1446): Emergency Service
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1446): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_gfit, value : null
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_ON
D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  960): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  960): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
,V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3}
D/qcom_sensors_hal(  960): hal_acquire_resources
D/qcom_sensors_hal(  960): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  960): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  960): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  960): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  960): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/UsbSettings( 2594): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,V/ActivityManager(  960): Moving to DESTROYING: ActivityRecord{4362f1a0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
I/LGImmersionVibrator(  960): Vibrator off
V/UsbSettings( 2594): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2594): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2594): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
,D/WifiStateMachine(  960): handleScreenStateChanged: false
D/WifiStateMachine(  960): handleMessage: E msg.what=131154
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131158
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  960): doBoolean: DRIVER SETSUSPENDMODE 1
V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{43f1f5d0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  960): CMD_SCREEN_OFF 
,D/WifiController(  960): shouldWifiStayAwake TRUE
E/AudioSystem(  960): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 960
V/SRS_Proc(  276): ParamSet string: screen_state=off
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{4362f1a0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1154): clear
,D/KeyguardViewMediator( 1140): handleNotifyScreenOff
D/KeyguardViewManager( 1140): onScreenTurnedOff()
D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  960):    returned true
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=2
,D/WifiStateMachine(  960): handleMessage: X
D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
,I/[LGHome]EVENT( 1486): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
,D/WeatherService( 1819): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:27:17
D/WeatherService( 1819): 2 : ACTION screen off
,D/WeatherService( 1819): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:27:17
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
E/Parcel  (  470): Reading a NULL string not supported here.
,E/Parcel  (  470): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1446): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1446): Emergency Service
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1446): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
,V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_smart_dialing, value : null
D/NfcService( 1471): NFC-C OFF
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1446): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_OFF
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1459): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1154): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1154): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1154): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1154): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1154): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1154): set_light_notifications: 2,ff003939,10,0,2
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
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  415): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
,E/ThermalEngine(  290): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1446): getIsInUseVoLTE : false
,D/PhoneApp( 1446): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1545): Vacuum at: now=1452011246568 tag=VacuumService
,I/GoogleURLConnFactory( 1545): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1545): No account for auth token provided
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/Finsky  ( 5127): [459] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5127): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1545): No account for auth token provided
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1545):  no longer exists, so no auth token.
,W/Uploader( 1545): No account for auth token provided
,W/Uploader( 1545): No account for auth token provided
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011255335334325; DSPS: 5279990; Offset: 1452011094202827001
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011275337046505; DSPS: 5935406; Offset: 1452011094202830197
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011280046, nextTick: 59978, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011280053, nextTick: 59976, mDrawingTime: 1
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011295338096237; DSPS: 6590800; Offset: 1452011094202842331
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011315339074772; DSPS: 7246192; Offset: 1452011094202844304
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011335340675961; DSPS: 7901605; Offset: 1452011094202828061
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011340050, nextTick: 59977, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011340056, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011355342289808; DSPS: 8557018; Offset: 1452011094202824476
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011375344127717; DSPS: 9212438; Offset: 1452011094202831331
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011395345709792; DSPS: 9867850; Offset: 1452011094202826492
,D/wpa_supplicant( 2039): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 7 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 9 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 10 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 11 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 12 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 8 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 13 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 06:7c:34:12:7f:81]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 06:7c:34:38:27:cc]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 44:e9:dd:10:c0:ac]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 64:7c:34:38:27:cc]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 10:9a:dd:8e:22:d9]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 44:e9:dd:10:c0:ab]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 44:e9:dd:10:c0:ad]
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011400036, nextTick: 59963, mDrawingTime: 12
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011400059, nextTick: 59972, mDrawingTime: 1
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011415347532649; DSPS: 10523269; Offset: 1452011094202848812
,D/dalvikvm( 2648): GC_CONCURRENT freed 7866K, 33% free 16760K/24832K, paused 3ms+1ms, total 40ms
,D/dalvikvm( 2648): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011435349624465; DSPS: 11178698; Offset: 1452011094202834915
,I/LocationManagerService(  960): remove 43909cd0
,D/LocationManagerService(  960): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  960): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  960): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  960): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  960): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2648): GC_CONCURRENT freed 1713K, 32% free 17054K/24832K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 2648): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 2648): GC_FOR_ALLOC freed 1498K, 31% free 17266K/24832K, paused 22ms, total 23ms
,I/Mlt MonitorService( 2648): parseLastkmsg to dump
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011455351198676; DSPS: 11834109; Offset: 1452011094202852729
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011460028, nextTick: 59966, mDrawingTime: 17
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011460064, nextTick: 59967, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011475352980700; DSPS: 12489528; Offset: 1452011094202834216
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011495354640796; DSPS: 13144942; Offset: 1452011094202846363
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011515356381361; DSPS: 13800359; Offset: 1452011094202847426
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011520017, nextTick: 60000, mDrawingTime: 11
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011520070, nextTick: 59961, mDrawingTime: 1
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x4384d648: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1545): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1545): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1545): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1545): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1545): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5127): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5127): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5127): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5127): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5127): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5127): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5127): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5127): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1545): GC_CONCURRENT freed 1646K, 27% free 18194K/24832K, paused 3ms+4ms, total 97ms
,W/System  ( 5127): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5127): isDataSchedulerEnabled():false
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011535358658646; DSPS: 14455794; Offset: 1452011094202835893
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011555360280252; DSPS: 15111207; Offset: 1452011094202840067
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011575361841183; DSPS: 15766618; Offset: 1452011094202844601
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011580039, nextTick: 59956, mDrawingTime: 16
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011580062, nextTick: 59971, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011595363600706; DSPS: 16422036; Offset: 1452011094202834105
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011615365357260; DSPS: 17077453; Offset: 1452011094202851157
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011635367090951; DSPS: 17732870; Offset: 1452011094202845346
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011640018, nextTick: 60001, mDrawingTime: 10
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011640066, nextTick: 59967, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011655368747298; DSPS: 18388284; Offset: 1452011094202853744
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011675370489424; DSPS: 19043702; Offset: 1452011094202825850
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011695372375303; DSPS: 19699123; Offset: 1452011094202850157
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011700041, nextTick: 59981, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011700046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011715373977795; DSPS: 20354536; Offset: 1452011094202835217
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011735375760288; DSPS: 21009954; Offset: 1452011094202847691
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011755377323457; DSPS: 21665366; Offset: 1452011094202823946
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011760040, nextTick: 59985, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011760043, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011775379247512; DSPS: 22320788; Offset: 1452011094202855911
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011795380833390; DSPS: 22976200; Offset: 1452011094202854875
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011815382638226; DSPS: 23631620; Offset: 1452011094202828656
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011820033, nextTick: 59957, mDrawingTime: 16
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011820060, nextTick: 59971, mDrawingTime: 1
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/WifiController(  960): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 268 plugged : true isCharging : false
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011835384250041; DSPS: 24287032; Offset: 1452011094202853557
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011855385892273; DSPS: 24942446; Offset: 1452011094202847840
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011875388320756; DSPS: 25597886; Offset: 1452011094202834917
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011880018, nextTick: 59997, mDrawingTime: 11
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011880064, nextTick: 59967, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011895389980175; DSPS: 26253300; Offset: 1452011094202846386
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011915391613657; DSPS: 26908714; Offset: 1452011094202831919
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  960): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  960): Done.
,D/QcConnectivityService(  960): Setting timer for 720seconds
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011935393503180; DSPS: 27564136; Offset: 1452011094202829352
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011940043, nextTick: 59968, mDrawingTime: 11
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452011940054, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011955395110881; DSPS: 28219548; Offset: 1452011094202850139
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011975396679311; DSPS: 28874960; Offset: 1452011094202831655
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452011995398610866; DSPS: 29530383; Offset: 1452011094202840603
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012000041, nextTick: 59978, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012000048, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012015400451119; DSPS: 30185803; Offset: 1452011094202849801
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012035402197413; DSPS: 30841221; Offset: 1452011094202826076
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012055404042197; DSPS: 31496641; Offset: 1452011094202839805
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012060045, nextTick: 59975, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012060053, nextTick: 59975, mDrawingTime: 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012075405647189; DSPS: 32152054; Offset: 1452011094202827365
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012095407493067; DSPS: 32807474; Offset: 1452011094202842189
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012115409241966; DSPS: 33462891; Offset: 1452011094202851586
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012120041, nextTick: 59981, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012120048, nextTick: 59980, mDrawingTime: 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012135411156229; DSPS: 34118314; Offset: 1452011094202843241
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012155412852107; DSPS: 34773730; Offset: 1452011094202830135
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012175414517360; DSPS: 35429144; Offset: 1452011094202847439
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012180049, nextTick: 59974, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012180055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012195416435320; DSPS: 36084567; Offset: 1452011094202842791
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012215418396146; DSPS: 36739991; Offset: 1452011094202850492
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012235419653327; DSPS: 37395393; Offset: 1452011094202825935
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012240043, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012240050, nextTick: 59978, mDrawingTime: 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012255421217277; DSPS: 38050804; Offset: 1452011094202833488
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012275423128259; DSPS: 38706226; Offset: 1452011094202852381
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012295424710960; DSPS: 39361638; Offset: 1452011094202848168
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012300042, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012300046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012315426306056; DSPS: 40017051; Offset: 1452011094202825832
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012335428733341; DSPS: 40672490; Offset: 1452011094202842228
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012355430337864; DSPS: 41327903; Offset: 1452011094202829320
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012360031, nextTick: 59981, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012360045, nextTick: 59980, mDrawingTime: 3
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012375432231762; DSPS: 41983325; Offset: 1452011094202831128
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012395434028005; DSPS: 42638744; Offset: 1452011094202826834
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012415435629716; DSPS: 43294156; Offset: 1452011094202841631
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012420044, nextTick: 59966, mDrawingTime: 10
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012420058, nextTick: 59972, mDrawingTime: 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012435436947000; DSPS: 43949559; Offset: 1452011094202846659
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012455438672670; DSPS: 44604976; Offset: 1452011094202832827
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012475440289537; DSPS: 45260389; Offset: 1452011094202832262
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012480023, nextTick: 59999, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012480066, nextTick: 59966, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012495441928696; DSPS: 45915802; Offset: 1452011094202853989
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012515443923897; DSPS: 46571228; Offset: 1452011094202835030
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012535445226805; DSPS: 47226631; Offset: 1452011094202825682
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012540060, nextTick: 59965, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012540064, nextTick: 59967, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012555446957371; DSPS: 47882047; Offset: 1452011094202847264
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012575449473405; DSPS: 48537490; Offset: 1452011094202830339
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012595451265324; DSPS: 49192909; Offset: 1452011094202821721
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012600063, nextTick: 59963, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012600067, nextTick: 59964, mDrawingTime: 1
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012615453001046; DSPS: 49848325; Offset: 1452011094202848459
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012635454347236; DSPS: 50503729; Offset: 1452011094202851875
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  960): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  960): Done.
,D/GCM     ( 1545): Message class com.google.f.a.a.i
,D/QcConnectivityService(  960): Setting timer for 720seconds
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/EventLogService( 1888): Aggregate from 1452011214914 (log), 1452010450422 (data)
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012655456240354; DSPS: 51159151; Offset: 1452011094202852903
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012660032, nextTick: 59975, mDrawingTime: 10
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012660048, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012675458649721; DSPS: 51814590; Offset: 1452011094202851382
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012695460432526; DSPS: 52470009; Offset: 1452011094202833650
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012715462407883; DSPS: 53125433; Offset: 1452011094202855882
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012720047, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012720054, nextTick: 59974, mDrawingTime: 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012735464015010; DSPS: 53780846; Offset: 1452011094202845577
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012755466005107; DSPS: 54436271; Offset: 1452011094202852031
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012775467845308; DSPS: 55091692; Offset: 1452011094202830660
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012780042, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012780045, nextTick: 59983, mDrawingTime: 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012795469827852; DSPS: 55747117; Offset: 1452011094202829561
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012815471386283; DSPS: 56402528; Offset: 1452011094202831596
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012835473286900; DSPS: 57057950; Offset: 1452011094202840123
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012840028, nextTick: 59992, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012840059, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012855475052464; DSPS: 57713368; Offset: 1452011094202835668
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012875476774697; DSPS: 58368784; Offset: 1452011094202848916
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012895478437346; DSPS: 59024199; Offset: 1452011094202833098
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012900034, nextTick: 59968, mDrawingTime: 12
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012900054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012915480027806; DSPS: 59679611; Offset: 1452011094202836644
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012935481616341; DSPS: 60335023; Offset: 1452011094202838265
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012955482914718; DSPS: 60990426; Offset: 1452011094202824386
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012960028, nextTick: 59995, mDrawingTime: 7
,I/ProcessStatsService(  960): Prepared write state in 55ms
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452012960086, nextTick: 59947, mDrawingTime: 0
,I/ProcessStatsService(  960): Pruning old procstats: /data/system/procstats/state-2016-01-05-01-38-35.bin
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012975485002627; DSPS: 61645854; Offset: 1452011094202837100
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452012995486785692; DSPS: 62301272; Offset: 1452011094202850146
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452013015488914071; DSPS: 62956702; Offset: 1452011094202842294
,I/ActivityManager(  960): Killing 4951:com.google.android.gms.unstable/u0a6 (adj 15): empty for 1800s
,I/ActivityManager(  960): Killing 4912:com.google.android.apps.magazines/u0a104 (adj 15): empty for 1800s
,I/ActivityManager(  960): Killing 4900:com.lge.wireless_storage/u0a101 (adj 15): empty for 1800s
,I/ActivityManager(  960): Killing 4868:com.lge.lgdmsgcm/1000 (adj 15): empty for 1800s
,I/ActivityManager(  960): Killing 4848:com.lge.drmservice/u0a66 (adj 15): empty for 1800s
,I/ActivityManager(  960): Killing 4833:com.android.chrome/u0a63 (adj 15): empty for 1800s
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452013020072, nextTick: 59953, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452013020076, nextTick: 59953, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{438b09d8 stackId=1, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,TIME-OUT KILL (timeout was 1800000ms)
```
