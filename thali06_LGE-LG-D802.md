#### Test 506502785223c58_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1851): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1851): launchTask
W/dalvikvm( 1851): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1851): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1851): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1851): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1851): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1851): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1851): No vision deps
W/GAV2    ( 4639): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
V/ConfigFetchTask( 1851): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Xly_TQJ2UPkyI0p2xOTi8mBGvMJ9f6_0TB8moL2-b8EqLDaVFtBP2AIVevlXvyxfyn7GBJg2yydevruKhiQAayR5lETb9nyu0TLtoPhXjdmBQn6gus91fzdOLWwow42w6OGyRZd71vqD-nyH9aYK4B4LKv6Q49W04An2yFb1S93IWPmg3FcQbFGg0mEm32qiwz6VCw
,I/GoogleURLConnFactory( 1851): Using platform SSLCertificateSocketFactory
--------- beginning of /dev/log/system
I/ActivityManager(  963): Killing 4116:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{432fc1f0 u0 com.android.settings/.UsbSettings t2}
W/BaseAppContext( 1851): Using Auth Proxy for data requests.
W/BaseAppContext( 1851): Using Auth Proxy for data requests.
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/PeopleContactsSync( 1851): CP2 sync disabled
I/dalvikvm( 1851): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1851): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1851): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1851): Using Auth Proxy for data requests.
D/dalvikvm( 1851): GC_EXPLICIT freed 834K, 23% free 19168K/24836K, paused 2ms+6ms, total 70ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/BaseAppContext( 1851): Using Auth Proxy for data requests.
W/BaseAppContext( 1851): Using Auth Proxy for data requests.
W/BaseAppContext( 1851): Using Auth Proxy for data requests.
D/AndroidRuntime( 4684): 
D/AndroidRuntime( 4684): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4684): CheckJNI is OFF
D/dalvikvm( 4684): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4684): Added shared lib libjavacore.so 0x0
D/dalvikvm( 1554): GC_EXPLICIT freed 1196K, 29% free 17821K/24836K, paused 1ms+3ms, total 23ms
D/dalvikvm( 4684): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4684): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4684): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/ConfigFetchService( 1851): fetch service done; releasing wakelock
I/ConfigFetchService( 1851): stopping self
D/dalvikvm( 4684): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  963): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/ChimeraCfgMgr( 1851): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1851): Module APK com.google.android.play.games already loaded
E/memtrack( 4684): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4684): failed to load memtrack module: -2
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/AndroidRuntime( 4684): Calling main entry com.android.commands.am.Am
I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4684
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (106 us)
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{432fc1f0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  963): startService SlideAside
W/ContextImpl(  963): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{433123a0 stackId=1, 2 tasks}
D/AndroidRuntime( 4684): Shutting down VM
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{432fc1f0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/dalvikvm( 4684): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/UsbSettingsControl( 2637): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2637): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 4083): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{432fc1f0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  963): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4705 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 4083): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/SlideAside( 4083): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4705): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4705): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4705): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4705): Binding Chromium to the background looper Looper (main, tid 1) {42858c40}
I/chromium( 4705): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4705): Initializing chromium process, renderers=0
W/chromium( 4705): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4705): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4705): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4705): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4705): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4705): Remote Branch: 
I/Adreno-EGL( 4705): Local Patches: 
I/Adreno-EGL( 4705): Reconstruct Branch: 
I/dalvikvm( 4705): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4705): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4705): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4705): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4705): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4705): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4705): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4705): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4705): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4705): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4705): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4705): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4705): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4705): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4705): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4705): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4705): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4705): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4705): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4705): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4705): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4705): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4705): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4705): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4705): Enabling debug mode 0
,W/AwContents( 4705): nativeOnDraw failed; clearing to background color.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  963): Displayed com.test.thalitest/.MainActivity: +359ms
,W/AwContents( 4705): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  963): IME STATUS OFF
,I/ActivityManager( 4705): Timeline: Activity_idle id: android.os.BinderProxy@4285a320 time:108449
,D/JsMessageQueue( 4705): Set native->JS mode to OnlineEventsBridgeMode
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2051): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2051): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/dalvikvm( 4705): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4285e838
,D/dalvikvm( 4705): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4285e838
,D/jxcore_app_log( 4705): JniHelper::setJavaVM(0x41723838), pthread_self() = 1631041080
,D/JX-Cordova( 4705): jxcore cordova android initializing
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3} time:108858
D/ActivityManager(  963): no-history finish of ActivityRecord{432fc1f0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  963): Finishing activity token=Token{42daef08 ActivityRecord{432fc1f0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
,D/UsbSettings( 2637): [AUTORUN] onStop()
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{432fc1f0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{432fc1f0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{432fc1f0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 4705): GC_CONCURRENT freed 2821K, 13% free 21826K/24836K, paused 1ms+2ms, total 47ms
,D/dalvikvm( 4705): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4705): GC_FOR_ALLOC freed 152K, 13% free 21820K/24836K, paused 21ms, total 21ms
D/dalvikvm( 4705): GC_FOR_ALLOC freed 169K, 12% free 21863K/24836K, paused 22ms, total 22ms
I/dalvikvm-heap( 4705): Grow heap (frag case) to 23.666MB for 144892-byte allocation
D/dalvikvm( 4705): GC_FOR_ALLOC freed 262K, 13% free 21902K/24980K, paused 21ms, total 21ms
I/dalvikvm-heap( 4705): Grow heap (frag case) to 23.773MB for 217334-byte allocation
D/dalvikvm( 4705): GC_FOR_ALLOC freed 369K, 13% free 21977K/25196K, paused 21ms, total 21ms
I/dalvikvm-heap( 4705): Grow heap (frag case) to 23.950MB for 325996-byte allocation
D/dalvikvm( 4705): GC_FOR_ALLOC freed 568K, 14% free 22098K/25516K, paused 22ms, total 22ms
I/dalvikvm-heap( 4705): Grow heap (frag case) to 24.224MB for 488990-byte allocation
D/dalvikvm( 4705): GC_FOR_ALLOC freed 867K, 15% free 22275K/25996K, paused 21ms, total 21ms
I/dalvikvm-heap( 4705): Grow heap (frag case) to 24.630MB for 733480-byte allocation
D/dalvikvm( 4705): GC_FOR_ALLOC freed 1283K, 16% free 22532K/26716K, paused 22ms, total 22ms
D/dalvikvm( 4705): GC_CONCURRENT freed 1674K, 15% free 22905K/26716K, paused 2ms+2ms, total 25ms
D/dalvikvm( 4705): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 4705): GC_FOR_ALLOC freed 368K, 15% free 22862K/26716K, paused 37ms, total 38ms
I/dalvikvm-heap( 4705): Grow heap (frag case) to 26.078MB for 1650320-byte allocation
D/dalvikvm( 4705): GC_CONCURRENT freed 1607K, 18% free 23426K/28328K, paused 1ms+1ms, total 25ms
,D/dalvikvm( 4705): GC_FOR_ALLOC freed 1440K, 17% free 23521K/28328K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4705): Grow heap (frag case) to 27.507MB for 2475476-byte allocation
,D/dalvikvm( 4705): GC_CONCURRENT freed 239K, 17% free 25791K/30748K, paused 2ms+2ms, total 27ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4705): GC_CONCURRENT freed 4361K, 21% free 24495K/30748K, paused 0ms+8ms, total 49ms
,D/dalvikvm( 4705): WAIT_FOR_CONCURRENT_GC blocked 47ms
,I/dalvikvm-heap( 4705): Grow heap (frag case) to 29.639MB for 3713210-byte allocation
,D/dalvikvm( 4705): GC_CONCURRENT freed 606K, 19% free 27872K/34376K, paused 2ms+3ms, total 46ms
,D/dalvikvm( 4705): GC_FOR_ALLOC freed 2864K, 27% free 25419K/34376K, paused 22ms, total 23ms
,W/jxcore-log( 4705): Initializing JXcore engine
,W/jxcore-log( 4705): JXcore engine is ready
,D/dalvikvm( 4705): GC_CONCURRENT freed 338K, 19% free 28065K/34376K, paused 1ms+2ms, total 29ms
D/dalvikvm( 4705): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/jxcore-log( 4705): Starting JXcore engine
,W/jxcore-log( 4705): Platform android
W/jxcore-log( 4705): 
,W/jxcore-log( 4705): Process ARCH arm
W/jxcore-log( 4705): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/jxcore-log( 4705): JXcore Cordova bridge is ready!
I/jxcore-log( 4705): 
W/jxcore-log( 4705): JXcore engine is started
I/chromium( 4705): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2051): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2051): nl80211: survey data missing!
D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4639): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4705): Toggling radios to true
I/jxcore-log( 4705): 
,D/BluetoothManagerService(  963): Message: 20
,D/BluetoothManagerService(  963): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44a07148:true
,D/BluetoothAdapter( 4705): enable(): BT is already enabled..!
,D/WifiStateMachine(  963): handleMessage: E msg.what=131145
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiService(  963): New client listening to asynchronous messages
D/WifiService(  963): setWifiEnabled: true pid=4705, uid=10304
E/WifiService(  963): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  963): setWifiEnabled startWifiDelaySendMsg true
,D/WifiService(  963): disconnect pid=4705, uid=10304
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doBoolean: DISCONNECT
,I/jxcore-log( 4705): Radios toggled
I/jxcore-log( 4705): 
,D/BluetoothManagerService(  963): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4705): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4705): 
,D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2051): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2051): wlan0: Cancelling scan request
D/wpa_supplicant( 2051): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2051): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2051): TDLS: Tear down peers
D/wpa_supplicant( 2051): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4705): Perf Test app loaded loaded
I/jxcore-log( 4705): 
,I/Choreographer( 4705): Skipped 68 frames!  The application may be doing too much work on its main thread.
D/WifiService(  963): reconnect pid=4705, uid=10304
,D/wpa_supplicant( 2051): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2051): wlan0: Deauthentication notification
D/wpa_supplicant( 2051): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2051): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2051): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2051): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2051): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2051): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8d62d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2051):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2051): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2051): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2051): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2051): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2051): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2051): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2051): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2051): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2051): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2051): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2051): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2051): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2051): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2051): nl80211: Event message available
D/wpa_supplicant( 2051): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received, for wlan0
D/wpa_supplicant( 2051): nl80211: Ignore disconnect event triggered during reassociation
D/wpa_supplicant( 2051): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2051): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2051): nl80211: if_removed already cleared - ignore event
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: ConnectedState
W/Settings(  963): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  963): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  963): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131146
D/WifiStateMachine(  963): processMsg: DisconnectingState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiNative-wlan0(  963): doBoolean: RECONNECT
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54,
D/wpa_supplicant( 2051): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2051): Fast associate: Old scan results
D/wpa_supplicant( 2051): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2051): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2051): wlan0: nl80211: scan request
D/wpa_supplicant( 2051): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/wpa_supplicant( 2051): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2051): nl80211: Event message available
,D/wpa_supplicant( 2051): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2051): wlan0: nl80211: Scan trigger
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
I/chromium( 4705): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147460
D/WifiStateMachine(  963): processMsg: DisconnectingState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): Network connection lost
D/WifiStateMachine(  963): Stopping DHCP and clearing IP
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  963): doBoolean: SET ps 1
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2051): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2051): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2051): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2051): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2051): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  963):    returned true
,D/DhcpStateMachine(  963): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  963): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  963): addressRemoved: 192.168.1.140/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  963): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  963): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/WifiHS20(  963): hidePasspointNotification off =false
,D/QcConnectivityService(  963): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
D/QCNEA   (  484): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  484): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  484): |CAC| updateNetCfgInfo
V/QCNEA   (  484): |CAC| *********************************************
V/QCNEA   (  484): |CAC|                   Netconfig               
V/QCNEA   (  484): |CAC| *********************************************
V/QCNEA   (  484): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  484): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  484): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  484): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  484): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  484): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  484): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  484): |CAC| *********************************************
D/QCNEA   (  484): |CAC| Received bssid= 
D/QCNEA   (  484): |CAC| net type = 3
V/QCNEA   (  484): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  484): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  484): |CAC| 	ssid           =NG700
V/QCNEA   (  484): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  484): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  484): |CAC| *********************************************
D/QCNEA   (  484): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  484): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  484): |CAC| dispatchNetCfg: updating:0xb81ec8dc
D/QCNEA   (  484): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  963): Attempting to switch to mobile
D/QcConnectivityService(  963): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=1 connState=2
,I/chromium( 4705): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/WifiStateMachine(  963): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  963): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  963): handleMessage: X
D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=131213
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131213
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
,I/ActivityManager(  963): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4757 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,D/HyLog   ( 4757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4757): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,W/NetworkManagementService(  963): route cmd failed: 
W/NetworkManagementService(  963): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  963): '
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  963): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  963): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  963): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  963): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/NetUtils(  963): android_net_utils_resetConnections in env=0x6287ca28 clazz=0x6cf00001 iface=wlan0 mask=0x3
,I/jxcore-log( 4705): check test folder
I/jxcore-log( 4705): 
,I/jxcore-log( 4705): found test : ./testFindPeers.js
I/jxcore-log( 4705): 
D/QcConnectivityService(  963): resetConnections(wlan0, 3)
,I/PCSuite ( 4757): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 4757): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4757): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/NativeCrypto( 1554): Read error: ssl=0x6252abd0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1554): SSL shutdown failed: ssl=0x6252abd0: I/O error during system call, Broken pipe
,I/ActivityManager(  963): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4793 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  963): Killing 4198:com.google.android.talk/u0a77 (adj 15): empty #17
,I/jxcore-log( 4705): found test : ./testSendData.js
I/jxcore-log( 4705): 
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
D/GpsLocationProvider(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/HyLog   ( 4793): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4793): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4793): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4793): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4793): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4793): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4793): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4793): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4793): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4793): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4793): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4793): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  963): Killing 3946:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
,I/chromium( 4705): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/DhcpStateMachine(  963): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.452240 Y: -0.404114 Z: 9.765244 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452240 .y:-0.404114 .z:9.765244
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/ConfigService( 1554): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.468124 Y: -0.414337 Z: 9.759293 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.468124 .y:-0.414337 .z:9.759293
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4057): onReceive
,D/AppUp4:CustFacade( 4057): Context : android.app.ReceiverRestrictedContext@42875ec0
D/AppUp4:CustFacade( 4057): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4057): isOpenOperator : true
,D/AppUp4:CustFacade( 4057): isPhone : true
,I/LicenseContentProvider( 3053): start selecting data
,D/SIMObserver( 3053): simInfo1
,I/AppUp4:EulaManager( 4057): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4057): begin check event
,I/AppUp4:CustModeStarterReceiver( 4057): Event For GoodConnectivity
,D/wpa_supplicant( 2051): nl80211: Event message available
D/wpa_supplicant( 2051): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2051): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2051): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2051): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 2051): nl80211: Survey data missing
D/wpa_supplicant( 2051): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2051): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 2051): wlan0: New scan results available
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2051): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2051): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2051): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2051): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2051): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2051): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2051): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2051): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2051): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-46 wps
D/wpa_supplicant( 2051): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2051): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2051): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2051): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2051): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2051): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2051): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2051): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2051): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2051): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2051): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8d645a8  current_ssid=0x0
D/wpa_supplicant( 2051): scard is not null..
D/wpa_supplicant( 2051): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2051): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2051): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2051): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2051): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2051): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2051): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2051): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2051): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2051): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2051): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2051): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f a,c 02 00 00
D/wpa_supplicant( 2051): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2051): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2051): wlan0: Cancelling scan request
D/wpa_supplicant( 2051): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2051): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2051): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2051): RSN: PMKSA cache search - network_ctx=0xb8d645a8 try_opportunistic=0
D/wpa_supplicant( 2051): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2051): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2051): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2051): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2051): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2051): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2051): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2051): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2051): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2051): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2051): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2051): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2051): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2051): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2051): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2051): nl80211: Unsubscribe mgmt frames handle 0xb8d63590 (mode change)
D/wpa_supplicant( 2051): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8d63590
D/wpa_supplicant( 2051): nl80211: Register frame type=0xd0 nl_handle=0xb8d63590
D/wpa_supplicant( 2051): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2051): nl80211: Register frame type=0xd0 nl_handle=0xb8d63590
D/wpa_supplicant( 2051): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2051): nl80211: Register frame type=0xd0 nl_handle=0xb8d63590
D/wpa_supplicant( 2051): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2051): nl80211: Register frame type=0xd0 nl_handle=0xb8d63590
D/wpa_supplicant( 2051): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2051): nl80211: Register frame type=0xd0 nl_handle=0xb8d63590
D/wpa_supplicant( 2051): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2051): nl80211: Register frame type=0xd0 nl_handle=0xb8d63590
D/wpa_supplicant( 2051): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2051): nl80211: Register frame type=0xd0 nl_handle=0xb8d63590
D/wpa_supplicant( 2051): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2051): nl80211: Register frame type=0xd0 nl_handle=0xb8d63590
D/wpa_supplicant( 2051): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2051): nl80211: Register frame type=0xd0 nl_handle=0xb8d63590
D/wpa_supplicant( 2051): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2051): nl80211: Register frame type=0xd0 nl_handle=0xb8d63590
D/wpa_supplicant( 2051): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2051): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2051):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051):   * freq=2412
D/wpa_supplicant( 2051):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2051):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2051):   * Auth Type 0
D/wpa_supplicant( 2051):   * WPA Versions 0x2
D/WifiMonitor(  963): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  963): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2051): nl80211: Connect request send successfully
D/wpa_supplicant( 2051): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2051): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2051): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2051): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2051): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2051): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2051): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  963): handleMessage: E msg.what=147461
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  963): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2051): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/EAS     ( 4622): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/wpa_supplicant( 2051): nl80211: Event message available
D/wpa_supplicant( 2051): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2051): nl80211: Connect event
D/wpa_supplicant( 2051): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2051): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2051): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2051): wlan0: Association info event
D/wpa_supplicant( 2051): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2051): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2051): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2051): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2051): wlan0: freq=2412 MHz
D/wpa_supplicant( 2051): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2051): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2051): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2051): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2051): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2051): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): scard is not null..
D/wpa_supplicant( 2051): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2051): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2051): TDLS: Remove peers on association
D/wpa_supplicant( 2051): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2051): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2051): EAPOL: enable timer tick
D/wpa_supplicant( 2051): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2051): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2051): wlan0: Cancelling scan request
D/wpa_supplicant( 2051): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2051): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2051): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2051): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2051): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2051): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2051): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2051): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2051): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2051): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  963): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  963): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c3 76 4e a4 52 e7 2f cb 35 54 ff 0a b4 5f 13 ...
D/wpa_supplicant( 2051): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2051): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2051): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2051): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2051): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2051):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2051):   key_nonce - hexdump(len=32): c3 76 4e a4 52 e7 2f cb 35 54 ff 0a b4 5f 13 5d e0 a8 9a fd c4 a8 f0 13 85 d5 ca c0 dd ff f1 41
D/wpa_supplicant( 2051):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2051):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2051):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2051):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2051): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c3 76 4e a4 52 e7 2f cb 35 54 ff 0a b4 5f 13 ...
D/wpa_supplicant( 2051): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2051): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2051): Get randomness: len=32 entropy=9
D/wpa_supplicant( 2051): WPA: Renewed SNonce - hexdump(len=32): 76 6f da 17 c4 97 d3 88 7d f0 47 81 8b 3f dd c9 40 9b 93 c3 a5 43 84 3e 71 eb b8 4b f1 0f 32 72
D/wpa_supplicant( 2051): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): WPA: Nonce1 - hexdump(len=32): 76 6f da 17 c4 97 d3 88 7d f0 47 81 8b 3f dd c9 40 9b 93 c3 a5 43 84 3e 71 eb b8 4b f1 0f 32 72
D/wpa_supplicant( 2051): WPA: Nonce2 - hexdump(len=32): c3 76 4e a4 52 e7 2f cb 35 54 ff 0a b4 5f 13 5d e0 a8 9a fd c4 a8 f0 13 85 d5 ca c0 dd ff f1 41
D/wpa_supplicant( 2051): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2051): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2051): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2051): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2051): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2051): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2051): WPA: Derived Key MIC - hexdump(len=16): 4c b1 2f b6 98 02 e2 8e ae f6 02 b3 11 c8 27 d5
D/wpa_supplicant( 2051): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 76 6f da 17 c4 97 d3 88 7d f0 47 81 8b 3f dd ...
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  963): processMsg: ConnectModeState
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2051): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c3 76 4e a4 52 e7 2f cb 35 54 ff 0a b4 5f 13 ...
D/wpa_supplicant( 2051): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2051): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2051): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/wpa_supplicant( 2051): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2051):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2051):   key_nonce - hexdump(len=32): c3 76 4e a4 52 e7 2f cb 35 54 ff 0a b4 5f 13 5d e0 a8 9a fd c4 a8 f0 13 85 d5 ca c0 dd ff f1 41
D/wpa_supplicant( 2051):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2051):   key_rsc - hexdump(len=8): a0 7a 00 00 00 00 00 00
D/wpa_supplicant( 2051):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2051):   key_mic - hexdump(len=16): e8 fa a0 a6 28 ca a5 ce 36 50 79 19 ce f7 6c c1
D/wpa_supplicant( 2051): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c3 76 4e a4 52 e7 2f cb 35 54 ff 0a b4 5f 13 ...
D/wpa_supplicant( 2051): RSN: encrypted key data - hexdump(len=56): a4 6e 85 69 d7 36 bd bc e6 c3 5d a2 27 03 fe 0b 4c b4 73 8b 7a 70 1b a9 d4 a1 b1 ea 57 5f 80 9a ...
D/wpa_supplicant( 2051): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2051): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2051): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2051): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 da 36 ...
D/wpa_supplicant( 2051): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2051): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2051): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2051): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2051): WPA: Derived Key MIC - hexdump(len=16): 21 bf d7 6e 77 d0 49 c4 ec 4e 7e b4 99 14 86 42
D/wpa_supplicant( 2051): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2051): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8d63c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2051):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/wpa_supplicant( 2051): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2051): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2051): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2051): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2051): WPA: RSC - hexdump(len=6): a0 7a 00 00 00 00
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f9b03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2051):    broadcast key
D/EAS     ( 4622): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2051): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2051): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2051): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2051): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2051): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2051): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2051): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2051): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2051): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2051): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2051): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2051): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2051): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2051): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2051): EAPOL authentication completed successfully
D/wpa_supplicant( 2051): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2051): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2051): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  963): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  963): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): Network connection established
D/WifiNative-wlan0(  963): doString: STATUS
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2051): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/eas_req ( 4622): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  963):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  963): ssid=NG700
D/WifiNative-wlan0(  963): id=0
D/WifiNative-wlan0(  963): mode=station
D/WifiNative-wlan0(  963): pairwise_cipher=CCMP
D/WifiNative-wlan0(  963): group_cipher=CCMP
D/WifiNative-wlan0(  963): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  963): wpa_state=COMPLETED
D/WifiNative-wlan0(  963): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  963): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  963): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  963): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  963): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: DisconnectedState
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/LgeMiscReceiver( 4358): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4358): action = android.net.conn.CONNECTIVITY_CHANGE
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
I/LgeMiscReceiver( 4358): networkInfo.isConnected() = false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  963): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  963): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  963): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  963): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  963): WaitBeforeStartState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-13ms what=147462 obj=android.net.wifi.StateChangeResult@43d14340 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-24ms what=147462 obj=android.net.wifi.StateChangeResult@44333390 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-25ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-17ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2051): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2051): nl80211: survey data missing!
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196612
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-19ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2051): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
W/linker  ( 4622): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4622): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4622): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4622): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
E/Parcel  (  484): Reading a NULL string not supported here.
I/dalvikvm( 4622): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
I/ActivityManager(  963): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4843 uid=10052 gids={50052, 3003}
D/HtmlEditor( 4622): register_HtmlEditor, Success
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
D/HtmlEditor( 4622): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4622): register_HtmlEditorTimer, Success
D/HtmlEditor( 4622): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4622): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4622): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4622): register_HtmlEditorFont, Success
D/HtmlEditor( 4622): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4622): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4622): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/HtmlEditor( 4622): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4622): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4622): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4622): JNI_OnLoad Success
I/HubEmail( 4622): JNI_OnLoad()
I/HubEmail( 4622): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4622): registerNatives()
I/HubEmail( 4622): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4622): registerNativeMethods()
I/HubEmail( 4622): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4622): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 4843): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4843): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4843): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4843): [loadRssi] File not exist 
V/LGRssiData( 4843): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4843): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4843): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4843): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4843): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4843): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 4843): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4843): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 4843): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4843): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4843): [getValue] FEATURE key : vzw_roaming_state, value : null
E/PhoneMonitor( 4843): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4843): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/ActivityManager(  963): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4859 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  963): Killing 4403:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  963): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HyLog   ( 4859): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4859): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4859): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 2051): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  963): doBoolean: SET ps 0
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2051): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2051): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2051): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
,D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2051): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2051): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING STOP
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2051): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2051): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  963): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  963): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
D/WifiStateMachine(  963): addressUpdated: 192.168.1.140/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  963): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
,D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.140/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196613
,D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  963): doBoolean: SET ps 1
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432d3a30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432d3a30 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2051): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2051): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2051): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2051): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2051): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
,D/WifiStateMachine(  963): DHCP successful
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  963): invokeEnterMethods: VerifyingLinkState
,D/WifiStateMachine(  963): VerifyingLinkState enter
,D/WifiStateMachine(  963): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  963): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  963): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4873 uid=10066 gids={50066, 4002, 3003, 1028}
,D/WifiStateMachine(  963): handleMessage: X
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  963): send additional Connectivity Action
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
D/WifiStateMachine(  963): handleMessage: E msg.what=135190
D/WifiStateMachine(  963): processMsg: VerifyingLinkState
D/WifiStateMachine(  963): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  963): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/Parcel  (  484): Reading a NULL string not supported here.
D/WifiStateMachine(  963): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  963): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): CaptivePortalCheckState enter
D/WifiStateMachine(  963): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
I/ActivityManager(  963): Killing 4547:com.android.defcontainer/u0a4 (adj 15): empty #17
W/WifiStateTracker(  963): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  963): 
W/WifiStateTracker(  963):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  963):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  963): handleMessage: X
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  484): Reading a NULL string not supported here.
,D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  963): handleMessage: E msg.what=131092
D/WifiStateMachine(  963): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  963): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/QcConnectivityService(  963): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  963): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/WifiStateMachine(  963): transitionTo: destState=ConnectedState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  963): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
D/HyLog   ( 4873): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/HyLog   ( 4873): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4873): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,E/Parcel  (  484): Reading a NULL string not supported here.
E/ActivityThread(  963): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=2 connState=1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/        (  264): RouteController
,I/ActivityManager(  963): Killing 4580:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2943): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/        (  264): RouteController
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
,D/LGDMClient( 2943): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  963): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4892 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/LGDMClient( 2943): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/        (  264): RouteController
E/LGDMClient( 2943): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2943): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2943): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2943): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/        (  264): RouteController
V/        (  264): RouteController
D/HyLog   ( 4892): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4892): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4892): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
,D/LGDMSGCM( 4892): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4892): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager(  963): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4915 uid=10101 gids={50101, 1028, 1015, 3003}
,D/QCNEA   (  484): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  484): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  484): |CAC| updateNetCfgInfo
V/QCNEA   (  484): |CAC| *********************************************
V/QCNEA   (  484): |CAC|                   Netconfig               
V/QCNEA   (  484): |CAC| *********************************************
V/QCNEA   (  484): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  484): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  484): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  484): |CAC| 	NetConfig: ip4        =192.168.1.140
V/QCNEA   (  484): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  484): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  484): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  484): |CAC| *********************************************
D/QCNEA   (  484): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  484): |CAC| net type = 1
V/QCNEA   (  484): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  484): |CAC| Received ssid= NG700
V/QCNEA   (  484): |CAC| 	ssid           =NG700
V/QCNEA   (  484): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  484): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  484): |CAC| *********************************************
D/QCNEA   (  484): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  484): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  484): |CAC| dispatchNetCfg: updating:0xb81ec8dc
,D/QCNEA   (  484): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/ActivityManager(  963): Killing 4609:com.lge.bnr/1000 (adj 15): empty #17
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/HyLog   ( 4915): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4915): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4915): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1851): Checking schedule, now: 1450312773234 next: 1450312718178
,I/CheckinService( 1851): active receiver: enabled
,I/CheckinService( 1851): Preparing to send checkin request
,I/EventLogService( 1851): Accumulating logs since 1450312685343
,I/NFS     ( 4915): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4915): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4915): intf.getDisplayName() = lo
I/Wireless_Storage( 4915): intf.getDisplayName() = sit0
,I/Wireless_Storage( 4915): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4915): intf.getDisplayName() = teql0
I/Wireless_Storage( 4915): intf.getDisplayName() = wlan0
D/NFS     ( 4915): interface name:wlan0 name:wlan0
D/NFS     ( 4915): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4915): interface name:wlan0 name:wlan0
D/DhcpStateMachine(  963): DHCP request on wlan0
D/NFS     ( 4915): addr:192.168.1.140 broadcast:192.168.1.255
,I/Wireless_Storage( 4915): CONNECT : WIFI_CONNECT
,D/LgDhcpStateMachineHelper(  963): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinRequestBuilder( 1851): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  963): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4931 uid=10104 gids={50104, 3003, 1028, 1015}
I/ActivityManager(  963): Killing 4248:com.android.contacts/u0a21 (adj 15): empty #17
E/ActivityThread( 1851): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 4931): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4931): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4931): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  963): GC_EXPLICIT freed 23287K, 49% free 29706K/57552K, paused 3ms+8ms, total 127ms
,W/GAV2    ( 4931): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1851): awaiting user notification for token
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x431070e0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  963): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4976 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4976): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4976): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4976): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24836K, paused 2ms+3ms, total 29ms
W/dalvikvm( 4976): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4976): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4976): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4976): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4976): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4976): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4976): install
,V/WebViewChromium( 4931): Binding Chromium to the main looper Looper (main, tid 1) {428615b8}
I/chromium( 4931): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/MultiDex( 4976): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/BrowserProcessMain( 4931): Initializing chromium process, renderers=0
,I/MultiDex( 4976): loading existing secondary dex files
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 2ms+3ms, total 22ms
,I/MultiDex( 4976): load found 3 secondary dex files
,I/MultiDex( 4976): install done
,W/chromium( 4931): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4931): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4931): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4931): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4931): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4931): Remote Branch: 
I/Adreno-EGL( 4931): Local Patches: 
I/Adreno-EGL( 4931): Reconstruct Branch: 
,D/dalvikvm( 4976): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4976): VFY: unable to resolve instance field 61
,D/dalvikvm( 4976): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4976): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4976): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4976): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4976): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4976): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4976): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4976): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4976): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+2ms, total 21ms
,D/dalvikvm( 4976): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42868768
,D/dalvikvm( 4976): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42868768
,D/dalvikvm( 4976): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42868768, skipping init
,D/dalvikvm( 4976): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42868768
,D/dalvikvm( 4976): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42868768
,V/JNIHelp ( 4976): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 4931): Starting up...
,I/ActivityManager(  963): Killing 4263:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4793): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4793): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4793): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4793): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/dalvikvm( 4976): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42868768
,D/dalvikvm( 4976): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42868768
D/dalvikvm( 4976): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42868768
,D/dalvikvm( 4976): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42868768
,D/DhcpStateMachine(  963): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  963): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  963): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.140
,V/LgDhcpStateMachineHelper(  963): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  963): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  963): DHCP Start/Renew wake lock is released.
D/QRemote ( 4793): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/DhcpStateMachine(  963): RunningState
,I/QRemote ( 4793): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4757): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4757): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4793): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4793): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4793): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4793): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 4976): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1554): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1554): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1851): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3419): callingUid 10006, callindPid: 3419
,D/LocationInitializer( 1851): Restart initialization of location
,E/MDM     ( 1424): [67] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 4976): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4976): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4976): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4976): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4976): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4976): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f91000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f91000
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=2156218435
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2051): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2051): EAPOL: disable timer tick
,D/dalvikvm( 4976): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a49738
D/dalvikvm( 4976): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a49738
,D/dalvikvm( 4976): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a49738, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4976): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 5011): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4976): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4976): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 64ms
,I/Adreno-EGL( 4976): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4976): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4976): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4976): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4976): Remote Branch: 
I/Adreno-EGL( 4976): Local Patches: 
I/Adreno-EGL( 4976): Reconstruct Branch: 
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  963): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Adreno-EGL( 4976): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4976): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4976): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4976): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4976): Remote Branch: 
I/Adreno-EGL( 4976): Local Patches: 
I/Adreno-EGL( 4976): Reconstruct Branch: 
,I/Adreno-EGL( 4976): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4976): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4976): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4976): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4976): Remote Branch: 
I/Adreno-EGL( 4976): Local Patches: 
I/Adreno-EGL( 4976): Reconstruct Branch: 
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,I/jxcore-log( 4705): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4705): 
D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=819401241
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Settings( 4976): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1851): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  963): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  963): send additional Connectivity Action
,D/WifiStateMachine(  963): handleMessage: X
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QcConnectivityService(  963): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  963):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  963): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1851): GC_CONCURRENT freed 1578K, 22% free 19540K/24836K, paused 10ms+7ms, total 86ms
,I/CheckinTask( 1851): Sending checkin request (11590 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1851): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1851): Failed to find provider info for com.google.android.wearable.settings
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2051): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2051): nl80211: survey data missing!
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  963): handleMessage: X
E/Parcel  (  484): Reading a NULL string not supported here.
,E/Parcel  (  484): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x42b42f60: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1851): awaiting user notification for token
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1851): Classify the device as Phone.
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] request level :IDLE....
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/AppUp4:CustModeStarterReceiver( 4057): onReceive
,D/AppUp4:CustFacade( 4057): Context : android.app.ReceiverRestrictedContext@42875ec0
D/AppUp4:CustFacade( 4057): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4057): isOpenOperator : true
,D/AppUp4:CustFacade( 4057): isPhone : true
,I/LicenseContentProvider( 3053): start selecting data
,D/SIMObserver( 3053): simInfo1
,I/CheckinTask( 1851): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/AppUp4:EulaManager( 4057): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4057): begin check event
I/AppUp4:CustModeStarterReceiver( 4057): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4057): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4057): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4057): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4057): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4057): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 2148): DownloadService onCreate
I/CheckinService( 1851): Checking schedule, now: 1450312776152 next: 1450890172146
I/CheckinService( 1851): active receiver: disabled
,I/DownloadManager( 2148): in removeSpuriousFiles
,D/EAS     ( 4622): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4622): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 2148): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/eas_req ( 4622): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 2148): created cursor android.database.sqlite.SQLiteCursor@42951c28 on behalf of 2148
,I/DownloadManager( 2148): in trimDatabase
V/DownloadManager( 2148): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 2148): created cursor android.database.sqlite.SQLiteCursor@428ead78 on behalf of 2148
,V/DownloadManager( 2148): DownloadService onStartCommand
,V/DownloadManager( 2148): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 2148): created cursor android.database.sqlite.SQLiteCursor@4286e348 on behalf of 2148
I/LgeMiscReceiver( 4358): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4358): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 2148): DownloadService onDestroy
,I/LgeMiscReceiver( 4358): networkInfo.isConnected() = false
,W/Settings( 4622): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4843): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4843): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2943): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4892): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2943): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,I/LGDMClient( 2943): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4915): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4915): CONNECT : WIFI_CONNECT
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 4892): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2943): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2943): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2943): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/LGDMClient( 2943): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/CheckinService( 1851): Checking schedule, now: 1450312776244 next: 1450890172146
,I/CheckinService( 1851): active receiver: disabled
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4057): onReceive
D/AppUp4:CustFacade( 4057): Context : android.app.ReceiverRestrictedContext@42875ec0
D/AppUp4:CustFacade( 4057): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4057): isOpenOperator : true
,D/AppUp4:CustFacade( 4057): isPhone : true
I/LicenseContentProvider( 3053): start selecting data
,D/SIMObserver( 3053): simInfo1
,I/AppUp4:EulaManager( 4057): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4057): begin check event
,I/AppUp4:CustModeStarterReceiver( 4057): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 2148): DownloadService onCreate
,I/DownloadManager( 2148): in removeSpuriousFiles
,D/EAS     ( 4622): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 2148): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4622): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 2148): created cursor android.database.sqlite.SQLiteCursor@428f4498 on behalf of 2148
V/DownloadManager( 2148): DownloadService onStartCommand
,V/DownloadManager( 2148): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 2148): in trimDatabase
V/DownloadManager( 2148): created cursor android.database.sqlite.SQLiteCursor@42937618 on behalf of 2148
,V/DownloadManager( 2148): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4358): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4358): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4358): networkInfo.isConnected() = true
,D/PhoneState( 4358): setPdpRejectCasuse : false
,V/DownloadManager( 2148): created cursor android.database.sqlite.SQLiteCursor@4293fd10 on behalf of 2148
V/DownloadManager( 2148): DownloadService onDestroy
,D/MobileConnectivityChangeReceiver( 4843): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4843): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4622): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2943): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2943): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4892): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2943): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4892): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4915): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4915): CONNECT : WIFI_CONNECT
E/LGDMClient( 2943): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2943): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2943): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2943): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/GCM     ( 1554): Connected
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1554): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3,
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1156): GC_CONCURRENT freed 2887K, 11% free 25443K/28512K, paused 2ms+4ms, total 42ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4057): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4057): onReceive
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AppUp4:CustFacade( 4057): Context : android.app.ReceiverRestrictedContext@42875ec0
D/AppUp4:CustFacade( 4057): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4057): isOpenOperator : true
D/AppUp4:CustFacade( 4057): isPhone : true
I/LicenseContentProvider( 3053): start selecting data
D/SIMObserver( 3053): simInfo1
I/AppUp4:EulaManager( 4057): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4057): begin check event
I/AppUp4:CustModeStarterReceiver( 4057): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 2148): DownloadService onCreate
,D/EAS     ( 4622): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4622): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 2148): in removeSpuriousFiles
,V/DownloadManager( 2148): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 2148): created cursor android.database.sqlite.SQLiteCursor@428b89a8 on behalf of 2148
,V/DownloadManager( 2148): DownloadService onStartCommand
I/DownloadManager( 2148): in trimDatabase
I/LgeMiscReceiver( 4358): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4358): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 2148): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4358): networkInfo.isConnected() = true
,D/PhoneState( 4358): setPdpRejectCasuse : false
,V/DownloadManager( 2148): created cursor android.database.sqlite.SQLiteCursor@4286f6e8 on behalf of 2148
,W/Settings( 4622): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4843): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,V/DownloadManager( 2148): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/MobileConnectivityChangeReceiver( 4843): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 2148): created cursor android.database.sqlite.SQLiteCursor@428f2c20 on behalf of 2148
,V/DownloadManager( 2148): DownloadService onDestroy
,D/LGDMClient( 2943): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4892): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2943): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 4892): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2943): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4915): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4915): CONNECT : WIFI_CONNECT
E/LGDMClient( 2943): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2943): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2943): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2943): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  963): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4931): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2051): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2051): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4285): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4285): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  963): Killing 4639:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2051): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2051): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
E/Parcel  (  484): Reading a NULL string not supported here.
,E/Parcel  (  484): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.442169 Y: -0.396896 Z: 9.774246 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442169 .y:-0.396896 .z:9.774246
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.451889 Y: -0.406326 Z: 9.760956 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451889 .y:-0.406326 .z:9.760956
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/InputReader(  963): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  963): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5115 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,E/SlideAside( 4083): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 4083): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
D/administrator(  963): Handling package changes for user 0
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HyLog   ( 5115): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5115): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5115): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  963):   Scheme: "smsto"
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1424): DISABLE
,D/dalvikvm(  963): GC_EXPLICIT freed 3018K, 49% free 29776K/57552K, paused 4ms+9ms, total 112ms
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  963): applying state to connected service
,D/LocationProviderProxy(  963): applying state to connected service
,I/MediaCodecList( 5115): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 5115): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5115): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/Babel   ( 5115): MmsConfig: mnc/mcc: 0/0
I/MediaCodecList( 5115): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 5115): MmsConfig.loadMmsSettings
,I/Babel   ( 5115): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5115): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5115): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5115): MmsConfig.loadFromResources
,E/Babel   ( 5115): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 5115): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5115): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5115): [loadRssi] File not exist 
V/LGRssiData( 5115): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5115): [loadFeatureFromXml] *** start feature loading from xml
D/AppUp4:Utils( 4057): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4057): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4057): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4057): onReceive
,V/TelephonyAutoProfiling( 5115): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/AppUp4:CustFacade( 4057): Context : android.app.ReceiverRestrictedContext@42875ec0
D/AppUp4:CustFacade( 4057): isCustomizationCompleted : false
V/TelephonyAutoProfiling( 5115): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5115): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:CustFacade( 4057): isOpenOperator : true
D/AppUp4:CustFacade( 4057): isPhone : true
,I/LicenseContentProvider( 3053): start selecting data
,D/SIMObserver( 3053): simInfo1
,I/AppUp4:EulaManager( 4057): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4057): begin check event
D/AppUp4:Utils( 4057): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4057): Event For Nothing, skip.
,I/ActivityManager(  963): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5163 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5163): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5163): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5163): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5163): BUILD Country: EU
,I/SystemConfig( 5163): BUILD Operator: OPEN
I/ActivityManager(  963): Killing 4757:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  963): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5176 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/SystemConfig( 5163): systemFeature RCS result false
,D/SystemConfig( 5163): refreshRcsSupport() :false
I/ActivityManager(  963): Killing 4793:com.lge.qremote/u0a96 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
,D/HyLog   ( 5176): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5176): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5176): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
,I/IcingCorporaProvider( 2712): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  963): Killing 2148:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1851): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1851): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  963): Delaying start of: ServiceRecord{43d41670 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1851): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2712): UpdateCorporaTask done [took 200 ms] updated apps [took 200 ms] 
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2051): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2051): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  963): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  963): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  963): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  963): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  963): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2051): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2051): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV4    ( 5115): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2051): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2051): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2051): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2051): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
E/Parcel  (  484): Reading a NULL string not supported here.
,E/Parcel  (  484): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PowerManagerService(  963): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  963): [updateScreenState] screen on = false
D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  963): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, enabled=1
,D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8244 usec
,D/qcom_sensors_hal(  963): hal_acquire_resources
,I/qcom_sensors_hal(  963): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  963): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  963): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  963): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  963): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  963): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  963): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  963): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.455765 Y: -0.398178 Z: 9.757629 
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.451324 Y: -0.378174 Z: 9.788757 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.455765 .y:-0.398178 .z:9.757629
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Sensors (  459): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.451141 Y: -0.408585 Z: 9.785690 
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451141 .y:-0.408585 .z:9.785690
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  963): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  963): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  963): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  963): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  963): proximitySensorChanged  positive = true
I/KnockOnPowerController(  963): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.454086 Y: -0.393448 Z: 9.791092 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454086 .y:-0.393448 .z:9.791092
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.451157 Y: -0.400040 Z: 9.768311 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451157 .y:-0.400040 .z:9.768311
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.436249 Y: -0.418991 Z: 9.785065 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.436249 .y:-0.418991 .z:9.785065
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.440384 Y: -0.412048 Z: 9.788544 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440384 .y:-0.412048 .z:9.788544
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  963): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43361730)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/KeyguardViewMediator( 1142): handleNotifyScreenOn
D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  963): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,I/WindowManager(  963): No lock screen! windowToken=null
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8c8c450
D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.441864 Y: -0.394897 Z: 9.779022 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441864 .y:-0.394897 .z:9.779022
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,E/SlideAside( 4083): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WifiStateMachine(  963): handleScreenStateChanged: true
,D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2051): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  963): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2051): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  963): handleMessage: E msg.what=131127
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=132097
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  963): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2051): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2051): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiOffDelayIfNotUsed(  963): stopMonitoring
E/Parcel  (  484): Reading a NULL string not supported here.
,E/Parcel  (  484): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 963
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{428a0850 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherAncestor( 1821): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:39:55
I/SlideAside( 4083): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/UpdateThreadPoolManager( 1821): 2 : This is isUpdating : false
D/WeatherAncestor( 1821): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:39:55
D/WeatherService( 1821): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1156): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1156): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1156): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1156): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 225, B = 225
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/qdlights( 1156): set_light_notifications: 2,ff00dbdb,10,0,2
D/SurfaceControl(  963): Excessive delay in blankDisplay() while turning screen off: 397ms
,D/qdlights( 1156): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1156): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1156): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,D/qdlights( 1156): [Current] = 255, R = 0, G = 93, B = 93
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.452789 Y: -0.394150 Z: 9.792831 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452789 .y:-0.394150 .z:9.792831
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/qdlights( 1156): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1156): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1156): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 75, B = 75
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.453522 Y: -0.397278 Z: 9.789551 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453522 .y:-0.397278 .z:9.789551
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/qdlights( 1156): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1156): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1156): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1156): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 51, B = 51
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450312796394, nextTick: 3639, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1156): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 39, B = 39
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,D/qdlights( 1156): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1156): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1156): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 21, B = 21
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450312796446, nextTick: 3587, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/qdlights( 1156): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
,E/Parcel  (  484): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
,D/WeatherService( 1821): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:39:56
,D/WeatherService( 1821): 2 : ACTION screen on
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1821): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:39:56
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): ACTION_SCREEN_ON
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, enabled=0
,I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.455307 Y: -0.406418 Z: 9.764191 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455307 .y:-0.406418 .z:9.764191
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/qcom_sensors_hal(  963): hal_acquire_resources
D/qcom_sensors_hal(  963): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  963): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3}
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  963): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  963): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  963): hal_smgr_report_delete: Rcvd success response from request
,V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/UsbSettings( 2637): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2637): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2637): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2637): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  963): Vibrator off
,D/WifiStateMachine(  963): handleScreenStateChanged: false
D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  963): doBoolean: DRIVER SETSUSPENDMODE 1
E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 963
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{432fc1f0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  963): CMD_SCREEN_OFF 
,D/WifiController(  963): shouldWifiStayAwake TRUE
D/wpa_supplicant( 2051): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2051): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
,D/KeyguardViewManager( 1142): onScreenTurnedOff()
,D/wpa_supplicant( 2051): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  963):    returned true
,D/WifiStateMachine(  963): handleMessage: X
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/EmotionalLed( 1156): RESTART MSG
D/VolumeVibrator( 1156): clear
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{432fc1f0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
,I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
E/Parcel  (  484): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WeatherService( 1821): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:39:56
D/WeatherService( 1821): 2 : ACTION screen off
D/WeatherService( 1821): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:39:56
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/NfcService( 1475): NFC-C OFF
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): ACTION_SCREEN_OFF
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,I/Sensors (  459): sns_pwr.c(320):releasing wakelock
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450312800051, nextTick: 59969, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450312800060, nextTick: 59972, mDrawingTime: 0
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1554): Vacuum at: now=1450312804886 tag=VacuumService
,I/GoogleURLConnFactory( 1554): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1554): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1554): GC_CONCURRENT freed 1826K, 28% free 18034K/24836K, paused 2ms+5ms, total 49ms
,W/Uploader( 1554): No account for auth token provided
,I/ConfigService( 1554): onCreate
,I/ConfigFetchService( 1851): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1851): running network task: configservice_periodic
,E/WakeLock( 1851): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1851): launchTask
,I/ConfigFetchService( 1851): service connected
,D/ConfigFetchService( 1851): ConfigApi connection successful.
,W/Uploader( 1554): No account for auth token provided
,W/Uploader( 1554):  no longer exists, so no auth token.
,W/Uploader( 1554): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450312813956065939; DSPS: 5272526; Offset: 1450312653051341818
,V/ConfigFetchTask( 1851): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UC1gmzJlyzXnWMpcKGXf8XY1gD4GCNYEH9vigutVrnoYCrSzznBLrD4_XeRtMBIs7jnvNRQ-0G47qCmJHJaW68Ff3unZcxbTbpPTPchWj3zKNAynI-I8JJPZf9XctPeBZTd55MQ5wFJ0XMvkxkOBVcx1VrUM-MKsMdR0y1wSle3aaOTo0MFsDXg65dpuRjXWwL9-Ce
,I/GoogleURLConnFactory( 1851): Using platform SSLCertificateSocketFactory
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1851): GC_CONCURRENT freed 1956K, 22% free 19566K/24836K, paused 4ms+5ms, total 69ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigFetchTask( 1851): updating config table for com.google.android.gms
,I/ConfigFetchService( 1851): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1851): fetch service done; releasing wakelock
,I/ConfigFetchService( 1851): stopping self
I/ConfigFetchService( 1851): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1851): GmsCore config value changed; rescheduling
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1554): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  963): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450312833958404005; DSPS: 5927962; Offset: 1450312653051360548
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigFetchService( 1851): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1851): stopping self
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450312853959736549; DSPS: 6583366; Offset: 1450312653051350319
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450312860042, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450312860049, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450312873960898677; DSPS: 7238764; Offset: 1450312653051352779
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450312893962650961; DSPS: 7894182; Offset: 1450312653051335044
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450312913963965328; DSPS: 8549585; Offset: 1450312653051337155
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450312920042, nextTick: 59986, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450312920056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450312933965705373; DSPS: 9205002; Offset: 1450312653051337698
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450312953967563543; DSPS: 9860423; Offset: 1450312653051334295
,D/wpa_supplicant( 2051): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wlan0: BSS: Remove id 7 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wlan0: BSS: Remove id 6 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2051): wlan0: BSS: Remove id 5 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2051): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 06:7c:34:12:7f:81]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 64:7c:34:12:7f:81]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 fe:94:e3:11:35:3c]
,I/jxcore-log( 4705): Connected to the server!
I/jxcore-log( 4705): 
,I/chromium( 4705): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450312973969399003; DSPS: 10515843; Offset: 1450312653051338701
,I/jxcore-log( 4705): --- start :testFindPeers.js---
I/jxcore-log( 4705): 
,I/jxcore-log( 4705): testFindPeers created [object Object]
I/jxcore-log( 4705): 
,I/jxcore-log( 4705): serverPort is 8876
I/jxcore-log( 4705): 
,I/dalvikvm( 4705): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4705): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4705): VFY: replacing opcode 0x6e at 0x0019
,I/dalvikvm( 4705): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4705): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4705): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 4705): Shutting down VM
,W/dalvikvm( 4705): threadid=1: thread exiting with uncaught exception (group=0x4181ee48)
E/AndroidRuntime( 4705): FATAL EXCEPTION: main
E/AndroidRuntime( 4705): Process: com.test.thalitest, PID: 4705
E/AndroidRuntime( 4705): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4705): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 4705): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 4705): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 4705): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 4705): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 4705): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4705): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4705): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4705): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4705): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4705): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4705): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4705): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4705): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4705): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4705): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4705): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4705): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  963):   Force finishing activity com.test.thalitest/.MainActivity
,V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3 f}
,I/ActivityManager(  963): Killing 4622:com.lge.email/u0a24 (adj 15): empty #17
,V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/Process ( 4705): Sending signal. PID: 4705 SIG: 9
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{433123a0 stackId=1, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: No more activities go home
,E/JavaBinder(  963): !!! FAILED BINDER TRANSACTION !!!
V/ActivityManager(  963): moveHomeStack:
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d9a8f8 stackId=0, 1 tasks}
,V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{42cafc60 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{42cafc60 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  963): resumeTopActivityLocked: Resumed ActivityRecord{42cafc60 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42d9a8f8 stackId=0, 1 tasks}
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{42cafc60 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{42cafc60 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiService(  963): Client connection lost with reason: 4
I/WindowState(  963): WIN DEATH: Window{44f428b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  963): Process com.test.thalitest (pid 4705) has died.
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43cb19c0 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d9a8f8 stackId=0, 1 tasks}
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{42cafc60 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{42cafc60 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: some activity pausing.
D/WeatherAncestor( 1821): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:42:57
I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
D/UpdateThreadPoolManager( 1821): 2 : This is isUpdating : false
I/[LGHome]EVENT( 1489): [Launcher.java:894:onPause()]onPause
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{42cafc60 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{42cafc60 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/WeatherAncestor( 1821): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:42:57
D/WeatherService( 1821): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
,I/[LGHome]EVENT( 1489): [Launcher.java:4955:onStop()]onStop
,I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,W/Binder  ( 1301): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1301): java.lang.NullPointerException
W/Binder  ( 1301): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1301): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1301): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1301): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  963): IME STATUS OFF
W/InputMethodManagerService(  963): Got RemoteException sending setActive(false) notification to pid 4705 uid 10304
,V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{42cafc60 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 4637K, 10% free 71126K/78372K, paused 43ms, total 43ms
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{42cafc60 u0 com.lge.launcher2/.Launcher t1} time:320793
,D/dalvikvm( 1489): GC_CONCURRENT freed 5290K, 9% free 60688K/66168K, paused 2ms+5ms, total 35ms
,D/dalvikvm( 1489): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  963): Start proc com.lge.email for content provider com.lge.email/.providers.LGEmailContentProvider: pid=5542 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,D/HyLog   ( 5542): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5542): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5542): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/LGEmail ( 5542): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 5542): EmailContentProvider.query: uri=content://com.lge.providers.lgemail/account, projection=[accountID, userName, mailAddress, accountName, InboxID], selection=null, selectionArgs=null sortOrder=null, TABLE_NAMES=EAccountmatch is 0 (at LGEmailContentProvider.java query 492)[v:null]
E/LGEmail ( 5542): Email Not Started (at LGEmailContentProvider.java query 509)[v:6.30.33]
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,D/LGEmail ( 5542): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/BaseRuntimeLoader( 5542): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5542): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5542): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5542): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@4285d050 time:321086
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1489): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450312980039, nextTick: 59973, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450312980060, nextTick: 59971, mDrawingTime: 1
,D/dalvikvm( 2690): GC_CONCURRENT freed 7763K, 32% free 16889K/24836K, paused 3ms+2ms, total 48ms
,D/dalvikvm( 2690): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  963): GC_EXPLICIT freed 1611K, 49% free 29759K/57552K, paused 8ms+10ms, total 178ms
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x42870ea0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1554): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1554): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1554): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1554): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1554): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4285): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4285): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4285): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4285): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4285): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4285): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4285): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4285): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4285): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4285): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450312993970822908; DSPS: 11171249; Offset: 1450312653051358797
,I/LocationManagerService(  963): remove 433162c0
D/LocationManagerService(  963): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  963): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2690): GC_CONCURRENT freed 1899K, 32% free 17007K/24836K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 2690): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 2690): GC_CONCURRENT freed 1767K, 31% free 17287K/24836K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2690): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 2690): GC_FOR_ALLOC freed 1622K, 30% free 17495K/24836K, paused 20ms, total 20ms
,I/Mlt MonitorService( 2690): parseLastkmsg to dump
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313013971714458; DSPS: 11826639; Offset: 1450312653051334820
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313033972585823; DSPS: 12482027; Offset: 1450312653051351693
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313040048, nextTick: 59963, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313040060, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313053973514634; DSPS: 13137418; Offset: 1450312653051334459
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313073973942533; DSPS: 13792792; Offset: 1450312653051335112
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313093974413007; DSPS: 14448167; Offset: 1450312653051347822
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313100040, nextTick: 59981, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313100046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313113974894682; DSPS: 15103543; Offset: 1450312653051341216
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313133975336709; DSPS: 15758917; Offset: 1450312653051355997
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313153975780643; DSPS: 16414292; Offset: 1450312653051342167
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313160028, nextTick: 59999, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313160054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313173976240592; DSPS: 17069667; Offset: 1450312653051344352
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313193976683668; DSPS: 17725042; Offset: 1450312653051329665
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313213979038440; DSPS: 18380479; Offset: 1450312653051334583
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313220046, nextTick: 59972, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313220055, nextTick: 59973, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313233979929183; DSPS: 19035868; Offset: 1450312653051340316
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313253980351717; DSPS: 19691242; Offset: 1450312653051335604
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313273980813500; DSPS: 20346617; Offset: 1450312653051339624
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313280039, nextTick: 59988, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313280042, nextTick: 59989, mDrawingTime: 1
,I/ActivityManager(  963): Killing 4843:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d9a8f8 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313293981754351; DSPS: 21002008; Offset: 1450312653051334430
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313313982184793; DSPS: 21657382; Offset: 1450312653051337626
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
D/WifiController(  963): battery changed pluggedType: 2
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313333982669534; DSPS: 22312758; Offset: 1450312653051334085
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313340031, nextTick: 59997, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313340033, nextTick: 59998, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313353983596353; DSPS: 22968148; Offset: 1450312653051345377
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313373984485603; DSPS: 23623537; Offset: 1450312653051349617
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313393984950110; DSPS: 24278912; Offset: 1450312653051356360
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313400039, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313400042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313413985438341; DSPS: 24934288; Offset: 1450312653051356310
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313433997989711; DSPS: 25590060; Offset: 1450312653051334438
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313453998857708; DSPS: 26245448; Offset: 1450312653051347943
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313460041, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313460044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313473999341770; DSPS: 26900824; Offset: 1450312653051343724
,D/Finsky  ( 4285): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  963): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  963): Done.
,D/QcConnectivityService(  963): Setting timer for 720seconds
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Finsky  ( 4285): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/EventLogService( 1851): Aggregate from 1450312773268 (log), 1450311512648 (data)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4285): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4285): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4285): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4285): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4285): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313494000045785; DSPS: 27556207; Offset: 1450312653051345834
,D/Finsky  ( 4285): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4285): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313514001443785; DSPS: 28211613; Offset: 1450312653051340026
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313520032, nextTick: 59987, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313520042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313534001896185; DSPS: 28866988; Offset: 1450312653051334662
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313554002359587; DSPS: 29522363; Offset: 1450312653051340300
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313574002796290; DSPS: 30177737; Offset: 1450312653051349757
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313580028, nextTick: 60000, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313580053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313594003735752; DSPS: 30833128; Offset: 1450312653051343174
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313614004210119; DSPS: 31488504; Offset: 1450312653051329260
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313634004664237; DSPS: 32143878; Offset: 1450312653051356132
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313640031, nextTick: 59998, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313640046, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313654006068393; DSPS: 32799285; Offset: 1450312653051325962
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313674006943888; DSPS: 33454673; Offset: 1450312653051346965
,D/GCM     ( 1554): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313694007419907; DSPS: 34110049; Offset: 1450312653051334702
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313700039, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313700042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313714013557232; DSPS: 34765610; Offset: 1450312653051337994
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313734014445774; DSPS: 35420999; Offset: 1450312653051341526
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313754014906902; DSPS: 36076374; Offset: 1450312653051344891
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313760040, nextTick: 59989, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313760043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313774015378402; DSPS: 36731749; Offset: 1450312653051358627
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313794015820281; DSPS: 37387124; Offset: 1450312653051342742
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313814016698043; DSPS: 38042513; Offset: 1450312653051335495
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313820038, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313820041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313834017182309; DSPS: 38697888; Offset: 1450312653051361997
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313854017629988; DSPS: 39353263; Offset: 1450312653051351912
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313874028007118; DSPS: 40008963; Offset: 1450312653051353066
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313880036, nextTick: 59987, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313880045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313894028973136; DSPS: 40664355; Offset: 1450312653051342521
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313914029421521; DSPS: 41319730; Offset: 1450312653051333143
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313934035258608; DSPS: 41975281; Offset: 1450312653051341372
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313940032, nextTick: 59996, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450313940045, nextTick: 59983, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313954036637353; DSPS: 42630686; Offset: 1450312653051346826
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313974038941131; DSPS: 43286122; Offset: 1450312653051331268
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450313994039384779; DSPS: 43941496; Offset: 1450312653051347670
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314000035, nextTick: 59994, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314000037, nextTick: 59974, mDrawingTime: 8
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314014040314587; DSPS: 44596887; Offset: 1450312653051331433
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314034041186084; DSPS: 45252275; Offset: 1450312653051348438,
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314054041641702; DSPS: 45907650; Offset: 1450312653051346292
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314060030, nextTick: 59998, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314060031, nextTick: 59998, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314074042107672; DSPS: 46563025; Offset: 1450312653051354499
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314094046162009; DSPS: 47218518; Offset: 1450312653051349998
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314114046611832; DSPS: 47873893; Offset: 1450312653051342057
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314120037, nextTick: 59993, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314120043, nextTick: 59983, mDrawingTime: 3
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314134048965943; DSPS: 48529330; Offset: 1450312653051346315
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314154057413909; DSPS: 49184967; Offset: 1450312653051340911
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314174058773279; DSPS: 49840372; Offset: 1450312653051326990
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314180031, nextTick: 59984, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314180046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314194059212197; DSPS: 50495746; Offset: 1450312653051338662
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314214059675113; DSPS: 51151121; Offset: 1450312653051343815
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314234060561360; DSPS: 51806510; Offset: 1450312653051345052
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314240036, nextTick: 59983, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314240045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314254061540494; DSPS: 52461902; Offset: 1450312653051347623
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314274061994699; DSPS: 53117277; Offset: 1450312653051344065
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314294062447252; DSPS: 53772652; Offset: 1450312653051338854
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314300026, nextTick: 60001, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314300056, nextTick: 59972, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314314063915971; DSPS: 54428060; Offset: 1450312653051342729
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314334064336893; DSPS: 55083434; Offset: 1450312653051336405
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314354065200977; DSPS: 55738822; Offset: 1450312653051345997
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314360036, nextTick: 59987, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314360045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314374072510316; DSPS: 56394422; Offset: 1450312653051331117
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314394073420565; DSPS: 57049811; Offset: 1450312653051356357
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314414074268660; DSPS: 57705199; Offset: 1450312653051349959
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314420032, nextTick: 59998, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314420034, nextTick: 59997, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314434074739041; DSPS: 58360575; Offset: 1450312653051332059
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314454075658096; DSPS: 59015965; Offset: 1450312653051335587
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314474076563291; DSPS: 59671354; Offset: 1450312653051355772
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,I/ProcessStatsService(  963): Prepared write state in 42ms
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314480080, nextTick: 59951, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314480082, nextTick: 59951, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  963): Pruning old procstats: /data/system/procstats/state-2015-12-16-12-14-00.bin
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314494078133134; DSPS: 60326766; Offset: 1450312653051338701
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314514078561776; DSPS: 60982140; Offset: 1450312653051340097
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314534079034091; DSPS: 61637515; Offset: 1450312653051354648
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314540035, nextTick: 59980, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450314540048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314554079495155; DSPS: 62292890; Offset: 1450312653051357948
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1450314574079940693; DSPS: 62948265; Offset: 1450312653051345723
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  963): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  963): Done.
,D/QcConnectivityService(  963): Setting timer for 720seconds
,D/LocationManagerService(  963): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1554): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,TIME-OUT KILL (timeout was 1800000ms)
```
