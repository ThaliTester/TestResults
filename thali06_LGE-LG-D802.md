#### Test 549702613245198_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2046): nl80211: survey data missing!
D/WifiStateMachine(  968): handleMessage: X
,I/ConfigFetchService( 1841): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1841): launchTask
W/dalvikvm( 1841): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1841): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1841): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1841): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UeXbgrtq5UaH1PtNzxhszx9ynuBTUOlB5MV66phX8cxloM3QBDZrDBblsWWlGZF7cWGsRJFDKJDRAa_J3QGUZX1iY0IP4R7K11v6hE3b00pfBmkMWNUb4brBarySYoImtJtQYFCaXGHTyOkTSSqeV2HiSToNHyNIxXgRBaz99HoCh-irY4Epk_GujtqhaQhDSf0jBT
I/GoogleURLConnFactory( 1841): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1841): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1841): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1841): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1841): No vision deps
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/GAV2    ( 4691): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  968): Killing 3583:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 1 tasks}
I/PeopleContactsSync( 1841): CP2 sync disabled
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4332e320 u0 com.android.settings/.UsbSettings t2}
I/dalvikvm( 1841): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1841): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
W/BaseAppContext( 1841): Using Auth Proxy for data requests.
D/dalvikvm( 1841): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1841): Using Auth Proxy for data requests.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/BaseAppContext( 1841): Using Auth Proxy for data requests.
W/BaseAppContext( 1841): Using Auth Proxy for data requests.
W/BaseAppContext( 1841): Using Auth Proxy for data requests.
W/BaseAppContext( 1841): Using Auth Proxy for data requests.
D/dalvikvm( 1841): GC_CONCURRENT freed 1634K, 22% free 19425K/24832K, paused 3ms+4ms, total 34ms
D/AndroidRuntime( 4740): 
D/AndroidRuntime( 4740): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4740): CheckJNI is OFF
D/dalvikvm( 4740): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4740): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4740): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4740): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4740): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4740): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/dalvikvm( 1541): GC_EXPLICIT freed 1198K, 29% free 17823K/24832K, paused 1ms+3ms, total 25ms
I/ConfigFetchService( 1841): fetch service done; releasing wakelock
I/ConfigFetchService( 1841): stopping self
E/memtrack( 4740): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4740): failed to load memtrack module: -2
D/ChimeraCfgMgr( 1841): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1841): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4740): Calling main entry com.android.commands.am.Am
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4740
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (123 us)
V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{4332e320 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
D/ActivityManager(  968): resumeTopActivityLocked: Pausing null
V/ActivityManager(  968): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  968): startService SlideAside
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  968): setFocusedStack: mFocusedStack=ActivityStack{433660f8 stackId=1, 2 tasks}
D/UsbSettingsControl( 2592): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2592): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4740): Shutting down VM
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{4332e320 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{4332e320 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Restarting ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 4740): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 2ms
I/Icing   ( 1841): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
I/ActivityManager(  968): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4767 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/SlideAside( 3749): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  968): Moving to RESUMED: ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3749): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/HyLog   ( 4767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4767): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/SlideAside( 3749): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/WebViewChromium( 4767): Binding Chromium to the background looper Looper (main, tid 1) {428a3db0}
I/chromium( 4767): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4767): Initializing chromium process, renderers=0
D/Icing   ( 1841): Loaded CLD2 Version V2.0 - 20141016
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
I/Icing   ( 1841): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
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
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/OpenGLRenderer( 4767): Enabling debug mode 0
,W/AwContents( 4767): nativeOnDraw failed; clearing to background color.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/AwContents( 4767): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  968): IME STATUS OFF
,I/ActivityManager(  968): Displayed com.test.thalitest/.MainActivity: +381ms
,I/ActivityManager( 4767): Timeline: Activity_idle id: android.os.BinderProxy@428a5a80 time:109309
,D/JsMessageQueue( 4767): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4767): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428a9b60
D/dalvikvm( 4767): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428a9b60
D/jxcore_app_log( 4767): JniHelper::setJavaVM(0x4176c838), pthread_self() = 1632491376
D/JX-Cordova( 4767): jxcore cordova android initializing
D/ActivityManager(  968): no-history finish of ActivityRecord{4332e320 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  968): Finishing activity token=Token{43184760 ActivityRecord{4332e320 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  968): Moving to FINISHING: ActivityRecord{4332e320 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  968): Timeline: Activity_windows_visible id: ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3} time:109720
D/UsbSettings( 2592): [AUTORUN] onStop()
V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{4332e320 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  968): Moving to STOPPED: ActivityRecord{4332e320 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4767): GC_CONCURRENT freed 2776K, 12% free 21865K/24832K, paused 4ms+2ms, total 87ms
D/dalvikvm( 4767): WAIT_FOR_CONCURRENT_GC blocked 33ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4767): GC_FOR_ALLOC freed 112K, 12% free 21862K/24832K, paused 46ms, total 46ms
D/dalvikvm( 4767): GC_FOR_ALLOC freed 125K, 12% free 21882K/24832K, paused 41ms, total 41ms
I/dalvikvm-heap( 4767): Grow heap (frag case) to 23.634MB for 95956-byte allocation
D/dalvikvm( 4767): GC_FOR_ALLOC freed 178K, 13% free 21917K/24928K, paused 41ms, total 42ms
I/dalvikvm-heap( 4767): Grow heap (frag case) to 23.714MB for 143930-byte allocation
D/dalvikvm( 4767): GC_FOR_ALLOC freed 252K, 13% free 21964K/25072K, paused 38ms, total 38ms
I/dalvikvm-heap( 4767): Grow heap (frag case) to 23.829MB for 215890-byte allocation
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/dalvikvm( 4767): GC_FOR_ALLOC freed 366K, 13% free 22038K/25284K, paused 38ms, total 38ms
I/dalvikvm-heap( 4767): Grow heap (frag case) to 24.004MB for 323830-byte allocation
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 564K, 14% free 22159K/25604K, paused 35ms, total 35ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 24.276MB for 485740-byte allocation
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 860K, 15% free 22335K/26080K, paused 26ms, total 26ms
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 1275K, 14% free 22590K/26080K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 25.277MB for 1092904-byte allocation
,D/dalvikvm( 4767): GC_CONCURRENT freed 1791K, 16% free 22976K/27148K, paused 1ms+2ms, total 29ms
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 257K, 16% free 22903K/27148K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 26.103MB for 1639352-byte allocation
,D/dalvikvm( 4767): GC_CONCURRENT freed 1620K, 19% free 23480K/28752K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 1350K, 19% free 23550K/28752K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 27.517MB for 2459024-byte allocation
,D/dalvikvm( 4767): GC_CONCURRENT freed 1994K, 23% free 24257K/31156K, paused 1ms+5ms, total 47ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm( 4767): GC_CONCURRENT freed 2359K, 22% free 24496K/31156K, paused 1ms+3ms, total 39ms
,D/dalvikvm( 4767): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 4767): GC_FOR_ALLOC freed 294K, 22% free 24510K/31156K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4767): Grow heap (frag case) to 29.627MB for 3688532-byte allocation
,D/dalvikvm( 4767): GC_CONCURRENT freed 331K, 20% free 28111K/34760K, paused 5ms+4ms, total 54ms
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,W/jxcore-log( 4767): Initializing JXcore engine
,W/jxcore-log( 4767): JXcore engine is ready
,W/jxcore-log( 4767): Starting JXcore engine
,W/jxcore-log( 4767): Platform android
W/jxcore-log( 4767): 
,W/jxcore-log( 4767): Process ARCH arm
W/jxcore-log( 4767): 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/jxcore-log( 4767): JXcore Cordova bridge is ready!
I/jxcore-log( 4767): 
W/jxcore-log( 4767): JXcore engine is started
I/chromium( 4767): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/chromium( 4767): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4767): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/jxcore-log( 4767): Toggling radios to true
I/jxcore-log( 4767): 
D/BluetoothManagerService(  968): Message: 20
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44998b90:true
D/BluetoothAdapter( 4767): enable(): BT is already enabled..!
D/WifiService(  968): New client listening to asynchronous messages
D/WifiStateMachine(  968): handleMessage: E msg.what=131145
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doBoolean: DISCONNECT
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2046): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2046): wlan0: Cancelling scan request
D/wpa_supplicant( 2046): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2046): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2046): TDLS: Tear down peers
D/wpa_supplicant( 2046): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4767): Radios toggled
I/jxcore-log( 4767): 
D/WifiService(  968): setWifiEnabled: true pid=4767, uid=10304
E/WifiService(  968): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  968): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  968): disconnect pid=4767, uid=10304
D/WifiService(  968): reconnect pid=4767, uid=10304
D/wpa_supplicant( 2046): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2046): wlan0: Deauthentication notification
D/wpa_supplicant( 2046): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2046): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2046): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2046): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2046): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2046): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7cd9d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2046):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2046): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2046): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2046): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2046): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2046): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2046): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2046): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2046): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2046): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2046): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2046): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2046): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2046): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2046): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2046): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2046): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2046): nl80211: Event message available
D/wpa_supplicant( 2046): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2046): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  968): invokeExitMethods: ConnectedState
W/Settings(  968): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  968): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131146
D/WifiStateMachine(  968): processMsg: DisconnectingState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiNative-wlan0(  968): doBoolean: RECONNECT
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2046): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2046): Fast associate: Old scan results
D/wpa_supplicant( 2046): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2046): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2046): wlan0: nl80211: scan request
D/wpa_supplicant( 2046): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147460
D/wpa_supplicant( 2046): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiStateMachine(  968): processMsg: DisconnectingState
D/wpa_supplicant( 2046): nl80211: Event message available
D/wpa_supplicant( 2046): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2046): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): Network connection lost
D/WifiStateMachine(  968): Stopping DHCP and clearing IP
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  968): doBoolean: SET ps 1
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2046): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2046): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2046): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2046): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2046): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  968):    returned true
D/DhcpStateMachine(  968): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/WifiStateMachine(  968): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  968): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
D/QCNEA   (  413): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  413): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  413): |CAC| updateNetCfgInfo
V/QCNEA   (  413): |CAC| *********************************************
V/QCNEA   (  413): |CAC|                   Netconfig               
V/QCNEA   (  413): |CAC| *********************************************
V/QCNEA   (  413): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  413): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  413): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  413): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  413): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  413): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  413): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  413): |CAC| *********************************************
D/QCNEA   (  413): |CAC| Received bssid= 
D/QCNEA   (  413): |CAC| net type = 3
V/QCNEA   (  413): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  413): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  413): |CAC| 	ssid           =NG700
V/QCNEA   (  413): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  413): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  413): |CAC| *********************************************
D/QCNEA   (  413): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  413): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  413): |CAC| dispatchNetCfg: updating:0xb72238dc
D/QCNEA   (  413): |CAC| readCallback: read len:0, ret:-1, errno:11
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  968): hidePasspointNotification off =false
D/QcConnectivityService(  968): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 0
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  968): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
D/QcConnectivityService(  968): Attempting to switch to mobile
D/QcConnectivityService(  968): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  968): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=SCANNING
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
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
I/ActivityManager(  968): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4820 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  271): RouteController
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
V/        (  271): RouteController
V/        (  271): RouteController
V/        (  271): RouteController
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 4820): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4820): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4820): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  271): RouteController
V/        (  271): RouteController
V/        (  271): RouteController
V/        (  271): RouteController
I/PCSuite ( 4820): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
W/NetworkManagementService(  968): route cmd failed: 
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
D/NetUtils(  968): android_net_utils_resetConnections in env=0x628ca030 clazz=0x6d600001 iface=wlan0 mask=0x3
D/PCSuite ( 4820): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4820): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QcConnectivityService(  968): resetConnections(wlan0, 3)
V/NativeCrypto( 1541): Read error: ssl=0x62584c98: I/O error during system call, Connection timed out
V/NativeCrypto( 1541): SSL shutdown failed: ssl=0x62584c98: I/O error during system call, Broken pipe
I/ActivityManager(  968): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4856 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  968): Killing 4255:com.google.android.talk/u0a77 (adj 15): empty #17
D/HyLog   ( 4856): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4856): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4856): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/LocSvc_java(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=false
D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
D/QRemote ( 4856): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 4856): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4856): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4856): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4856): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4856): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4856): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 4856): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4856): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  968): Killing 3117:android.process.media/u0a23 (adj 15): empty #17
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  968): StoppedState
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/ProcessCpuTracker(  968): Skipping unknown process pid 4838
,W/ProcessCpuTracker(  968): Skipping unknown process pid 4839
,W/ProcessCpuTracker(  968): Skipping unknown process pid 4849
,W/ProcessCpuTracker(  968): Skipping unknown process pid 4876
,W/ProcessCpuTracker(  968): Skipping unknown process pid 4879
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4691): Thread[GAThread,5,main]: No campaign data found.
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.437759 Y: -0.410416 Z: 9.797318 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.437759 .y:-0.410416 .z:9.797318
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.431686 Y: -0.419037 Z: 9.805176 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.431686 .y:-0.419037 .z:9.805176
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,I/ConfigService( 1541): onDestroy
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/WifiController(  968): battery changed pluggedType: 2
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
,D/WifiStateMachine(  968): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4018): onReceive
,D/AppUp4:CustFacade( 4018): Context : android.app.ReceiverRestrictedContext@428be268
D/AppUp4:CustFacade( 4018): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4018): isOpenOperator : true
,D/AppUp4:CustFacade( 4018): isPhone : true
,I/LicenseContentProvider( 4032): start selecting data
,D/SIMObserver( 4032): simInfo1
,I/AppUp4:EulaManager( 4018): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4018): begin check event
,I/AppUp4:CustModeStarterReceiver( 4018): Event For GoodConnectivity
,I/ActivityManager(  968): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4895 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4895): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4895): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4895): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4895): DownloadService onCreate
D/wpa_supplicant( 2046): nl80211: Event message available
D/wpa_supplicant( 2046): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2046): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2046): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2046): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 2046): nl80211: Survey data missing
D/wpa_supplicant( 2046): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2046): wlan0: BSS: Add new id 8 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): wlan0: BSS: Add new id 9 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 2046): wlan0: New scan results available
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2046): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2046): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2046): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2046): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2046): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2046): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2046): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2046): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2046): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2046): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2046): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2046): WPS: AP[4] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2046): WPS: AP[5] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2046): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2046): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 00:37:b7:9d:3e:73]
D/wpa_supplicant( 2046): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2046): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53
D/wpa_supplicant( 2046): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2046): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2046): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2046): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2046): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2046): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2046): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2046): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2046): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2046): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2046): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00,:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7cdb5a8  current_ssid=0x0
D/wpa_supplicant( 2046): scard is not null..
D/wpa_supplicant( 2046): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2046): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2046): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2046): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2046): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2046): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2046): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2046): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2046): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2046): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2046): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2046): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2046): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2046): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/DownloadManager( 4895): in removeSpuriousFiles
D/wpa_supplicant( 2046): wlan0: Cancelling scan request
D/wpa_supplicant( 2046): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2046): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2046): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2046): RSN: PMKSA cache search - network_ctx=0xb7cdb5a8 try_opportunistic=0
D/wpa_supplicant( 2046): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2046): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2046): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2046): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2046): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2046): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2046): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2046): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2046): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2046): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2046): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2046): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2046): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2046): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2046): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2046): nl80211: Unsubscribe mgmt frames handle 0xb7cda590 (mode change)
D/wpa_supplicant( 2046): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7cda590
D/wpa_supplicant( 2046): nl80211: Register frame type=0xd0 nl_handle=0xb7cda590
D/wpa_supplicant( 2046): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2046): nl80211: Register frame type=0xd0 nl_handle=0xb7cda590
D/wpa_supplicant( 2046): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2046): nl80211: Register frame type=0xd0 nl_handle=0xb7cda590
D/wpa_supplicant( 2046): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2046): nl80211: Register frame type=0xd0 nl_handle=0xb7cda590
D/wpa_supplicant( 2046): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2046): nl80211: Register frame type=0xd0 nl_handle=0xb7cda590
D/wpa_supplicant( 2046): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2046): nl80211: Register frame type=0xd0 nl_handle=0xb7cda590
D/wpa_supplicant( 2046): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2046): nl80211: Register frame type=0xd0 nl_handle=0xb7cda590
D/wpa_supplicant( 2046): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2046): nl80211: Register frame type=0xd0 nl_handle=0xb7cda590
D/wpa_supplicant( 2046): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2046): nl80211: Register frame type=0xd0 nl_handle=0xb7cda590
D/wpa_supplicant( 2046): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2046): nl80211: Register frame type=0xd0 nl_handle=0xb7cda590
D/wpa_supplicant( 2046): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2046): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2046):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046):   * freq=2412
D/wpa_supplicant( 2046):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2046):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2046):   * Auth Type 0
D/wpa_supplicant( 2046):   * WPA Versions 0x2
V/DownloadManager( 4895): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/wpa_supplicant( 2046): nl80211: Connect request send successfully
D/wpa_supplicant( 2046): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2046): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2046): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2046): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2046): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2046): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 44:e9:dd:10:c0:ab]
D/wpa_supplicant( 2046): nl80211: if_removed already cleared - ignore event
D/EAS     ( 4674): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@428e6dc0 on behalf of 4895
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/WifiStateMachine(  968): handleMessage: E msg.what=147461
W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  968): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2046): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2046): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2046): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2046): WPS: Unknown Vendor Extension (Vendor ID 311)
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
I/DownloadManager( 4895): in trimDatabase
V/DownloadManager( 4895): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@428eb258 on behalf of 4895
D/WifiStateMachine(  968): handleMessage: X
V/DownloadManager( 4895): DownloadService onStartCommand
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
V/DownloadManager( 4895): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4674): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@428ee5d0 on behalf of 4895
D/eas_req ( 4674): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4895): DownloadService onDestroy
I/LgeMiscReceiver( 4435): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4435): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4435): networkInfo.isConnected() = false
W/linker  ( 4674): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4674): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4674): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4674): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4674): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4674): register_HtmlEditor, Success
D/HtmlEditor( 4674): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4674): register_HtmlEditorTimer, Success
D/HtmlEditor( 4674): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4674): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4674): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4674): register_HtmlEditorFont, Success
D/HtmlEditor( 4674): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4674): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4674): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4674): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4674): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4674): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4674): JNI_OnLoad Success
,I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4925 uid=10052 gids={50052, 3003}
I/HubEmail( 4674): JNI_OnLoad()
I/HubEmail( 4674): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4674): registerNatives()
I/HubEmail( 4674): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4674): registerNativeMethods()
I/HubEmail( 4674): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/wpa_supplicant( 2046): nl80211: Event message available
D/wpa_supplicant( 2046): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2046): nl80211: Connect event
D/wpa_supplicant( 2046): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2046): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2046): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2046): wlan0: Association info event
D/wpa_supplicant( 2046): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2046): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2046): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2046): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2046): wlan0: freq=2412 MHz
D/wpa_supplicant( 2046): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2046): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2046): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2046): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2046): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2046): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): scard is not null..
D/wpa_supplicant( 2046): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2046): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2046): TDLS: Remove peers on association
D/wpa_supplicant( 2046): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2046): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2046): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2046): EAPOL: enable timer tick
D/wpa_supplicant( 2046): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2046): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2046): wlan0: Cancelling scan request
D/wpa_supplicant( 2046): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2046): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2046): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2046): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2046): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2046): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2046): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2046): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2046): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2046): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
W/WifiMonitor(  968): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
W/Settings( 4674): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  968): Killing 3925:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/HyLog   ( 4925): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4925): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4925): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
D/wpa_supplicant( 2046): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 95 57 22 b6 6e ca 0d 34 ca 42 22 67 b3 1a 81 ...
D/wpa_supplicant( 2046): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2046): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2046): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2046): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2046): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2046):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2046):   key_nonce - hexdump(len=32): 95 57 22 b6 6e ca 0d 34 ca 42 22 67 b3 1a 81 5c fc 70 f5 0a 74 f3 d3 a0 9e 93 0e 5f c9 0b 07 06
D/wpa_supplicant( 2046):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2046):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2046):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2046):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2046): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 95 57 22 b6 6e ca 0d 34 ca 42 22 67 b3 1a 81 ...
D/wpa_supplicant( 2046): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2046): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2046): Get randomness: len=32 entropy=10
D/wpa_supplicant( 2046): WPA: Renewed SNonce - hexdump(len=32): 6d b8 0e 70 bb c2 59 97 e9 e9 74 3d 69 bc 8e 12 43 af 5d f7 a7 b6 fe 65 ad 22 09 8a 4c fe 25 0d
D/wpa_supplicant( 2046): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046): WPA: Nonce1 - hexdump(len=32): 6d b8 0e 70 bb c2 59 97 e9 e9 74 3d 69 bc 8e 12 43 af 5d f7 a7 b6 fe 65 ad 22 09 8a 4c fe 25 0d
D/wpa_supplicant( 2046): WPA: Nonce2 - hexdump(len=32): 95 57 22 b6 6e ca 0d 34 ca 42 22 67 b3 1a 81 5c fc 70 f5 0a 74 f3 d3 a0 9e 93 0e 5f c9 0b 07 06
D/wpa_supplicant( 2046): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2046): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2046): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2046): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2046): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2046): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2046): WPA: Derived Key MIC - hexdump(len=16): ec e5 39 81 54 65 fe 33 30 7c fa 92 5c 11 d6 92
D/wpa_supplicant( 2046): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 6d b8 0e 70 bb c2 59 97 e9 e9 74 3d 69 bc 8e ...
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
V/LGRssiData( 4925): [loadRssi] File not exist 
V/LGRssiData( 4925): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4925): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4925): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4925): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4925): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4925): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/wpa_supplicant( 2046): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 95 57 22 b6 6e ca 0d 34 ca 42 22 67 b3 1a 81 ...
D/wpa_supplicant( 2046): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2046): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2046): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2046): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2046):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2046):   key_nonce - hexdump(len=32): 95 57 22 b6 6e ca 0d 34 ca 42 22 67 b3 1a 81 5c fc 70 f5 0a 74 f3 d3 a0 9e 93 0e 5f c9 0b 07 06
D/wpa_supplicant( 2046):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2046):   key_rsc - hexdump(len=8): 31 65 00 00 00 00 00 00
D/wpa_supplicant( 2046):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2046):   key_mic - hexdump(len=16): 31 64 43 8a d2 64 82 9a f3 f1 c3 e6 15 ce b2 a5
D/wpa_supplicant( 2046): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 95 57 22 b6 6e ca 0d 34 ca 42 22 67 b3 1a 81 ...
D/wpa_supplicant( 2046): RSN: encrypted key data - hexdump(len=56): b0 6c b3 16 6a b7 25 bb a3 f0 f4 fa 33 8c a0 e0 68 76 8a ba 11 6f 9f 3d fc 12 75 03 85 56 21 de ...
D/wpa_supplicant( 2046): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2046): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2046): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2046): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 22 85 ...
V/TelephonyAutoProfiling( 4925): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/wpa_supplicant( 2046): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2046): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2046): wlan0: WPA: Sending EAPOL-Key 4/4
V/TelephonyAutoProfiling( 4925): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
D/wpa_supplicant( 2046): WPA: KCK - hexdump(len=16): [REMOVED]
V/TelephonyAutoProfiling( 4925): [getValue] FEATURE key : vzw_roaming_state, value : null
D/wpa_supplicant( 2046): WPA: Derived Key MIC - hexdump(len=16): bc 6b 5a ea 4a f8 3a 24 9e c6 3b 7a 2c 87 d0 19
D/wpa_supplicant( 2046): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2046): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7cdac54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2046):    addr=c0:ff:d4:d3:aa:48
D/MobileConnectivityChangeReceiver( 4925): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4925): onReceive CONNECTIVITY_CHANGE networkType=1
D/wpa_supplicant( 2046): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2046): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2046): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2046): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2046): WPA: RSC - hexdump(len=6): 31 65 00 00 00 00
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6edd03a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2046):    broadcast key
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/PhoneMonitor( 4925): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4925): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/wpa_supplicant( 2046): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2046): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2046): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2046): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2046): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2046): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2046): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2046): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2046): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2046): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2046): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2046): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2046): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2046): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2046): EAPOL authentication completed successfully
D/wpa_supplicant( 2046): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2046): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2046): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): Network connection established
D/WifiNative-wlan0(  968): doString: STATUS
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4939 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  968): Killing 4407:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2046): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/WifiServiceExtension(  968): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  968): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-9ms what=147462 obj=android.net.wifi.StateChangeResult@43dab378 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-6ms what=147462 obj=android.net.wifi.StateChangeResult@43dacad8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/DhcpStateMachine(  968): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  968): WaitBeforeStartState
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WifiStateMachine(  968): ObtainingIpState{ when=-5ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
D/wpa_supplicant( 2046): nl80211: survey data missing!
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196612
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2046): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
D/HyLog   ( 4939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4939): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  968): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4954 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  968): Killing 4596:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/HyLog   ( 4954): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4954): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4954): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  275): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+2ms, total 20ms
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,D/LGDMClient( 2864): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  968): Killing 4632:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/LGDMClient( 2864): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 15ms
,D/wpa_supplicant( 2046): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  968): doBoolean: SET ps 0
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2046): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2046): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2046): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2046): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2046): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  968):    returned null
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2046): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2046): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  968):    returned null
E/WifiStateMachine(  968): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  968): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  968): DHCP Start wake lock is acquired.
,D/CommandListener(  271): Setting iface cfg
D/WifiP2pService(  968): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43354690 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43354690 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  271): Trying to bring up wlan0
D/WifiStateMachine(  968): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  968): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-1ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196613
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 15ms
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  968): doBoolean: SET ps 1
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2046): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2046): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2046): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2046): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2046): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
,D/WifiStateMachine(  968): DHCP successful
D/WifiP2pService(  968): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  968): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  968): VerifyingLinkState enter
,D/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  968): handleMessage: X
I/ActivityManager(  968): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4967 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,W/WifiStateTracker(  968): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  968): 
W/WifiStateTracker(  968):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  968):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  968): send additional Connectivity Action
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
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
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  968): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): CaptivePortalCheckState enter
D/WifiStateMachine(  968): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  968): handleMessage: X
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
,E/Parcel  (  413): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WifiStateMachine(  968): handleMessage: E msg.what=131092
D/WifiStateMachine(  968): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  968): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 4967): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4967): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4967): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/QcConnectivityService(  968): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/WifiStateMachine(  968): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
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
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 1
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/LGDMSGCM( 4967): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
E/ActivityThread(  968): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  968): handleConnectivityChange: preConnState=2 connState=1
W/ContextImpl( 4967): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/ActivityManager(  968): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4985 uid=10101 gids={50101, 1028, 1015, 3003}
,V/        (  271): RouteController
,I/ActivityManager(  968): Killing 4661:com.lge.bnr/1000 (adj 15): empty #17
V/        (  271): RouteController
V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,D/QCNEA   (  413): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  413): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  413): |CAC| updateNetCfgInfo
V/QCNEA   (  413): |CAC| *********************************************
V/QCNEA   (  413): |CAC|                   Netconfig               
,V/QCNEA   (  413): |CAC| *********************************************
V/QCNEA   (  413): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  413): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  413): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  413): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  413): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  413): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  413): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  413): |CAC| *********************************************
D/QCNEA   (  413): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  413): |CAC| net type = 1
V/QCNEA   (  413): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  413): |CAC| Received ssid= NG700
V/QCNEA   (  413): |CAC| 	ssid           =NG700
V/QCNEA   (  413): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  413): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  413): |CAC| *********************************************
D/QCNEA   (  413): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  413): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  413): |CAC| dispatchNetCfg: updating:0xb72238dc
,D/QCNEA   (  413): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
,D/DhcpStateMachine(  968): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  968): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  968): GC_EXPLICIT freed 23630K, 49% free 29783K/57880K, paused 2ms+8ms, total 140ms
,D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 4985): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4985): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4985): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 4985): connectivityManager.getNetworkInfo = TYPE_WIFI
I/CheckinService( 1841): Checking schedule, now: 1452283732811 next: 1452283677163
,I/CheckinService( 1841): active receiver: enabled
,I/Wireless_Storage( 4985): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4985): intf.getDisplayName() = lo
I/Wireless_Storage( 4985): intf.getDisplayName() = sit0
I/Wireless_Storage( 4985): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4985): intf.getDisplayName() = teql0
I/Wireless_Storage( 4985): intf.getDisplayName() = wlan0
D/NFS     ( 4985): interface name:wlan0 name:wlan0
D/NFS     ( 4985): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4985): interface name:wlan0 name:wlan0
,D/NFS     ( 4985): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4985): CONNECT : WIFI_CONNECT
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinService( 1841): Preparing to send checkin request
,I/EventLogService( 1841): Accumulating logs since 1452283644314
E/BatteryObserver( 1155): usb Uevent not necessary.
I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5017 uid=10104 gids={50104, 3003, 1028, 1015}
I/ActivityManager(  968): Killing 4304:com.android.contacts/u0a21 (adj 15): empty #17
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  968): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HyLog   ( 5017): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5017): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5017): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  968): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1222): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/CheckinRequestBuilder( 1841): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1841): Failed to find provider info for com.google.android.wearable.settings
,W/GAV2    ( 5017): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/WebViewChromium( 5017): Binding Chromium to the main looper Looper (main, tid 1) {428a2088}
I/chromium( 5017): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5017): Initializing chromium process, renderers=0
,W/chromium( 5017): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5017): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5017): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5017): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5017): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5017): Remote Branch: 
I/Adreno-EGL( 5017): Local Patches: 
I/Adreno-EGL( 5017): Reconstruct Branch: 
,I/GLSUser ( 1541): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1541): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1541): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1541): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1541): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1541): [DefaultAuthDelegateService] Use browser flow? false
,I/NSApplication( 5017): Starting up...
,I/ActivityManager(  968): Killing 4318:com.android.gallery3d/u0a27 (adj 15): empty #17
D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x4313a810: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1841): awaiting user notification for token
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4856): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4856): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4856): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4856): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/ActivityManager(  968): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5071 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/QRemote ( 4856): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4856): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4820): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/HyLog   ( 5071): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5071): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5071): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/PCSuite ( 4820): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4856): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4856): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4856): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4856): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
W/dalvikvm( 5071): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5071): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5071): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5071): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5071): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 5071): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5071): install
,I/MultiDex( 5071): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5071): loading existing secondary dex files
,I/MultiDex( 5071): load found 3 secondary dex files
,I/MultiDex( 5071): install done
,D/dalvikvm( 5071): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 5071): VFY: unable to resolve instance field 61
D/dalvikvm( 5071): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 5071): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5071): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5071): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5071): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5071): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5071): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5071): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5071): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5071): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a9670
D/dalvikvm( 5071): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a9670
,D/dalvikvm( 5071): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a9670, skipping init
,D/dalvikvm( 5071): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a9670
D/dalvikvm( 5071): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a9670
,V/JNIHelp ( 5071): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 5071): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a9670
,D/dalvikvm( 5071): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428a9670
D/dalvikvm( 5071): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a9670
,D/dalvikvm( 5071): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428a9670
,D/DhcpStateMachine(  968): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  968): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  968): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  968): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  968): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  968): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  968): RunningState
,I/ProviderInstaller( 5071): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1541): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1541): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1541): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1841): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1786): callingUid 10006, callindPid: 1786
,D/LocationInitializer( 1841): Restart initialization of location
,E/MDM     ( 1427): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 5071): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5071): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5071): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5071): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5071): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5071): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f57000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f57000
,D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  277): PrepareKeyRequest: nonce=917394272
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2046): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2046): EAPOL: disable timer tick
,D/dalvikvm( 5071): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a7ed40
D/dalvikvm( 5071): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a7ed40
,D/dalvikvm( 5071): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a7ed40, skipping init
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  968): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm( 5071): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 5093): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 5071): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5071): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 97ms
,I/Adreno-EGL( 5071): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5071): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5071): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5071): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5071): Remote Branch: 
I/Adreno-EGL( 5071): Local Patches: 
I/Adreno-EGL( 5071): Reconstruct Branch: 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1,
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=1418059529
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,W/Settings( 5071): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 5071): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5071): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5071): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5071): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5071): Remote Branch: 
I/Adreno-EGL( 5071): Local Patches: 
I/Adreno-EGL( 5071): Reconstruct Branch: 
,I/Adreno-EGL( 5071): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5071): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5071): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5071): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5071): Remote Branch: 
I/Adreno-EGL( 5071): Local Patches: 
I/Adreno-EGL( 5071): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1841): Classify the device as Phone.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  968): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
,D/WifiStateMachine(  968): processMsg: DefaultState
,D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  968): send additional Connectivity Action
,D/WifiStateMachine(  968): handleMessage: X
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  968): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  968):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  968): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,I/CheckinTask( 1841): Sending checkin request (11464 bytes)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1841): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1841): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1541): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1541): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1541): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1541): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1541): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1541): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x42e14e98: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1841): awaiting user notification for token
D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1841): Classify the device as Phone.
,I/CheckinTask( 1841): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1841): Checking schedule, now: 1452283735203 next: 1452861131198
,I/CheckinService( 1841): active receiver: disabled
,D/GCM     ( 1541): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1841): GC_CONCURRENT freed 1821K, 22% free 19539K/24832K, paused 4ms+2ms, total 42ms
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
E/Parcel  (  413): Reading a NULL string not supported here.
,E/Parcel  (  413): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/GCM     ( 1541): Connected
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1541): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4018): onReceive
,D/AppUp4:CustFacade( 4018): Context : android.app.ReceiverRestrictedContext@428be268
D/AppUp4:CustFacade( 4018): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4018): isOpenOperator : true
,D/AppUp4:CustFacade( 4018): isPhone : true
,I/LicenseContentProvider( 4032): start selecting data
,D/SIMObserver( 4032): simInfo1
,I/AppUp4:EulaManager( 4018): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4018): begin check event
,I/AppUp4:CustModeStarterReceiver( 4018): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4018): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4018): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4018): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4018): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4018): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4674): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4895): DownloadService onCreate
,D/EAS     ( 4674): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4674): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4435): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4435): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4435): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4925): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4925): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2864): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4967): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/NFS     ( 4985): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4985): CONNECT : WIFI_CONNECT
W/ContextImpl( 4967): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 4895): in removeSpuriousFiles
,W/Settings( 4674): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4895): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2864): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@428f4468 on behalf of 4895
I/DownloadManager( 4895): in trimDatabase
V/DownloadManager( 4895): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/LGDMClient( 2864): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@428f5558 on behalf of 4895
E/LGDMClient( 2864): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2864): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2864): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 4895): DownloadService onStartCommand
V/DownloadManager( 4895): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2864): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@428f8010 on behalf of 4895
V/DownloadManager( 4895): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4018): onReceive
,D/AppUp4:CustFacade( 4018): Context : android.app.ReceiverRestrictedContext@428be268
D/AppUp4:CustFacade( 4018): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4018): isOpenOperator : true
,D/AppUp4:CustFacade( 4018): isPhone : true
,I/LicenseContentProvider( 4032): start selecting data
,D/SIMObserver( 4032): simInfo1
,I/AppUp4:EulaManager( 4018): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4018): begin check event
,I/AppUp4:CustModeStarterReceiver( 4018): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4895): DownloadService onCreate
,I/DownloadManager( 4895): in removeSpuriousFiles
,V/DownloadManager( 4895): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@428fc698 on behalf of 4895
D/EAS     ( 4674): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 4895): in trimDatabase
,V/DownloadManager( 4895): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/EAS     ( 4674): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4895): DownloadService onStartCommand
,V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@428fe008 on behalf of 4895
,V/DownloadManager( 4895): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@428ffd00 on behalf of 4895
I/LgeMiscReceiver( 4435): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4435): action = android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 4674): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4435): networkInfo.isConnected() = true
,D/PhoneState( 4435): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4925): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4925): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4895): DownloadService onDestroy
,D/LGDMClient( 2864): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4967): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2864): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2864): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4985): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4985): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4967): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2864): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2864): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2864): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2864): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,D/WifiController(  968): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/jxcore-log( 4767): Test app app.js loaded
I/jxcore-log( 4767): 
I/Choreographer( 4767): Skipped 424 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4767): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  968): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4018): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4018): onReceive
,D/AppUp4:CustFacade( 4018): Context : android.app.ReceiverRestrictedContext@428be268
D/AppUp4:CustFacade( 4018): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4018): isOpenOperator : true
,D/AppUp4:CustFacade( 4018): isPhone : true
,I/LicenseContentProvider( 4032): start selecting data
,D/SIMObserver( 4032): simInfo1
,I/AppUp4:EulaManager( 4018): getAgreementForKK : Eula agreement is false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  291): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,E/BatteryObserver( 1155): usb Uevent not necessary.
D/AppUp4:CustModeStarterReceiver( 4018): begin check event
,I/AppUp4:CustModeStarterReceiver( 4018): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received.
D/EAS     ( 4674): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
V/DownloadManager( 4895): DownloadService onCreate
,D/EAS     ( 4674): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4895): in removeSpuriousFiles
,V/DownloadManager( 4895): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/LgeMiscReceiver( 4435): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4435): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4435): networkInfo.isConnected() = true
,D/PhoneState( 4435): setPdpRejectCasuse : false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@42903ec8 on behalf of 4895
I/DownloadManager( 4895): in trimDatabase
V/DownloadManager( 4895): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/MobileConnectivityChangeReceiver( 4925): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4925): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4674): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
,V/WifiServiceExtension(  968): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
D/dalvikvm(  968): GC_EXPLICIT freed 2352K, 49% free 29695K/57880K, paused 4ms+7ms, total 93ms
V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@42905570 on behalf of 4895
V/DownloadManager( 4895): DownloadService onStartCommand
,V/DownloadManager( 4895): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4895): created cursor android.database.sqlite.SQLiteCursor@42907ab0 on behalf of 4895
,V/DownloadManager( 4895): DownloadService onDestroy
,D/LGDMClient( 2864): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2864): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4967): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2864): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4967): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4985): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4985): CONNECT : WIFI_CONNECT
E/LGDMClient( 2864): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2864): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2864): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2864): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GAV2    ( 5017): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  968): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  968): Killing 4691:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452283740032, nextTick: 59999, mDrawingTime: 1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452283740033, nextTick: 59999, mDrawingTime: 0
,D/Finsky  ( 4336): [414] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4336): [1] 5.onFinished: Installation state replication succeeded.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  968): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  968): battery changed pluggedType: 2
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
D/WifiController(  968): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/WifiController(  968): battery changed pluggedType: 2
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  968): battery changed pluggedType: 2
D/HeadsetStateMachine( 1222): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/WifiController(  968): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  968): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/InputReader(  968): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "sms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) },
,E/SlideAside( 3749): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,D/administrator(  968): Handling package changes for user 0
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5206 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 3749): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5206): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5206): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5206): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
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
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.444000 Y: -0.419083 Z: 9.811813 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444000 .y:-0.419083 .z:9.811813
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.457672 Y: -0.423981 Z: 9.812988 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457672 .y:-0.423981 .z:9.812988
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,I/Babel   ( 5206): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5206): MmsConfig.loadMmsSettings
I/MediaCodecList( 5206): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5206): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5206): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5206): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5206): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5206): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5206): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5206): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5206): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5206): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5206): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5206): MmsConfig.loadFromResources
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452283743429772670; DSPS: 4295624; Offset: 1452283612337731655
E/Babel   ( 5206): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5206): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5206): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5206): [loadRssi] File not exist 
V/LGRssiData( 5206): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5206): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 5206): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/AppUp4:Utils( 4018): [getPackageName] uri : package:com.google.android.gms
V/TelephonyAutoProfiling( 5206): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5206): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4  ( 4018): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4018): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4018): onReceive
D/AppUp4:CustFacade( 4018): Context : android.app.ReceiverRestrictedContext@428be268
D/AppUp4:CustFacade( 4018): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4018): isOpenOperator : true
,D/AppUp4:CustFacade( 4018): isPhone : true
I/LicenseContentProvider( 4032): start selecting data
,D/SIMObserver( 4032): simInfo1
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/AppUp4:EulaManager( 4018): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4018): begin check event
D/AppUp4:Utils( 4018): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4018): Event For Nothing, skip.
,V/GmsNetworkLocationProvi( 1427): DISABLE
I/ActivityManager(  968): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5243 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/HyLog   ( 5243): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5243): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5243): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5243): BUILD Country: EU
,I/SystemConfig( 5243): BUILD Operator: OPEN
,I/SystemConfig( 5243): systemFeature RCS result false
,D/SystemConfig( 5243): refreshRcsSupport() :false
I/ActivityManager(  968): Killing 4820:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  968): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5265 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5265): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5265): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5265): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  968): Killing 4856:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,D/LocationProviderProxy(  968): applying state to connected service
,D/LocationProviderProxy(  968): applying state to connected service
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/ActivityManager(  968): Killing 4895:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2680): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1841): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1841): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  968): Delaying start of: ServiceRecord{44abd008 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1841): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/IcingCorporaProvider( 2680): UpdateCorporaTask done [took 415 ms] updated apps [took 415 ms] 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,E/Parcel  (  413): Reading a NULL string not supported here.
,E/Parcel  (  413): Reading a NULL string not supported here.
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  968): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  968): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  968): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  968): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  968): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  413): Reading a NULL string not supported here.
,E/Parcel  (  413): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/GAV4    ( 5206): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,I/PowerManagerService(  968): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  968): [updateScreenState] screen on = false
D/KnockOnPowerController(  968): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  968): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  968): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  968): _hal_sensors_flush: handle=35
,D/KnockOnPowerController(  968): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  968): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  968): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8581 usec
,D/qcom_sensors_hal(  968): hal_acquire_resources
,I/qcom_sensors_hal(  968): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  968): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  968): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  968): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  968): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  968): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  968): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  968): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.454330 Y: -0.417160 Z: 9.806854 
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.446548 Y: -0.446014 Z: 9.785751 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.454330 .y:-0.417160 .z:9.806854
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.453918 Y: -0.418671 Z: 9.826279 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453918 .y:-0.418671 .z:9.826279
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,I/Sensors (  396): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  968): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  968): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  968): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  968): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  968): proximitySensorChanged  positive = true
I/KnockOnPowerController(  968): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.456726 Y: -0.422623 Z: 9.826691 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456726 .y:-0.422623 .z:9.826691
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.432587 Y: -0.407669 Z: 9.831345 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.432587 .y:-0.407669 .z:9.831345
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.443726 Y: -0.421402 Z: 9.810883 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443726 .y:-0.421402 .z:9.810883
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.447937 Y: -0.418991 Z: 9.805908 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447937 .y:-0.418991 .z:9.805908
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  968): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44c979e8)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  968): **** SHOWN CALLED ****
,D/SurfaceFlinger(  274): Screen released, type=0 flinger=0xb8565450
V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.450989 Y: -0.412720 Z: 9.810440 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450989 .y:-0.412720 .z:9.810440
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,I/WindowManager(  968): No lock screen! windowToken=null
D/qdhwcomposer(  274): hwc_blank: Blanking display: 0
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/WifiStateMachine(  968): handleScreenStateChanged: true
,D/WifiStateMachine(  968): handleMessage: E msg.what=131154
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131127
D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=131158
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiServiceExtension(  968): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  968): handleMessage: E msg.what=132097
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
,D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  968): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2046): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2046): initialize kt scan interval and do scan state=9
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  968): stopMonitoring
,E/AudioSystem(  968): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 968
V/SRS_Proc(  277): ParamSet string: screen_state=on
,D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43413b08 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/WeatherAncestor( 1770): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 21:9:14
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/SlideAside( 3749): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
I/SlideAside( 3749): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/WifiStateMachine(  968): handleMessage: X
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1770): 2 : This is isUpdating : false
,D/WeatherAncestor( 1770): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 21:9:14
,D/WeatherService( 1770): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1770): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/WeatherService( 1770): 2 : shouldTimeTickRegistered : false
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1155): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1155): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1155): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1155): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1155): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1155): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  274): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  968): Excessive delay in blankDisplay() while turning screen off: 399ms
D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
,D/dalvikvm( 1155): GC_CONCURRENT freed 2905K, 11% free 25450K/28532K, paused 5ms+4ms, total 49ms
,D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1155): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1155): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 57, B = 57
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,D/qdlights( 1155): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 51, B = 51
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452283755485, nextTick: 44545, mDrawingTime: 1
,D/qdlights( 1155): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1155): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1155): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1155): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452283755555, nextTick: 44477, mDrawingTime: 0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/WeatherService( 1770): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 21:9:15
,D/WeatherService( 1770): 2 : ACTION screen on
,D/WeatherService( 1770): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1770): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 21:9:15
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
,E/Parcel  (  413): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): ACTION_SCREEN_ON
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  968): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  968): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.446594 Y: -0.409668 Z: 9.812729 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446594 .y:-0.409668 .z:9.812729
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
D/qcom_sensors_hal(  968): hal_acquire_resources
D/qcom_sensors_hal(  968): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  968): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=1000
V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  968): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  968): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  968): hal_smgr_report_delete: Rcvd success response from request
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  968): Vibrator off
V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,D/UsbSettings( 2592): [AUTORUN] onDestroy() : getDefaultFunction =boot
,D/WifiStateMachine(  968): handleScreenStateChanged: false
D/WifiStateMachine(  968): handleMessage: E msg.what=131154
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131158
D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 1
V/UsbSettings( 2592): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
,V/UsbSettings( 2592): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2592): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,E/AudioSystem(  968): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 968
V/SRS_Proc(  277): ParamSet string: screen_state=off
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2046): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
V/ActivityManager(  968): Moving to DESTROYING: ActivityRecord{4332e320 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/WifiController(  968): CMD_SCREEN_OFF 
D/WifiController(  968): shouldWifiStayAwake TRUE
V/ActivityManager(  968): Moving to STOPPED: ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3} (stop complete)
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/wpa_supplicant( 2046): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
,D/WifiNative-wlan0(  968):    returned true
,D/WifiStateMachine(  968): handleMessage: X
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/EmotionalLed( 1155): RESTART MSG
D/VolumeVibrator( 1155): clear
V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{4332e320 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{433660f8 stackId=1, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=2
,I/[LGHome]EVENT( 1492): [Launcher.java:1567:onReceive()]Screen Off
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
E/Parcel  (  413): Reading a NULL string not supported here.
,E/Parcel  (  413): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WeatherService( 1770): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 21:9:15
D/WeatherService( 1770): 2 : ACTION screen off
D/WeatherService( 1770): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 21:9:15
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
,D/NfcService( 1477): NFC-C OFF
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_OFF
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): ACTION_SCREEN_OFF
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1465): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,I/Sensors (  396): sns_pwr.c(320):releasing wakelock,
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): handleMessage: X
,E/ThermalEngine(  291): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): handleMessage: X
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452283763431604694; DSPS: 4951045; Offset: 1452283612337702107
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1541): Vacuum at: now=1452283763792 tag=VacuumService
,I/GoogleURLConnFactory( 1541): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1541): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1541): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1541): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1541): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1541): No account for auth token provided
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1541): GC_CONCURRENT freed 1821K, 28% free 18031K/24832K, paused 3ms+6ms, total 52ms
,W/Uploader( 1541): No account for auth token provided
,W/Uploader( 1541):  no longer exists, so no auth token.
,W/Uploader( 1541): No account for auth token provided
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452283783433346665; DSPS: 5606462; Offset: 1452283612337704576
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452283800056, nextTick: 59974, mDrawingTime: 1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452283800060, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452283803435064105; DSPS: 6261878; Offset: 1452283612337713031
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452283823436929358; DSPS: 6917299; Offset: 1452283612337716712
,D/wpa_supplicant( 2046): wlan0: BSS: Remove id 7 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 dc:4a:3e:0f:c2:f1]
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452283843438623569; DSPS: 7572715; Offset: 1452283612337701939
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452283860042, nextTick: 59983, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452283860048, nextTick: 59964, mDrawingTime: 7
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452283863440646583; DSPS: 8228141; Offset: 1452283612337710792
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452283883441992825; DSPS: 8883545; Offset: 1452283612337714261
,I/jxcore-log( 4767): --= Surplus to requirements =--
I/jxcore-log( 4767): 
,I/jxcore-log( 4767): ****TEST TOOK:  ms ****
I/jxcore-log( 4767): 
,I/jxcore-log( 4767): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4767): 
,D/AndroidRuntime( 5517): 
D/AndroidRuntime( 5517): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5517): CheckJNI is OFF
,D/dalvikvm( 5517): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5517): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 5517): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5517): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5517): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5517): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5517): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5517): failed to load memtrack module: -2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 5517): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  968): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  968): Killing 4767:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
I/MDM     (  968):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  968):   Force finishing activity ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  968): Moving to FINISHING: ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  968): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  968): moveHomeStack:
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7d640 stackId=0, 1 tasks}
,V/ActivityManager(  968): Moving to RESUMED: ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  968): resumeTopActivityLocked: Resumed ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7d640 stackId=0, 1 tasks}
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  968): resumeTopActivityLocked: Skip resume: some activity pausing.
,V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{44f771e8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7d640 stackId=0, 1 tasks}
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  968): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1492): [Launcher.java:4947:onStart()]onStart
,I/WindowState(  968): WIN DEATH: Window{43e0a6e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  968): Client connection lost with reason: 4
,W/PackageSettings(  968): Skipping PackageSetting{42d767e8 com.example.hello/10312} due to missing metadata
,I/[LGHome]EVENT( 1492): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1452): getIsInUseVoLTE : false
I/ActivityManager(  968): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7d640 stackId=0, 1 tasks}
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  968): resumeTopActivityLocked: Skip resume: some activity pausing.
,D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  968): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]LGActivityUtil( 1492): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,E/SlideAside( 3749): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/SlideAside( 3749): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
,D/AppUp4:Utils( 4018): [getPackageName] uri : package:com.test.thalitest
,W/System.err( 2666): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,D/AppUp4  ( 4018): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
,I/AppUp4  ( 4018):  isExcludedPackage  packagename = com.test.thalitest
,W/System.err( 2666): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2666): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2666): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
,W/System.err( 2666): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2666): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2666): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2666): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2666): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2666): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2666): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
,W/System.err( 2666): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2666): 	at dalvik.system.NativeStart.main(Native Method)
,D/AppUp4  ( 4018):  isExcludedPackage TRUE : com.test.thalitest
,I/ActivityManager(  968): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5535 uid=10090 gids={50090}
,W/GeofencerStateMachine( 1427): Ignoring removeGeofence because network location is disabled.
,I/[LGHome]EVENT( 1492): [Launcher.java:868:onResume()]onResume end
,I/[LGHome]EVENT( 1492): [Launcher.java:894:onPause()]onPause
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
W/ActivityManager(  968): getAssistContextExtras failed: no resumed activity
W/ActivityManager(  968): getAssistContextExtras failed: no resumed activity
V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/GlowPadView( 1141): changeTargets() succeeded. size: 20
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "sms"
,D/dalvikvm( 2680): GC_EXPLICIT freed 4100K, 28% free 17919K/24832K, paused 1ms+3ms, total 85ms
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
I/ActivityManager(  968): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5561 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
,I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1492): [Launcher.java:4955:onStop()]onStop
I/[LGHome]EVENT( 1492): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,D/HyLog   ( 5535): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5535): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5535): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5561): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5561): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5561): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  968):   Scheme: "sms"
I/LockScreenSettings( 5535): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/dalvikvm(  968): GC_EXPLICIT freed 2846K, 49% free 30048K/57880K, paused 2ms+18ms, total 193ms
D/dalvikvm(  968): WAIT_FOR_CONCURRENT_GC blocked 97ms
,D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1141): createShortcutInfo...
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1141): createShortcutInfo...
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1141): createShortcutInfo...
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
,D/[BNRAppListMgrReceiver]( 5561): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputMethodManagerService(  968): IME STATUS OFF
,W/Binder  ( 1303): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1303): java.lang.NullPointerException
W/Binder  ( 1303): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1303): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1303): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1303): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  968): Got RemoteException sending setActive(false) notification to pid 4767 uid 10304
,I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1141): createShortcutInfo...
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
I/ActivityManager(  968): Killing 4674:com.lge.email/u0a24 (adj 15): empty #17
,D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1141): createShortcutInfo...
,D/administrator(  968): Handling package changes for user 0
D/VoicemailCleanupService( 1757): Cleaning up data for package: com.test.thalitest
,W/BroadcastQueue(  968): Exception when sending broadcast to ComponentInfo{com.lge.email/com.lge.email.receiver.PackageChangeReceiver}
W/BroadcastQueue(  968): android.os.DeadObjectException
W/BroadcastQueue(  968): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  968): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:814)
W/BroadcastQueue(  968): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:239)
W/BroadcastQueue(  968): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:895)
W/BroadcastQueue(  968): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:14216)
W/BroadcastQueue(  968): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:387)
W/BroadcastQueue(  968): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2168)
W/BroadcastQueue(  968): 	at android.os.Binder.execTransact(Binder.java:407)
W/BroadcastQueue(  968): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  968): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5575 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/KeyguardModel( 1141): handleShortcutListChanged...
D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1141): createShortcutInfo...
,I/ActivityManager(  968): Process com.lge.email (pid 4674) has died and restarted (pid 5575).
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1141): createShortcutInfo...
,D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1141): createShortcutInfo...
,D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1141): createShortcutInfo...
,D/KeyguardModel( 1141): handleShortcutListChanged...
D/HyLog   ( 5575): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5575): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5575): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  968): Killing 4925:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
V/ActivityManager(  968): Moving to STOPPED: ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/ActivityManager(  968): Timeline: Activity_windows_visible id: ActivityRecord{4329bc90 u0 com.lge.launcher2/.Launcher t1} time:272292
,I/LGEmail ( 5575): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c7d640 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,D/BackupManagerService(  968): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/InteractionManagerConfigurator(  968): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  968): com.test.thalitest isn't inclued in dragdropPackageList
,D/LGEmail ( 5575): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
V/BackupManagerService(  968): removePackageParticipantsLocked: uid=10304 #1
,D/dalvikvm( 1492): GC_CONCURRENT freed 5273K, 9% free 60694K/66148K, paused 5ms+3ms, total 45ms
,D/dalvikvm( 1492): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm(  968): GC_EXPLICIT freed 682K, 49% free 29901K/57880K, paused 4ms+22ms, total 250ms
,W/BaseRuntimeLoader( 5575): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5575): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5575): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5575): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/dalvikvm( 1141): GC_CONCURRENT freed 8072K, 11% free 70321K/78580K, paused 5ms+8ms, total 52ms
,D/dalvikvm( 1141): WAIT_FOR_CONCURRENT_GC blocked 48ms
,E/[LGHome]NumberBadge( 1492): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageChangeReceiver( 5575): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,D/PackageIntentReceiver( 2592): Not supported Hotkey customization function 
,D/HideNavigationAppsReceiver( 2592): Receive package name : com.test.thalitest
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,D/HideNavigationAppsReceiver( 2592): Delete mPackageMame : com.test.thalitest
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/IcingCorporaProvider( 2680): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/AndroidRuntime( 5517): Shutting down VM
,D/dalvikvm( 5517): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
I/ActivityManager(  968): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5599 uid=10073 gids={50073, 3003, 1028, 1015}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/dalvikvm(  275): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+3ms, total 28ms
,D/HyLog   ( 5599): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5599): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5599): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 23ms
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+2ms, total 23ms
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/IcingCorporaProvider( 2680): UpdateCorporaTask done [took 92 ms] updated apps [took 92 ms] 
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1492): Timeline: Activity_idle id: android.os.BinderProxy@428a4f08 time:272631
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SQLiteDatabase( 5599): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5599): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5599): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5599): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5599): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5599): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5599): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5599): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5599): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 5599): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 5599): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 5599): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 5599): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5599): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5599): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5599): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5599): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5599): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5599): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5599): 	at aJh.a(Scopes.java:65)
E/SQLiteDatabase( 5599): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5599): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteDatabase( 5599): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteDatabase( 5599): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5599): 	at aGr.a(GellyInjector.java:117)
E/SQLiteDatabase( 5599): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5599): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5599): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteDatabase( 5599): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteDatabase( 5599): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 5599): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 5599): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5599): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5599): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 5599): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5599): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5599): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 5599): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 5599): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 5599): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5599): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5599): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5599): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 5599): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 5599): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5599): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5599): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5599): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 5599): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 5599): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 5599): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 5599): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 5599): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5599): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5599): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5599): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5599): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5599): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5599): 	at aJh.a(Scopes.java:65)
E/SQLiteOpenHelper( 5599): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5599): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteOpenHelper( 5599): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteOpenHelper( 5599): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5599): 	at aGr.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5599): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5599): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5599): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteOpenHelper( 5599): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteOpenHelper( 5599): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 5599): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 5599): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5599): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 5599): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 5599): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5599): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5599): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 5599): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 5599): 	at dalvik.system.NativeStart.main(Native Method)

```
