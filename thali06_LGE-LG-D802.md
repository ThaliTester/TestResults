#### Test 549702617cfd775_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/ChimeraCfgMgr( 1940): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1940): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1940): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1940): No vision deps
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/PeopleContactsSync( 1940): CP2 sync disabled
I/dalvikvm( 1940): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1940): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1940): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1940): Using Auth Proxy for data requests.
W/BaseAppContext( 1940): Using Auth Proxy for data requests.
W/GAV2    ( 4595): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  956): Killing 4065:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 1 tasks}
,D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c96b68 u0 com.android.settings/.UsbSettings t2}
W/BaseAppContext( 1940): Using Auth Proxy for data requests.
W/BaseAppContext( 1940): Using Auth Proxy for data requests.
W/BaseAppContext( 1940): Using Auth Proxy for data requests.
D/dalvikvm( 1545): GC_EXPLICIT freed 1027K, 29% free 17823K/24832K, paused 2ms+6ms, total 42ms
W/BaseAppContext( 1940): Using Auth Proxy for data requests.
D/dalvikvm( 1940): GC_CONCURRENT freed 1555K, 22% free 19421K/24832K, paused 3ms+4ms, total 40ms
I/ConfigFetchService( 1940): fetch service done; releasing wakelock
I/ConfigFetchService( 1940): stopping self
D/AndroidRuntime( 4640): 
D/AndroidRuntime( 4640): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4640): CheckJNI is OFF
D/dalvikvm( 4640): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4640): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4640): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4640): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4640): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4640): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1940): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/ChimeraCfgMgr( 1940): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1940): Module APK com.google.android.play.games already loaded
D/Icing   ( 1940): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1940): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4640): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4640): failed to load memtrack module: -2
D/AndroidRuntime( 4640): Calling main entry com.android.commands.am.Am
I/ActivityManager(  956): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4640
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (112 us)
V/ActivityManager(  956): Moving to PAUSING: ActivityRecord{42c96b68 u0 com.android.settings/.UsbSettings t2}
D/UsbSettingsControl( 2593): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2593): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4640): Shutting down VM
I/SlideAside( 3760): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4640): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/ActivityManager(  956): resumeTopActivityLocked: Pausing null
V/ActivityManager(  956): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  956): startService SlideAside
W/ContextImpl(  956): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  956): setFocusedStack: mFocusedStack=ActivityStack{43326cf8 stackId=1, 2 tasks}
D/ActivityManager(  956): allPausedActivitiesComplete: r=ActivityRecord{42c96b68 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  956): Moving to PAUSED: ActivityRecord{42c96b68 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
D/ActivityManager(  956): resumeTopActivityLocked: Restarting ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3760): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
I/ActivityManager(  956): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4654 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
D/SlideAside( 3760): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  956): Moving to RESUMED: ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4654): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4654): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4654): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4654): Binding Chromium to the background looper Looper (main, tid 1) {4288c770}
I/chromium( 4654): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4654): Initializing chromium process, renderers=0
W/chromium( 4654): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4654): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4654): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4654): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4654): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4654): Remote Branch: 
I/Adreno-EGL( 4654): Local Patches: 
I/Adreno-EGL( 4654): Reconstruct Branch: 
I/dalvikvm( 4654): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4654): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4654): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4654): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4654): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4654): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4654): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4654): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4654): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4654): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4654): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4654): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4654): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4654): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4654): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4654): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4654): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4654): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4654): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4654): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4654): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4654): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4654): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4654): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/BubblePopupHelper( 1136): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4654): Enabling debug mode 0
W/AwContents( 4654): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  956): IME STATUS OFF
W/AwContents( 4654): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  956): Displayed com.test.thalitest/.MainActivity: +411ms
I/ActivityManager( 4654): Timeline: Activity_idle id: android.os.BinderProxy@4288e030 time:108552
D/JsMessageQueue( 4654): Set native->JS mode to OnlineEventsBridgeMode
D/WifiStateMachine(  956): handleMessage: E msg.what=131155
D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2025): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2025): nl80211: survey data missing!
D/WifiStateMachine(  956): handleMessage: X
D/dalvikvm( 4654): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42892848
D/dalvikvm( 4654): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42892848
D/jxcore_app_log( 4654): JniHelper::setJavaVM(0x41758838), pthread_self() = 1631356728
D/JX-Cordova( 4654): jxcore cordova android initializing
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1216): Disconnected process message: 10
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
D/WifiController(  956): battery changed pluggedType: 2
I/ActivityManager(  956): Timeline: Activity_windows_visible id: ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3} time:108884
D/ActivityManager(  956): no-history finish of ActivityRecord{42c96b68 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  956): Finishing activity token=Token{4310b768 ActivityRecord{42c96b68 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  956): Moving to FINISHING: ActivityRecord{42c96b68 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  956): Moving to STOPPING: ActivityRecord{42c96b68 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2593): [AUTORUN] onStop()
V/ActivityManager(  956): Moving to STOPPED: ActivityRecord{42c96b68 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4654): GC_CONCURRENT freed 2763K, 12% free 21865K/24832K, paused 3ms+1ms, total 46ms
,D/dalvikvm( 4654): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4654): GC_FOR_ALLOC freed 112K, 12% free 21862K/24832K, paused 34ms, total 34ms
,D/dalvikvm( 4654): GC_FOR_ALLOC freed 125K, 12% free 21882K/24832K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4654): Grow heap (frag case) to 23.634MB for 95956-byte allocation
,D/dalvikvm( 4654): GC_FOR_ALLOC freed 177K, 13% free 21917K/24928K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4654): Grow heap (frag case) to 23.714MB for 143930-byte allocation
,D/dalvikvm( 4654): GC_FOR_ALLOC freed 252K, 13% free 21964K/25072K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4654): Grow heap (frag case) to 23.829MB for 215890-byte allocation
,D/dalvikvm( 4654): GC_FOR_ALLOC freed 366K, 13% free 22038K/25284K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4654): Grow heap (frag case) to 24.003MB for 323830-byte allocation
,D/dalvikvm( 4654): GC_FOR_ALLOC freed 564K, 14% free 22159K/25604K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4654): Grow heap (frag case) to 24.276MB for 485740-byte allocation
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/dalvikvm( 4654): GC_FOR_ALLOC freed 860K, 15% free 22335K/26080K, paused 23ms, total 23ms
,D/dalvikvm( 4654): GC_FOR_ALLOC freed 1275K, 14% free 22590K/26080K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4654): Grow heap (frag case) to 25.277MB for 1092904-byte allocation
,D/dalvikvm( 4654): GC_CONCURRENT freed 1939K, 16% free 23011K/27148K, paused 1ms+5ms, total 47ms
,D/dalvikvm( 4654): WAIT_FOR_CONCURRENT_GC blocked 2ms
,I/dalvikvm-heap( 4654): Grow heap (frag case) to 26.208MB for 1639352-byte allocation
,D/dalvikvm( 4654): GC_CONCURRENT freed 1969K, 18% free 23660K/28752K, paused 1ms+4ms, total 46ms
,D/dalvikvm( 4654): GC_FOR_ALLOC freed 1137K, 19% free 23526K/28752K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4654): Grow heap (frag case) to 27.493MB for 2459024-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,D/dalvikvm( 4654): GC_CONCURRENT freed 324K, 17% free 25861K/31156K, paused 3ms+3ms, total 41ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4654): GC_FOR_ALLOC freed 4271K, 22% free 24535K/31156K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4654): Grow heap (frag case) to 29.651MB for 3688532-byte allocation
,D/dalvikvm( 4654): GC_CONCURRENT freed 452K, 20% free 28077K/34760K, paused 2ms+8ms, total 53ms
,D/dalvikvm( 4654): GC_FOR_ALLOC freed 3165K, 27% free 25480K/34760K, paused 23ms, total 23ms
,W/jxcore-log( 4654): Initializing JXcore engine
,W/jxcore-log( 4654): JXcore engine is ready
,D/dalvikvm( 4654): GC_CONCURRENT freed 360K, 20% free 28111K/34760K, paused 1ms+2ms, total 32ms
,D/dalvikvm( 4654): WAIT_FOR_CONCURRENT_GC blocked 30ms
,W/jxcore-log( 4654): Starting JXcore engine
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,W/jxcore-log( 4654): Platform android
W/jxcore-log( 4654): 
,W/jxcore-log( 4654): Process ARCH arm
W/jxcore-log( 4654): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4654): JXcore Cordova bridge is ready!
I/jxcore-log( 4654): 
,W/jxcore-log( 4654): JXcore engine is started
,I/chromium( 4654): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4654): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4654): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/jxcore-log( 4654): Toggling radios to true
I/jxcore-log( 4654): 
,D/BluetoothManagerService(  956): Message: 20
D/BluetoothManagerService(  956): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43e313b0:true
D/BluetoothAdapter( 4654): enable(): BT is already enabled..!
D/WifiStateMachine(  956): handleMessage: E msg.what=131145
D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiNative-wlan0(  956): doBoolean: DISCONNECT
I/jxcore-log( 4654): Radios toggled
I/jxcore-log( 4654): 
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2025): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2025): wlan0: Cancelling scan request
D/wpa_supplicant( 2025): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2025): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2025): TDLS: Tear down peers
D/wpa_supplicant( 2025): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4654): My device name is: LGE-LG-D802
I/jxcore-log( 4654): 
D/WifiService(  956): New client listening to asynchronous messages
D/WifiService(  956): setWifiEnabled: true pid=4654, uid=10304
E/WifiService(  956): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  956): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  956): disconnect pid=4654, uid=10304
D/WifiService(  956): reconnect pid=4654, uid=10304
,D/wpa_supplicant( 2025): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2025): wlan0: Deauthentication notification
D/wpa_supplicant( 2025): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2025): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2025): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2025): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2025): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2025): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2025): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2025): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2025): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2025): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2025): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7697d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2025):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2025): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2025): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2025): netlink: Operstate: linkmode=-1, operstate=5
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2025): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2025): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2025): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2025): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2025): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2025): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2025): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2025): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2025): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2025): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2025): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2025): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2025): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2025): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2025): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2025): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2025): nl80211: Event message available
D/wpa_supplicant( 2025): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
,D/wpa_supplicant( 2025): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
,D/WifiNative-wlan0(  956):    returned true
D/WifiStateMachine(  956): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  956): handleMessage: new destination call exit/enter
D/WifiStateMachine(  956): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  956): invokeExitMethods: ConnectedState
W/Settings(  956): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  956): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  956): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  956): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  956): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=131146
D/WifiStateMachine(  956): processMsg: DisconnectingState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiNative-wlan0(  956): doBoolean: RECONNECT
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2025): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2025): Fast associate: Old scan results
D/wpa_supplicant( 2025): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2025): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2025): wlan0: nl80211: scan request
D/wpa_supplicant( 2025): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2025): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2025): nl80211: Event message available
D/wpa_supplicant( 2025): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2025): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  956):    returned true
D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=147460
D/WifiStateMachine(  956): processMsg: DisconnectingState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): Network connection lost
D/WifiStateMachine(  956): Stopping DHCP and clearing IP
D/WifiStateMachine(  956): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  956): doBoolean: SET ps 1
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2025): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2025): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2025): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  956):    returned true
D/WifiNative-wlan0(  956): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  956): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  956): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2025): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2025): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  956):    returned true
D/DhcpStateMachine(  956): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  956): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  956): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  956): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
V/WfdStateTracker( 1159): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1136): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  956): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/QCNEA   (  401): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  401): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  401): |CAC| updateNetCfgInfo
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC|                   Netconfig               
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  401): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  401): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  401): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  401): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  401): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  401): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| Received bssid= 
D/QCNEA   (  401): |CAC| net type = 3
V/QCNEA   (  401): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  401): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  401): |CAC| 	ssid           =NG700
V/QCNEA   (  401): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  401): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  401): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  401): |CAC| dispatchNetCfg: updating:0xb81158dc
,D/QCNEA   (  401): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  956): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
D/WifiHS20(  956): hidePasspointNotification off =false
D/QcConnectivityService(  956): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/NetworkManagementService(  956): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  956): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  956): handleMessage: new destination call exit/enter
D/WifiStateMachine(  956): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  956): invokeExitMethods: DisconnectingState
,D/WifiStateMachine(  956): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  956): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  956): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=147462
D/WifiStateMachine(  956): processMsg: DisconnectedState
D/WifiStateMachine(  956): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=147462
D/WifiStateMachine(  956): processMsg: DisconnectedState
D/WifiStateMachine(  956): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  956): processMsg: ConnectModeState
,D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=131213
D/WifiStateMachine(  956): processMsg: DisconnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): processMsg: DriverStartedState
D/WifiStateMachine(  956): processMsg: DriverStartedStateExt
D/WifiStateMachine(  956): processMsg: SupplicantStartedState
D/WifiStateMachine(  956): processMsg: DefaultState
D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=131213
D/WifiStateMachine(  956): processMsg: DisconnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): processMsg: DriverStartedState
D/WifiStateMachine(  956): processMsg: DriverStartedStateExt
D/WifiStateMachine(  956): processMsg: SupplicantStartedState
D/WifiStateMachine(  956): processMsg: DefaultState
,D/WifiStateMachine(  956): handleMessage: X
I/RemoteControlStatusBar( 1136): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/NetworkManagementService(  956): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  956): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
D/QcConnectivityService(  956): Attempting to switch to mobile
D/QcConnectivityService(  956): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  956): handleConnectivityChange: preConnState=1 connState=2
I/ActivityManager(  956): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4704 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/HyLog   ( 4704): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4704): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4704): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,I/PCSuite ( 4704): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  264): RouteController
,D/PCSuite ( 4704): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4704): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,W/NetworkManagementService(  956): route cmd failed: 
W/NetworkManagementService(  956): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  956): '
W/NetworkManagementService(  956): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  956): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  956): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  956): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  956): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  956): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  956): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  956): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  956): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  956): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  956): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  956): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  956): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  956): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4728 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  956): Killing 4161:com.google.android.talk/u0a77 (adj 15): empty #17
,D/NetUtils(  956): android_net_utils_resetConnections in env=0x6183d7d0 clazz=0x6d700001 iface=wlan0 mask=0x3
D/QcConnectivityService(  956): resetConnections(wlan0, 3)
,V/NativeCrypto( 1545): Read error: ssl=0x6487d580: I/O error during system call, Connection timed out
,V/NativeCrypto( 1545): SSL shutdown failed: ssl=0x6487d580: I/O error during system call, Broken pipe
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
,D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,D/LocSvc_java(  956): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  956): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/HyLog   ( 4728): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4728): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4728): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Nat464Xlat(  956): requiresClat: netType=1, hasIPv4Address=false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/LocSvc_java(  956): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  956): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  956): handleInetConditionChange: no active default network - ignore
,D/QRemote ( 4728): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4728): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4728): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4728): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4728): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4728): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4728): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4728): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4728): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  956): Killing 3099:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
,D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  956): StoppedState
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: DisconnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): processMsg: DriverStartedState
D/WifiStateMachine(  956): processMsg: DriverStartedStateExt
D/WifiStateMachine(  956): processMsg: SupplicantStartedState
D/WifiStateMachine(  956): processMsg: DefaultState
,D/WifiStateMachine(  956): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4595): Thread[GAThread,5,main]: No campaign data found.
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.458649 Y: -0.406662 Z: 9.817825 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458649 .y:-0.406662 .z:9.817825
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.447266 Y: -0.408920 Z: 9.815323 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447266 .y:-0.408920 .z:9.815323
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
I/ConfigService( 1545): onDestroy
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  956): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  956): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  956): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4026): onReceive
,D/AppUp4:CustFacade( 4026): Context : android.app.ReceiverRestrictedContext@428ab3e0
D/AppUp4:CustFacade( 4026): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4026): isOpenOperator : true
,D/AppUp4:CustFacade( 4026): isPhone : true
,I/LicenseContentProvider( 2959): start selecting data
,D/SIMObserver( 2959): simInfo1
,I/AppUp4:EulaManager( 4026): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4026): begin check event
,I/AppUp4:CustModeStarterReceiver( 4026): Event For GoodConnectivity
,I/ActivityManager(  956): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4767 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4767): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2025): nl80211: Event message available
D/wpa_supplicant( 2025): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2025): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2025): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2025): nl80211: Received scan results (12 BSSes)
D/wpa_supplicant( 2025): nl80211: Survey data missing
D/wpa_supplicant( 2025): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2025): wlan0: BSS: Add new id 8 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): wlan0: BSS: Add new id 9 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2025): wlan0: BSS: Add new id 10 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): wlan0: BSS: Add new id 11 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free'
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): BSS: last_scan_res_used=12/32 last_scan_full=0
D/wpa_supplicant( 2025): wlan0: New scan results available
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2025): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2025): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2025): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2025): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2025): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2025): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2025): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2025): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2025): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2025): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2025): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2025): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2025): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2025): WPS: AP[4] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2025): WPS: AP[5] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2025): WPS: AP[6] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2025): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2025): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps
D/wpa_supplicant( 2025): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2025): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-47
D/wpa_supplicant( 2025): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2025): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2025): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2025): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2025): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2025): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2025): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2025): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2025): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2025): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2025): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb76995a8  current_ssid=0x0
D/wpa_supplicant( 2025): scard is not null..
D/wpa_supplicant( 2025): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2025): wpa_supplicant_check_mdm,_ac_policy policy: 0
D/wpa_supplicant( 2025): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2025): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2025): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2025): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2025): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2025): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2025): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2025): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2025): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2025): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2025): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2025): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2025): wlan0: Cancelling scan request
D/wpa_supplicant( 2025): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2025): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2025): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2025): RSN: PMKSA cache search - network_ctx=0xb76995a8 try_opportunistic=0
D/wpa_supplicant( 2025): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2025): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2025): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2025): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2025): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2025): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2025): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2025): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2025): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2025): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2025): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2025): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2025): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2025): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2025): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2025): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2025): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2025): nl80211: Unsubscribe mgmt frames handle 0xb7698590 (mode change)
D/wpa_supplicant( 2025): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7698590
D/wpa_supplicant( 2025): nl80211: Register frame type=0xd0 nl_handle=0xb7698590
D/wpa_supplicant( 2025): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2025): nl80211: Register frame type=0xd0 nl_handle=0xb7698590
D/wpa_supplicant( 2025): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2025): nl80211: Register frame type=0xd0 nl_handle=0xb7698590
D/wpa_supplicant( 2025): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2025): nl80211: Register frame type=0xd0 nl_handle=0xb7698590
D/wpa_supplicant( 2025): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2025): nl80211: Register frame type=0xd0 nl_handle=0xb7698590
D/wpa_supplicant( 2025): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2025): nl80211: Register frame type=0xd0 nl_handle=0xb7698590
D/wpa_supplicant( 2025): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2025): nl80211: Register frame type=0xd0 nl_handle=0xb7698590
D/wpa_supplicant( 2025): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2025): nl80211: Register frame type=0xd0 nl_handle=0xb7698590
D/wpa_supplicant( 2025): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2025): nl80211: Register frame type=0xd0 nl_handle=0xb7698590
D/wpa_supplicant( 2025): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2025): nl80211: Register frame type=0xd0 nl_handle=0xb7698590
D/wpa_supplicant( 2025): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2025): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2025):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2025):   * freq=2412
D/wpa_supplicant( 2025):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2025):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2025):   * Auth Type 0
D/wpa_supplicant( 2025):   * WPA Versions 0x2
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 44:e9:dd:10:c0:ab]
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 64:7c:34:38:27:cc]
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 06:7c:34:38:27:cc]
D/WifiMonitor(  956): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  956): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  956): handleMessage: E msg.what=147461
D/WifiStateMachine(  956): processMsg: DisconnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): processMsg: DriverStartedState
D/WifiStateMachine(  956): processMsg: DriverStartedStateExt
D/WifiStateMachine(  956): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  956): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2025): nl80211: Connect request send successfully
D/wpa_supplicant( 2025): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2025): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2025): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2025): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2025): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2025): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2025): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2025): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2025): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2025): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2025): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=147462
D/WifiStateMachine(  956): processMsg: DisconnectedState
D/WifiStateMachine(  956): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2025): nl80211: Event message available
D/wpa_supplicant( 2025): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2025): nl80211: Connect event
D/wpa_supplicant( 2025): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2025): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2025): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2025): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2025): wlan0: Association info event
D/wpa_supplicant( 2025): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2025): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2025): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2025): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2025): wlan0: freq=2412 MHz
D/wpa_supplicant( 2025): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2025): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2025): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2025): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2025): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2025): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2025): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2025): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2025): scard is not null..
D/wpa_supplicant( 2025): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2025): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2025): TDLS: Remove peers on association
D/wpa_supplicant( 2025): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2025): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  956): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/wpa_supplicant( 2025): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
W/WifiMonitor(  956): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2025): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2025): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2025): EAPOL: enable timer tick
D/wpa_supplicant( 2025): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2025): wlan0: Setting authentication timeout: 10 sec 0 usec
D/WifiStateMachine(  956): handleMessage: E msg.what=147462
D/wpa_supplicant( 2025): wlan0: Cancelling scan request
D/wpa_supplicant( 2025): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/WifiStateMachine(  956): processMsg: DisconnectedState
D/wpa_supplicant( 2025): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2025): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2025): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2025): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2025): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiStateMachine(  956): setDetailed state, old =CONNECTING and new state=CONNECTING
D/wpa_supplicant( 2025): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2025): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): handleMessage: X
D/wpa_supplicant( 2025): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2025): nl80211: if_removed already cleared - ignore event
,V/DownloadManager( 4767): DownloadService onCreate
,D/EAS     ( 4575): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4575): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/wpa_supplicant( 2025): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2025): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 a3 a2 df 36 35 da 26 5a 10 e1 dc 39 d4 45 6d ...
D/wpa_supplicant( 2025): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2025): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2025): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2025): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2025): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2025):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2025):   key_nonce - hexdump(len=32): a3 a2 df 36 35 da 26 5a 10 e1 dc 39 d4 45 6d 5e f6 0a 13 e1 ac 1e 80 5a 3b fa be 26 c1 be 87 95
D/wpa_supplicant( 2025):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2025):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2025):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2025):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2025): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 a3 a2 df 36 35 da 26 5a 10 e1 dc 39 d4 45 6d ...
D/wpa_supplicant( 2025): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2025): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2025): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2025): WPA: Renewed SNonce - hexdump(len=32): 4e 76 ae 98 83 ef 6c e4 b0 a8 3a d4 9f 9b 5e 10 bf 0b 5d 48 cb 55 25 ee 87 ee 40 2c 4c b9 83 4d
D/wpa_supplicant( 2025): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2025): WPA: Nonce1 - hexdump(len=32): 4e 76 ae 98 83 ef 6c e4 b0 a8 3a d4 9f 9b 5e 10 bf 0b 5d 48 cb 55 25 ee 87 ee 40 2c 4c b9 83 4d
D/wpa_supplicant( 2025): WPA: Nonce2 - hexdump(len=32): a3 a2 df 36 35 da 26 5a 10 e1 dc 39 d4 45 6d 5e f6 0a 13 e1 ac 1e 80 5a 3b fa be 26 c1 be 87 95
D/wpa_supplicant( 2025): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2025): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2025): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2025): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2025): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2025): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2025): WPA: Derived Key MIC - hexdump(len=16): b9 f5 6f db d0 fd 0c dc c2 a2 f5 83 0d c0 d5 a3
D/wpa_supplicant( 2025): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 4e 76 ae 98 83 ef 6c e4 b0 a8 3a d4 9f 9b 5e ...
I/DownloadManager( 4767): in removeSpuriousFiles
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  956): handleMessage: E msg.what=147462
D/WifiStateMachine(  956): processMsg: DisconnectedState
D/WifiStateMachine(  956): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  956): processMsg: ConnectModeState
,D/WifiStateMachine(  956): handleMessage: X
,D/eas_req ( 4575): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/wpa_supplicant( 2025): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2025): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 a3 a2 df 36 35 da 26 5a 10 e1 dc 39 d4 45 6d ...
D/wpa_supplicant( 2025): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2025): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2025): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2025): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2025):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2025):   key_nonce - hexdump(len=32): a3 a2 df 36 35 da 26 5a 10 e1 dc 39 d4 45 6d 5e f6 0a 13 e1 ac 1e 80 5a 3b fa be 26 c1 be 87 95
D/wpa_supplicant( 2025):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2025):   key_rsc - hexdump(len=8): d1 18 00 00 00 00 00 00
D/wpa_supplicant( 2025):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2025):   key_mic - hexdump(len=16): 1d 51 79 1b d3 49 49 eb 3d 76 19 00 ae 62 b2 f3
D/wpa_supplicant( 2025): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 a3 a2 df 36 35 da 26 5a 10 e1 dc 39 d4 45 6d ...
D/wpa_supplicant( 2025): RSN: encrypted key data - hexdump(len=56): 72 e4 e5 e5 29 9b 82 59 ac aa 61 8f 16 7a 18 73 5c cc 0f 12 7e 55 8e e4 6c 79 37 bc 69 1c 97 94 ...
D/wpa_supplicant( 2025): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2025): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2025): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2025): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 6d 3b ...
D/wpa_supplicant( 2025): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2025): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2025): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2025): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2025): WPA: Derived Key MIC - hexdump(len=16): 17 29 ab 0c de 2e af 01 eb d5 ec 9c bc 31 0c b6
D/wpa_supplicant( 2025): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2025): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2025): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7698c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2025):    addr=c0:ff:d4:d3:aa:48
,V/DownloadManager( 4767): DownloadService onStartCommand
D/wpa_supplicant( 2025): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2025): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2025): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2025): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2025): WPA: RSC - hexdump(len=6): d1 18 00 00 00 00
D/wpa_supplicant( 2025): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f5a03a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2025):    broadcast key
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  956): handleMessage: E msg.what=147462
D/WifiStateMachine(  956): processMsg: DisconnectedState
D/WifiStateMachine(  956): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  956): processMsg: ConnectModeState
I/wpa_supplicant( 2025): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2025): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2025): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2025): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2025): netlink: Operstate: linkmode=-1, operstate=6
V/DownloadManager( 4767): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/wpa_supplicant( 2025): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2025): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2025): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2025): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2025): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2025): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2025): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2025): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2025): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2025): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2025): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2025): EAPOL authentication completed successfully
D/wpa_supplicant( 2025): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,D/wpa_supplicant( 2025): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiStateMachine(  956): handleMessage: X
,D/wpa_supplicant( 2025): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  956): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  956): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  956): handleMessage: E msg.what=147459
,D/WifiStateMachine(  956): processMsg: DisconnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): Network connection established
,V/DownloadManager( 4767): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/WifiNative-wlan0(  956): doString: STATUS
I/LgeMiscReceiver( 4313): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4313): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4313): networkInfo.isConnected() = false
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2025): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2025): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428d3c88 on behalf of 4767
,I/DownloadManager( 4767): in trimDatabase
,V/DownloadManager( 4767): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428d6de0 on behalf of 4767
,V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428d5570 on behalf of 4767
,D/WifiNative-wlan0(  956):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  956): ssid=NG700
D/WifiNative-wlan0(  956): id=0
D/WifiNative-wlan0(  956): mode=station
D/WifiNative-wlan0(  956): pairwise_cipher=CCMP
D/WifiNative-wlan0(  956): group_cipher=CCMP
D/WifiNative-wlan0(  956): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  956): wpa_state=COMPLETED
D/WifiNative-wlan0(  956): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  956): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  956): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  956): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  956): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  956): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  956): handleMessage: new destination call exit/enter
D/WifiStateMachine(  956): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  956): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  956): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1136): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,W/linker  ( 4575): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/ActivityManager(  956): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4800 uid=10052 gids={50052, 3003}
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  956): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/RemoteControlStatusBar( 1136): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  956): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  956): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  956): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  956): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  956): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  956): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  956): WaitBeforeStartState
D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=147462
D/WifiStateMachine(  956): processMsg: ObtainingIpState
D/WifiStateMachine(  956): ObtainingIpState{ when=-23ms what=147462 obj=android.net.wifi.StateChangeResult@4501c1f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=147462
D/WifiStateMachine(  956): processMsg: ObtainingIpState
D/WifiStateMachine(  956): ObtainingIpState{ when=-19ms what=147462 obj=android.net.wifi.StateChangeResult@4501d5c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=147459
D/WifiStateMachine(  956): processMsg: ObtainingIpState
D/WifiStateMachine(  956): ObtainingIpState{ when=-20ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=131155
D/WifiStateMachine(  956): processMsg: ObtainingIpState
D/WifiStateMachine(  956): ObtainingIpState{ when=-1ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2025): wlan0: Control interface command 'SIGNAL_POLL'
V/DownloadManager( 4767): DownloadService onDestroy
D/wpa_supplicant( 2025): nl80211: survey data missing!
D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=196612
D/WifiStateMachine(  956): processMsg: ObtainingIpState
D/WifiStateMachine(  956): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiNative-wlan0(  956): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2025): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/HtmlEditor( 4575): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4575): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4575): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4575): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so),
D/HtmlEditor( 4575): register_HtmlEditor, Success
D/HtmlEditor( 4575): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4575): register_HtmlEditorTimer, Success
D/HtmlEditor( 4575): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4575): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4575): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4575): register_HtmlEditorFont, Success
D/HtmlEditor( 4575): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4575): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4575): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4575): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4575): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4575): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4575): JNI_OnLoad Success
D/HyLog   ( 4800): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4800): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4800): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/HubEmail( 4575): JNI_OnLoad()
I/HubEmail( 4575): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4575): registerNatives()
I/HubEmail( 4575): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4575): registerNativeMethods()
I/HubEmail( 4575): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4575): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  956): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  956): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4800): [loadRssi] File not exist 
V/LGRssiData( 4800): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4800): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 4800): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4800): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4800): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4800): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4800): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4800): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4800): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 4800): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4800): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4800): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4800): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  956): Killing 3944:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
I/ActivityManager(  956): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4815 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  956): Killing 4359:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
,D/HyLog   ( 4815): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4815): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4815): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,D/wpa_supplicant( 2025): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  956):    returned true
D/WifiStateMachine(  956): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  956): doBoolean: SET ps 0
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2025): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2025): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2025): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  956):    returned true
,D/WifiNative-wlan0(  956): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2025): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2025): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  956):    returned null
E/WifiStateMachine(  956): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  956): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2025): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2025): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  956):    returned null
E/WifiStateMachine(  956): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  956): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  956): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
I/ActivityManager(  956): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4828 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  956): Killing 4501:com.android.defcontainer/u0a4 (adj 15): empty #17
D/WifiP2pService(  956): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4322ddd8 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  956): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  956): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
,D/CommandListener(  264): Trying to bring up wlan0
,D/WifiStateMachine(  956): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,V/LgDhcpStateMachineHelper(  956): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=131212
,D/WifiStateMachine(  956): processMsg: ObtainingIpState
D/WifiStateMachine(  956): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): processMsg: DriverStartedState
D/WifiStateMachine(  956): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  956): processMsg: SupplicantStartedState
D/WifiStateMachine(  956): processMsg: DefaultState
D/WifiStateMachine(  956): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=196613
,D/WifiStateMachine(  956): processMsg: ObtainingIpState
D/WifiP2pService(  956): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4322ddd8 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
,D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
D/WifiStateMachine(  956): ObtainingIpState{ when=-5ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiStateMachine(  956): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  956): doBoolean: SET ps 1
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2025): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2025): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2025): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  956):    returned true
,D/WifiNative-wlan0(  956): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2025): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2025): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/HyLog   ( 4828): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4828): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4828): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiP2pService(  956): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  956): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  956):    returned true
D/WifiStateMachine(  956): DHCP successful
D/WifiStateMachine(  956): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  956): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  956): handleMessage: new destination call exit/enter
D/WifiStateMachine(  956): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  956): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  956): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  956): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  956): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  956): VerifyingLinkState enter
D/WifiStateMachine(  956): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  956): handleMessage: X
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  956): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1136): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  956): handleMessage: E msg.what=135190
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/WifiStateMachine(  956): processMsg: VerifyingLinkState
D/WifiStateMachine(  956): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  956): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  956): handleMessage: new destination call exit/enter
D/WifiStateMachine(  956): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  956): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  956): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  956): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  956): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  956): CaptivePortalCheckState enter
D/WifiStateMachine(  956): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,E/Parcel  (  401): Reading a NULL string not supported here.
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  956): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/BubblePopupHelper( 1136): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1136): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/WifiStateTracker(  956): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  956): 
W/WifiStateTracker(  956):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  956):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  956): handleMessage: X
D/LocSvc_java(  956): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/KeyguardUpdateMonitor( 1136): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1136): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/Nat464Xlat(  956): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  956): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  956): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  956): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  956): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.,
D/WifiOffDelayIfNotUsed(  956): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  956): handleMessage: E msg.what=131092
D/WifiStateMachine(  956): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  956): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  956): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  956): transitionTo: destState=ConnectedState
D/WifiStateMachine(  956): handleMessage: new destination call exit/enter
D/WifiStateMachine(  956): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  956): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  956): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  956): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
,D/WifiStateMachine(  956): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  956): handleMessage: X
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  956): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/QcConnectivityService(  956): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  956): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  956): handleInetConditionChange: no active default network - ignore
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1136): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  401): Reading a NULL string not supported here.
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  956): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1159): handleWifiStateChangedEvent: 1
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,I/ActivityManager(  956): Killing 4535:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/RemoteControlStatusBar( 1136): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  956): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4842 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
E/ActivityThread(  956): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  956): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  956): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
D/HyLog   ( 4842): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4842): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4842): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
V/        (  264): RouteController
,D/LGDMSGCM( 4842): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4842): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,V/        (  264): RouteController
I/ActivityManager(  956): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4865 uid=10101 gids={50101, 1028, 1015, 3003}
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  956): Killing 4562:com.lge.bnr/1000 (adj 15): empty #17
,V/        (  264): RouteController
D/QCNEA   (  401): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  401): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  401): |CAC| updateNetCfgInfo
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC|                   Netconfig               
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  401): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  401): |CAC| 	NetConfig:         fl =21
,V/QCNEA   (  401): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  401): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  401): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  401): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  401): |CAC| net type = 1
V/QCNEA   (  401): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  401): |CAC| Received ssid= NG700
V/QCNEA   (  401): |CAC| 	ssid           =NG700
V/QCNEA   (  401): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  401): |CAC| 	DNS v4        =0.0.0.0
D/LocSvc_java(  956): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  401): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  401): |CAC| dispatchNetCfg: updating:0xb81158dc
D/QCNEA   (  401): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/GpsLocationProvider(  956): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,D/Nat464Xlat(  956): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/HyLog   ( 4865): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4865): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4865): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 4865): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4865): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4865): intf.getDisplayName() = lo
I/Wireless_Storage( 4865): intf.getDisplayName() = sit0
I/Wireless_Storage( 4865): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4865): intf.getDisplayName() = teql0
I/Wireless_Storage( 4865): intf.getDisplayName() = wlan0
D/NFS     ( 4865): interface name:wlan0 name:wlan0
,D/NFS     ( 4865): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4865): interface name:wlan0 name:wlan0
D/NFS     ( 4865): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4865): CONNECT : WIFI_CONNECT
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,D/DhcpStateMachine(  956): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  956): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  956): GC_EXPLICIT freed 23435K, 49% free 29775K/57900K, paused 6ms+8ms, total 136ms
,I/ActivityManager(  956): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4890 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  956): Killing 4208:com.android.contacts/u0a21 (adj 15): empty #17
D/LocSvc_java(  956): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  956): ignore wifi update if we are not in OPENING or CLOSING
D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  956): battery changed pluggedType: 2
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
,I/CheckinService( 1940): Checking schedule, now: 1452520954828 next: 1452520901209
,I/CheckinService( 1940): active receiver: enabled
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,D/HyLog   ( 4890): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4890): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4890): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1940): Preparing to send checkin request
,I/EventLogService( 1940): Accumulating logs since 1452520867713
,I/CheckinRequestBuilder( 1940): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1940): Failed to find provider info for com.google.android.wearable.settings
,W/GAV2    ( 4890): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromium( 4890): Binding Chromium to the main looper Looper (main, tid 1) {42896300}
,I/chromium( 4890): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4890): Initializing chromium process, renderers=0
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,W/chromium( 4890): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4890): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4890): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4890): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4890): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4890): Remote Branch: 
I/Adreno-EGL( 4890): Local Patches: 
I/Adreno-EGL( 4890): Reconstruct Branch: 
,D/NotificationService(  956): updateLightListLocked :r=NotificationRecord(0x43349120: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  956): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1940): awaiting user notification for token
,I/NSApplication( 4890): Starting up...
I/ActivityManager(  956): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4924 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ActivityManager(  956): Killing 4224:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/HyLog   ( 4924): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4924): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4924): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4728): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4728): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,W/dalvikvm( 4924): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4924): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4924): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4924): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4924): VFY: replacing opcode 0x62 at 0x005e
,D/QRemote ( 4728): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/MultiDex( 4924): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4924): install
I/QRemote ( 4728): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/MultiDex( 4924): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/QRemote ( 4728): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4728): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/MultiDex( 4924): loading existing secondary dex files
,I/PCSuite ( 4704): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,I/MultiDex( 4924): load found 3 secondary dex files
,D/PCSuite ( 4704): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4728): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/MultiDex( 4924): install done
,D/QRemote ( 4728): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4728): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4728): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/dalvikvm( 4924): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4924): VFY: unable to resolve instance field 61
,D/dalvikvm( 4924): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4924): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4924): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4924): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4924): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4924): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4924): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4924): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4924): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4924): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42887458
D/dalvikvm( 4924): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42887458
,D/dalvikvm( 4924): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42887458, skipping init
,D/dalvikvm( 4924): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42887458
D/dalvikvm( 4924): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42887458
,V/JNIHelp ( 4924): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4924): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42887458
,D/dalvikvm( 4924): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42887458
D/dalvikvm( 4924): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42887458
,D/dalvikvm( 4924): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42887458
,I/ProviderInstaller( 4924): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1545): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1545): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1545): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1940): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1897): callingUid 10006, callindPid: 1897
,E/MDM     ( 1422): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1940): Restart initialization of location
,I/dalvikvm( 4924): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4924): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4924): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4924): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4924): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4924): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d7c000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d7c000
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
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=722027083
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2025): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2025): EAPOL: disable timer tick
,D/dalvikvm( 4924): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a5fc90
D/dalvikvm( 4924): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a5fc90
,D/dalvikvm( 4924): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a5fc90, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,W/Settings( 4924): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4924): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  956): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/dalvikvm( 4943): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4924): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4924): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 84ms
,I/Adreno-EGL( 4924): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4924): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4924): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4924): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4924): Remote Branch: 
I/Adreno-EGL( 4924): Local Patches: 
I/Adreno-EGL( 4924): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,D/WifiController(  956): battery changed pluggedType: 2
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
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
D/WVCdm   (  271): PrepareKeyRequest: nonce=267868671
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  956): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  956): handleMessage: E msg.what=131212
D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): processMsg: DriverStartedState
D/WifiStateMachine(  956): processMsg: DriverStartedStateExt
D/WifiStateMachine(  956): processMsg: SupplicantStartedState
,D/WifiStateMachine(  956): processMsg: DefaultState
,D/WifiStateMachine(  956): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  956): send additional Connectivity Action
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  956): handleConnectivityChange:1 is conntected
D/WifiStateMachine(  956): handleMessage: X
D/LocSvc_java(  956): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  956): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  956): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  956): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  956):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  956): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  956): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  956): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
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
,I/CheckinRequestBuilder( 1940): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/DhcpStateMachine(  956): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  956): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  956): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  956): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  956): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine(  956): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  956): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  956): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  956): RunningState
,I/CheckinTask( 1940): Sending checkin request (11586 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
D/WifiController(  956): battery changed pluggedType: 2
,D/WifiController(  956): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1216): Disconnected process message: 10
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/CheckinRequestBuilder( 1940): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1940): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  956): updateLightListLocked :r=NotificationRecord(0x44fc2d98: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1940): awaiting user notification for token
D/NotificationService(  956): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1940): Classify the device as Phone.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1940): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1940): Checking schedule, now: 1452520957056 next: 1453098353053
,I/CheckinService( 1940): active receiver: disabled
,D/GCM     ( 1545): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1545): Connected
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1545): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2025): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2025): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  956): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  956): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4026): onReceive
,D/AppUp4:CustFacade( 4026): Context : android.app.ReceiverRestrictedContext@428ab3e0
D/AppUp4:CustFacade( 4026): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4026): isOpenOperator : true
,D/AppUp4:CustFacade( 4026): isPhone : true
,I/LicenseContentProvider( 2959): start selecting data
,D/SIMObserver( 2959): simInfo1
,I/AppUp4:EulaManager( 4026): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4026): begin check event
I/AppUp4:CustModeStarterReceiver( 4026): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4026): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4026): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4026): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4026): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4026): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4575): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4767): DownloadService onCreate
,D/EAS     ( 4575): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4575): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4313): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4313): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4313): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4800): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4800): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4842): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4842): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4865): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4865): CONNECT : WIFI_CONNECT
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/Tethering(  956): MasterInitialState.processMessage what=3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/CaptivePortalTracker(  956): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,W/Settings( 4575): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,I/DownloadManager( 4767): in removeSpuriousFiles
V/DownloadManager( 4767): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428dd098 on behalf of 4767
,I/DownloadManager( 4767): in trimDatabase
,V/DownloadManager( 4767): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428dea90 on behalf of 4767
,V/DownloadManager( 4767): DownloadService onStartCommand
,V/DownloadManager( 4767): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428e0c40 on behalf of 4767
,V/DownloadManager( 4767): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4026): onReceive
D/AppUp4:CustFacade( 4026): Context : android.app.ReceiverRestrictedContext@428ab3e0
D/AppUp4:CustFacade( 4026): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4026): isOpenOperator : true
,D/AppUp4:CustFacade( 4026): isPhone : true
,I/LicenseContentProvider( 2959): start selecting data
,D/SIMObserver( 2959): simInfo1
,I/AppUp4:EulaManager( 4026): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4026): begin check event
,I/AppUp4:CustModeStarterReceiver( 4026): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4767): DownloadService onCreate
,I/DownloadManager( 4767): in removeSpuriousFiles
,V/DownloadManager( 4767): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4575): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4575): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428e4f30 on behalf of 4767
,I/DownloadManager( 4767): in trimDatabase
,V/DownloadManager( 4767): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428e6470 on behalf of 4767
,V/DownloadManager( 4767): DownloadService onStartCommand
,V/DownloadManager( 4767): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 4313): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4313): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4313): networkInfo.isConnected() = true
D/PhoneState( 4313): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 4800): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/Settings( 4575): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4800): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428e8970 on behalf of 4767
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4842): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4767): DownloadService onDestroy
,W/ContextImpl( 4842): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4865): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4865): CONNECT : WIFI_CONNECT
E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  956): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  956): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,I/jxcore-log( 4654): Test app app.js loaded
I/jxcore-log( 4654): 
,I/Choreographer( 4654): Skipped 420 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4654): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/WifiController(  956): battery changed pluggedType: 2
D/HeadsetStateMachine( 1216): Disconnected process message: 10
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/WifiController(  956): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,D/WifiController(  956): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1216): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  956): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  956): DelayedCaptiveCheckState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4026): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4026): onReceive
,D/AppUp4:CustFacade( 4026): Context : android.app.ReceiverRestrictedContext@428ab3e0
D/AppUp4:CustFacade( 4026): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4026): isOpenOperator : true
,D/AppUp4:CustFacade( 4026): isPhone : true
,I/LicenseContentProvider( 2959): start selecting data
,D/SIMObserver( 2959): simInfo1
,I/AppUp4:EulaManager( 4026): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4026): begin check event
,I/AppUp4:CustModeStarterReceiver( 4026): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4575): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4767): DownloadService onCreate
,D/EAS     ( 4575): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4313): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4313): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4313): networkInfo.isConnected() = true
,D/PhoneState( 4313): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4800): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4800): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4842): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4842): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4865): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4865): CONNECT : WIFI_CONNECT
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 4767): in removeSpuriousFiles
,V/DownloadManager( 4767): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428ecbb8 on behalf of 4767
I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/Settings( 4575): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DownloadManager( 4767): in trimDatabase
V/DownloadManager( 4767): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4767): DownloadService onStartCommand
V/DownloadManager( 4767): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm(  956): GC_EXPLICIT freed 2177K, 49% free 29699K/57900K, paused 3ms+5ms, total 85ms
,V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428eea28 on behalf of 4767
,V/DownloadManager( 4767): created cursor android.database.sqlite.SQLiteCursor@428f02b8 on behalf of 4767
,E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 4767): DownloadService onDestroy
,I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  956): battery changed pluggedType: 2
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  956): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  956): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  956): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  956): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/WifiController(  956): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,I/GAV2    ( 4890): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  956): battery changed pluggedType: 2
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2025): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2025): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/WifiController(  956): battery changed pluggedType: 2
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  956): battery changed pluggedType: 2
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,I/ActivityManager(  956): Killing 4595:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
,D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,D/WifiController(  956): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500,
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  956): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  956): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  956): battery changed pluggedType: 2
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4252): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4252): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  956): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  956): battery changed pluggedType: 2
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
D/WifiController(  956): battery changed pluggedType: 2
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  956): battery changed pluggedType: 2
D/HeadsetStateMachine( 1216): Disconnected process message: 10
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2025): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2025): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/InputReader(  956): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "sms"
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "smsto"
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  956): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5115 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "mms"
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3760): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
D/administrator(  956): Handling package changes for user 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SlideAside( 3760): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "mmsto"
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5115): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5115): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5115): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GlobalAccess( 1136): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1136): changeTargets() succeeded. size: 20
,I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "sms"
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "smsto"
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "mms"
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "mmsto"
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
D/WifiController(  956): battery changed pluggedType: 2
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Babel   ( 5115): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5115): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5115): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5115): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5115): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5115): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5115): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5115): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5115): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5115): MmsConfig.loadFromResources
,E/Babel   ( 5115): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5115): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1422): DISABLE
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 5115): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  956): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  956): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5115): [loadRssi] File not exist 
V/LGRssiData( 5115): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5115): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5115): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5115): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5115): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4026): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4026): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4026): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4026): onReceive
,D/AppUp4:CustFacade( 4026): Context : android.app.ReceiverRestrictedContext@428ab3e0
D/AppUp4:CustFacade( 4026): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4026): isOpenOperator : true
,D/AppUp4:CustFacade( 4026): isPhone : true
,I/LicenseContentProvider( 2959): start selecting data
,D/SIMObserver( 2959): simInfo1
,I/AppUp4:EulaManager( 4026): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4026): begin check event
D/AppUp4:Utils( 4026): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4026): Event For Nothing, skip.
,I/ActivityManager(  956): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5167 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/LocationProviderProxy(  956): applying state to connected service
,D/LocationProviderProxy(  956): applying state to connected service
D/HyLog   ( 5167): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5167): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5167): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5167): BUILD Country: EU
,I/SystemConfig( 5167): BUILD Operator: OPEN
I/SystemConfig( 5167): systemFeature RCS result false
,D/SystemConfig( 5167): refreshRcsSupport() :false
I/ActivityManager(  956): Killing 4704:com.lge.sync/1000 (adj 15): empty #17
I/ActivityManager(  956): Killing 4728:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  956): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5185 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
,D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
,D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5185): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5185): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5185): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  956): Killing 4767:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2665): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 2 tasks}
,D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.453552 Y: -0.418137 Z: 9.805801 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453552 .y:-0.418137 .z:9.805801
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,D/PackageBroadcastService( 1940): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1940): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  956): Delaying start of: ServiceRecord{42c0a2d8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1940): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1940): GC_CONCURRENT freed 1910K, 22% free 19544K/24832K, paused 3ms+3ms, total 31ms
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.450256 Y: -0.388306 Z: 9.802261 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450256 .y:-0.388306 .z:9.802261
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2665): UpdateCorporaTask done [took 195 ms] updated apps [took 195 ms] 
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,D/WifiController(  956): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2025): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2025): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/CaptivePortalTracker(  956): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  956): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  956): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  956): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  956): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  956): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  956): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  956): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2025): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2025): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV4    ( 5115): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2025): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2025): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2025): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2025): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,I/PowerManagerService(  956): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  956): [updateScreenState] screen on = false
D/KnockOnPowerController(  956): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  956): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,D/KnockOnPowerController(  956): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  956): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  956): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  956): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  956): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  956): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  956): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8877 usec
,D/qcom_sensors_hal(  956): hal_acquire_resources
,I/qcom_sensors_hal(  956): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  956): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  956): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  956): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  956): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  956): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  956): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.460510 Y: -0.420044 Z: 9.829468 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460510 .y:-0.420044 .z:9.829468
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.445160 Y: -0.402496 Z: 9.829330 
,V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.445160 Y: -0.403610 Z: 9.818283 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.445160 .y:-0.402496 .z:9.829330
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,I/Sensors (  352): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  956): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  956): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  956): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
D/KnockOnPowerController(  956): proximity onSensorChanged : proximity = 1
,D/KnockOnPowerController(  956): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  956): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.455536 Y: -0.400574 Z: 9.813370 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455536 .y:-0.400574 .z:9.813370
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.455231 Y: -0.400085 Z: 9.817490 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455231 .y:-0.400085 .z:9.817490
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.433182 Y: -0.393204 Z: 9.824753 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.433182 .y:-0.393204 .z:9.824753
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.438812 Y: -0.409164 Z: 9.812332 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.438812 .y:-0.409164 .z:9.812332
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  956): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44fb9088)
,D/KeyguardViewMediator( 1136): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1136): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1136): OMADM Lock is OFF
,D/KeyguardViewMediator( 1136): handleNotifyScreenOn
,D/KeyguardViewManager( 1136): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  956): **** SHOWN CALLED ****
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb792b450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
I/WindowManager(  956): No lock screen! windowToken=null
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.447052 Y: -0.410263 Z: 9.803665 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447052 .y:-0.410263 .z:9.803665
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,E/SlideAside( 3760): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WifiStateMachine(  956): handleScreenStateChanged: true
,D/WifiStateMachine(  956): handleMessage: E msg.what=131154
D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2025): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2025): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/WifiStateMachine(  956): handleMessage: E msg.what=131127
D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiStateMachine(  956): processMsg: ConnectModeState
,D/WifiStateMachine(  956): handleMessage: X
,D/WifiStateMachine(  956): handleMessage: E msg.what=131158
D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): processMsg: DriverStartedState
D/WifiStateMachine(  956): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  956): handleMessage: X
,D/WifiServiceExtension(  956): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  956): handleMessage: E msg.what=132097
D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): processMsg: DriverStartedState
,D/WifiStateMachine(  956): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  956): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2025): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2025): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  956): handleMessage: X
,D/WifiOffDelayIfNotUsed(  956): stopMonitoring
,E/AudioSystem(  956): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 956
V/SRS_Proc(  271): ParamSet string: screen_state=on
,D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1159): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433890f8 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1159): enqueuing start. mLedList.size()=2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1159): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WeatherAncestor( 1846): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:2:58
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SlideAside( 3760): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/UpdateThreadPoolManager( 1846): 2 : This is isUpdating : false
D/WeatherAncestor( 1846): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:2:58
D/WeatherService( 1846): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/LockPatternUtilsEx( 1136): OMADM Lock is OFF
D/WeatherService( 1846): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1846): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1159): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1159): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1159): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 231, B = 231
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1159): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 225, B = 225
E/BatteryObserver( 1159): usb Uevent not necessary.
,D/qdlights( 1159): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 219, B = 219
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1159): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  956): Excessive delay in blankDisplay() while turning screen off: 411ms
D/qdlights( 1159): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 207, B = 207
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1159): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1159): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 189, B = 189
D/GlobalAccess( 1136): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1136): changeTargets() succeeded. size: 20
,D/Clock   ( 1136): Clock updated, drawingStartTime : 1452520978519, nextTick: 1511, mDrawingTime: 2
V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.439850 Y: -0.401108 Z: 9.835968 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.439850 .y:-0.401108 .z:9.835968
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
D/qdlights( 1159): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 183, B = 183
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 177, B = 177
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiStateMachine(  956): handleMessage: X
,D/qdlights( 1159): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1159): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 165, B = 165
,D/Clock   ( 1136): Clock updated, drawingStartTime : 1452520978566, nextTick: 1467, mDrawingTime: 0
D/qdlights( 1159): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 159, B = 159
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,D/qdlights( 1159): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 153, B = 153
D/WeatherService( 1846): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:2:58
,D/WeatherService( 1846): 2 : ACTION screen on
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1846): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:2:58
,D/qdlights( 1159): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 147, B = 147
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.432068 Y: -0.374695 Z: 9.824188 
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.464249 Y: -0.417969 Z: 9.817520 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.432068 .y:-0.374695 .z:9.824188
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1159): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 141, B = 141
,V/TelephonyAutoProfiling(  956): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,D/qdlights( 1159): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 135, B = 135
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,D/qdlights( 1159): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 129, B = 129
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  956): ACTION_SCREEN_ON
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/qdlights( 1159): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 123, B = 123
I/qcom_sensors_hal(  956): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  956): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  956): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  956): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1136): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1136): notifyScreenOffLocked
V/ActivityManager(  956): Moving to PAUSING: ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,D/qdlights( 1159): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 117, B = 117
D/qcom_sensors_hal(  956): hal_acquire_resources
,D/qcom_sensors_hal(  956): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  956): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  956): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  956): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  956): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1159): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1159): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 105, B = 105
,V/ActivityManager(  956): Moving to PAUSED: ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,D/qdlights( 1159): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 99, B = 99
V/ActivityManager(  956): Moving to STOPPING: ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,D/KeyguardViewMediator( 1136): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/UsbSettings( 2593): [AUTORUN] onDestroy() : getDefaultFunction =boot
I/LGImmersionVibrator(  956): Vibrator off
,V/UsbSettings( 2593): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2593): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2593): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,D/WifiStateMachine(  956): handleScreenStateChanged: false
D/WifiStateMachine(  956): handleMessage: E msg.what=131154
D/WifiStateMachine(  956): processMsg: ConnectedState
D/qdlights( 1159): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 93, B = 93
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiStateMachine(  956): handleMessage: X
V/ActivityManager(  956): Moving to DESTROYING: ActivityRecord{42c96b68 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  956): Moving to STOPPED: ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiStateMachine(  956): handleMessage: E msg.what=131158
D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): processMsg: DriverStartedState
D/WifiStateMachine(  956): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  956): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2025): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2025): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/KeyguardViewMediator( 1136): handleNotifyScreenOff
,D/KeyguardViewManager( 1136): onScreenTurnedOff()
D/qdlights( 1159): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 87, B = 87
D/WifiController(  956): CMD_SCREEN_OFF 
D/WifiController(  956): shouldWifiStayAwake TRUE
E/AudioSystem(  956): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 956
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
V/ActivityManager(  956): Moving to DESTROYED: ActivityRecord{42c96b68 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{43326cf8 stackId=1, 1 tasks}
D/ActivityManager(  956): resumeTopActivityLocked: Going to sleep and all paused
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1159): clear
E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/wpa_supplicant( 2025): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/qdlights( 1159): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 81, B = 81
D/WifiNative-wlan0(  956):    returned true
D/WifiStateMachine(  956): handleMessage: X
D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=2
,D/qdlights( 1159): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 75, B = 75
,I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1846): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:2:58
,D/WeatherService( 1846): 2 : ACTION screen off
D/qdlights( 1159): set_light_notifications: 2,ff004545,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 69, B = 69
,D/WeatherService( 1846): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:2:58
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  956): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/BubblePopupHelper( 1136): isShowingBubblePopup : false
,D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/qdlights( 1159): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 63, B = 63
,D/NfcService( 1471): NFC-C OFF
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
D/qdlights( 1159): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 57, B = 57
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1136): OMADM Lock is OFF
D/qdlights( 1159): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 51, B = 51
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  956): ACTION_SCREEN_OFF
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/TangibleManager( 1459): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1159): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 45, B = 45
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
,D/qdlights( 1159): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 39, B = 39
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1159): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1159): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 27, B = 27
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1159): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1159): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1159): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  352): sns_pwr.c(320):releasing wakelock
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1136): handleTimeUpdate
,D/KeyguardModel( 1136): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1136): Clock updated, drawingStartTime : 1452520980040, nextTick: 59982, mDrawingTime: 4
,D/Clock   ( 1136): Clock updated, drawingStartTime : 1452520980058, nextTick: 59974, mDrawingTime: 0
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiStateMachine(  956): handleMessage: X
,D/KeyguardViewMediator( 1136): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1136): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1136): OMADM Lock is OFF
,D/KeyguardViewMediator( 1136): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1136): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1545): Vacuum at: now=1452520987235 tag=VacuumService
,I/GoogleURLConnFactory( 1545): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1545): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1545): GC_CONCURRENT freed 1809K, 28% free 18058K/24832K, paused 7ms+5ms, total 75ms
,D/dalvikvm( 1545): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/Uploader( 1545): No account for auth token provided
,W/Uploader( 1545):  no longer exists, so no auth token.
,W/Uploader( 1545): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1452520996513626877; DSPS: 5275385; Offset: 1452520835521653001
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1452521016515737130; DSPS: 5930815; Offset: 1452520835521627023
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1136): handleBatteryUpdate (2) (100)
,D/WifiController(  956): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1136): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1452521036517308165; DSPS: 6586226; Offset: 1452520835521641662
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1136): handleTimeUpdate
,D/KeyguardModel( 1136): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1136): Clock updated, drawingStartTime : 1452521040040, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1136): Clock updated, drawingStartTime : 1452521040047, nextTick: 59962, mDrawingTime: 8
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1452521056519110761; DSPS: 7241645; Offset: 1452520835521643720
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1452521076521062941; DSPS: 7897069; Offset: 1452520835521642775
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1452521096522721996; DSPS: 8552483; Offset: 1452520835521653881
,D/KeyguardUpdateMonitor( 1136): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1136): handleTimeUpdate
,D/KeyguardModel( 1136): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1136): Clock updated, drawingStartTime : 1452521100025, nextTick: 60003, mDrawingTime: 4
,D/Clock   ( 1136): Clock updated, drawingStartTime : 1452521100058, nextTick: 59967, mDrawingTime: 4
,I/jxcore-log( 4654): --= Surplus to requirements =--
I/jxcore-log( 4654): 
,I/jxcore-log( 4654): ****TEST TOOK:  ms ****
I/jxcore-log( 4654): 
,I/jxcore-log( 4654): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4654): 
,D/AndroidRuntime( 5457): 
D/AndroidRuntime( 5457): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5457): CheckJNI is OFF
D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1452521116526452769; DSPS: 9207966; Offset: 1452520835521630992
,D/dalvikvm( 5457): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5457): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 5457): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5457): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5457): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5457): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5457): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5457): failed to load memtrack module: -2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 5457): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  956): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  956): Killing 4654:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  956): Moving to DESTROYED: ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
,I/MDM     (  956):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  956):   Force finishing activity ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  956): Moving to FINISHING: ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  956): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  956): moveHomeStack:
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7c0b0 stackId=0, 1 tasks}
,I/WindowState(  956): WIN DEATH: Window{44f07918 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  956): Client connection lost with reason: 4
,I/dalvikvm(  956): Total arena pages for JIT: 15
,W/PackageSettings(  956): Skipping PackageSetting{42d63420 com.example.hello/10312} due to missing metadata
,V/ActivityManager(  956): Moving to RESUMED: ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  956): Moving to PAUSING: ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  956): resumeTopActivityLocked: Resumed ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7c0b0 stackId=0, 1 tasks}
D/ActivityManager(  956): allPausedActivitiesComplete: r=ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  956): allPausedActivitiesComplete: r=ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  956): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/ActivityManager(  956): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
,I/ActivityManager(  956):   Force finishing activity ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3 f}
,W/ActivityManager(  956): Duplicate finish request for ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7c0b0 stackId=0, 1 tasks}
D/ActivityManager(  956): allPausedActivitiesComplete: r=ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,D/ActivityManager(  956): allPausedActivitiesComplete: r=ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  956): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,V/ActivityManager(  956): Moving to DESTROYED: ActivityRecord{45009d88 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7c0b0 stackId=0, 1 tasks}
D/ActivityManager(  956): allPausedActivitiesComplete: r=ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  956): allPausedActivitiesComplete: r=ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  956): resumeTopActivityLocked: Skip resume: some activity pausing.
I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/PhoneApp( 1447): getIsInUseVoLTE : false
D/KeyguardModel( 1136): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader(  956): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "sms"
,I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/AppUp4:Utils( 4026): [getPackageName] uri : package:com.test.thalitest
D/AppUp4  ( 4026): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 4026):  isExcludedPackage  packagename = com.test.thalitest
D/dalvikvm( 2665): GC_EXPLICIT freed 4101K, 28% free 17919K/24832K, paused 7ms+3ms, total 72ms
,D/AppUp4  ( 4026):  isExcludedPackage TRUE : com.test.thalitest
I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "smsto"
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/System.err( 2652): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 2652): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2652): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
,W/System.err( 2652): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2652): 	at android.os.Handler.handleCallback(Handler.java:733)
,W/System.err( 2652): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 2652): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2652): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2652): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 2652): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2652): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2652): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2652): 	at dalvik.system.NativeStart.main(Native Method)
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  956): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5476 uid=10090 gids={50090}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ActivityManager(  956): getAssistContextExtras failed: no resumed activity
I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "mms"
E/SlideAside( 3760): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/SlideAside( 3760): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
,W/GeofencerStateMachine( 1422): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  956): GC_EXPLICIT freed 3012K, 49% free 30001K/57900K, paused 8ms+14ms, total 190ms
,D/dalvikvm(  956): WAIT_FOR_CONCURRENT_GC blocked 100ms
,D/dalvikvm(  956): WAIT_FOR_CONCURRENT_GC blocked 85ms
,D/dalvikvm(  956): WAIT_FOR_CONCURRENT_GC blocked 94ms
D/dalvikvm(  956): WAIT_FOR_CONCURRENT_GC blocked 80ms
,D/dalvikvm(  956): WAIT_FOR_CONCURRENT_GC blocked 84ms
I/ActivityManager(  956): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5502 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
,W/ActivityManager(  956): getAssistContextExtras failed: no resumed activity
I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  956):   Scheme: "mmsto"
,D/GlobalAccess( 1136): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1136): changeTargets() succeeded. size: 20
D/administrator(  956): Handling package changes for user 0
,D/HyLog   ( 5476): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5476): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5476): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "sms"
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1136): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "smsto"
,D/HyLog   ( 5502): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5502): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5502): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/ActivityManager(  956): Moving to PAUSED: ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  956): Moving to STOPPING: ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "mms"
,I/LockScreenSettings( 5476): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1136): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1136): createShortcutInfo...
,I/PackageManager(  956):   Action: "android.intent.action.SENDTO"
I/PackageManager(  956):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  956):   Scheme: "mmsto"
I/PackageManager(  956): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/[BNRAppListMgrReceiver]( 5502): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
,D/KeyguardModel( 1136): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1136): createShortcutInfo...
,I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
,I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/KeyguardModel( 1136): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1136): createShortcutInfo...
,D/KeyguardModel( 1136): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1136): createShortcutInfo...
,D/KeyguardModel( 1136): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1136): createShortcutInfo...
,W/Binder  ( 1350): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1350): java.lang.NullPointerException
W/Binder  ( 1350): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1350): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1350): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1350): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  956): Killing 4575:com.lge.email/u0a24 (adj 15): empty #17
I/InputMethodManagerService(  956): IME STATUS OFF
W/InputMethodManagerService(  956): Got RemoteException sending setActive(false) notification to pid 4654 uid 10304
I/ActivityManager(  956): Killing 4800:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,D/KeyguardModel( 1136): handleShortcutListChanged...
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7c0b0 stackId=0, 1 tasks}
,D/KeyguardModel( 1136): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1136): createShortcutInfo...
,D/VoicemailCleanupService( 1831): Cleaning up data for package: com.test.thalitest
,D/ActivityManager(  956): resumeTopActivityLocked: Going to sleep and all paused
D/KeyguardModel( 1136): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1136): createShortcutInfo...
D/KeyguardModel( 1136): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1136): createShortcutInfo...
D/KeyguardModel( 1136): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1136): createShortcutInfo...
D/KeyguardModel( 1136): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1136): createShortcutInfo...
,D/KeyguardModel( 1136): handleShortcutListChanged...
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7c0b0 stackId=0, 1 tasks}
D/ActivityManager(  956): resumeTopActivityLocked: Going to sleep and all paused
,D/BackupManagerService(  956): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/InteractionManagerConfigurator(  956): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  956): com.test.thalitest isn't inclued in dragdropPackageList
V/BackupManagerService(  956): removePackageParticipantsLocked: uid=10304 #1
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
V/ActivityManager(  956): Moving to STOPPED: ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,D/dalvikvm( 1487): GC_CONCURRENT freed 5028K, 8% free 60537K/65748K, paused 1ms+2ms, total 20ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,D/dalvikvm( 1136): GC_CONCURRENT freed 5005K, 8% free 70300K/76124K, paused 2ms+8ms, total 51ms
,D/dalvikvm( 1136): WAIT_FOR_CONCURRENT_GC blocked 41ms
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/ActivityManager(  956): Timeline: Activity_windows_visible id: ActivityRecord{43101a38 u0 com.lge.launcher2/.Launcher t1} time:277633
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/dalvikvm(  956): GC_EXPLICIT freed 830K, 49% free 29934K/57900K, paused 5ms+17ms, total 252ms
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/PackageIntentReceiver( 2593): Not supported Hotkey customization function 
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/HideNavigationAppsReceiver( 2593): Receive package name : com.test.thalitest
,D/HideNavigationAppsReceiver( 2593): Delete mPackageMame : com.test.thalitest
,I/IcingCorporaProvider( 2665): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  956): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5520 uid=10073 gids={50073, 3003, 1028, 1015}
,D/HyLog   ( 5520): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5520): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5520): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  956): Start proc com.lge.email for content provider com.lge.email/.providers.LGEmailContentProvider: pid=5537 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
D/HyLog   ( 5537): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5537): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5537): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/IcingCorporaProvider( 2665): UpdateCorporaTask done [took 133 ms] updated apps [took 133 ms] 
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,D/AndroidRuntime( 5457): Shutting down VM
,D/dalvikvm( 5457): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 1ms
,I/LGEmail ( 5537): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/LGEmail ( 5537): EmailContentProvider.query: uri=content://com.lge.providers.lgemail/account, projection=[accountID, userName, mailAddress, accountName, InboxID], selection=null, selectionArgs=null sortOrder=null, TABLE_NAMES=EAccountmatch is 0 (at LGEmailContentProvider.java query 492)[v:null]
,E/LGEmail ( 5537): Email Not Started (at LGEmailContentProvider.java query 509)[v:6.30.33]
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  956): Killing 4815:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7c0b0 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,D/LGEmail ( 5537): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
D/ActivityManager(  956): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,W/BaseRuntimeLoader( 5537): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5537): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5537): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5537): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@42890f08 time:277905
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  956): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5564 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,W/GAV2    ( 5520): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/HyLog   ( 5564): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5564): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5564): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/ContextImpl( 5564): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,I/dalvikvm( 4252): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
,W/dalvikvm( 4252): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 4252): VFY: replacing opcode 0x6e at 0x0013
,E/NetworkScheduler.SchedulerReceiver( 1545): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1545): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  956): Killing 4828:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7c0b0 stackId=0, 1 tasks}
,D/ChimeraCfgMgr( 1940): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1940): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1940): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1940): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1940): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1940): Module APK com.google.android.play.games already loaded
,D/WeatherAncestor( 1846): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:5:17
,D/ActivityManager(  956): resumeTopActivityLocked: Going to sleep and all paused
D/UpdateThreadPoolManager( 1846): 2 : This is isUpdating : false
D/WeatherService( 1846): 2 : shouldTimeTickRegistered : false
D/WeatherAncestor( 1846): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:5:17
D/WeatherService( 1846): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherService( 1846): 2 : shouldTimeTickRegistered : false
D/PackageIntentReceiver( 2593): Not supported Hotkey customization function 
,E/SQLiteLog( 1940): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/LocationSettingsChecker( 1940): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  956): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5591 uid=10065 gids={50065, 1028, 4002}
,E/DriveAsyncService( 1940): disk I/O error (code 3850)
E/DriveAsyncService( 1940): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1940): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1940): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1940): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1940): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1940): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1940): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1940): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1940): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteDatabase( 1940): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1940): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 1940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1940): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1940): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1940): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1940): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/HyLog   ( 5591): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5591): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5591): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  956): Delaying start of: ServiceRecord{43da35f0 u0 com.google.android.gms/.wearable.service.WearableControlService}
E/SQLiteOpenHelper( 1940): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1940): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 1940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1940): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1940): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1940): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1940): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1940): Opened phenotype.db in read-only mode
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1545): onCreate
,I/ConfigFetchService( 1940): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1940): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/PeopleContactsSync( 1940): CP2 sync disabled
E/SQLiteDatabase( 1940): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1940): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 1940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1940): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1940): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1940): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1940): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1940): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1940): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1940): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Icing   ( 1940): doRemovePackageData com.test.thalitest
E/SQLiteOpenHelper( 1940): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1940): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 1940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1940): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1940): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1940): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1940): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1940): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1940): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1940): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1545): Failed to open database '/data/data/com.google.android.gms/databases/config.db'.
E/SQLiteDatabase( 1545): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 1545): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 1545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1545): 	at com.google.android.gms.config.ConfigService.a(SourceFile:47)
E/SQLiteDatabase( 1545): 	at com.google.android.gms.config.j.run(SourceFile:163)
E/SQLiteDatabase( 1545): 	at java.lang.Thread.run(Thread.java:841)
W/SQLiteOpenHelper( 1940): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1940): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1940): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1940): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1940): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1940): threadid=49: thread exiting with uncaught exception (group=0x41853e48)
I/Process ( 1940): Sending signal. PID: 1940 SIG: 9
E/SQLiteOpenHelper( 1545): Couldn't open config.db for writing (will try read-only):
E/SQLiteOpenHelper( 1545): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 1545): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 1545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1545): 	at com.google.android.gms.config.ConfigService.a(SourceFile:47)
E/SQLiteOpenHelper( 1545): 	at com.google.android.gms.config.j.run(SourceFile:163)
E/SQLiteOpenHelper( 1545): 	at java.lang.Thread.run(Thread.java:841)
D/Documents( 5591): Loading roots for com.android.externalstorage.documents
,W/SQLiteOpenHelper( 1545): Opened config.db in read-only mode
E/AndroidRuntime( 1940): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1940): Process: com.google.android.gms, PID: 1940
E/AndroidRuntime( 1940): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1940): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1940): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/AndroidRuntime( 1940): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 1940): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1940): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/AndroidRuntime( 1940): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1940): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1940): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1940): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1940): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  956): Can't write: system_app_crash
E/DropBoxManagerService(  956): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  956): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  956): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  956): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  956): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  956): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  956): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  956): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  956): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  956): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  956): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  956): 	... 5 more
E/SQLiteDatabase( 2652): Error inserting f006=10065 f003=com.android.documentsui f002=1452521117968 f005=5591 f004=13
E/SQLiteDatabase( 2652): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 2652): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2652): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:785)
E/SQLiteDatabase( 2652): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 2652): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2652): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
E/SQLiteDatabase( 2652): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1440)
E/SQLiteDatabase( 2652): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 2652): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 2652): 	at android.content.ContentResolver.insert(ContentResolver.java:1206)
E/SQLiteDatabase( 2652): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2406)
E/SQLiteDatabase( 2652): 	at com.lge.mlt.MltMonitorService.access$2500(MltMonitorService.java:38)
E/SQLiteDatabase( 2652): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3210)
E/SQLiteDatabase( 2652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2652): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2652): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3313)
E/SQLiteDatabase( 5591): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5591): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteDatabase.open(SQLit,eDatabase.java:890)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 5591): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 5591): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5591): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 5591): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 5591): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 5591): 	at android.content.ContentResolver.call(ContentResolver.java:1371)
E/SQLiteDatabase( 5591): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 5591): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2424)
E/SQLiteDatabase( 5591): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 5591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1276)
E/SQLiteDatabase( 5591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5591): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5591): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 5591): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5591): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 5591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 5591): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 5591): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 5591): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5591): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
W/System.err( 5591): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
W/System.err( 5591): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5591): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5591): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5591): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
W/System.err( 5591): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
W/System.err( 5591): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
W/System.err( 5591): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
W/System.err( 5591): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
W/System.err( 5591): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 5591): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 5591): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
W/System.err( 5591): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
W/System.err( 5591): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
W/System.err( 5591): 	at android.content.ContentResolver.call(ContentResolver.java:1371)
W/System.err( 5591): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
W/System.err( 5591): 	at android.app.ActivityThread.handleRecei,ver(ActivityThread.java:2424)
W/System.err( 5591): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
W/System.err( 5591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1276)
W/System.err( 5591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5591): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 5591): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 5591): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 5591): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 5591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 5591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 5591): 	at dalvik.system.NativeStart.main(Native Method)
I/Process ( 5591): Sending signal. PID: 5591 SIG: 9
I/ActivityManager(  956): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5616 uid=10005 gids={50005, 1028, 1015, 1023}
I/ActivityManager(  956): Killing 4842:com.lge.lgdmsgcm/1000 (adj 15): empty #17
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7c0b0 stackId=0, 1 tasks}
D/ActivityManager(  956): resumeTopActivityLocked: Going to sleep and all paused
D/WifiService(  956): Client connection lost with reason: 4
I/ActivityManager(  956): Killing 4865:com.lge.wireless_storage/u0a101 (adj 15): empty #17
I/ActivityManager(  956): Process com.google.android.gms (pid 1940) has died.
W/ActivityManager(  956): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  956): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  956): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  956): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
W/ActivityManager(  956): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
W/ActivityManager(  956): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10998ms
W/ActivityManager(  956): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10998ms
I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7c0b0 stackId=0, 1 tasks}

```
