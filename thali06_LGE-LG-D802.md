#### Test 5497026186051be_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/Vision  ( 1854): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1854): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1854): No vision deps
I/PeopleContactsSync( 1854): CP2 sync disabled
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/dalvikvm( 1854): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1854): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1854): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1558): GC_EXPLICIT freed 1195K, 29% free 17825K/24832K, paused 2ms+2ms, total 24ms
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
W/GAV2    ( 4675): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  967): Killing 4026:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d3d2a0 u0 com.android.settings/.UsbSettings t2}
I/ConfigFetchService( 1854): fetch service done; releasing wakelock
I/ConfigFetchService( 1854): stopping self
D/dalvikvm( 1854): GC_CONCURRENT freed 1532K, 22% free 19437K/24832K, paused 5ms+4ms, total 36ms
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4729): 
D/AndroidRuntime( 4729): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4729): CheckJNI is OFF
D/dalvikvm( 4729): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4729): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4729): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4729): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4729): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4729): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4729): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4729): failed to load memtrack module: -2
D/AndroidRuntime( 4729): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4729
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (181 us)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{42d3d2a0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{43335870 stackId=1, 2 tasks}
I/ActivityManager(  967): startService SlideAside
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/UsbSettingsControl( 2628): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2628): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42d3d2a0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{42d3d2a0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
D/AndroidRuntime( 4729): Shutting down VM
D/dalvikvm( 4729): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 5ms
I/Icing   ( 1854): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4749 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3771): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3771): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/HyLog   ( 4749): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4749): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4749): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/SlideAside( 3771): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Icing   ( 1854): Loaded CLD2 Version V2.0 - 20141016
V/WebViewChromium( 4749): Binding Chromium to the background looper Looper (main, tid 1) {428ca3a0}
I/chromium( 4749): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4749): Initializing chromium process, renderers=0
I/Icing   ( 1854): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
W/chromium( 4749): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4749): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4749): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4749): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4749): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4749): Remote Branch: 
I/Adreno-EGL( 4749): Local Patches: 
I/Adreno-EGL( 4749): Reconstruct Branch: 
I/dalvikvm( 4749): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4749): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4749): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4749): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4749): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4749): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4749): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4749): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4749): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4749): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4749): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4749): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4749): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4749): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4749): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4749): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4749): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4749): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4749): CordovaWebView is running on device made by: LGE
,D/dalvikvm( 4749): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4749): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4749): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4749): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4749): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4749): Enabling debug mode 0
,W/AwContents( 4749): nativeOnDraw failed; clearing to background color.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/InputMethodManagerService(  967): IME STATUS OFF
,W/AwContents( 4749): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +411ms
,I/ActivityManager( 4749): Timeline: Activity_idle id: android.os.BinderProxy@428cbc60 time:106917
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/JsMessageQueue( 4749): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4749): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428d1988
,D/dalvikvm( 4749): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428d1988
,D/jxcore_app_log( 4749): JniHelper::setJavaVM(0x41796838), pthread_self() = 1639646416
,D/JX-Cordova( 4749): jxcore cordova android initializing
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3} time:107284
,D/UsbSettings( 2628): [AUTORUN] onStop()
D/ActivityManager(  967): no-history finish of ActivityRecord{42d3d2a0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{429c8458 ActivityRecord{42d3d2a0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{42d3d2a0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{42d3d2a0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{42d3d2a0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4749): GC_CONCURRENT freed 2749K, 12% free 21883K/24832K, paused 2ms+1ms, total 45ms
D/dalvikvm( 4749): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/dalvikvm( 4749): GC_FOR_ALLOC freed 130K, 12% free 21862K/24832K, paused 23ms, total 24ms
D/dalvikvm( 4749): GC_FOR_ALLOC freed 125K, 12% free 21882K/24832K, paused 21ms, total 21ms
I/dalvikvm-heap( 4749): Grow heap (frag case) to 23.634MB for 95956-byte allocation
D/dalvikvm( 4749): GC_FOR_ALLOC freed 177K, 13% free 21917K/24928K, paused 21ms, total 21ms
I/dalvikvm-heap( 4749): Grow heap (frag case) to 23.714MB for 143930-byte allocation
D/dalvikvm( 4749): GC_FOR_ALLOC freed 251K, 13% free 21964K/25072K, paused 20ms, total 21ms
I/dalvikvm-heap( 4749): Grow heap (frag case) to 23.829MB for 215890-byte allocation
D/dalvikvm( 4749): GC_FOR_ALLOC freed 366K, 13% free 22038K/25284K, paused 21ms, total 21ms
I/dalvikvm-heap( 4749): Grow heap (frag case) to 24.004MB for 323830-byte allocation
D/dalvikvm( 4749): GC_FOR_ALLOC freed 564K, 14% free 22159K/25604K, paused 21ms, total 22ms
I/dalvikvm-heap( 4749): Grow heap (frag case) to 24.277MB for 485740-byte allocation
D/dalvikvm( 4749): GC_FOR_ALLOC freed 860K, 15% free 22335K/26080K, paused 22ms, total 23ms
D/dalvikvm( 4749): GC_FOR_ALLOC freed 1278K, 14% free 22590K/26080K, paused 23ms, total 23ms
I/dalvikvm-heap( 4749): Grow heap (frag case) to 25.276MB for 1092904-byte allocation
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4749): GC_CONCURRENT freed 1781K, 16% free 22977K/27148K, paused 1ms+2ms, total 26ms
D/dalvikvm( 4749): GC_FOR_ALLOC freed 266K, 16% free 22904K/27148K, paused 21ms, total 22ms
I/dalvikvm-heap( 4749): Grow heap (frag case) to 26.104MB for 1639352-byte allocation
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 4749): GC_CONCURRENT freed 1557K, 19% free 23480K/28752K, paused 2ms+1ms, total 33ms
,D/dalvikvm( 4749): GC_FOR_ALLOC freed 1409K, 19% free 23555K/28752K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4749): Grow heap (frag case) to 27.521MB for 2459024-byte allocation
,D/dalvikvm( 4749): GC_CONCURRENT freed 1898K, 22% free 24358K/31156K, paused 2ms+3ms, total 47ms
,D/dalvikvm( 4749): GC_CONCURRENT freed 2478K, 22% free 24512K/31156K, paused 2ms+8ms, total 55ms
,D/dalvikvm( 4749): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2045): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2045): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/dalvikvm( 4749): GC_FOR_ALLOC freed 421K, 22% free 24364K/31156K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4749): Grow heap (frag case) to 29.485MB for 3688532-byte allocation
,D/dalvikvm( 4749): GC_CONCURRENT freed 2708K, 27% free 25590K/34760K, paused 2ms+3ms, total 41ms
,D/dalvikvm( 4749): GC_FOR_ALLOC freed 734K, 27% free 25480K/34760K, paused 22ms, total 22ms
,W/jxcore-log( 4749): Initializing JXcore engine
,W/jxcore-log( 4749): JXcore engine is ready
,D/dalvikvm( 4749): GC_CONCURRENT freed 359K, 20% free 28111K/34760K, paused 1ms+2ms, total 38ms
,D/dalvikvm( 4749): WAIT_FOR_CONCURRENT_GC blocked 36ms
,W/jxcore-log( 4749): Starting JXcore engine
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/jxcore-log( 4749): Platform android
W/jxcore-log( 4749): 
,W/jxcore-log( 4749): Process ARCH arm
W/jxcore-log( 4749): 
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/jxcore-log( 4749): JXcore Cordova bridge is ready!
I/jxcore-log( 4749): 
,W/jxcore-log( 4749): JXcore engine is started
,I/chromium( 4749): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4749): Toggling radios to true
I/jxcore-log( 4749): 
,D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44e6c878:true
,D/BluetoothAdapter( 4749): enable(): BT is already enabled..!
D/WifiStateMachine(  967): handleMessage: E msg.what=131145
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DISCONNECT
I/jxcore-log( 4749): Radios toggled
I/jxcore-log( 4749): 
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2045): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2045): wlan0: Cancelling scan request
D/wpa_supplicant( 2045): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2045): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2045): TDLS: Tear down peers
D/wpa_supplicant( 2045): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  967): New client listening to asynchronous messages
D/WifiService(  967): setWifiEnabled: true pid=4749, uid=10304
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  967): disconnect pid=4749, uid=10304
,D/WifiService(  967): reconnect pid=4749, uid=10304
I/jxcore-log( 4749): My device name is: LGE-LG-D802
I/jxcore-log( 4749): 
,D/wpa_supplicant( 2045): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2045): wlan0: Deauthentication notification
,D/wpa_supplicant( 2045): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2045): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2045): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2045): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2045): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2045): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb75f6d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2045):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2045): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2045): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2045): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2045): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2045): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2045): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2045): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2045): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2045): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2045): nl80211: if_removed already cleared - ignore event
D/wpa_supplica,nt( 2045): nl80211: Event message available
D/wpa_supplicant( 2045): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2045): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  967):    returned true
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  967): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
W/Settings(  967): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131146
D/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiNative-wlan0(  967): doBoolean: RECONNECT
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2045): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2045): Fast associate: Old scan results
D/wpa_supplicant( 2045): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2045): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2045): wlan0: nl80211: scan request
D/wpa_supplicant( 2045): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147460
D/WifiStateMachine(  967): processMsg: DisconnectingState
D/wpa_supplicant( 2045): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2045): nl80211: Event message available
D/wpa_supplicant( 2045): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2045): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection lost
D/WifiStateMachine(  967): Stopping DHCP and clearing IP
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2045): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2045): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2045): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2045): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2045): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
,D/DhcpStateMachine(  967): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/WifiStateMachine(  967): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
,E/Parcel  (  425): Reading a NULL string not supported here.
D/QCNEA   (  425): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  425): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  425): |CAC| updateNetCfgInfo
V/QCNEA   (  425): |CAC| *********************************************
V/QCNEA   (  425): |CAC|                   Netconfig               
V/QCNEA   (  425): |CAC| *********************************************
V/QCNEA   (  425): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  425): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  425): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  425): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  425): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  425): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  425): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  425): |CAC| *********************************************
D/QCNEA   (  425): |CAC| Received bssid= 
D/QCNEA   (  425): |CAC| net type = 3
V/QCNEA   (  425): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  425): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  425): |CAC| 	ssid           =NG700
V/QCNEA   (  425): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  425): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  425): |CAC| *********************************************
D/QCNEA   (  425): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  425): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  425): |CAC| dispatchNetCfg: updating:0xb87a78dc
,D/QCNEA   (  425): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
D/WifiHS20(  967): hidePasspointNotification off =false
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  967): Attempting to switch to mobile
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4812 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  271): RouteController
,V/        (  271): RouteController
,D/HyLog   ( 4812): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  271): RouteController
D/HyLog   ( 4812): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4812): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/PCSuite ( 4812): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  271): RouteController
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
,D/NetUtils(  967): android_net_utils_resetConnections in env=0x61f726a8 clazz=0x6d000001 iface=wlan0 mask=0x3
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/PCSuite ( 4812): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4812): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/NativeCrypto( 1558): Read error: ssl=0x63a4d638: I/O error during system call, Connection timed out
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/NativeCrypto( 1558): SSL shutdown failed: ssl=0x63a4d638: I/O error during system call, Broken pipe
,I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4846 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  967): Killing 4235:com.google.android.talk/u0a77 (adj 15): empty #17
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
,W/ActivityManager(  967): Failed to clear dns cache for: com.google.android.talk
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/HyLog   ( 4846): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4846): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4846): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4846): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4846): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4846): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4846): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4846): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4846): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4846): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4846): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4846): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  967): Killing 2176:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  967): StoppedState
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Killing 3934:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,I/GAV2    ( 4675): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1558): onDestroy
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449966 Y: -0.402313 Z: 9.794434 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449966 .y:-0.402313 .z:9.794434
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.459091 Y: -0.413254 Z: 9.780823 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459091 .y:-0.413254 .z:9.780823
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4081): onReceive
,D/AppUp4:CustFacade( 4081): Context : android.app.ReceiverRestrictedContext@428e9520
D/AppUp4:CustFacade( 4081): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4081): isOpenOperator : true
D/AppUp4:CustFacade( 4081): isPhone : true
,I/LicenseContentProvider( 3801): start selecting data
,D/SIMObserver( 3801): simInfo1
,I/AppUp4:EulaManager( 4081): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4081): begin check event
,I/AppUp4:CustModeStarterReceiver( 4081): Event For GoodConnectivity
,I/ActivityManager(  967): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4898 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4898): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4898): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4898): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2045): nl80211: Event message available
D/wpa_supplicant( 2045): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2045): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2045): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2045): nl80211: Received scan results (13 BSSes)
D/wpa_supplicant( 2045): nl80211: Survey data missing
D/wpa_supplicant( 2045): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2045): wlan0: BSS: Add new id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Add new id 7 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Add new id 8 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear'
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 c2:ff:d4:d3:aa:48]
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Add new id 9 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series'
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Add new id 10 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Add new id 11 BSSID 64:7c:34:b0:03:6e SSID 'UPC4688432'
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 64:7c:34:38:27:cc]
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Add new id 12 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): BSS: last_scan_res_used=13/32 last_scan_full=0
D/wpa_supplicant( 2045): wlan0: New scan results available
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 00:26:f2:18:08:c8]
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2045): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2045): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2045): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2045): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 dc:4a:3e:0f:c2:f1]
D/wpa_supplicant( 2045): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2045): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2045): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2045): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2045): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2045): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 2045): WPS: AP[0] c0:ff:d4:d,3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2045): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2045): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2045): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2045): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2045): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2045): WPS: AP[6] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 44:e9:dd:10:c0:ab]
D/wpa_supplicant( 2045): WPS: AP[7] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2045): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2045): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps
D/wpa_supplicant( 2045): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2045): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2045): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2045): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2045): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2045): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 64:7c:34:b0:03:6e]
D/wpa_supplicant( 2045): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2045): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2045): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2045): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2045): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb75f85a8  current_ssid=0x0
D/wpa_supplicant( 2045): scard is not null..
D/wpa_supplicant( 2045): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2045): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2045): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2045): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2045): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2045): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2045): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 44:e9:dd:10:c0:ad]
D/wpa_supplicant( 2045): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2045): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2045): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2045): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2045): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2045): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2045): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2045): wlan0: Cancelling scan request
D/wpa_supplicant( 2045): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2045): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2045): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2045): RSN: PMKSA cache search - network_ctx=0xb75f85a8 try_opportunistic=0
D/wpa_supplicant( 2045): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2045): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2045): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2045): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2045): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2045): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2045): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2045): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2045): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2045): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2045): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 2045): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2045): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2045): netlink: Operstate: linkmode=-1, operstate=5
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2045): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
D/wpa_supplicant( 2045): nl80211: Unsubscribe mgmt frames handle 0xb75f7590 (mode change)
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/wpa_supplicant( 2045): nl80211: Subscribe to mgmt frames with non-AP handle 0xb75f7590
D/wpa_supplicant( 2045): nl80211: Register frame type=0xd0 nl_handle=0xb75f7590
D/wpa_supplicant( 2045): nl80211: Register frame match - hexdump(len=2): 04 0a
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/wpa_supplicant( 2045): nl80211: Register frame type=0xd0 nl_handle=0xb75f7590
D/wpa_supplicant( 2045): nl80211: Register frame match - hexdump(len=2): 04 0b
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/wpa_supplicant( 2045): nl80211: Register frame type=0xd0 nl_handle=0xb75f7590
D/wpa_supplicant( 2045): nl80211: Register frame match - hexdump(len=2): 04 0c
D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2045): nl80211: Register frame type=0xd0 nl_handle=0xb75f7590
D/wpa_supplicant( 2045): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2045): nl80211: Register frame type=0xd0 nl_handle=0xb75f7590
D/wpa_supplicant( 2045): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2045): nl80211: Register frame type=0xd0 nl_handle=0xb75f7590
D/wpa_supplicant( 2045): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2045): nl80211: Register frame type=0xd0 nl_handle=0xb75f7590
D/wpa_supplicant( 2045): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2045): nl80211: Register frame type=0xd0 nl_handle=0xb75f7590
D/wpa_supplicant( 2045): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2045): nl80211: Register frame type=0xd0 nl_handle=0xb75f7590
D/wpa_supplicant( 2045): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2045): nl80211: Register frame type=0xd0 nl_handle=0xb75f7590
D/wpa_supplicant( 2045): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2045): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2045):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045):   * freq=2412
D/wpa_supplicant( 2045):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2045):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2045):   * Auth Type 0
D/wpa_supplicant( 2045):   * WPA Versions 0x2
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2045): nl80211: Connect request send successfully
D/wpa_supplicant( 2045): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2045): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2045): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2045): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2045): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2045): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2045): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2045): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2045): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 2045): nl80211: Event message available
D/wpa_supplicant( 2045): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2045): nl80211: Connect event
D/wpa_supplicant( 2045): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2045): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2045): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2045): wlan0: Association info event
D/wpa_supplicant( 2045): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2045): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2045): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2045): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2045): wlan0: freq=2412 MHz
D/wpa_supplicant( 2045): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2045): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2045): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2045): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2045): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2045): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): scard is not null..
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2045): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2045): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2045): TDLS: Remove peers on association
D/wpa_supplicant( 2045): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2045): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2045): EAPOL: enable timer tick
D/wpa_supplicant( 2045): EAPOL: SUPP_BE entering state IDLE
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2045): wlan0: Cancelling scan request
D/wpa_supplicant( 2045): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2045): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2045): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2045): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2045): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2045): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2045): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2045): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2045): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2045): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2045): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 13 7f 4a 6a 9f 41 54 8b dd 00 f4 a9 76 bc 81 ...
D/wpa_supplicant( 2045): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2045): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2045): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2045): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2045): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2045):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2045):   key_nonce - hexdump(len=32): 13 7f 4a 6a 9f 41 54 8b dd 00 f4 a9 76 bc 81 7c 95 02 80 d2 1a 8e 3d 74 4b 65 a8 ad eb e8 75 3c
D/wpa_supplicant( 2045):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2045):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2045):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2045):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2045): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 13 7f 4a 6a 9f 41 54 8b dd 00 f4 a9 76 bc 81 ...
D/wpa_supplicant( 2045): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2045): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2045): Get randomness: len=32 entropy=11
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 2045): WPA: Renewed SNonce - hexdump(len=32): da 45 83 b3 79 19 af 83 b9 d3 6d 0e d8 8f 80 4e 22 1a a1 e0 c2 8c ec d4 de 01 02 b8 da 00 66 d0
D/wpa_supplicant( 2045): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): WPA: Nonce1 - hexdump(len=32): da 45 83 b3 79 19 af 83 b9 d3 6d 0e d8 8f 80 4e 22 1a a1 e0 c2 8c ec d4 de 01 02 b8 da 00 66 d0
D/wpa_supplicant( 2045): WPA: Nonce2 - hexdump(len=32): 13 7f 4a 6a 9f 41 54 8b dd 00 f4 a9 76 bc 81 7c 95 02 80 d2 1a 8e 3d 74 4b 65 a8 ad eb e8 75 3c
D/wpa_supplicant( 2045): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2045): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2045): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2045): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2045): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2045): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2045): WPA: Derived Key MIC - hexdump(len=16): b9 d1 c4 b1 ec a2 b5 8e 46 d1 1f 98 ea 45 52 3f
D/wpa_supplicant( 2045): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 da 45 83 b3 79 19 af 83 b9 d3 6d 0e d8 8f 80 ...
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2045): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 13 7f 4a 6a 9f 41 54 8b dd 00 f4 a9 76 bc 81 ...
D/wpa_supplicant( 2045): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2045): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2045): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2045): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2045):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2045):   key_nonce - hexdump(len=32): 13 7f 4a 6a 9f 41 54 8b dd 00 f4 a9 76 bc 81 7c 95 02 80 d2 1a 8e 3d 74 4b 65 a8 ad eb e8 75 3c
D/wpa_supplicant( 2045):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2045):   key_rsc - hexdump(len=8): 84 cd 00 00 00 00 00 00
D/wpa_supplicant( 2045):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2045):   key_mic - hexdump(len=16): bd 64 25 43 53 e8 7b 36 6c 2b 2e fd 4c aa 48 14
D/wpa_supplicant( 2045): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 13 7f 4a 6a 9f 41 54 8b dd 00 f4 a9 76 bc 81 ...
D/wpa_supplicant( 2045): RSN: encrypted key data - hexdump(len=56): 95 48 5c 11 58 83 fc 05 10 5b 7e 1e c1 f4 d0 ba 2f c8 01 bf dc 37 2c e2 18 8f b4 9f d6 aa 96 ed ...
D/wpa_supplicant( 2045): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2045): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2045): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2045): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 19 b2 ...
D/wpa_supplicant( 2045): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2045): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2045): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2045): WPA: KCK - hexdump(len=16): [REMOVED]
V/DownloadManager( 4898): DownloadService onCreate
D/wpa_supplicant( 2045): WPA: Derived Key MIC - hexdump(len=16): 24 0b ac f4 a7 09 a2 51 90 97 05 c9 cb 6d c0 e4
D/wpa_supplicant( 2045): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2045): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb75f7c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2045):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2045): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2045): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2045): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2045): WPA: RSC - hexdump(len=6): 84 cd 00 00 00 00
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f5b03a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2045):    broadcast key
I/DownloadManager( 4898): in removeSpuriousFiles
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/EAS     ( 4658): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4658): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
I/wpa_supplicant( 2045): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2045): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2045): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2045): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2045): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2045): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2045): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2045): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2045): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2045): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2045): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2045): EAPOL authentication completed successfully
D/wpa_supplicant( 2045): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2045): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2045): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/eas_req ( 4658): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection established
D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2045): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
V/DownloadManager( 4898): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
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
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
I/WifiServiceExtension(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@4290ed28 on behalf of 4898
D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/LgeMiscReceiver( 4408): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4408): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4408): networkInfo.isConnected() = false
W/linker  ( 4658): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/HtmlEditor( 4658): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4658): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4658): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
I/dalvikvm( 4658): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
I/DownloadManager( 4898): in trimDatabase
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
,V/DownloadManager( 4898): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  967): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-21ms what=147462 obj=android.net.wifi.StateChangeResult@43da7e88 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-18ms what=147462 obj=android.net.wifi.StateChangeResult@4448e178 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/HtmlEditor( 4658): register_HtmlEditor, Success
D/HtmlEditor( 4658): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/HtmlEditor( 4658): register_HtmlEditorTimer, Success
D/HtmlEditor( 4658): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4658): register_HtmlEditorDownloader, Success
D/WifiStateMachine(  967): ObtainingIpState{ when=-18ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/HtmlEditor( 4658): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/WifiStateMachine(  967): handleMessage: X
D/HtmlEditor( 4658): register_HtmlEditorFont, Success
D/HtmlEditor( 4658): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4658): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4658): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-3ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
,D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2045): wlan0: Control interface command 'SIGNAL_POLL'
D/HtmlEditor( 4658): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4658): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4658): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4658): JNI_OnLoad Success
,D/wpa_supplicant( 2045): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196612
D/WifiStateMachine(  967): processMsg: ObtainingIpState
V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@42914108 on behalf of 4898
D/WifiStateMachine(  967): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2045): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4928 uid=10052 gids={50052, 3003}
I/HubEmail( 4658): JNI_OnLoad()
I/HubEmail( 4658): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4658): registerNatives()
I/HubEmail( 4658): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4658): registerNativeMethods()
I/HubEmail( 4658): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
V/DownloadManager( 4898): DownloadService onStartCommand
,V/DownloadManager( 4898): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/WifiController(  967): battery changed pluggedType: 2
V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@42916538 on behalf of 4898
W/Settings( 4658): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4898): DownloadService onDestroy
D/HyLog   ( 4928): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4928): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4928): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): Killing 4446:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4928): [loadRssi] File not exist 
V/LGRssiData( 4928): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4928): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4928): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4928): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4928): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4928): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4928): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/MobileConnectivityChangeReceiver( 4928): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/TelephonyAutoProfiling( 4928): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4928): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 4928): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4928): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4928): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4942 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4583:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4942): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4942): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4942): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2045): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2045): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2045): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2045): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2045): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2045): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2045): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2045): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
,D/CommandListener(  271): Setting iface cfg
,D/WifiStateMachine(  967): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/CommandListener(  271): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42e93980 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42e93980 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2045): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2045): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2045): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2045): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2045): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): DHCP successful
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  967): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState enter
,D/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  967): handleMessage: X
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  967): send additional Connectivity Action
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
,E/Parcel  (  425): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  967): handleMessage: X
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4957 uid=10066 gids={50066, 4002, 3003, 1028}
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  967): handleMessage: E msg.what=131092
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
I/ActivityManager(  967): Killing 4616:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
,D/HyLog   ( 4957): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4957): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4957): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
,D/LGDMClient( 2882): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2882): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  967): Killing 4644:com.lge.bnr/1000 (adj 15): empty #17
V/        (  271): RouteController
,I/LGDMClient( 2882): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2882): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2882): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2882): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2882): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4973 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,D/HyLog   ( 4973): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4973): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4973): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
,D/LGDMSGCM( 4973): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4973): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/        (  271): RouteController
V/        (  271): RouteController
,V/        (  271): RouteController
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,D/QCNEA   (  425): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  425): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  425): |CAC| updateNetCfgInfo
V/QCNEA   (  425): |CAC| *********************************************
V/QCNEA   (  425): |CAC|                   Netconfig               
V/QCNEA   (  425): |CAC| *********************************************
V/QCNEA   (  425): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  425): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  425): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  425): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  425): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  425): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  425): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  425): |CAC| *********************************************
D/QCNEA   (  425): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  425): |CAC| net type = 1
V/QCNEA   (  425): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  425): |CAC| Received ssid= NG700
V/QCNEA   (  425): |CAC| 	ssid           =NG700
V/QCNEA   (  425): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  425): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  425): |CAC| *********************************************
D/QCNEA   (  425): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  425): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  425): |CAC| dispatchNetCfg: updating:0xb87a78dc
,D/QCNEA   (  425): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4998 uid=10101 gids={50101, 1028, 1015, 3003}
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/dalvikvm(  275): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/ActivityManager(  967): Killing 4285:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  967): GC_EXPLICIT freed 23483K, 49% free 29762K/57868K, paused 2ms+7ms, total 133ms
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 4998): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4998): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4998): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1854): Checking schedule, now: 1452511792928 next: 1452511740837
,I/CheckinService( 1854): active receiver: enabled
,I/CheckinService( 1854): Preparing to send checkin request
,I/EventLogService( 1854): Accumulating logs since 1452511708166
,I/NFS     ( 4998): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4998): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4998): intf.getDisplayName() = lo
I/Wireless_Storage( 4998): intf.getDisplayName() = sit0
I/Wireless_Storage( 4998): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4998): intf.getDisplayName() = teql0
,I/Wireless_Storage( 4998): intf.getDisplayName() = wlan0
D/NFS     ( 4998): interface name:wlan0 name:wlan0
D/NFS     ( 4998): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4998): interface name:wlan0 name:wlan0
D/NFS     ( 4998): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4998): CONNECT : WIFI_CONNECT
,I/CheckinRequestBuilder( 1854): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5019 uid=10104 gids={50104, 3003, 1028, 1015}
,E/ActivityThread( 1854): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 5019): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5019): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5019): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 5019): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1854): awaiting user notification for token
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x4335c7f0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5037 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5037): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5037): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5037): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/WebViewChromium( 5019): Binding Chromium to the main looper Looper (main, tid 1) {428c8268}
W/dalvikvm( 5037): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5037): VFY: replacing opcode 0x60 at 0x000b
,I/chromium( 5019): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5019): Initializing chromium process, renderers=0
D/dalvikvm( 5037): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5037): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5037): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5037): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5037): install
,I/MultiDex( 5037): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5037): loading existing secondary dex files
,I/MultiDex( 5037): load found 3 secondary dex files
,I/MultiDex( 5037): install done
,W/chromium( 5019): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5019): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5019): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5019): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5019): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5019): Remote Branch: 
I/Adreno-EGL( 5019): Local Patches: 
I/Adreno-EGL( 5019): Reconstruct Branch: 
D/dalvikvm( 5037): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5037): VFY: unable to resolve instance field 61
,D/dalvikvm( 5037): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5037): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5037): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5037): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5037): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5037): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5037): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5037): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5037): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5037): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428d12d0
D/dalvikvm( 5037): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428d12d0
,D/dalvikvm( 5037): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428d12d0, skipping init
,D/dalvikvm( 5037): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428d12d0
D/dalvikvm( 5037): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428d12d0
,V/JNIHelp ( 5037): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 5019): Starting up...
,I/ActivityManager(  967): Killing 4300:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4846): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4846): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/dalvikvm( 5037): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428d12d0
,D/dalvikvm( 5037): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428d12d0
D/dalvikvm( 5037): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428d12d0
,D/dalvikvm( 5037): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428d12d0
,D/QRemote ( 4846): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4846): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4846): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4846): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4812): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4812): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4846): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4846): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4846): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4846): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 5037): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1558): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1558): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1558): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1723): callingUid 10006, callindPid: 1723
,E/MDM     ( 1424): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/dalvikvm( 5037): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5037): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5037): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5037): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5037): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5037): VFY: replacing opcode 0x6e at 0x0201
,D/LocationInitializer( 1854): Restart initialization of location
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
,D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2050000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2050000
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
,D/WVCdm   (  277): PrepareKeyRequest: nonce=3656862528
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2045): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2045): EAPOL: disable timer tick
,D/dalvikvm( 5037): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ae07e8
D/dalvikvm( 5037): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ae07e8
,D/dalvikvm( 5037): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ae07e8, skipping init
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings( 5037): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 5037): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 5072): DexOpt: load 4ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 5037): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5037): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 66ms
,I/Adreno-EGL( 5037): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5037): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5037): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5037): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5037): Remote Branch: 
I/Adreno-EGL( 5037): Local Patches: 
I/Adreno-EGL( 5037): Reconstruct Branch: 
,I/Adreno-EGL( 5037): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5037): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5037): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5037): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5037): Remote Branch: 
I/Adreno-EGL( 5037): Local Patches: 
I/Adreno-EGL( 5037): Reconstruct Branch: 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  277): PrepareKeyRequest: nonce=2869247131
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 5037): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5037): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5037): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5037): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5037): Remote Branch: 
I/Adreno-EGL( 5037): Local Patches: 
I/Adreno-EGL( 5037): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1854): Classify the device as Phone.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  967): RunningState
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1854): Sending checkin request (11586 bytes)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/GCM     ( 1558): Connected
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1558): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CheckinRequestBuilder( 1854): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1854): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43cddfb8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/CheckinRequestBuilder( 1854): awaiting user notification for token
,I/CheckinRequestBuilder( 1854): Classify the device as Phone.
,I/CheckinTask( 1854): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1854): Checking schedule, now: 1452511794977 next: 1453089190974
,I/CheckinService( 1854): active receiver: disabled
,D/GCM     ( 1558): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2045): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2045): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  425): Reading a NULL string not supported here.
,E/Parcel  (  425): Reading a NULL string not supported here.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4081): onReceive
,D/AppUp4:CustFacade( 4081): Context : android.app.ReceiverRestrictedContext@428e9520
D/AppUp4:CustFacade( 4081): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4081): isOpenOperator : true
,D/AppUp4:CustFacade( 4081): isPhone : true
,I/LicenseContentProvider( 3801): start selecting data
,D/SIMObserver( 3801): simInfo1
,I/AppUp4:EulaManager( 4081): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4081): begin check event
I/AppUp4:CustModeStarterReceiver( 4081): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4081): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4081): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4081): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4081): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4081): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4658): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4898): DownloadService onCreate
,D/EAS     ( 4658): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4658): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/Settings( 4658): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4898): in removeSpuriousFiles
,V/DownloadManager( 4898): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@4291c3d0 on behalf of 4898
,I/DownloadManager( 4898): in trimDatabase
V/DownloadManager( 4898): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@4291d4a0 on behalf of 4898
,V/DownloadManager( 4898): DownloadService onStartCommand
,V/DownloadManager( 4898): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@4291ff38 on behalf of 4898
,I/LgeMiscReceiver( 4408): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4408): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4408): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4928): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4928): onReceive CONNECTIVITY_CHANGE networkType=1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2882): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4898): DownloadService onDestroy
,D/LGDMSGCM( 4973): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2882): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2882): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 4998): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4998): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4973): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2882): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2882): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2882): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2882): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4081): onReceive
,D/AppUp4:CustFacade( 4081): Context : android.app.ReceiverRestrictedContext@428e9520
D/AppUp4:CustFacade( 4081): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4081): isOpenOperator : true
,D/AppUp4:CustFacade( 4081): isPhone : true
,I/LicenseContentProvider( 3801): start selecting data
,D/SIMObserver( 3801): simInfo1
,I/AppUp4:EulaManager( 4081): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4081): begin check event
,I/AppUp4:CustModeStarterReceiver( 4081): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4898): DownloadService onCreate
,D/EAS     ( 4658): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4658): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4898): in removeSpuriousFiles
,V/DownloadManager( 4898): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@42924100 on behalf of 4898
,I/LgeMiscReceiver( 4408): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4408): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4408): networkInfo.isConnected() = true
,D/PhoneState( 4408): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4928): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4928): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4658): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4898): in trimDatabase
,V/DownloadManager( 4898): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/LGDMClient( 2882): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@42925af8 on behalf of 4898
,V/DownloadManager( 4898): DownloadService onStartCommand
,V/DownloadManager( 4898): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMSGCM( 4973): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2882): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2882): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4973): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4998): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4998): CONNECT : WIFI_CONNECT
V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@42927ca8 on behalf of 4898
E/LGDMClient( 2882): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2882): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2882): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2882): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4898): DownloadService onDestroy
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/jxcore-log( 4749): Test app app.js loaded
I/jxcore-log( 4749): 
,I/Choreographer( 4749): Skipped 456 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4749): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4749): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4749): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  967): battery changed pluggedType: 2
D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4081): onReceive
,D/AppUp4:CustFacade( 4081): Context : android.app.ReceiverRestrictedContext@428e9520
D/AppUp4:CustFacade( 4081): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4081): isOpenOperator : true
,D/AppUp4:CustFacade( 4081): isPhone : true
,I/LicenseContentProvider( 3801): start selecting data
,D/SIMObserver( 3801): simInfo1
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/AppUp4:EulaManager( 4081): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4081): begin check event
,I/AppUp4:CustModeStarterReceiver( 4081): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4898): DownloadService onCreate
,I/DownloadManager( 4898): in removeSpuriousFiles
,D/EAS     ( 4658): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4658): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4898): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@4292cb90 on behalf of 4898
,V/DownloadManager( 4898): DownloadService onStartCommand
I/DownloadManager( 4898): in trimDatabase
,V/DownloadManager( 4898): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4898): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@4292eb80 on behalf of 4898
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/dalvikvm(  967): GC_EXPLICIT freed 2297K, 49% free 29667K/57868K, paused 2ms+6ms, total 84ms
,V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@4292f530 on behalf of 4898
,I/LgeMiscReceiver( 4408): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4408): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4408): networkInfo.isConnected() = true
D/PhoneState( 4408): setPdpRejectCasuse : false
,W/Settings( 4658): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4928): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/DownloadManager( 4898): DownloadService onDestroy
,D/MobileConnectivityChangeReceiver( 4928): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2882): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4973): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2882): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2882): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 4998): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4998): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2882): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2882): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,W/ContextImpl( 4973): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2882): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2882): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GAV2    ( 5019): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Killing 4318:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  967): Killing 4675:com.google.android.apps.docs/u0a73 (adj 15): empty #18
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2045): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2045): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/WifiController(  967): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452511800037, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452511800049, nextTick: 59984, mDrawingTime: 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5232 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5232): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5232): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5232): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5232): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 5232): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5232): VFY: replacing opcode 0x6e at 0x000b
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5232): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5232): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5232): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5232): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5232): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5232): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5232): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5232): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5232): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,W/Settings( 5232): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5232): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/dalvikvm( 5232): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5232): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5232): VFY: replacing opcode 0x6e at 0x011e
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/dalvikvm( 5232): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5232): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5232): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5232): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5232): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5232): VFY: replacing opcode 0x6e at 0x029a
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/DownloadManager( 4898): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4898): created cursor android.database.sqlite.SQLiteCursor@42934d68 on behalf of 5232
,I/dalvikvm( 5232): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 5232): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5232): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5232): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 5232): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5232): VFY: replacing opcode 0x6e at 0x0049
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5232): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5232): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5232): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5232): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm( 5232): Total arena pages for JIT: 11
,I/dalvikvm( 5232): Total arena pages for JIT: 12
I/dalvikvm( 5232): Total arena pages for JIT: 13
,I/dalvikvm( 5232): Total arena pages for JIT: 14
,D/Finsky  ( 5232): [466] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5232): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  967): Killing 4812:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  291): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2045): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2045): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/Finsky  ( 5232): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5232): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5232): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5232): VFY: replacing opcode 0x62 at 0x0037
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5232): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1558): GC_EXPLICIT freed 1128K, 29% free 17828K/24832K, paused 2ms+5ms, total 35ms
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5232): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5232): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5232): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5232): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5232): [1] DailyHygiene.reschedule: Scheduling new run in 881 minutes (failures=5)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5311 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,D/administrator(  967): Handling package changes for user 0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,E/SlideAside( 3771): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 3771): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
D/HyLog   ( 5311): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5311): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5311): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
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
,I/Babel   ( 5311): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5311): MmsConfig.loadMmsSettings
I/Babel   ( 5311): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5311): MmsConfig.loadFromDatabase
I/MediaCodecList( 5311): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 5311): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5311): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5311): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5311): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5311): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5311): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5311): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5311): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5311): MmsConfig.loadFromResources
E/Babel   ( 5311): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5311): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5311): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4081): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4081): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4081): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/LGRssiData( 5311): [loadRssi] File not exist 
V/LGRssiData( 5311): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5311): [loadFeatureFromXml] *** start feature loading from xml
,I/AppUp4:CustModeStarterReceiver( 4081): onReceive
D/AppUp4:CustFacade( 4081): Context : android.app.ReceiverRestrictedContext@428e9520
D/AppUp4:CustFacade( 4081): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4081): isOpenOperator : true
D/AppUp4:CustFacade( 4081): isPhone : true
V/TelephonyAutoProfiling( 5311): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5311): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5311): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/LicenseContentProvider( 3801): start selecting data
,D/SIMObserver( 3801): simInfo1
,I/AppUp4:EulaManager( 4081): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4081): begin check event
D/AppUp4:Utils( 4081): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4081): Event For Nothing, skip.
,I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5357 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
E/BatteryObserver( 1154): usb Uevent not necessary.
,V/GmsNetworkLocationProvi( 1424): DISABLE
D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HyLog   ( 5357): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5357): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5357): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/SystemConfig( 5357): BUILD Country: EU
,I/SystemConfig( 5357): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 4846:com.lge.qremote/u0a96 (adj 15): empty #17
,I/SystemConfig( 5357): systemFeature RCS result false
,D/SystemConfig( 5357): refreshRcsSupport() :false
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5373 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  967): Killing 4658:com.lge.email/u0a24 (adj 15): empty #17
,D/LocationProviderProxy(  967): applying state to connected service
,D/HyLog   ( 5373): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5373): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5373): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  967): applying state to connected service
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,I/IcingCorporaProvider( 2697): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  967): Killing 4928:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1854): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1854): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  967): Delaying start of: ServiceRecord{44a36890 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1854): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1854): GC_CONCURRENT freed 1902K, 22% free 19550K/24832K, paused 2ms+3ms, total 31ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/IcingCorporaProvider( 2697): UpdateCorporaTask done [took 195 ms] updated apps [took 195 ms] 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2045): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2045): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.444839 Y: -0.418167 Z: 9.791397 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444839 .y:-0.418167 .z:9.791397
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449539 Y: -0.417603 Z: 9.782806 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449539 .y:-0.417603 .z:9.782806
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=0 what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  967): Checking http://216.58.209.78/generate_204
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2045): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2045): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV4    ( 5311): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2045): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2045): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2045): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2045): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2045): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2045): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/PowerManagerService(  967): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  967): [updateScreenState] screen on = false
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  967): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8620 usec
,D/qcom_sensors_hal(  967): hal_acquire_resources
,I/qcom_sensors_hal(  967): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  967): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  967): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  967): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  967): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  967): hal_sam_send_cancel: Sending cancel to 21
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  967): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  967): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.458389 Y: -0.408859 Z: 9.811966 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458389 .y:-0.408859 .z:9.811966
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.459488 Y: -0.409943 Z: 9.809891 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459488 .y:-0.409943 .z:9.809891
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  416): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  967): hal_sam_parse_ind: Received 1 samples
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
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.447525 Y: -0.423615 Z: 9.819122 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447525 .y:-0.423615 .z:9.819122
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.444641 Y: -0.425842 Z: 9.811050 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444641 .y:-0.425842 .z:9.811050
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.429520 Y: -0.424515 Z: 9.795273 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.429520 .y:-0.424515 .z:9.795273
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.461258 Y: -0.409912 Z: 9.809845 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461258 .y:-0.409912 .z:9.809845
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43e2e280)
,D/SurfaceFlinger(  274): Screen released, type=0 flinger=0xb7a8b450
,D/qdhwcomposer(  274): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.465073 Y: -0.402191 Z: 9.822861 
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.455078 Y: -0.395538 Z: 9.780655 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.465073 .y:-0.402191 .z:9.822861
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/dalvikvm(  967): GC_EXPLICIT freed 1860K, 49% free 29915K/57868K, paused 16ms+15ms, total 207ms
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1140): notifyScreenOnLocked
,D/KeyguardViewMediator( 1140): handleNotifyScreenOn
D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
I/WindowManager(  967): No lock screen! windowToken=null
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2045): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/wpa_supplicant( 2045): nl80211: survey data missing!
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
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2045): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2045): initialize kt scan interval and do scan state=9
D/WifiStateMachine(  967): handleMessage: X
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
V/SRS_Proc(  277): ParamSet string: screen_state=on
,D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
,D/WeatherAncestor( 1825): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:30:18
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4343e908 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/UpdateThreadPoolManager( 1825): 2 : This is isUpdating : false
,D/WeatherAncestor( 1825): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:30:18
D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
D/WeatherService( 1825): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1825): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1825): 2 : shouldTimeTickRegistered : false
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3771): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3771): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
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
,D/qdhwcomposer(  274): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 424ms
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452511818577, nextTick: 41454, mDrawingTime: 2
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452511818620, nextTick: 41412, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/qdlights( 1154): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 249, B = 249
D/WeatherService( 1825): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:30:18
,D/WeatherService( 1825): 2 : ACTION screen on
,D/WeatherService( 1825): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1825): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:30:18
,D/qdlights( 1154): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 243, B = 243
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
D/qdlights( 1154): set_light_notifications: 2,ff00eded,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 237, B = 237
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
D/qdlights( 1154): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 231, B = 231
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1154): set_light_notifications: 2,ff00e1e1,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 225, B = 225
,V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  967): Vibrator off
,V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3} (stop requested)
D/dalvikvm( 1154): GC_CONCURRENT freed 2892K, 11% free 25449K/28520K, paused 11ms+1ms, total 30ms
D/qdlights( 1154): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 219, B = 219
D/UsbSettings( 2628): [AUTORUN] onDestroy() : getDefaultFunction =boot
,D/WifiStateMachine(  967): handleScreenStateChanged: false
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/KeyguardViewMediator( 1140): handleNotifyScreenOff
,D/KeyguardViewManager( 1140): onScreenTurnedOff()
D/WifiStateMachine(  967): handleMessage: X
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{42d3d2a0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
V/UsbSettings( 2628): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2628): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2628): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2045): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
,V/SRS_Proc(  277): ParamSet string: screen_state=off
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
D/WifiController(  967): CMD_SCREEN_OFF 
,D/WifiController(  967): shouldWifiStayAwake TRUE
D/wpa_supplicant( 2045): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1154): clear
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{42d3d2a0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1825): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:30:18
,D/WeatherService( 1825): 2 : ACTION screen off
,D/WeatherService( 1825): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:30:18
D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
,D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/NfcService( 1473): NFC-C OFF
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
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
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1154): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1154): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1154): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1154): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  416): sns_pwr.c(320):releasing wakelock
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  291): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1558): Vacuum at: now=1452511827712 tag=VacuumService
,I/GoogleURLConnFactory( 1558): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1558): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1558): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1558): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1558): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1558): No account for auth token provided
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/Finsky  ( 5232): [466] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5232): [1] 5.onFinished: Installation state replication succeeded.
,W/Uploader( 1558): No account for auth token provided
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1558):  no longer exists, so no auth token.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1558): No account for auth token provided
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452511836371630471; DSPS: 5278849; Offset: 1452511675273943704
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452511856372963328; DSPS: 5934253; Offset: 1452511675273933787
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452511860046, nextTick: 59977, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452511860052, nextTick: 59971, mDrawingTime: 3
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452511876374860820; DSPS: 6589675; Offset: 1452511675273939190
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452511896376215553; DSPS: 7245079; Offset: 1452511675273951149
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452511916378053357; DSPS: 7900500; Offset: 1452511675273927381
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452511920045, nextTick: 59977, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452511920051, nextTick: 59955, mDrawingTime: 10
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452511936379852725; DSPS: 8555918; Offset: 1452511675273956729
,I/jxcore-log( 4749): TAP version 13
I/jxcore-log( 4749): 
,I/jxcore-log( 4749): # setup
I/jxcore-log( 4749): 
,I/jxcore-log( 4749): # multiplex can send data
I/jxcore-log( 4749): 
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452511956381613967; DSPS: 9211336; Offset: 1452511675273947952
,I/jxcore-log( 4749): # teardown
I/jxcore-log( 4749): 
,I/jxcore-log( 4749): ok 1 String should be length:200
I/jxcore-log( 4749): 
,I/jxcore-log( 4749): # setup
I/jxcore-log( 4749): 
,I/jxcore-log( 4749): # muxServerBridge
I/jxcore-log( 4749): 
,I/jxcore-log( 4749): # teardown
I/jxcore-log( 4749): 
,I/jxcore-log( 4749): server bridge: new client socket
I/jxcore-log( 4749): 
,I/jxcore-log( 4749): client bridge: new client socket
I/jxcore-log( 4749): 
,I/jxcore-log( 4749): client bridge: socket closed
I/jxcore-log( 4749): 
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452511976382882917; DSPS: 9866738; Offset: 1452511675273935164
,D/wpa_supplicant( 2045): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Remove id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Remove id 7 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Remove id 8 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Remove id 9 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Remove id 10 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2045): wlan0: BSS: Remove id 11 BSSID 64:7c:34:b0:03:6e SSID 'UPC4688432' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: BSS: Remove id 12 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 64:7c:34:38:27:cc]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:26:f2:18:08:c8]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 44:e9:dd:10:c0:ab]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 64:7c:34:b0:03:6e]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 44:e9:dd:10:c0:ad]
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452511980037, nextTick: 59990, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452511980049, nextTick: 59979, mDrawingTime: 3
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452511996384708952; DSPS: 10522158; Offset: 1452511675273930144
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512016386275246; DSPS: 11177569; Offset: 1452511675273940041
,I/LocationManagerService(  967): remove 4339b780
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2685): GC_CONCURRENT freed 7739K, 32% free 16913K/24832K, paused 15ms+2ms, total 89ms
,D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 44ms
,D/dalvikvm( 2685): GC_CONCURRENT freed 1827K, 32% free 17133K/24832K, paused 3ms+1ms, total 29ms
,D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/Mlt MonitorService( 2685): parseLastkmsg to dump
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512036388100186; DSPS: 11832989; Offset: 1452511675273933927
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512040044, nextTick: 59984, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512040050, nextTick: 59973, mDrawingTime: 4
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512056389470960; DSPS: 12488394; Offset: 1452511675273931410
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512076391318713; DSPS: 13143814; Offset: 1452511675273948108
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512096392618132; DSPS: 13799217; Offset: 1452511675273935271
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512100039, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512100043, nextTick: 59979, mDrawingTime: 5
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x432a5290: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1558): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1558): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1558): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1558): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1558): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5232): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5232): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5232): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5232): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5232): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5232): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5232): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5232): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1558): GC_CONCURRENT freed 1663K, 27% free 18189K/24832K, paused 3ms+4ms, total 94ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 5232): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5232): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512116394285990; DSPS: 14454631; Offset: 1452511675273955180
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512136395573326; DSPS: 15110034; Offset: 1452511675273930260
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512156397475558; DSPS: 15765456; Offset: 1452511675273940402
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512160037, nextTick: 59992, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512160048, nextTick: 59984, mDrawingTime: 1
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512176399156956; DSPS: 16420871; Offset: 1452511675273943333
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512196400848927; DSPS: 17076287; Offset: 1452511675273926320
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512216402235899; DSPS: 17731692; Offset: 1452511675273940001
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512220039, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512220045, nextTick: 59970, mDrawingTime: 6
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512236403831361; DSPS: 18387104; Offset: 1452511675273948549
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512256405648434; DSPS: 19042524; Offset: 1452511675273934567
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512276406938741; DSPS: 19697926; Offset: 1452511675273943136
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512280038, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512280048, nextTick: 59981, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512296408539983; DSPS: 20353339; Offset: 1452511675273926946
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512316410438621; DSPS: 21008761; Offset: 1452511675273933495
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512336412237884; DSPS: 21664180; Offset: 1452511675273932220
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512340035, nextTick: 59993, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512340039, nextTick: 59984, mDrawingTime: 4
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512356413844283; DSPS: 22319592; Offset: 1452511675273951705
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512376415689901; DSPS: 22975013; Offset: 1452511675273935751
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512396417282133; DSPS: 23630425; Offset: 1452511675273941069
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512400049, nextTick: 59972, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512400057, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512416418848010; DSPS: 24285836; Offset: 1452511675273950550
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512436419730138; DSPS: 24941225; Offset: 1452511675273947668
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512456421408932; DSPS: 25596640; Offset: 1452511675273947995
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512460046, nextTick: 59983, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512460047, nextTick: 59986, mDrawingTime: 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500,
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512476422840904; DSPS: 26252047; Offset: 1452511675273945641
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512496425129647; DSPS: 26907482; Offset: 1452511675273945565
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,I/EventLogService( 1854): Aggregate from 1452511792959 (log), 1452510594340 (data)
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512516427035785; DSPS: 27562905; Offset: 1452511675273929096
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512520049, nextTick: 59972, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512520057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512536428574319; DSPS: 28218315; Offset: 1452511675273941751
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512556430271915; DSPS: 28873731; Offset: 1452511675273930363
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512576431569095; DSPS: 29529133; Offset: 1452511675273945804
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512580046, nextTick: 59977, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512580052, nextTick: 59975, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512596433073358; DSPS: 30184543; Offset: 1452511675273924189
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512616435422101; DSPS: 30839979; Offset: 1452511675273953596
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512636437117250; DSPS: 31495395; Offset: 1452511675273939760
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512640049, nextTick: 59964, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512640062, nextTick: 59967, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512656438967971; DSPS: 32150816; Offset: 1452511675273928909
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512676440261505; DSPS: 32806218; Offset: 1452511675273940705
,D/GCM     ( 1558): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GoogleURLConnFactory( 1558): Using platform SSLCertificateSocketFactory
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512696441886289; DSPS: 33461631; Offset: 1452511675273948057
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512700049, nextTick: 59976, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512700053, nextTick: 59976, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512716444276750; DSPS: 34117070; Offset: 1452511675273927629
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512736445893044; DSPS: 34772483; Offset: 1452511675273926492
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512756447416735; DSPS: 35427893; Offset: 1452511675273924304
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512760057, nextTick: 59972, mDrawingTime: 3
D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512760058, nextTick: 59973, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512776448714227; DSPS: 36083295; Offset: 1452511675273940058
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512796450060782; DSPS: 36738699; Offset: 1452511675273943839
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512816451859160; DSPS: 37394118; Offset: 1452511675273941680
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512820031, nextTick: 60001, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512820049, nextTick: 59982, mDrawingTime: 1
,W/ProcessCpuTracker(  967): Skipping unknown process pid 6457
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512836453920715; DSPS: 38049546; Offset: 1452511675273928040
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512856455701281; DSPS: 38704964; Offset: 1452511675273938586
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512876457286116; DSPS: 39360376; Offset: 1452511675273936507
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512880037, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512880041, nextTick: 59983, mDrawingTime: 3
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512896458883452; DSPS: 40015788; Offset: 1452511675273946929
,D/wpa_supplicant( 2045): nl80211: Event message available
D/wpa_supplicant( 2045): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2045): nl80211: Disconnect event
D/wpa_supplicant( 2045): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2045): wlan0: Deauthentication notification
D/wpa_supplicant( 2045): wlan0:  * reason 0
D/wpa_supplicant( 2045): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2045): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2045): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2045): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2045): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2045): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2045): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2045): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2045): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
,D/WifiStateMachine(  967): handleMessage: E msg.what=147460
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState,
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb75f6d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2045):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2045): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2045): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): EAPOL: External notification - portEnabled=0,
,D/wpa_supplicant( 2045): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized,
,D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2045): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2045): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2045): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2045): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2045): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2045): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection lost
D/WifiStateMachine(  967): Stopping DHCP and clearing IP
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2045): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2045): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2045): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2045): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2045): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/DhcpStateMachine(  967): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  967): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/wpa_supplicant( 2045): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2045): wlan0: nl80211: scan request
,D/wpa_supplicant( 2045): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2045): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2045): nl80211: Event message available
D/wpa_supplicant( 2045): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2045): wlan0: nl80211: Scan trigger
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
D/QCNEA   (  425): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  425): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  425): |CAC| updateNetCfgInfo
V/QCNEA   (  425): |CAC| *********************************************
V/QCNEA   (  425): |CAC|                   Netconfig               
V/QCNEA   (  425): |CAC| *********************************************
V/QCNEA   (  425): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  425): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  425): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  425): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  425): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  425): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  425): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  425): |CAC| *********************************************
D/QCNEA   (  425): |CAC| Received bssid= 
D/QCNEA   (  425): |CAC| net type = 3
V/QCNEA   (  425): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  425): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  425): |CAC| 	ssid           =NG700
V/QCNEA   (  425): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  425): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  425): |CAC| *********************************************
D/QCNEA   (  425): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  425): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  425): |CAC| dispatchNetCfg: updating:0xb87a78dc
,D/QCNEA   (  425): |CAC| readCallback: read len:0, ret:-1, errno:11,
,D/WifiHS20(  967): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  425): Reading a NULL string not supported here.
,E/Parcel  (  425): Reading a NULL string not supported here.
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/QcConnectivityService(  967): Attempting to switch to mobile
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6526 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 6526): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
D/HyLog   ( 6526): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6526): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
,I/PCSuite ( 6526): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6526): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6526): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
W/NetworkManagementService(  967): route cmd failed: 
W/NetworkManagementService(  967): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,D/NetUtils(  967): android_net_utils_resetConnections in env=0x61f726a8 clazz=0xce900001 iface=wlan0 mask=0x3
I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6567 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  967): Killing 4942:com.android.chrome/u0a63 (adj 15): empty #17
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
,I/jxcore-log( 4749): Toggling radios to false
I/jxcore-log( 4749): 
,D/DhcpStateMachine(  967): StoppedState
D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  967): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42f67840 mBinding = false
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,V/NativeCrypto( 1558): Read error: ssl=0x63a4e3d0: I/O error during system call, Connection timed out
,D/HyLog   ( 6567): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6567): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6567): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/NativeCrypto( 1558): SSL shutdown failed: ssl=0x63a4e3d0: I/O error during system call, Broken pipe
,D/BluetoothManagerService(  967): Message: 2
,D/BluetoothManagerService(  967): Sending off request.
D/BluetoothAdapterService(1116705464)( 1222): disable() called...
D/BluetoothAdapterState( 1222): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,I/BluetoothAdapterState( 1222): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1222): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btif ( 1222): btif_set_adapter_property type: 7, len 4, 0x429b4e78
I/bt-btif ( 1222): set property scan mode : 0
,I/bt-btif ( 1222): bta_dm_sm_execute event:0x3
I/bt-btif ( 1222): btif_in_storage_request_copy_cb
I/bt-btif ( 1222): execute storage request event : 2
I/BluetoothAdapterState( 1222): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/bt-btif ( 1222): type: 7, len 4, 0x607ddd42
D/bt-btif ( 1222): in, bd addr:, prop type:7, len:4
,I/bt-btif ( 1222): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothAdapterState( 1222): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bluedroid( 1222): disable 1
I/bt-btif ( 1222): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
D/bt-btif ( 1222): h:6, process_cmd_sock return false, exit...
D/bt-btif ( 1222): socket poll thread exiting, h:6
D/bt-btif ( 1222): cleanup slot:1, fd:89, scn:6, sdp_handle:0x1000a
D/bt-btif ( 1222): del_rfc_sdp_rec: handle:0x1000a
I/bt-btif ( 1222): BTA_JvDeleteRecord
D/bt-sdp  ( 1222): SDP_DeleteRecord ok, num_records:12
,I/bt-btif ( 1222): BTA_JvRfcommStopServer
V/BluetoothMapService( 1222): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 1222): bta_jv_rfcomm_stop_server
D/bt-btif ( 1222): find_rfc_pcb(): FOUND rfc_cb_handle 0x1, port.jv_handle: 0x81, state: 4, rfc_cb->handle: 0x81
D/bt-btif ( 1222): bta_jv_rfcomm_stop_server: p_pcb:0x60e8c0e8, p_pcb->port_handle:6
,D/bt-btif ( 1222): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60e8c0e8, user:1, state:4, jv handle: 0x81
D/bt-btif ( 1222): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:6, user_data:1
D/bt-btif ( 1222): bta_jv_rfcomm_stop_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1222): cleanup slot:2, fd:91, scn:19, sdp_handle:0x1000b
V/BluetoothPbapService( 1222): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/bt-btif ( 1222): del_rfc_sdp_rec: handle:0x1000b
I/bt-btif ( 1222): BTA_JvDeleteRecord
D/bt-sdp  ( 1222): SDP_DeleteRecord ok, num_records:11
I/bt-btif ( 1222): BTA_JvRfcommStopServer
E/bt-btif ( 1222): bta_jv_rfcomm_stop_server
D/bt-btif ( 1222): find_rfc_pcb(): FOUND rfc_cb_handle 0x2, port.jv_handle: 0x82, state: 4, rfc_cb->handle: 0x82
D/bt-btif ( 1222): bta_jv_rfcomm_stop_server: p_pcb:0x60e8c0fc, p_pcb->port_handle:7
D/bt-btif ( 1222): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60e8c0fc, user:2, state:4, jv handle: 0x82
D/bt-btif ( 1222): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:19, user_data:2
D/bt-btif ( 1222): bta_jv_rfcomm_stop_server: sec id in use:1, rfc_cb in use:1
D/bt-btif ( 1222): cleanup slot:3, fd:94, scn:12, sdp_handle:0x1000c
D/bt-btif ( 1222): del_rfc_sdp_rec: handle:0x1000c
D/WifiService(  967): setWifiEnabled: false pid=4749, uid=10304
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
I/bt-btif ( 1222): BTA_JvDeleteRecord
D/bt-sdp  ( 1222): SDP_DeleteRecord ok, num_records:10
I/bt-btif ( 1222): BTA_JvRfcommStopServer
E/BtOppRfcommListener( 1222): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-btif ( 1222): leaving
D/IOP_DB_BT( 1222): db_close: nbr users 0
D/IOP_DB_BT( 1222): db_close: free database
D/BluetoothManagerService(  967): Message: 60
D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  967): Bluetooth State Change Intent: 12 -> 13
D/btif_config_util( 1222): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
E/bt-btif ( 1222): leaving
D/bt-btif ( 1222): find_rfc_pcb(): FOUND rfc_cb_handle 0x3, port.jv_handle: 0x83, state: 4, rfc_cb->handle: 0x83
D/bt-btif ( 1222): bta_jv_rfcomm_stop_server: p_pcb:0x60e8c110, p_pcb->port_handle:8
D/bt-btif ( 1222): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60e8c110, user:3, state:4, jv handle: 0x83
D/bt-btif ( 1222): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:12, user_data:3
D/bt-btif ( 1222): bta_jv_rfcomm_stop_server: sec id in use:0, rfc_cb in use:0
D/bt-sdp  ( 1222): SDP_DeleteRecord ok, num_records:9
I/bt-btif ( 1222): Removing UUID=0x1116 from EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1222): Removing UUID=0x1116 from EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1222): Removing UUID=0x1117 from EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1222): Removing UUID=0x1115 from EIR
D/bt-btif ( 1222): BTA is generating EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04011460
I/bt-btif ( 1222): bta_dm_sm_execute event:0x1
D/bt-btif ( 1222): bta_sys_disable: module 0
W/bt-btif ( 1222): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
I/bt-btif ( 1222): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 1222): bta_ag_del_records 0
D/bt-sdp  ( 1222): SDP_DeleteRecord ok, num_records:8
I/bt-btif ( 1222): Removing UUID=0x1112 from EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04001460
D/bt-btif ( 1222): bta_ag_del_records 1
D/bt-sdp  ( 1222): SDP_DeleteRecord ok, num_records:7
I/bt-btif ( 1222): Removing UUID=0x111F from EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000494 00001460
D/bt-btif ( 1222): bta_ag_scb_dealloc 1
W/bt-obex ( 1222): Ignore event 10 in state 1
D/bt-sdp  ( 1222): SDP_DeleteRecord ok, num_records:6
I/bt-btif ( 1222): Removing UUID=0x1106 from EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000494 00001420
D/bt-sdp  ( 1222): SDP_DeleteRecord ok, num_records:5
I/bt-btif ( 1222): Removing UUID=0x112D from EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00001420
I/bt-btif ( 1222): bta_av_del_rc  handle: 0 status=0x10, rc_acp_handle:0, idx:1
I/bt-btif ( 1222): end del_rc handle: 255 status=0x0, rc_acp_handle:255, lidx:0
D/bt-btif ( 1222): bta_av_cleanup
D/bt-btif ( 1222): deregistered 64(h65)
D/bt-sdp  ( 1222): SDP_DeleteRecord ok, num_records:4
I/bt-btif ( 1222): Removing UUID=0x110A from EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00001020
D/bt-btif ( 1222): audio 0x0, video: 0x0, disable:1
D/bt-sdp  ( 1222): SDP_DeleteRecord ok, num_records:3
I/bt-btif ( 1222): Removing UUID=0x110C from EIR
I/bt-btif ( 1222): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00000020
D/bt-btif ( 1222): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1222): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1222): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1222): bta_gattc_disable
I/bt-att  ( 1222): GATT_Deregister gatt_if=3
I/bt-att  ( 1222): G,ATT_Listen gatt_if=3
D/bt-btif ( 1222): bta_dm_gattc_callback event = 1
I/bt-att  ( 1222): GATT_Deregister gatt_if=4
I/bt-att  ( 1222): GATT_Listen gatt_if=4
D/bt-btif ( 1222): bta_hh_gattc_callback event = 1
I/bt-btif ( 1222): bta_dm_search_sm_execute state:0, event:0x206
E/bt-btif ( 1222): bta_gattc_deregister Deregister Failed, unknown client cif
D/LGBluetoothAPIService( 1154): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/WifiStateMachine(  967): handleMessage: E msg.what=131084
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
I/jxcore-log( 4749): Radios toggled
I/jxcore-log( 4749): 
D/bt-btif ( 1222): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/bt-btif ( 1222): btif_fts_upstreams_evt: event=BTA_FTS_DISABLE_EVT
I/bt-btif ( 1222): File Transfer: Disable complete
D/bt-btif ( 1222): btif_hh_upstreams_evt: event=BTA_HH_DISABLE_EVT
D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
D/WifiStateMachine(  967): invokeExitMethods: ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: DriverStartedState
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/LGBluetoothUtils( 2628): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 2628): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2045): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2045): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/BluetoothMapService( 1222): onReceive
D/BluetoothMapService( 1222): STATE_TURNING_OFF
D/BluetoothMapService( 1222): MAP Service closeService in
D/LGBluetoothMapAdapter( 1222): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1222): MAP Service closeService out
V/BtOppService( 1222): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 1222): stopping Accept Thread
V/BtOppRfcommListener( 1222): close mBtServerSocket
V/BtOppRfcommListener( 1222): waiting for thread to terminate
I/BtOppRfcommListener( 1222): BluetoothSocket listen thread finished
,V/BtOppRfcommListener( 1222): done waiting for thread to terminate
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
,V/BtOppService( 1222): onDestroy
,D/LGBluetoothOppAdapter( 1222): [BTUI] LGBluetoothOppAdapter cleanup
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2045): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2045): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  967):    returned null
D/WifiStateMachine(  967): invokeExitMethods: DriverStartedStateExt
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine(  967): invokeEnterMethods: WaitForP2pDisableState
D/WifiMonitor(  967): WifiMonitorSingleton gotten
,D/WifiMonitor(  967): stopMonitoring(p2p0) = android.net.wifi.p2p.WifiP2pService$P2pStateMachine@431a3a10
,D/WfdService( 1154): Waiting for Wifi disabling
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131205
D/WifiStateMachine(  967): processMsg: WaitForP2pDisableState
D/WifiStateMachine(  967): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  967): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine(  967): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=1
D/WifiP2pService(  967): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pDisablingState
D/WifiP2pService(  967): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): p2p socket connection lost
D/WifiP2pService(  967): P2pDisabledState
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine(  967): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine(  967): Stopping DHCP and clearing IP
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2045): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2045): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2045): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/WifiP2pService(  967): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/wpa_supplicant( 2045): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2045): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
I/bt-btif ( 1222): btif_dm_cancel_discovery
I/bt-btif ( 1222): bta_dm_search_sm_execute state:0, event:0x201
D/wpa_supplicant( 2045): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
,D/DhcpStateMachine(  967): StoppedState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=DISCONNECTED
D/WifiStateMachine(  967): stopping supplicant
D/WifiMonitor(  967): WifiMonitorSingleton gotten
,D/WifiNative-p2p0(  967): doBoolean: TERMINATE
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/Parcel  (  425): Reading a NULL string not supported here.
,E/Parcel  (  425): Reading a NULL string not supported here.
D/wpa_supplicant( 2045): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/wpa_supplicant( 2045): p2p0: Removing interface p2p0
D/wpa_supplicant( 2045): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 2045): TDLS: Tear down peers
D/wpa_supplicant( 2045): p2p0: No keys have been configured - skip key clearing
,D/wpa_supplicant( 2045): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2045): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2045): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2045): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): p2p0: No keys have been configured - skip key clearing
D/WifiNative-p2p0(  967):    returned true
D/WifiStateMachine(  967): setWifiState: disabling
,E/WifiStateMachine(  967): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  967): useWiFiOffloading() : false
E/WifiStateMachine(  967): CONFIG_LGE_WLAN_PATH : true
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196614
D/WifiStateMachine(  967): processMsg: SupplicantStoppingState
D/QRemote ( 6567): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiHS20(  967): hidePasspointNotification off =false
V/WfdStateTracker( 1154): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServiceExtension(  967): WIFI_STATE_CHANGED_ACTION [0]
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6567): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/QRemote ( 6567): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6567): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 6567): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6567): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6567): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/wpa_supplicant( 2045): p2p0: Cancelling scan request
D/wpa_supplicant( 2045): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 2045): p2p0: Cancelling authentication timeout
D/wpa_supplicant( 2045): p2p0: P2P: Disable P2P since removing the management interface is being removed
D/wpa_supplicant( 2045): P2P: Stopping find
D/wpa_supplicant( 2045): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2045): P2P: State IDLE -> IDLE
,D/wpa_supplicant( 2045): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/QRemote ( 6567): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6567): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
,I/ActivityManager(  967): Killing 4957:com.lge.drmservice/u0a66 (adj 15): empty #17
,D/wpa_supplicant( 2045): netlink: Operstate: linkmode=0, operstate=6
D/wpa_supplicant( 2045): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 2045): nl80211: Unsubscribe mgmt frames handle 0xb7606c28 (mode change)
I/wpa_supplicant( 2045): p2p0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/wpa_supplicant( 2045): [ITEC] Close WIFLUS socket interface - START
I/wpa_supplicant( 2045): [ITEC] Close WIFLUS read interface - DONE
,I/wpa_supplicant( 2045): HY wiflus comm channel de-initialized : wiflus = 0
D/wpa_supplicant( 2045): Control interface directory not empty - leaving it behind
,D/wpa_supplicant( 2045): wlan0: Removing interface wlan0
D/WifiMonitor(  967): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/wpa_supplicant( 2045): wlan0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=SCANNING
D/WifiMonitor(  967): Dropping event because monitor (p2p0) is stopped
D/wpa_supplicant( 2045): TDLS: Tear down peers
D/wpa_supplicant( 2045): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2045): wlan0: State: SCANNING -> DISCONNECTED
,D/wpa_supplicant( 2045): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2045): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2045): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2045): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2045): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2045): wlan0: No keys have been configured - skip key clearing
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
W/wpa_supplicant( 2045): USIM:  scard_deinit function
D/WifiStateMachine(  967): processMsg: SupplicantStoppingState
D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,V/BluetoothPbapReceiver( 1222): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1222): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1222): ***********state = 13
D/DockEventReceiver( 2628): finishStartingService: stopping service
,V/BluetoothPbapReceiver( 1222): ***********Calling start service!!!! with action = null
W/ContextImpl( 2628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
V/BluetoothPbapService( 1222): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapService( 1222): state: 13
,V/BluetoothPbapService( 1222): Pbap Service closeService in
V/BluetoothPbapService( 1222): successfully stopped pbap service
,V/BluetoothPbapService( 1222): Pbap Service closeService out
V/BluetoothPbapService( 1222): Pbap Service onDestroy
V/BluetoothPbapService( 1222): Pbap Service closeService in
V/BluetoothPbapService( 1222): Pbap Service closeService out
,D/LGBluetoothPbapAdapter( 1222): [BTUI] cleanup
,D/LGBluetoothAuthorization( 2628): [BTUI] cancel All Notification
D/BluetoothPbap( 2628): Proxy object disconnected
,D/PbapServerProfile( 2628): Bluetooth service disconnected
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/BluetoothPermissionRequest( 2628): onReceive
D/LGBluetoothAuthorization( 2628): [BTUI] cancel All Notification
,D/LGBluetoothResetSettingReceiver( 2628): return without doing reset settings.
D/wpa_supplicant( 2045): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2045): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2045): wlan0: Cancelling scan request
D/wpa_supplicant( 2045): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2045): wlan0: Cancelling authentication timeout
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
,V/BluetoothOppReceiver( 1222): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,D/BluetoothOppNotification( 1222): [BTUI] cancel opp incoming file confirm notification
,D/BluetoothOppNotification( 1222): [BTUI] cancel opp active transfer file notification
,D/wpa_supplicant( 2045): netlink: Operstate: linkmode=0, operstate=6
,D/wpa_supplicant( 2045): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2045): nl80211: Unsubscribe mgmt frames handle 0xb75f7590 (mode change)
I/wpa_supplicant( 2045): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 2045): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/wpa_supplicant( 2045): [ITEC] Close WIFLUS socket interface - START
I/wpa_supplicant( 2045): [ITEC] - NOT INITIALIZED - DONE
D/wpa_supplicant( 2045): Control interface directory not empty - leaving it behind
,D/wpa_supplicant( 2045): Get randomness: len=20 entropy=0
D/Tethering(  967): InitialState.processMessage what=4
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
D/WifiStateMachine(  967): handleMessage: E msg.what=147458
D/WifiStateMachine(  967): processMsg: SupplicantStoppingState
D/WifiStateMachine(  967): Supplicant connection lost
D/WifiMonitor(  967): WifiMonitorSingleton gotten
,D/Tethering(  967): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,I/ActivityManager(  967): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6591 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/Tethering(  967): sendTetherStateChangedBroadcast 0, 0, 0
,I/bt-btif ( 1222): bta_sys_sm_execute state:2, event:0x3
D/bt-btif ( 1222): bta_sys_hw_api_disable for 0, active modules: 0x0001
D/bt-btif ( 1222): bta_sys_disable: module 0
I/bt-btif ( 1222): bta_sys_sm_execute state:3, event:0x4
D/bt-btif ( 1222): bta_sys_hw_evt_disabled - module 0x0
D/bt-btif ( 1222):  bta_dm_sys_hw_cback with event: 0
I/bt-btif ( 1222): btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
,I/bt-btif ( 1222): btif_disable_bluetooth_evt()::btif_core_cb: is_radio_req: 0, radio_ref_count: 0, state: 4
I/bt-btif ( 1222): HC lib lpm enable=0 return 0
D/bt-btif ( 1222): bte_main_disable
D/bt-btif ( 1222): bte_hci_disable
D/bt_hwcfg( 1222): hw_epilog_process
D/bt-btif ( 1222): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1222): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1222): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1222): audio 0x0, video: 0x0, disable:1
W/bt-l2cap( 1222): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1222): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1222): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1222): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1222): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1222): ag scb idx 1 not allocated
E/bt-btif ( 1222): BTA AG is already disabled, ignoring ...
,I/bt-btif ( 1222): HC lpm_result_cb 0
,D/HyLog   ( 6591): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6591): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6591): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/AuthorizationBluetoothService( 1558): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  967): Killing 4973:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/Wireless_Storage( 4998): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
I/PCSuite ( 6526): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6526): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6526): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6567): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6567): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
,D/bt_hwcfg( 1222): hw_epilog_cback Opcode:0x0C03 Status: 0
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/PCSuite ( 6526): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/UsbSettingsReceiver( 2628): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2628): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2628): [AUTORUN] sys.usb.state = boot,adb
D/UsbSettingsReceiver( 2628): [AUTORUN] persist.sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2628): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/Config  ( 2628): getOperator() : OPEN
D/UsbSettingsControl( 2628): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 2628): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 2628): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 2628): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2628): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 2628): [AUTORUN] setTetherStatus() : status=false
,D/WifiStateMachine(  967): setWifiState: disabled
,W/Settings( 5311): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,D/LGDMClient( 2882): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiActivationWhileCharging(  967): register : WIFI_ACTIVATION_WHILE_CHARGING_OFF[1]
,E/WifiStateMachine(  967): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  967): useWiFiOffloading() : false
E/WifiStateMachine(  967): CONFIG_LGE_WLAN_PATH : true
,D/LGDMClient( 2882): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6607 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  967): transitionTo: destState=InitialState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  967): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine(  967): invokeEnterMethods: InitialState
V/WfdStateTracker( 1154): WfdStateTracker handleDirectStateChangedEvent: 0
I/WifiServiceExtension(  967): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServiceExtension(  967): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServiceExtension(  967): batteryPsActivateMsgHandler : this is not treated
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
W/Settings( 1424): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  425): Reading a NULL string not supported here.
E/Parcel  (  425): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/HyLog   ( 6607): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6607): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/bt_hci_bdroid( 1222): bt_hc_worker_thread exiting
W/bt_userial( 1222): select_read return size <=0:0, exiting userial_read_thread
I/bt_userial_vendor( 1222): device fd = 84 close
,D/HyLog   ( 6607): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/BTSNOOP-DISP( 1222): btsnoop_close
I/GKI_LINUX( 1222): GKI_destroy_task: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,I/GKI_LINUX( 1222): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1222): GKI_destroy_task: GKI_destroy_task(): task [BTU] terminated
,I/GKI_LINUX( 1222): GKI_freeze: GKI_freeze
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,I/bt-btif ( 1222): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothServiceJni( 1222): adapter_state_change_callback: Status is: 0
D/BluetoothAdapterState( 1222): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/LGDMSGCM( 6607): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
,W/BluetoothAdapterService( 1222): Stopping service com.broadcom.bt.service.hfp.BrcmHeadsetService
,W/BluetoothAdapterService( 1222): Stopping service com.android.bluetooth.a2dp.A2dpService
,D/BrcmHeadsetService( 1222): Received stop request...Stopping profile...
I/LGBluetoothHfpAdapter( 1222): [BTUI] LGBluetoothHfpAdapter cleanup
,W/LGBluetoothHeadsetServiceJni( 1222): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428f92b8
,D/HeadsetStateMachine( 1222): Exit Disconnected: -1
D/BluetoothHeadset(  967): Proxy object disconnected
D/BluetoothHeadset( 2628): Proxy object disconnected
,D/HeadsetProfile( 2628): Bluetooth service disconnected
,D/BluetoothHeadset( 1449): Proxy object disconnected
,D/BluetoothHeadset( 1449): Proxy object disconnected
D/BluetoothAdapterService(1116705464)( 1222): Message: 1
,D/BluetoothAdapterService(1116705464)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still running: com.broadcom.bt.service.sap.SapService
D/HeadsetStateMachine( 1222): Unbinding service...
,D/BluetoothHeadset( 1449): Proxy object disconnected
,W/BluetoothAdapterService( 1222): Stopping service com.android.bluetooth.hid.HidService
,W/ContextImpl( 6607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/HeadsetPhoneState( 1222): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1222): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 1222): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1222): [BTUI] listenForMultiSimPhoneState : start = false
W/Brcm_BluetoothHeadsetServiceJni( 1222): Cleaning up Bluetooth Handsfree Interface...
I/bt-btif ( 1222): cleanup
W/BluetoothAdapterService( 1222): Stopping service com.android.bluetooth.hdp.HealthService
I/PCSuite ( 6526): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 6526): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6526): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/bt-btif ( 1222): btif_disable_service: Current Services:0x120108
W/Brcm_BluetoothHeadsetServiceJni( 1222): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 1222): [BTUI] LGBluetoothHfpAdapter cleanup
W/BluetoothAdapterService( 1222): Stopping service com.android.bluetooth.pan.PanService
D/A2dpService( 1222): Received stop request...Stopping profile...
D/A2dpStateMachine( 1222): Exit Disconnected: -1
D/LGBluetoothA2dpAdapter( 1222): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 1222): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428f92b8
D/BluetoothA2dp(  967): Proxy object disconnected
W/BluetoothAdapterService( 1222): Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothA2dp( 2628): Proxy object disconnected
D/A2dpProfile( 2628): Bluetooth service disconnected
D/HidService( 1222): Received stop request...Stopping profile...
W/BluetoothAdapterService( 1222): Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428f92b8
W/BluetoothAdapterService( 1222): Stopping service com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1222): Stopping service com.broadcom.bt.service.ftp.FTPService
D/HealthService( 1222): Received stop request...Stopping profile...
D/BluetoothInputDevice( 2628): Proxy object disconnected
D/HidProfile( 2628): Bluetooth service disconnected
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428f92b8
D/BluetoothAdapterState( 1222): Stopping profile services that were post enabled
D/BluetoothAdapterService(1116705464)( 1222): Message: 1
D/BluetoothAdapterService(1116705464)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still running: com.broadcom.bt.service.sap.SapService
D/PanService( 1222): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428f92b8
D/BluetoothTethering(  967): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  967): attempted to stop reverse tether with nothing tethered
D/BluetoothPan(  967): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 2628): BluetoothPAN Proxy object disconnected
,D/PanProfile( 2628): Bluetooth service disconnected
I/bt-btif ( 1222): cleanup
I/bt-btif ( 1222): ## A2DP STOP MEDIA TASK ##
I/GKI_LINUX( 1222): GKI_destroy_task: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,D/bt-btif ( 1222): UIPC_Close : ch_id 5
D/bt-btif ( 1222): UIPC_Close : waiting for shutdown to complete
I/bt-btif ( 1222): UIPC SEND WAKE UP
I/bt-btif ( 1222): UIPC READ THREAD EXITING
I/bt-btif ( 1222): uipc_main_cleanup
I/bt-btif ( 1222): CLOSE CHANNEL 0
I/bt-btif ( 1222): CLOSE SERVER (FD 69)
D/bt-btif ( 1222): A2DP-CTRL-CHANNEL EVENT UIPC_CLOSE_EVT
I/bt-btif ( 1222): UIPC SEND WAKE UP
,I/bt-btif ( 1222): CLOSE CHANNEL 1
I/bt-btif ( 1222): CLOSE CHANNEL 2
I/bt-btif ( 1222): CLOSE CHANNEL 3
I/bt-btif ( 1222): UIPC READ THREAD DONE
D/bt-btif ( 1222): UIPC_Close : shutdown complete
D/bt-btif ( 1222): MEDIA TASK EXITING
I/GKI_LINUX( 1222): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1222): GKI_destroy_task: GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/bt-btif ( 1222): btif_disable_service: Current Services:0x120100
D/LGBluetoothAvrcpAdapter( 1222): [BTUI] cleanup
D/LGBluetoothAvrcpManager( 1222): [BTUI] terminateAvrcpManager
,D/LGBluetoothAvrcpManager( 1222): [BTUI] cleanupPlayStatus() : mPlayStatus = 0
V/BluetoothAVRCP1.3ServiceJni( 1222): cleanupNativeAVRCP
I/bt-btif ( 1222): ## cleanup ##
,D/bt-btif ( 1222): close_uinput
D/BluetoothMapService( 1222): Received stop request...Stopping profile...
,D/BluetoothMapService( 1222): stop()
D/BluetoothMapService( 1222): MAP Service closeService in
D/LGBluetoothMapAdapter( 1222): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1222): MAP Service closeService out
,D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428f92b8
,I/ActivityManager(  967): Killing 5019:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
D/BluetoothMap( 2628): Proxy object disconnected
D/MapProfile( 2628): Bluetooth service disconnected
D/BluetoothAdapterService(1116705464)( 1222): Message: 1
D/BluetoothAdapterService(1116705464)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still running: com.broadcom.bt.service.sap.SapService
D/BtGatt.DebugUtils( 1222): handleDebugAction() action=null
D/BtGatt.GattService( 1222): Received stop request...Stopping profile...
D/BtGatt.GattService( 1222): stop()
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428f92b8
W/BluetoothHidServiceJni( 1222): Cleaning up Bluetooth HID Interface...
I/bt-btif ( 1222): cleanup
W/bt-btif ( 1222): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1222): Cleaning up Bluetooth GID callback object
D/SapService( 1222): Received stop request...Stopping profile...
D/SapService( 1222): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 1222): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 1222): [BTUI] terminateSapManager
D/LgeBluetoothSimManager( 1449): [BTUI] SAP_DISABLE_EVT
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428f92b8
D/BluetoothAdapterService(1116705464)( 1222): Message: 1
D/BluetoothAdapterService(1116705464)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still running: com.broadcom.bt.service.sap.SapService
D/**BluetoothFTPService( 1222): Received stop request...Stopping profile...
D/**BluetoothFTPService( 1222): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 1222): closeFtpServerNative
I/bt-btif ( 1222): cleanup
D/bt-btif ( 1222): btif_disable_service: Current Services:0x120000
D/BluetoothAdapterService( 1222): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428f92b8
W/BluetoothHealthServiceJni( 1222): Cleaning up Bluetooth Health Interface...
I/bt-btif ( 1222): cleanup
D/bt-btif ( 1222): Process name (droid.bluetooth)
D/bt-btif ( 1222): btif_disable_service: Current Services:0x120000
D/bt-btif ( 1222): btif_hl_disable
D/bt-btif ( 1222): btif_hl_signal_select_exit
D/bt-btif ( 1222): select unblocked ret=1
D/bt-btif ( 1222): btif_hl_select_wake_signaled, signal ret=1
D/bt-btif ( 1222): btif_hl_select_wake_signaled
D/bt-btif ( 1222): btif_hl_select_wake_reset
D/bt-btif ( 1222): btif_hl_select_wake_signaled, signal:2
D/bt-btif ( 1222): hl thread cleanup
D/bt-btif ( 1222): Exit hl_select_thread for btif_hl_signal_select_exit
W/BluetoothHealthServiceJni( 1222): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 1222): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(1116705464)( 1222): Message: 1
D/BluetoothAdapterService(1116705464)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 1222): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1222): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(1116705464)( 1222): Message: 1
D/BluetoothAdapterService(1116705464)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothMapService( 1222): cleanup()
,D/BluetoothMapService( 1222): MAP Service closeService in
D/LGBluetoothMapAdapter( 1222): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1222): MAP Service closeService out
D/BluetoothAdapterService(1116705464)( 1222): Message: 1
D/BluetoothAdapterService(1116705464)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116705464)( 1222): Message: 1
,D/BluetoothAdapterService(1116705464)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1222): Profile still running: com.broadcom.bt.service.ftp.FTPService
W/BluetoothSAPServiceJni( 1222): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
I/bt-btif ( 1222): cleanup
D/bt-btif ( 1222): btif_disable_service: Current Services:0x100000
,W/BluetoothSAPServiceJni( 1222): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(1116705464)( 1222): Message: 1
D/BluetoothAdapterService(1116705464)( 1222): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1222): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 10, doUpdate = true
,D/BluetoothAdapterService( 1222): All profile services stopped...
D/BluetoothAdapterState( 1222): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 1222): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1222): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  967): Message: 60
D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  967): Broadcasting onBluetoothStateChange(false) to 12 receivers.
,I/BluetoothAdapterState( 1222): Entering OffState
D/BluetoothFTPService( 1222): cleanup FTP Service
V/BluetoothFTPServiceJni( 1222): closeFtpServerNative
I/bt-btif ( 1222): cleanup
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
V/BluetoothFTPServiceJni( 1222): cleanupNative
W/BluetoothFTPServiceJni( 1222): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 1222): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 1222): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 1222): cleanup done
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
D/BluetoothHeadset( 2628): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
D/BluetoothA2dp( 2628): onBluetoothStateChange: up=false
D/BluetoothHeadset(  967): onBluetoothStateChange: up=false
D/BluetoothMap( 2628): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 2628): onBluetoothStateChange: up=false
D/BluetoothA2dp(  967): onBluetoothStateChange: up=false
D/BluetoothPbap( 2628): onBluetoothStateChange: up=false
D/BluetoothManagerService(  967): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  967): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService(  967): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42f67840 mBinding = false
D/BluetoothManagerService(  967): Sending unbind request.
D/BluetoothAdapterService(1116705464)( 1222): onUnbind, calling cleanup
D/BluetoothAdapterService(1116705464)( 1222): cleanup()
D/BluetoothAdapterService( 1222): Cleaning up adapter native....
I/bluedroid( 1222): cleanup 1
I/bt-btif ( 1222): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 1222): GKI_destroy_task: GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/bt-btif ( 1222): btif_disassociate_evt: notify DISASSOCIATE_JVM
I/bt-btif ( 1222): HAL bt_hal_cbacks->thread_evt_cb
E/bt-gki  ( 1222): gki_pool_usage:  0: size     64 cur   0 max  11  total  48
E/bt-gki  ( 1222): gki_pool_usage:  1: size    288 cur   0 max   3  total  26
E/bt-gki  ( 1222): gki_pool_usage:  2: size    660 cur   0 max  24  total  45
E/bt-gki  ( 1222): gki_pool_usage:  3: size   4112 cur   0 max   3  total 200
E/bt-gki  ( 1222): gki_pool_usage:  4: size   8108 cur   0 max   0  total  20
E/bt-gki  ( 1222): pool:  4: not allocated
E/bt-gki  ( 1222): gki_pool_usage:  5: size    748 cur   0 max   0  total  64
,E/bt-gki  ( 1222): pool:  5: not allocated
E/bt-gki  ( 1222): gki_pool_usage:  6: size    268 cur   0 max   0  total  60
E/bt-gki  ( 1222): pool:  6: not allocated
E/bt-gki  ( 1222): gki_pool_usage:  7: size  10264 cur   0 max   0  total   2
E/bt-gki  ( 1222): pool:  7: not allocated
E/bt-gki  ( 1222): gki_pool_usage:  8: size    128 cur   3 max   3  total  30
E/bt-gki  ( 1222): gki_pool_usage:  9: size   8192 cur   0 max   0  total   5
E/bt-gki  ( 1222): pool:  9: not allocated
,D/bt-btif ( 1222): btif task exiting
I/GKI_LINUX( 1222): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1222): GKI_destroy_task: GKI_destroy_task(): task [BTIF] terminated
D/BluetoothManagerService(  967): Bluetooth State Change Intent: 13 -> 10
I/GKI_LINUX( 1222): GKI_destroy_task: GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1222): GKI_destroy_task: GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1222): GKI_destroy_task: GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1222): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 1222): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1222): GKI_exit_task: GKI_exit_task 0 done
D/bt-btif ( 1222): btif_shutdown_bluetooth done
I/BluetoothServiceJni( 1222): cleanupNative: return from cleanup
D/BluetoothAdapterService( 1222): Done cleaning up adapter native....
W/LGBluetoothServiceJni( 1222): Cleaning up Bluetooth Service callback object
D/LGBluetoothAPIService( 1154): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 1140): 1118567848: getState() :  mService = null. Returning STATE_OFF
,D/LGBluetoothAPIService( 1154): Message: 2
D/LGBluetoothAPIService( 1154): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@430ae630 mBinding = false
D/LGBluetoothAPIService( 1154): Sending unbind request.
E/LGBluetoothEventManager( 2628): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 2628): [BTUI] clear device connection state
D/LGBluetoothSettingsDBObserver( 1222): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapterService(1116705464)( 1222): cleanup() done
D/BluetoothAdapterService(1116705464)( 1222): ****onDestroy()********
,D/BtGatt.GattService( 1222): cleanup()
W/bt-btif ( 1222): GATTC Module not enabled/already disabled
W/bt-btif ( 1222): GATTS Module not enabled/already disabled
D/LGBluetoothAPIServer( 1222): [BTUI] onUnbind()
D/LGBluetoothAPIServer( 1222): [BTUI] cleanup() done
D/LGBluetoothAPIServer( 1222): [BTUI] onDestroy()
,W/ContextImpl( 2628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
V/BluetoothPbapReceiver( 1222): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1222): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1222): ***********state = 10
D/DockEventReceiver( 2628): finishStartingService: stopping service
D/BluetoothPermissionRequest( 2628): onReceive
E/LGBluetoothUtils( 2628): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/BluetoothDiscoverableTimeoutReceiver( 2628): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 2628): return without doing reset settings.
,D/LGBluetoothProfileConnectionReceiver( 2628): [BTUI] STATE_OFF : reset connected device information - BluetoothSettings
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 6591): [BTUI] STATE_OFF : reset connected device information EasySettings
,D/AuthorizationBluetoothService( 1558): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131101
D/WifiStateMachine(  967): processMsg: InitialState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4081): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4081): onReceive
,D/AppUp4:CustFacade( 4081): Context : android.app.ReceiverRestrictedContext@428e9520
D/AppUp4:CustFacade( 4081): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4081): isOpenOperator : true
,D/AppUp4:CustFacade( 4081): isPhone : true
,I/LicenseContentProvider( 3801): start selecting data
,D/SIMObserver( 3801): simInfo1
,I/AppUp4:EulaManager( 4081): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4081): begin check event
,I/AppUp4:CustModeStarterReceiver( 4081): Event For GoodConnectivity
,I/ActivityManager(  967): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6636 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/dalvikvm(  275): GC_EXPLICIT freed 46K, 34% free 16472K/24832K, paused 2ms+3ms, total 53ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+10ms, total 36ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 6636): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6636): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6636): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 28ms
,I/LGEmail ( 6636): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 6636): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,W/BaseRuntimeLoader( 6636): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6636): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6636): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6636): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 6636): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6636): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 6636): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4408): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4408): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4408): networkInfo.isConnected() = false
,W/linker  ( 6636): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 6636): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 6636): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 6636): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 6636): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 6636): register_HtmlEditor, Success
D/HtmlEditor( 6636): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 6636): register_HtmlEditorTimer, Success
D/HtmlEditor( 6636): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 6636): register_HtmlEditorDownloader, Success
D/HtmlEditor( 6636): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6636): register_HtmlEditorFont, Success
D/HtmlEditor( 6636): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6636): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 6636): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6636): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 6636): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6636): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 6636): JNI_OnLoad Success
I/HubEmail( 6636): JNI_OnLoad()
I/HubEmail( 6636): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6636): registerNatives()
I/HubEmail( 6636): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6636): registerNativeMethods()
,I/HubEmail( 6636): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 6636): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6670 uid=10052 gids={50052, 3003}
,I/ActivityManager(  967): Killing 5037:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 1 tasks}
,D/HyLog   ( 6670): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6670): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6670): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6670): [loadRssi] File not exist 
,V/LGRssiData( 6670): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6670): [loadFeatureFromXml] *** start feature loading from xml
,D/MobileConnectivityChangeReceiver( 6670): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/BaseRuntimeLoader( 6670): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6670): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 6670): onReceive CONNECTIVITY_CHANGE networkType=1
,W/BaseRuntimeLoader( 6670): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6670): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 6670): [getMatchedProfile] selected file : /cust/config/featureset.xml
,V/TelephonyAutoProfiling( 6670): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6670): [getValue] FEATURE key : vzw_roaming_state, value : null
,E/PhoneMonitor( 6670): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 6670): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6691 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 5311:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6691): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6691): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6691): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  967): GC_EXPLICIT freed 2890K, 49% free 29824K/57868K, paused 7ms+15ms, total 196ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6707 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  967): Killing 5357:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6707): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6707): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6707): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2882): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6607): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2882): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/ActivityManager(  967): Killing 5373:com.android.gallery3d/u0a27 (adj 15): empty #17
W/ContextImpl( 6607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4998): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/Wireless_Storage( 4998): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4998): intf.getDisplayName() = lo
I/Wireless_Storage( 4998): intf.getDisplayName() = sit0
,I/Wireless_Storage( 4998): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4998): intf.getDisplayName() = teql0
,I/Wireless_Storage( 4998): intf.getDisplayName() = wlan0
I/Wireless_Storage( 4998): intf.getDisplayName() = rev_rmnet8
,I/Wireless_Storage( 4998): intf.getDisplayName() = rev_rmnet2
I/Wireless_Storage( 4998): intf.getDisplayName() = rev_rmnet3
,I/Wireless_Storage( 4998): intf.getDisplayName() = rev_rmnet4
I/Wireless_Storage( 4998): intf.getDisplayName() = rev_rmnet5
,I/Wireless_Storage( 4998): intf.getDisplayName() = rev_rmnet6
,I/Wireless_Storage( 4998): intf.getDisplayName() = rev_rmnet7
,I/Wireless_Storage( 4998): intf.getDisplayName() = rev_rmnet0
,I/Wireless_Storage( 4998): intf.getDisplayName() = rev_rmnet1
I/Wireless_Storage( 4998): intf.getDisplayName() = rmnet0
,I/Wireless_Storage( 4998): intf.getDisplayName() = rmnet1
I/Wireless_Storage( 4998): intf.getDisplayName() = rmnet2
,I/Wireless_Storage( 4998): intf.getDisplayName() = rmnet3
I/Wireless_Storage( 4998): intf.getDisplayName() = rmnet4
,I/Wireless_Storage( 4998): intf.getDisplayName() = rmnet5
I/Wireless_Storage( 4998): intf.getDisplayName() = rmnet6
,I/Wireless_Storage( 4998): intf.getDisplayName() = rmnet7
,I/Wireless_Storage( 4998): CONNECT : WIFI_DISCONNECT
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6721 uid=10104 gids={50104, 3003, 1028, 1015}
,D/HyLog   ( 6721): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6721): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6721): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 6721): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/WebViewChromium( 6721): Binding Chromium to the main looper Looper (main, tid 1) {428cabd0}
,I/chromium( 6721): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6721): Initializing chromium process, renderers=0
,W/chromium( 6721): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6721): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6721): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6721): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6721): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6721): Remote Branch: 
I/Adreno-EGL( 6721): Local Patches: 
I/Adreno-EGL( 6721): Reconstruct Branch: 
,I/NSApplication( 6721): Starting up...
,I/ActivityManager(  967): Killing 1723:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,I/iu.Environment( 1854): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1854): num queued entries: 0
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335870 stackId=1, 1 tasks}
,I/iu.UploadsManager( 1854): num updated entries: 0
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/iu.SyncManager( 1854): NEXT; no task
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiP2pService(  967): P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  967): handleMessage: E msg.what=131089
,D/WifiStateMachine(  967): processMsg: InitialState
D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,I/GAV2    ( 6721): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
,W/ProcessCpuTracker(  967): Skipping unknown process pid 6768
,W/ProcessCpuTracker(  967): Skipping unknown process pid 6769
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512916459958445; DSPS: 40671183; Offset: 1452511675273953807
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512936461847760; DSPS: 41326605; Offset: 1452511675273951032
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512940041, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452512940056, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512956464102596; DSPS: 41982039; Offset: 1452511675273947567
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512976467991391; DSPS: 42637527; Offset: 1452511675273930112
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452512996469811122; DSPS: 43292946; Offset: 1452511675273949306
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513000043, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513000060, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513016471425490; DSPS: 43948359; Offset: 1452511675273946242
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513036473030534; DSPS: 44603772; Offset: 1452511675273933855
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513056475398808; DSPS: 45259209; Offset: 1452511675273952275
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513060058, nextTick: 59964, mDrawingTime: 5
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513060064, nextTick: 59967, mDrawingTime: 1
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513076477112238; DSPS: 45914626; Offset: 1452511675273926203
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513096478646865; DSPS: 46570036; Offset: 1452511675273934951
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513116480297274; DSPS: 47225450; Offset: 1452511675273937411
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513120028, nextTick: 60001, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513120047, nextTick: 59986, mDrawingTime: 0
,W/ProcessCpuTracker(  967): Skipping unknown process pid 6972
,W/ProcessCpuTracker(  967): Skipping unknown process pid 6973
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513136482160444; DSPS: 47880871; Offset: 1452511675273939009
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513156484105853; DSPS: 48536295; Offset: 1452511675273931293
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513176485802095; DSPS: 49191710; Offset: 1452511675273949068
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513180041, nextTick: 59985, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513180048, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513196487717452; DSPS: 49847133; Offset: 1452511675273941818
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513216489430153; DSPS: 50502549; Offset: 1452511675273945534
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513236491260458; DSPS: 51157969; Offset: 1452511675273944785
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513240033, nextTick: 59991, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513240039, nextTick: 59970, mDrawingTime: 8
,D/dalvikvm( 2685): GC_CONCURRENT freed 2312K, 33% free 16741K/24832K, paused 3ms+4ms, total 35ms
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513256493170189; DSPS: 51813392; Offset: 1452511675273931908
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513276495017422; DSPS: 52468812; Offset: 1452511675273948087
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513296496958873; DSPS: 53124236; Offset: 1452511675273936413
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513300044, nextTick: 59981, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513300048, nextTick: 59970, mDrawingTime: 6
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513316498876886; DSPS: 53779659; Offset: 1452511675273931818
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513336500748492; DSPS: 54435080; Offset: 1452511675273941852
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513356502382756; DSPS: 55090494; Offset: 1452511675273928167
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513360040, nextTick: 59980, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513360048, nextTick: 59978, mDrawingTime: 4
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513376504147905; DSPS: 55745912; Offset: 1452511675273923296
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513396506059981; DSPS: 56401334; Offset: 1452511675273943282
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513416507465181; DSPS: 57056740; Offset: 1452511675273944674
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513420053, nextTick: 59973, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513420057, nextTick: 59973, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513436509316371; DSPS: 57712161; Offset: 1452511675273934291
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513456514180895; DSPS: 58367680; Offset: 1452511675273946520
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513476515743856; DSPS: 59023091; Offset: 1452511675273953085
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513480041, nextTick: 59966, mDrawingTime: 10
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513480057, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513496517103119; DSPS: 59678496; Offset: 1452511675273939057
,I/ProcessStatsService(  967): Prepared write state in 62ms
,I/ProcessStatsService(  967): Pruning old procstats: /data/system/procstats/state-2016-01-10-09-42-00.bin
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513516518638580; DSPS: 60333906; Offset: 1452511675273948639
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513536520456020; DSPS: 60989326; Offset: 1452511675273935024
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513540056, nextTick: 59969, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513540058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513556522219763; DSPS: 61644744; Offset: 1452511675273928748
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513576524059912; DSPS: 62300164; Offset: 1452511675273937842
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452513596525358758; DSPS: 62955567; Offset: 1452511675273924432
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513600034, nextTick: 59971, mDrawingTime: 11
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452513600051, nextTick: 59977, mDrawingTime: 2
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7409): 
D/AndroidRuntime( 7409): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7409): CheckJNI is OFF
D/dalvikvm( 7409): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7409): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7409): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7409): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7409): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 7409): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 7409): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7409): failed to load memtrack module: -2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 7409): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
I/ActivityManager(  967): Killing 4749:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
I/MDM     (  967):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  967):   Force finishing activity ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  967): moveHomeStack:
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c8da48 stackId=0, 1 tasks}
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{430c5e88 u0 com.lge.launcher2/.Launcher t1} (in existing)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{430c5e88 u0 com.lge.launcher2/.Launcher t1}
D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{430c5e88 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c8da48 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{430c5e88 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{430c5e88 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{43dada00 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c8da48 stackId=0, 1 tasks}
I/WindowState(  967): WIN DEATH: Window{43d42ab8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  967): Client connection lost with reason: 4
I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PhoneApp( 1449): getIsInUseVoLTE : false
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{430c5e88 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{430c5e88 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
W/PackageSettings(  967): Skipping PackageSetting{42da0558 com.example.hello/10312} due to missing metadata
I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
I/[LGHome]EVENT( 1489): [Launcher.java:894:onPause()]onPause
D/WeatherAncestor( 1825): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:0:2
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{430c5e88 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{430c5e88 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/[LGHome]EVENT( 1489): [Launcher.java:4955:onStop()]onStop
I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/InputMethodManagerService(  967): IME STATUS OFF
W/InputMethodManagerService(  967): Got RemoteException sending setActive(false) notification to pid 4749 uid 10304
W/Binder  ( 1309): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1309): java.lang.NullPointerException
W/Binder  ( 1309): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1309): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1309): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1309): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c8da48 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
D/UpdateThreadPoolManager( 1825): 2 : This is isUpdating : false
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
E/SlideAside( 3771): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/SlideAside( 3771): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
D/dalvikvm( 1140): GC_CONCURRENT freed 5471K, 10% free 70846K/78224K, paused 6ms+16ms, total 76ms
D/dalvikvm( 1140): WAIT_FOR_CONCURRENT_GC blocked 70ms
W/System.err( 2685): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{430c5e88 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
D/WeatherService( 1825): 2 : shouldTimeTickRegistered : false
D/WeatherAncestor( 1825): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:0:3
W/System.err( 2685): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
D/WeatherService( 1825): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
W/System.err( 2685): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2685): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2685): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2685): 	at android.os.Handler.dispatchMessage(Handler.java:95)
D/WeatherService( 1825): 2 : shouldTimeTickRegistered : false
W/System.err( 2685): 	at android.os.Looper.loop(Looper.java:136)
W/GeofencerStateMachine( 1424): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "sms"
W/System.err( 2685): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2685): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2685): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2685): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2685): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2685): 	at dalvik.system.NativeStart.main(Native Method)
D/dalvikvm( 1489): GC_FOR_ALLOC freed 5569K, 9% free 60776K/66668K, paused 21ms, total 21ms
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
D/AppUp4:Utils( 4081): [getPackageName] uri : package:com.test.thalitest
D/AppUp4  ( 4081): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 4081):  isExcludedPackage  packagename = com.test.thalitest
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{430c5e88 u0 com.lge.launcher2/.Launcher t1} time:1923564
I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "smsto"
D/dalvikvm( 2697): GC_EXPLICIT freed 4021K, 28% free 17879K/24832K, paused 1ms+46ms, total 97ms
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/AppUp4  ( 4081):  isExcludedPackage TRUE : com.test.thalitest
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  967): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=7443 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/dalvikvm(  967): GC_EXPLICIT freed 1807K, 49% free 29837K/57868K, paused 5ms+14ms, total 167ms
D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 118ms
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
D/HyLog   ( 7443): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7443): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7443): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mms"
D/administrator(  967): Handling package changes for user 0
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/[BNRAppListMgrReceiver]( 7443): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
D/dalvikvm( 1140): GC_FOR_ALLOC freed 6497K, 14% free 68452K/79144K, paused 31ms, total 31ms
I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7460 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): Killing 5232:com.android.vending/u0a50 (adj 15): empty #17
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
D/HyLog   ( 7460): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7460): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7460): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  967): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7473 uid=10090 gids={50090}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c8da48 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
D/HyLog   ( 7473): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7473): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7473): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/InteractionManagerConfigurator(  967): updateIntentFilterConfig
I/InteractionManagerConfigurator(  967): com.test.thalitest isn't inclued in dragdropPackageList
D/BackupManagerService(  967): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  967): removePackageParticipantsLocked: uid=10304 #1
I/SystemConfig( 7460): BUILD Country: EU
I/SystemConfig( 7460): BUILD Operator: OPEN
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
I/LockScreenSettings( 7473): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/ActivityManager(  967): Killing 6567:com.lge.qremote/u0a96 (adj 15): empty #17
I/PackageChangeReceiver( 6636): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/VoicemailCleanupService( 1752): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7489 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c8da48 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1140): createShortcutInfo...
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1140): createShortcutInfo...
D/HyLog   ( 7489): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7489): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7489): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/SystemConfig( 7460): systemFeature RCS result false
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1140): createShortcutInfo...
D/SystemConfig( 7460): refreshRcsSupport() :false
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1140): createShortcutInfo...
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
D/KeyguardModel( 1140): handleShortcutListChanged...
D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1140): createShortcutInfo...
I/ActivityManager(  967): Killing 6526:com.lge.sync/1000 (adj 15): empty #17
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1140): createShortcutInfo...
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
D/KeyguardModel( 1140): handleShortcutListChanged...
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c8da48 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/dalvikvm(  967): GC_EXPLICIT freed 515K, 49% free 29871K/57868K, paused 4ms+11ms, total 263ms
I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@428cefd0 time:1923937
D/AndroidRuntime( 7409): Shutting down VM
D/dalvikvm( 7409): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/PackageIntentReceiver( 2628): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 2628): Receive package name : com.test.thalitest
I/ActivityManager(  967): Killing 6591:com.lge.settings.easy/1000 (adj 15): empty #17
D/HideNavigationAppsReceiver( 2628): Delete mPackageMame : com.test.thalitest
I/IcingCorporaProvider( 2697): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c8da48 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  967): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7504 uid=10073 gids={50073, 3003, 1028, 1015}
D/HyLog   ( 7504): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7504): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7504): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/IcingCorporaProvider( 2697): UpdateCorporaTask done [took 77 ms] updated apps [took 76 ms] 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/SQLiteDatabase( 7504): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 7504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 7504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 7504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 7504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7504): 	at ahn.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 7504): 	at ahi.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 7504): 	at ahi.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 7504): 	at azE.a(Suppliers.java:125)
E/SQLiteDatabase( 7504): 	at ahj.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 7504): threadid=11: thread exiting with uncaught exception (group=0x41891e48)
E/AndroidRuntime( 7504): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 7504): Process: com.google.android.apps.docs, PID: 7504
E/AndroidRuntime( 7504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/AndroidRuntime( 7504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/AndroidRuntime( 7504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 7504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/AndroidRuntime( 7504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 7504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7504): 	at ahn.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 7504): 	at ahi.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 7504): 	at ahi.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 7504): 	at azE.a(Suppliers.java:125)
E/AndroidRuntime( 7504): 	at ahj.run(AbstractDatabaseInstance.java:455)
I/Process ( 7504): Sending signal. PID: 7504 SIG: 9
E/DropBoxManagerService(  967): Can't write: system_app_crash
E/DropBoxManagerService(  967): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  967): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  967): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  967): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  967): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  967): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  967): 	... 5 more
I/ActivityManager(  967): Process com.google.android.apps.docs (pid 7504) has died.
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c8da48 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
E/SQLiteLog( 2685): (3850) statement aborts at 15: [INSERT INTO t001(f006,f003,f002,f005,f004) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2685): Error inserting f006=-1 f003= f002=1452513603869 f005=7504 f004=20
E/SQLiteDatabase( 2685): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2685): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2685): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:785)
E/SQLiteDatabase( 2685): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 2685): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2685): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
E/SQLiteDatabase( 2685): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1440)
E/SQLiteDatabase( 2685): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 2685): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 2685): 	at android.content.ContentResolver.insert(ContentResolver.java:1206)
E/SQLiteDatabase( 2685): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2406)
E/SQLiteDatabase( 2685): 	at com.lge.mlt.MltMonitorService.access$2500(MltMonitorService.java:38)
E/SQLiteDatabase( 2685): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3210)
E/SQLiteDatabase( 2685): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2685): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2685): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3313)

```
