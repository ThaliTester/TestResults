#### Test 506502782e2cb10_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1882): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1882): launchTask
W/dalvikvm( 1882): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/ConfigFetchTask( 1882): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UawKdPiav8jwp8EKAPQ7RtGYXGuQfBxvLwdcCtjPU4VXMu1zLodwzvNlmRLbPpnnBiwGQNEgIV2HD00-DhowI3rx6IhfAO12sGQe0qu-cR81EEhjiBCjxzCSaf_FGgE1PPJq8E-trBKy_8VHjrs-JP1iXP95DFXN436usfjIzbXI45YGH2CMVR6lYR_qqnWPpCS1ey
I/GoogleURLConnFactory( 1882): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1882): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1882): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1882): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1882): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1882): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1882): No vision deps
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/PeopleContactsSync( 1882): CP2 sync disabled
W/BaseAppContext( 1882): Using Auth Proxy for data requests.
W/BaseAppContext( 1882): Using Auth Proxy for data requests.
I/dalvikvm( 1882): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1882): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1882): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1882): Using Auth Proxy for data requests.
W/BaseAppContext( 1882): Using Auth Proxy for data requests.
W/BaseAppContext( 1882): Using Auth Proxy for data requests.
W/BaseAppContext( 1882): Using Auth Proxy for data requests.
D/dalvikvm( 1882): GC_CONCURRENT freed 1795K, 22% free 19397K/24832K, paused 6ms+6ms, total 54ms
D/dalvikvm( 1882): WAIT_FOR_CONCURRENT_GC blocked 35ms
D/dalvikvm( 1882): WAIT_FOR_CONCURRENT_GC blocked 36ms
W/GAV2    ( 4691): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  960): Killing 4081:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{434ba668 u0 com.android.settings/.UsbSettings t2}
I/ConfigFetchService( 1882): fetch service done; releasing wakelock
I/ConfigFetchService( 1882): stopping self
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/ChimeraCfgMgr( 1882): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1882): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1882): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Icing   ( 1882): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1882): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
,E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2039): nl80211: survey data missing!
D/WifiStateMachine(  960): handleMessage: X
D/AndroidRuntime( 4749): 
D/AndroidRuntime( 4749): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4749): CheckJNI is OFF
D/dalvikvm( 4749): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4749): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4749): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4749): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4749): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4749): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/memtrack( 4749): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4749): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4749): Calling main entry com.android.commands.am.Am
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4749
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{434ba668 u0 com.android.settings/.UsbSettings t2}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (112 us)
D/ActivityManager(  960): resumeTopActivityLocked: Pausing null
V/ActivityManager(  960): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  960): startService SlideAside
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  960): setFocusedStack: mFocusedStack=ActivityStack{434e01f0 stackId=1, 2 tasks}
D/UsbSettingsControl( 2625): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2625): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4749): Shutting down VM
D/dalvikvm( 4749): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 3ms
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{434ba668 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{434ba668 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Restarting ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  960): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4767 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3784): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+1ms, total 19ms
D/HyLog   ( 4767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4767): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
I/SlideAside( 3784): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3784): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 16ms
V/WebViewChromium( 4767): Binding Chromium to the background looper Looper (main, tid 1) {42ab5e48}
I/chromium( 4767): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4767): Initializing chromium process, renderers=0
W/chromium( 4767): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4767): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4767): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4767): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4767): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4767): Remote Branch: 
I/Adreno-EGL( 4767): Local Patches: 
I/Adreno-EGL( 4767): Reconstruct Branch: 
I/dalvikvm( 4767): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4767): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4767): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4767): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4767): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4767): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4767): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4767): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4767): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4767): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4767): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4767): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4767): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4767): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4767): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4767): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4767): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4767): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4767): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4767): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4767): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4767): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4767): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4767): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4767): Enabling debug mode 0
,W/AwContents( 4767): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  960): IME STATUS OFF
,W/AwContents( 4767): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  960): Displayed com.test.thalitest/.MainActivity: +392ms
,I/ActivityManager( 4767): Timeline: Activity_idle id: android.os.BinderProxy@42ab7708 time:118587
,D/JsMessageQueue( 4767): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4767): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42abb7e8
,D/dalvikvm( 4767): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42abb7e8
,D/jxcore_app_log( 4767): JniHelper::setJavaVM(0x41a62808), pthread_self() = 1637079008
,D/JX-Cordova( 4767): jxcore cordova android initializing
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3} time:118934
D/ActivityManager(  960): no-history finish of ActivityRecord{434ba668 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  960): Finishing activity token=Token{434dadd8 ActivityRecord{434ba668 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  960): Moving to FINISHING: ActivityRecord{434ba668 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{434ba668 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,D/UsbSettings( 2625): [AUTORUN] onStop()
,V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{434ba668 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  960): battery changed pluggedType: 2
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/dalvikvm( 4767): GC_CONCURRENT freed 2803K, 13% free 21850K/24832K, paused 1ms+1ms, total 45ms
,D/dalvikvm( 4767): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 203K, 13% free 21825K/24832K, paused 21ms, total 22ms
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 183K, 12% free 21855K/24832K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 23.655MB for 144892-byte allocation
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 253K, 13% free 21903K/24976K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 23.770MB for 217334-byte allocation
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 369K, 13% free 21977K/25192K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 23.947MB for 325996-byte allocation
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 568K, 14% free 22099K/25512K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 24.221MB for 488990-byte allocation
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 866K, 15% free 22276K/25992K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 24.626MB for 733480-byte allocation
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 1284K, 16% free 22533K/26712K, paused 23ms, total 23ms
,D/dalvikvm( 4767): GC_CONCURRENT freed 1675K, 15% free 22906K/26712K, paused 2ms+1ms, total 29ms
,D/dalvikvm( 4767): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 368K, 15% free 22863K/26712K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 26.074MB for 1650320-byte allocation
,D/dalvikvm( 4767): GC_CONCURRENT freed 1597K, 18% free 23429K/28324K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 1449K, 17% free 23522K/28324K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 27.505MB for 2475476-byte allocation
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 4767): GC_CONCURRENT freed 2009K, 22% free 24199K/30744K, paused 2ms+2ms, total 37ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4767): GC_CONCURRENT freed 2331K, 21% free 24446K/30744K, paused 1ms+7ms, total 56ms
,D/dalvikvm( 4767): WAIT_FOR_CONCURRENT_GC blocked 48ms
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 452K, 21% free 24309K/30744K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 29.454MB for 3713210-byte allocation
,D/dalvikvm( 4767): GC_CONCURRENT freed 288K, 19% free 27918K/34372K, paused 2ms+3ms, total 41ms
D/dalvikvm( 4767): GC_FOR_ALLOC freed 2990K, 27% free 25429K/34372K, paused 23ms, total 26ms
W/jxcore-log( 4767): Initializing JXcore engine
W/jxcore-log( 4767): JXcore engine is ready
D/dalvikvm( 4767): GC_CONCURRENT freed 348K, 19% free 28067K/34372K, paused 1ms+2ms, total 44ms
D/dalvikvm( 4767): WAIT_FOR_CONCURRENT_GC blocked 42ms
W/jxcore-log( 4767): Starting JXcore engine
W/jxcore-log( 4767): Platform android
W/jxcore-log( 4767): 
W/jxcore-log( 4767): Process ARCH arm
W/jxcore-log( 4767): 
D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2039): nl80211: survey data missing!
D/WifiStateMachine(  960): handleMessage: X
E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/jxcore-log( 4767): JXcore Cordova bridge is ready!
I/jxcore-log( 4767): 
W/jxcore-log( 4767): JXcore engine is started
,I/chromium( 4767): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4767): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4767): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GAV2    ( 4691): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1536): onDestroy
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4767): Toggling radios to true
I/jxcore-log( 4767): 
,D/BluetoothManagerService(  960): Message: 20
,D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@449735c0:true
,D/BluetoothAdapter( 4767): enable(): BT is already enabled..!
,D/WifiStateMachine(  960): handleMessage: E msg.what=131145
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doBoolean: DISCONNECT
,I/jxcore-log( 4767): Radios toggled
I/jxcore-log( 4767): 
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2039): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2039): wlan0: Cancelling scan request
D/wpa_supplicant( 2039): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2039): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2039): TDLS: Tear down peers
,D/wpa_supplicant( 2039): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  960): New client listening to asynchronous messages
D/WifiService(  960): setWifiEnabled: true pid=4767, uid=10304
E/WifiService(  960): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  960): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  960): disconnect pid=4767, uid=10304
,D/WifiService(  960): reconnect pid=4767, uid=10304
D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4767): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4767): 
I/jxcore-log( 4767): Perf Test app loaded loaded
I/jxcore-log( 4767): 
I/Choreographer( 4767): Skipped 79 frames!  The application may be doing too much work on its main thread.
D/wpa_supplicant( 2039): wlan0: Event DEAUTH (12) received
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
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8e0bd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
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
D/wpa_supplicant( 2039): nl80211:, Set supplicant port unauthorized for 00:00:00:00:00:00
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
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  960):    returned true
,D/WifiStateMachine(  960): transitionTo: destState=DisconnectingState
,D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
,D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  960): invokeExitMethods: ConnectedState
W/Settings(  960): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  960): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  960): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131146
D/WifiStateMachine(  960): processMsg: DisconnectingState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiNative-wlan0(  960): doBoolean: RECONNECT
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2039): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2039): Fast associate: Old scan results
D/wpa_supplicant( 2039): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2039): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/jxcore-log( 4767): check test folder
I/jxcore-log( 4767): 
D/wpa_supplicant( 2039): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2039): wlan0: nl80211: scan request
,D/wpa_supplicant( 2039): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2039): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2039): nl80211: Event message available
D/wpa_supplicant( 2039): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2039): wlan0: nl80211: Scan trigger
,I/jxcore-log( 4767): found test : ./testFindPeers.js
I/jxcore-log( 4767): 
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147460
,D/WifiStateMachine(  960): processMsg: DisconnectingState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): Network connection lost
D/WifiStateMachine(  960): Stopping DHCP and clearing IP
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  960): doBoolean: SET ps 1
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2039): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2039): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2039): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
,D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  960):    returned true
D/DhcpStateMachine(  960): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  960): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  960): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
,D/WifiHS20(  960): hidePasspointNotification off =false
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
D/QCNEA   (  480): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  480): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  480): |CAC| updateNetCfgInfo
V/QCNEA   (  480): |CAC| *********************************************
V/QCNEA   (  480): |CAC|                   Netconfig               
V/QCNEA   (  480): |CAC| *********************************************
V/QCNEA   (  480): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  480): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  480): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  480): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  480): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  480): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  480): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  480): |CAC| *********************************************
D/QCNEA   (  480): |CAC| Received bssid= 
D/QCNEA   (  480): |CAC| net type = 3
V/QCNEA   (  480): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  480): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  480): |CAC| 	ssid           =NG700
V/QCNEA   (  480): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  480): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  480): |CAC| *********************************************
D/QCNEA   (  480): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  480): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  480): |CAC| dispatchNetCfg: updating:0xb76878dc
D/QCNEA   (  480): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  480): Reading a NULL string not supported here.
,E/Parcel  (  480): Reading a NULL string not supported here.
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/jxcore-log( 4767): found test : ./testSendData.js
I/jxcore-log( 4767): 
,D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiStateMachine(  960): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/QcConnectivityService(  960): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  960): Attempting to switch to mobile
D/QcConnectivityService(  960): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  960): handleConnectivityChange: preConnState=1 connState=2
,D/WifiStateMachine(  960): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  960): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
,D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
,D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): handleMessage: X
,I/ActivityManager(  960): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4826 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
,I/jxcore-log( 4767): found test : ./testSendData2.js
I/jxcore-log( 4767): 
,E/jxcore  ( 4767): Error!: missing ) after argument list
E/jxcore  ( 4767): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/chromium( 4767): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
V/        (  264): RouteController
,D/HyLog   ( 4826): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4826): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4826): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,W/NetworkManagementService(  960): route cmd failed: 
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
,D/NetUtils(  960): android_net_utils_resetConnections in env=0x61f69508 clazz=0x6ab00001 iface=wlan0 mask=0x3
,D/QcConnectivityService(  960): resetConnections(wlan0, 3)
I/PCSuite ( 4826): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
V/NativeCrypto( 1536): Read error: ssl=0x642cdbf8: I/O error during system call, Connection timed out
V/NativeCrypto( 1536): SSL shutdown failed: ssl=0x642cdbf8: I/O error during system call, Broken pipe
,D/PCSuite ( 4826): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4826): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  960): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4862 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  960): Killing 4196:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4862): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4862): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4862): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/LocSvc_java(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
,D/QRemote ( 4862): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4862): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4862): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4862): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4862): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4862): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4862): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4862): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4862): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
,I/ActivityManager(  960): Killing 3164:android.process.media/u0a23 (adj 15): empty #17
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  960): StoppedState
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
,D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): handleMessage: X
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.457642 Y: -0.401779 Z: 9.767990 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457642 .y:-0.401779 .z:9.767990
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.455154 Y: -0.415375 Z: 9.754135 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455154 .y:-0.415375 .z:9.754135
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  960): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Tethering(  960): MasterInitialState.processMessage what=3
D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4058): onReceive
,D/AppUp4:CustFacade( 4058): Context : android.app.ReceiverRestrictedContext@42ac95e0
D/AppUp4:CustFacade( 4058): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4058): isOpenOperator : true
,D/AppUp4:CustFacade( 4058): isPhone : true
,I/LicenseContentProvider( 3015): start selecting data
,D/SIMObserver( 3015): simInfo1
,I/AppUp4:EulaManager( 4058): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4058): begin check event
,I/AppUp4:CustModeStarterReceiver( 4058): Event For GoodConnectivity
,D/wpa_supplicant( 2039): nl80211: Event message available
D/wpa_supplicant( 2039): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2039): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2039): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2039): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 2039): nl80211: Survey data missing
D/wpa_supplicant( 2039): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 2039): wlan0: New scan results available
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2039): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2039): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2039): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2039): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2039): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2039): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2039): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-65 wps
D/wpa_supplicant( 2039): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2039): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2039): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8e0d5a8  current_ssid=0x0
D/wpa_supplicant( 2039): scard is not null..
D/wpa_supplicant( 2039): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=,3): 03 01 01
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2039): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2039): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2039): wlan0: Cancelling scan request
D/wpa_supplicant( 2039): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2039): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2039): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2039): RSN: PMKSA cache search - network_ctx=0xb8e0d5a8 try_opportunistic=0
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
D/wpa_supplicant( 2039): nl80211: Unsubscribe mgmt frames handle 0xb8e0c590 (mode change)
D/wpa_supplicant( 2039): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2039): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2039):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039):   * freq=2412
D/wpa_supplicant( 2039):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2039):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039):   * Auth Type 0
D/wpa_supplicant( 2039):   * WPA Versions 0x2
I/ActivityManager(  960): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4903 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
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
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 a0:c5:62:7a:49:97]
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  960): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  960): handleMessage: E msg.what=147461
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  960): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2039): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2039): nl80211: Event message available
D/wpa_supplicant( 2039): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2039): nl80211: Connect event
D/wpa_supplicant( 2039): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2039): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2039): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2039): wlan0: Association info event
D/wpa_supplicant( 2039): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2039): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
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
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2039): scard is not null..
D/wpa_supplicant( 2039): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2039): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2039): TDLS: Remove peers on association
D/wpa_supplicant( 2039): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2039): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
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
D/WifiMonitor(  960): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  960): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 4903): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4903): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4903): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2039): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 1c 7a b7 16 52 22 35 ff 48 21 cb 5b 21 0e 2b ...
D/wpa_supplicant( 2039): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2039): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2039): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2039): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2039): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2039):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2039):   key_nonce - hexdump(len=32): 1c 7a b7 16 52 22 35 ff 48 21 cb 5b 21 0e 2b c4 29 48 6e da 60 8d de d1 48 99 ec 42 d2 a8 97 0c
D/wpa_supplicant( 2039):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 1c 7a b7 16 52 22 35 ff 48 21 cb 5b 21 0e 2b ...
D/wpa_supplicant( 2039): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2039): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2039): Get randomness: len=32 entropy=7
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/wpa_supplicant( 2039): WPA: Renewed SNonce - hexdump(len=32): da a7 97 8c 40 1a 30 95 f0 23 ad 5f ad 14 a2 77 42 28 07 07 c3 17 90 a8 07 9c 73 51 e1 f0 5f 54
D/wpa_supplicant( 2039): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): WPA: Nonce1 - hexdump(len=32): da a7 97 8c 40 1a 30 95 f0 23 ad 5f ad 14 a2 77 42 28 07 07 c3 17 90 a8 07 9c 73 51 e1 f0 5f 54
D/wpa_supplicant( 2039): WPA: Nonce2 - hexdump(len=32): 1c 7a b7 16 52 22 35 ff 48 21 cb 5b 21 0e 2b c4 29 48 6e da 60 8d de d1 48 99 ec 42 d2 a8 97 0c
D/wpa_supplicant( 2039): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2039): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2039): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2039): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2039): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2039): WPA: Derived Key MIC - hexdump(len=16): d6 9a 50 f0 44 2b 62 c4 fd bb 33 7e 1c cc 9c 78
D/wpa_supplicant( 2039): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 da a7 97 8c 40 1a 30 95 f0 23 ad 5f ad 14 a2 ...
D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
D/wpa_supplicant( 2039): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 1c 7a b7 16 52 22 35 ff 48 21 cb 5b 21 0e 2b ...
D/wpa_supplicant( 2039): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2039): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2039): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2039): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2039):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2039):   key_nonce - hexdump(len=32): 1c 7a b7 16 52 22 35 ff 48 21 cb 5b 21 0e 2b c4 29 48 6e da 60 8d de d1 48 99 ec 42 d2 a8 97 0c
D/wpa_supplicant( 2039):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_rsc - hexdump(len=8): 55 58 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_mic - hexdump(len=16): 2c 5d e7 53 04 95 fb 31 41 80 50 30 1d d0 15 69
D/wpa_supplicant( 2039): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 1c 7a b7 16 52 22 35 ff 48 21 cb 5b 21 0e 2b ...
D/wpa_supplicant( 2039): RSN: encrypted key data - hexdump(len=56): 4a 69 9f af 08 ea 5e 1b 80 25 8b 55 8b 1f 57 c4 f5 2a 7c 96 23 98 a1 15 34 79 21 00 cb 18 c7 88 ...
D/wpa_supplicant( 2039): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2039): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2039): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2039): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 81 f8 ...
D/wpa_supplicant( 2039): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2039): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2039): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2039): WPA: Derived Key MIC - hexdump(len=16): 9a 9c 31 04 1d 30 87 1b c0 65 4a 25 d0 49 12 eb
D/wpa_supplicant( 2039): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2039): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8e0cc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2039):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2039): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2039): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2039): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2039): WPA: RSC - hexdump(len=6): 55 58 00 00 00 00
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f9603a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2039):    broadcast key
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
D/wpa_supplicant( 2039): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2039): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2039): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2039): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2039): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2039): EAPOL authentication completed successfully
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  960): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
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
I/WifiServiceExtension(  960): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  960): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  960): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: DisconnectedState
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
D/WifiStateMachine(  960): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  960): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/DhcpStateMachine(  960): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): ObtainingIpState{ when=-12ms what=147462 obj=android.net.wifi.StateChangeResult@43f8fd20 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  960): WaitBeforeStartState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-8ms what=147462 obj=android.net.wifi.StateChangeResult@43f91250 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-8ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2039): nl80211: survey data missing!
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196612
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,V/DownloadManager( 4903): DownloadService onCreate
D/EAS     ( 4671): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4671): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4903): in removeSpuriousFiles
,D/eas_req ( 4671): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4903): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42af0a10 on behalf of 4903
,V/DownloadManager( 4903): DownloadService onStartCommand
,I/DownloadManager( 4903): in trimDatabase
V/DownloadManager( 4903): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4903): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42af4cd8 on behalf of 4903
,V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42af5458 on behalf of 4903
I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4368): networkInfo.isConnected() = false
,V/DownloadManager( 4903): DownloadService onDestroy
,D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  960): doBoolean: SET ps 0
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2039): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2039): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2039): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4940 uid=10052 gids={50052, 3003}
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
,E/WifiStateMachine(  960): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  960): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  960): DHCP Start wake lock is acquired.
W/linker  ( 4671): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 4671): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4671): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4671): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,D/CommandListener(  264): Setting iface cfg
D/WifiP2pService(  960): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4347b3b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4347b3b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  960): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-5ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196613
I/dalvikvm( 4671): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-5ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
D/HtmlEditor( 4671): register_HtmlEditor, Success
D/HtmlEditor( 4671): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/WifiNative-wlan0(  960): doBoolean: SET ps 1
D/HtmlEditor( 4671): register_HtmlEditorTimer, Success
D/HtmlEditor( 4671): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4671): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4671): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4671): register_HtmlEditorFont, Success
D/HtmlEditor( 4671): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4671): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4671): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4671): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4671): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4671): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4671): JNI_OnLoad Success
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/HyLog   ( 4940): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2039): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2039): CTRL_IFACE SET 'ps'='1'
D/HyLog   ( 4940): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/wpa_supplicant( 2039): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/HyLog   ( 4940): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
I/HubEmail( 4671): JNI_OnLoad()
I/HubEmail( 4671): -- called f,rom 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4671): registerNatives()
I/HubEmail( 4671): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4671): registerNativeMethods()
I/HubEmail( 4671): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,W/Settings( 4671): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
,D/WifiStateMachine(  960): DHCP successful
,D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  960): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  960): VerifyingLinkState enter
,D/WifiStateMachine(  960): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  960): send additional Connectivity Action
,D/WifiStateMachine(  960): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
,E/Parcel  (  480): Reading a NULL string not supported here.
D/WifiStateMachine(  960): handleMessage: E msg.what=135190
D/WifiStateMachine(  960): processMsg: VerifyingLinkState
D/WifiStateMachine(  960): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  960): transitionTo: destState=CaptivePortalCheckState
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  960): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  960): CaptivePortalCheckState enter
,D/WifiStateMachine(  960): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/WifiStateTracker(  960): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  960): 
W/WifiStateTracker(  960):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  960):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  960): handleMessage: X
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  960): handleMessage: E msg.what=131092
D/WifiStateMachine(  960): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  960): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/QcConnectivityService(  960): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
,D/WifiStateMachine(  960): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  960): transitionTo: destState=ConnectedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/ActivityThread(  960): Failed to find provider info for com.lge.ims.provisioning
I/ActivityManager(  960): Killing 3942:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  960): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3}
V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
V/        (  264): RouteController
V/LGRssiData( 4940): [loadRssi] File not exist 
V/LGRssiData( 4940): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4940): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4940): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4940): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4940): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4940): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 4940): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/        (  264): RouteController
D/MobileConnectivityChangeReceiver( 4940): onReceive CONNECTIVITY_CHANGE networkType=1
V/        (  264): RouteController
V/TelephonyAutoProfiling( 4940): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4940): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4940): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
,V/        (  264): RouteController
E/PhoneMonitor( 4940): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4940): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  960): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4967 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  960): Killing 4414:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3}
V/        (  264): RouteController
,D/QCNEA   (  480): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  480): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  480): |CAC| updateNetCfgInfo
V/QCNEA   (  480): |CAC| *********************************************
V/QCNEA   (  480): |CAC|                   Netconfig               
V/QCNEA   (  480): |CAC| *********************************************
V/QCNEA   (  480): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  480): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  480): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  480): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  480): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  480): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  480): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  480): |CAC| *********************************************
D/QCNEA   (  480): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  480): |CAC| net type = 1
V/QCNEA   (  480): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  480): |CAC| Received ssid= NG700
V/QCNEA   (  480): |CAC| 	ssid           =NG700
V/QCNEA   (  480): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  480): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  480): |CAC| *********************************************
D/QCNEA   (  480): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  480): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  480): |CAC| dispatchNetCfg: updating:0xb76878dc
,D/QCNEA   (  480): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/HyLog   ( 4967): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4967): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4967): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,D/DhcpStateMachine(  960): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  960): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/ActivityManager(  960): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4991 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  960): Killing 4596:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4991): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4991): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4991): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  960): Killing 4631:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  960): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5010 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3}
,E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/HyLog   ( 5010): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5010): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5010): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5010): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5010): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  960): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5024 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  960): Killing 4659:com.lge.bnr/1000 (adj 15): empty #17
,D/dalvikvm(  960): GC_EXPLICIT freed 23765K, 49% free 29777K/57564K, paused 4ms+10ms, total 187ms
,I/CheckinService( 1882): Checking schedule, now: 1450736112297 next: 1450736047206
,I/CheckinService( 1882): active receiver: enabled
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5024): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5024): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5024): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1882): Preparing to send checkin request
,I/EventLogService( 1882): Accumulating logs since 1450736014075
,I/NFS     ( 5024): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5024): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5024): intf.getDisplayName() = lo
I/Wireless_Storage( 5024): intf.getDisplayName() = sit0
I/Wireless_Storage( 5024): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5024): intf.getDisplayName() = teql0
I/Wireless_Storage( 5024): intf.getDisplayName() = wlan0
,D/NFS     ( 5024): interface name:wlan0 name:wlan0
D/NFS     ( 5024): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5024): interface name:wlan0 name:wlan0
D/NFS     ( 5024): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 5024): CONNECT : WIFI_CONNECT
,I/CheckinRequestBuilder( 1882): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  960): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5057 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  960): Killing 4246:com.android.contacts/u0a21 (adj 15): empty #17
,E/ActivityThread( 1882): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
,D/HyLog   ( 5057): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5057): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5057): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3}
,W/GAV2    ( 5057): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x42acd978: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1882): awaiting user notification for token
D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  960): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5075 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5075): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5075): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5075): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/WebViewChromium( 5057): Binding Chromium to the main looper Looper (main, tid 1) {42ab4580}
W/dalvikvm( 5075): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5075): VFY: replacing opcode 0x60 at 0x000b
,I/chromium( 5057): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5057): Initializing chromium process, renderers=0
D/dalvikvm( 5075): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5075): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5075): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 5075): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5075): install
,I/MultiDex( 5075): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,W/chromium( 5057): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/MultiDex( 5075): loading existing secondary dex files
,I/MultiDex( 5075): load found 3 secondary dex files
,I/Adreno-EGL( 5057): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5057): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5057): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5057): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5057): Remote Branch: 
I/Adreno-EGL( 5057): Local Patches: 
I/Adreno-EGL( 5057): Reconstruct Branch: 
,I/MultiDex( 5075): install done
,D/dalvikvm( 5075): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5075): VFY: unable to resolve instance field 61
,D/dalvikvm( 5075): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5075): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5075): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5075): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5075): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5075): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5075): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5075): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5075): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5075): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42abb738
,D/dalvikvm( 5075): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42abb738
,D/dalvikvm( 5075): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42abb738, skipping init
D/dalvikvm( 5075): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42abb738
D/dalvikvm( 5075): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42abb738
,V/JNIHelp ( 5075): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 5057): Starting up...
,D/DhcpStateMachine(  960): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  960): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  960): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  960): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  960): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  960): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  960): RunningState
I/ActivityManager(  960): Killing 4262:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4862): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4862): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/dalvikvm( 5075): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42abb738
,D/dalvikvm( 5075): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42abb738
D/dalvikvm( 5075): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42abb738
,D/dalvikvm( 5075): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42abb738
,D/QRemote ( 4862): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4862): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4862): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4862): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4826): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4826): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4862): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4862): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4862): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4862): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ProviderInstaller( 5075): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1536): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1536): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1882): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1752): callingUid 10006, callindPid: 1752
,E/MDM     ( 1423): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1882): Restart initialization of location
I/dalvikvm( 5075): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5075): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5075): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5075): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5075): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5075): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fee000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fee000
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
I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=1796753641
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2039): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2039): EAPOL: disable timer tick
,D/GCM     ( 1536): Connected
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1536): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 5075): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c86940
,D/dalvikvm( 5075): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c86940
,D/dalvikvm( 5075): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c86940, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  960): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  960): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): handleMessage: X
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  960): send additional Connectivity Action
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  960): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  960):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  960): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  960): battery changed pluggedType: 2
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=195264503
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 5075): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5123): DexOpt: load 3ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 5075): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5075): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 76ms
,I/Adreno-EGL( 5075): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5075): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5075): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5075): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5075): Remote Branch: 
I/Adreno-EGL( 5075): Local Patches: 
I/Adreno-EGL( 5075): Reconstruct Branch: 
I/dalvikvm( 4767): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4767): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4767): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4767): Shutting down VM
,W/dalvikvm( 4767): threadid=1: thread exiting with uncaught exception (group=0x41a73e48)
E/AndroidRuntime( 4767): FATAL EXCEPTION: main
E/AndroidRuntime( 4767): Process: com.test.thalitest, PID: 4767
E/AndroidRuntime( 4767): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4767): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4767): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4767): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4767): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4767): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4767): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4767): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4767): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4767): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4767): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4767): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4767): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4767): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4767): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4767): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4767): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4767): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4767): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  960):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3 f}
,W/Settings( 5075): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 5075): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5075): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5075): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5075): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5075): Remote Branch: 
I/Adreno-EGL( 5075): Local Patches: 
I/Adreno-EGL( 5075): Reconstruct Branch: 
,I/Adreno-EGL( 5075): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5075): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5075): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5075): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5075): Remote Branch: 
I/Adreno-EGL( 5075): Local Patches: 
I/Adreno-EGL( 5075): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1882): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1882): Sending checkin request (11457 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  960): Activity pause timeout for ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e01f0 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  960): moveHomeStack:
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  960): resumeTopActivityLocked: Resumed ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1488): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1488): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1488): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1488): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1830): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 23:15:14
,D/UpdateThreadPoolManager( 1830): 2 : This is isUpdating : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiController(  960): battery changed pluggedType: 2
,D/WeatherQuickCover( 1830): 2 : quick cover state : opened : 0
D/WeatherService( 1830): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1830): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1830): 2 : shouldTimeTickRegistered().........
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,W/ContextImpl( 1830): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WeatherService( 1830): 2 : TimeTick Receiver Register
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherAncestor( 1830): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 23:15:14
D/WeatherService( 1830): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1830): 2 : quick cover state : opened : 0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/Weather.Utils( 1830): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WeatherService( 1830): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1830): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1830): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1830): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/WifiController(  960): battery changed pluggedType: 2
D/UpdateThreadPoolManager( 1830): 2 : This is isUpdating : false
D/WeatherService( 1830): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1830): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1830): 2 : Map key string is -2
D/lim     ( 1830): 2 : time = 23:15
I/WeatherReflect( 1830): Model Name : LG-D802
D/WeatherTheme( 1830): 2 : Different view - status_min_formatted : 13 != 15
D/WeatherTheme( 1830): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1830): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1830): 2 : Fixed theme : optimus
D/WeatherTheme( 1830): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1830): 2 : quick cover state : opened : 0
D/Weather.Utils( 1830): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1830): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1830): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinRequestBuilder( 1882): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1882): Failed to find provider info for com.google.android.wearable.settings
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/dalvikvm( 1140): GC_CONCURRENT freed 7640K, 10% free 70800K/78656K, paused 1ms+4ms, total 32ms
,D/dalvikvm( 1140): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 1488): GC_CONCURRENT freed 5343K, 9% free 60769K/66324K, paused 3ms+4ms, total 36ms
,D/dalvikvm( 1488): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/dalvikvm( 1536): GC_EXPLICIT freed 809K, 29% free 17858K/24832K, paused 1ms+6ms, total 37ms
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,D/dalvikvm(  960): GC_FOR_ALLOC freed 2298K, 47% free 30732K/57564K, paused 122ms, total 124ms
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x44050640: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,W/CheckinRequestBuilder( 1882): awaiting user notification for token
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/CheckinRequestBuilder( 1882): Classify the device as Phone.
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,D/dalvikvm( 1882): GC_CONCURRENT freed 1827K, 22% free 19529K/24832K, paused 3ms+3ms, total 54ms
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1} time:128734
,D/dalvikvm(  960): GC_CONCURRENT freed 571K, 48% free 30435K/57564K, paused 3ms+7ms, total 96ms
,I/CheckinTask( 1882): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1882): Checking schedule, now: 1450736114675 next: 1451313510672
,I/CheckinService( 1882): active receiver: disabled
,D/dalvikvm( 1488): GC_FOR_ALLOC freed 5020K, 9% free 62062K/67784K, paused 18ms, total 18ms
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager( 1488): Timeline: Activity_idle id: android.os.BinderProxy@42ab1470 time:128843
,D/UsbSettings( 2625): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2625): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2625): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2625): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  960): Moving to FINISHING: ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  960): Moving to DESTROYING: ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
V/ActivityManager(  960): Moving to DESTROYING: ActivityRecord{434ba668 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{434ba668 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1}
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
E/Parcel  (  480): Reading a NULL string not supported here.
,E/Parcel  (  480): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4058): onReceive
,D/AppUp4:CustFacade( 4058): Context : android.app.ReceiverRestrictedContext@42ac95e0
D/AppUp4:CustFacade( 4058): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4058): isOpenOperator : true
D/AppUp4:CustFacade( 4058): isPhone : true
I/LicenseContentProvider( 3015): start selecting data
D/SIMObserver( 3015): simInfo1
I/AppUp4:EulaManager( 4058): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4058): begin check event
I/AppUp4:CustModeStarterReceiver( 4058): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4058): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4058): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4058): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4058): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4058): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4903): DownloadService onCreate
,I/DownloadManager( 4903): in removeSpuriousFiles
V/DownloadManager( 4903): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4671): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4671): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42afbcd8 on behalf of 4903
,D/eas_req ( 4671): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4903): in trimDatabase
,V/DownloadManager( 4903): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4903): DownloadService onStartCommand
V/DownloadManager( 4903): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42afd260 on behalf of 4903
,V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42afee60 on behalf of 4903
I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4368): networkInfo.isConnected() = false
,W/Settings( 4671): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4940): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4940): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4903): DownloadService onDestroy
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5010): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5024): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5024): CONNECT : WIFI_CONNECT
,W/ContextImpl( 5010): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4058): onReceive
,D/AppUp4:CustFacade( 4058): Context : android.app.ReceiverRestrictedContext@42ac95e0
D/AppUp4:CustFacade( 4058): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4058): isOpenOperator : true
,D/AppUp4:CustFacade( 4058): isPhone : true
I/LicenseContentProvider( 3015): start selecting data
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/SIMObserver( 3015): simInfo1
,I/AppUp4:EulaManager( 4058): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4058): begin check event
,I/AppUp4:CustModeStarterReceiver( 4058): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4903): DownloadService onCreate
,D/EAS     ( 4671): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4671): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4903): in removeSpuriousFiles
,V/DownloadManager( 4903): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4903): DownloadService onStartCommand
,V/DownloadManager( 4903): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42b05808 on behalf of 4903
,V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42b055f0 on behalf of 4903
I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4368): networkInfo.isConnected() = true
,D/PhoneState( 4368): setPdpRejectCasuse : false
I/DownloadManager( 4903): in trimDatabase
,V/DownloadManager( 4903): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,W/Settings( 4671): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4940): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4940): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42b06d30 on behalf of 4903
,V/DownloadManager( 4903): DownloadService onDestroy
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5010): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 5010): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5024): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5024): CONNECT : WIFI_CONNECT
E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/WifiController(  960): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,D/WifiController(  960): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1461): GC_CONCURRENT freed 1538K, 7% free 25440K/27280K, paused 3ms+2ms, total 42ms
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1488): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] request level :IDLE....
D/WifiController(  960): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/AppUp4:CustModeStarterReceiver( 4058): onReceive
D/AppUp4:CustFacade( 4058): Context : android.app.ReceiverRestrictedContext@42ac95e0
D/AppUp4:CustFacade( 4058): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4058): isOpenOperator : true
D/AppUp4:CustFacade( 4058): isPhone : true
I/LicenseContentProvider( 3015): start selecting data
D/SIMObserver( 3015): simInfo1
I/AppUp4:EulaManager( 4058): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4058): begin check event
I/AppUp4:CustModeStarterReceiver( 4058): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/DownloadManager( 4903): DownloadService onCreate
D/EAS     ( 4671): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4671): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4903): in removeSpuriousFiles
V/DownloadManager( 4903): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42b0b088 on behalf of 4903
I/DownloadManager( 4903): in trimDatabase
V/DownloadManager( 4903): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42b0c158 on behalf of 4903
V/DownloadManager( 4903): DownloadService onStartCommand
I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4368): networkInfo.isConnected() = true
V/DownloadManager( 4903): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/PhoneState( 4368): setPdpRejectCasuse : false
V/DownloadManager( 4903): created cursor android.database.sqlite.SQLiteCursor@42b0ebf0 on behalf of 4903
D/MobileConnectivityChangeReceiver( 4940): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4940): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4671): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4903): DownloadService onDestroy
D/LGDMSGCM( 5010): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 5010): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 5024): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5024): CONNECT : WIFI_CONNECT
E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,D/WifiController(  960): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  960): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 5057): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4279): [399] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4279): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  960): Killing 4691:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  960): Killing 4826:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1}
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3784): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3784): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
D/administrator(  960): Handling package changes for user 0
,I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5267 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 3ms+11ms, total 64ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
,I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+2ms, total 38ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,D/HyLog   ( 5267): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5267): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5267): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5267): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5267): MmsConfig.loadMmsSettings
,I/Babel   ( 5267): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5267): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5267): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5267): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5267): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5267): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5267): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5267): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5267): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5267): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/Settings( 5267): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 5267): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5267): MmsConfig.loadFromResources
,E/Babel   ( 5267): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5267): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5267): [loadRssi] File not exist 
V/LGRssiData( 5267): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5267): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5267): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5267): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
D/AppUp4:Utils( 4058): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4058): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
V/TelephonyAutoProfiling( 5267): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4  ( 4058): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4058): onReceive
D/AppUp4:CustFacade( 4058): Context : android.app.ReceiverRestrictedContext@42ac95e0
D/AppUp4:CustFacade( 4058): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4058): isOpenOperator : true
,D/AppUp4:CustFacade( 4058): isPhone : true
,I/LicenseContentProvider( 3015): start selecting data
,D/SIMObserver( 3015): simInfo1
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/AppUp4:EulaManager( 4058): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4058): begin check event
D/AppUp4:Utils( 4058): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4058): Event For Nothing, skip.
,I/ActivityManager(  960): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5317 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,V/GmsNetworkLocationProvi( 1423): DISABLE
,I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/HyLog   ( 5317): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5317): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5317): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5317): BUILD Country: EU
,I/SystemConfig( 5317): BUILD Operator: OPEN
,I/ActivityManager(  960): Killing 4862:com.lge.qremote/u0a96 (adj 15): empty #17
I/SystemConfig( 5317): systemFeature RCS result false
D/SystemConfig( 5317): refreshRcsSupport() :false
,I/ActivityManager(  960): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5332 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 5332): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5332): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5332): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  960): Killing 4767:com.test.thalitest/u0a304 (adj 15): empty #17
,I/WindowState(  960): WIN DEATH: Window{43f79040 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  960): Client connection lost with reason: 4
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{450bcf28 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
,I/[LGHome]EVENT( 1488): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,W/Binder  ( 1314): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1314): java.lang.NullPointerException
W/Binder  ( 1314): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1314): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1314): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1314): 	at dalvik.system.NativeStart.run(Native Method)
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1}
I/InputMethodManagerService(  960): IME STATUS OFF
W/InputMethodManagerService(  960): Got RemoteException sending setActive(false) notification to pid 4767 uid 10304
,I/IcingCorporaProvider( 2693): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  960): Killing 4903:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1882): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1882): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  960): Delaying start of: ServiceRecord{44039fc0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
D/LocationProviderProxy(  960): applying state to connected service
D/LocationProviderProxy(  960): applying state to connected service
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1211): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Icing   ( 1882): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/IcingCorporaProvider( 2693): UpdateCorporaTask done [took 200 ms] updated apps [took 200 ms] 
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PowerManagerService(  960): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  960): [updateScreenState] screen on = false
D/KnockOnPowerController(  960): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  960): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  960): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  960): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  960): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  960): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9429 usec
D/KnockOnPowerController(  960): [setProximitySensorEnabled] enable = true
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
D/qcom_sensors_hal(  960): hal_acquire_resources
I/qcom_sensors_hal(  960): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  960): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
I/qcom_sensors_hal(  960): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.459335 Y: -0.389282 Z: 9.778214 
D/qcom_sensors_hal(  960): hal_sam_algo_activate: Update freq 0 -> 20
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459335 .y:-0.389282 .z:9.778214
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,I/qcom_sensors_hal(  960): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  960): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.463608 Y: -0.398697 Z: 9.768845 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463608 .y:-0.398697 .z:9.768845
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,I/Sensors (  458): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  960): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  960): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  960): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
D/KnockOnPowerController(  960): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  960): proximitySensorChanged  positive = true
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.459564 Y: -0.408615 Z: 9.779556 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459564 .y:-0.408615 .z:9.779556
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
I/KnockOnPowerController(  960): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.439514 Y: -0.401474 Z: 9.775986 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.439514 .y:-0.401474 .z:9.775986
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.443466 Y: -0.396179 Z: 9.774780 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443466 .y:-0.396179 .z:9.774780
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.453339 Y: -0.391251 Z: 9.786499 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453339 .y:-0.391251 .z:9.786499
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.459488 Y: -0.394638 Z: 9.784134 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459488 .y:-0.394638 .z:9.784134
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  960): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4460d680)
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1140): notifyScreenOnLocked
D/KeyguardViewMediator( 1140): handleNotifyScreenOn
,D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  960): **** SHOWN CALLED ****
D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb71a1450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
I/WindowManager(  960): No lock screen! windowToken=null
,D/WifiStateMachine(  960): handleScreenStateChanged: true
,E/SlideAside( 3784): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/WifiStateMachine(  960): handleMessage: E msg.what=131154
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2039): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  960): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2039): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131127
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=131158
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=132097
D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  960): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2039): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2039): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  960): handleMessage: X
,D/WifiOffDelayIfNotUsed(  960): stopMonitoring
,E/AudioSystem(  960): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 960
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,D/WeatherAncestor( 1830): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 23:15:24
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43543e40 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,I/SlideAside( 3784): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1830): 2 : This is isUpdating : false
,D/WeatherAncestor( 1830): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 23:15:24
,D/WeatherService( 1830): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/WeatherService( 1830): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1830): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1830): 2 : shouldTimeTickRegistered : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.450150 Y: -0.414383 Z: 9.759583 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450150 .y:-0.414383 .z:9.759583
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
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
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.449280 Y: -0.400681 Z: 9.773117 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449280 .y:-0.400681 .z:9.773117
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
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
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  960): Excessive delay in blankDisplay() while turning screen off: 421ms
,D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736124725, nextTick: 35308, mDrawingTime: 0
,D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736124744, nextTick: 35289, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
D/WeatherService( 1830): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:15:24
,D/WeatherService( 1830): 2 : ACTION screen on
,D/WeatherService( 1830): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1830): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:15:24
,D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_ON
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  960): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  960): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : trf_based_vzw, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
,I/[LGHome]EVENT( 1488): [Launcher.java:894:onPause()]onPause
D/GsmSST  ( 1448): Emergency Service
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  960): hal_acquire_resources
D/qcom_sensors_hal(  960): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  960): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=1000
D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  960): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  960): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  960): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
,I/LGImmersionVibrator(  960): Vibrator off
,D/WifiStateMachine(  960): handleScreenStateChanged: false
D/WifiStateMachine(  960): handleMessage: E msg.what=131154
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
I/[LGHome]EVENT( 1488): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  960): handleMessage: E msg.what=131158
D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): processMsg: ConnectModeState
D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  960): doBoolean: DRIVER SETSUSPENDMODE 1
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
E/AudioSystem(  960): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 960
V/SRS_Proc(  270): ParamSet string: screen_state=off
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  960):    returned true
,D/WifiStateMachine(  960): handleMessage: X
V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{4332b1e0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  960): CMD_SCREEN_OFF 
D/WifiController(  960): shouldWifiStayAwake TRUE
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1154): clear
D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
,D/KeyguardViewMediator( 1140): handleNotifyScreenOff
,D/KeyguardViewManager( 1140): onScreenTurnedOff()
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
,I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
D/WeatherService( 1830): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:15:24
,D/WeatherService( 1830): 2 : ACTION screen off
,D/WeatherService( 1830): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:15:24
,D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
,E/Parcel  (  480): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
,D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_OFF
,D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/NfcService( 1473): NFC-C OFF
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
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=2
D/qdlights( 1154): set_light_notifications: 1,ff00ff00,500,2000,1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/CaptivePortalTracker(  960): Checking http://216.58.209.46/generate_204
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/CaptivePortalTracker(  960): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  960): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  960): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  960): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  458): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
,I/GAV4    ( 5267): Thread[GAThread,5,main]: No campaign data found.
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736142714857995; DSPS: 5276672; Offset: 1450735981683607995
,I/GoogleURLConnFactory( 1536): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1536): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1536):  no longer exists, so no auth token.
,W/Uploader( 1536): No account for auth token provided
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736160034, nextTick: 59998, mDrawingTime: 0
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736160036, nextTick: 59997, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736162718185674; DSPS: 5932141; Offset: 1450735981683609258
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736182724075314; DSPS: 6587693; Offset: 1450735981683639523
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736202729315157; DSPS: 7243225; Offset: 1450735981683630343
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736220036, nextTick: 59985, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736220045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736222733578670; DSPS: 7898725; Offset: 1450735981683621395
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736242742549971; DSPS: 8554379; Offset: 1450735981683620528
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736262746240011; DSPS: 9209860; Offset: 1450735981683617941
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  960): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736280057, nextTick: 59974, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736280057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736282753887293; DSPS: 9865470; Offset: 1450735981683635829
,D/wpa_supplicant( 2039): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 3 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:97]
,D/wpa_supplicant( 2039): wlan0: BSS: Remove id 2 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 06:7c:34:12:7f:81]
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736302756174367; DSPS: 10520905; Offset: 1450735981683634084
,D/dalvikvm( 2680): GC_CONCURRENT freed 7762K, 32% free 16891K/24832K, paused 3ms+2ms, total 49ms
,D/dalvikvm( 2680): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm(  960): GC_EXPLICIT freed 2444K, 47% free 30726K/57564K, paused 3ms+9ms, total 116ms
,I/ActivityManager(  960): Killing 4671:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x4529aea0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1536): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1536): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 4279): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4279): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4279): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4279): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4279): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4279): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4279): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4279): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4279): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4279): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736322760990437; DSPS: 11176423; Offset: 1450735981683628377
,I/LocationManagerService(  960): remove 43690410
,D/LocationManagerService(  960): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  960): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  960): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  960): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  960): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2680): GC_CONCURRENT freed 1874K, 32% free 17002K/24832K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 2680): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2680): GC_CONCURRENT freed 1771K, 31% free 17278K/24832K, paused 3ms+1ms, total 28ms
,D/dalvikvm( 2680): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2680): GC_FOR_ALLOC freed 1611K, 30% free 17480K/24832K, paused 20ms, total 20ms
,I/Mlt MonitorService( 2680): parseLastkmsg to dump
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736340042, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736340049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736342766497958; DSPS: 11831964; Offset: 1450735981683612216
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736362772442664; DSPS: 12487519; Offset: 1450735981683605995
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736382778076265; DSPS: 13143063; Offset: 1450735981683624361
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736400058, nextTick: 59970, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736400063, nextTick: 59969, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736402784145502; DSPS: 13798622; Offset: 1450735981683620600
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736422790375132; DSPS: 14454186; Offset: 1450735981683624644
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736442793817579; DSPS: 15109659; Offset: 1450735981683618605
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736460056, nextTick: 59973, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736460059, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736462804710208; DSPS: 15765376; Offset: 1450735981683616458
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736482809408974; DSPS: 16420890; Offset: 1450735981683615517
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736502813501767; DSPS: 17076384; Offset: 1450735981683618955
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736520039, nextTick: 59965, mDrawingTime: 10
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736520058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736522819630744; DSPS: 17731945; Offset: 1450735981683613899
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736542824863052; DSPS: 18387476; Offset: 1450735981683627701
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736562829394659; DSPS: 19042985; Offset: 1450735981683612189
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736580035, nextTick: 59983, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736580048, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736582832038614; DSPS: 19698431; Offset: 1450735981683631632
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736602837532788; DSPS: 20353971; Offset: 1450735981683632642
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736622843686980; DSPS: 21009533; Offset: 1450735981683622283
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736640032, nextTick: 59994, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736640034, nextTick: 59997, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736642849746267; DSPS: 21665091; Offset: 1450735981683639090
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736662853215121; DSPS: 22320565; Offset: 1450735981683628940
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736682860811258; DSPS: 22976174; Offset: 1450735981683626200
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736700037, nextTick: 59967, mDrawingTime: 11
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736700056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736702863755477; DSPS: 23631631; Offset: 1450735981683610214
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736722872368993; DSPS: 24287273; Offset: 1450735981683617773
,D/wpa_supplicant( 2039): nl80211: Event message available
D/wpa_supplicant( 2039): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2039): nl80211: Disconnect event
D/wpa_supplicant( 2039): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2039): wlan0: Deauthentication notification
D/wpa_supplicant( 2039): wlan0:  * reason 0
D/wpa_supplicant( 2039): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2039): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2039): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2039): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2039): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2039): wlan0: Setting scan request: 0 sec 100000 usec
,D/wpa_supplicant( 2039): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
D/wpa_supplicant( 2039): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2039): wlan0: Disconnect event - remove keys,
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  960): handleMessage: E msg.what=147460,
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState,
D/WifiStateMachine(  960): processMsg: ConnectModeState,
D/WifiStateMachine(  960): Network connection lost
D/WifiStateMachine(  960): Stopping DHCP and clearing IP,
,D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  960): doBoolean: SET ps 1,
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8e0bd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2039):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2039): wlan0: State: COMPLETED -> DISCONNECTED,
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2039): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 2039): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2039): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2039): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2039): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2039): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  960):    returned true
,D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  960):    returned true
,D/DhcpStateMachine(  960): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  960): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  960): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  960): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/wpa_supplicant( 2039): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2039): wlan0: nl80211: scan request
,D/wpa_supplicant( 2039): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2039): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2039): nl80211: Event message available
D/wpa_supplicant( 2039): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2039): wlan0: nl80211: Scan trigger
,D/WifiHS20(  960): hidePasspointNotification off =false
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,D/QcConnectivityService(  960): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
D/QCNEA   (  480): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  480): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  480): |CAC| updateNetCfgInfo
V/QCNEA   (  480): |CAC| *********************************************
V/QCNEA   (  480): |CAC|                   Netconfig               
V/QCNEA   (  480): |CAC| *********************************************
V/QCNEA   (  480): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  480): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  480): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  480): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  480): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  480): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  480): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  480): |CAC| *********************************************
D/QCNEA   (  480): |CAC| Received bssid= 
D/QCNEA   (  480): |CAC| net type = 3
V/QCNEA   (  480): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  480): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  480): |CAC| 	ssid           =NG700
V/QCNEA   (  480): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  480): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  480): |CAC| *********************************************
D/QCNEA   (  480): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  480): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  480): |CAC| dispatchNetCfg: updating:0xb76878dc
D/QCNEA   (  480): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  480): Reading a NULL string not supported here.
,E/Parcel  (  480): Reading a NULL string not supported here.
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QcConnectivityService(  960): Attempting to switch to mobile
D/QcConnectivityService(  960): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  960): handleConnectivityChange: preConnState=1 connState=2
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  960): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: ConnectedState
D/WifiStateMachine(  960): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  960): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
,D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
,D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  960): handleMessage: X
,D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
I/ActivityManager(  960): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6001 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/HyLog   ( 6001): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6001): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6001): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,W/NetworkManagementService(  960): route cmd failed: 
W/NetworkManagementService(  960): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,D/NetUtils(  960): android_net_utils_resetConnections in env=0x61f69508 clazz=0xb9d00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  960): resetConnections(wlan0, 3)
,I/EventLogService( 1882): Aggregate from 1450736112330 (log), 1450734559187 (data)
,V/NativeCrypto( 1536): Read error: ssl=0x642cdbf8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1536): SSL shutdown failed: ssl=0x642cdbf8: I/O error during system call, Broken pipe
,I/PCSuite ( 6001): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6001): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6001): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  960): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6040 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/DhcpStateMachine(  960): StoppedState
D/HyLog   ( 6040): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6040): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6040): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 6040): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6040): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 6040): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6040): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 6040): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6040): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6040): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6040): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6040): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  960): Killing 4940:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  960): Killing 4967:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2039): nl80211: Event message available
D/wpa_supplicant( 2039): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2039): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2039): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2039): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 2039): nl80211: Survey data missing
D/wpa_supplicant( 2039): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 6 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 7 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 8 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 9 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 10 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Add new id 11 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 2039): wlan0: New scan results available
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2039): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2039): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2039): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2039): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2039): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2039): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2039): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2039): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2039): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2039): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-62 wps
D/wpa_supplicant( 2039): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2039): wlan0: 2: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-83
D/wpa_supplicant( 2039): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2039): wlan0: 3: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len,=20 caps=0x1111 level=-89 wps
D/wpa_supplicant( 2039): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2039): wlan0: 4: 10:9a:dd:8e:22:d9 ssid='Apple AirPort' wpa_ie_len=0 rsn_ie_len=20 caps=0x1431 level=-86
D/wpa_supplicant( 2039): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2039): wlan0: 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-89 wps
D/wpa_supplicant( 2039): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2039): wlan0: 6: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 caps=0x1411 level=-89 wps
D/wpa_supplicant( 2039): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2039): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2039): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2039): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2039): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2039): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2039): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-62 wps
,D/wpa_supplicant( 2039): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2039): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2039): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8e0d5a8  current_ssid=0x0
D/wpa_supplicant( 2039): scard is not null..
D/wpa_supplicant( 2039): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
,D/wpa_supplicant( 2039): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2039): wlan0: [MDM] lg_mdm_auto_connect_policy 0
,D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30,
,D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01,
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00,
D/wpa_supplicant( 2039): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2039): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 2039): wlan0: Cancelling scan request
D/wpa_supplicant( 2039): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2039): wlan0: WPA: clearing own WPA/RSN IE,
D/wpa_supplicant( 2039): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2039): RSN: PMKSA cache search - network_ctx=0xb8e0d5a8 try_opportunistic=0
D/wpa_supplicant( 2039): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): RSN: No PMKSA cache entry found
,D/wpa_supplicant( 2039): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2039): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2039): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2039): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2039): wlan0: WPA: using PTK CCMP,
D/wpa_supplicant( 2039): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2039): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
,D/wpa_supplicant( 2039): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2039): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2039): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2039): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2039): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0),
D/wpa_supplicant( 2039): nl80211: Set mode ifindex 23 iftype 2 (STATION),
D/wpa_supplicant( 2039): nl80211: Unsubscribe mgmt frames handle 0xb8e0c590 (mode change)
D/wpa_supplicant( 2039): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8e0c590,
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0d,
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
,D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09,
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 04 0e,
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 0a 07,
D/wpa_supplicant( 2039): nl80211: Register frame type=0xd0 nl_handle=0xb8e0c590
D/wpa_supplicant( 2039): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2039): nl80211: Connect (ifindex=23),
D/wpa_supplicant( 2039):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039):   * freq=2412
D/wpa_supplicant( 2039):   * SSID - hexdump(len=5): 4e 47 37 30 30,
D/wpa_supplicant( 2039):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039):   * Auth Type 0
D/wpa_supplicant( 2039):   * WPA Versions 0x2
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 06:7c:34:12:7f:81],
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 a0:c5:62:7a:49:97]
D/wpa_supplicant( 2039): nl80211: Connect request send successfully
D/wpa_supplicant( 2039): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2039): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2039): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): EAPOL: External notification - portControl=Auto,
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 10:9a:dd:8e:22:d9]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 64:7c:34:12:7f:81]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 a0:c5:62:7a:49:96]
D/WifiStateMachine(  960): handleMessage: E msg.what=147461
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  960): doString: BSS RANGE=0- MASK=0x21987
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  960): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=],
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2039): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987',
,D/wpa_supplicant( 2039): nl80211: Event message available,
D/wpa_supplicant( 2039): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2039): nl80211: Connect event
D/wpa_supplicant( 2039): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2039): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
,D/wpa_supplicant( 2039): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2039): wlan0: Association info event
D/wpa_supplicant( 2039): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2039): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00,
D/wpa_supplicant( 2039): wlan0: freq=2412 MHz
D/wpa_supplicant( 2039): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2039): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2039): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2039): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): wlan0: No keys have been configured - skip key clearing,
D/wpa_supplicant( 2039): wlan0: WPA: clearing AP WPA IE,
D/wpa_supplicant( 2039): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2039): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): scard is not null..
,D/wpa_supplicant( 2039): wlan0: WPA: Association event - clear replay counter
,D/wpa_supplicant( 2039): wlan0: WPA: Clear old PTK,
D/wpa_supplicant( 2039): TDLS: Remove peers on association
D/wpa_supplicant( 2039): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): EAPOL: External notification - portValid=0,
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2039): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2039): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2039): EAPOL: SUPP_PAE entering state CONNECTING,
,D/wpa_supplicant( 2039): EAPOL: enable timer tick,
D/wpa_supplicant( 2039): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2039): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2039): wlan0: Cancelling scan request
D/wpa_supplicant( 2039): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event,
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700],
D/wpa_supplicant( 2039): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 f4 8b 54 d6 57 1e 35 0c ca 4a 5f e5 80 ee 38 ...
D/wpa_supplicant( 2039): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2039): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2039): wlan0:   EAPOL-Key type=2
,D/wpa_supplicant( 2039): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2039): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2039):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2039):   key_nonce - hexdump(len=32): f4 8b 54 d6 57 1e 35 0c ca 4a 5f e5 80 ee 38 3a d2 c4 3b 56 02 8e d2 45 61 62 f6 40 68 6a 77 1a
D/wpa_supplicant( 2039):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00,
D/wpa_supplicant( 2039):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 f4 8b 54 d6 57 1e 35 0c ca 4a 5f e5 80 ee 38 ...,
,D/wpa_supplicant( 2039): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2039): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2039): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2039): Get randomness: len=32 entropy=8
D/wpa_supplicant( 2039): WPA: Renewed SNonce - hexdump(len=32): 92 78 85 a4 5d 6f e6 58 81 50 d1 f5 e7 71 b1 24 b0 d4 08 98 bf c6 a6 26 8a bf e0 13 02 8a db 60
D/wpa_supplicant( 2039): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48,
,D/wpa_supplicant( 2039): WPA: Nonce1 - hexdump(len=32): 92 78 85 a4 5d 6f e6 58 81 50 d1 f5 e7 71 b1 24 b0 d4 08 98 bf c6 a6 26 8a bf e0 13 02 8a db 60,
,D/wpa_supplicant( 2039): WPA: Nonce2 - hexdump(len=32): f4 8b 54 d6 57 1e 35 0c ca 4a 5f e5 80 ee 38 3a d2 c4 3b 56 02 8e d2 45 61 62 f6 40 68 6a 77 1a
D/wpa_supplicant( 2039): WPA: PMK - hexdump(len=32): [REMOVED],
D/wpa_supplicant( 2039): WPA: PTK - hexdump(len=48): [REMOVED],
D/wpa_supplicant( 2039): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2039): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2039): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2039): WPA: KCK - hexdump(len=16): [REMOVED],
,D/wpa_supplicant( 2039): WPA: Derived Key MIC - hexdump(len=16): df e5 c2 a0 5e ef 58 94 01 68 d2 99 13 a4 b7 16
D/wpa_supplicant( 2039): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 92 78 85 a4 5d 6f e6 58 81 50 d1 f5 e7 71 b1 ...
D/wpa_supplicant( 2039): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 f4 8b 54 d6 57 1e 35 0c ca 4a 5f e5 80 ee 38 ...,
,D/wpa_supplicant( 2039): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2039): wlan0:   EAPOL-Key type=2,
D/wpa_supplicant( 2039): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
,D/wpa_supplicant( 2039): wlan0:   key_length=16 key_data_length=56,
D/wpa_supplicant( 2039):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2039):   key_nonce - hexdump(len=32): f4 8b 54 d6 57 1e 35 0c ca 4a 5f e5 80 ee 38 3a d2 c4 3b 56 02 8e d2 45 61 62 f6 40 68 6a 77 1a
D/wpa_supplicant( 2039):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_rsc - hexdump(len=8): 04 5a 00 00 00 00 00 00
D/wpa_supplicant( 2039):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 2039):   key_mic - hexdump(len=16): 73 96 86 90 e8 75 c3 7d 0b b7 18 c7 78 d3 46 72
D/wpa_supplicant( 2039): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 f4 8b 54 d6 57 1e 35 0c ca 4a 5f e5 80 ee 38 ...,
D/wpa_supplicant( 2039): RSN: encrypted key data - hexdump(len=56): 0d 14 c7 c3 71 d3 81 c9 2e 11 17 58 ec 23 cd 83 c6 02 ec 0c 41 f0 b4 57 67 b1 ad 8f 91 90 1f 6c ...
D/wpa_supplicant( 2039): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2039): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2039): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2039): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 81 f8 ...
D/wpa_supplicant( 2039): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
,D/wpa_supplicant( 2039): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2039): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2039): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2039): WPA: Derived Key MIC - hexdump(len=16): e3 b7 d7 a5 49 6c d8 9f b0 02 8e 95 6a b3 32 bc
D/wpa_supplicant( 2039): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2039): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8e0cc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2039):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): EAPOL: External notification - portValid=1,
D/wpa_supplicant( 2039): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED],
D/wpa_supplicant( 2039): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2039): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2039): WPA: RSC - hexdump(len=6): 04 5a 00 00 00 00
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f9603a key_idx=2 set_tx=0 seq_len=6 key_len=16,
D/wpa_supplicant( 2039):    broadcast key
D/WifiMonitor(  960): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,I/wpa_supplicant( 2039): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2039): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2039): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=],
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP),
D/wpa_supplicant( 2039): netlink: Operstate: linkmode=-1, operstate=6
W/WifiMonitor(  960): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2039): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2039): wpa_supplicant_set_state, isWPS : 0,
,D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2039): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2039): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2039): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2039): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 2039): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2039): EAPOL: Supplicant port status: Authorized,
D/wpa_supplicant( 2039): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2039): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2039): EAPOL authentication completed successfully
D/wpa_supplicant( 2039): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2039): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2039): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  960): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
,D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
,D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): Network connection established
,D/WifiNative-wlan0(  960): doString: STATUS
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2039): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiNative-wlan0(  960):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  960): ssid=NG700
D/WifiNative-wlan0(  960): id=0
D/WifiNative-wlan0(  960): mode=station
D/WifiNative-wlan0(  960): pairwise_cipher=CCMP
D/WifiNative-wlan0(  960): group_cipher=CCMP
D/WifiNative-wlan0(  960): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  960): wpa_state=COMPLETED
D/WifiNative-wlan0(  960): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  960): address=34:fc:ef:de:0a:e2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/WifiServiceExtension(  960): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  960): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  960): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  960): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  960): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/DhcpStateMachine(  960): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  960): WaitBeforeStartState
D/WifiStateMachine(  960): ObtainingIpState{ when=-30ms what=147462 obj=android.net.wifi.StateChangeResult@4347fcc0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-13ms what=147462 obj=android.net.wifi.StateChangeResult@44b36108 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] connect :false
D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-10ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): pr,ocessMsg: L2ConnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196612
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/AppUp4:CustModeStarterReceiver( 4058): onReceive
D/AppUp4:CustFacade( 4058): Context : android.app.ReceiverRestrictedContext@42ac95e0
D/AppUp4:CustFacade( 4058): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4058): isOpenOperator : true
D/AppUp4:CustFacade( 4058): isPhone : true
I/LicenseContentProvider( 3015): start selecting data
D/SIMObserver( 3015): simInfo1
I/AppUp4:EulaManager( 4058): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4058): begin check event
I/AppUp4:CustModeStarterReceiver( 4058): Event For GoodConnectivity
,I/ActivityManager(  960): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=6084 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 6084): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6084): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6084): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  960): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  960):    returned true
,D/WifiNative-wlan0(  960): doBoolean: SET ps 0
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2039): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2039): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2039): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/DhcpStateMachine(  960): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  960): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  264): Setting iface cfg
,D/WifiStateMachine(  960): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4347b3b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4347b3b8 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  960): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-5ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196613
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  960): doBoolean: DRIVER SETSUSPENDMODE 1
V/DownloadManager( 6084): DownloadService onCreate
I/DownloadManager( 6084): in removeSpuriousFiles
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: SET ps 1
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2039): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2039): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2039): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
V/DownloadManager( 6084): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2039): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2039): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42af3708 on behalf of 6084
,I/DownloadManager( 6084): in trimDatabase
D/wpa_supplicant( 2039): wpa_driver_nl80211_driver_cmd OK len = 0, 2
V/DownloadManager( 6084): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): DHCP successful
V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42af4f78 on behalf of 6084
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  960): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  960): VerifyingLinkState enter
,D/WifiStateMachine(  960): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  960): handleMessage: X
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  960): send additional Connectivity Action
D/WifiStateMachine(  960): handleMessage: E msg.what=135190
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
D/WifiStateMachine(  960): processMsg: VerifyingLinkState
D/WifiStateMachine(  960): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
E/Parcel  (  480): Reading a NULL string not supported here.
D/WifiStateMachine(  960): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  960): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  960): CaptivePortalCheckState enter
,D/WifiStateMachine(  960): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
I/ActivityManager(  960): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6106 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
W/WifiStateTracker(  960): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  960): 
W/WifiStateTracker(  960):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  960):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): handleMessage: X
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,V/DownloadManager( 6084): DownloadService onStartCommand
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
V/DownloadManager( 6084): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42af73a8 on behalf of 6084
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  480): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  960): handleMessage: E msg.what=131092
D/WifiStateMachine(  960): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  960): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine(  960): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/WifiStateMachine(  960): transitionTo: destState=ConnectedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
D/QcConnectivityService(  960): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  480): Reading a NULL string not supported here.
E/Parcel  (  480): Reading a NULL string not supported here.
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  480): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/DownloadManager( 6084): DownloadService onDestroy
E/ActivityThread(  960): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  960): handleConnectivityChange: preConnState=2 connState=1
I/ActivityManager(  960): Killing 4991:com.lge.drmservice/u0a66 (adj 15): empty #17
,V/        (  264): RouteController
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/HyLog   ( 6106): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6106): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6106): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/LGEmail ( 6106): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  480): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  480): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  480): |CAC| updateNetCfgInfo
V/QCNEA   (  480): |CAC| *********************************************
V/QCNEA   (  480): |CAC|                   Netconfig               
V/QCNEA   (  480): |CAC| *********************************************
V/QCNEA   (  480): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  480): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  480): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  480): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  480): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  480): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  480): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  480): |CAC| *********************************************
D/QCNEA   (  480): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  480): |CAC| net type = 1
D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/QCNEA   (  480): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  480): |CAC| Received ssid= NG700
V/QCNEA   (  480): |CAC| 	ssid           =NG700
V/QCNEA   (  480): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  480): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  480): |CAC| *********************************************
D/QCNEA   (  480): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  480): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  480): |CAC| dispatchNetCfg: updating:0xb76878dc
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
D/QCNEA   (  480): |CAC| readCallback: read len:0, ret:-1, errno:11
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,D/LGEmail ( 6106): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,D/DhcpStateMachine(  960): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  960): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/BaseRuntimeLoader( 6106): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6106): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6106): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6106): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 6106): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6106): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 6106): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4368): networkInfo.isConnected() = false
,W/linker  ( 6106): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 6106): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 6106): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 6106): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 6106): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 6106): register_HtmlEditor, Success
D/HtmlEditor( 6106): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 6106): register_HtmlEditorTimer, Success
D/HtmlEditor( 6106): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 6106): register_HtmlEditorDownloader, Success
D/HtmlEditor( 6106): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6106): register_HtmlEditorFont, Success
,D/HtmlEditor( 6106): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6106): register_HtmlEditorDrawText, Success
D/HtmlEditor( 6106): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6106): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 6106): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 6106): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 6106): JNI_OnLoad Success
,I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6145 uid=10052 gids={50052, 3003}
I/HubEmail( 6106): JNI_OnLoad()
I/HubEmail( 6106): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6106): registerNatives()
I/HubEmail( 6106): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6106): registerNativeMethods()
I/HubEmail( 6106): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 6106): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 6145): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6145): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6145): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  960): Killing 5010:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,V/LGRssiData( 6145): [loadRssi] File not exist 
,V/LGRssiData( 6145): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6145): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 6145): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6145): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6145): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6145): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 6145): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6145): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6145): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 6145): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6145): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  960): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6163 uid=10063 gids={50063, 3003, 1028, 1015}
,E/PhoneMonitor( 6145): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 6145): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  960): Killing 5024:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/CheckinService( 1882): Checking schedule, now: 1450736729022 next: 1450736144672
,I/CheckinService( 1882): active receiver: enabled
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/CheckinService( 1882): Preparing to send checkin request
,I/EventLogService( 1882): Accumulating logs since 1450736725341
,D/HyLog   ( 6163): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6163): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6163): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinRequestBuilder( 1882): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1882): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  960): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6196 uid=10066 gids={50066, 4002, 3003, 1028}
,D/HyLog   ( 6196): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6196): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6196): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  960): Killing 5057:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  960): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6212 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6212): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6212): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6212): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 6212): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6212): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/DhcpStateMachine(  960): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  960): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  960): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
,V/LgDhcpStateMachineHelper(  960): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  960): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  960): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  960): RunningState
,D/dalvikvm(  960): GC_EXPLICIT freed 2501K, 47% free 30585K/57564K, paused 6ms+12ms, total 162ms
,I/ActivityManager(  960): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6226 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  960): Killing 5075:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
,D/HyLog   ( 6226): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6226): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6226): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 13ms
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
I/NFS     ( 6226): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Wireless_Storage( 6226): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 6226): intf.getDisplayName() = lo
I/Wireless_Storage( 6226): intf.getDisplayName() = sit0
I/Wireless_Storage( 6226): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6226): intf.getDisplayName() = teql0
,I/Wireless_Storage( 6226): intf.getDisplayName() = wlan0
D/NFS     ( 6226): interface name:wlan0 name:wlan0
D/NFS     ( 6226): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 6226): interface name:wlan0 name:wlan0
D/NFS     ( 6226): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 6226): CONNECT : WIFI_CONNECT
,I/ActivityManager(  960): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6240 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  960): Killing 5267:com.google.android.talk/u0a77 (adj 15): empty #17
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/HyLog   ( 6240): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6240): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6240): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,W/CheckinRequestBuilder( 1882): awaiting user notification for token
D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x42f0eb50: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1536): GC_CONCURRENT freed 1601K, 27% free 18196K/24832K, paused 2ms+3ms, total 38ms
D/wpa_supplicant( 2039): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2039): EAPOL: disable timer tick
I/ActivityManager(  960): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6256 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,W/GAV2    ( 6240): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/HyLog   ( 6256): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6256): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6256): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6256): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6256): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 6256): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6256): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6256): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 6256): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6256): install
,I/MultiDex( 6256): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6256): loading existing secondary dex files
,I/MultiDex( 6256): load found 3 secondary dex files
,I/MultiDex( 6256): install done
,D/dalvikvm( 6256): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6256): VFY: unable to resolve instance field 61
,D/dalvikvm( 6256): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6256): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6256): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6256): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 6256): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6256): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6256): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6256): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6256): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6256): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ab32e0
,D/dalvikvm( 6256): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ab32e0
,D/dalvikvm( 6256): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ab32e0, skipping init
,D/dalvikvm( 6256): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42ab32e0
D/dalvikvm( 6256): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42ab32e0
,V/JNIHelp ( 6256): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 6240): Binding Chromium to the main looper Looper (main, tid 1) {42aab538}
,I/chromium( 6240): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6240): Initializing chromium process, renderers=0
,W/chromium( 6240): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6240): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6240): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6240): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6240): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6240): Remote Branch: 
I/Adreno-EGL( 6240): Local Patches: 
I/Adreno-EGL( 6240): Reconstruct Branch: 
,D/dalvikvm( 6256): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42ab32e0
,D/dalvikvm( 6256): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42ab32e0
D/dalvikvm( 6256): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42ab32e0
,D/dalvikvm( 6256): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42ab32e0
,I/NSApplication( 6240): Starting up...
,I/ActivityManager(  960): Killing 5317:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 6040): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6040): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6040): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6040): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6040): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6040): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6001): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6001): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6040): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6040): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6040): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6040): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 6256): Installed default security provider GmsCore_OpenSSL
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1536): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1536): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1882): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1752): callingUid 10006, callindPid: 1752
,D/LocationInitializer( 1882): Restart initialization of location
,E/MDM     ( 1423): [66] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 6256): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6256): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6256): VFY: replacing opcode 0x6e at 0x000d
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  960): NetTransition Wakelock for ConnectedState released by timeout
,I/dalvikvm( 6256): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6256): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6256): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fee000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fee000
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
I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/GCM     ( 1536): Connected
D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=4197330562
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1536): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 6256): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42cd52f0
,D/dalvikvm( 6256): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42cd52f0
,D/dalvikvm( 6256): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42cd52f0, skipping init
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  960): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  960): handleMessage: X
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  960): send additional Connectivity Action
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  960): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  960):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  960): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
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
,D/WVCdm   (  270): PrepareKeyRequest: nonce=24535842
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 6256): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6316): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 6256): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6256): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 103ms
,I/Adreno-EGL( 6256): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6256): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6256): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6256): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6256): Remote Branch: 
I/Adreno-EGL( 6256): Local Patches: 
I/Adreno-EGL( 6256): Reconstruct Branch: 
,W/Settings( 6256): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 6256): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6256): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6256): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6256): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6256): Remote Branch: 
I/Adreno-EGL( 6256): Local Patches: 
I/Adreno-EGL( 6256): Reconstruct Branch: 
,I/Adreno-EGL( 6256): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6256): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6256): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6256): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6256): Remote Branch: 
I/Adreno-EGL( 6256): Local Patches: 
I/Adreno-EGL( 6256): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1882): Classify the device as Phone.
,V/NativeCrypto( 1882): SSL shutdown failed: ssl=0x6bfbf440: I/O error during system call, Connection timed out
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/NativeCrypto( 1882): SSL shutdown failed: ssl=0x6be40bf0: I/O error during system call, Connection timed out
,I/CheckinTask( 1882): Sending checkin request (11450 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1882): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1882): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=-23ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4058): onReceive
,D/AppUp4:CustFacade( 4058): Context : android.app.ReceiverRestrictedContext@42ac95e0
D/AppUp4:CustFacade( 4058): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4058): isOpenOperator : true
,D/AppUp4:CustFacade( 4058): isPhone : true
,I/LicenseContentProvider( 3015): start selecting data
,D/SIMObserver( 3015): simInfo1
,I/AppUp4:EulaManager( 4058): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4058): begin check event
I/AppUp4:CustModeStarterReceiver( 4058): Event For GoodConnectivity
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/AppUp4:CustModeStarterReceiver( 4058): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4058): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4058): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4058): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4058): handleAsyncCustNotification do not startCustService
,D/EAS     ( 6106): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6084): DownloadService onCreate
,D/EAS     ( 6106): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 6106): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4368): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6145): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6145): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6212): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6212): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6226): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6226): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 6084): in removeSpuriousFiles
,V/DownloadManager( 6084): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
W/Settings( 6106): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42afd718 on behalf of 6084
I/DownloadManager( 6084): in trimDatabase
V/DownloadManager( 6084): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 6084): DownloadService onStartCommand
V/DownloadManager( 6084): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42b00880 on behalf of 6084
V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42afeff0 on behalf of 6084
,V/DownloadManager( 6084): DownloadService onDestroy
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4058): onReceive
D/AppUp4:CustFacade( 4058): Context : android.app.ReceiverRestrictedContext@42ac95e0
D/AppUp4:CustFacade( 4058): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4058): isOpenOperator : true
,D/AppUp4:CustFacade( 4058): isPhone : true
,I/LicenseContentProvider( 3015): start selecting data
,D/SIMObserver( 3015): simInfo1
,I/AppUp4:EulaManager( 4058): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4058): begin check event
,I/AppUp4:CustModeStarterReceiver( 4058): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6084): DownloadService onCreate
,I/DownloadManager( 6084): in removeSpuriousFiles
D/EAS     ( 6106): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6084): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 6106): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6084): DownloadService onStartCommand
V/DownloadManager( 6084): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42b05c90 on behalf of 6084
,V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42b077a0 on behalf of 6084
,I/DownloadManager( 6084): in trimDatabase
,V/DownloadManager( 6084): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42b091b8 on behalf of 6084
I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4368): networkInfo.isConnected() = true
,D/PhoneState( 4368): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 6145): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/Settings( 6106): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 6145): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 6084): DownloadService onDestroy
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 6212): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 6226): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6226): CONNECT : WIFI_CONNECT
W/ContextImpl( 6212): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1882): awaiting user notification for token
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x42e97720: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1882): Classify the device as Phone.
,I/CheckinTask( 1882): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1882): Checking schedule, now: 1450736732179 next: 1451314128162
,I/CheckinService( 1882): active receiver: disabled
,I/CheckinService( 1882): Checking schedule, now: 1450736732210 next: 1451314128162
,I/CheckinService( 1882): active receiver: disabled
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1882): GC_CONCURRENT freed 1898K, 22% free 19617K/24832K, paused 6ms+11ms, total 91ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4058): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4058): onReceive
,D/AppUp4:CustFacade( 4058): Context : android.app.ReceiverRestrictedContext@42ac95e0
D/AppUp4:CustFacade( 4058): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4058): isOpenOperator : true
,D/AppUp4:CustFacade( 4058): isPhone : true
,I/LicenseContentProvider( 3015): start selecting data
,D/SIMObserver( 3015): simInfo1
,I/AppUp4:EulaManager( 4058): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4058): begin check event
,I/AppUp4:CustModeStarterReceiver( 4058): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6084): DownloadService onCreate
,D/EAS     ( 6106): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6106): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4368): networkInfo.isConnected() = true
,D/PhoneState( 4368): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6145): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6145): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6212): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6212): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6226): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6226): CONNECT : WIFI_CONNECT
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 6084): in removeSpuriousFiles
,V/DownloadManager( 6084): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/Settings( 6106): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42b0cc98 on behalf of 6084
I/DownloadManager( 6084): in trimDatabase
V/DownloadManager( 6084): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42b0e690 on behalf of 6084
V/DownloadManager( 6084): DownloadService onStartCommand
V/DownloadManager( 6084): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 6084): created cursor android.database.sqlite.SQLiteCursor@42b10800 on behalf of 6084
,D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 6084): DownloadService onDestroy
,D/dalvikvm( 3954): GC_FOR_ALLOC freed 372K, 2% free 37808K/38444K, paused 35ms, total 37ms
,I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  960): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/GAV2    ( 6240): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  960): Killing 4279:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  960): Killing 5332:com.android.gallery3d/u0a27 (adj 15): empty #18
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6419 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,W/ActivityManager(  960): getAssistContextExtras failed: no resumed activity
,W/ActivityManager(  960): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  960):   Scheme: "smsto"
,E/SlideAside( 3784): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3784): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  960): Handling package changes for user 0
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 6419): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6419): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6419): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  960):   Scheme: "mms"
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 6419): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6419): MmsConfig.loadMmsSettings
I/Babel   ( 6419): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6419): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 6419): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6419): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/MediaCodecList( 6419): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 6419): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
W/BaseRuntimeLoader( 6419): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
I/MediaCodecList( 6419): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 6419): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
W/BaseRuntimeLoader( 6419): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 6419): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6419): MmsConfig.loadFromResources
E/Babel   ( 6419): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6419): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/Settings( 6419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GmsNetworkLocationProvi( 1423): DISABLE
V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/LGRssiData( 6419): [loadRssi] File not exist 
V/LGRssiData( 6419): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6419): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 6419): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6419): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6419): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4058): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4058): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4058): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4058): onReceive
D/AppUp4:CustFacade( 4058): Context : android.app.ReceiverRestrictedContext@42ac95e0
,D/AppUp4:CustFacade( 4058): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4058): isOpenOperator : true
,D/AppUp4:CustFacade( 4058): isPhone : true
,I/LicenseContentProvider( 3015): start selecting data
,D/SIMObserver( 3015): simInfo1
,D/dalvikvm(  960): GC_EXPLICIT freed 3012K, 47% free 30710K/57564K, paused 5ms+16ms, total 164ms
,D/LocationProviderProxy(  960): applying state to connected service
,I/AppUp4:EulaManager( 4058): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4058): begin check event
,D/AppUp4:Utils( 4058): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4058): Event For Nothing, skip.
,I/ActivityManager(  960): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6471 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  960): Killing 6001:com.lge.sync/1000 (adj 15): empty #17
D/LocationProviderProxy(  960): applying state to connected service
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6471): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6471): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6471): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6471): BUILD Country: EU
,I/SystemConfig( 6471): BUILD Operator: OPEN
I/ActivityManager(  960): Killing 6040:com.lge.qremote/u0a96 (adj 15): empty #17
,I/SystemConfig( 6471): systemFeature RCS result false
,D/SystemConfig( 6471): refreshRcsSupport() :false
I/ActivityManager(  960): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6485 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6485): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6485): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6485): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  960): Killing 6084:android.process.media/u0a23 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2693): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  960): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6504 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 6504): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6504): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6504): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6504): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6504): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6504): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6504): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6504): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 6504): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6504): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6504): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6504): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6504): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6504): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/IcingCorporaProvider( 2693): UpdateCorporaTask done [took 322 ms] updated apps [took 322 ms] 
,D/Finsky  ( 6504): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6504): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6504): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6504): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6504): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6504): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 6504): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6504): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6504): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6504): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 6504): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6504): VFY: replacing opcode 0x6e at 0x029a
,I/ActivityManager(  960): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6539 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/dalvikvm( 6504): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 6504): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6504): VFY: replacing opcode 0x6e at 0x001a
D/HyLog   ( 6539): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6539): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6539): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6504): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 6504): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6504): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6504): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6504): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1882): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1882): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1882): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 6539): DownloadService onCreate
,I/DownloadManager( 6539): in removeSpuriousFiles
,V/DownloadManager( 6539): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6539): created cursor android.database.sqlite.SQLiteCursor@42af27e0 on behalf of 6539
,V/DownloadManager( 6539): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 6539): in trimDatabase
,V/DownloadManager( 6539): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6539): DownloadService onStartCommand
,V/DownloadManager( 6539): created cursor android.database.sqlite.SQLiteCursor@42af9eb0 on behalf of 6539
V/DownloadManager( 6539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6539): created cursor android.database.sqlite.SQLiteCursor@42af9a10 on behalf of 6504
,V/DownloadManager( 6539): created cursor android.database.sqlite.SQLiteCursor@42afc448 on behalf of 6539
,D/Finsky  ( 6504): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 6539): DownloadService onDestroy
,D/Finsky  ( 6504): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  960): Killing 6106:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6504): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6504): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6504): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6504): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6504): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6504): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 6504): Total arena pages for JIT: 11
,I/dalvikvm( 6504): Total arena pages for JIT: 12
I/dalvikvm( 6504): Total arena pages for JIT: 13
,I/dalvikvm( 6504): Total arena pages for JIT: 14
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  960): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  960): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  960): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  960): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  960): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6504): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6504): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6504): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6504): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1423): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736742877961768; DSPS: 24942816; Offset: 1450735981683625831
,I/GAV4    ( 6419): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  960): Killing 6145:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea7c90 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/Finsky  ( 6504): [507] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6504): [1] 5.onFinished: Installation state replication succeeded.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736760031, nextTick: 59982, mDrawingTime: 10
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736760065, nextTick: 59968, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736762884002635; DSPS: 25598374; Offset: 1450735981683624218
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736782890634750; DSPS: 26253952; Offset: 1450735981683603500
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736802896798878; DSPS: 26909514; Offset: 1450735981683603078
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736820033, nextTick: 59992, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736820035, nextTick: 59997, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736822902433116; DSPS: 27565058; Offset: 1450735981683622081
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736842907761220; DSPS: 28220593; Offset: 1450735981683609609
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736862915944225; DSPS: 28876221; Offset: 1450735981683613903
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736880028, nextTick: 59999, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736880053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736882919800562; DSPS: 29531708; Offset: 1450735981683594508
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736902927991652; DSPS: 30187336; Offset: 1450735981683606887
,D/wpa_supplicant( 2039): wlan0: BSS: Remove id 6 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 7 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 8 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 9 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 10 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2039): wlan0: BSS: Remove id 11 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2039): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 06:7c:34:12:7f:81]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 a0:c5:62:7a:49:97]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 10:9a:dd:8e:22:d9]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 64:7c:34:12:7f:81]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 a0:c5:62:7a:49:96]
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736922932448585; DSPS: 30842842; Offset: 1450735981683608253
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736940041, nextTick: 59986, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450736940044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736942939546391; DSPS: 31498434; Offset: 1450735981683625981
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736962943077104; DSPS: 32153910; Offset: 1450735981683616655
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450736982951716114; DSPS: 32809553; Offset: 1450735981683619191
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737000033, nextTick: 59996, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737000035, nextTick: 59997, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737002956080135; DSPS: 33465056; Offset: 1450735981683619198
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737022961072876; DSPS: 34120579; Offset: 1450735981683637574
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  960): GC_EXPLICIT freed 1250K, 47% free 30580K/57564K, paused 6ms+10ms, total 168ms
,D/dalvikvm( 1536): GC_EXPLICIT freed 1543K, 28% free 18007K/24832K, paused 2ms+5ms, total 43ms
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x4349cab8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1536): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1536): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 6504): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6504): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6504): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6504): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6504): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6504): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6504): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6504): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 6504): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6504): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737042966002413; DSPS: 34776101; Offset: 1450735981683623263
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737060031, nextTick: 59989, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737060054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737062972860503; DSPS: 35431686; Offset: 1450735981683614898
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737082979393101; DSPS: 36087260; Offset: 1450735981683616734
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737102985452422; DSPS: 36742818; Offset: 1450735981683633575
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737120031, nextTick: 59980, mDrawingTime: 9
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737120057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737122990182889; DSPS: 37398333; Offset: 1450735981683633817
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737142997285951; DSPS: 38053927; Offset: 1450735981683595766
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737163000136651; DSPS: 38709380; Offset: 1450735981683608331
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737180024, nextTick: 60000, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737180049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737183006559525; DSPS: 39364950; Offset: 1450735981683622514
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737203011059248; DSPS: 40020458; Offset: 1450735981683605635
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737223015816020; DSPS: 40675973; Offset: 1450735981683632183
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737240060, nextTick: 59966, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737240064, nextTick: 59969, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737243018987907; DSPS: 41331438; Offset: 1450735981683599724
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737263023933655; DSPS: 41986959; Offset: 1450735981683632142
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737283028319452; DSPS: 42642463; Offset: 1450735981683623408
,D/Finsky  ( 6504): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6504): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6504): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6504): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6504): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6504): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6504): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/DeviceConnectionService( 1423): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737300038, nextTick: 59966, mDrawingTime: 11
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737300057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737303034289530; DSPS: 43298019; Offset: 1450735981683612040
,D/Finsky  ( 6504): [507] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6504): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737323039811529; DSPS: 43953560; Offset: 1450735981683610358
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737343045847144; DSPS: 44609118; Offset: 1450735981683603492
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737360036, nextTick: 59977, mDrawingTime: 10
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737360046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737363048690858; DSPS: 45264571; Offset: 1450735981683609071
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737383056246801; DSPS: 45920178; Offset: 1450735981683627173
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737403058782520; DSPS: 46575621; Offset: 1450735981683629933
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737420036, nextTick: 59989, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737420043, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737423065368670; DSPS: 47231197; Offset: 1450735981683624286
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737443074119389; DSPS: 47886844; Offset: 1450735981683616460
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737463078437938; DSPS: 48542345; Offset: 1450735981683632030
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737480037, nextTick: 59986, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737480042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737483085091660; DSPS: 49197924; Offset: 1450735981683602403
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737503089623547; DSPS: 49853432; Offset: 1450735981683617688
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737523095975185; DSPS: 50509000; Offset: 1450735981683621670
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737540039, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737540041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737543099000379; DSPS: 51164459; Offset: 1450735981683625624
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737563106758685; DSPS: 51820074; Offset: 1450735981683601947
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737583112295529; DSPS: 52475615; Offset: 1450735981683615110
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737600036, nextTick: 59993, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737600038, nextTick: 59993, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737603118460373; DSPS: 53131177; Offset: 1450735981683615403
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737623125370292; DSPS: 53786763; Offset: 1450735981683628349
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737643131911829; DSPS: 54442338; Offset: 1450735981683608607
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737660037, nextTick: 59992, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737660039, nextTick: 59992, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737663137209518; DSPS: 55097871; Offset: 1450735981683626755
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737683142917424; DSPS: 55753418; Offset: 1450735981683627874
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737703149319818; DSPS: 56408988; Offset: 1450735981683621576
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737720035, nextTick: 59994, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737720042, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737723153827849; DSPS: 57064496; Offset: 1450735981683613006
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737743159445391; DSPS: 57720040; Offset: 1450735981683615313
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737763162443649; DSPS: 58375498; Offset: 1450735981683622849
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737780049, nextTick: 59973, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737780056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737783166786996; DSPS: 59031001; Offset: 1450735981683602182
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737803172884093; DSPS: 59686560; Offset: 1450735981683626281
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  960): Sampling interval elapsed, updating statistics ..
,I/ProcessStatsService(  960): Prepared write state in 68ms
,D/QcConnectivityService(  960): Done.
,D/QcConnectivityService(  960): Setting timer for 720seconds
,I/ProcessStatsService(  960): Pruning old procstats: /data/system/procstats/state-2015-12-21-00-50-43.bin
,D/LocationManagerService(  960): getAllProviders()=[passive, gps, network]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,D/GCM     ( 1536): Message class com.google.f.a.a.i
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737823180985016; DSPS: 60342186; Offset: 1450735981683609528
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737840033, nextTick: 59991, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737840039, nextTick: 59993, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737843184784945; DSPS: 60997670; Offset: 1450735981683625278
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737863192993105; DSPS: 61653299; Offset: 1450735981683624209
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737883196009277; DSPS: 62308758; Offset: 1450735981683619141
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737900032, nextTick: 59987, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450737900040, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450737903203085344; DSPS: 62964350; Offset: 1450735981683615130
,TIME-OUT KILL (timeout was 1800000ms)
```
