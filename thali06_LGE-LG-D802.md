#### Test 55613145b105d0b_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
D/dalvikvm( 1525): GC_EXPLICIT freed 993K, 29% free 17837K/24832K, paused 1ms+3ms, total 23ms
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1152): usb Uevent not necessary.
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  958): battery changed pluggedType: 2
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1215): Disconnected process message: 10
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
W/GAV2    ( 4694): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  958): Killing 4006:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 1 tasks}
D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{432fa238 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1854): GC_CONCURRENT freed 1603K, 22% free 19424K/24832K, paused 2ms+3ms, total 29ms
D/dalvikvm( 1854): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 1854): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/ConfigFetchService( 1854): fetch service done; releasing wakelock
I/ConfigFetchService( 1854): stopping self
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4750): 
D/AndroidRuntime( 4750): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4750): CheckJNI is OFF
D/dalvikvm( 4750): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4750): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4750): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4750): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4750): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4750): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1854): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
E/memtrack( 4750): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4750): failed to load memtrack module: -2
D/Icing   ( 1854): Loaded CLD2 Version V2.0 - 20141016
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1854): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4750): Calling main entry com.android.commands.am.Am
I/ActivityManager(  958): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4750
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
D/PermissionCache(  272): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (90 us)
V/ActivityManager(  958): Moving to PAUSING: ActivityRecord{432fa238 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  958): resumeTopActivityLocked: Pausing null
V/ActivityManager(  958): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  958): startService SlideAside
W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  958): setFocusedStack: mFocusedStack=ActivityStack{4389f838 stackId=1, 2 tasks}
D/UsbSettingsControl( 2631): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2631): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4750): Shutting down VM
D/dalvikvm( 4750): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 2ms
D/ActivityManager(  958): allPausedActivitiesComplete: r=ActivityRecord{432fa238 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  958): Moving to PAUSED: ActivityRecord{432fa238 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
D/ActivityManager(  958): resumeTopActivityLocked: Restarting ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 4133): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  958): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4774 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  958): Moving to RESUMED: ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4774): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4774): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4774): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/SlideAside( 4133): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4133): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/WebViewChromium( 4774): Binding Chromium to the background looper Looper (main, tid 1) {42ec25c0}
I/chromium( 4774): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4774): Initializing chromium process, renderers=0
W/chromium( 4774): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4774): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4774): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4774): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4774): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4774): Remote Branch: 
I/Adreno-EGL( 4774): Local Patches: 
I/Adreno-EGL( 4774): Reconstruct Branch: 
I/dalvikvm( 4774): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4774): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4774): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4774): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4774): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4774): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4774): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4774): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4774): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4774): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4774): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4774): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4774): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4774): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4774): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4774): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4774): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4774): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4774): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4774): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4774): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4774): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4774): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4774): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4774): Enabling debug mode 0
W/AwContents( 4774): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  958): IME STATUS OFF
W/AwContents( 4774): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  958): Displayed com.test.thalitest/.MainActivity: +437ms
I/ActivityManager( 4774): Timeline: Activity_idle id: android.os.BinderProxy@42ec3ca0 time:119703
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1152): usb Uevent not necessary.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1215): Disconnected process message: 10
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
D/WifiController(  958): battery changed pluggedType: 2
D/JsMessageQueue( 4774): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4774): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42ec8b38
D/dalvikvm( 4774): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42ec8b38
D/jxcore_app_log( 4774): JniHelper::setJavaVM(0x41e75808), pthread_self() = 1632581448
D/JX-Cordova( 4774): jxcore cordova android initializing
I/ActivityManager(  958): Timeline: Activity_windows_visible id: ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3} time:120035
D/ActivityManager(  958): no-history finish of ActivityRecord{432fa238 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  958): Finishing activity token=Token{4312d648 ActivityRecord{432fa238 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  958): Moving to FINISHING: ActivityRecord{432fa238 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  958): Moving to STOPPING: ActivityRecord{432fa238 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2631): [AUTORUN] onStop()
V/ActivityManager(  958): Moving to STOPPED: ActivityRecord{432fa238 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4774): GC_CONCURRENT freed 2777K, 12% free 21867K/24832K, paused 2ms+1ms, total 41ms
D/dalvikvm( 4774): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 4774): GC_FOR_ALLOC freed 112K, 12% free 21864K/24832K, paused 37ms, total 37ms
D/dalvikvm( 4774): GC_FOR_ALLOC freed 124K, 12% free 21885K/24832K, paused 35ms, total 35ms
I/dalvikvm-heap( 4774): Grow heap (frag case) to 23.636MB for 95956-byte allocation
D/dalvikvm( 4774): GC_FOR_ALLOC freed 178K, 13% free 21919K/24928K, paused 22ms, total 22ms
I/dalvikvm-heap( 4774): Grow heap (frag case) to 23.716MB for 143930-byte allocation
D/dalvikvm( 4774): GC_FOR_ALLOC freed 252K, 13% free 21967K/25072K, paused 21ms, total 21ms
I/dalvikvm-heap( 4774): Grow heap (frag case) to 23.831MB for 215890-byte allocation
D/dalvikvm( 4774): GC_FOR_ALLOC freed 366K, 13% free 22041K/25284K, paused 21ms, total 21ms
I/dalvikvm-heap( 4774): Grow heap (frag case) to 24.006MB for 323830-byte allocation
D/dalvikvm( 4774): GC_FOR_ALLOC freed 563K, 14% free 22161K/25604K, paused 22ms, total 22ms
I/dalvikvm-heap( 4774): Grow heap (frag case) to 24.279MB for 485740-byte allocation
D/dalvikvm( 4774): GC_FOR_ALLOC freed 860K, 15% free 22337K/26080K, paused 35ms, total 37ms
D/dalvikvm( 4774): GC_FOR_ALLOC freed 1278K, 14% free 22592K/26080K, paused 22ms, total 23ms
I/dalvikvm-heap( 4774): Grow heap (frag case) to 25.279MB for 1092904-byte allocation
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1152): usb Uevent not necessary.
E/ThermalEngine(  293): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4774): GC_CONCURRENT freed 1692K, 16% free 22966K/27148K, paused 1ms+2ms, total 27ms
D/dalvikvm( 4774): GC_FOR_ALLOC freed 343K, 16% free 22917K/27148K, paused 21ms, total 22ms
I/dalvikvm-heap( 4774): Grow heap (frag case) to 26.117MB for 1639352-byte allocation
D/dalvikvm( 4774): GC_CONCURRENT freed 1707K, 19% free 23488K/28752K, paused 2ms+3ms, total 34ms
,D/WifiStateMachine(  958): handleMessage: E msg.what=131155
,D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiNative-wlan0(  958): doString: SIGNAL_POLL
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2056): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2056): nl80211: survey data missing!
,D/WifiStateMachine(  958): handleMessage: X
,D/dalvikvm( 4774): GC_FOR_ALLOC freed 1288K, 19% free 23550K/28752K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4774): Grow heap (frag case) to 27.517MB for 2459024-byte allocation
,D/dalvikvm( 4774): GC_CONCURRENT freed 225K, 17% free 25978K/31156K, paused 3ms+4ms, total 49ms
,D/dalvikvm( 4774): GC_FOR_ALLOC freed 4387K, 22% free 24538K/31156K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4774): Grow heap (frag case) to 29.654MB for 3688532-byte allocation
,D/dalvikvm( 4774): GC_CONCURRENT freed 528K, 20% free 28080K/34760K, paused 2ms+4ms, total 66ms
,D/dalvikvm( 4774): GC_FOR_ALLOC freed 3101K, 27% free 25469K/34760K, paused 23ms, total 23ms
,W/jxcore-log( 4774): Initializing JXcore engine
,W/jxcore-log( 4774): JXcore engine is ready
,D/dalvikvm( 4774): GC_CONCURRENT freed 309K, 20% free 28149K/34760K, paused 1ms+1ms, total 23ms
,D/dalvikvm( 4774): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/jxcore-log( 4774): Starting JXcore engine
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  958): battery changed pluggedType: 2
D/HeadsetStateMachine( 1215): Disconnected process message: 10
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
,W/jxcore-log( 4774): Platform android
W/jxcore-log( 4774): 
,W/jxcore-log( 4774): Process ARCH arm
W/jxcore-log( 4774): 
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
D/WifiController(  958): battery changed pluggedType: 2
,I/jxcore-log( 4774): JXcore Cordova bridge is ready!
I/jxcore-log( 4774): 
,W/jxcore-log( 4774): JXcore engine is started
,I/chromium( 4774): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4774): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4774): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/jxcore-log( 4774): Toggling radios to true
I/jxcore-log( 4774): 
,D/BluetoothManagerService(  958): Message: 20
D/BluetoothManagerService(  958): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@450760d8:true
,D/BluetoothAdapter( 4774): enable(): BT is already enabled..!
D/WifiService(  958): New client listening to asynchronous messages
D/WifiService(  958): setWifiEnabled: true pid=4774, uid=10304
E/WifiService(  958): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  958): setWifiEnabled startWifiDelaySendMsg true
,D/WifiStateMachine(  958): handleMessage: E msg.what=131145
D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiNative-wlan0(  958): doBoolean: DISCONNECT
I/jxcore-log( 4774): Radios toggled
I/jxcore-log( 4774): 
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2056): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2056): wlan0: Cancelling scan request
D/wpa_supplicant( 2056): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2056): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2056): TDLS: Tear down peers
D/wpa_supplicant( 2056): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4774): My device name is: LGE-LG-D802
I/jxcore-log( 4774): 
D/WifiService(  958): disconnect pid=4774, uid=10304
D/WifiService(  958): reconnect pid=4774, uid=10304
,D/wpa_supplicant( 2056): wlan0: Event DEAUTH (12) received
,D/wpa_supplicant( 2056): wlan0: Deauthentication notification
D/wpa_supplicant( 2056): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2056): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2056): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2056): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2056): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2056): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2056): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2056): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2056): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2056): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2056): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8eead6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2056):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2056): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2056): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2056): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2056): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2056): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2056): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2056): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2056): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2056): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2056): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2056): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2056): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2056): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2056): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2056): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2056): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2056): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2056): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2056): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2056): nl80211: Event message available
D/wpa_supplicant( 2056): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2056): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiNative-wlan0(  958):    returned true
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  958): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  958): handleMessage: new destination call exit/enter
D/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  958): invokeExitMethods: ConnectedState
W/Settings(  958): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  958): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  958): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=131146
D/WifiStateMachine(  958): processMsg: DisconnectingState
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiNative-wlan0(  958): doBoolean: RECONNECT
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2056): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2056): Fast associate: Old scan results
D/wpa_supplicant( 2056): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2056): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2056): wlan0: nl80211: scan request
D/wpa_supplicant( 205,6): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2056): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2056): nl80211: Event message available
D/wpa_supplicant( 2056): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2056): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  958):    returned true
D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=147460
D/WifiStateMachine(  958): processMsg: DisconnectingState
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): Network connection lost
D/WifiStateMachine(  958): Stopping DHCP and clearing IP
D/WifiStateMachine(  958): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  958): doBoolean: SET ps 1
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2056): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2056): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2056): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  958):    returned true
D/WifiP2pService(  958): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  958): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2056): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2056): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  958):    returned true
,D/DhcpStateMachine(  958): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  269): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  958): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiP2pService(  958): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  958): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  958): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  958): transitionTo: destState=DisconnectedState
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  958): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
,E/Parcel  (  603): Reading a NULL string not supported here.
D/QCNEA   (  603): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  603): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  603): |CAC| updateNetCfgInfo
V/QCNEA   (  603): |CAC| *********************************************
V/QCNEA   (  603): |CAC|                   Netconfig               
V/QCNEA   (  603): |CAC| *********************************************
V/QCNEA   (  603): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  603): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  603): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  603): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  603): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  603): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  603): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  603): |CAC| *********************************************
D/QCNEA   (  603): |CAC| Received bssid= 
D/QCNEA   (  603): |CAC| net type = 3
V/QCNEA   (  603): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  603): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  603): |CAC| 	ssid           =NG700
V/QCNEA   (  603): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  603): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  603): |CAC| *********************************************
D/QCNEA   (  603): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  603): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  603): |CAC| dispatchNetCfg: updating:0xb7e398dc
D/QCNEA   (  603): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  603): Reading a NULL string not supported here.
,E/Parcel  (  603): Reading a NULL string not supported here.
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  958): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  958): hidePasspointNotification off =false
,D/QcConnectivityService(  958): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
V/WfdStateTracker( 1152): handleWifiStateChangedEvent: 0
D/KeyguardUpdateMonitor( 1138): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/WifiStateMachine(  958): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  958): invokeExitMethods: DisconnectingState
,D/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/QcConnectivityService(  958): Attempting to switch to mobile
D/QcConnectivityService(  958): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  958): handleConnectivityChange: preConnState=1 connState=2
,D/WifiStateMachine(  958): invokeEnterMethods: DisconnectedState
,I/RemoteControlStatusBar( 1138): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=147462
D/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiStateMachine(  958): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  958): processMsg: ConnectModeState
,D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=147462
D/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiStateMachine(  958): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=131213
,D/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): processMsg: DriverStartedState
D/WifiStateMachine(  958): processMsg: DriverStartedStateExt
D/WifiStateMachine(  958): processMsg: SupplicantStartedState
D/WifiStateMachine(  958): processMsg: DefaultState
D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=131213
,D/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): processMsg: DriverStartedState
D/WifiStateMachine(  958): processMsg: DriverStartedStateExt
D/WifiStateMachine(  958): processMsg: SupplicantStartedState
D/WifiStateMachine(  958): processMsg: DefaultState
,D/WifiStateMachine(  958): handleMessage: X
,I/ActivityManager(  958): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4818 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/NetworkManagementService(  958): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  958): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  958): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  269): RouteController
,V/        (  269): RouteController
,V/        (  269): RouteController
,V/        (  269): RouteController
,D/HyLog   ( 4818): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4818): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4818): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  269): RouteController
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  269): RouteController
,V/        (  269): RouteController
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  269): RouteController
I/PCSuite ( 4818): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
W/NetworkManagementService(  958): route cmd failed: 
W/NetworkManagementService(  958): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  958): '
W/NetworkManagementService(  958): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  958): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  958): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  958): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  958): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  958): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  958): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  958): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  958): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  958): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  958): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  958): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  958): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  958): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  958): android_net_utils_resetConnections in env=0x629dbcd8 clazz=0x6d100001 iface=wlan0 mask=0x3
D/PCSuite ( 4818): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4818): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/QcConnectivityService(  958): resetConnections(wlan0, 3)
V/NativeCrypto( 1525): Read error: ssl=0x60e0b648: I/O error during system call, Connection timed out
,V/NativeCrypto( 1525): SSL shutdown failed: ssl=0x60e0b648: I/O error during system call, Broken pipe
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1152): usb Uevent not necessary.
,I/ActivityManager(  958): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4853 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  958): Killing 3178:android.process.media/u0a23 (adj 15): empty #17
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1215): Disconnected process message: 10
,W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  958): battery changed pluggedType: 2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/JavaBinder(  958): !!! FAILED BINDER TRANSACTION !!!
D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  958): requiresClat: netType=1, hasIPv4Address=false
W/ActivityManager(  958): Failed to clear dns cache for: android.process.media
D/QcConnectivityService(  958): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
D/LocSvc_java(  958): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  958): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1215): Disconnected process message: 10
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HyLog   ( 4853): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4853): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4853): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/LocSvc_java(  958): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  958): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  958): battery changed pluggedType: 2
,D/QRemote ( 4853): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4853): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4853): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4853): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4853): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4853): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4853): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4853): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4853): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  958): Killing 3356:com.android.mms/u0a35 (adj 15): empty #17
,I/LocationManagerService(  958): remove 43a80ce8
,D/LocationManagerService(  958): provider request: passive ProviderRequest[ON interval=0]
D/CountryDetector(  958): No listener is left
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  958): StoppedState
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4694): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1525): onDestroy
,D/WifiStateMachine(  958): handleMessage: E msg.what=131155
D/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): processMsg: DriverStartedState
D/WifiStateMachine(  958): processMsg: DriverStartedStateExt
D/WifiStateMachine(  958): processMsg: SupplicantStartedState
D/WifiStateMachine(  958): processMsg: DefaultState
,D/WifiStateMachine(  958): handleMessage: X
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  958): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  958): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  958): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  958): hal_process_report_ind: X: -0.466599 Y: -0.403748 Z: 9.789276 
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466599 .y:-0.403748 .z:9.789276
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=0
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  958): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  958): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  958): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  958): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  958): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  958): hal_process_report_ind: X: -0.473740 Y: -0.394928 Z: 9.795517 
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.473740 .y:-0.394928 .z:9.795517
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=0
D/QcConnectivityService(  958): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] connect :false
I/AppUp4:CustModeStarterReceiver( 4346): onReceive
D/AppUp4:CustFacade( 4346): Context : android.app.ReceiverRestrictedContext@42edcd60
D/AppUp4:CustFacade( 4346): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4346): isOpenOperator : true
,D/AppUp4:CustFacade( 4346): isPhone : true
I/LicenseContentProvider( 4417): start selecting data
D/SIMObserver( 4417): simInfo1
D/wpa_supplicant( 2056): nl80211: Event message available
D/wpa_supplicant( 2056): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2056): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2056): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2056): nl80211: Received scan results (12 BSSes)
D/wpa_supplicant( 2056): nl80211: Survey data missing
D/wpa_supplicant( 2056): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2056): wlan0: BSS: Add new id 8 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): wlan0: BSS: Add new id 9 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): wlan0: BSS: Add new id 10 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325'
,D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): wlan0: BSS: Add new id 11 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): BSS: last_scan_res_used=12/32 last_scan_full=0
D/wpa_supplicant( 2056): wlan0: New scan results available
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2056): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2056): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2056): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2056): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2056): WPS: AP b8:bc:1b:5a:18:00 type 0 added
D/wpa_supplicant( 2056): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2056): WPS: AP 44:e9:dd:10:c0:ac type 0 added
D/wpa_supplicant( 2056): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2056): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2056): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2056): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2056): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2056): WPS: AP[3] b8:bc:1b:5a:18:00 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2056): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2056): WPS: AP[5] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2056): WPS: AP[6] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2056): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2056): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2056): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2056): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53
D/wpa_supplicant( 2056): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2056): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2056): wlan0:    selected based on RSN IE
,D/wpa_supplicant( 2056): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2056): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2056): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2056): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2056): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2056): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2056): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2056): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8eec5a8  current_ssid=0x0
D/wpa_supplicant( 2056): scard is not null..
D/wpa_supplicant( 2056): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2056): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2056): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2056): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2056): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2056): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2056): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2056): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2056): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2056): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2056): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2056): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2056): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2056): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2056): wlan0: Cancelling scan request
D/wpa_supplicant( 2056): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2056): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2056): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2056): RSN: PMKSA cache search - network_ctx=0xb8eec5a8 try_opportunistic=0
D/wpa_supplicant( 2056): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): RSN: No PMKSA cache entry found
,D/wpa_supplicant( 2056): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2056): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2056): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2056): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2056): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2056): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2056): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2056): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2056): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2056): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2056): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2056): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2056): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2056): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2056): nl80211: Set mode ifindex 23 iftype 2 (STATION)
,D/wpa_supplicant( 2056): nl80211: Unsubscribe mgmt frames handle 0xb8eeb590 (mode change)
D/wpa_supplicant( 2056): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8eeb590
D/wpa_supplicant( 2056): nl80211: Register frame type=0xd0 nl_handle=0xb8eeb590
D/wpa_supplicant( 2056): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2056): nl80211: Register frame type=0xd0 nl_handle=0xb8eeb590
D/wpa_supplicant( 2056): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2056): nl80211: Register frame type=0xd0 nl_handle=0xb8eeb590
D/wpa_supplicant( 2056): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2056): nl80211: Register frame type=0xd0 nl_handle=0xb8eeb590
D/wpa_supplicant( 2056): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2056): nl80211: Register frame type=0xd0 nl_handle=0xb8eeb590
D/wpa_supplicant( 2056): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2056): nl80211: Register frame type=0xd0 nl_handle=0xb8eeb590
D/wpa_supplicant( 2056): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2056): nl80211: Register frame type=0xd0 nl_handle=0xb8eeb590
D/wpa_supplicant( 2056): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2056): nl80211: Register frame type=0xd0 nl_handle=0xb8eeb590
D/wpa_supplicant( 2056): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2056): nl80211: Register frame type=0xd0 nl_handle=0xb8eeb590
D/wpa_supplicant( 2056): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2056): nl80211: Register frame type=0xd0 nl_handle=0xb8eeb590
D/wpa_supplicant( 2056): nl80211: Register frame match - hexdump(len=2): 0a 11
,D/wpa_supplicant( 2056): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2056):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056):   * freq=2412
D/wpa_supplicant( 2056):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2056):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2056):   * Auth Type 0
D/wpa_supplicant( 2056):   * WPA Versions 0x2
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 a0:c5:62:7a:49:97]
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 fc:94:e3:11:35:3a]
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 44:e9:dd:10:c0:ac]
D/WifiStateMachine(  958): handleMessage: E msg.what=147461
D/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): processMsg: DriverStartedState
D/WifiStateMachine(  958): processMsg: DriverStartedStateExt
D/WifiStateMachine(  958): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  958): doString: BSS RANGE=0- MASK=0x21987
D/WifiMonitor(  958): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  958): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
I/AppUp4:EulaManager( 4346): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4346): begin check event
I/AppUp4:CustModeStarterReceiver( 4346): Event For GoodConnectivity, noConnectivity : true, but skip! 
D/wpa_supplicant( 2056): nl80211: Connect request send successfully
D/wpa_supplicant( 2056): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2056): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2056): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2056): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2056): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2056): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2056): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2056): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2056): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2056): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2056): nl80211: if_removed already cleared - ignore event
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  958): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4880 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=147462
D/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiStateMachine(  958): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): handleMessage: X
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
D/WifiController(  958): battery changed pluggedType: 2
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1215): Disconnected process message: 10
D/wpa_supplicant( 2056): nl80211: Event message available
D/wpa_supplicant( 2056): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2056): nl80211: Connect event
D/wpa_supplicant( 2056): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2056): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): nl80211: Operating fr,equency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2056): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2056): wlan0: Association info event
D/wpa_supplicant( 2056): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2056): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2056): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2056): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2056): wlan0: freq=2412 MHz
D/wpa_supplicant( 2056): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2056): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2056): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2056): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2056): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2056): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2056): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): scard is not null..
D/wpa_supplicant( 2056): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2056): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2056): TDLS: Remove peers on association
D/wpa_supplicant( 2056): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2056): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2056): EAPOL: enable timer tick
D/wpa_supplicant( 2056): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2056): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2056): wlan0: Cancelling scan request
D/wpa_supplicant( 2056): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2056): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2056): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2056): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2056): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2056): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2056): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2056): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2056): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2056): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  958): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  958): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  958): handleMessage: E msg.what=147462
D/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiStateMachine(  958): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): handleMessage: X
D/HyLog   ( 4880): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4880): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4880): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2056): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 8f c3 10 a6 b3 68 c7 d5 19 4f 16 ab 36 f4 6f ...
D/wpa_supplicant( 2056): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2056): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2056): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2056): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2056): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2056):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2056):   key_nonce - hexdump(len=32): 8f c3 10 a6 b3 68 c7 d5 19 4f 16 ab 36 f4 6f 61 3e 83 f9 ff f6 f4 63 ad c8 9f 6e c9 4a ac e1 e0
D/wpa_supplicant( 2056):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2056):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2056):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2056):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2056): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 8f c3 10 a6 b3 68 c7 d5 19 4f 16 ab 36 f4 6f ...
D/wpa_supplicant( 2056): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2056): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2056): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2056): WPA: Renewed SNonce - hexdump(len=32): 17 26 f2 51 af 17 b2 72 fb 63 d8 df bf 1d 9f 2b b4 04 3c 65 2b 42 4a e4 42 c3 61 87 91 25 c8 75
D/wpa_supplicant( 2056): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): WPA: Nonce1 - hexdump(len=32): 17 26 f2 51 af 17 b2 72 fb 63 d8 df bf 1d 9f 2b b4 04 3c 65 2b 42 4a e4 42 c3 61 87 91 25 c8 75
D/wpa_supplicant( 2056): WPA: Nonce2 - hexdump(len=32): 8f c3 10 a6 b3 68 c7 d5 19 4f 16 ab 36 f4 6f 61 3e 83 f9 ff f6 f4 63 ad c8 9f 6e c9 4a ac e1 e0
D/wpa_supplicant( 2056): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2056): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2056): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2056): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2056): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2056): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2056): WPA: Derived Key MIC - hexdump(len=16): 36 0b 3c 4e b1 6f 78 22 fe 13 99 95 44 be fa 5d
D/wpa_supplicant( 2056): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 17 26 f2 51 af 17 b2 72 fb 63 d8 df bf 1d 9f ...
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  958): handleMessage: E msg.what=147462
D/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiStateMachine(  958): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): handleMessage: X
D/wpa_supplicant( 2056): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 8f c3 10 a6 b3 68 c7 d5 19 4f 16 ab 36 f4 6f ...
D/wpa_supplicant( 2056): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2056): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2056): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2056): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2056):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2056):   key_nonce - hexdump(len=32): 8f c3 10 a6 b3 68 c7 d5 19 4f 16 ab 36 f4 6f 61 3e 83 f9 ff f6 f4 63 ad c8 9f 6e c9 4a ac e1 e0
D/wpa_supplicant( 2056):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2056):   key_rsc - hexdump(len=8): e1 d7 00 00 00 00 00 00
D/wpa_supplicant( 2056):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2056):   key_mic - hexdump(len=16): 46 ff 4f d1 fa 39 be 64 74 a4 f2 74 67 9e cd 09
D/wpa_supplicant( 2056): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 8f c3 10 a6 b3 68 c7 d5 19 4f 16 ab 36 f4 6f ...
D/wpa_supplicant( 2056): RSN: encrypted key data - hexdump(len=56): ae 66 03 c7 e9 eb a4 cc 29 b8 e8 b2 e6 33 21 c1 26 24 77 16 01 26 9b 2e 8b c7 1c 1c 22 5f ce 12 ...
D/wpa_supplicant( 2056): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2056): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2056): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2056): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 04 29 ...
D/wpa_supplicant( 2056): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2056): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2056): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2056): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2056): WPA: Derived Key MIC - hexdump(len=16): 15 44 7d 84 61 fb 6e 44 2b 2d 47 ec eb a1 6c 10
D/wpa_supplicant( 2056): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2056): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2056): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8eebc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2056):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2056): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2056): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2056): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2056): WPA: RSC - hexdump(len=6): e1 d7 00 00 00 00
D/wpa_supplicant( 2056): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f3703a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2056):    broadcast key
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  958): handleMessage: E msg.what=147462
D/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiStateMachine(  958): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): handleMessage: X
I/wpa_supplicant( 2056): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2056): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2056): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2056): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2056): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2056): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2056): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2056): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2056): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2056): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2056): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2056): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2056): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2056): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2056): EAPOL authentication completed successfully
D/wpa_supplicant( 2056): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2056): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2056): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  958): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  958): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  958): handleMessage: E msg.what=147459
D/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): Network connection established
D/WifiNative-wlan0(  958): doString: STATUS
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2056): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2056): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  958):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  958): ssid=NG700
D/WifiNative-wlan0(  958): id=0
D/WifiNative-wlan0(  958): mode=station
D/WifiNative-wlan0(  958): pairwise_cipher=CCMP
D/WifiNative-wlan0(  958): group_cipher=CCMP
D/WifiNative-wlan0(  958): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  958): wpa_state=COMPLETED
D/WifiNative-wlan0(  958): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  958): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  958): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  958): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  958): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  958): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1138): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1138): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  958): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  958): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  958): handleMessage: new destination call exit/enter
D/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  958): invokeExitMethods: DisconnectedState
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  958): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  958): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  958): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  958): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  958): WaitBeforeStartState
D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=147462
D/WifiStateMachine(  958): processMsg: ObtainingIpState
D/WifiStateMachine(  958): ObtainingIpState{ when=-20ms what=147462 obj=android.net.wifi.StateChangeResult@4550ef88 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=147462
D/WifiStateMachine(  958): processMsg: ObtainingIpState
D/WifiStateMachine(  958): ObtainingIpState{ when=-16ms what=147462 obj=android.net.wifi.StateChangeResult@45513058 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=147459
D/WifiStateMachine(  958): processMsg: ObtainingIpState
D/WifiStateMachine(  958): ObtainingIpState{ when=-17ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=131155
D/WifiStateMachine(  958): processMsg: ObtainingIpState
D/WifiStateMachine(  958): ObtainingIpState{ when=-1ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiNative-wlan0(  958): doString: SIGNAL_POLL
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2056): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2056): nl80211: survey data missing!
D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=196612
D/WifiStateMachine(  958): processMsg: ObtainingIpState
D/WifiStateMachine(  958): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiNative-wlan0(  958): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2056): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4880): DownloadService onCreate
D/EAS     ( 4676): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4676): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4880): in removeSpuriousFiles
D/eas_req ( 4676): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4880): DownloadService onStartCommand
V/DownloadManager( 4880): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4880): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4880): created cursor android.database.sqlite.SQLiteCursor@42f0a118 on behalf of 4880
V/DownloadManager( 4880): created cursor android.database.sqlite.SQLiteCursor@42f0ba00 on behalf of 4880
I/DownloadManager( 4880): in trimDatabase
V/DownloadManager( 4880): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4880): DownloadService onDestroy
W/linker  ( 4676): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4676): JNI_OnLoad
V/DownloadManager( 4880): created cursor android.database.sqlite.SQLiteCursor@42f0fab8 on behalf of 4880
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4676): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4676): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4676): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
I/ActivityManager(  958): Start proc com.android.mms for broadcast com.android.mms/.transaction.LgeMiscReceiver: pid=4915 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
D/HtmlEditor( 4676): register_HtmlEditor, Success
D/HtmlEditor( 4676): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4676): register_HtmlEditorTimer, Success
D/HtmlEditor( 4676): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4676): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4676): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4676): register_HtmlEditorFont, Success
D/HtmlEditor( 4676): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4676): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4676): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4676): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4676): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4676): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4676): JNI_OnLoad Success
D/HyLog   ( 4915): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4915): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4915): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/HubEmail( 4676): JNI_OnLoad()
I/HubEmail( 4676): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4676): registerNatives()
I/HubEmail( 4676): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4676): registerNativeMethods()
I/HubEmail( 4676): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4676): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  958): Killing 4333:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/wpa_supplicant( 2056): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  958):    returned true
D/WifiStateMachine(  958): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  958): doBoolean: SET ps 0
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2056): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2056): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2056): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  958):    returned true
D/WifiNative-wlan0(  958): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2056): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2056): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  958):    returned null
E/WifiStateMachine(  958): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  958): doString: DRIVER WLS_BATCHING STOP
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2056): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2056): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  958):    returned null
E/WifiStateMachine(  958): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  958): Current State is mWaitBeforeStartState.
I/ConversationSkinProvider( 4915): skin provider oncreate
D/DhcpStateMachine(  958): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  958): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  958): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  269): Setting iface cfg
,D/CommandListener(  269): Trying to bring up wlan0
,D/WifiStateMachine(  958): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,V/LgDhcpStateMachineHelper(  958): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=131212
D/WifiStateMachine(  958): processMsg: ObtainingIpState
D/WifiStateMachine(  958): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  958): processMsg: L2ConnectedState
,D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): processMsg: DriverStartedState
D/WifiStateMachine(  958): processMsg: DriverStartedStateExt
D/WifiStateMachine(  958): processMsg: SupplicantStartedState
D/WifiStateMachine(  958): processMsg: DefaultState
D/WifiP2pService(  958): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43a27c58 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  958): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43a27c58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  958): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=196613
D/WifiStateMachine(  958): processMsg: ObtainingIpState
D/WifiStateMachine(  958): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiStateMachine(  958): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  958): doBoolean: SET ps 1
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2056): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2056): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2056): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  958):    returned true
,D/WifiNative-wlan0(  958): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2056): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2056): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  958):    returned true
,D/WifiStateMachine(  958): DHCP successful
D/WifiStateMachine(  958): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  958): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  958): handleMessage: new destination call exit/enter
D/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  958): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  958): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  958): VerifyingLinkState enter
,D/WifiStateMachine(  958): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  958): handleMessage: X
,D/KeyguardUpdateMonitor( 1138): received broadcast android.net.wifi.STATE_CHANGE
D/WifiP2pService(  958): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  958): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  958): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  958): 
W/WifiStateTracker(  958):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  958):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  958): send additional Connectivity Action
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
D/WifiStateMachine(  958): handleMessage: E msg.what=135190
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  958): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
I/RemoteControlStatusBar( 1138): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  958): processMsg: VerifyingLinkState
D/WifiStateMachine(  958): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  958): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  958): handleMessage: new destination call exit/enter
D/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  958): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  958): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  958): CaptivePortalCheckState enter
D/WifiStateMachine(  958): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  958): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  958): handleMessage: X
,D/KeyguardUpdateMonitor( 1138): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
D/GpsLocationProvider(  958): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/RemoteControlStatusBar( 1138): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
,D/Nat464Xlat(  958): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
D/LocSvc_java(  958): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  958): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/[MMS]   ( 4915): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
D/WifiOffDelayIfNotUsed(  958): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
W/BaseRuntimeLoader( 4915): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4915): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4915): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4915): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  958): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,E/Parcel  (  603): Reading a NULL string not supported here.
D/WifiStateMachine(  958): handleMessage: E msg.what=131092
D/WifiStateMachine(  958): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  958): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/QcConnectivityService(  958): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  958): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  958): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  958): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
E/[MMS]   ( 4915): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 4915): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 4915): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4915): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 4915): MmsSettings: loadxmlstring=open_eu_mms_config
D/[MMS]   ( 4915): MmsSettings: Matching Xml Data file name = 2131034168
D/WifiStateMachine(  958): transitionTo: destState=ConnectedState
D/WifiStateMachine(  958): handleMessage: new destination call exit/enter
D/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  958): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  958): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  958): handleMessage: X
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1138): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  603): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
V/WfdStateTracker( 1152): handleWifiStateChangedEvent: 1
D/ConnectivityServiceHSM(  958): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  958): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ActivityThread(  958): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  958): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  958): handleConnectivityChange: preConnState=2 connState=1
,V/        (  269): RouteController
,V/        (  269): RouteController
,I/RemoteControlStatusBar( 1138): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  269): RouteController
,V/        (  269): RouteController
,V/        (  269): RouteController
,V/        (  269): RouteController
,V/        (  269): RouteController
,V/        (  269): RouteController
,V/        (  269): RouteController
,D/[MMS]   ( 4915): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 4915): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 4915): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 4915): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 4915): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   cb_on = [0]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 4915): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   auto_retr = [1]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 4915): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 4915): MmsSettings: [LGE]   recv_adv = [1]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 4915): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_slide_num = [10]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 4915): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 4915): MmsSettings: [LGE]   sms_recipient_length = [20]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   sms_dr_invisible = [0]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   sms_validity_invisible = [0]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   discard_visible = [0]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   inline_msg_item = [1]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   one_bubble = [1]
D/QCNEA   (  603): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  603): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  603): |CAC| updateNetCfgInfo
V/QCNEA   (  603): |CAC| *********************************************
V/QCNEA   (  603): |CAC|                   Netconfig               
V/QCNEA   (  603): |CAC| *********************************************
V/QCNEA   (  603): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  603): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  603): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  603): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  603): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  603): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  603): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  603): |CAC| *********************************************
D/QCNEA   (  603): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  603): |CAC| net type = 1
V/QCNEA   (  603): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  603): |CAC| Received ssid= NG700
V/QCNEA   (  603): |CAC| 	ssid           =NG700
V/QCNEA   (  603): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  603): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  603): |CAC| *********************************************
D/QCNEA   (  603): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  603): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  603): |CAC| dispatchNetCfg: updating:0xb7e398dc
D/QCNEA   (  603): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  958): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/[MMS]   ( 4915): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   ciq_on = [0]
,I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 4915): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/GpsLocationProvider(  958): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/[MMS]   ( 4915): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   docomo_led_button_blink = [0]
I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
D/[MMS]   ( 4915): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 4915): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   online_album_dest_num = [000]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   voice_mail = [0]
,D/[MMS]   ( 4915): MmsSettings: [LGE]   smsc_readonly = [0]
,D/Nat464Xlat(  958): requiresClat: netType=1, hasIPv4Address=true
D/[MMS]   ( 4915): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   mms_callback = [0]
D/[MMS]   ( 4915): MmsSettings: [LGE]   message_counters_key = [0]
E/[MMS]   ( 4915): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
I/[MMS]   ( 4915): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 4915): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4915): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 4915): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
D/LocSvc_java(  958): getAGpsConnectionInfo connType - 4
D/MmsConfig( 4915): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
D/LocSvc_java(  958): ignore wifi update if we are not in OPENING or CLOSING
,I/[MMS]   ( 4915): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
,I/LGDrmService( 4915): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  280): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  280): qmi_init:  Created client handle b72751f8
,E/Diag_Lib(  280): qmi_client [280] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  280): qmi_client [280] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  280): Sending signal ...... to read cmd data 
E/Diag_Lib(  280): qmi error code.........:0
E/Diag_Lib(  280): qmi sys error code.........:0
D/DRM_Adap(  280): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  280): Setting the api flag to : 1
,E/Diag_Lib(  280): qmi_client [280] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  280): qmi_client [280] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  280):  API Flag .............. 1 
,E/Diag_Lib(  280):  Message ID ............... 37 
E/Diag_Lib(  280): qmi_service_release called, user_handle=20200
E/Diag_Lib(  280): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  280): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  280): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  280): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  280): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  280): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  280): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  280): qmi_client [280] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  280): qmi_client [280] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  280): Sending signal ...... to read cmd data 
E/Diag_Lib(  280): qmi error code.........:0
E/Diag_Lib(  280): qmi sys error code.........:0
D/DRM_Adap(  280): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  280): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  280): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  280): qmi_init:  Created client handle b7275210
,E/Diag_Lib(  280): qmi_client [280] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  280): qmi_client [280] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  280): Sending signal ...... to read cmd data 
E/Diag_Lib(  280): qmi error code.........:0
E/Diag_Lib(  280): qmi sys error code.........:0
D/DRM_Adap(  280): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  280): Setting the api flag to : 1
,E/Diag_Lib(  280): qmi_client [280] 7: sending 47 bytes on fd = 16
,E/Diag_Lib(  280): qmi_client [280] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  280):  API Flag .............. 1 
E/Diag_Lib(  280):  Message ID ............... 37 
E/Diag_Lib(  280): qmi_service_release called, user_handle=20200
E/Diag_Lib(  280): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  280): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  280): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  280): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  280): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  280): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  280): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  280): qmi_client [280] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  280): qmi_client [280] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  280): Sending signal ...... to read cmd data 
E/Diag_Lib(  280): qmi error code.........:0
E/Diag_Lib(  280): qmi sys error code.........:0
,D/DRM_Adap(  280): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  280): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 4915): isDrmV1 =true
,V/DrmWrapper( 4915): isDrmV2 =false
,V/MmsConfig( 4915): [isMmsEnabledWhenDataDisabled]value=1
V/MmsConfigStaticVar( 4915): [setMmsEnabledWhenDataDisabled]enabled=true
,V/MmsConfigStaticVar( 4915): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,D/CmasFeatures( 4915): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 4915): Contact init()_Create new insatnce
,I/MessagingNotification( 4915): registerLEDObserver
,I/MessagingNotification( 4915): registerLEDObserver REGISTER
,D/DhcpStateMachine(  958): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  958): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  958): GC_EXPLICIT freed 23492K, 49% free 29790K/57944K, paused 2ms+8ms, total 132ms
,V/MmsConfig( 4915): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
,D/CountryDetector(  958): The first listener is added
,V/TelephonyAutoProfiling(  958): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/LocationManagerService(  958): getProviders()=[passive, gps]
,I/LOG_TAG ( 4915): registerContactDBChangeObserver
,D/LocationManagerService(  958): request 43b95938 passive Request[POWER_NONE passive fastest=0] from android(1000)
,D/LocationManagerService(  958): provider request: passive ProviderRequest[ON interval=0]
I/LgeMiscReceiver( 4915): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4915): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4915): networkInfo.isConnected() = false
,V/LGRssiData( 4915): [loadRssi] File not exist 
,E/ActivityThread( 4915): Failed to find provider info for com.lge.ims.provider.uc
V/LGRssiData( 4915): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4915): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 4915): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4915): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4915): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  958): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4969 uid=10052 gids={50052, 3003}
I/ActivityManager(  958): Killing 4371:com.google.android.talk/u0a77 (adj 15): empty #17
,D/HyLog   ( 4969): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4969): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4969): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
,V/TelephonyAutoProfiling(  958): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  958): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4969): [loadRssi] File not exist 
V/LGRssiData( 4969): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4969): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 4969): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4969): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4969): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4969): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4969): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4969): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4969): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 4969): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4969): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  958): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4985 uid=10063 gids={50063, 3003, 1028, 1015}
,E/PhoneMonitor( 4969): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4969): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  958): Killing 4595:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/dalvikvm(  273): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
D/HyLog   ( 4985): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4985): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4985): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
,I/CheckinService( 1854): Checking schedule, now: 1452763993294 next: 1452763929044
,I/CheckinService( 1854): active receiver: enabled
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 13ms
,I/CheckinService( 1854): Preparing to send checkin request
,I/EventLogService( 1854): Accumulating logs since 1452763896426
,I/ActivityManager(  958): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5000 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  958): Killing 4635:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5000): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5000): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5000): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinRequestBuilder( 1854): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1854): Failed to find provider info for com.google.android.wearable.settings
,D/LGDMClient( 2906): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2906): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2906): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  958): Killing 4663:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  958): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5013 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,E/LGDMClient( 2906): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2906): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2906): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2906): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5013): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5013): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5013): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5013): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  958): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5028 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  958): Killing 4430:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,D/HyLog   ( 5028): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5028): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5028): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 5028): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5028): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5028): intf.getDisplayName() = lo
I/Wireless_Storage( 5028): intf.getDisplayName() = sit0
I/Wireless_Storage( 5028): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5028): intf.getDisplayName() = teql0
I/Wireless_Storage( 5028): intf.getDisplayName() = wlan0
D/NFS     ( 5028): interface name:wlan0 name:wlan0
D/NFS     ( 5028): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5028): interface name:wlan0 name:wlan0
D/NFS     ( 5028): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 5028): CONNECT : WIFI_CONNECT
,I/ActivityManager(  958): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5040 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  958): Killing 4446:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5040): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5040): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5040): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GAV2    ( 5040): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  958): updateLightListLocked :r=NotificationRecord(0x43285820: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  958): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1854): awaiting user notification for token
,I/ActivityManager(  958): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5058 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5058): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5058): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5058): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5058): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5058): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 5058): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5058): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5058): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5058): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5058): install
,I/MultiDex( 5058): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5058): loading existing secondary dex files
,I/MultiDex( 5058): load found 3 secondary dex files
,I/MultiDex( 5058): install done
,V/WebViewChromium( 5040): Binding Chromium to the main looper Looper (main, tid 1) {42ec1278}
,I/chromium( 5040): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5040): Initializing chromium process, renderers=0
D/dalvikvm( 5058): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5058): VFY: unable to resolve instance field 61
,D/dalvikvm( 5058): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5058): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5058): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5058): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5058): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5058): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5058): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5058): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5058): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5058): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ec9628
D/dalvikvm( 5058): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ec9628
,D/dalvikvm( 5058): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ec9628, skipping init
,D/dalvikvm( 5058): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42ec9628
W/chromium( 5040): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/dalvikvm( 5058): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42ec9628
,V/JNIHelp ( 5058): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Adreno-EGL( 5040): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5040): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5040): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5040): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5040): Remote Branch: 
I/Adreno-EGL( 5040): Local Patches: 
I/Adreno-EGL( 5040): Reconstruct Branch: 
,I/NSApplication( 5040): Starting up...
,I/ActivityManager(  958): Killing 4694:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4853): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4853): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/dalvikvm( 5058): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ec9628
D/dalvikvm( 5058): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42ec9628
,D/dalvikvm( 5058): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42ec9628
D/dalvikvm( 5058): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42ec9628
,D/QRemote ( 4853): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4853): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4853): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4853): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4818): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4818): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4853): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4853): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
I/QRemote ( 4853): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 4853): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 2056): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2056): EAPOL: disable timer tick
,I/ProviderInstaller( 5058): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1525): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1525): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1525): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3469): callingUid 10006, callindPid: 3469
,E/MDM     ( 1419): [68] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1854): Restart initialization of location
I/dalvikvm( 5058): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 5058): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5058): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5058): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5058): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5058): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  275): Instantiating CDM.
,I/WVCdm   (  275): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  275): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  275): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  275): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1dd5000
,E/DrmWidevineDash(  275): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1dd5000
,D/DrmWidevineDash(  275): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  275): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  275): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  275): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  275): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  275): CdmEngine::OpenSession
,D/DrmWidevineDash(  275): calling OEMCrypto_OpenSession...
,D/DhcpStateMachine(  958): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  958): CheckDhcpDirectory [Lease File Count] : 3
D/DrmWidevineDash(  275): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  275): OEMCrypto_OpenSession returns 0
V/LgDhcpStateMachineHelper(  958): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
D/LgDhcpStateMachineHelper(  958): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  958): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  958): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  958): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  958): DHCP Start/Renew wake lock is released.
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  275): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DhcpStateMachine(  958): RunningState
,D/DrmWidevineDash(  275): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  275): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  275): PrepareKeyRequest: nonce=3575814041
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  958): NetTransition Wakelock for ConnectedState released by timeout
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5058): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4308a958
,D/dalvikvm( 5058): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4308a958
,D/dalvikvm( 5058): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4308a958, skipping init
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  275): CdmEngine::CloseSession
D/DrmWidevineDash(  275): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_CloseSession returns 0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WVCdm   (  275): CdmEngine::OpenSession
,D/DrmWidevineDash(  275): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  275): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_OpenSession returns 0
I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  275): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  275): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  275): PrepareKeyRequest: nonce=3394031080
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WifiStateMachine(  958): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  958): handleMessage: E msg.what=131212
D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): processMsg: DriverStartedState
D/WifiStateMachine(  958): processMsg: DriverStartedStateExt
D/WifiStateMachine(  958): processMsg: SupplicantStartedState
,D/WifiStateMachine(  958): processMsg: DefaultState
D/WifiStateMachine(  958): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  958): handleMessage: X
D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  958): send additional Connectivity Action
,D/LocSvc_java(  958): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
D/QcConnectivityService(  958): handleConnectivityChange:1 is conntected
,D/GpsLocationProvider(  958): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  958): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  958): ignore wifi update if we are not in OPENING or CLOSING
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  275): CdmEngine::CloseSession
,D/DrmWidevineDash(  275): calling OEMCrypto_CloseSession. SID = 1
,I/TelephonyProvider( 1444): getPreferredApnId: subscription=0
D/QcConnectivityService(  958): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  958):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  958): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  958): requiresClat: netType=1, hasIPv4Address=true
,D/DrmWidevineDash(  275): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5058): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5120): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 5058): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5058): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 76ms
,I/Adreno-EGL( 5058): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5058): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5058): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5058): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5058): Remote Branch: 
I/Adreno-EGL( 5058): Local Patches: 
I/Adreno-EGL( 5058): Reconstruct Branch: 
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings( 5058): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 5058): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5058): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5058): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5058): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5058): Remote Branch: 
I/Adreno-EGL( 5058): Local Patches: 
I/Adreno-EGL( 5058): Reconstruct Branch: 
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 5058): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5058): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5058): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5058): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5058): Remote Branch: 
I/Adreno-EGL( 5058): Local Patches: 
I/Adreno-EGL( 5058): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1854): Classify the device as Phone.
,D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1854): Sending checkin request (11467 bytes)
,I/CheckinRequestBuilder( 1854): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1854): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  958): updateLightListLocked :r=NotificationRecord(0x42ee0630: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  958): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1854): awaiting user notification for token
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1152): usb Uevent not necessary.
,I/CheckinRequestBuilder( 1854): Classify the device as Phone.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinTask( 1854): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1854): Checking schedule, now: 1452763995795 next: 1453341391792
,I/CheckinService( 1854): active receiver: disabled
,D/WifiStateMachine(  958): handleMessage: E msg.what=131155
,D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiNative-wlan0(  958): doString: SIGNAL_POLL
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2056): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2056): nl80211: survey data missing!
,D/WifiStateMachine(  958): handleMessage: X
E/Parcel  (  603): Reading a NULL string not supported here.
,E/Parcel  (  603): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/GCM     ( 1525): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  958): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  958): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4346): onReceive
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
D/AppUp4:CustFacade( 4346): Context : android.app.ReceiverRestrictedContext@42edcd60
D/AppUp4:CustFacade( 4346): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4346): isOpenOperator : true
,D/AppUp4:CustFacade( 4346): isPhone : true
,I/LicenseContentProvider( 4417): start selecting data
,D/SIMObserver( 4417): simInfo1
,I/AppUp4:EulaManager( 4346): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4346): begin check event
I/AppUp4:CustModeStarterReceiver( 4346): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4346): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4346): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4346): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4346): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4346): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4880): DownloadService onCreate
I/DownloadManager( 4880): in removeSpuriousFiles
,V/DownloadManager( 4880): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4880): created cursor android.database.sqlite.SQLiteCursor@42f13758 on behalf of 4880
D/EAS     ( 4676): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4676): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4880): in trimDatabase
,V/DownloadManager( 4880): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4880): created cursor android.database.sqlite.SQLiteCursor@42f14990 on behalf of 4880
,D/eas_req ( 4676): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4915): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4915): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4915): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4969): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4969): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4676): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2906): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5013): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/NFS     ( 5028): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5028): CONNECT : WIFI_CONNECT
W/ContextImpl( 5013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/LGDMClient( 2906): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2906): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2906): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2906): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2906): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  958): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  958): MasterInitialState.processMessage what=3
,I/LGDMClient( 2906): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4346): onReceive
D/AppUp4:CustFacade( 4346): Context : android.app.ReceiverRestrictedContext@42edcd60
D/AppUp4:CustFacade( 4346): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4346): isOpenOperator : true
,D/AppUp4:CustFacade( 4346): isPhone : true
,I/LicenseContentProvider( 4417): start selecting data
,D/SIMObserver( 4417): simInfo1
,D/dalvikvm(  958): GC_EXPLICIT freed 2068K, 49% free 29674K/57944K, paused 3ms+6ms, total 114ms
,I/AppUp4:EulaManager( 4346): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4346): begin check event
,I/AppUp4:CustModeStarterReceiver( 4346): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4880): DownloadService onStartCommand
,V/DownloadManager( 4880): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4880): created cursor android.database.sqlite.SQLiteCursor@42f18198 on behalf of 4880
,V/DownloadManager( 4880): DownloadService onStartCommand
,D/EAS     ( 4676): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4676): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4880): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4880): created cursor android.database.sqlite.SQLiteCursor@42f1a7a0 on behalf of 4880
I/LgeMiscReceiver( 4915): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4915): action = android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4880): DownloadService onDestroy
I/LgeMiscReceiver( 4915): networkInfo.isConnected() = true
,D/PhoneState( 4915): setPdpRejectCasuse : false
,W/Settings( 4676): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4969): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4969): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2906): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5013): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2906): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 5028): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5028): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2906): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 5013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/GCM     ( 1525): Connected
,E/LGDMClient( 2906): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2906): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2906): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2906): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/jxcore-log( 4774): Test app app.js loaded
I/jxcore-log( 4774): 
,I/Choreographer( 4774): Skipped 402 frames!  The application may be doing too much work on its main thread.
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/chromium( 4774): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1525): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  958): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  958): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  958): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4346): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4346): onReceive
,D/AppUp4:CustFacade( 4346): Context : android.app.ReceiverRestrictedContext@42edcd60
,D/AppUp4:CustFacade( 4346): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4346): isOpenOperator : true
,D/AppUp4:CustFacade( 4346): isPhone : true
,I/LicenseContentProvider( 4417): start selecting data
,D/SIMObserver( 4417): simInfo1
,I/AppUp4:EulaManager( 4346): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4346): begin check event
,I/AppUp4:CustModeStarterReceiver( 4346): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4676): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4880): DownloadService onCreate
,D/EAS     ( 4676): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4915): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4915): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4915): networkInfo.isConnected() = true
,D/PhoneState( 4915): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4969): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4969): onReceive CONNECTIVITY_CHANGE networkType=1
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2906): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/DownloadManager( 4880): in removeSpuriousFiles
,V/DownloadManager( 4880): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/Settings( 4676): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2906): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5013): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4880): DownloadService onStartCommand
,V/DownloadManager( 4880): created cursor android.database.sqlite.SQLiteCursor@42f1f2f8 on behalf of 4880
,V/DownloadManager( 4880): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 2906): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ContextImpl( 5013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 5028): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5028): CONNECT : WIFI_CONNECT
I/DownloadManager( 4880): in trimDatabase
V/DownloadManager( 4880): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4880): created cursor android.database.sqlite.SQLiteCursor@42f213d8 on behalf of 4880
V/DownloadManager( 4880): created cursor android.database.sqlite.SQLiteCursor@42f22000 on behalf of 4880
,E/LGDMClient( 2906): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2906): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2906): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2906): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 4880): DownloadService onDestroy
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WifiServiceExtension(  958): MESSAGE_INTERNET_CHECK msg is received.
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  958): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  958): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  958): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 5040): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,D/WifiStateMachine(  958): handleMessage: E msg.what=131155
D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  958): doString: SIGNAL_POLL
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2056): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2056): nl80211: survey data missing!
,D/WifiStateMachine(  958): handleMessage: X
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  958): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/ActivityManager(  958): Killing 4233:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  958): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5238 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5238): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5238): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5238): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5238): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5238): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5238): VFY: replacing opcode 0x6e at 0x000b
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5238): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5238): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5238): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5238): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5238): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5238): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5238): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5238): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5238): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5238): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5238): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5238): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 5238): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5238): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5238): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5238): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5238): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5238): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5238): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5238): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 5238): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 5238): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5238): VFY: replacing opcode 0x6e at 0x001a
,V/DownloadManager( 4880): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4880): created cursor android.database.sqlite.SQLiteCursor@42f27610 on behalf of 5238
,I/dalvikvm( 5238): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5238): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5238): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5238): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5238): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5238): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5238): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm( 5238): Total arena pages for JIT: 11
,I/dalvikvm( 5238): Total arena pages for JIT: 12
I/dalvikvm( 5238): Total arena pages for JIT: 13
,I/dalvikvm( 5238): Total arena pages for JIT: 14
,D/Finsky  ( 5238): [474] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5238): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  958): Killing 4818:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5238): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5238): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5238): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5238): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5238): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  958): handleMessage: E msg.what=131155
D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiNative-wlan0(  958): doString: SIGNAL_POLL
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2056): wlan0: Control interface command 'SIGNAL_POLL'
,D/dalvikvm( 1525): GC_EXPLICIT freed 1069K, 29% free 17825K/24832K, paused 3ms+5ms, total 37ms
,D/wpa_supplicant( 2056): nl80211: survey data missing!
,D/WifiStateMachine(  958): handleMessage: X
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5238): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5238): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5238): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5238): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5238): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1419): client connected with version: 7571000
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/InputReader(  958): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "sms"
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1484): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/administrator(  958): Handling package changes for user 0
,I/ActivityManager(  958): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5331 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,E/SlideAside( 4133): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1484): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/SlideAside( 4133): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/[LGHome]LGPlusHomeDBManager( 1484): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "smsto"
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1484): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HyLog   ( 5331): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5331): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5331): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "mms"
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1138): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1138): changeTargets() succeeded. size: 20
I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "mmsto"
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "sms"
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "smsto"
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "mms"
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "mmsto"
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5331): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5331): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5331): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5331): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5331): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5331): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5331): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5331): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5331): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5331): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5331): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5331): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5331): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5331): MmsConfig.loadFromResources
,I/[LGHome]EVENT( 1484): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
E/Babel   ( 5331): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5331): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1419): DISABLE
,I/GCoreNlp( 1419): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 5331): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  958): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  958): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5331): [loadRssi] File not exist 
V/LGRssiData( 5331): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5331): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5331): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5331): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5331): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4346): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4346): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4346): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4346): onReceive
D/AppUp4:CustFacade( 4346): Context : android.app.ReceiverRestrictedContext@42edcd60
,D/AppUp4:CustFacade( 4346): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4346): isOpenOperator : true
,D/AppUp4:CustFacade( 4346): isPhone : true
I/LicenseContentProvider( 4417): start selecting data
,D/SIMObserver( 4417): simInfo1
,I/AppUp4:EulaManager( 4346): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4346): begin check event
D/AppUp4:Utils( 4346): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4346): Event For Nothing, skip.
,D/LocationProviderProxy(  958): applying state to connected service
,D/LocationProviderProxy(  958): applying state to connected service
,I/ActivityManager(  958): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5380 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5380): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5380): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5380): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5380): BUILD Country: EU
,I/SystemConfig( 5380): BUILD Operator: OPEN
I/ActivityManager(  958): Killing 4853:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  958): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5395 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
,I/SystemConfig( 5380): systemFeature RCS result false
,D/SystemConfig( 5380): refreshRcsSupport() :false
I/ActivityManager(  958): Killing 4676:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 5395): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5395): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5395): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
D/WifiController(  958): battery changed pluggedType: 2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1457): GC_CONCURRENT freed 1539K, 7% free 25440K/27280K, paused 1ms+1ms, total 16ms
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/dalvikvm(  958): GC_EXPLICIT freed 1757K, 49% free 29892K/57944K, paused 2ms+7ms, total 89ms
,I/ActivityManager(  958): Killing 4915:com.android.mms/u0a35 (adj 15): empty #17
,I/IcingCorporaProvider( 2703): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/CountryDetector(  958): No listener is left
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 2 tasks}
,D/ActivityManager(  958): resumeTopActivityLocked: Top activity resumed ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
I/LocationManagerService(  958): remove 43b95938
D/LocationManagerService(  958): provider request: passive ProviderRequest[ON interval=0]
,D/PackageBroadcastService( 1854): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1854): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  958): Delaying start of: ServiceRecord{450e4ab0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,D/dalvikvm( 1854): GC_CONCURRENT freed 1859K, 22% free 19558K/24832K, paused 3ms+3ms, total 40ms
,I/Icing   ( 1854): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2703): UpdateCorporaTask done [took 228 ms] updated apps [took 228 ms] 
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  958): battery changed pluggedType: 2
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  958): handleMessage: E msg.what=131155
,D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  958): doString: SIGNAL_POLL
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2056): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2056): nl80211: survey data missing!
,D/WifiStateMachine(  958): handleMessage: X
,I/PowerManagerService(  958): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  958): [updateScreenState] screen on = false
,D/KnockOnPowerController(  958): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  958): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  958): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  958): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  958): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  958): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,I/qcom_sensors_hal(  958): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  958): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8449 usec
D/KnockOnPowerController(  958): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  958): hal_acquire_resources
,I/qcom_sensors_hal(  958): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  958): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  958): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
D/qcom_sensors_hal(  958): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,V/qcom_sensors_hal(  958): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,I/qcom_sensors_hal(  958): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  958): hal_process_report_ind: X: -0.477142 Y: -0.421967 Z: 9.792419 
V/qcom_sensors_hal(  958): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.477142 .y:-0.421967 .z:9.792419
,D/qcom_sensors_hal(  958): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  958): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  958): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  958): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  958): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  958): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  958): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  958): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  958): hal_process_report_ind: X: -0.460846 Y: -0.413803 Z: 9.809326 
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460846 .y:-0.413803 .z:9.809326
,D/qcom_sensors_hal(  958): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=0
,I/Sensors (  584): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  958): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  958): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  958): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  958): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  958): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  958): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  958): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  958): hal_process_report_ind: X: -0.455872 Y: -0.403809 Z: 9.793030 
,D/qcom_sensors_hal(  958): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455872 .y:-0.403809 .z:9.793030
,D/qcom_sensors_hal(  958): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  958): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  958): proximitySensorChanged  positive = true
I/KnockOnPowerController(  958): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  958): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  958): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  958): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  958): hal_process_report_ind: X: -0.460571 Y: -0.413696 Z: 9.796280 
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460571 .y:-0.413696 .z:9.796280
,D/qcom_sensors_hal(  958): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  958): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  958): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  958): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  958): hal_process_report_ind: X: -0.461304 Y: -0.411377 Z: 9.805527 
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461304 .y:-0.411377 .z:9.805527
,D/qcom_sensors_hal(  958): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  958): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  958): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  958): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  958): hal_process_report_ind: X: -0.461060 Y: -0.397522 Z: 9.798004 
,D/qcom_sensors_hal(  958): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461060 .y:-0.397522 .z:9.798004
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  958): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44d8fad0)
,D/KeyguardViewMediator( 1138): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1138): notifyScreenOnLocked
,V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  958): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  958): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  958): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  958): hal_process_report_ind: X: -0.464813 Y: -0.396255 Z: 9.793762 
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464813 .y:-0.396255 .z:9.793762
,D/qcom_sensors_hal(  958): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=0
,D/LockPatternUtilsEx( 1138): OMADM Lock is OFF
,D/KeyguardViewMediator( 1138): handleNotifyScreenOn
,D/KeyguardViewManager( 1138): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  958): **** SHOWN CALLED ****
,D/SurfaceFlinger(  272): Screen released, type=0 flinger=0xb7ac2450
,D/qdhwcomposer(  272): hwc_blank: Blanking display: 0
I/WindowManager(  958): No lock screen! windowToken=null
,D/NativeNfcBrcmPowerMode( 1469): setPowerMode; state=4
,D/WifiStateMachine(  958): handleScreenStateChanged: true
,D/WifiStateMachine(  958): handleMessage: E msg.what=131154
D/WifiStateMachine(  958): processMsg: ConnectedState
,D/WifiStateMachine(  958): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  958): doString: SIGNAL_POLL
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2056): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  958): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2056): nl80211: survey data missing!
,D/WifiStateMachine(  958): handleMessage: X
,D/WifiStateMachine(  958): handleMessage: E msg.what=131127
D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
,D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): handleMessage: X
,D/WifiStateMachine(  958): handleMessage: E msg.what=131158
D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
,D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): processMsg: DriverStartedState
D/WifiStateMachine(  958): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=132097
,D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiStateMachine(  958): processMsg: ConnectModeState
,D/WifiStateMachine(  958): processMsg: DriverStartedState
,D/WifiStateMachine(  958): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  958): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2056): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2056): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  958): handleMessage: X
,V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  958): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  958): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  958): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  958): hal_process_report_ind: X: -0.466873 Y: -0.404175 Z: 9.798370 
,D/qcom_sensors_hal(  958): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466873 .y:-0.404175 .z:9.798370
D/qcom_sensors_hal(  958): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  958): stopMonitoring
,E/AudioSystem(  958): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=on, calling pid 958
V/SRS_Proc(  275): ParamSet string: screen_state=on
,D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=on
V/voice   (  275): voice_set_parameters: enter: screen_state=on
V/voice   (  275): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  275): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  275): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1152): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1152): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43873fe0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1152): enqueuing start. mLedList.size()=2
,D/qdlights( 1152): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1152): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1152): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1152): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1152): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1818): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 10:33:25
E/SlideAside( 4133): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 4133): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/UpdateThreadPoolManager( 1818): 2 : This is isUpdating : false
,D/WeatherAncestor( 1818): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 10:33:25
,D/WeatherService( 1818): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
,D/LockPatternUtilsEx( 1138): OMADM Lock is OFF
D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1152): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1152): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1152): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 237, B = 237
,D/CaptivePortalTracker(  958): DelayedCaptiveCheckState{ when=-4ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  958): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  958): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/qdlights( 1152): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1152): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1152): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1152): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  272): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  958): Excessive delay in blankDisplay() while turning screen off: 392ms
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1152): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 207, B = 207
,D/CaptivePortalTracker(  958): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  958): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  958): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  958): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  958): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
D/qdlights( 1152): set_light_notifications: 2,ff00c9c9,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1152): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1152): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 189, B = 189
,D/GlobalAccess( 1138): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1138): changeTargets() succeeded. size: 20
,D/qdlights( 1152): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452764006102, nextTick: 33929, mDrawingTime: 1
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1152): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1152): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1152): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 165, B = 165
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452764006139, nextTick: 33894, mDrawingTime: 0
,D/qdlights( 1152): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 159, B = 159
,D/NativeNfcBrcmPowerMode( 1469): setPowerMode; state=4
,D/qdlights( 1152): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 153, B = 153
,D/WeatherService( 1818): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:33:26
,D/WeatherService( 1818): 2 : ACTION screen on
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1818): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:33:26
D/qdlights( 1152): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 147, B = 147
,V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  958): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/qdlights( 1152): set_light_notifications: 2,ff008d8d,10,0,2
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
,E/Parcel  (  603): Reading a NULL string not supported here.
,D/qdlights( 1152): [Current] = 255, R = 0, G = 141, B = 141
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/GsmSST  ( 1444): Emergency Service
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1444): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1444): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1444): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1444): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1444): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1152): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 135, B = 135
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  958): ACTION_SCREEN_ON
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/KeyguardViewMediator( 1138): onScreenTurnedOff(3)
I/qcom_sensors_hal(  958): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  958): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  958): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  958): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1138): notifyScreenOffLocked
,D/qdlights( 1152): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 129, B = 129
,V/ActivityManager(  958): Moving to PAUSING: ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
D/qcom_sensors_hal(  958): hal_acquire_resources
D/qcom_sensors_hal(  958): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  958): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  958): hal_wait_for_response: timeout=1000
D/KeyguardViewMediator( 1138): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/KeyguardViewMediator( 1138): handleNotifyScreenOff
D/qdlights( 1152): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 123, B = 123
,D/KeyguardViewManager( 1138): onScreenTurnedOff()
,V/qcom_sensors_hal(  958): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  958): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  958): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  958): hal_smgr_report_delete: Rcvd success response from request
V/ActivityManager(  958): Moving to PAUSED: ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,I/LGImmersionVibrator(  958): Vibrator off
D/qdlights( 1152): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 117, B = 117
V/ActivityManager(  958): Moving to STOPPING: ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,V/ActivityManager(  958): Moving to DESTROYING: ActivityRecord{432fa238 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/WifiStateMachine(  958): handleScreenStateChanged: false
D/WifiStateMachine(  958): handleMessage: E msg.what=131154
D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
,D/WifiStateMachine(  958): handleMessage: X
D/WifiStateMachine(  958): handleMessage: E msg.what=131158
D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiStateMachine(  958): processMsg: DriverStartedState
D/WifiStateMachine(  958): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  958): doBoolean: DRIVER SETSUSPENDMODE 1
,D/UsbSettings( 2631): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/qdlights( 1152): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 111, B = 111
V/ActivityManager(  958): Moving to STOPPED: ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  958): CMD_SCREEN_OFF 
,D/WifiController(  958): shouldWifiStayAwake TRUE
D/wpa_supplicant( 2056): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2056): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
E/AudioSystem(  958): AudioSystem::setParameters()...keyValue screen_state=off
V/UsbSettings( 2631): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2631): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2631): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=off, calling pid 958
V/SRS_Proc(  275): ParamSet string: screen_state=off
D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=off
V/voice   (  275): voice_set_parameters: enter: screen_state=off
V/voice   (  275): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  275): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  275): adev_set_parameters: exit with code(-2)
D/qdlights( 1152): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 105, B = 105
I/EmotionalLed( 1152): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/wpa_supplicant( 2056): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  958):    returned true
,D/WifiStateMachine(  958): handleMessage: X
,E/CliptrayService( 1152): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1152): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 99, B = 99
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/VolumeVibrator( 1152): clear
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NativeNfcBrcmPowerMode( 1469): setPowerMode; state=2
,I/[LGHome]EVENT( 1484): [Launcher.java:1567:onReceive()]Screen Off
V/ActivityManager(  958): Moving to DESTROYED: ActivityRecord{432fa238 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4389f838 stackId=1, 1 tasks}
,D/ActivityManager(  958): resumeTopActivityLocked: Going to sleep and all paused
D/qdlights( 1152): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 93, B = 93
D/WeatherService( 1818): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:33:26
D/WeatherService( 1818): 2 : ACTION screen off
D/WeatherService( 1818): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:33:26
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
V/TelephonyAutoProfiling(  958): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
E/Parcel  (  603): Reading a NULL string not supported here.
D/qdlights( 1152): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 87, B = 87
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1444): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1444): Emergency Service
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1444): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/LockPatternUtilsEx( 1138): OMADM Lock is OFF
D/BrcmNfcJni( 1469): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1469): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1444): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1444): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1444): [getValue] FEATURE key : vzw_gfit, value : null
V/PhoneApp( 1444): Action intent recieved:android.intent.action.SCREEN_OFF
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  958): ACTION_SCREEN_OFF
D/qdlights( 1152): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 81, B = 81
D/NfcService( 1469): NFC-C OFF
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1457): [TangibleIO] LCD is off. Remove tangible if exist.
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1152): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1152): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1152): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1152): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1152): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1152): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1152): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1152): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1152): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1152): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1152): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1152): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1152): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1152): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1152): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  958): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  584): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  293): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  958): handleMessage: E msg.what=131155
,D/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiStateMachine(  958): processMsg: L2ConnectedState
,D/WifiStateMachine(  958): handleMessage: X
,D/WifiStateMachine(  958): handleMessage: E msg.what=131155
,D/WifiStateMachine(  958): processMsg: ConnectedState
,D/WifiStateMachine(  958): processMsg: L2ConnectedState
,D/WifiStateMachine(  958): handleMessage: X
,I/GAV4    ( 5331): Thread[GAThread,5,main]: No campaign data found.
,D/KeyguardViewMediator( 1138): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1444): getIsInUseVoLTE : false
,D/PhoneApp( 1444): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1138): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1138): OMADM Lock is OFF
,D/KeyguardViewMediator( 1138): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1138): doKeyguard is called, but is not locked.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1525): Vacuum at: now=1452764017212 tag=VacuumService
,I/GoogleURLConnFactory( 1525): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1525): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1525): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1525): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1525): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1525): No account for auth token provided
,D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/Finsky  ( 5238): [474] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5238): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1525): No account for auth token provided
,W/Uploader( 1525): No account for auth token provided
,W/Uploader( 1525):  no longer exists, so no auth token.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ProcessCpuTracker(  958): Skipping unknown process pid 5542
,W/ProcessCpuTracker(  958): Skipping unknown process pid 5545
,D/qcom_sensors_hal(  958): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  958): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  958): hal_ts_offset_is: Apps: 1452764023874842399; DSPS: 5284830; Offset: 1452763862594629997
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1138): handleTimeUpdate
,D/KeyguardModel( 1138): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452764040036, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452764040046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  958): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  958): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  958): hal_ts_offset_is: Apps: 1452764043876701609; DSPS: 5940251; Offset: 1452763862594627635
,D/qcom_sensors_hal(  958): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  958): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  958): hal_ts_offset_is: Apps: 1452764063878514727; DSPS: 6595671; Offset: 1452763862594609698
,D/qcom_sensors_hal(  958): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  958): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  958): hal_ts_offset_is: Apps: 1452764083880190917; DSPS: 7251086; Offset: 1452763862594607421
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  958): battery changed pluggedType: 2
D/HeadsetStateMachine( 1215): Disconnected process message: 10
W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1138): handleTimeUpdate
,D/KeyguardModel( 1138): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452764100029, nextTick: 59999, mDrawingTime: 3
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452764100067, nextTick: 59963, mDrawingTime: 1
,D/qcom_sensors_hal(  958): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  958): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  958): hal_ts_offset_is: Apps: 1452764103881994972; DSPS: 7906505; Offset: 1452763862594610939
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
,D/WifiController(  958): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,W/Settings(  958): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  958): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  958): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  958): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  958): hal_ts_offset_is: Apps: 1452764123883923662; DSPS: 8561928; Offset: 1452763862594617022
,D/qcom_sensors_hal(  958): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  958): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  958): hal_ts_offset_is: Apps: 1452764143886251103; DSPS: 9217364; Offset: 1452763862594625127
,I/jxcore-log( 4774): --= Surplus to requirements =--
I/jxcore-log( 4774): 
,I/jxcore-log( 4774): ****TEST TOOK:  ms ****
I/jxcore-log( 4774): 
,I/jxcore-log( 4774): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4774): 
,D/AndroidRuntime( 5677): 
D/AndroidRuntime( 5677): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5677): CheckJNI is OFF
,D/dalvikvm( 5677): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5677): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 5677): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5677): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5677): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5677): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5677): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5677): failed to load memtrack module: -2
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 5677): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  958): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  958): Killing 4774:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  958): Moving to DESTROYED: ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
I/MDM     (  958):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  958):   Force finishing activity ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  958): Moving to FINISHING: ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  958): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  958): moveHomeStack:
,I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4329dc18 stackId=0, 1 tasks}
,V/ActivityManager(  958): Moving to RESUMED: ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  958): Moving to PAUSING: ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  958): resumeTopActivityLocked: Resumed ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4329dc18 stackId=0, 1 tasks}
D/ActivityManager(  958): allPausedActivitiesComplete: r=ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  958): allPausedActivitiesComplete: r=ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  958): resumeTopActivityLocked: Skip resume: some activity pausing.
,V/ActivityManager(  958): Moving to DESTROYED: ActivityRecord{4551ba28 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4329dc18 stackId=0, 1 tasks}
D/ActivityManager(  958): allPausedActivitiesComplete: r=ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  958): allPausedActivitiesComplete: r=ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  958): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1484): [Launcher.java:4947:onStart()]onStart
,I/WindowState(  958): WIN DEATH: Window{45544330 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  958): Client connection lost with reason: 4
,W/PackageSettings(  958): Skipping PackageSetting{4339c908 com.example.hello/10312} due to missing metadata
,I/[LGHome]EVENT( 1484): [Launcher.java:717:onResume()]onResume
I/ActivityManager(  958): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4329dc18 stackId=0, 1 tasks}
D/ActivityManager(  958): allPausedActivitiesComplete: r=ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  958): allPausedActivitiesComplete: r=ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  958): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1484): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
D/KeyguardModel( 1138): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]Launcher.Model( 1484): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/PhoneApp( 1444): getIsInUseVoLTE : false
,W/ActivityManager(  958): getAssistContextExtras failed: no resumed activity
,W/ActivityManager(  958): getAssistContextExtras failed: no resumed activity
,I/InputReader(  958): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 4133): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/SlideAside( 4133): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
,D/GlobalAccess( 1138): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1138): changeTargets() succeeded. size: 20
,I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "sms"
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AppUp4:Utils( 4346): [getPackageName] uri : package:com.test.thalitest
,D/AppUp4  ( 4346): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
,I/AppUp4  ( 4346):  isExcludedPackage  packagename = com.test.thalitest
,I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  958):   Scheme: "smsto"
,D/AppUp4  ( 4346):  isExcludedPackage TRUE : com.test.thalitest
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/System.err( 2687): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/GeofencerStateMachine( 1419): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "mms"
,I/[LGHome]LGActivityUtil( 1484): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/System.err( 2687): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2687): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2687): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2687): 	at android.os.Handler.handleCallback(Handler.java:733)
,W/System.err( 2687): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2687): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2687): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2687): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2687): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2687): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2687): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2687): 	at dalvik.system.NativeStart.main(Native Method)
,I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "mmsto"
,D/KeyguardModel( 1138): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/dalvikvm( 2703): GC_EXPLICIT freed 4388K, 27% free 18155K/24832K, paused 66ms+6ms, total 124ms
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  958): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5706 uid=10090 gids={50090}
,D/dalvikvm(  958): GC_EXPLICIT freed 1858K, 49% free 29941K/57944K, paused 2ms+10ms, total 141ms
,D/dalvikvm(  958): WAIT_FOR_CONCURRENT_GC blocked 51ms
,I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "sms"
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  958): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5721 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/[LGHome]EVENT( 1484): [Launcher.java:868:onResume()]onResume end
I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  958):   Scheme: "smsto"
D/administrator(  958): Handling package changes for user 0
,I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  273): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+3ms, total 29ms
,I/[LGHome]EVENT( 1484): [Launcher.java:894:onPause()]onPause
,I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "mms"
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
V/ActivityManager(  958): Moving to PAUSED: ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  958): Moving to STOPPING: ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 23ms
,I/[LGHome]EVENT( 1484): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1484): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1484): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 21ms
,D/HyLog   ( 5706): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5706): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5706): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1484): [Launcher.java:4955:onStop()]onStop
,I/[LGHome]EVENT( 1484): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PackageManager(  958):   Action: "android.intent.action.SENDTO"
I/PackageManager(  958):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  958):   Scheme: "mmsto"
,D/HyLog   ( 5721): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  958): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/InputMethodManagerService(  958): IME STATUS OFF
D/HyLog   ( 5721): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5721): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/Binder  ( 1309): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1309): java.lang.NullPointerException
W/Binder  ( 1309): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1309): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1309): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1309): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  958): Got RemoteException sending setActive(false) notification to pid 4774 uid 10304
,I/LockScreenSettings( 5706): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/KeyguardModel( 1138): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1138): createShortcutInfo...
,D/dalvikvm(  958): GC_EXPLICIT freed 512K, 49% free 29889K/57944K, paused 6ms+18ms, total 175ms
,I/[LGHome]Launcher.Model( 1484): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1484): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
V/ActivityManager(  958): Moving to STOPPED: ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,D/KeyguardModel( 1138): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1138): createShortcutInfo...
I/InteractionManagerConfigurator(  958): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  958): com.test.thalitest isn't inclued in dragdropPackageList
,D/KeyguardModel( 1138): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1138): createShortcutInfo...
D/BackupManagerService(  958): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService(  958): removePackageParticipantsLocked: uid=10304 #1
D/KeyguardModel( 1138): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1138): createShortcutInfo...
I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
D/[BNRAppListMgrReceiver]( 5721): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
D/KeyguardModel( 1138): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1138): createShortcutInfo...
,I/ActivityManager(  958): Timeline: Activity_windows_visible id: ActivityRecord{43335ef0 u0 com.lge.launcher2/.Launcher t1} time:292485
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
D/KeyguardModel( 1138): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1138): createShortcutInfo...
I/ActivityManager(  958): Killing 4969:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/VoicemailCleanupService( 1764): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  958): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5738 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4329dc18 stackId=0, 1 tasks}
D/ActivityManager(  958): resumeTopActivityLocked: Going to sleep and all paused
,D/AndroidRuntime( 5677): Shutting down VM
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 5677): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
,D/dalvikvm( 1138): GC_CONCURRENT freed 8411K, 11% free 69931K/78528K, paused 1ms+5ms, total 41ms
,D/dalvikvm( 1138): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/HyLog   ( 5738): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5738): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5738): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1484): GC_CONCURRENT freed 5556K, 9% free 60845K/66580K, paused 2ms+4ms, total 39ms
,D/dalvikvm( 1484): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/KeyguardModel( 1138): handleShortcutListChanged...
,D/KeyguardModel( 1138): handleShortcutListChanged...
I/ActivityManager(  958): Killing 4985:com.android.chrome/u0a63 (adj 15): empty #17
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4329dc18 stackId=0, 1 tasks}
D/ActivityManager(  958): resumeTopActivityLocked: Going to sleep and all paused
,I/LGEmail ( 5738): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1484): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,D/LGEmail ( 5738): EmailContentProvider.query: uri=content://com.lge.providers.lgemail/account, projection=[accountID, userName, mailAddress, accountName, InboxID], selection=null, selectionArgs=null sortOrder=null, TABLE_NAMES=EAccountmatch is 0 (at LGEmailContentProvider.java query 492)[v:6.30.33]
E/LGEmail ( 5738): Email Not Started (at LGEmailContentProvider.java query 509)[v:6.30.33]
I/[LGHome]Launcher.Model( 1484): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1484): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher( 1484): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,E/[LGHome]NumberBadge( 1484): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]Launcher.Model( 1484): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1484): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1484): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1484): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1484): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1484): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]Launcher( 1484): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,D/LGEmail ( 5738): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1484): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1484): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]Launcher( 1484): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1484): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1484): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,W/BaseRuntimeLoader( 5738): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5738): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5738): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5738): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/PackageChangeReceiver( 5738): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]EVENT( 1484): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
I/[LGHome]Launcher( 1484): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  958): Killing 5000:com.lge.drmservice/u0a66 (adj 15): empty #17
D/PackageIntentReceiver( 2631): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 2631): Receive package name : com.test.thalitest
D/HideNavigationAppsReceiver( 2631): Delete mPackageMame : com.test.thalitest
,I/ActivityManager( 1484): Timeline: Activity_idle id: android.os.BinderProxy@42ec3f68 time:292757
,I/IcingCorporaProvider( 2703): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  958): resumeTopActivitiesLocked(): target Stack:ActivityStack{4329dc18 stackId=0, 1 tasks}
D/ActivityManager(  958): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  958): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5760 uid=10073 gids={50073, 3003, 1028, 1015}
,D/HyLog   ( 5760): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5760): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5760): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2703): UpdateCorporaTask done [took 118 ms] updated apps [took 118 ms] 
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0

```
