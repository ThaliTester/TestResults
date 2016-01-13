#### Test 558973767bac5c9_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1945): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1945): launchTask
W/dalvikvm( 1945): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1945): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1U056G8EJXX_eINrEta5QbsiWHGbHtSdAexW_QLR3akaoprZ2dRucWemmf7uTNvveIEUVGzdrWjDEeQjTT2JsI1HqVEonigkGrRt7XMmdIbZO_2jImwK_Km6bNrYj3cSedZregxVBXUEQR29kNug2jEjwx6JcZPUuH9sIzZ9ioYO5Sfb3sIrsAxTGbWJluLEhNil5jJ
I/GoogleURLConnFactory( 1945): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1945): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1945): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1945): No vision deps
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/PeopleContactsSync( 1945): CP2 sync disabled
I/dalvikvm( 1945): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1945): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1945): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/GAV2    ( 4638): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  967): Killing 4155:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43323e10 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4346d3e0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1162): usb Uevent not necessary.
I/ConfigFetchService( 1945): fetch service done; releasing wakelock
I/ConfigFetchService( 1945): stopping self
D/dalvikvm( 1555): GC_EXPLICIT freed 1035K, 29% free 17820K/24832K, paused 1ms+5ms, total 27ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4695): 
D/AndroidRuntime( 4695): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4695): CheckJNI is OFF
D/dalvikvm( 4695): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4695): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4695): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4695): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4695): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4695): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1945): GC_CONCURRENT freed 1512K, 22% free 19466K/24832K, paused 4ms+3ms, total 33ms
I/Icing   ( 1945): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1945): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1945): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4695): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4695): failed to load memtrack module: -2
D/BubblePopupHelper( 1146): isShowingBubblePopup : false
D/AndroidRuntime( 4695): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4695
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43323e10 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (175 us)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{4346d3e0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{43323e10 stackId=1, 2 tasks}
D/UsbSettingsControl( 2608): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2608): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4695): Shutting down VM
I/SlideAside( 4139): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4695): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 2ms
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{4346d3e0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{4346d3e0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43323e10 stackId=1, 2 tasks}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{44f9c858 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4725 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 4139): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4139): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{44f9c858 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4725): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4725): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4725): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4725): Binding Chromium to the background looper Looper (main, tid 1) {428d4c20}
I/chromium( 4725): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4725): Initializing chromium process, renderers=0
W/chromium( 4725): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4725): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4725): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4725): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4725): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4725): Remote Branch: 
I/Adreno-EGL( 4725): Local Patches: 
I/Adreno-EGL( 4725): Reconstruct Branch: 
I/dalvikvm( 4725): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4725): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4725): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4725): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4725): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4725): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4725): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4725): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4725): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4725): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4725): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4725): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4725): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4725): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4725): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4725): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4725): Enabling debug mode 0
W/AwContents( 4725): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  967): IME STATUS OFF
W/AwContents( 4725): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +355ms
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2026): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
I/ActivityManager( 4725): Timeline: Activity_idle id: android.os.BinderProxy@428d63f0 time:108487
D/JsMessageQueue( 4725): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4725): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428da988
D/dalvikvm( 4725): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428da988
D/jxcore_app_log( 4725): JniHelper::setJavaVM(0x417a1838), pthread_self() = 1639695040
I/chromium( 4725): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1162): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{44f9c858 u0 com.test.thalitest/.MainActivity t3} time:108891
D/ActivityManager(  967): no-history finish of ActivityRecord{4346d3e0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{43467748 ActivityRecord{4346d3e0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{4346d3e0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f9c858 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{4346d3e0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2608): [AUTORUN] onStop()
I/chromium( 4725): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{4346d3e0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/chromium( 4725): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/dalvikvm( 4725): GC_CONCURRENT freed 2780K, 12% free 21863K/24832K, paused 1ms+1ms, total 34ms
,D/dalvikvm( 4725): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 113K, 12% free 21860K/24832K, paused 22ms, total 23ms
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 125K, 12% free 21880K/24832K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 23.632MB for 95956-byte allocation
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 178K, 13% free 21915K/24928K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 23.712MB for 143930-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 253K, 13% free 21962K/25072K, paused 41ms, total 42ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 23.827MB for 215890-byte allocation
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 368K, 13% free 22036K/25284K, paused 42ms, total 43ms
I/dalvikvm-heap( 4725): Grow heap (frag case) to 24.001MB for 323830-byte allocation
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 567K, 14% free 22157K/25604K, paused 38ms, total 39ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 24.275MB for 485740-byte allocation
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 863K, 15% free 22332K/26080K, paused 35ms, total 36ms
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 1280K, 14% free 22588K/26080K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 25.275MB for 1092904-byte allocation
,D/dalvikvm( 4725): GC_CONCURRENT freed 1810K, 16% free 22983K/27148K, paused 1ms+3ms, total 36ms
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 251K, 16% free 22899K/27148K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 26.099MB for 1639352-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/dalvikvm( 4725): GC_CONCURRENT freed 1673K, 19% free 23484K/28752K, paused 2ms+3ms, total 30ms
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 1319K, 19% free 23548K/28752K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 27.514MB for 2459024-byte allocation
,D/dalvikvm( 4725): GC_CONCURRENT freed 256K, 18% free 25834K/31156K, paused 2ms+3ms, total 43ms
,D/dalvikvm( 4725): GC_CONCURRENT freed 4363K, 22% free 24547K/31156K, paused 2ms+4ms, total 35ms
,D/dalvikvm( 4725): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 29.663MB for 3688532-byte allocation
,D/dalvikvm( 4725): GC_CONCURRENT freed 324K, 20% free 27907K/34760K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 3271K, 27% free 25497K/34760K, paused 24ms, total 25ms
,W/jxcore-log( 4725): Initializing JXcore engine
,W/jxcore-log( 4725): JXcore engine is ready
,D/dalvikvm( 4725): GC_CONCURRENT freed 384K, 20% free 28105K/34760K, paused 2ms+1ms, total 25ms
,D/dalvikvm( 4725): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/jxcore-log( 4725): Starting JXcore engine
,W/jxcore-log( 4725): Platform android
W/jxcore-log( 4725): 
,W/jxcore-log( 4725): Process ARCH arm
W/jxcore-log( 4725): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4725): JXcore Cordova bridge is ready!
I/jxcore-log( 4725): 
,W/jxcore-log( 4725): JXcore engine is started
,E/jxcore  ( 4725): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4725): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4725): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  967): Finishing activity token=Token{44198138 ActivityRecord{44f9c858 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{44f9c858 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm(  967): GC_FOR_ALLOC freed 23156K, 49% free 29687K/57880K, paused 113ms, total 114ms
,W/PluginManager( 4725): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 126ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{44f9c858 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{44f9c858 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43323e10 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  967): moveHomeStack:
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e473c8 stackId=0, 1 tasks}
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{43106320 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{43106320 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  967): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42e473c8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43106320 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1491): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1491): [Launcher.java:717:onResume()]onResume
I/[LGHome]EVENT( 1491): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PhoneApp( 1451): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1491): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1491): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1875): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:53:22
D/UpdateThreadPoolManager( 1875): 2 : This is isUpdating : false
D/WeatherQuickCover( 1875): 2 : quick cover state : opened : 0
D/WeatherService( 1875): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1875): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1875): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1875): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherService( 1875): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1875): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:53:22
D/WeatherService( 1875): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1875): 2 : quick cover state : opened : 0
D/Weather.Utils( 1875): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1875): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1875): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1875): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1875): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1875): 2 : This is isUpdating : false
D/WeatherService( 1875): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1875): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1875): 2 : Map key string is -2
,D/lim     ( 1875): 2 : time = 14:53
,I/WeatherReflect( 1875): Model Name : LG-D802
D/WeatherTheme( 1875): 2 : Different view - status_min_formatted : 51 != 53
,I/[LGHome]EVENT( 1491): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/WeatherTheme( 1875): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
,D/WeatherTheme( 1875): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1875): 2 : Fixed theme : optimus
,D/WeatherTheme( 1875): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,W/IInputConnectionWrapper( 4725): showStatusIcon on inactive InputConnection
,D/WeatherQuickCover( 1875): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1875): 2 : Utils getTopActivity com.lge.launcher2 / true
,I/InputMethodManagerService(  967): IME STATUS OFF
D/WeatherService( 1875): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1875): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1491): GC_CONCURRENT freed 5520K, 9% free 60928K/66632K, paused 3ms+4ms, total 25ms
,D/dalvikvm( 1491): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 1146): GC_CONCURRENT freed 3740K, 7% free 71567K/76612K, paused 2ms+4ms, total 39ms
,D/dalvikvm( 1146): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge( 1491): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1491): GC_FOR_ALLOC freed 4794K, 9% free 61910K/67428K, paused 18ms, total 19ms
,I/ActivityManager( 1491): Timeline: Activity_idle id: android.os.BinderProxy@428da400 time:111818
,V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{4346d3e0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/UsbSettings( 2608): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2608): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2608): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2608): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{4346d3e0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e473c8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43106320 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{43106320 u0 com.lge.launcher2/.Launcher t1} time:111865
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{44f9c858 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  967): Killing 4234:com.google.android.talk/u0a77 (adj 15): empty #17
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{44f9c858 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4725): call to OpenGL ES API with no current context (logged once per thread)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1162): usb Uevent not necessary.
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e473c8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43106320 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{44f9c858 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e473c8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43106320 u0 com.lge.launcher2/.Launcher t1}
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1214): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4638): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,D/HeadsetStateMachine( 1214): Disconnected process message: 10,
,D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.456619 Y: -0.379669 Z: 9.818329 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456619 .y:-0.379669 .z:9.818329
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/ConfigService( 1555): onDestroy
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.469238 Y: -0.388855 Z: 9.807236 
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.471451 Y: -0.418808 Z: 9.796143 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.469238 .y:-0.388855 .z:9.807236
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1162): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1214): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1214): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]NumberBadge.LGBroadCastBadge( 1491): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
E/[LGHome]NumberBadge( 1491): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1162): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1214): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4318): [402] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4318): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
,D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: X
,E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.445251 Y: -0.393021 Z: 9.804260 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445251 .y:-0.393021 .z:9.804260
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.455521 Y: -0.393753 Z: 9.825348 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455521 .y:-0.393753 .z:9.825348
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/PowerManagerService(  967): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  967): [updateScreenState] screen on = false
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = true
,I/qcom_sensors_hal(  967): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8638 usec
,D/qcom_sensors_hal(  967): hal_acquire_resources
,I/qcom_sensors_hal(  967): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  967): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,I/qcom_sensors_hal(  967): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  967): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  967): hal_sam_algo_activate: Update freq 0 -> 20
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
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.462509 Y: -0.389847 Z: 9.826233 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462509 .y:-0.389847 .z:9.826233
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.455856 Y: -0.395721 Z: 9.835571 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455856 .y:-0.395721 .z:9.835571
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  385): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  967): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  967): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  967): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
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
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.461670 Y: -0.390762 Z: 9.817749 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461670 .y:-0.390762 .z:9.817749
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.456543 Y: -0.393875 Z: 9.811417 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456543 .y:-0.393875 .z:9.811417
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449615 Y: -0.399017 Z: 9.825333 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449615 .y:-0.399017 .z:9.825333
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.454895 Y: -0.395889 Z: 9.829590 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454895 .y:-0.395889 .z:9.829590
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@433253b0)
,D/KeyguardViewMediator( 1146): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1146): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1146): OMADM Lock is OFF
D/KeyguardViewMediator( 1146): handleNotifyScreenOn
,D/KeyguardViewManager( 1146): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
,I/WindowManager(  967): No lock screen! windowToken=null
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8794450
D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.452713 Y: -0.394394 Z: 9.832520 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452713 .y:-0.394394 .z:9.832520
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132097
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2026): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2026): initialize kt scan interval and do scan state=9
D/WifiStateMachine(  967): handleMessage: X
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
V/SRS_Proc(  270): ParamSet string: screen_state=on
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1162): getCurrentHighestLGLedRecord() start. mLedList.size=2
,V/EmotionalLed( 1162): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433f5a00 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/WeatherAncestor( 1875): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:53:49
,E/SlideAside( 4139): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 4139): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1875): 2 : This is isUpdating : false
,D/WeatherAncestor( 1875): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:53:49
,D/LockPatternUtilsEx( 1146): OMADM Lock is OFF
,D/WeatherService( 1875): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1875): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1875): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1875): 2 : shouldTimeTickRegistered : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/EmotionalLed( 1162): enqueuing start. mLedList.size()=2
,D/qdlights( 1162): set_light_notifications: 0,0,0,0,3
D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
I/EmotionalLed( 1162): updateLightsLocked() start. mLedList.size=3
D/EmotionalLed( 1162): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1162): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1162): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 249, B = 249
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 411ms
,D/qdlights( 1162): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1162): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 237, B = 237
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1162): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1162): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 225, B = 225
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.438232 Y: -0.392685 Z: 9.836380 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.438232 .y:-0.392685 .z:9.836380
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/GlobalAccess( 1146): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1146): changeTargets() succeeded. size: 20
,D/qdlights( 1162): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 219, B = 219
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693229934, nextTick: 10098, mDrawingTime: 0
,D/qdlights( 1162): set_light_notifications: 2,ff00d5d5,10,0,2,
,D/qdlights( 1162): [Current] = 255, R = 0, G = 213, B = 213
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1162): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 207, B = 207
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693229958, nextTick: 10074, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
D/qdlights( 1162): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1162): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1162): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 189, B = 189
,D/WeatherService( 1875): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:53:49
,D/WeatherService( 1875): 2 : ACTION screen on
,D/WeatherService( 1875): 2 : shouldTimeTickRegistered : false
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/WeatherService( 1875): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:53:49
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
D/qdlights( 1162): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 183, B = 183
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.450104 Y: -0.391205 Z: 9.842300 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450104 .y:-0.391205 .z:9.842300
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
D/qdlights( 1162): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 177, B = 177
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1146): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1146): notifyScreenOffLocked
,I/[LGHome]EVENT( 1491): [Launcher.java:894:onPause()]onPause
D/qdlights( 1162): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 171, B = 171
,V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{43106320 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1162): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1162): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 159, B = 159
W/ProcessCpuTracker(  967): Skipping unknown process pid 4843
W/ProcessCpuTracker(  967): Skipping unknown process pid 4844
W/ProcessCpuTracker(  967): Skipping unknown process pid 4851
W/ProcessCpuTracker(  967): Skipping unknown process pid 4852
W/ProcessCpuTracker(  967): Skipping unknown process pid 4861
W/ProcessCpuTracker(  967): Skipping unknown process pid 4862
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1162): set_light_notifications: 2,ff009999,10,0,2
I/LGImmersionVibrator(  967): Vibrator off
D/qdlights( 1162): [Current] = 255, R = 0, G = 153, B = 153
,D/KeyguardViewMediator( 1146): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/WifiStateMachine(  967): handleScreenStateChanged: false
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
I/[LGHome]EVENT( 1491): [Launcher.java:4955:onStop()]onStop
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{43106320 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{43106320 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/WifiController(  967): CMD_SCREEN_OFF 
,D/WifiController(  967): shouldWifiStayAwake TRUE
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/qdlights( 1162): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 147, B = 147
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{43106320 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/EmotionalLed( 1162): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1162): clear
,D/qdlights( 1162): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 141, B = 141
D/KeyguardViewMediator( 1146): handleNotifyScreenOff
,D/KeyguardViewManager( 1146): onScreenTurnedOff()
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd  len = 0, 0
E/CliptrayService( 1162): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
D/qdlights( 1162): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1162): [Current] = 255, R = 0, G = 135, B = 135
I/[LGHome]EVENT( 1491): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1162): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 129, B = 129
D/WeatherService( 1875): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:53:50
D/WeatherService( 1875): 2 : ACTION screen off
,D/WeatherService( 1875): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:53:50
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
D/qdlights( 1162): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 123, B = 123
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_OFF
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/LockPatternUtilsEx( 1146): OMADM Lock is OFF
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
,D/NfcService( 1475): NFC-C OFF
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
D/qdlights( 1162): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 117, B = 117
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1162): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1162): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1162): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1162): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1162): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1162): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1162): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1162): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1162): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1162): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1162): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1162): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1162): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1162): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1162): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1162): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1162): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1162): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1162): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1162): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1162): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  385): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1146): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1146): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1146): OMADM Lock is OFF
,D/KeyguardViewMediator( 1146): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1146): doKeyguard is called, but is not locked.
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693240056, nextTick: 59976, mDrawingTime: 0
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693240059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693247692050263; DSPS: 5270934; Offset: 1452693086835910127
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693267693378693; DSPS: 5926338; Offset: 1452693086835895783
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693287694239414; DSPS: 6581726; Offset: 1452693086835902012
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1555): Vacuum at: now=1452693292750 tag=VacuumService
,I/GoogleURLConnFactory( 1555): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1555): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1555): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1555):  no longer exists, so no auth token.
,W/Uploader( 1555): No account for auth token provided
,D/wpa_supplicant( 2026): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 7 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 8 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 9 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 10 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11],
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 06:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 fc:94:e3:11:35:3a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 fe:94:e3:11:35:3c]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 dc:4a:3e:0f:c2:f1]
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693300039, nextTick: 59988, mDrawingTime: 2
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693300056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693307695622688; DSPS: 7237131; Offset: 1452693086835911995
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693327696467836; DSPS: 7892519; Offset: 1452693086835902651
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693347696905536; DSPS: 8547893; Offset: 1452693086835913105
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693360042, nextTick: 59971, mDrawingTime: 7
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693360055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693367698244748; DSPS: 9203297; Offset: 1452693086835909543
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693387699098073; DSPS: 9858685; Offset: 1452693086835908376
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693407700031972; DSPS: 10514076; Offset: 1452693086835896230
,D/dalvikvm( 2672): GC_CONCURRENT freed 7768K, 33% free 16869K/24832K, paused 2ms+1ms, total 34ms
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693420027, nextTick: 59997, mDrawingTime: 5
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693420057, nextTick: 59976, mDrawingTime: 0
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x430cf318: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1555): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1555): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1555): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1555): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1555): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1555): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1555): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1555): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4318): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4318): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4318): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4318): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4318): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4318): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4318): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4318): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4318): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693427700915246; DSPS: 11169465; Offset: 1452693086835894495
,I/LocationManagerService(  967): remove 43368218
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2672): GC_CONCURRENT freed 1603K, 31% free 17313K/24832K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 2672): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 2672): GC_FOR_ALLOC freed 1715K, 31% free 17265K/24832K, paused 21ms, total 21ms
,I/Mlt MonitorService( 2672): parseLastkmsg to dump
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693447702366905; DSPS: 11824872; Offset: 1452693086835911827
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693467705184449; DSPS: 12480325; Offset: 1452693086835891237
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693480045, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693480054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693487706527774; DSPS: 13135729; Offset: 1452693086835891788
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693507706948080; DSPS: 13791102; Offset: 1452693086835915366
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693527707391613; DSPS: 14446477; Offset: 1452693086835901135
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693540040, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693540055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693547712474366; DSPS: 15102003; Offset: 1452693086835917970
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693567713328318; DSPS: 15757391; Offset: 1452693086835917430
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693587714184976; DSPS: 16412779; Offset: 1452693086835919596
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693600045, nextTick: 59971, mDrawingTime: 7
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693600060, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693607714632417; DSPS: 17068154; Offset: 1452693086835909273
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693627716150274; DSPS: 17723564; Offset: 1452693086835901251
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693647716998704; DSPS: 18378952; Offset: 1452693086835895189
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693660039, nextTick: 59983, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693660056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693667717443280; DSPS: 19034326; Offset: 1452693086835912519
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693687718383271; DSPS: 19689717; Offset: 1452693086835906465
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693707719734878; DSPS: 20345121; Offset: 1452693086835915298
,I/ActivityManager(  967): Killing 3176:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e473c8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693720040, nextTick: 59968, mDrawingTime: 10
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693720056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693727720183412; DSPS: 21000496; Offset: 1452693086835906069
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693747720620176; DSPS: 21655870; Offset: 1452693086835915587
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693767722054231; DSPS: 22311277; Offset: 1452693086835915315
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693780032, nextTick: 59983, mDrawingTime: 9
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693780060, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693787722995109; DSPS: 22966668; Offset: 1452693086835910149
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693807724516195; DSPS: 23622078; Offset: 1452693086835905356
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693827733535458; DSPS: 24277734; Offset: 1452693086835891416
,D/Finsky  ( 4318): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4318): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1555): GC_CONCURRENT freed 1746K, 28% free 18023K/24832K, paused 2ms+5ms, total 39ms
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4318): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4318): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4318): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4318): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4318): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1426): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693840032, nextTick: 59991, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693840045, nextTick: 59987, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  967): GC_CONCURRENT freed 2270K, 48% free 30604K/57880K, paused 10ms+10ms, total 157ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693847735010294; DSPS: 24933142; Offset: 1452693086835901408
,D/Finsky  ( 4318): [402] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4318): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693867735434245; DSPS: 25588516; Offset: 1452693086835898113
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693887735872675; DSPS: 26243890; Offset: 1452693086835909297
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693900039, nextTick: 59970, mDrawingTime: 10
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693900054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693907736834594; DSPS: 26899282; Offset: 1452693086835894653
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693927738390681; DSPS: 27554693; Offset: 1452693086835894344
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693947739298901; DSPS: 28210082; Offset: 1452693086835917554
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693960033, nextTick: 59992, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452693960044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693967739737123; DSPS: 28865457; Offset: 1452693086835898012
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452693987741069408; DSPS: 29520861; Offset: 1452693086835887524
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694007742487160; DSPS: 30176267; Offset: 1452693086835901467
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694020039, nextTick: 59967, mDrawingTime: 11
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694020056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694027742935278; DSPS: 30831642; Offset: 1452693086835891821
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694047747409697; DSPS: 31487148; Offset: 1452693086835910674
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694067748724273; DSPS: 32142551; Offset: 1452693086835912994
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694080032, nextTick: 59982, mDrawingTime: 10
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694080057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694087749582754; DSPS: 32797939; Offset: 1452693086835916983
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694107750013997; DSPS: 33453314; Offset: 1452693086835890462
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694127758402948; DSPS: 34108949; Offset: 1452693086835887079
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694140033, nextTick: 59983, mDrawingTime: 9
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694140053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694147759720908; DSPS: 34764352; Offset: 1452693086835892783
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694167760552203; DSPS: 35419739; Offset: 1452693086835900104
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694187760986675; DSPS: 36075113; Offset: 1452693086835907330
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694200031, nextTick: 59992, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694200046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694207762980105; DSPS: 36730538; Offset: 1452693086835917117
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694227763831035; DSPS: 37385926; Offset: 1452693086835913555
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694247764265402; DSPS: 38041301; Offset: 1452693086835890158
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694260037, nextTick: 59978, mDrawingTime: 8
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694260054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694267765487008; DSPS: 38696701; Offset: 1452693086835891061
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694287766779762; DSPS: 39352103; Offset: 1452693086835902077
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694307768041159; DSPS: 40007504; Offset: 1452693086835912253
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694320026, nextTick: 60000, mDrawingTime: 5
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694320056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694327768469434; DSPS: 40662878; Offset: 1452693086835913282
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694347770131718; DSPS: 41318293; Offset: 1452693086835897099
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694367770970981; DSPS: 41973680; Offset: 1452693086835912388
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694380053, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694380055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694387771871651; DSPS: 42629070; Offset: 1452693086835897530
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694407773660393; DSPS: 43284488; Offset: 1452693086835916253
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694427774590177; DSPS: 43939879; Offset: 1452693086835899992
,D/dalvikvm( 2672): GC_CONCURRENT freed 2448K, 33% free 16737K/24832K, paused 7ms+2ms, total 65ms
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694440042, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694440055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694447775475274; DSPS: 44595268; Offset: 1452693086835900079
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694467775960682; DSPS: 45250644; Offset: 1452693086835897206
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694487776854946; DSPS: 45906033; Offset: 1452693086835906460
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694500039, nextTick: 59986, mDrawingTime: 5
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694500055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694507778167334; DSPS: 46561436; Offset: 1452693086835906592
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694527778585243; DSPS: 47216810; Offset: 1452693086835897255
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694547779039558; DSPS: 47872185; Offset: 1452693086835893807
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,D/GCM     ( 1555): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694560039, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694560056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694567780461425; DSPS: 48527591; Offset: 1452693086835911865
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694587781312616; DSPS: 49182979; Offset: 1452693086835908564
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694607783623286; DSPS: 49838415; Offset: 1452693086835899898
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694620045, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694620055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694627787339371; DSPS: 50493897; Offset: 1452693086835892838
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694647788605510; DSPS: 51149298; Offset: 1452693086835907757
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694667789441544; DSPS: 51804685; Offset: 1452693086835919816
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694680035, nextTick: 59985, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694680042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694687789896952; DSPS: 52460060; Offset: 1452693086835917460
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694707790757466; DSPS: 53115449; Offset: 1452693086835892965
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694727791613865; DSPS: 53770837; Offset: 1452693086835894871
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694740037, nextTick: 59966, mDrawingTime: 12
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694740055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694747792485004; DSPS: 54426225; Offset: 1452693086835911518
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694767792938798; DSPS: 55081600; Offset: 1452693086835907548
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694787794238477; DSPS: 55737003; Offset: 1452693086835894972
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694800031, nextTick: 59989, mDrawingTime: 8
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694800048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694807795117793; DSPS: 56392391; Offset: 1452693086835919795
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694827796032056; DSPS: 57047781; Offset: 1452693086835918531
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694847801774391; DSPS: 57703330; Offset: 1452693086835893044
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694860032, nextTick: 59991, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694860057, nextTick: 59969, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694867803160114; DSPS: 58358735; Offset: 1452693086835905476
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694887804011304; DSPS: 59014123; Offset: 1452693086835902174
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694907805361139; DSPS: 59669527; Offset: 1452693086835909235
,I/ProcessStatsService(  967): Prepared write state in 45ms
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694920079, nextTick: 59950, mDrawingTime: 3
D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694920080, nextTick: 59952, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  967): Pruning old procstats: /data/system/procstats/state-2016-01-12-16-48-00.bin
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694927806285143; DSPS: 60324918; Offset: 1452693086835887194
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694947807564718; DSPS: 60980319; Offset: 1452693086835915549
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694967808405857; DSPS: 61635707; Offset: 1452693086835902195
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
I/ActivityManager(  967): Killing 4381:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty for 1851s
I/ActivityManager(  967): Killing 3990:com.google.android.gms.unstable/u0a6 (adj 15): empty for 1853s
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694980055, nextTick: 59975, mDrawingTime: 2
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1452694980059, nextTick: 59974, mDrawingTime: 0
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e473c8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e473c8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452694987808848140; DSPS: 62291081; Offset: 1452693086835917232
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452695007810124539; DSPS: 62946483; Offset: 1452693086835911893
,TIME-OUT KILL (timeout was 1800000ms)
```
