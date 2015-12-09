#### Test 50650278d0426ce_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4585): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  964): Killing 4059:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4320d328 u0 com.android.settings/.UsbSettings t2}
,D/dalvikvm( 1554): GC_EXPLICIT freed 1183K, 29% free 17817K/24832K, paused 1ms+3ms, total 23ms
I/ConfigFetchService( 1964): fetch service done; releasing wakelock
I/ConfigFetchService( 1964): stopping self
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1964): GC_CONCURRENT freed 1537K, 22% free 19468K/24832K, paused 3ms+9ms, total 39ms
D/ChimeraCfgMgr( 1964): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1964): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/AndroidRuntime( 4635): 
D/AndroidRuntime( 4635): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4635): CheckJNI is OFF
D/dalvikvm( 4635): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4635): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4635): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4635): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4635): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4635): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1964): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1964): Loaded CLD2 Version V2.0 - 20141016
E/memtrack( 4635): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4635): failed to load memtrack module: -2
I/Icing   ( 1964): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4635): Calling main entry com.android.commands.am.Am
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4635
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (114 us)
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{4320d328 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  964): resumeTopActivityLocked: Pausing null
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  964): startService SlideAside
D/ActivityManager(  964): setFocusedStack: mFocusedStack=ActivityStack{43223d48 stackId=1, 2 tasks}
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/AndroidRuntime( 4635): Shutting down VM
D/UsbSettingsControl( 2576): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2576): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3751): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4635): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 3ms
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{4320d328 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{4320d328 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Restarting ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4656 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3751): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3751): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+2ms, total 26ms
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4656): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4656): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4656): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 18ms
V/WebViewChromium( 4656): Binding Chromium to the background looper Looper (main, tid 1) {427eb068}
I/chromium( 4656): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4656): Initializing chromium process, renderers=0
W/chromium( 4656): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4656): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4656): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4656): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4656): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4656): Remote Branch: 
I/Adreno-EGL( 4656): Local Patches: 
I/Adreno-EGL( 4656): Reconstruct Branch: 
I/dalvikvm( 4656): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4656): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4656): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4656): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4656): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4656): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4656): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4656): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4656): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4656): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4656): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4656): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4656): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4656): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4656): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4656): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4656): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4656): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4656): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4656): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4656): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4656): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4656): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4656): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4656): Enabling debug mode 0
,W/AwContents( 4656): nativeOnDraw failed; clearing to background color.
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +406ms
,W/AwContents( 4656): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  964): IME STATUS OFF
,I/ActivityManager( 4656): Timeline: Activity_idle id: android.os.BinderProxy@427ec748 time:105869
,D/JsMessageQueue( 4656): Set native->JS mode to OnlineEventsBridgeMode
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/dalvikvm( 4656): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427f0828
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4656): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427f0828
,D/jxcore_app_log( 4656): JniHelper::setJavaVM(0x416ad838), pthread_self() = 1631613952
,D/JX-Cordova( 4656): jxcore cordova android initializing
,I/dalvikvm( 4656): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
,W/dalvikvm( 4656): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4656): VFY: replacing opcode 0x6e at 0x0045
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3} time:106207
D/ActivityManager(  964): no-history finish of ActivityRecord{4320d328 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  964): Finishing activity token=Token{4320d490 ActivityRecord{4320d328 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{4320d328 u0 com.android.settings/.UsbSettings t2 f}
,D/UsbSettings( 2576): [AUTORUN] onStop()
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{4320d328 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{4320d328 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4656): GC_CONCURRENT freed 2788K, 12% free 21852K/24832K, paused 3ms+1ms, total 45ms
D/dalvikvm( 4656): GC_FOR_ALLOC freed 133K, 13% free 21833K/24832K, paused 27ms, total 27ms
D/dalvikvm( 4656): GC_FOR_ALLOC freed 301K, 12% free 21899K/24832K, paused 22ms, total 22ms
I/dalvikvm-heap( 4656): Grow heap (frag case) to 23.696MB for 143930-byte allocation
D/dalvikvm( 4656): GC_FOR_ALLOC freed 265K, 13% free 21935K/24976K, paused 22ms, total 22ms
I/dalvikvm-heap( 4656): Grow heap (frag case) to 23.800MB for 215890-byte allocation
D/dalvikvm( 4656): GC_FOR_ALLOC freed 368K, 13% free 22008K/25188K, paused 22ms, total 22ms
I/dalvikvm-heap( 4656): Grow heap (frag case) to 23.975MB for 323830-byte allocation
D/dalvikvm( 4656): GC_FOR_ALLOC freed 565K, 14% free 22130K/25508K, paused 23ms, total 23ms
I/dalvikvm-heap( 4656): Grow heap (frag case) to 24.248MB for 485740-byte allocation
D/dalvikvm( 4656): GC_FOR_ALLOC freed 862K, 15% free 22305K/25984K, paused 22ms, total 22ms
I/dalvikvm-heap( 4656): Grow heap (frag case) to 24.650MB for 728606-byte allocation
D/dalvikvm( 4656): GC_FOR_ALLOC freed 1278K, 16% free 22561K/26696K, paused 22ms, total 22ms
D/dalvikvm( 4656): GC_CONCURRENT freed 1676K, 15% free 22932K/26696K, paused 2ms+2ms, total 34ms
D/dalvikvm( 4656): WAIT_FOR_CONCURRENT_GC blocked 16ms
W/PluginManager( 4656): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
D/dalvikvm( 4656): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm( 4656): GC_FOR_ALLOC freed 365K, 15% free 22887K/26696K, paused 23ms, total 23ms
I/dalvikvm-heap( 4656): Grow heap (frag case) to 26.087MB for 1639352-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4656): GC_CONCURRENT freed 1669K, 18% free 23455K/28300K, paused 1ms+3ms, total 32ms
,D/dalvikvm( 4656): GC_FOR_ALLOC freed 1373K, 17% free 23536K/28300K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4656): Grow heap (frag case) to 27.502MB for 2459024-byte allocation
,D/dalvikvm( 4656): GC_CONCURRENT freed 217K, 16% free 25867K/30704K, paused 2ms+6ms, total 38ms
,D/dalvikvm( 4656): GC_CONCURRENT freed 4377K, 21% free 24508K/30704K, paused 2ms+4ms, total 36ms
D/dalvikvm( 4656): WAIT_FOR_CONCURRENT_GC blocked 31ms
I/dalvikvm-heap( 4656): Grow heap (frag case) to 29.625MB for 3688532-byte allocation
D/dalvikvm( 4656): GC_CONCURRENT freed 2930K, 26% free 25500K/34308K, paused 2ms+4ms, total 46ms
D/dalvikvm( 4656): GC_FOR_ALLOC freed 625K, 26% free 25445K/34308K, paused 23ms, total 24ms
W/jxcore-log( 4656): Initializing JXcore engine
W/jxcore-log( 4656): JXcore engine is ready
D/dalvikvm( 4656): GC_CONCURRENT freed 355K, 19% free 28063K/34308K, paused 2ms+1ms, total 25ms
D/dalvikvm( 4656): WAIT_FOR_CONCURRENT_GC blocked 20ms
W/jxcore-log( 4656): Starting JXcore engine
W/jxcore-log( 4656): Platform android
W/jxcore-log( 4656): 
W/jxcore-log( 4656): Process ARCH arm
W/jxcore-log( 4656): 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4656): JXcore Cordova bridge is ready!
I/jxcore-log( 4656): 
,W/jxcore-log( 4656): JXcore engine is started
,I/chromium( 4656): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4656): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4656): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/jxcore-log( 4656): Toggling radios to true
I/jxcore-log( 4656): 
,D/BluetoothManagerService(  964): Message: 20
,D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@449717c0:true
,D/BluetoothAdapter( 4656): enable(): BT is already enabled..!
,D/WifiStateMachine(  964): handleMessage: E msg.what=131145
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doBoolean: DISCONNECT
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2023): TDLS: Tear down peers
,D/wpa_supplicant( 2023): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4656): Radios toggled
I/jxcore-log( 4656): 
D/WifiService(  964): New client listening to asynchronous messages
D/WifiService(  964): setWifiEnabled: true pid=4656, uid=10304
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  964): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  964): disconnect pid=4656, uid=10304
D/WifiService(  964): reconnect pid=4656, uid=10304
,D/wpa_supplicant( 2023): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2023): wlan0: Deauthentication notification
D/wpa_supplicant( 2023): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2023): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2023): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2023): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2023): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb87b4d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2023): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2023): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
W/Settings(  964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131146
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiNative-wlan0(  964): doBoolean: RECONNECT
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2023): Fast associate: Old scan results
D/wpa_supplicant( 2023): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2023): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2023): wlan0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  964):    returned true
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147460
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection lost
D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
,D/DhcpStateMachine(  964): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  964): addressRemoved: 192.168.1.121/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
D/QCNEA   (  431): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  431): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  431): |CAC| updateNetCfgInfo
V/QCNEA   (  431): |CAC| *********************************************
V/QCNEA   (  431): |CAC|                   Netconfig               
V/QCNEA   (  431): |CAC| *********************************************
V/QCNEA   (  431): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  431): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  431): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  431): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  431): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  431): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  431): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  431): |CAC| *********************************************
D/QCNEA   (  431): |CAC| Received bssid= 
D/QCNEA   (  431): |CAC| net type = 3
V/QCNEA   (  431): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  431): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  431): |CAC| 	ssid           =NG700
V/QCNEA   (  431): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  431): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  431): |CAC| *********************************************
D/QCNEA   (  431): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  431): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  431): |CAC| dispatchNetCfg: updating:0xb7a6e8dc
D/QCNEA   (  431): |CAC| readCallback: read len:0, ret:-1, errno:11
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/Parcel  (  431): Reading a NULL string not supported here.
,E/Parcel  (  431): Reading a NULL string not supported here.
D/WifiHS20(  964): hidePasspointNotification off =false
D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
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
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4702 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  264): RouteController
,D/HyLog   ( 4702): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4702): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4702): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
W/NetworkManagementService(  964): route cmd failed: 
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
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x62808078 clazz=0x6c300001 iface=wlan0 mask=0x3
,D/QcConnectivityService(  964): resetConnections(wlan0, 3)
V/NativeCrypto( 1554): Read error: ssl=0x610c0d90: I/O error during system call, Connection timed out
V/NativeCrypto( 1554): SSL shutdown failed: ssl=0x610c0d90: I/O error during system call, Broken pipe
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,I/PCSuite ( 4702): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 4702): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4702): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4737 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  964): Killing 4138:com.google.android.talk/u0a77 (adj 15): empty #17
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4737): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4737): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4737): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4737): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4737): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4737): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4737): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4737): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4737): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4737): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4737): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4737): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 3109:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  964): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4585): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1554): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4023): onReceive
,D/AppUp4:CustFacade( 4023): Context : android.app.ReceiverRestrictedContext@427ff410
D/AppUp4:CustFacade( 4023): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4023): isOpenOperator : true
,D/AppUp4:CustFacade( 4023): isPhone : true
I/LicenseContentProvider( 2952): start selecting data
,D/SIMObserver( 2952): simInfo1
,I/AppUp4:EulaManager( 4023): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4023): begin check event
,I/AppUp4:CustModeStarterReceiver( 4023): Event For GoodConnectivity
,I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4766 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4766): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4766): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4766): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4766): DownloadService onCreate
,I/DownloadManager( 4766): in removeSpuriousFiles
D/EAS     ( 4566): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4566): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4766): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/eas_req ( 4566): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@42822cb0 on behalf of 4766
I/DownloadManager( 4766): in trimDatabase
V/DownloadManager( 4766): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@428269d0 on behalf of 4766
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2023): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 7 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 8 BSSID 34:36:3b:bd:89:28 SSID 'andilabs'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 2023): wlan0: New scan results available
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2023): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2023): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2023): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2023): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2023): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[4] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2023): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-51 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2023): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2023): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant(, 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2023): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87b65a8  current_ssid=0x0
D/wpa_supplicant( 2023): scard is not null..
D/wpa_supplicant( 2023): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2023): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2023): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2023): RSN: PMKSA cache search - network_ctx=0xb87b65a8 try_opportunistic=0
D/wpa_supplicant( 2023): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2023): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2023): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2023): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2023): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2023): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2023): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2023): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2023): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2023): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2023): nl80211: Unsubscribe mgmt frames handle 0xb87b5590 (mode change)
D/wpa_supplicant( 2023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb87b5590
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb87b5590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb87b5590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb87b5590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb87b5590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb87b5590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb87b5590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb87b5590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb87b5590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb87b5590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb87b5590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2023): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2023):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023):   * freq=2412
D/wpa_supplicant( 2023):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2023):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023):   * Auth Type 0
D/wpa_supplicant( 2023):   * WPA Versions 0x2
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 a0:c5:62:7a:49:97]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 34:36:3b:bd:89:28]
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2023): nl80211: Connect request send successfully
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2023): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
I/LgeMiscReceiver( 4324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
V/DownloadManager( 4766): DownloadService onStartCommand
I/LgeMiscReceiver( 4324): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4324): networkInfo.isConnected() = false
V/DownloadManager( 4766): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/linker  ( 4566): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4566): JNI_OnLoad
V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@4282a4c0 on behalf of 4766
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4566): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4566): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4566): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4566): register_HtmlEditor, Success
D/HtmlEditor( 4566): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4566): register_HtmlEditorTimer, Success
D/HtmlEditor( 4566): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4566): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4566): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4566): register_HtmlEditorFont, Success
D/HtmlEditor( 4566): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4566): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4566): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4566): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4566): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4566): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4566): JNI_OnLoad Success
I/HubEmail( 4566): JNI_OnLoad()
I/HubEmail( 4566): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4566): registerNatives()
I/HubEmail( 4566): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4566): registerNativeMethods()
I/HubEmail( 4566): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4566): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4766): DownloadService onDestroy
I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4793 uid=10052 gids={50052, 3003}
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2023): nl80211: Connect event
D/wpa_supplicant( 2023): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2023): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2023): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2023): wlan0: Association info event
D/wpa_supplicant( 2023): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2023): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2023): wlan0: freq=2412 MHz
D/wpa_supplicant( 2023): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2023): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2023): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2023): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): scard is not null..
D/wpa_supplicant( 2023): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2023): wlan0: WPA: Clear old PTK
D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): TDLS: Remove peers on association
I/ActivityManager(  964): Killing 3926:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2023): EAPOL: enable timer tick
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/HyLog   ( 4793): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4793): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4793): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4793): [loadRssi] File not exist 
V/LGRssiData( 4793): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4793): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4793): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4793): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4793): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4793): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 4793): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4793): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 4793): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4793): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4793): [getValue] FEATURE key : vzw_roaming_state, value : null
E/PhoneMonitor( 4793): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4793): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 1c 62 cd b7 23 50 a2 fb b7 9b 9c fa 8d 09 8c ...
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): 1c 62 cd b7 23 50 a2 fb b7 9b 9c fa 8d 09 8c 80 c1 24 60 e2 ff 62 9c 90 f6 05 d8 cc f9 97 70 29
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 1c 62 cd b7 23 50 a2 fb b7 9b 9c fa 8d 09 8c ...
D/wpa_supplicant( 2023): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2023): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2023): Get randomness: len=32 entropy=10
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2023): WPA: Renewed SNonce - hexdump(len=32): 0d ac 3a 63 0e d1 e2 e3 fc 45 10 b7 d6 c3 ec 17 ba 35 f1 01 f8 aa 20 04 1b a3 b0 70 de 80 6b b1
D/wpa_supplicant( 2023): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): WPA: Nonce1 - hexdump(len=32): 0d ac 3a 63 0e d1 e2 e3 fc 45 10 b7 d6 c3 ec 17 ba 35 f1 01 f8 aa 20 04 1b a3 b0 70 de 80 6b b1
D/wpa_supplicant( 2023): WPA: Nonce2 - hexdump(len=32): 1c 62 cd b7 23 50 a2 fb b7 9b 9c fa 8d 09 8c 80 c1 24 60 e2 ff 62 9c 90 f6 05 d8 cc f9 97 70 29
D/wpa_supplicant( 2023): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2023): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2023): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): 59 7a 15 61 cb be 6b f7 0e fa db 51 b7 c8 00 75
D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 0d ac 3a 63 0e d1 e2 e3 fc 45 10 b7 d6 c3 ec ...
D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 1c 62 cd b7 23 50 a2 fb b7 9b 9c fa 8d 09 8c ...
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): 1c 62 cd b7 23 50 a2 fb b7 9b 9c fa 8d 09 8c 80 c1 24 60 e2 ff 62 9c 90 f6 05 d8 cc f9 97 70 29
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 16 35 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): 47 bb ae a2 99 76 12 bf c0 ee cc f9 21 97 04 7c
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 1c 62 cd b7 23 50 a2 fb b7 9b 9c fa 8d 09 8c ...
D/wpa_supplicant( 2023): RSN: encrypted key data - hexdump(len=56): 5a 30 99 e2 57 d4 23 36 13 a8 0a ab bd ed f7 b2 9f 1e 5e bd 48 ed 1c 56 ab 8f f7 d7 5b 42 5e f5 ...
D/wpa_supplicant( 2023): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2023): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 01 ec ...
D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): 72 c3 05 88 d2 5e 48 b0 9f e2 97 fb 0f f8 30 bb
D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb87b5c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48
I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4810 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  964): Killing 4310:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2023): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2023): WPA: RSC - hexdump(len=6): 16 35 00 00 00 00
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f9003a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2023):    broadcast key
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
I/wpa_supplicant( 2023): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2023): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2023): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2023): EAPOL authentication completed successfully
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): Network connection established
D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2023): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  964): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-11ms what=147462 obj=android.net.wifi.StateChangeResult@44273f48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-7ms what=147462 obj=android.net.wifi.StateChangeResult@44e26040 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-7ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg:, L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2023): nl80211: survey data missing!
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/HyLog   ( 4810): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4810): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4810): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4825 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  964): Killing 4489:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4825): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4825): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4825): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2836): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/ActivityManager(  964): Killing 4525:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4838 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
,D/CommandListener(  264): Trying to bring up wlan0
,D/WifiStateMachine(  964): addressUpdated: 192.168.1.121/24 on wlan0 flags 128 scope 0
,V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  964): handleMessage: X
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4301a930 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4301a930 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.121/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/HyLog   ( 4838): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4838): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4838): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
,D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/LGDMSGCM( 4838): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): DHCP successful
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
,D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl( 4838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
,D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  964): handleMessage: X
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,E/BatteryObserver( 1157): usb Uevent not necessary.
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4852 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  964): Killing 4553:com.lge.bnr/1000 (adj 15): empty #17
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
,E/Parcel  (  431): Reading a NULL string not supported here.
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  964): GC_EXPLICIT freed 23199K, 49% free 29595K/57516K, paused 4ms+7ms, total 125ms
,D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  431): Reading a NULL string not supported here.
,E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/DhcpStateMachine(  964): DHCP request on wlan0
D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,V/        (  264): RouteController
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/HyLog   ( 4852): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4852): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4852): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/NFS     ( 4852): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4852): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4852): intf.getDisplayName() = lo
I/Wireless_Storage( 4852): intf.getDisplayName() = sit0
I/Wireless_Storage( 4852): intf.getDisplayName() = p2p0
,I/Wireless_Storage( 4852): intf.getDisplayName() = teql0
I/Wireless_Storage( 4852): intf.getDisplayName() = wlan0
D/NFS     ( 4852): interface name:wlan0 name:wlan0
D/NFS     ( 4852): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4852): interface name:wlan0 name:wlan0
D/NFS     ( 4852): addr:192.168.1.121 broadcast:192.168.1.255
,I/Wireless_Storage( 4852): CONNECT : WIFI_CONNECT
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4886 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 4187:com.android.contacts/u0a21 (adj 15): empty #17
,D/QCNEA   (  431): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  431): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  431): |CAC| updateNetCfgInfo
V/QCNEA   (  431): |CAC| *********************************************
V/QCNEA   (  431): |CAC|                   Netconfig               
V/QCNEA   (  431): |CAC| *********************************************
V/QCNEA   (  431): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  431): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  431): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  431): |CAC| 	NetConfig: ip4        =192.168.1.121
V/QCNEA   (  431): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  431): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  431): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  431): |CAC| *********************************************
D/QCNEA   (  431): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  431): |CAC| net type = 1
V/QCNEA   (  431): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  431): |CAC| Received ssid= NG700
V/QCNEA   (  431): |CAC| 	ssid           =NG700
V/QCNEA   (  431): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  431): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  431): |CAC| *********************************************
D/QCNEA   (  431): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  431): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  431): |CAC| dispatchNetCfg: updating:0xb7a6e8dc
,D/QCNEA   (  431): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4886): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4886): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4886): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1964): Checking schedule, now: 1449681211730 next: 1449681160448
,I/CheckinService( 1964): active receiver: enabled
,I/CheckinService( 1964): Preparing to send checkin request
,I/EventLogService( 1964): Accumulating logs since 1449681127760
,I/CheckinRequestBuilder( 1964): Checkin reason type: 8 attempt count: 1
,W/GAV2    ( 4886): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/ActivityThread( 1964): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,V/WebViewChromium( 4886): Binding Chromium to the main looper Looper (main, tid 1) {427e9540}
,I/chromium( 4886): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4886): Initializing chromium process, renderers=0
,W/CheckinRequestBuilder( 1964): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x42c25a08: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/chromium( 4886): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4886): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4886): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4886): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4886): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4886): Remote Branch: 
I/Adreno-EGL( 4886): Local Patches: 
I/Adreno-EGL( 4886): Reconstruct Branch: 
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4919 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/NSApplication( 4886): Starting up...
,D/HyLog   ( 4919): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4919): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4919): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): Killing 4203:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
,W/dalvikvm( 4919): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4919): VFY: replacing opcode 0x60 at 0x000b
,D/QRemote ( 4737): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4737): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 4919): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4919): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4919): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4919): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4919): install
I/MultiDex( 4919): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/QRemote ( 4737): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4737): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/MultiDex( 4919): loading existing secondary dex files
I/MultiDex( 4919): load found 3 secondary dex files
D/QRemote ( 4737): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/MultiDex( 4919): install done
I/QRemote ( 4737): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/PCSuite ( 4702): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 4702): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 4737): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 4737): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4737): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 4737): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/dalvikvm( 4919): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4919): VFY: unable to resolve instance field 61
D/dalvikvm( 4919): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4919): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4919): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4919): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4919): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4919): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4919): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4919): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4919): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
D/dalvikvm( 4919): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427f08c8
D/dalvikvm( 4919): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427f08c8
D/dalvikvm( 4919): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427f08c8, skipping init
D/dalvikvm( 4919): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427f08c8
D/dalvikvm( 4919): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427f08c8
V/JNIHelp ( 4919): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.445633 Y: -0.393967 Z: 9.760117 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445633 .y:-0.393967 .z:9.760117
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/dalvikvm( 4919): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427f08c8
,D/dalvikvm( 4919): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x427f08c8
D/dalvikvm( 4919): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427f08c8
,D/dalvikvm( 4919): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427f08c8
,I/ProviderInstaller( 4919): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1554): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1554): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1964): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.468674 Y: -0.402237 Z: 9.750504 
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.457748 Y: -0.395691 Z: 9.750504 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.468674 .y:-0.402237 .z:9.750504
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/WearableService( 1836): callingUid 10006, callindPid: 1836
,E/MDM     ( 1424): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1964): Restart initialization of location
,I/dalvikvm( 4919): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4919): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4919): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4919): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4919): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4919): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e9a000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e9a000
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
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=3783909462
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4919): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4297cf08
D/dalvikvm( 4919): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4297cf08
,D/dalvikvm( 4919): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4297cf08, skipping init
,D/wpa_supplicant( 2023): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2023): EAPOL: disable timer tick
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::OpenSession
D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 2
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 2
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 2
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=2975187326
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 2
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 2
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  964): handleMessage: X
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.121
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,D/dalvikvm( 4919): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4964): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4919): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4919): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 65ms
,I/Adreno-EGL( 4919): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4919): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4919): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4919): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4919): Remote Branch: 
I/Adreno-EGL( 4919): Local Patches: 
I/Adreno-EGL( 4919): Reconstruct Branch: 
,I/Adreno-EGL( 4919): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4919): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4919): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4919): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4919): Remote Branch: 
I/Adreno-EGL( 4919): Local Patches: 
I/Adreno-EGL( 4919): Reconstruct Branch: 
,I/Adreno-EGL( 4919): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4919): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4919): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4919): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4919): Remote Branch: 
I/Adreno-EGL( 4919): Local Patches: 
I/Adreno-EGL( 4919): Reconstruct Branch: 
,W/Settings( 4919): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1964): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1964): Sending checkin request (11459 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1225): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/CheckinRequestBuilder( 1964): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1964): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x43168d38: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1964): awaiting user notification for token
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1964): Classify the device as Phone.
,I/CheckinTask( 1964): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1964): Checking schedule, now: 1449681213826 next: 1450258609822
,I/CheckinService( 1964): active receiver: disabled
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1554): Connected
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1554): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  431): Reading a NULL string not supported here.
,E/Parcel  (  431): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4023): onReceive
,D/AppUp4:CustFacade( 4023): Context : android.app.ReceiverRestrictedContext@427ff410
,D/AppUp4:CustFacade( 4023): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4023): isOpenOperator : true
,D/AppUp4:CustFacade( 4023): isPhone : true
,I/jxcore-log( 4656): Test app app.js loaded
I/jxcore-log( 4656): 
,I/LicenseContentProvider( 2952): start selecting data
,D/SIMObserver( 2952): simInfo1
,I/Choreographer( 4656): Skipped 394 frames!  The application may be doing too much work on its main thread.
,I/AppUp4:EulaManager( 4023): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4023): begin check event
I/AppUp4:CustModeStarterReceiver( 4023): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4023): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4023): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4023): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4023): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4023): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4566): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4766): DownloadService onCreate
,D/EAS     ( 4566): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4566): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
I/chromium( 4656): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/DownloadManager( 4766): in removeSpuriousFiles
V/DownloadManager( 4766): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@42830358 on behalf of 4766
I/DownloadManager( 4766): in trimDatabase
,V/DownloadManager( 4766): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4324): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4324): networkInfo.isConnected() = false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/MobileConnectivityChangeReceiver( 4793): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4793): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4566): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
,V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@42831590 on behalf of 4766
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4766): DownloadService onStartCommand
V/DownloadManager( 4766): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2836): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@42833f00 on behalf of 4766
,D/LGDMClient( 2836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4838): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ContextImpl( 4838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/DownloadManager( 4766): DownloadService onDestroy
I/LGDMClient( 2836): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4852): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4852): CONNECT : WIFI_CONNECT
E/LGDMClient( 2836): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2836): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2836): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2836): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] request level :IDLE....
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/AppUp4:CustModeStarterReceiver( 4023): onReceive
D/AppUp4:CustFacade( 4023): Context : android.app.ReceiverRestrictedContext@427ff410
D/AppUp4:CustFacade( 4023): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4023): isOpenOperator : true
,D/AppUp4:CustFacade( 4023): isPhone : true
,I/LicenseContentProvider( 2952): start selecting data
,D/SIMObserver( 2952): simInfo1
,I/AppUp4:EulaManager( 4023): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4023): begin check event
,I/AppUp4:CustModeStarterReceiver( 4023): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4766): DownloadService onCreate
,I/DownloadManager( 4766): in removeSpuriousFiles
,V/DownloadManager( 4766): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4566): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4566): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@42838588 on behalf of 4766
,I/DownloadManager( 4766): in trimDatabase
,V/DownloadManager( 4766): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@42839ef8 on behalf of 4766
,V/DownloadManager( 4766): DownloadService onStartCommand
,V/DownloadManager( 4766): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@4283bc30 on behalf of 4766
,I/LgeMiscReceiver( 4324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4324): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4324): networkInfo.isConnected() = true
,D/PhoneState( 4324): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4793): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/DownloadManager( 4766): DownloadService onDestroy
D/MobileConnectivityChangeReceiver( 4793): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4566): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2836): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4838): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2836): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 4852): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4852): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2836): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2836): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2836): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2836): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm(  964): GC_EXPLICIT freed 2256K, 49% free 29497K/57516K, paused 2ms+5ms, total 83ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-6ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4023): onReceive
,D/AppUp4:CustFacade( 4023): Context : android.app.ReceiverRestrictedContext@427ff410
,D/AppUp4:CustFacade( 4023): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4023): isOpenOperator : true
,D/AppUp4:CustFacade( 4023): isPhone : true
,I/LicenseContentProvider( 2952): start selecting data
,D/SIMObserver( 2952): simInfo1
,I/AppUp4:EulaManager( 4023): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4023): begin check event
,I/AppUp4:CustModeStarterReceiver( 4023): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4566): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4766): DownloadService onCreate
,D/EAS     ( 4566): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4324): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4324): networkInfo.isConnected() = true
,D/PhoneState( 4324): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4793): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4793): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2836): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4838): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4852): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4852): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 4766): in removeSpuriousFiles
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4766): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@4283fea8 on behalf of 4766
I/LGDMClient( 2836): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/Settings( 4566): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DownloadManager( 4766): in trimDatabase
V/DownloadManager( 4766): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@428410e0 on behalf of 4766
E/LGDMClient( 2836): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2836): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2836): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2836): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4766): DownloadService onStartCommand
V/DownloadManager( 4766): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4766): created cursor android.database.sqlite.SQLiteCursor@42843a50 on behalf of 4766
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
V/DownloadManager( 4766): DownloadService onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 4886): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  964): Killing 4585:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1225): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/WifiController(  964): battery changed pluggedType: 2
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1225): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  964): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/Finsky  ( 4223): [399] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4223): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  964): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
D/WifiController(  964): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/WifiController(  964): battery changed pluggedType: 2
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1461): GC_CONCURRENT freed 1540K, 7% free 25440K/27280K, paused 4ms+3ms, total 35ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "sms"
,E/SlideAside( 3751): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,D/administrator(  964): Handling package changes for user 0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5076 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+3ms, total 46ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 3751): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+4ms, total 32ms
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 24ms
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "mmsto"
D/HyLog   ( 5076): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5076): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5076): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
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
,I/Babel   ( 5076): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5076): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5076): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5076): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5076): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/Babel   ( 5076): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 5076): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5076): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5076): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5076): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5076): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5076): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5076): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5076): MmsConfig.loadFromResources
,E/Babel   ( 5076): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5076): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5076): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5076): [loadRssi] File not exist 
V/LGRssiData( 5076): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5076): [loadFeatureFromXml] *** start feature loading from xml
D/AppUp4:Utils( 4023): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4023): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4023): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/TelephonyAutoProfiling( 5076): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5076): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5076): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:CustModeStarterReceiver( 4023): onReceive
D/AppUp4:CustFacade( 4023): Context : android.app.ReceiverRestrictedContext@427ff410
D/AppUp4:CustFacade( 4023): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4023): isOpenOperator : true
,D/AppUp4:CustFacade( 4023): isPhone : true
,I/LicenseContentProvider( 2952): start selecting data
,D/SIMObserver( 2952): simInfo1
,V/GmsNetworkLocationProvi( 1424): DISABLE
I/AppUp4:EulaManager( 4023): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4023): begin check event
D/AppUp4:Utils( 4023): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4023): Event For Nothing, skip.
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5126 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5126): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5126): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5126): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5126): BUILD Country: EU
,I/SystemConfig( 5126): BUILD Operator: OPEN
,D/LocationProviderProxy(  964): applying state to connected service
,I/ActivityManager(  964): Killing 4702:com.lge.sync/1000 (adj 15): empty #17
D/LocationProviderProxy(  964): applying state to connected service
I/SystemConfig( 5126): systemFeature RCS result false
D/SystemConfig( 5126): refreshRcsSupport() :false
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5140 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  964): Killing 4737:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
,D/HyLog   ( 5140): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5140): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5140): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  964): Killing 4766:android.process.media/u0a23 (adj 15): empty #17
I/IcingCorporaProvider( 2647): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1964): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1964): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  964): Delaying start of: ServiceRecord{4308bab8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1964): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1964): GC_CONCURRENT freed 1953K, 22% free 19557K/24832K, paused 2ms+5ms, total 44ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2647): UpdateCorporaTask done [took 238 ms] updated apps [took 238 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.472580 Y: -0.417313 Z: 9.780014 
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.454834 Y: -0.374023 Z: 9.757828 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.472580 .y:-0.417313 .z:9.780014
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.454727 Y: -0.388123 Z: 9.755493 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454727 .y:-0.388123 .z:9.755493
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.430328 Y: -0.384247 Z: 9.768509 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.430328 .y:-0.384247 .z:9.768509
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV4    ( 5076): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1157): GC_CONCURRENT freed 2886K, 11% free 25448K/28512K, paused 30ms+2ms, total 81ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
E/Parcel  (  431): Reading a NULL string not supported here.
,E/Parcel  (  431): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PowerManagerService(  964): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  964): [updateScreenState] screen on = false
D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  964): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9025 usec
,D/qcom_sensors_hal(  964): hal_acquire_resources
,I/qcom_sensors_hal(  964): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  964): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  964): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  964): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  964): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  964): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  964): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.454437 Y: -0.384079 Z: 9.767822 
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.445511 Y: -0.405258 Z: 9.748871 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.454437 .y:-0.384079 .z:9.767822
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.451569 Y: -0.400742 Z: 9.768387 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451569 .y:-0.400742 .z:9.768387
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Sensors (  405): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  964): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  964): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  964): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  964): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  964): proximitySensorChanged  positive = true
I/KnockOnPowerController(  964): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.470947 Y: -0.393250 Z: 9.789459 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470947 .y:-0.393250 .z:9.789459
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.461685 Y: -0.386368 Z: 9.777512 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461685 .y:-0.386368 .z:9.777512
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.461960 Y: -0.378891 Z: 9.761566 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461960 .y:-0.378891 .z:9.761566
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.464294 Y: -0.388397 Z: 9.767288 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464294 .y:-0.388397 .z:9.767288
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  964): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44803960)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  964): **** SHOWN CALLED ****
I/WindowManager(  964): No lock screen! windowToken=null
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb7632450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.451660 Y: -0.395874 Z: 9.783936 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451660 .y:-0.395874 .z:9.783936
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  964): handleScreenStateChanged: true
,D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  964): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiOffDelayIfNotUsed(  964): stopMonitoring
D/WifiStateMachine(  964): handleMessage: E msg.what=131127
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=132097
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  964): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2023): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2023): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  964): handleMessage: X
E/Parcel  (  431): Reading a NULL string not supported here.
,E/Parcel  (  431): Reading a NULL string not supported here.
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=on
,E/SlideAside( 3751): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WeatherAncestor( 1890): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:13:57
,I/SlideAside( 3751): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{427ea820 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1890): 2 : This is isUpdating : false
,D/WeatherAncestor( 1890): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:13:57
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1890): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1890): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1890): 2 : shouldTimeTickRegistered : false
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/qdlights( 1157): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 225, B = 225
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1157): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  964): Excessive delay in blankDisplay() while turning screen off: 409ms
,D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681237967, nextTick: 2064, mDrawingTime: 1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681237985, nextTick: 2047, mDrawingTime: 0
D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/WeatherService( 1890): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:13:58
,D/WeatherService( 1890): 2 : ACTION screen on
,D/WeatherService( 1890): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1890): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:13:58
D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
,E/Parcel  (  431): Reading a NULL string not supported here.
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3}
D/qcom_sensors_hal(  964): hal_acquire_resources
D/qcom_sensors_hal(  964): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  964): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  964): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5206
,D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
W/ProcessCpuTracker(  964): Skipping unknown process pid 5207
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5213
D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  964): Vibrator off
D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
,D/UsbSettings( 2576): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/WifiStateMachine(  964): handleScreenStateChanged: false
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
,D/WifiStateMachine(  964): processMsg: ConnectedState
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{4320d328 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/WifiStateMachine(  964): processMsg: L2ConnectedState
V/UsbSettings( 2576): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
D/WifiStateMachine(  964): handleMessage: X
V/UsbSettings( 2576): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2576): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
,D/KeyguardViewManager( 1142): onScreenTurnedOff()
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{44ec5fa0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1157): clear
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): handleMessage: X
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{4320d328 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
,D/WeatherService( 1890): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:13:58
D/WeatherService( 1890): 2 : ACTION screen off
,D/WeatherService( 1890): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:13:58
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,D/NfcService( 1474): NFC-C OFF
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
,D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  405): sns_pwr.c(320):releasing wakelock
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681240036, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681240062, nextTick: 59970, mDrawingTime: 0
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681256218439429; DSPS: 5281241; Offset: 1449681095047754615
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1225): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1554): Vacuum at: now=1449681268379 tag=VacuumService
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681276219990567; DSPS: 5936652; Offset: 1449681095047749357
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681296221644154; DSPS: 6592066; Offset: 1449681095047754994
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681300036, nextTick: 59966, mDrawingTime: 12
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681300055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681316223285813; DSPS: 7247480; Offset: 1449681095047748704
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681336225135805; DSPS: 7902901; Offset: 1449681095047737124
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681356226875536; DSPS: 8558318; Offset: 1449681095047737353
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681360020, nextTick: 59973, mDrawingTime: 17
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681360064, nextTick: 59968, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681376228211467; DSPS: 9213721; Offset: 1449681095047761028
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681396229781667; DSPS: 9869133; Offset: 1449681095047744314
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 7 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 3 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 8 BSSID 34:36:3b:bd:89:28 SSID 'andilabs' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 a0:c5:62:7a:49:97]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 34:36:3b:bd:89:28]
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681416232178900; DSPS: 10524571; Offset: 1449681095047761176
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681420030, nextTick: 59987, mDrawingTime: 11
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681420065, nextTick: 59968, mDrawingTime: 0
,I/EventLogService( 1964): Aggregate from 1449681211760 (log), 1449679569034 (data)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 2631): GC_CONCURRENT freed 7743K, 33% free 16862K/24832K, paused 2ms+2ms, total 39ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  964): GC_EXPLICIT freed 2595K, 49% free 29774K/57516K, paused 6ms+15ms, total 189ms
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1554): GC_EXPLICIT freed 1297K, 29% free 17845K/24832K, paused 6ms+6ms, total 62ms
,W/GLSActivity( 1554): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1554): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1554): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1554): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1554): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4223): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4223): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4223): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4223): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4223): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4223): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4223): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4223): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x44da6970: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/System  ( 4223): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4223): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681436233594309; DSPS: 11179978; Offset: 1449681095047742259
,I/LocationManagerService(  964): remove 432ad478
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2631): GC_CONCURRENT freed 1600K, 31% free 17309K/24832K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 2631): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 2631): GC_FOR_ALLOC freed 1706K, 31% free 17261K/24832K, paused 22ms, total 23ms
,I/Mlt MonitorService( 2631): parseLastkmsg to dump
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681456235251228; DSPS: 11835392; Offset: 1449681095047751228
,I/jxcore-log( 4656): TAP version 13
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # multiplex can send data
I/jxcore-log( 4656): 
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681476237107626; DSPS: 12490813; Offset: 1449681095047746054
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 1 String should be length:200
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681480046, nextTick: 59964, mDrawingTime: 11
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681480059, nextTick: 59973, mDrawingTime: 0
,I/jxcore-log( 4656): # basic
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 2 sane
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # another
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 3 sane
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 4 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 5 null
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 6 (unnamed assert)
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 7 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 8 should not throw
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 9 (unnamed assert)
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 10 (unnamed assert)
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 11 should not throw
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 12 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 13 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 14 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # failed to get mobile documents path
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 15 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 16 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 17 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 18 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #init should register the networkChanged event
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 19 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #startBroadcasting should throw on null device name
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 20 should throw
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 21 should throw
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 22 should throw
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #startBroadcasting should throw on NaN port
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 23 should throw
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #startBroadcasting should throw on negative port
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 24 should throw
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #startBroadcasting should throw on too large port
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 25 should throw
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 26 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 27 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 28 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 29 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 30 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 31 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 32 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 33 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 34 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 35 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 36 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 37 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 38 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 39 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 40 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 41 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 42 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681496238948348; DSPS: 13146233; Offset: 1449681095047755722
,I/jxcore-log( 4656): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 43 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 44 should be equal
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681496619.4656
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496619.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
,D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:4
D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/LGBluetoothServiceAdapter( 1225): [BTUI] createSocketChannel FD=97 mFd=95
,D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
,D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:9 handle:0x84
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496619.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496619.4656"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363631392e34363536227dc027
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363631392e34363536227dc027'
,D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363631390634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363631390634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
,D/WifiNative-p2p0(  964):    returned true
D/WifiP2pService(  964): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6679213 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6679213 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
,D/WifiP2pService(  964): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
,D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
,D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
D/WifiP2pService(  964): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 4656): start: OK
I/jxcore-log( 4656): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
D/bt-btif ( 1225): cleanup slot:4, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a124, p_pcb->port_handle:9
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a124, user:4, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:4
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 2023): P2P: Running p2p_scan
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
,D/WifiNative-p2p0(  964):    returned true
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/WifiP2pService(  964): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
,I/jxcore-log( 4656): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681496744.4656
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiP2pService(  964): InactiveState{ when=-6ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService(  964): P2pEnabledState{ when=-9ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState clear service
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496744.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:5
D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:10 handle:0x84
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363631390634363536227d0a636f72646f7661703270c00c001001
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363631390634363536227d0a636f72646f7661703270c00c001001'
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496744.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496744.4656"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 4656): start: OK
,I/jxcore-log( 4656): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
,I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
,D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
D/bt-btif ( 1225): cleanup slot:5, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
I/bt-btif ( 1225): BTA_JvDeleteRecord
,D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
,D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a138, p_pcb->port_handle:10
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a138, user:5, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:5
,D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
D/WifiP2pService(  964): remove client information from framework
,D/WifiP2pService(  964): InactiveState{ when=-49ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
I/jxcore-log( 4656): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681496794.4656
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService(  964): P2pEnabledState{ when=-56ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiP2pService(  964): P2pEnabledState clear service request
,D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496794.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiNative-p2p0(  964):    returned true
,W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:6
D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:11 handle:0x84
D/WifiP2pService(  964): InactiveState{ when=-66ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363734342e34363536227dc027
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363734342e34363536227dc027'
D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363734340634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363734340634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496794.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496794.4656"}", service type: "Cordovap2p._tcp"
D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: p2p_scan is already running
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
,D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
D/wpa_supplicant( 2023): P2P: Could not start p2p_scan at this point - will try again after previous scan completes
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH_WHEN_READY
,D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 4656): start: OK
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363734340634363536227d0a636f72646f7661703270c00c001001
,I/jxcore-log( 4656): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363734340634363536227d0a636f72646f7661703270c00c001001'
I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
D/bt-btif ( 1225): cleanup slot:6, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
,I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a14c, p_pcb->port_handle:11
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a14c, user:6, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:6
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/WifiNative-p2p0(  964):    returned true
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiP2pService(  964): InactiveState{ when=-43ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@db1327d5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-45ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@db1327d5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
D/WifiP2pService(  964): add a new client
D/WifiP2pService(  964): InactiveState{ when=-43ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-44ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-35ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-36ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service
D/WifiP2pService(  964): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
I/jxcore-log( 4656): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
,D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH_WHEN_READY)
,I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH_WHEN_READY -> IDLE
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681496831.4656
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363739342e34363536227dc027
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363739342e34363536227dc027'
D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363739340634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363739340634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
,D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
,D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: p2p_scan is already running
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
,D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
D/wpa_supplicant( 2023): P2P: Could not start p2p_scan at this point - will try again after previous scan completes
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH_WHEN_READY
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/WifiNative-p2p0(  964):    returned true
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService(  964): InactiveState{ when=-39ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-40ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
D/WifiP2pService(  964): InactiveState{ when=-40ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-18ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-18ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast false
D/WifiP2pService(  964): InactiveState{ when=-9ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d7d61a0b target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-9ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d7d61a0b target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
D/WifiP2pService(  964): add a new client
D/WifiP2pService(  964): InactiveState{ when=-10ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-10ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast true
D/WifiP2pService(  964): InactiveState{ when=-11ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496831.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
,D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363739340634363536227d0a636f72646f7661703270c00c001001
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363739340634363536227d0a636f72646f7661703270c00c001001'
D/WifiNative-p2p0(  964):    returned true
,W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
,E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH_WHEN_READY)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH_WHEN_READY -> IDLE
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:7
D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:12 handle:0x84
,D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496831.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496831.4656"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363833312e34363536227dc027
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363833312e34363536227dc027'
D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
D/WifiP2pService(  964): P2pEnabledState{ when=-12ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service
D/WifiP2pService(  964): remove client information from framework
D/WifiP2pService(  964): InactiveState{ when=-14ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-14ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
D/WifiP2pService(  964): InactiveState{ when=-14ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-13ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-13ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast false
D/WifiP2pService(  964): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@de65321b target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@de65321b target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
,D/WifiP2pService(  964): add a new client
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363833310634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 4656): start: OK
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363833310634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiNative-p2p0(  964):    returned true
,I/jxcore-log( 4656): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
,D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: p2p_scan is already running
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/bt-btif ( 1225): cleanup slot:7, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
I/bt-btif ( 1225): BTA_JvDeleteRecord
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
I/bt-btif ( 1225): BTA_JvRfcommStopServer
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a160, p_pcb->port_handle:12
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a160, user:7, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:7
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
D/wpa_supplicant( 2023): P2P: Could not start p2p_scan at this point - will try agai,n after previous scan completes
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH_WHEN_READY
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
I/jxcore-log( 4656): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
D/WifiNative-p2p0(  964):    returned true
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681496855.4656
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363833310634363536227d0a636f72646f7661703270c00c001001
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363833310634363536227d0a636f72646f7661703270c00c001001'
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/WifiP2pService(  964): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast true
D/WifiP2pService(  964): InactiveState{ when=-3ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-3ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service
D/WifiP2pService(  964): remove client information from framework
D/WifiP2pService(  964): InactiveState{ when=-5ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-5ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
,D/WifiP2pService(  964): InactiveState{ when=-5ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH_WHEN_READY)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH_WHEN_READY -> IDLE
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
,D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496855.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:8
D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
,D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:13 handle:0x84
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496855.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496855.4656"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  964): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast false
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363835352e34363536227dc027
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 4656): start: OK
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363835352e34363536227dc027'
D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363835350634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363835350634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
,D/WifiNative-p2p0(  964):    returned true
I/jxcore-log( 4656): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
D/bt-btif ( 1225): cleanup slot:8, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
I/bt-btif ( 1225): BTA_JvDeleteRecord
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a174, p_pcb->port_handle:13
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a174, user:8, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:8
,D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: p2p_scan is already running
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
,D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
D/wpa_supplicant( 2023): P2P: Could not start p2p_scan at this point - will try again after previous scan completes
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH_WHEN_READY
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
,D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/jxcore-log( 4656): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363835350634363536227d0a636f72646f7661703270c00c001001
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363835350634363536227d0a636f72646f7661703270c00c001001'
,D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH_WHEN_READY)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH_WHEN_READY -> IDLE
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
D/WifiP2pService(  964): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3537ff8f target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3537ff8f target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
D/WifiP2pService(  964): add a new client
D/WifiP2pService(  964): InactiveState{ when=-2ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-2ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast true
D/WifiP2pService(  964): InactiveState{ when=-2ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-3ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service
D/WifiP2pService(  964): remove client information from framework
D/WifiP2pService(  964): InactiveState{ when=-4ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-4ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
,D/WifiP2pService(  964): InactiveState{ when=-5ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0(  964):    returned true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681496878.4656
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496878.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
D/WifiP2pService(  964): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): discovery change broadcast false
E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:9
D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:14 handle:0x84
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496878.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496878.4656"}", service type: "Cordovap2p._tcp"
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363837382e34363536227dc027
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363837382e34363536227dc027'
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363837380634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363837380634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 4656): start: OK
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: p2p_scan is already running
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
D/wpa_supplicant( 2023): P2P: Could not start p2p_scan at this point - will try again after previous scan completes
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH_WHEN_READY
,D/WifiNative-p2p0(  964):    returned true
,I/jxcore-log( 4656): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
D/WifiP2pService(  964): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5c699845 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5c699845 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
D/WifiP2pService(  964): add a new client
D/WifiP2pService(  964): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
D/bt-btif ( 1225): cleanup slot:9, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
,I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a188, p_pcb->port_handle:14
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a188, user:9, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:9
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363837380634363536227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363837380634363536227d0a636f72646f7661703270c00c001001'
D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH_WHEN_READY)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH_WHEN_READY -> IDLE
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 4656): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
D/WifiNative-p2p0(  964):    returned true
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681496905.4656
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
D/WifiP2pService(  964): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service
D/WifiP2pService(  964): remove client information from framework
D/WifiP2pService(  964): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
D/WifiP2pService(  964): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496905.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:10
D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:15 handle:0x84
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496905.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496905.4656"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 4656): start: OK
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363930352e34363536227dc027
I/jxcore-log( 4656): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
,D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
D/bt-btif ( 1225): cleanup slot:10, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
I/bt-btif ( 1225): BTA_JvDeleteRecord
I/bt-btif ( 1225): BTA_JvRfcommStopServer
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a19c, p_pcb->port_handle:15
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a19c, user:10, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:10
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363930352e34363536227dc027'
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
D/WifiP2pService(  964): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@96d1b317 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@96d1b317 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
,D/WifiP2pService(  964): add a new client
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363930350634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363930350634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
D/WifiNative-p2p0(  964):    returned true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
I/jxcore-log( 4656): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
,D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: p2p_scan is already running
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681496921.4656
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 2023): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
D/wpa_supplicant( 2023): P2P: Could not start p2p_scan at this point - will try again after previous scan completes
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH_WHEN_READY
D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363930350634363536227d0a636f72646f7661703270c00c001001
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363930350634363536227d0a636f72646f7661703270c00c001001'
,D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH_WHEN_READY)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH_WHEN_READY -> IDLE
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
D/WifiNative-p2p0(  964):    returned true
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496921.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService(  964): InactiveState{ when=-3ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-3ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast true
D/WifiP2pService(  964): InactiveState{ when=-4ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-4ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service
D/WifiP2pService(  964): remove client information from framework
D/WifiP2pService(  964): InactiveState{ when=-6ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-6ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
D/WifiP2pService(  964): InactiveState{ when=-5ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): discovery change broadcast false
W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:11
D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:16 handle:0x84
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496921.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496921.4656"}", service type: "Cordovap2p._tcp"
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363932312e34363536227dc027
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363932312e34363536227dc027'
D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363932310634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363932310634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
,D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 4656): start: OK
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: p2p_scan is already running
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
D/wpa_supplicant( 2023): P2P: Could not start p2p_scan at this point - will try again after previous scan completes
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH_WHEN_READY
,D/WifiNative-p2p0(  964):    returned true
,I/jxcore-log( 4656): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
,D/bt-btif ( 1225): cleanup slot:11, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
D/WifiP2pService(  964): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@709ada9b target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@709ada9b target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
D/WifiP2pService(  964): add a new client
D/WifiP2pService(  964): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): discovery change broadcast true
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a1b0, p_pcb->port_handle:16
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a1b0, user:11, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:11
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363932310634363536227d0a636f72646f7661703270c00c001001
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363932310634363536227d0a636f72646f7661703270c00c001001'
D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH_WHEN_READY)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH_WHEN_READY -> IDLE
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 4656): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
,D/WifiNative-p2p0(  964):    returned true
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681496943.4656
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
D/WifiP2pService(  964): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service
D/WifiP2pService(  964): remove client information from framework
D/WifiP2pService(  964): InactiveState{ when=-1ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
D/WifiP2pService(  964): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496943.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:12
D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:17 handle:0x84
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496943.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496943.4656"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 4656): start: OK
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363934332e34363536227dc027
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363934332e34363536227dc027'
D/WifiP2pService(  964): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@682b3e93 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@682b3e93 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
,D/WifiP2pService(  964): add a new client
I/jxcore-log( 4656): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
D/bt-btif ( 1225): cleanup slot:12, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a1c4, p_pcb->port_handle:17
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a1c4, user:12, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:12
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363934330634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZ,ED
I/jxcore-log( 4656): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363934330634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: p2p_scan is already running
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
D/wpa_supplicant( 2023): P2P: Could not start p2p_scan at this point - will try again after previous scan completes
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH_WHEN_READY
D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681496963.4656
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363934330634363536227d0a636f72646f7661703270c00c001001
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363934330634363536227d0a636f72646f7661703270c00c001001'
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
,D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/WifiP2pService(  964): InactiveState{ when=-5ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-5ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast true
D/WifiP2pService(  964): InactiveState{ when=-5ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-5ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service
D/WifiP2pService(  964): remove client information from framework
D/WifiP2pService(  964): InactiveState{ when=-7ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-7ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
,D/WifiP2pService(  964): InactiveState{ when=-8ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH_WHEN_READY)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH_WHEN_READY -> IDLE
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496963.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
,D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:13
D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
,D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:18 handle:0x84
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496963.4656"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681496963.4656"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363936332e34363536227dc027
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 4656): start: OK
D/WifiP2pService(  964): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast false
D/WifiP2pService(  964): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@79390f target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@79390f target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
,D/WifiP2pService(  964): add a new client
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439363936332e34363536227dc027'
I/jxcore-log( 4656): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
D/bt-btif ( 1225): cleanup slot:13, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a1d8, p_pcb->port_handle:18
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a1d8, user:13, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:13
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
I/jxcore-log( 4656): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363936330634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 4,9 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363936330634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: p2p_scan is already running
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
,D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
,D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
D/wpa_supplicant( 2023): P2P: Could not start p2p_scan at this point - will try again after previous scan completes
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH_WHEN_READY
D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363936330634363536227d0a636f72646f7661703270c00c001001
D/WifiP2pService(  964): InactiveState{ when=-5ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-5ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast true
D/WifiP2pService(  964): InactiveState{ when=-6ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-7ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState clear service
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439363936330634363536227d0a636f72646f7661703270c00c001001'
,D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
,D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH_WHEN_READY)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH_WHEN_READY -> IDLE
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0(  964):    returned true
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
,I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
,I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
D/WifiP2pService(  964): remove client information from framework
D/WifiP2pService(  964): InactiveState{ when=-9ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-9ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
D/WifiP2pService(  964): InactiveState{ when=-10ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 2023): p2p0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): BSS: last_scan_res_used=1/32 last_scan_full=0
,D/wpa_supplicant( 2023): P2P: Scan results received (1 BSS),
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.242434)
,D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added,
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  964): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48]
,I/jxcore-log( 4656): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681498151.4656
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681498151.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
,I/bt-btif ( 1225): BTA_JvCreateRecordByUser
D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:14
,D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
,D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:19 handle:0x84
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681498151.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681498151.4656"}", service type: "Cordovap2p._tcp"
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439383135312e34363536227dc027
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439383135312e34363536227dc027'
D/WifiP2pService(  964): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@55bf00e1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@55bf00e1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
,D/WifiP2pService(  964): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 4656): start: OK
I/jxcore-log( 4656): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
I/jxcore-log( 4656): ok 66 Cannot call startBroadcasting twice
I/jxcore-log( 4656): 
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439383135310634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/io.jxcore.node.ConnectionHelper( 4656): stop
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439383135310634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
D/bt-btif ( 1225): cleanup slot:14, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a1ec, p_pcb->port_handle:19
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a1ec, user:14, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:14
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 46,56): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
D/WifiNative-p2p0(  964):    returned true
,I/jxcore-log( 4656): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
D/WifiP2pService(  964): InactiveState{ when=-14ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
,D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
D/WifiP2pService(  964): P2pEnabledState{ when=-18ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): P2P: Running p2p_scan
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
,D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
D/WifiP2pService(  964): discovery change broadcast true
D/WifiP2pService(  964): InactiveState{ when=-30ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
,D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439383135310634363536227d0a636f72646f7661703270c00c001001
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439383135310634363536227d0a636f72646f7661703270c00c001001'
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
,D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH -> IDLE
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  964): P2pEnabledState{ when=-31ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service
D/WifiP2pService(  964): remove client information from framework
D/WifiP2pService(  964): InactiveState{ when=-37ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-37ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
,D/WifiP2pService(  964): InactiveState{ when=-38ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
D/WifiP2pService(  964): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast false
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 2023): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 2023): P2P: Scan results received (1 BSS)
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.245526)
,D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
,I/jxcore-log( 4656): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681499782.4656
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681499782.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
,D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
,D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
,I/bt-btif ( 1225): BTA_JvCreateRecordByUser
,D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:15
,D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
,I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
,D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:20 handle:0x84
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681499782.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681499782.4656"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
D/WifiP2pService(  964): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@59cb3e0b target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@59cb3e0b target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439393738322e34363536227dc027
D/WifiP2pService(  964): P2pEnabledState add service
D/WifiP2pService(  964): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 4656): start: OK
,I/jxcore-log( 4656): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
,I/io.jxcore.node.ConnectionHelper( 4656): connect: Trying to connect to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 4656): hasConnection: No connection with peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 4656): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,E/io.jxcore.node.ConnectionHelper( 4656): connect: Invalid Bluetooth address: foobar
,I/jxcore-log( 4656): ok 69 Should not connect to a bad peer
I/jxcore-log( 4656): 
,I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
,D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
D/bt-btif ( 1225): cleanup slot:15, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
,I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
,D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a200, p_pcb->port_handle:20
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a200, user:15, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:15
,D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
,I/jxcore-log( 4656): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313439393738322e34363536227dc027'
,D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439393738320634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439393738320634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
,D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
D/WifiP2pService(  964): InactiveState{ when=-37ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-37ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): P2P: Running p2p_scan
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiP2pService(  964): discovery change broadcast true
D/WifiP2pService(  964): InactiveState{ when=-31ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-31ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState clear service
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439393738320634363536227d0a636f72646f7661703270c00c001001
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313439393738320634363536227d0a636f72646f7661703270c00c001001'
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
,D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH -> IDLE
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
,D/WifiNative-p2p0(  964):    returned true
D/WifiP2pService(  964): remove client information from framework
D/WifiP2pService(  964): InactiveState{ when=-36ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-36ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
,D/WifiP2pService(  964): InactiveState{ when=-38ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
D/WifiP2pService(  964): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast false
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 3
D/wpa_supplicant( 2023): p2p0: BSS: Add new id 1 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2023): P2P: Scan results received (2 BSS)
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.242628)
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 06 Group Capability 09
D/wpa_supplicant( 2023): P2P: Attribute 13 length 45
D/wpa_supplicant( 2023): P2P: * Device Info: addr 9e:93:4e:3e:3a:c5 primary device type 3-0050F204-5 device name 'DIRECT-qjWorkCentre 3025' config methods 0x80
D/wpa_supplicant( 2023): P2P: Attribute 14 length 0
D/wpa_supplicant( 2023): P2P: * Group Info
D/wpa_supplicant( 2023): P2P: Update peer 9e:93:4e:3e:3a:c5 config_methods 0x0 -> 0x80
D/wpa_supplicant( 2023): P2P: Peer found with Listen frequency 2437 MHz (rx_time=1449681501.192628)
I/wpa_supplicant( 2023): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event,
,D/WifiMonitor(  964): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 1 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  964): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
,D/WifiP2pService(  964): InactiveState{ when=-15ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  964):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  964):  primary type: 3-0050F204-5
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 128
D/WifiP2pService(  964):  grpcapab: 9
D/WifiP2pService(  964):  devcapab: 4
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-16ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  964):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  964):  primary type: 3-0050F204-5
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 128
D/WifiP2pService(  964):  grpcapab: 9
D/WifiP2pService(  964):  devcapab: 4
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): DefaultState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): InactiveState{ when=-20ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-22ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServiceExtension(  964): No p2p device connected
,I/jxcore-log( 4656): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 4656): 
D/WifiP2pService(  964): DefaultState{ when=-36ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-37ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-37ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-38ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681501373.4656
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681501373.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
,D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
,D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:16
,D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
,I/bt-btif ( 1225): BTA_JvRfcommStartServer
D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
,D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:21 handle:0x84
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681501373.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681501373.4656"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
D/WifiP2pService(  964): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d639ff33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d639ff33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313530313337332e34363536227dc027
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
,D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313530313337332e34363536227dc027'
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 4656): start: OK
D/WifiP2pService(  964): P2pEnabledState add service
,D/WifiP2pService(  964): add a new client
I/jxcore-log( 4656): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
D/io.jxcore.node.ConnectionHelper( 4656): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 4656): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 4656): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 4656): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 4656): ok 72 Disconnect should fail to a non-existant peer 
I/jxcore-log( 4656): 
D/WifiNative-p2p0(  964):    returned true
I/io.jxcore.node.ConnectionHelper( 4656): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
D/bt-btif ( 1225): cleanup slot:16, fd:96, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a214, p_pcb->port_handle:21
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a214, user:16, state:4, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:16
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
D/WifiN,ative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313530313337330634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313530313337330634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: NOT_INITIALIZED
I/jxcore-log( 4656): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 4656): 
D/WifiNative-p2p0(  964):    returned true
I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
D/WifiP2pService(  964): InactiveState{ when=-17ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-21ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
,D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
,D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
,D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): P2P: Running p2p_scan
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
,D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
,D/WifiNative-p2p0(  964):    returned true
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiP2pService(  964): discovery change broadcast true
D/WifiP2pService(  964): InactiveState{ when=-31ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-31ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState clear service
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313530313337330634363536227d0a636f72646f7661703270c00c001001
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313530313337330634363536227d0a636f72646f7661703270c00c001001'
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
,D/WifiNative-p2p0(  964):    returned true
D/WifiP2pService(  964): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
,D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH -> IDLE
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
D/WifiP2pService(  964): InactiveState{ when=-42ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-43ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
D/WifiP2pService(  964): InactiveState{ when=-43ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast false
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 4
D/wpa_supplicant( 2023): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2023): P2P: Scan results received (2 BSS)
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.246564)
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
,D/wpa_supplicant( 2023): P2P: Attribute 2 length 2,
D/wpa_supplicant( 2023): P2P: * Device Capability 06 Group Capability 09
,D/wpa_supplicant( 2023): P2P: Attribute 13 length 45
,D/wpa_supplicant( 2023): P2P: * Device Info: addr 9e:93:4e:3e:3a:c5 primary device type 3-0050F204-5 device name 'DIRECT-qjWorkCentre 3025' config methods 0x80,
D/wpa_supplicant( 2023): P2P: Attribute 14 length 0,
,D/wpa_supplicant( 2023): P2P: * Group Info
,D/wpa_supplicant( 2023): P2P: Peer found with Listen frequency 2437 MHz (rx_time=1449681502.726564),
,I/wpa_supplicant( 2023): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9,
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
,D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added,
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  964): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
,D/WifiP2pService(  964): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  964):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  964):  primary type: 3-0050F204-5
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 128
D/WifiP2pService(  964):  grpcapab: 9
D/WifiP2pService(  964):  devcapab: 4
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  964):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  964):  primary type: 3-0050F204-5
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 128
D/WifiP2pService(  964):  grpcapab: 9
D/WifiP2pService(  964):  devcapab: 4
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServiceExtension(  964): No p2p device connected
D/WifiP2pService(  964): DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-6ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-6ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-7ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4656): # ThaliEmitter can discover and connect to peers
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): # teardown
I/jxcore-log( 4656): 
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: 34:FC:EF:9D:93:0B 1449681507386.4656
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4656): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681507386.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1225): SOCK FLAG = 0 ***********************
,D/bt-btif ( 1225): btsock_rfc_listen, service_name:Thaili_Bluetooth
,D/bt-btif ( 1225): BTA_JvCreateRecordByUser:Thaili_Bluetooth
I/bt-btif ( 1225): BTA_JvCreateRecordByUser
,D/bt-btif ( 1225): jv_dm_cback: event:11, slot id:17
,D/bt-btif ( 1225): name:Thaili_Bluetooth, scn:7
D/bt-sdp  ( 1225): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1225): BTA_JvRfcommStartServer
,D/bt-btif ( 1225): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
,D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:22 handle:0x84
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): start: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681507386.4656"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): start: Identity string: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681507386.4656"}", service type: "Cordovap2p._tcp"
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313530373338362e34363536227dc027
D/WifiP2pService(  964): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8c01b01f target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8c01b01f target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState add service
,D/WifiP2pService(  964): add a new client
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=217): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227261223a2233343a46433a45463a39443a39333a3042222c227069223a2233343a46433a45463a39443a39333a3042222c22706e223a22313434393638313530373338362e34363536227dc027'
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 4656): start: OK
I/jxcore-log( 4656): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 4656): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onWifiStateChanged: State changed to 2
D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): restart: Restarting...
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: RUNNING
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313530373338360634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=249): 50 32 50 5f 53 45 52 56 49 43 45 5f 41 44 44 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313530373338360634363536227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local service added successfully
,D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
,D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/WifiP2pService(  964): InactiveState{ when=-7ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-9ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): P2P: Running p2p_scan
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
,D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
D/WifiP2pService(  964): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
,D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH -> IDLE
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): restart: Restarting...
D/WifiP2pService(  964): InactiveState{ when=-19ms what=139307 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-19ms what=139307 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
D/WifiP2pService(  964): InactiveState{ when=-20ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): discovery change broadcast false
,D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): P2P: State IDLE -> IDLE
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
D/WifiP2pService(  964): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
D/WifiP2pService(  964): InactiveState{ when=-2ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2023): p2p0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48]
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 5
D/wpa_supplicant( 2023): p2p0: BSS: Add new id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 2023): P2P: Scan results received (1 BSS)
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.249394)
,D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event,
,D/WifiMonitor(  964): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 2 c0:ff:d4:d3:aa:48]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): start: Starting peer discovery...
D/WifiP2pService(  964): InactiveState{ when=-1ms what=139265 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
D/WifiP2pService(  964): P2pEnabledState{ when=-2ms what=139265 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
,D/wpa_supplicant( 2023): WPS:  * Manufacturer,
,D/wpa_supplicant( 2023): WPS:  * Model Name
,D/wpa_supplicant( 2023): WPS:  * Model Number
,D/wpa_supplicant( 2023): WPS:  * Device Name,
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1),
D/wpa_supplicant( 2023): P2P: * P2P IE header,
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00,
,D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
,D/wpa_supplicant( 2023): p2p0: nl80211: scan request,
,D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d,
,D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...,
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
,D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
,D/wpa_supplicant( 2023): P2P: Running p2p_scan
,D/wpa_supplicant( 2023): nl80211: Event message available,
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
,D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger,
D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
D/WifiP2pService(  964): discovery change broadcast true
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 6
D/wpa_supplicant( 2023): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2023): P2P: Scan results received (2 BSS)
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.244777)
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 06 Group Capability 09
D/wpa_supplicant( 2023): P2P: Attribute 3 length 6
D/wpa_supplicant( 2023): P2P: * Device ID 9e:93:4e:3e:3a:c5
D/wpa_supplicant( 2023): P2P: Peer found with Listen frequency 2437 MHz (rx_time=1449681513.804777)
I/wpa_supplicant( 2023): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=6-0050F204-1 name='WorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 2023): P2P: ### Servicing 0xb87c8d98 dev->flags 0x8002 SD schedule FALSE devaddr 9e:93:4e:3e:3a:c5
,D/wpa_supplicant( 2023): P2P: Starting short listen state (state=SEARCH),
,D/WifiMonitor(  964): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=6-0050F204-1 name='WorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry,
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/wpa_supplicant( 2023): nl80211: Enable Probe Request reporting nl_preq=0xb87c9790,
,D/wpa_supplicant( 2023): nl80211: Register frame type=0x40 nl_handle=0xb87c9790
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=0): [NULL]
,D/wpa_supplicant( 2023): nl80211: Remain-on-channel cookie 0x1 for freq=2437 MHz duration=307
D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
,D/wpa_supplicant( 2023): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=307 cookie=0x1 (match))
,D/wpa_supplicant( 2023): p2p0: Event REMAIN_ON_CHANNEL (22) received
D/wpa_supplicant( 2023): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0)
D/wpa_supplicant( 2023): P2P: Starting Listen timeout(0,307200) on freq=2437 based on callback,
D/wpa_supplicant( 2023): P2P: Set timeout (state=SEARCH): 0.327200 sec,
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added,
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiP2pService(  964): InactiveState{ when=0 what=147477 obj=Device: WorkCentre 3025
D/WifiP2pService(  964):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  964):  primary type: 6-0050F204-1
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 128
D/WifiP2pService(  964):  grpcapab: 9
D/WifiP2pService(  964):  devcapab: 4
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=147477 obj=Device: WorkCentre 3025
D/WifiP2pService(  964):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  964):  primary type: 6-0050F204-1
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 128
D/WifiP2pService(  964):  grpcapab: 9
D/WifiP2pService(  964):  devcapab: 4
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): InactiveState{ when=-5ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-8ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): DefaultState{ when=-8ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): InactiveState{ when=-7ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-8ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): DefaultState{ when=-8ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-10ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-10ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServiceExtension(  964): No p2p device connected
D/WifiP2pService(  964): DefaultState{ when=-11ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-12ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-12ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): onP2pDeviceListChanged: Peer 1: WorkCentre 3025 9e:93:4e:3e:3a:c5
,D/WifiP2pManager( 4656): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService(  964): DefaultState{ when=-12ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=0 what=139301 arg2=9 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139301 arg2=9 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState add service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service request added successfully
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0x1 (match))
D/wpa_supplicant( 2023): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (23) received
D/wpa_supplicant( 2023): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
D/wpa_supplicant( 2023): P2P: Driver ended Listen state (freq=2437)
,D/wpa_supplicant( 2023): P2P: Skip stop_listen since not in listen_only state.
,D/wpa_supplicant( 2023): P2P: Timeout (state=SEARCH)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): nl80211: Disable Probe Request reporting nl_preq=0xb87c9790
D/wpa_supplicant( 2023): P2P: Starting search
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: Scan frequency 2412 MHz
D/wpa_supplicant( 2023): nl80211: Scan frequency 2437 MHz
D/wpa_supplicant( 2023): nl80211: Scan frequency 2462 MHz
,D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): P2P: Running p2p_scan
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
,D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 7
D/wpa_supplicant( 2023): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2023): P2P: Scan results received (2 BSS)
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.241938)
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 06 Group Capability 09
D/wpa_supplicant( 2023): P2P: Attribute 13 length 45
D/wpa_supplicant( 2023): P2P: * Device Info: addr 9e:93:4e:3e:3a:c5 primary device type 3-0050F204-5 device name 'DIRECT-qjWorkCentre 3025' config methods 0x80
D/wpa_supplicant( 2023): P2P: Attribute 14 length 0
D/wpa_supplicant( 2023): P2P: * Group Info
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH
,D/wpa_supplicant( 2023): P2P: Starting short listen state (state=SEARCH),
,D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 2023): WPS:  * UUID-E
,D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 2023): P2P: * P2P IE header
,D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
,D/wpa_supplicant( 2023): P2P: * Device Info
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0,
,D/wpa_supplicant( 2023): nl80211: Enable Probe Request reporting nl_preq=0xb87c99f0,
,D/wpa_supplicant( 2023): nl80211: Register frame type=0x40 nl_handle=0xb87c99f0
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=0): [NULL]
,D/wpa_supplicant( 2023): nl80211: Remain-on-channel cookie 0x2 for freq=2437 MHz duration=307
D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=307 cookie=0x2 (match))
D/wpa_supplicant( 2023): p2p0: Event REMAIN_ON_CHANNEL (22) received
D/wpa_supplicant( 2023): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0)
D/wpa_supplicant( 2023): P2P: Starting Listen timeout(0,307200) on freq=2437 based on callback
D/wpa_supplicant( 2023): P2P: Set timeout (state=SEARCH): 0.327200 sec
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0x2 (match))
D/wpa_supplicant( 2023): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (23) received
D/wpa_supplicant( 2023): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
D/wpa_supplicant( 2023): P2P: Driver ended Listen state (freq=2437)
,D/wpa_supplicant( 2023): P2P: Skip stop_listen since not in listen_only state.
D/wpa_supplicant( 2023): P2P: Timeout (state=SEARCH)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): nl80211: Disable Probe Request reporting nl_preq=0xb87c99f0
D/wpa_supplicant( 2023): P2P: Starting search
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: Scan frequency 2412 MHz
D/wpa_supplicant( 2023): nl80211: Scan frequency 2437 MHz
D/wpa_supplicant( 2023): nl80211: Scan frequency 2462 MHz
,D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
,D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): P2P: Running p2p_scan
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
,D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
,D/WifiP2pService(  964): InactiveState{ when=-1ms what=139310 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-2ms what=139310 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0(  964): doString: P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01
D/WifiP2pService(  964): P2pEnabledState discover services
,D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=76): 50 32 50 5f 53 45 52 56 5f 44 49 53 43 5f 52 45 51 20 30 30 3a 30 30 3a 30 30 3a 30 30 3a 30 30 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01'
,D/wpa_supplicant( 2023): P2P: Added SD Query 0xb87c9a00
,D/WifiNative-p2p0(  964):    returned b87c9a00
,D/WifiNative-p2p0(  964): doBoolean: P2P_FIND 120
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=12): 50 32 50 5f 46 49 4e 44 20 31 32 30
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_FIND 120'
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): P2P: Starting find (type=0)
D/wpa_supplicant( 2023): P2P: p2p_scan is already running
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
,D/wpa_supplicant( 2023): nl80211: Scan trigger failed: ret=-16 (Device or resource busy),
D/wpa_supplicant( 2023): P2P: Could not start p2p_scan at this point - will try again after previous scan completes
,D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH_WHEN_READY
,D/WifiNative-p2p0(  964):    returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service discovery started successfully,
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): onServiceListChanged: Got empty list
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 8
D/wpa_supplicant( 2023): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2023): P2P: Scan results received (2 BSS)
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.243784)
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 06 Group Capability 09
D/wpa_supplicant( 2023): P2P: Attribute 13 length 45
D/wpa_supplicant( 2023): P2P: * Device Info: addr 9e:93:4e:3e:3a:c5 primary device type 3-0050F204-5 device name 'DIRECT-qjWorkCentre 3025' config methods 0x80
D/wpa_supplicant( 2023): P2P: Attribute 14 length 0
D/wpa_supplicant( 2023): P2P: * Group Info
D/wpa_supplicant( 2023): P2P: Peer found with Listen frequency 2437 MHz (rx_time=1449681514.963784)
I/wpa_supplicant( 2023): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=1)
,D/wpa_supplicant( 2023): P2P: Starting pending P2P find now that previous scan was completed,
,D/wpa_supplicant( 2023): P2P: Starting find (type=0)
,D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH_WHEN_READY),
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/wpa_supplicant( 2023): P2P: State SEARCH_WHEN_READY -> SEARCH,
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request,
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10),
,D/wpa_supplicant( 2023): WPS:  * Request Type
,D/wpa_supplicant( 2023): WPS:  * Config Methods (4388),
D/wpa_supplicant( 2023): WPS:  * UUID-E,
,D/wpa_supplicant( 2023): WPS:  * Primary Device Type
,D/wpa_supplicant( 2023): WPS:  * RF Bands (3),
D/wpa_supplicant( 2023): WPS:  * Association State
,D/wpa_supplicant( 2023): WPS:  * Configuration Error (0),
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
,D/wpa_supplicant( 2023): WPS:  * Manufacturer,
D/wpa_supplicant( 2023): WPS:  * Model Name,
D/wpa_supplicant( 2023): WPS:  * Model Number,
,D/wpa_supplicant( 2023): WPS:  * Device Name
,D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1),
D/wpa_supplicant( 2023): P2P: * P2P IE header
,D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00,
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6,
,D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d,
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/WifiMonitor(  964): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): P2P: Running p2p_scan,
,D/wpa_supplicant( 2023): p2p0: P2P: Pending P2P operation continued after successful connection
D/wpa_supplicant( 2023): p2p0: P2P: Use 0 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiP2pService(  964): InactiveState{ when=-39ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  964):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  964):  primary type: 3-0050F204-5
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 128
D/WifiP2pService(  964):  grpcapab: 9
D/WifiP2pService(  964):  devcapab: 4
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-41ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  964):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  964):  primary type: 3-0050F204-5
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 128
D/WifiP2pService(  964):  grpcapab: 9
D/WifiP2pService(  964):  devcapab: 4
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-1ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServiceExtension(  964): No p2p device connected
D/WifiP2pService(  964): DefaultState{ when=-3ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681516240320423; DSPS: 13801638; Offset: 1449681095047754506
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 9
D/wpa_supplicant( 2023): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2023): P2P: Scan results received (2 BSS)
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.241185)
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 06 Group Capability 09
D/wpa_supplicant( 2023): P2P: Attribute 3 length 6
D/wpa_supplicant( 2023): P2P: * Device ID 9e:93:4e:3e:3a:c5
D/wpa_supplicant( 2023): P2P: Peer found with Listen frequency 2437 MHz (rx_time=1449681516.251185)
I/wpa_supplicant( 2023): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=6-0050F204-1 name='WorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 2023): P2P: ### Servicing 0xb87c8d98 dev->flags 0x8002 SD schedule FALSE devaddr 9e:93:4e:3e:3a:c5
,D/wpa_supplicant( 2023): P2P: Starting short listen state (state=SEARCH),
,D/WifiMonitor(  964): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=6-0050F204-1 name='WorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9],
,D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 2023): WPS:  * UUID-E
,D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
,D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/wpa_supplicant( 2023): nl80211: Enable Probe Request reporting nl_preq=0xb87c6c90
,D/wpa_supplicant( 2023): nl80211: Register frame type=0x40 nl_handle=0xb87c6c90
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=0): [NULL]
,D/wpa_supplicant( 2023): nl80211: Remain-on-channel cookie 0x3 for freq=2437 MHz duration=307
D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 2023): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0
,D/WifiP2pService(  964): InactiveState{ when=-9ms what=147477 obj=Device: WorkCentre 3025,
D/WifiP2pService(  964):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  964):  primary type: 6-0050F204-1
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 128
D/WifiP2pService(  964):  grpcapab: 9
D/WifiP2pService(  964):  devcapab: 4,
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=307 cookie=0x3 (match))
D/wpa_supplicant( 2023): p2p0: Event REMAIN_ON_CHANNEL (22) received,
D/wpa_supplicant( 2023): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0)
,D/wpa_supplicant( 2023): P2P: Starting Listen timeout(0,307200) on freq=2437 based on callback
D/wpa_supplicant( 2023): P2P: Set timeout (state=SEARCH): 0.327200 sec
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
,D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiP2pService(  964): P2pEnabledState{ when=-24ms what=147477 obj=Device: WorkCentre 3025
D/WifiP2pService(  964):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  964):  primary type: 6-0050F204-1
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 128
D/WifiP2pService(  964):  grpcapab: 9
D/WifiP2pService(  964):  devcapab: 4
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): InactiveState{ when=-1ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): DefaultState{ when=-2ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServiceExtension(  964): No p2p device connected
D/WifiP2pService(  964): DefaultState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-4ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-4ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-4ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 70 1b 00 07 44 49 52 45 43 54 ...
D/wpa_supplicant( 2023): nl80211: Frame event
D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Created device entry based on Probe Req: 3a:94:96:b5:06:dd dev_capab=0x25 group_capab=0x0 name='Galaxy S5-2' listen_freq=2412
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
,D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=01 (unknown) (ack=1),
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 70 1b 00 07 44 49 52 45 43 54 ...
D/wpa_supplicant( 2023): nl80211: Frame event
D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received,
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2,
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
,D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE,
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
,D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
,D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2,
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
,D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=02 (unknown) (ack=1)
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 80 1b 00 07 44 49 52 45 43 54 ...
D/wpa_supplicant( 2023): nl80211: Frame event
D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
,D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=03 (unknown) (ack=1),
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 80 1b 00 07 44 49 52 45 43 54 ...
D/wpa_supplicant( 2023): nl80211: Frame event
,D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
,D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1,
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
,D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1,
D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
,D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
,D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=04 (unknown) (ack=1)
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=36:fc:ef:de:0a:e2 A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=63): d0 00 00 00 36 fc ef de 0a e2 3a 94 96 b5 06 dd c0 ff d4 d3 aa 48 00 00 04 0a 00 6c 02 00 00 1e ...
D/wpa_supplicant( 2023): nl80211: Frame event
D/wpa_supplicant( 2023): p2p0: Event RX_ACTION (21) received
D/wpa_supplicant( 2023): p2p0: Received Action frame: SA=3a:94:96:b5:06:dd Category=4 DataLen=38 freq=2437 MHz
D/wpa_supplicant( 2023): P2P: GAS Initial Request from 3a:94:96:b5:06:dd (dialog token 0, freq 2437)
D/wpa_supplicant( 2023): P2P: Service Update Indicator: 55
D/wpa_supplicant( 2023): P2P: Service Discovery Request TLVs - hexdump(len=20): 12 00 01 01 0a 43 6f 72 64 6f 76 61 70 32 70 c0 0c 00 0c 01
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: Service Request TLV
D/wpa_supplicant( 2023): P2P: Service Protocol Type 1
D/wpa_supplicant( 2023): P2P: Service Transaction ID 1
D/wpa_supplicant( 2023): P2P: Query Data - hexdump(len=16): 0a 43 6f 72 64 6f 76 61 70 32 70 c0 0c 00 0c 01
D/wpa_supplicant( 2023): P2P: SD Request for Bonjour - hexdump(len=16): 0a 43 6f 72 64 6f 76 61 70 32 70 c0 0c 00 0c 01
D/wpa_supplicant( 2023): P2P: Matching Bonjour service - hexdump(len=80): 4d 7b 22 72 61 22 3a 22 33 34 3a 46 43 3a 45 46 3a 39 44 3a 39 33 3a 30 42 22 2c 22 70 69 22 3a ...
D/wpa_supplicant( 2023): P2P: SD response fits in initial response
D/wpa_supplicant( 2023): Off-channel: Send action frame: freq=2437 dst=3a:94:96:b5:06:dd src=36:fc:ef:de:0a:e2 bssid=36:fc:ef:de:0a:e2 len=124
D/wpa_supplicant( 2023): nl80211: Send Action frame (ifindex=22, freq=2437 MHz wait=200 ms no_cck=1)
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=200 no_cck=1 no_ack=0 offchanok=1
,D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=148): d0 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 04 0b 00 00 00 00 00 6c ...,
,D/WifiMonitor(  964): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 3a:94:96:b5:06:dd 0 55 120001010a436f72646f7661703270c00c000c01]
,D/wpa_supplicant( 2023): nl80211: Frame TX command accepted; cookie 0x5
D/wpa_supplicant( 2023): P2P: Timeout (state=SEARCH)
D/wpa_supplicant( 2023): P2P: Driver is still in Listen state - wait for it to end before continuing
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0x3 (match))
D/wpa_supplicant( 2023): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (23) received
D/wpa_supplicant( 2023): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0xb87c8a98)
D/wpa_supplicant( 2023): P2P: Driver ended Listen state (freq=2437)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): nl80211: Disable Probe Request reporting nl_preq=0xb87c6c90
D/wpa_supplicant( 2023): P2P: Starting search
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: Scan frequency 2412 MHz
D/wpa_supplicant( 2023): nl80211: Scan frequency 2437 MHz
D/wpa_supplicant( 2023): nl80211: Scan frequency 2462 MHz
,D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates,
,D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
,D/wpa_supplicant( 2023): P2P: Running p2p_scan
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
,D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=148): d0 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 04 0b 00 00 00 00 00 6c ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event,
,D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=05 (match) (ack=1)
,D/wpa_supplicant( 2023): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 2023): p2p0: EVENT_TX_STATUS dst=3a:94:96:b5:06:dd type=0 stype=13,
D/wpa_supplicant( 2023): Off-channel: TX status result=0 cb=0xb6f1ab25
,D/wpa_supplicant( 2023): P2P: Action frame TX callback (state=0 freq=2437 dst=3a:94:96:b5:06:dd src=36:fc:ef:de:0a:e2 bssid=36:fc:ef:de:0a:e2 result=0
,D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
,D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 10
D/wpa_supplicant( 2023): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2023): P2P: Scan results received (3 BSS)
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.242266)
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 06 Group Capability 09
D/wpa_supplicant( 2023): P2P: Attribute 13 length 45
D/wpa_supplicant( 2023): P2P: * Device Info: addr 9e:93:4e:3e:3a:c5 primary device type 3-0050F204-5 device name 'DIRECT-qjWorkCentre 3025' config methods 0x80
D/wpa_supplicant( 2023): P2P: Attribute 14 length 0
D/wpa_supplicant( 2023): P2P: * Group Info
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 13 length 32
D/wpa_supplicant( 2023): P2P: * Device Info: addr 3a:94:96:b5:06:dd primary device type 10-0050F204-5 device name 'Galaxy S5-2' config methods 0x188
D/wpa_supplicant( 2023): P2P: Update peer 3a:94:96:b5:06:dd config_methods 0x0 -> 0x188
D/wpa_supplicant( 2023): P2P: Peer found with Listen frequency 2412 MHz (rx_time=1449681516.862266)
I/wpa_supplicant( 2023): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH
,D/wpa_supplicant( 2023): P2P: Starting short listen state (state=SEARCH),
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10),
D/wpa_supplicant( 2023): WPS:  * UUID-E
,D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/wpa_supplicant( 2023): nl80211: Enable Probe Request reporting nl_preq=0xb87c6c90
,D/wpa_supplicant( 2023): nl80211: Register frame type=0x40 nl_handle=0xb87c6c90,
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=0): [NULL]
,D/WifiMonitor(  964): Event [P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0],
D/wpa_supplicant( 2023): nl80211: Remain-on-channel cookie 0x4 for freq=2437 MHz duration=204
,D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
D/wpa_supplicant( 2023): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0,
D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=204 cookie=0x4 (match)),
D/wpa_supplicant( 2023): p2p0: Event REMAIN_ON_CHANNEL (22) received,
D/wpa_supplicant( 2023): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0),
,D/wpa_supplicant( 2023): P2P: Starting Listen timeout(0,204800) on freq=2437 based on callback
,D/wpa_supplicant( 2023): P2P: Set timeout (state=SEARCH): 0.224800 sec,
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added,
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
,E/WifiServiceExtension(  964): No p2p device connected
D/WifiP2pService(  964): InactiveState{ when=-29ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  964):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  964):  primary type: 10-0050F204-5
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 392
D/WifiP2pService(  964):  grpcapab: 0
D/WifiP2pService(  964):  devcapab: 37
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-32ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  964):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  964):  primary type: 10-0050F204-5
D/WifiP2pService(  964):  secondary type: null
D/WifiP2pService(  964):  wps: 392
D/WifiP2pService(  964):  grpcapab: 0
D/WifiP2pService(  964):  devcapab: 37
D/WifiP2pService(  964):  status: 3
D/WifiP2pService(  964):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-1ms what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-2ms what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2023): P2P: Timeout (state=SEARCH)
,D/wpa_supplicant( 2023): P2P: Driver is still in Listen state - wait for it to end before continuing
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0x4 (match))
D/wpa_supplicant( 2023): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (23) received
D/wpa_supplicant( 2023): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
D/wpa_supplicant( 2023): P2P: Driver ended Listen state (freq=2437)
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry,
,D/wpa_supplicant( 2023): nl80211: Disable Probe Request reporting nl_preq=0xb87c6c90,
,D/wpa_supplicant( 2023): P2P: Starting search,
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request,
,D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10),
D/wpa_supplicant( 2023): WPS:  * Request Type,
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0),
,D/wpa_supplicant( 2023): WPS:  * Manufacturer,
,D/wpa_supplicant( 2023): WPS:  * Model Name
,D/wpa_supplicant( 2023): WPS:  * Model Number
,D/wpa_supplicant( 2023): WPS:  * Device Name
,D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
,D/wpa_supplicant( 2023): P2P: * P2P IE header
,D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
,D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
,D/wpa_supplicant( 2023): p2p0: nl80211: scan request,
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d,
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...,
D/wpa_supplicant( 2023): nl80211: Scan frequency 2412 MHz,
D/wpa_supplicant( 2023): nl80211: Scan frequency 2437 MHz
D/wpa_supplicant( 2023): nl80211: Scan frequency 2462 MHz,
D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates,
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds,
D/wpa_supplicant( 2023): P2P: Running p2p_scan,
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0,
,D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
,D/bt-btif ( 1225): in, bd addr:38:94:96:b5:06:dc, prop type:12, len:12
,D/IOP_DB_BT( 1225): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 38:94:96:b5:06:dc
,D/IOP_DB_BT( 1225): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1225): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 1225): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1225): db_query_execute: result 1
,D/IOP_DB_BT( 1225): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 38:94:96:b5:06:dc
,D/IOP_DB_BT( 1225): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1225): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 1225): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1225): db_query_execute: result 1
,I/bt-btif ( 1225): bta_dm_sm_execute event:0x8
,W/bt-btif ( 1225): info:x10
,I/bt-btif ( 1225): bta_dm_sm_execute event:0x8
,I/bt-btif ( 1225): btif_dm_upstreams_cback  ev: BTA_DM_LINK_UP_EVT
,D/bt-btif ( 1225): BTA_DM_LINK_UP_EVT. Sending BT_ACL_STATE_CONNECTED
,D/        ( 1225): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,D/bt-btif ( 1225): in, bd addr:38:94:96:b5:06:dc, prop type:12, len:12
,D/bt-att  ( 1225): GATT   ATT protocol channel with BDA: 389496b506dc is connected
,D/bt-att  ( 1225): gatt_is_bda_in_the_srv_chg_clt_list :38-94-96-b5-06-dc
,D/bt-att  ( 1225): gatt_add_srv_chg_clt
,D/bt-att  ( 1225): enqueue a srv chg client
,D/bt-att  ( 1225): connected is TRUE reason=0
,I/bt-smp  ( 1225): SMDBG l2c smp_connect_cback 
,I/bt-sdp  ( 1225): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x40
,D/bt-btif ( 1225): SDP - Rcvd L2CAP conn ind, sen
,I/bt-btif ( 1225): HAL bt_hal_cbacks->acl_state_changed_cb
,D/btif_config_util( 1225): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiServiceExtension(  964): Connected BT device : 1
,I/bt-sdp  ( 1225): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x40
,I/bt-btif ( 1225): btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
,I/bt-btif ( 1225): a2dp busy level set to 1
,D/bt-btif ( 1225): btif_check_send_bt_off() btif_core_state= (2),ACL links = (1), LE links = 0
,I/bt-sdp  ( 1225): SDP - Rcvd cfg cfm, CID: 0x40  Result: 0
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 11
D/wpa_supplicant( 2023): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2023): P2P: Scan results received (3 BSS)
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.245424)
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 06 Group Capability 09
D/wpa_supplicant( 2023): P2P: Attribute 13 length 45
D/wpa_supplicant( 2023): P2P: * Device Info: addr 9e:93:4e:3e:3a:c5 primary device type 3-0050F204-5 device name 'DIRECT-qjWorkCentre 3025' config methods 0x80
D/wpa_supplicant( 2023): P2P: Attribute 14 length 0
D/wpa_supplicant( 2023): P2P: * Group Info
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 13 length 32
D/wpa_supplicant( 2023): P2P: * Device Info: addr 3a:94:96:b5:06:dd primary device type 10-0050F204-5 device name 'Galaxy S5-2' config methods 0x188
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 2023): P2P: ### Servicing 0xb87c84d8 dev->flags 0x8012 SD schedule TRUE devaddr 3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): P2P: Start Service Discovery with 3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): Off-channel: Send action frame: freq=2412 dst=3a:94:96:b5:06:dd src=36:fc:ef:de:0a:e2 bssid=3a:94:96:b5:06:dd len=39
D/wpa_supplicant( 2023): nl80211: Send Action frame (ifindex=22, freq=2412 MHz wait=5000 ms no_cck=1)
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2412 wait=5000 no_cck=1 no_ack=0 offchanok=1
,D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=63): d0 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 3a 94 96 b5 06 dd 00 00 04 0a 00 6c 02 00 00 1e ...
,D/BluetoothManagerService(  964): Message: 20
,D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44f16550:true
,I/bt-sdp  ( 1225): SDP - Rcvd L2CAP disc, CID: 0x40
,D/bt-sdp  ( 1225): releasing SDP rsp_list
,D/LGBluetoothPowerSaveListener( 2576): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-rfcomm( 1225): port_select_mtu credit_rx_max 40, credit_rx_low 10, rx_buf_critical 45
,D/BluetoothManagerService(  964): Message: 20
,D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44e8b370:true
,D/bt-btif ( 1225): bta_jv_port_mgmt_sr_cback, code:0, port_handle:22
D/bt-btif ( 1225): bta_jv_port_mgmt_sr_cback code=0 port_handle:0x16 handle:0x84, p_pcb:0x60c9a228, user:17
,D/bt-btif ( 1225): bta_jv_add_rfc_port, port_handle:22, change the listen port to open state
D/bt-btif ( 1225): bta_jv_add_rfc_port max_sess=7 used:1 curr_sess:1, listen:1 si:2
D/bt-btif ( 1225): bta_jv_add_rfc_port: p_pcb->handle:0x184, curr_sess:2
D/bt-btif ( 1225): bta_jv_add_rfc_port: sec id in use:4, rfc_cb in use:4
,I/bt-btif ( 1225): BTA_JVSetPmProfile handle:0x84, app_id:255
I/bt-btif ( 1225): BTA_JVSetPmProfile handle:0x84, app_id:255
D/bt-btif ( 1225): create_srv_accept_rfc_slot(open_handle: 0x84, new_listen_handle:0x184) accept_rs->rfc_handle:0x84, srv_rs_listen->rfc_handle:0x184
,D/bt-btif ( 1225): create_srv_accept_rfc_slot, accept_rs->rfc_port_handle:0x16, srv_rs_listen->rfc_port_handle:0x17
D/bt-btif ( 1225): sending connect signal & app fd:98to app server to accept() the connection
D/bt-btif ( 1225): server fd:96, scn:7, accept rs id:17 app fd:98
,D/bt-btif ( 1225): close fd:98 after sent
,D/bt-btif ( 1225): PORT_SUCCESS: curr_sess:2, max_sess:7
I/bt-btif ( 1225): bta_jv_set_pm_profile(handle: 0x84, app_id: 255, init_st: 0)
I/bt-btif ( 1225): bta_jv_alloc_set_pm_profile_cb(handle 0x84, app_id 255): idx: 0, (BTA_JV_PM_MAX_NUM: 5), pp_cb: 0x60c9a238
I/bt-btif ( 1225): bta_jv_pm_state_change(p_cb: 0x60c9a324, handle: 0x84, busy/idle_state: 1, app_id: 255, conn_state: 0)
,D/bt-btif ( 1225): bta_dm_pm_cback: st(0), id(26), app(255)
W/bt-btif ( 1225): new conn_srvc id:26, app_id:255
W/bt-btif ( 1225): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 1225): bta_dm_pm_ssr:2, lat:1200
,D/bt-btif ( 1225): bta_dm_pm_set_mode: srvcsid: 26, state: 0, j: 14
I/bt-btif ( 1225): bta_jv_set_pm_profile(handle: 0x84, app_id: 255, init_st: 6)
I/bt-btif ( 1225): bta_jv_alloc_set_pm_profile_cb already allocated. return cb(handle 0x84, app_id 255): idx: 0)
,I/bt-btif ( 1225): bta_jv_pm_state_change(p_cb: 0x60c9a324, handle: 0x84, busy/idle_state: 1, app_id: 255, conn_state: 6)
D/bt-btif ( 1225): bta_dm_pm_cback: st(6), id(26), app(255)
D/bt-btif ( 1225): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1225): start dm_pm_timer:0, 7000
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Incoming connection initialized (thread ID: 431)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 4656): Entering thread (ID: 431)
,I/BTConnectionReceiver( 2647): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2647): Bluetooth Device Name: Galaxy S5-2
,D/wpa_supplicant( 2023): nl80211: Frame TX command accepted; cookie 0x6
,D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=63): d0 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 3a 94 96 b5 06 dd 00 00 04 0a 00 6c 02 00 00 1e ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=06 (match) (ack=0)
D/wpa_supplicant( 2023): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 2023): p2p0: EVENT_TX_STATUS dst=3a:94:96:b5:06:dd type=0 stype=13
D/wpa_supplicant( 2023): Off-channel: TX status result=1 cb=0xb6f1ab25
D/wpa_supplicant( 2023): P2P: Action frame TX callback (state=5 freq=2412 dst=3a:94:96:b5:06:dd src=36:fc:ef:de:0a:e2 bssid=3a:94:96:b5:06:dd result=1
D/wpa_supplicant( 2023): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 2023): P2P: ### Servicing 0xb87c8d98 dev->flags 0x8002 SD schedule FALSE devaddr 9e:93:4e:3e:3a:c5
D/wpa_supplicant( 2023): P2P: Starting short listen state (state=SEARCH)
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/wpa_supplicant( 2023): nl80211: Enable Probe Request reporting nl_preq=0xb87c9e68
D/wpa_supplicant( 2023): nl80211: Register frame type=0x40 nl_handle=0xb87c9e68
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=0): [NULL]
D/wpa_supplicant( 2023): nl80211: Remain-on-channel cookie 0x5 for freq=2437 MHz duration=307
D/wpa_supplicant( 2023): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=307 cookie=0x5 (match))
D/wpa_supplicant( 2023): p2p0: Event REMAIN_ON_CHANNEL (22) received
D/wpa_supplicant( 2023): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0)
D/wpa_supplicant( 2023): P2P: Starting Listen timeout(0,307200) on freq=2437 based on callback
D/wpa_supplicant( 2023): P2P: Set timeout (state=SEARCH): 0.327200 sec
D/wpa_supplicant( 2023): p2p0: BSS: Remove id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  964): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): onBytesRead: Read 77 bytes successfully (thread ID: 431)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Got valid identity from [38:94:96:B5:06:DC 1449681505170.5215 38:94:96:B5:06:DC]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): onBytesWritten: 77 bytes successfully written (thread ID: 431)
I/bt-btif ( 1225): bta_jv_pm_state_change(p_cb: 0x60c9a324, handle: 0x84, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btif ( 1225): bta_dm_pm_cback: st(7), id(26), app(255)
D/bt-btif ( 1225): stop dm_pm_timer:0
D/bt-btif ( 1225): bta_dm_pm_set_mode: srvcsid: 26, state: 7, j: 14
D/bt-btif ( 1225): bta_jv_port_event_sr_cback code=x4 port_handle:22 handle:132
,I/bt-btif ( 1225): bta_jv_pm_state_change(p_cb: 0x60c9a324, handle: 0x84, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btif ( 1225): bta_dm_pm_cback: st(6), id(26), app(255)
D/bt-btif ( 1225): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1225): start dm_pm_timer:0, 7000
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): removeThreadFromList: Removing thread with ID 431
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Handshake thread disposed (thread ID: 431)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionConnected: [38:94:96:B5:06:DC 1449681505170.5215 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 4656): Exiting thread (ID: 431)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnected: [38:94:96:B5:06:DC 1449681505170.5215 38:94:96:B5:06:DC]
I/io.jxcore.node.ConnectionHelper( 4656): onConnected: Incoming connection, peer ID: 38:94:96:B5:06:DC, name: 1449681505170.5215, Bluetooth address: 38:94:96:B5:06:DC
,D/io.jxcore.node.ConnectionHelper( 4656): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
,I/io.jxcore.node.ConnectionHelper( 4656): addNewPeerToListAndNotify: Adding peer with ID 38:94:96:B5:06:DC
,I/io.jxcore.node.ConnectionHelper( 4656): connect: Trying to connect to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 4656): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
,I/io.jxcore.node.ConnectionHelper( 4656): connect: Connection process successfully started (peer ID: 38:94:96:B5:06:DC)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 4656): Trying to connect to peer with address 38:94:96:B5:06:DC (thread ID: 432)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 4656): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 4656): getBluetoothService() called with no BluetoothManagerCallback
,I/io.jxcore.node.ConnectionHelper( 4656): onConnected: Incoming socket thread, for peer with ID 38:94:96:B5:06:DC, created successfully
,D/io.jxcore.node.ConnectionHelper( 4656): onConnected: The total number of connections is now 1
,D/BTIF_SOCK( 1225): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/bt-btif ( 1225): can not find any slot is requesting sdp
,I/bt-btif ( 1225): BTA_JvStartDiscovery
D/bt-btif ( 1225): bta_jv_start_discovery in, sdp_active:0
D/bt-btif ( 1225): call SDP_InitDiscoveryDb, p_data->start_discovery.num_uuid:1
,I/bt-sdp  ( 1225): SDP - Originate started
,D/LGBluetoothServiceAdapter( 1225): [BTUI] connectSocket FD=99 mFd=97
,D/io.jxcore.node.IncomingSocketThread( 4656): Entering thread (ID: 433)
,D/BluetoothSocket( 4656): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[193]}
,E/DataScheduler( 4656): isDataSchedulerEnabled():false
,E/io.jxcore.node.IncomingSocketThread( 4656): Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 4656): java.net.ConnectException: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 4656): 	at libcore.io.IoBridge.connect(IoBridge.java:130)
E/io.jxcore.node.IncomingSocketThread( 4656): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:192)
E/io.jxcore.node.IncomingSocketThread( 4656): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:172)
E/io.jxcore.node.IncomingSocketThread( 4656): 	at java.net.Socket.startupSocket(Socket.java:566)
E/io.jxcore.node.IncomingSocketThread( 4656): 	at java.net.Socket.<init>(Socket.java:226)
E/io.jxcore.node.IncomingSocketThread( 4656): 	at io.jxcore.node.IncomingSocketThread.run(IncomingSocketThread.java:49)
E/io.jxcore.node.IncomingSocketThread( 4656): Caused by: libcore.io.ErrnoException: connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 4656): 	at libcore.io.Posix.connect(Native Method)
E/io.jxcore.node.IncomingSocketThread( 4656): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:85)
E/io.jxcore.node.IncomingSocketThread( 4656): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:176)
E/io.jxcore.node.IncomingSocketThread( 4656): 	at libcore.io.IoBridge.connect(IoBridge.java:128)
E/io.jxcore.node.IncomingSocketThread( 4656): 	... 5 more
,W/io.jxcore.node.ConnectionHelper( 4656): onDisconnected: Incoming connection, peer with ID 38:94:96:B5:06:DC disconnected: Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
I/io.jxcore.node.ConnectionHelper( 4656): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 433
I/io.jxcore.node.IncomingSocketThread( 4656): closeLocalSocketAndStreams: Nothing to close
,I/io.jxcore.node.IncomingSocketThread( 4656): closeBluetoothSocketAndStreams
D/bt-btif ( 1225): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:5, need_close:0, pending size:0
D/bt-btif ( 1225): cleanup slot:17, fd:97, scn:7, sdp_handle:0x0
,D/bt-btif ( 1225): closing rfcomm connection, rfc_handle:0x84
I/bt-btif ( 1225): BTA_JvRfcommClose
D/bt-btif ( 1225): bta_jv_rfcomm_close, rfc handle:132
,D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 5, rfc_cb->handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:2, p_pcb:0x60c9a228, user:17, state:5, jv handle: 0x84
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_OPEN, scn:7, user_data:17
,I/bt-btif ( 1225): bta_jv_free_set_pm_profile_cb(jv_handle: 0x84), idx: 0, app_id: 0xff
D/bt-btif ( 1225): bta_dm_pm_cback: st(1), id(26), app(255)
D/bt-btif ( 1225): stop dm_pm_timer:0
,D/bt-btif ( 1225): bta_jv_rfcomm_close: sec id in use:4, rfc_cb in use:4
D/io.jxcore.node.ConnectionHelper( 4656): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.IncomingSocketThread( 4656): Exiting thread (ID: 433)
,I/bt-sdp  ( 1225): SDP - got conn cnf, sent cfg req, CID: 0x42
,I/bt-sdp  ( 1225): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x42
,W/bt-btif ( 1225): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
D/bt-btif ( 1225): bta_jv_port_mgmt_sr_cback, code:19, port_handle:22
,E/bt-btif ( 1225): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,I/bt-sdp  ( 1225): SDP - Rcvd cfg cfm, CID: 0x42  Result: 0
,W/bt-sdp  ( 1225): process_service_search_attr_rsp
,I/bt-sdp  ( 1225): SDP - disconnect  CID: 0x42
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff f0 1b 00 07 44 49 52 45 43 54 ...
D/wpa_supplicant( 2023): nl80211: Frame event
D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
,D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
,D/wpa_supplicant( 2023): P2P: Parsing P2P IE
,D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
,D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
,D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1,
,D/wpa_supplicant( 2023): P2P: Parsing WPS IE
,D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
,D/wpa_supplicant( 2023): P2P: Device Password ID: 0
,D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
,D/wpa_supplicant( 2023): P2P: Parsing P2P IE
,D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
,D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00,
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5,
,D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
,D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state,
,D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 2023): WPS:  * UUID-E,
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0,
,D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
,D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
,D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff f0 1b 00 07 44 49 52 45 43 54 ...,
,D/wpa_supplicant( 2023): nl80211: Frame event
,D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5,
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
,D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * UUID-E
,D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
,D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
,D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 00 1c 00 07 44 49 52 45 43 54 ...
D/wpa_supplicant( 2023): nl80211: Frame event
D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
,D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
,D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
,D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
,D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
,D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
,D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 00 1c 00 07 44 49 52 45 43 54 ...,
D/wpa_supplicant( 2023): nl80211: Frame event
D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
,D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
,D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388,
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
,D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
,D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10),
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00,
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
,D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
,D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 10 1c 00 07 44 49 52 45 43 54 ...,
,D/wpa_supplicant( 2023): nl80211: Frame event
,D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0,
,D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
,D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
,D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
,D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
,D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
,D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
I/bt-sdp  ( 1225): SDP - Rcvd L2CAP disc cfm, CID: 0x42
,D/bt-btif ( 1225): bta_jv_start_discovery_cback res: 0x0
D/bt-btif ( 1225): bta_jv_cb.uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/bt-btif ( 1225): in, uuid:: 10000000-fa87-c0d0-afac-11de8a390800
D/bt-btif ( 1225): uuid len:16
,D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 10 1c 00 07 44 49 52 45 43 54 ...
D/wpa_supplicant( 2023): nl80211: Frame event
,D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
,D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE,
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
,D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
,D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5,
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
,D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10),
D/wpa_supplicant( 2023): WPS:  * UUID-E
,D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
,D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 30 1c 00 07 44 49 52 45 43 54 ...
D/wpa_supplicant( 2023): nl80211: Frame event,
D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
,D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
,D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0,
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE,
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
,D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
,D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
,D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 30 1c 00 07 44 49 52 45 43 54 ...
D/wpa_supplicant( 2023): nl80211: Frame event
D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
,D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
,D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
,D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE,
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2,
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state,
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
,D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 40 1c 00 07 44 49 52 45 43 54 ...
D/wpa_supplicant( 2023): nl80211: Frame event,
D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
,D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
,D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0,
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
,D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info,
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 59 (NL80211_CMD_FRAME) on p2p0(36:fc:ef:de:0a:e2) A1=ff:ff:ff:ff:ff:ff A2=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=256): 40 00 00 00 ff ff ff ff ff ff 3a 94 96 b5 06 dd ff ff ff ff ff ff 40 1c 00 07 44 49 52 45 43 54 ...
,D/wpa_supplicant( 2023): nl80211: Frame event
D/wpa_supplicant( 2023): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0,
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2,
,D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 2023): P2P: Parsing WPS IE,
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Device Password ID: 0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
,D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 6 length 5
D/wpa_supplicant( 2023): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 1
,D/wpa_supplicant( 2023): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Device Info
D/wpa_supplicant( 2023): nl80211: CMD_FRAME freq=2437 wait=0 no_cck=1 no_ack=1 offchanok=1
,D/wpa_supplicant( 2023): CMD_FRAME - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX command accepted (no ACK); cookie 0x0
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
,D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=07 (unknown) (ack=1)
,D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
,D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=08 (unknown) (ack=1)
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event,
D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=09 (unknown) (ack=1)
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2023): nl80211: Frame TX status event
D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=0a (unknown) (ack=1)
D/wpa_supplicant( 2023): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0x5 (match)),
D/wpa_supplicant( 2023): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (23) received
D/wpa_supplicant( 2023): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
D/wpa_supplicant( 2023): P2P: Driver ended Listen state (freq=2437)
D/wpa_supplicant( 2023): P2P: Skip stop_listen since not in listen_only state.,
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
,D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=0b (unknown) (ack=1)
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2023): nl80211: Frame TX status event
D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=0c (unknown) (ack=1)
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
,D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=0d (unknown) (ack=1)
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
,D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=0e (unknown) (ack=1)
,D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
,D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=0f (unknown) (ack=1)
D/wpa_supplicant( 2023): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 2023): nl80211: MLME event 60 (NL80211_CMD_FRAME_TX_STATUS) on p2p0(36:fc:ef:de:0a:e2) A1=3a:94:96:b5:06:dd A2=36:fc:ef:de:0a:e2
D/wpa_supplicant( 2023): nl80211: MLME event frame - hexdump(len=216): 50 00 00 00 3a 94 96 b5 06 dd 36 fc ef de 0a e2 36 fc ef de 0a e2 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): nl80211: Frame TX status event
D/wpa_supplicant( 2023): nl80211: Action TX status: cookie=010 (unknown) (ack=1),
D/wpa_supplicant( 2023): P2P: Timeout (state=SEARCH)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): nl80211: Disable Probe Request reporting nl_preq=0xb87c9e68
D/bt-btif ( 1225): cannot shorten none-reserved 128 bits uuid
,D/bt-btif ( 1225): shorten uuid:: fa87c0d0-afac-11de-8a39-0800200c9a66
D/bt-btif ( 1225): p_sdp_rec:0x60bbcf08
D/bt-btif ( 1225): jv_dm_cback: event:8, slot id:19
D/bt-btif ( 1225): BTA_JV_DISCOVERY_COMP_EVT, slot id:19, status:0, scn:5
I/bt-btif ( 1225): BTA_JvRfcommConnect
,D/bt-sdp  ( 1225): releasing SDP rsp_list
W/bt-rfcomm( 1225): port_select_mtu credit_rx_max 40, credit_rx_low 10, rx_buf_critical 45
D/bt-btif ( 1225): bta_jv_alloc_rfc_cb port_handle:24 handle:0x85
D/wpa_supplicant( 2023): P2P: Starting search
,D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
,D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type,
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0),
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
,D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header,
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
,D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: Scan frequency 2412 MHz
D/wpa_supplicant( 2023): nl80211: Scan frequency 2437 MHz
D/wpa_supplicant( 2023): nl80211: Scan frequency 2462 MHz
,D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): P2P: Running p2p_scan
D/wpa_supplicant( 2023): nl80211: Event message available
,D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
,D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
,D/bt-btif ( 1225): bta_jv_port_mgmt_cl_cback:code:0, port_handle24
,D/bt-btif ( 1225): bta_jv_port_mgmt_cl_cback code=0 port_handle:24 handle:133
I/bt-btif ( 1225): BTA_JVSetPmProfile handle:0x85, app_id:1
I/bt-btif ( 1225): BTA_JVSetPmProfile handle:0x85, app_id:1
D/bt-btif ( 1225): call send_app_connect_signal, slot id:19, fd:98, rfc scn:5, server:0, rfc_port_handle:0x18
,D/bt-btif ( 1225): on_rfc_connect_ind, connect signal sent, slot id:19, rfc scn:5, server:0
,I/bt-btif ( 1225): bta_jv_set_pm_profile(handle: 0x85, app_id: 1, init_st: 0)
I/bt-btif ( 1225): bta_jv_alloc_set_pm_profile_cb(handle 0x85, app_id 1): idx: 0, (BTA_JV_PM_MAX_NUM: 5), pp_cb: 0x60c9a260
I/bt-btif ( 1225): bta_jv_pm_state_change(p_cb: 0x60c9a324, handle: 0x85, busy/idle_state: 1, app_id: 1, conn_state: 0)
,D/bt-btif ( 1225): bta_dm_pm_cback: st(0), id(26), app(1)
W/bt-btif ( 1225): new conn_srvc id:26, app_id:1
W/bt-btif ( 1225): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 1225): bta_dm_pm_ssr:2, lat:1200
,D/bt-btif ( 1225): bta_dm_pm_set_mode: srvcsid: 26, state: 0, j: 13
I/bt-btif ( 1225): bta_jv_set_pm_profile(handle: 0x85, app_id: 1, init_st: 6)
I/bt-btif ( 1225): bta_jv_alloc_set_pm_profile_cb already allocated. return cb(handle 0x85, app_id 1): idx: 0)
,I/bt-btif ( 1225): bta_jv_pm_state_change(p_cb: 0x60c9a324, handle: 0x85, busy/idle_state: 1, app_id: 1, conn_state: 6)
D/bt-btif ( 1225): bta_dm_pm_cback: st(6), id(26), app(1)
D/bt-btif ( 1225): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 13
,D/bt-btif ( 1225): start dm_pm_timer:0, 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onSocketConnected: Authenticating next: [38:94:96:B5:06:DC 1449681505170.5215 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 4656): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 432)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 4656): onBytesWritten: 77 bytes successfully written (thread ID: 434)
I/bt-btif ( 1225): bta_jv_pm_state_change(p_cb: 0x60c9a324, handle: 0x85, busy/idle_state: 1, app_id: 1, conn_state: 7)
D/bt-btif ( 1225): bta_dm_pm_cback: st(7), id(26), app(1)
D/bt-btif ( 1225): stop dm_pm_timer:0
,D/bt-btif ( 1225): bta_dm_pm_set_mode: srvcsid: 26, state: 7, j: 13
I/bt-btif ( 1225): bta_jv_pm_state_change(p_cb: 0x60c9a324, handle: 0x85, busy/idle_state: 2, app_id: 1, conn_state: 6)
,D/bt-btif ( 1225): bta_dm_pm_cback: st(6), id(26), app(1)
D/bt-btif ( 1225): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 13
,D/bt-btif ( 1225): start dm_pm_timer:0, 5000
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 4656): Outgoing connection initialized (*handshake* thread ID: 434)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 4656): Exiting thread (thread ID: 432)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 4656): Entering thread (ID: 434)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 4656): onBytesRead: Read 77 bytes successfully (thread ID: 434)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 4656): Handshake succeeded with [38:94:96:B5:06:DC 1449681505170.5215 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onAuthenticated: Fully connected: [38:94:96:B5:06:DC 1449681505170.5215 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 4656): Exiting thread (ID: 434)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnected: [38:94:96:B5:06:DC 1449681505170.5215 38:94:96:B5:06:DC]
,I/io.jxcore.node.ConnectionHelper( 4656): onConnected: Outgoing connection, peer ID: 38:94:96:B5:06:DC, name: 1449681505170.5215, Bluetooth address: 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 4656): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
,I/io.jxcore.node.ConnectionHelper( 4656): addNewPeerToListAndNotify: Peer with ID 38:94:96:B5:06:DC already in the list
,I/io.jxcore.node.ConnectionHelper( 4656): onConnected: Outgoing socket thread, for peer with ID 38:94:96:B5:06:DC, created successfully
D/io.jxcore.node.ConnectionHelper( 4656): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 4656): Entering thread (ID: 435)
,D/io.jxcore.node.OutgoingSocketThread( 4656): Server socket local port: 56804
,I/io.jxcore.node.OutgoingSocketThread( 4656): Now accepting connections...
,D/bt-btif ( 1225): bta_jv_port_mgmt_cl_cback:code:19, port_handle24
,D/bt-btif ( 1225): bta_jv_port_mgmt_cl_cback code=19 port_handle:24 handle:133
D/bt-btif ( 1225): BTA_JV_RFCOMM_CLOSE_EVT: user_data:19
D/bt-btif ( 1225): on_rfc_close, slot id:19, fd:98, rfc scn:5, server:0
,D/bt-btif ( 1225): cleanup slot:19, fd:98, scn:0, sdp_handle:0x0
D/bt-btif ( 1225): closing rfcomm connection, rfc_handle:0x85
I/bt-btif ( 1225): BTA_JvRfcommClose
,D/bt-btif ( 1225): bta_jv_rfcomm_close, rfc handle:133
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x5, port.jv_handle: 0x85, state: 2, rfc_cb->handle: 0x85
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:1, curr_sess:1, p_pcb:0x60c9a250, user:19, state:2, jv handle: 0x85
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_CL_OPEN, scn:0, user_data:19
,I/bt-btif ( 1225): bta_jv_free_set_pm_profile_cb(jv_handle: 0x85), idx: 0, app_id: 0x1
D/bt-btif ( 1225): bta_dm_pm_cback: st(1), id(26), app(1)
,D/bt-btif ( 1225): stop dm_pm_timer:0
D/bt-btif ( 1225): bta_jv_rfcomm_close: sec id in use:4, rfc_cb in use:4
,W/bt-btif ( 1225): invalid rfc slot id: 19
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 2023): p2p0: nl80211: New scan results available
D/wpa_supplicant( 2023): p2p0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 12
D/wpa_supplicant( 2023): p2p0: BSS: Add new id 3 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2023): P2P: Scan results received (3 BSS)
D/wpa_supplicant( 2023): P2P: Ignore old scan result for c0:ff:d4:d3:aa:48 (rx_time=1449681211.248635)
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x0
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 06 Group Capability 09
D/wpa_supplicant( 2023): P2P: Attribute 13 length 45
D/wpa_supplicant( 2023): P2P: * Device Info: addr 9e:93:4e:3e:3a:c5 primary device type 3-0050F204-5 device name 'DIRECT-qjWorkCentre 3025' config methods 0x80
D/wpa_supplicant( 2023): P2P: Attribute 14 length 0
D/wpa_supplicant( 2023): P2P: * Group Info
D/wpa_supplicant( 2023): P2P: Parsing WPS IE
D/wpa_supplicant( 2023): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 2023): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 2023): P2P: Parsing P2P IE
D/wpa_supplicant( 2023): P2P: Attribute 2 length 2
D/wpa_supplicant( 2023): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 2023): P2P: Attribute 13 length 32
D/wpa_supplicant( 2023): P2P: * Device Info: addr 3a:94:96:b5:06:dd primary device type 10-0050F204-5 device name 'Galaxy S5-2' config methods 0x188
D/wpa_supplicant( 2023): P2P: Do not update peer entry based on old frame (rx_time=1449681516.868635 last_seen=1449681518.096541)
D/wpa_supplicant( 2023): P2P: State SEARCH -> SEARCH
,D/wpa_supplicant( 2023): P2P: Starting short listen state (state=SEARCH),
,D/WifiMonitor(  964): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 3 c0:ff:d4:d3:aa:48],
,D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 2023): WPS:  * UUID-E
,D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 2023): P2P: * P2P IE header,
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00,
D/wpa_supplicant( 2023): P2P: * Device Info,
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry,
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/wpa_supplicant( 2023): nl80211: Enable Probe Request reporting nl_preq=0xb87c9c88,
,D/wpa_supplicant( 2023): nl80211: Register frame type=0x40 nl_handle=0xb87c9c88,
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=0): [NULL],
,D/wpa_supplicant( 2023): nl80211: Remain-on-channel cookie 0x6 for freq=2437 MHz duration=204,
,D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 2023): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0
,D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=204 cookie=0x6 (match))
D/wpa_supplicant( 2023): p2p0: Event REMAIN_ON_CHANNEL (22) received,
,D/wpa_supplicant( 2023): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0)
,D/wpa_supplicant( 2023): P2P: Starting Listen timeout(0,204800) on freq=2437 based on callback
,D/wpa_supplicant( 2023): P2P: Set timeout (state=SEARCH): 0.224800 sec,
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added,
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
,I/io.jxcore.node.ConnectionHelper( 4656): onListeningForIncomingConnections: Outgoing connection is using port 56804 (peer ID: 38:94:96:B5:06:DC)
,I/jxcore-log( 4656): ok 75 Should be able to connect without error
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): ok 76 Port should be within range
I/jxcore-log( 4656): 
,D/io.jxcore.node.ConnectionHelper( 4656): disconnectOutgoingConnection: Trying to close connection to peer with ID 38:94:96:B5:06:DC
,I/io.jxcore.node.ConnectionHelper( 4656): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 38:94:96:B5:06:DC
,I/io.jxcore.node.OutgoingSocketThread( 4656): close
,I/io.jxcore.node.OutgoingSocketThread( 4656): closeLocalSocketAndStreams: Nothing to close
,I/io.jxcore.node.OutgoingSocketThread( 4656): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 4656): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 4656): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 4656): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 4656): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:55)
E/io.jxcore.node.OutgoingSocketThread( 4656): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:98)
E/io.jxcore.node.OutgoingSocketThread( 4656): 	at java.net.ServerSocket.implAccept(ServerSocket.java:203)
E/io.jxcore.node.OutgoingSocketThread( 4656): 	at java.net.ServerSocket.accept(ServerSocket.java:128)
E/io.jxcore.node.OutgoingSocketThread( 4656): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:71)
,W/io.jxcore.node.ConnectionHelper( 4656): onDisconnected: Outgoing connection, peer with ID 38:94:96:B5:06:DC disconnected: Failed to create local streams: Socket closed
,D/io.jxcore.node.ConnectionHelper( 4656): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 4656): disconnectOutgoingConnection: Successfully disconnected (peer ID: 38:94:96:B5:06:DC
,I/jxcore-log( 4656): ok 77 Should be able to disconnect without error
I/jxcore-log( 4656): 
,E/io.jxcore.node.ConnectionHelper( 4656): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
,D/io.jxcore.node.ConnectionHelper( 4656): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.OutgoingSocketThread( 4656): Exiting thread (ID: 435)
,I/jxcore-log( 4656): setting stopBroadcasting callback and ending test.
I/jxcore-log( 4656): 
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 2023): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0x6 (match))
D/wpa_supplicant( 2023): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (23) received
D/wpa_supplicant( 2023): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
D/wpa_supplicant( 2023): P2P: Driver ended Listen state (freq=2437)
,D/wpa_supplicant( 2023): P2P: Skip stop_listen since not in listen_only state.
,D/wpa_supplicant( 2023): P2P: Timeout (state=SEARCH)
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 2023): nl80211: Disable Probe Request reporting nl_preq=0xb87c9c88
D/wpa_supplicant( 2023): P2P: Starting search
D/wpa_supplicant( 2023): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 2023): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 2023): WPS:  * Request Type
D/wpa_supplicant( 2023): WPS:  * Config Methods (4388)
D/wpa_supplicant( 2023): WPS:  * UUID-E
D/wpa_supplicant( 2023): WPS:  * Primary Device Type
D/wpa_supplicant( 2023): WPS:  * RF Bands (3)
D/wpa_supplicant( 2023): WPS:  * Association State
D/wpa_supplicant( 2023): WPS:  * Configuration Error (0)
D/wpa_supplicant( 2023): WPS:  * Device Password ID (0)
D/wpa_supplicant( 2023): WPS:  * Manufacturer
D/wpa_supplicant( 2023): WPS:  * Model Name
D/wpa_supplicant( 2023): WPS:  * Model Number
D/wpa_supplicant( 2023): WPS:  * Device Name
D/wpa_supplicant( 2023): WPS:  * Version2 (0x20)
D/wpa_supplicant( 2023): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 2023): P2P: * P2P IE header
D/wpa_supplicant( 2023): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 2023): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 2023): p2p0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=7): 44 49 52 45 43 54 2d
D/wpa_supplicant( 2023): nl80211: Scan extra IEs - hexdump(len=143): dd 7a 00 50 f2 04 10 4a 00 01 10 10 3a 00 01 01 10 08 00 02 43 88 10 47 00 10 4d 54 bb 4b f9 ab ...
D/wpa_supplicant( 2023): nl80211: Scan frequency 2412 MHz
D/wpa_supplicant( 2023): nl80211: Scan frequency 2437 MHz
D/wpa_supplicant( 2023): nl80211: Scan frequency 2462 MHz
,D/wpa_supplicant( 2023): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): P2P: Running p2p_scan
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
,D/wpa_supplicant( 2023): p2p0: nl80211: Scan trigger
,I/jxcore-log( 4656): # setup
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): Toggling radios to false
I/jxcore-log( 4656): 
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  964): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42d87348 mBinding = false
,D/BluetoothManagerService(  964): Message: 2
,D/WifiService(  964): setWifiEnabled: false pid=4656, uid=10304
,E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothManagerService(  964): Sending off request.
,I/WifiService(  964): setWifiEnabled startWifiDelaySendMsg true
D/BluetoothAdapterService(1115750512)( 1225): disable() called...
D/BluetoothAdapterState( 1225): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
I/BluetoothAdapterState( 1225): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1225): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btif ( 1225): btif_set_adapter_property type: 7, len 4, 0x428fc520
I/bt-btif ( 1225): set property scan mode : 0
I/bt-btif ( 1225): bta_dm_sm_execute event:0x3
I/bt-btif ( 1225): btif_in_storage_request_copy_cb
I/bt-btif ( 1225): execute storage request event : 2
I/bt-btif ( 1225): type: 7, len 4, 0x605ef706
D/bt-btif ( 1225): in, bd addr:, prop type:7, len:4
I/bt-btif ( 1225): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterState( 1225): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/WifiStateMachine(  964): handleMessage: E msg.what=131084
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/BluetoothAdapterState( 1225): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
,W/Settings(  964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/bluedroid( 1225): disable 1
I/bt-btif ( 1225): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
,D/bt-btif ( 1225): h:6, process_cmd_sock return false, exit...
,D/bt-btif ( 1225): socket poll thread exiting, h:6
D/bt-btif ( 1225): cleanup slot:1, fd:89, scn:19, sdp_handle:0x1000a
D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,I/jxcore-log( 4656): Radios toggled
I/jxcore-log( 4656): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onBluetoothAdapterScanModeChanged: Mode changed to 20
,D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000a
,V/BluetoothPbapService( 1225): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
,E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x1, port.jv_handle: 0x81, state: 4, rfc_cb->handle: 0x81
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a0e8, p_pcb->port_handle:6
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a0e8, user:1, state:4, jv handle: 0x81
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:19, user_data:1
,D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
D/bt-btif ( 1225): cleanup slot:2, fd:91, scn:6, sdp_handle:0x1000b
D/BluetoothManagerService(  964): Message: 60
,D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000b
V/BluetoothMapService( 1225): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/WifiStateMachine(  964): invokeExitMethods: ConnectModeState
I/bt-btif ( 1225): BTA_JvDeleteRecord
,D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:12
D/BluetoothManagerService(  964): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x2, port.jv_handle: 0x82, state: 4, rfc_cb->handle: 0x82
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a0fc, p_pcb->port_handle:7
,D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a0fc, user:2, state:4, jv handle: 0x82
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:6, user_data:2
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1225): cleanup slot:3, fd:94, scn:12, sdp_handle:0x1000c
D/WifiStateMachine(  964): invokeExitMethods: DriverStartedState
,D/BluetoothManagerService(  964): Bluetooth State Change Intent: 12 -> 13
E/BtOppRfcommListener( 1225): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000c
I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:11
,I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x3, port.jv_handle: 0x83, state: 4, rfc_cb->handle: 0x83
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a110, p_pcb->port_handle:8
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a110, user:3, state:4, jv handle: 0x83
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:12, user_data:3
,D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:1, rfc_cb in use:1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onBluetoothAdapterScanModeChanged: Bluetooth disabled, stopping...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): shutdown
,D/bt-btif ( 1225): cleanup slot:18, fd:96, scn:7, sdp_handle:0x1000d
,D/bt-btif ( 1225): del_rfc_sdp_rec: handle:0x1000d
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:549)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:526)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onIncomingConnectionFailed: Socket is null
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4656): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4656): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 4656): stop: Stopping services
I/bt-btif ( 1225): BTA_JvDeleteRecord
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:10
,I/bt-btif ( 1225): BTA_JvRfcommStopServer
E/bt-btif ( 1225): bta_jv_rfcomm_stop_server
D/bt-btif ( 1225): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x184, state: 4, rfc_cb->handle: 0x84
,D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: p_pcb:0x60c9a23c, p_pcb->port_handle:23
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60c9a23c, user:18, state:4, jv handle: 0x184
D/bt-btif ( 1225): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:18
D/bt-btif ( 1225): bta_jv_rfcomm_stop_server: sec id in use:0, rfc_cb in use:0
,D/bt-btif ( 1225): leaving
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:9
I/bt-btif ( 1225): Removing UUID=0x1116 from EIR
D/bt-btif ( 1225): BTA is generating EIR
,I/bt-btif ( 1225): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1225): Removing UUID=0x1116 from EIR
D/bt-btif ( 1225): BTA is generating EIR
,I/bt-btif ( 1225): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1225): Removing UUID=0x1117 from EIR
D/bt-btif ( 1225): BTA is generating EIR
,I/bt-btif ( 1225): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1225): Removing UUID=0x1115 from EIR
D/bt-btif ( 1225): BTA is generating EIR
,I/bt-btif ( 1225): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04011460
I/bt-btif ( 1225): bta_dm_sm_execute event:0x1
D/bt-btif ( 1225): bta_sys_disable: module 0
,I/bt-btif ( 1225): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 1225): bta_ag_del_records 0
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:8
,I/bt-btif ( 1225): Removing UUID=0x1112 from EIR
I/bt-btif ( 1225): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04001460
D/bt-btif ( 1225): bta_ag_del_records 1
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:7
,I/bt-btif ( 1225): Removing UUID=0x111F from EIR
I/bt-btif ( 1225): bta_dm_eir_update_uuid UUID bit mask=0x00000494 00001460
D/bt-btif ( 1225): bta_ag_scb_dealloc 1
,W/bt-obex ( 1225): Ignore event 10 in state 1
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:6
I/bt-btif ( 1225): Removing UUID=0x1106 from EIR
I/bt-btif ( 1225): bta_dm_eir_update_uuid UUID bit mask=0x00000494 00001420
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:5
,I/bt-btif ( 1225): Removing UUID=0x112D from EIR
I/bt-btif ( 1225): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00001420
I/bt-btif ( 1225): bta_av_del_rc  handle: 0 status=0x10, rc_acp_handle:0, idx:1
I/bt-btif ( 1225): end del_rc handle: 255 status=0x0, rc_acp_handle:255, lidx:0
,D/bt-btif ( 1225): bta_av_cleanup
D/bt-btif ( 1225): deregistered 64(h65)
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:4
I/bt-btif ( 1225): Removing UUID=0x110A from EIR
I/bt-btif ( 1225): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00001020,
D/bt-btif ( 1225): audio 0x0, video: 0x0, disable:1
D/bt-sdp  ( 1225): SDP_DeleteRecord ok, num_records:3
I/bt-btif ( 1225): Removing UUID=0x110C from EIR
I/bt-btif ( 1225): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00000020
D/bt-btif ( 1225): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1225): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1225): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1225): bta_gattc_disable
I/bt-att  ( 1225): GATT_Deregister gatt_if=3
I/bt-att  ( 1225): GATT_Listen gatt_if=3,
D/bt-btif ( 1225): bta_dm_gattc_callback event = 1
I/bt-att  ( 1225): GATT_Deregister gatt_if=4
I/bt-att  ( 1225): GATT_Listen gatt_if=4
D/bt-btif ( 1225): bta_hh_gattc_callback event = 1
I/bt-btif ( 1225): bta_dm_search_sm_execute state:0, event:0x206
,E/bt-btif ( 1225): bta_gattc_deregister Deregister Failed, unknown client cif,
D/bt-btif ( 1225): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/bt-btif ( 1225): btif_fts_upstreams_evt: event=BTA_FTS_DISABLE_EVT
I/bt-btif ( 1225): File Transfer: Disable complete
D/bt-btif ( 1225): btif_hh_upstreams_evt: event=BTA_HH_DISABLE_EVT
,D/IOP_DB_BT( 1225): db_close: nbr users 0
D/IOP_DB_BT( 1225): db_close: free database
,D/btif_config_util( 1225): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiP2pService(  964): InactiveState{ when=0 what=139298 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=139298 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState clear service
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=56): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 30 61 34 33 36 66 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
,D/WifiNative-p2p0(  964):    returned true
,D/LGBluetoothAPIService( 1157): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothMapService( 1225): onReceive
,D/BluetoothMapService( 1225): STATE_TURNING_OFF
D/BluetoothMapService( 1225): MAP Service closeService in
,D/LGBluetoothMapAdapter( 1225): [BTUI] LGBluetoothMapAdapter cleanup
,V/BluetoothMapService( 1225): MAP Service closeService out
V/BtOppService( 1225): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 1225): stopping Accept Thread
,V/BtOppRfcommListener( 1225): close mBtServerSocket
,V/BtOppRfcommListener( 1225): waiting for thread to terminate
,I/BtOppRfcommListener( 1225): BluetoothSocket listen thread finished
,V/BtOppRfcommListener( 1225): done waiting for thread to terminate
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): stopWifiPeerDiscovery: Stopped
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313530373338360634363536227d0a636f72646f7661703270c00c001001
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 4656): onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=212): 50 32 50 5f 53 45 52 56 49 43 45 5f 44 45 4c 20 62 6f 6e 6a 6f 75 72 20 34 36 37 62 32 32 37 32 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 467b227261223a2233343a66633a65663a39643a39333a3062222c227069223a2233343a66633a65663a39643a39333a3062222c22706e223a22313434393638313530373338360634363536227d0a636f72646f7661703270c00c001001'
D/WifiNative-p2p0(  964):    returned true
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
D/WifiStateMachine(  964): invokeExitMethods: DriverStartedStateExt
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine(  964): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine(  964): handleMessage: X
V/BtOppService( 1225): onDestroy
,D/WifiNative-p2p0(  964): doBoolean: P2P_SERV_DISC_CANCEL_REQ b87c9a00
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=33): 50 32 50 5f 53 45 52 56 5f 44 49 53 43 5f 43 41 4e 43 45 4c 5f 52 45 51 20 62 38 37 63 39 61 30 ...
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_SERV_DISC_CANCEL_REQ b87c9a00'
D/wpa_supplicant( 2023): P2P: Cancel pending SD query 0xb87c9a00
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 4656): Local services cleared successfully
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_STOP_FIND
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=13): 50 32 50 5f 53 54 4f 50 5f 46 49 4e 44
D/wpa_supplicant( 2023): p2p0: Control interface command 'P2P_STOP_FIND'
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 2023): P2P-FIND-STOPPED 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): P2P: State SEARCH -> IDLE
,D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Service requests cleared successfully
D/LGBluetoothOppAdapter( 1225): [BTUI] LGBluetoothOppAdapter cleanup
D/WifiP2pService(  964): InactiveState{ when=-10ms what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-10ms what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState clear service request
D/WifiP2pService(  964): remove channel information from framework
,D/WifiP2pService(  964): InactiveState{ when=-8ms what=139268 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  964): Event [P2P-FIND-STOPPED ]
,D/WifiNative-p2p0(  964):    returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 4656): Peer discovery stopped successfully
,D/WifiMonitor(  964): WifiMonitorSingleton gotten
,D/WifiMonitor(  964): stopMonitoring(p2p0) = android.net.wifi.p2p.WifiP2pService$P2pStateMachine@43097e08
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4656): onWifiStateChanged: State changed to 1
,D/WfdService( 1157): Waiting for Wifi disabling
,E/WifiServiceExtension(  964): No p2p device connected
D/WifiP2pService(  964): InactiveState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pDisablingState
D/WifiP2pService(  964): P2pDisablingState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pDisablingState{ when=-3ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-5ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pDisablingState{ when=-5ms what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-6ms what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pDisablingState{ when=-6ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-7ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): handleMessage: E msg.what=131205
D/WifiStateMachine(  964): processMsg: WaitForP2pDisableState
D/WifiStateMachine(  964): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
,D/WifiStateMachine(  964): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine(  964): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine(  964): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/LGBluetoothUtils( 2576): [BTUI] resetProperty - success
,E/LGBluetoothEventManager( 2576): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,V/BluetoothPbapReceiver( 1225): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1225): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1225): ***********state = 13
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiP2pService(  964): p2p socket connection lost
D/WifiP2pService(  964): P2pDisabledState
W/ContextImpl( 2576): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
D/WifiP2pService(  964): P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  964):    returned true
D/DhcpStateMachine(  964): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothPbapReceiver( 1225): ***********Calling start service!!!! with action = null
D/CommandListener(  264): Clearing all IP addresses on wlan0
V/BluetoothPbapService( 1225): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1225): state: 13
V/BluetoothPbapService( 1225): Pbap Service closeService in
I/bt-btif ( 1225): btif_dm_cancel_discovery
I/bt-btif ( 1225): bta_dm_search_sm_execute state:0, event:0x201
V/BluetoothPbapService( 1225): successfully stopped pbap service
V/BluetoothPbapService( 1225): Pbap Service closeService out
V/BluetoothPbapService( 1225): Pbap Service onDestroy
V/BluetoothPbapService( 1225): Pbap Service closeService in
V/BluetoothPbapService( 1225): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 1225): [BTUI] cleanup
D/DockEventReceiver( 2576): finishStartingService: stopping service
D/WifiStateMachine(  964): addressRemoved: 192.168.1.121/24 on wlan0 flags 128 scope 0
D/LGBluetoothAuthorization( 2576): [BTUI] cancel All Notification
D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): stopping supplicant
D/WifiMonitor(  964): WifiMonitorSingleton gotten
,D/WifiNative-p2p0(  964): doBoolean: TERMINATE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,D/BluetoothPbap( 2576): Proxy object disconnected
D/PbapServerProfile( 2576): Bluetooth service disconnected
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
D/QCNEA   (  431): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  431): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  431): |CAC| updateNetCfgInfo
V/QCNEA   (  431): |CAC| *********************************************
V/QCNEA   (  431): |CAC|                   Netconfig               
V/QCNEA   (  431): |CAC| *********************************************
V/QCNEA   (  431): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  431): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  431): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  431): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  431): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  431): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  431): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  431): |CAC| *********************************************
D/QCNEA   (  431): |CAC| Received bssid= 
D/QCNEA   (  431): |CAC| net type = 3
V/QCNEA   (  431): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  431): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  431): |CAC| 	ssid           =NG700
V/QCNEA   (  431): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  431): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  431): |CAC| *********************************************
D/QCNEA   (  431): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  431): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  431): |CAC| dispatchNetCfg: updating:0xb7a6e8dc
D/QCNEA   (  431): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/BluetoothPermissionRequest( 2576): onReceive
,D/LGBluetoothAuthorization( 2576): [BTUI] cancel All Notification
D/WifiHS20(  964): hidePasspointNotification off =false
D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
,D/LGBluetoothResetSettingReceiver( 2576): return without doing reset settings.
D/wpa_supplicant( 2023): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
,D/wpa_supplicant( 2023): p2p0: Removing interface p2p0
D/wpa_supplicant( 2023): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 2023): TDLS: Tear down peers
D/wpa_supplicant( 2023): p2p0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2023): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2023): p2p0: No keys have been configured - skip key clearing
,V/BluetoothOppReceiver( 1225): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 1225): [BTUI] cancel opp incoming file confirm notification
D/WifiNative-p2p0(  964):    returned true
D/WifiStateMachine(  964): setWifiState: disabling
E/WifiStateMachine(  964): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  964): useWiFiOffloading() : false
E/WifiStateMachine(  964): CONFIG_LGE_WLAN_PATH : true
,D/BluetoothOppNotification( 1225): [BTUI] cancel opp active transfer file notification
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
,D/WifiStateMachine(  964): processMsg: SupplicantStoppingState
,V/WfdStateTracker( 1157): WfdStateTracker handleDirectStateChangedEvent: 6
,I/WifiServiceExtension(  964): WIFI_STATE_CHANGED_ACTION [0]
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
,E/Parcel  (  431): Reading a NULL string not supported here.
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: SupplicantStoppingState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  964): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5648 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
,V/        (  264): RouteController
D/wpa_supplicant( 2023): p2p0: BSS: Remove id 3 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): p2p0: BSS: Remove id 1 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): p2p0: Cancelling scan request
D/wpa_supplicant( 2023): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): p2p0: Cancelling authentication timeout
D/wpa_supplicant( 2023): p2p0: P2P: Disable P2P since removing the management interface is being removed
D/wpa_supplicant( 2023): P2P: Stopping find
D/wpa_supplicant( 2023): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2023): P2P: State IDLE -> IDLE
D/wpa_supplicant( 2023): wpa_driver_set_ap_wps_p2p_ie: Entry
,I/wpa_supplicant( 2023): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/wpa_supplicant( 2023): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/HyLog   ( 5648): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5648): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5648): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
,D/WifiMonitor(  964): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 3 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  964): Dropping event because monitor (p2p0) is stopped
D/WifiMonitor(  964): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 1 9e:93:4e:3e:ba:c5]
V/        (  264): RouteController
D/WifiMonitor(  964): Dropping event because monitor (p2p0) is stopped
D/WifiMonitor(  964): Event [P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd]
,D/WifiMonitor(  964): Dropping event because monitor (p2p0) is stopped
D/WifiMonitor(  964): Event [P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5]
,D/WifiMonitor(  964): Dropping event because monitor (p2p0) is stopped
D/dalvikvm( 1142): GC_CONCURRENT freed 9456K, 13% free 69093K/78748K, paused 6ms+10ms, total 72ms
,D/dalvikvm( 1142): WAIT_FOR_CONCURRENT_GC blocked 54ms
V/        (  264): RouteController
,D/AuthorizationBluetoothService( 1554): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Wireless_Storage( 4852): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
I/ActivityManager(  964): Killing 4566:com.lge.email/u0a24 (adj 15): empty #17
,W/NetworkManagementService(  964): route cmd failed: 
W/NetworkManagementService(  964): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x62808078 clazz=0xb8b00001 iface=wlan0 mask=0x3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
,V/NativeCrypto( 1554): Read error: ssl=0x61142688: I/O error during system call, Connection timed out
,V/NativeCrypto( 1554): SSL shutdown failed: ssl=0x61142688: I/O error during system call, Broken pipe
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5670 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/wpa_supplicant( 2023): netlink: Operstate: linkmode=0, operstate=6
D/wpa_supplicant( 2023): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 2023): nl80211: Unsubscribe mgmt frames handle 0xb87c4c28 (mode change)
I/wpa_supplicant( 2023): p2p0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/wpa_supplicant( 2023): [ITEC] Close WIFLUS socket interface - START
I/wpa_supplicant( 2023): [ITEC] Close WIFLUS read interface - DONE
,I/wpa_supplicant( 2023): HY wiflus comm channel de-initialized : wiflus = 0
,D/wpa_supplicant( 2023): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 2023): wlan0: Removing interface wlan0
D/wpa_supplicant( 2023): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2023): TDLS: Tear down peers
D/wpa_supplicant( 2023): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiMonitor(  964): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,D/WifiMonitor(  964): Dropping event because monitor (p2p0) is stopped
D/wpa_supplicant( 2023): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2023): wlan0: Deauthentication notification
D/wpa_supplicant( 2023): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2023): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2023): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2023): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2023): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb87b4d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/WifiStateMachine(  964): handleMessage: E msg.what=147460
D/WifiStateMachine(  964): processMsg: SupplicantStoppingState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2023): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
W/wpa_supplicant( 2023): USIM:  scard_deinit function
D/WifiStateMachine(  964): processMsg: SupplicantStoppingState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
,D/HyLog   ( 5670): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5670): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5670): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/PCSuite ( 5670): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5670): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5670): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: Cancelling authentication timeout
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
,I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5686 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  964): Killing 4793:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5686): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5686): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=0, operstate=6
,D/HyLog   ( 5686): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2023): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2023): nl80211: Unsubscribe mgmt frames handle 0xb87b5590 (mode change)
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/wpa_supplicant( 2023): [ITEC] Close WIFLUS socket interface - START
I/wpa_supplicant( 2023): [ITEC] - NOT INITIALIZED - DONE
D/wpa_supplicant( 2023): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 2023): Get randomness: len=20 entropy=24
,D/Tethering(  964): InitialState.processMessage what=4
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,D/Tethering(  964): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/WifiStateMachine(  964): handleMessage: E msg.what=147458
D/WifiStateMachine(  964): processMsg: SupplicantStoppingState
D/WifiStateMachine(  964): Supplicant connection lost
D/WifiMonitor(  964): WifiMonitorSingleton gotten
,D/Tethering(  964): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiStateMachine(  964): setWifiState: disabled
,D/WifiOffDelayIfNotUsed(  964): stopMonitoring
W/Settings( 5076): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiActivationWhileCharging(  964): register : WIFI_ACTIVATION_WHILE_CHARGING_OFF[1]
,E/WifiStateMachine(  964): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  964): useWiFiOffloading() : false
E/WifiStateMachine(  964): CONFIG_LGE_WLAN_PATH : true
,D/DhcpStateMachine(  964): StoppedState
,D/QRemote ( 5686): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/WifiStateMachine(  964): transitionTo: destState=InitialState
,D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  964): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine(  964): invokeEnterMethods: InitialState
,V/WfdStateTracker( 1157): WfdStateTracker handleDirectStateChangedEvent: 0
I/WifiServiceExtension(  964): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServiceExtension(  964): batteryPsActivateMsgHandler : state:0 event:1
,I/WifiServiceExtension(  964): batteryPsActivateMsgHandler : this is not treated
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
E/Parcel  (  431): Reading a NULL string not supported here.
,E/Parcel  (  431): Reading a NULL string not supported here.
,W/Settings( 1424): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QRemote ( 5686): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 5686): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 5686): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 5686): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 5686): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 5686): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5686): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5686): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
,D/PCSuite ( 5670): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/UsbSettingsReceiver( 2576): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2576): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2576): [AUTORUN] sys.usb.state = boot,adb
,D/UsbSettingsReceiver( 2576): [AUTORUN] persist.sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2576): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/Config  ( 2576): getOperator() : OPEN
D/UsbSettingsControl( 2576): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 2576): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 2576): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 2576): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2576): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsControl( 2576): [AUTORUN] setTetherStatus() : status=false
,D/LGDMClient( 2836): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,I/ActivityManager(  964): Killing 4810:com.android.chrome/u0a63 (adj 15): empty #17
,D/LGDMSGCM( 4838): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 2836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/PCSuite ( 5670): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 5670): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5670): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 4838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131101
,D/WifiStateMachine(  964): processMsg: InitialState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196614
D/WifiStateMachine(  964): processMsg: InitialState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Tethering(  964): MasterInitialState.processMessage what=3
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4023): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4023): onReceive
,D/AppUp4:CustFacade( 4023): Context : android.app.ReceiverRestrictedContext@427ff410
D/AppUp4:CustFacade( 4023): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4023): isOpenOperator : true
,D/AppUp4:CustFacade( 4023): isPhone : true
,I/LicenseContentProvider( 2952): start selecting data
,D/SIMObserver( 2952): simInfo1
,I/AppUp4:EulaManager( 4023): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4023): begin check event
,I/AppUp4:CustModeStarterReceiver( 4023): Event For GoodConnectivity
,I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5714 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 5714): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5714): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5714): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/bt-att  ( 1225): GATT   ATT protocol channel with BDA: 389496b506dc is disconnected
,D/bt-att  ( 1225): gatt_is_bda_in_the_srv_chg_clt_list :38-94-96-b5-06-dc
D/bt-att  ( 1225): bda is in the srv chg clt list
D/bt-att  ( 1225): gatt_cleanup_upon_disc 
D/bt-att  ( 1225): exit gatt_cleanup_upon_disc 
,D/bt-att  ( 1225): ATT disconnected
I/bt-smp  ( 1225): SMDBG l2c smp_connect_cback 
E/bt-btm  ( 1225): btm_sec_disconnected - Clearing Pending flag
I/bt-btif ( 1225): bta_dm_sm_execute event:0x8
,I/bt-btif ( 1225): bta_dm_sm_execute event:0x8
I/bt-btif ( 1225): btif_dm_upstreams_cback  ev: BTA_DM_LINK_DOWN_EVT
,D/bt-btif ( 1225): BTA_DM_LINK_DOWN_EVT. Sending BT_ACL_STATE_DISCONNECTED
,I/bt-btif ( 1225): HAL bt_hal_cbacks->acl_state_changed_cb
,D/WifiServiceExtension(  964): Connected BT device : 0
,I/bt-btif ( 1225): GT^^ : btif_dm_ssp_get_justworks: remote_addr=38:94:96:b5:06:dc
D/bt-btif ( 1225): in, bd addr:38:94:96:b5:06:dc, prop type:14, len:4
I/bt-btif ( 1225): GT^^ : btif_dm_ssp_get_justworks: justworks =0
I/bt-btif ( 1225): btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
,I/bt-btif ( 1225): a2dp busy level set to 0
,D/bt-btif ( 1225): btif_check_send_bt_off() btif_core_state= (4),ACL links = (0), LE links = 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 5714): DownloadService onCreate
,I/DownloadManager( 5714): in removeSpuriousFiles
,V/DownloadManager( 5714): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5714): created cursor android.database.sqlite.SQLiteCursor@42828568 on behalf of 5714
,I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=5744 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
I/DownloadManager( 5714): in trimDatabase
V/DownloadManager( 5714): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5714): DownloadService onStartCommand
V/DownloadManager( 5714): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5714): created cursor android.database.sqlite.SQLiteCursor@4282b210 on behalf of 5714
V/DownloadManager( 5714): created cursor android.database.sqlite.SQLiteCursor@4282d830 on behalf of 5714
,V/DownloadManager( 5714): DownloadService onDestroy
I/ActivityManager(  964): Killing 4825:com.lge.drmservice/u0a66 (adj 15): empty #17
,D/HyLog   ( 5744): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5744): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5744): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/LGEmail ( 5744): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 5744): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,W/BaseRuntimeLoader( 5744): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5744): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5744): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5744): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 5744): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 5744): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 5744): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4324): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4324): networkInfo.isConnected() = false
,W/linker  ( 5744): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 5744): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 5744): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 5744): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 5744): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,D/HtmlEditor( 5744): register_HtmlEditor, Success
D/HtmlEditor( 5744): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
,D/HtmlEditor( 5744): register_HtmlEditorTimer, Success
D/HtmlEditor( 5744): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
,D/HtmlEditor( 5744): register_HtmlEditorDownloader, Success
D/HtmlEditor( 5744): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5744): register_HtmlEditorFont, Success
,D/HtmlEditor( 5744): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5744): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 5744): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 5744): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 5744): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 5744): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 5744): JNI_OnLoad Success
,I/HubEmail( 5744): JNI_OnLoad()
I/HubEmail( 5744): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5744): registerNatives()
,I/HubEmail( 5744): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5744): registerNativeMethods()
,I/HubEmail( 5744): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5763 uid=10052 gids={50052, 3003}
W/Settings( 5744): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  964): Killing 4886:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,D/HyLog   ( 5763): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5763): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5763): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5763): [loadRssi] File not exist 
,V/LGRssiData( 5763): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5763): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 5763): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5763): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5763): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5763): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 5763): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5763): onReceive CONNECTIVITY_CHANGE networkType=1
,V/TelephonyAutoProfiling( 5763): [getMatchedProfile] selected file : /cust/config/featureset.xml
,V/TelephonyAutoProfiling( 5763): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5763): [getValue] FEATURE key : vzw_roaming_state, value : null
,E/PhoneMonitor( 5763): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5763): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5777 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  964): Killing 4919:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/HyLog   ( 5777): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5777): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5777): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5794 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  964): Killing 5076:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 5794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5794): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): Killing 5126:com.android.contacts/u0a21 (adj 15): empty #17
D/LGDMClient( 2836): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4838): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4852): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Wireless_Storage( 4852): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4852): intf.getDisplayName() = lo
I/Wireless_Storage( 4852): intf.getDisplayName() = sit0
I/Wireless_Storage( 4852): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4852): intf.getDisplayName() = teql0
I/Wireless_Storage( 4852): intf.getDisplayName() = wlan0
,I/Wireless_Storage( 4852): intf.getDisplayName() = rev_rmnet8
I/Wireless_Storage( 4852): intf.getDisplayName() = rev_rmnet2
,I/Wireless_Storage( 4852): intf.getDisplayName() = rev_rmnet3
I/Wireless_Storage( 4852): intf.getDisplayName() = rev_rmnet4
I/Wireless_Storage( 4852): intf.getDisplayName() = rev_rmnet5
,I/Wireless_Storage( 4852): intf.getDisplayName() = rev_rmnet6
I/Wireless_Storage( 4852): intf.getDisplayName() = rev_rmnet7
,I/Wireless_Storage( 4852): intf.getDisplayName() = rev_rmnet0
I/Wireless_Storage( 4852): intf.getDisplayName() = rev_rmnet1
I/Wireless_Storage( 4852): intf.getDisplayName() = rmnet0
,I/Wireless_Storage( 4852): intf.getDisplayName() = rmnet1
I/Wireless_Storage( 4852): intf.getDisplayName() = rmnet2
,I/Wireless_Storage( 4852): intf.getDisplayName() = rmnet3
I/Wireless_Storage( 4852): intf.getDisplayName() = rmnet4
,I/Wireless_Storage( 4852): intf.getDisplayName() = rmnet5
I/Wireless_Storage( 4852): intf.getDisplayName() = rmnet6
,I/Wireless_Storage( 4852): intf.getDisplayName() = rmnet7
,I/Wireless_Storage( 4852): CONNECT : WIFI_DISCONNECT
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5811 uid=10104 gids={50104, 3003, 1028, 1015}
,D/HyLog   ( 5811): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5811): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5811): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 3ms+5ms, total 44ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 3ms+4ms, total 30ms
,W/GAV2    ( 5811): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 27ms
,V/WebViewChromium( 5811): Binding Chromium to the main looper Looper (main, tid 1) {427eb558}
,I/chromium( 5811): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5811): Initializing chromium process, renderers=0
,W/chromium( 5811): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5811): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5811): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5811): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5811): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5811): Remote Branch: 
I/Adreno-EGL( 5811): Local Patches: 
I/Adreno-EGL( 5811): Reconstruct Branch: 
,I/NSApplication( 5811): Starting up...
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt-btif ( 1225): bta_sys_sm_execute state:2, event:0x3
D/bt-btif ( 1225): bta_sys_hw_api_disable for 0, active modules: 0x0001
D/bt-btif ( 1225): bta_sys_disable: module 0
I/bt-btif ( 1225): bta_sys_sm_execute state:3, event:0x4
D/bt-btif ( 1225): bta_sys_hw_evt_disabled - module 0x0
D/bt-btif ( 1225):  bta_dm_sys_hw_cback with event: 0
I/bt-btif ( 1225): btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
I/bt-btif ( 1225): btif_disable_bluetooth_evt()::btif_core_cb: is_radio_req: 0, radio_ref_count: 0, state: 4
D/bt-btif ( 1225): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1225): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1225): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1225): audio 0x0, video: 0x0, disable:1
W/bt-l2cap( 1225): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1225): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1225): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1225): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1225): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1225): ag scb idx 1 not allocated
,E/bt-btif ( 1225): BTA AG is already disabled, ignoring ...
I/bt-btif ( 1225): HC lib lpm enable=0 return 0
D/bt-btif ( 1225): bte_main_disable
,D/bt-btif ( 1225): bte_hci_disable
,D/bt_hwcfg( 1225): hw_epilog_process
,I/bt-btif ( 1225): HC lpm_result_cb 0
I/ActivityManager(  964): Killing 5140:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/iu.Environment( 1964): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1964): num queued entries: 0
,I/iu.UploadsManager( 1964): num updated entries: 0
,I/iu.SyncManager( 1964): NEXT; no task
,D/bt_hwcfg( 1225): hw_epilog_cback Opcode:0x0C03 Status: 0
,I/bt_hci_bdroid( 1225): bt_hc_worker_thread exiting
,W/bt_userial( 1225): select_read return size <=0:0, exiting userial_read_thread
,I/bt_userial_vendor( 1225): device fd = 84 close
,D/BTSNOOP-DISP( 1225): btsnoop_close
,I/GKI_LINUX( 1225): GKI_destroy_task: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1225): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1225): GKI_destroy_task: GKI_destroy_task(): task [BTU] terminated
,I/GKI_LINUX( 1225): GKI_freeze: GKI_freeze
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,I/bt-btif ( 1225): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothServiceJni( 1225): adapter_state_change_callback: Status is: 0
,D/BluetoothAdapterState( 1225): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,W/BluetoothAdapterService( 1225): Stopping service com.broadcom.bt.service.hfp.BrcmHeadsetService
,D/dalvikvm(  964): GC_EXPLICIT freed 2467K, 49% free 29700K/57516K, paused 5ms+14ms, total 175ms
,W/BluetoothAdapterService( 1225): Stopping service com.android.bluetooth.a2dp.A2dpService
,D/BrcmHeadsetService( 1225): Received stop request...Stopping profile...
I/LGBluetoothHfpAdapter( 1225): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 1225): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterService( 1225): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42810070
,D/HeadsetStateMachine( 1225): Exit Disconnected: -1
,W/BluetoothAdapterService( 1225): Stopping service com.android.bluetooth.hid.HidService
,D/BluetoothHeadset( 1449): Proxy object disconnected
,D/BluetoothHeadset(  964): Proxy object disconnected
,W/BluetoothAdapterService( 1225): Stopping service com.android.bluetooth.hdp.HealthService
D/BluetoothHeadset( 1449): Proxy object disconnected
D/BluetoothAdapterService(1115750512)( 1225): Message: 1
D/BluetoothAdapterService(1115750512)( 1225): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1225): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 10, doUpdate = true
,D/BluetoothHeadset( 1449): Proxy object disconnected
D/BluetoothAdapterService( 1225): Profile still running: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 1225): Stopping service com.android.bluetooth.pan.PanService
,D/A2dpService( 1225): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1225): Exit Disconnected: -1
E/LGBluetoothUtils( 2576): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
,W/BluetoothAdapterService( 1225): Stopping service com.android.bluetooth.map.BluetoothMapService
D/LGBluetoothA2dpAdapter( 1225): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 1225): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterService( 1225): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42810070
,D/BluetoothA2dp(  964): Proxy object disconnected
,W/BluetoothAdapterService( 1225): Stopping service com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 1225): Stopping service com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 1225): Stopping service com.broadcom.bt.service.ftp.FTPService
,D/HeadsetStateMachine( 1225): Unbinding service...
E/LGBluetoothUtils( 2576): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
,D/LGBluetoothPowerSaveListener( 2576): [BTUI] ACL disconnected => AclLinkCount = 0
,E/LGBluetoothUtils( 2576): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
,D/HeadsetPhoneState( 1225): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1225): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 1225): [BTUI] listenForPhoneState : start = false
D/BluetoothAdapterState( 1225): Stopping profile services that were post enabled
,D/LGBluetoothHfpManager( 1225): [BTUI] listenForMultiSimPhoneState : start = false
W/Brcm_BluetoothHeadsetServiceJni( 1225): Cleaning up Bluetooth Handsfree Interface...
I/bt-btif ( 1225): cleanup
D/bt-btif ( 1225): btif_disable_service: Current Services:0x120108
W/Brcm_BluetoothHeadsetServiceJni( 1225): Cleaning up Bluetooth Handsfree callback object
,I/LGBluetoothHfpAdapter( 1225): [BTUI] LGBluetoothHfpAdapter cleanup
D/HidService( 1225): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1225): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42810070
,D/BluetoothHeadset( 2576): Proxy object disconnected
D/HeadsetProfile( 2576): Bluetooth service disconnected
,D/BluetoothA2dp( 2576): Proxy object disconnected
D/A2dpProfile( 2576): Bluetooth service disconnected
D/BluetoothInputDevice( 2576): Proxy object disconnected
,D/HidProfile( 2576): Bluetooth service disconnected
,D/HealthService( 1225): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1225): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42810070
,D/PanService( 1225): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1225): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42810070
,D/BluetoothTethering(  964): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering(  964): attempted to stop reverse tether with nothing tethered
D/BluetoothPan(  964): BluetoothPAN Proxy object disconnected
,D/BluetoothPan( 2576): BluetoothPAN Proxy object disconnected
D/PanProfile( 2576): Bluetooth service disconnected
,D/BluetoothAdapterService(1115750512)( 1225): Message: 1
D/BluetoothAdapterService(1115750512)( 1225): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1225): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 10, doUpdate = true
,D/BluetoothAdapterService( 1225): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothMapService( 1225): Received stop request...Stopping profile...
,D/BluetoothMapService( 1225): stop()
D/BluetoothMapService( 1225): MAP Service closeService in
D/LGBluetoothMapAdapter( 1225): [BTUI] LGBluetoothMapAdapter cleanup
,V/BluetoothMapService( 1225): MAP Service closeService out
D/BluetoothAdapterService( 1225): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42810070
,I/BTConnectionReceiver( 2647): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/bt-btif ( 1225): cleanup
I/bt-btif ( 1225): ## A2DP STOP MEDIA TASK ##
I/GKI_LINUX( 1225): GKI_destroy_task: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/bt-btif ( 1225): UIPC_Close : ch_id 5
D/bt-btif ( 1225): UIPC_Close : waiting for shutdown to complete
,I/bt-btif ( 1225): UIPC SEND WAKE UP
I/bt-btif ( 1225): UIPC READ THREAD EXITING
I/bt-btif ( 1225): uipc_main_cleanup
I/bt-btif ( 1225): CLOSE CHANNEL 0
I/bt-btif ( 1225): CLOSE SERVER (FD 69)
D/bt-btif ( 1225): A2DP-CTRL-CHANNEL EVENT UIPC_CLOSE_EVT
I/bt-btif ( 1225): UIPC SEND WAKE UP
I/bt-btif ( 1225): CLOSE CHANNEL 1
I/bt-btif ( 1225): CLOSE CHANNEL 2
I/bt-btif ( 1225): CLOSE CHANNEL 3
I/bt-btif ( 1225): UIPC READ THREAD DONE
D/bt-btif ( 1225): UIPC_Close : shutdown complete
D/bt-btif ( 1225): MEDIA TASK EXITING
I/GKI_LINUX( 1225): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/BluetoothClassifier( 2647): Bluetooth Device Name: Galaxy S5-2
,I/GKI_LINUX( 1225): GKI_destroy_task: GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/bt-btif ( 1225): btif_disable_service: Current Services:0x120100
D/LGBluetoothAvrcpAdapter( 1225): [BTUI] cleanup
D/LGBluetoothAvrcpManager( 1225): [BTUI] terminateAvrcpManager
D/LGBluetoothAvrcpManager( 1225): [BTUI] cleanupPlayStatus() : mPlayStatus = 0
D/BluetoothMap( 2576): Proxy object disconnected
,D/MapProfile( 2576): Bluetooth service disconnected
V/BluetoothAVRCP1.3ServiceJni( 1225): cleanupNativeAVRCP
I/bt-btif ( 1225): ## cleanup ##
,D/bt-btif ( 1225): close_uinput
D/BtGatt.DebugUtils( 1225): handleDebugAction() action=null
D/BtGatt.GattService( 1225): Received stop request...Stopping profile...
D/BtGatt.GattService( 1225): stop()
,D/BluetoothAdapterService( 1225): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42810070
D/SapService( 1225): Received stop request...Stopping profile...
D/SapService( 1225): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 1225): [BTUI] LGBluetoothSapAdapter cleanup
,D/LGBluetoothSapManager( 1225): [BTUI] terminateSapManager
,D/LgeBluetoothSimManager( 1449): [BTUI] SAP_DISABLE_EVT
,D/BluetoothAdapterService( 1225): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42810070
D/**BluetoothFTPService( 1225): Received stop request...Stopping profile...
D/**BluetoothFTPService( 1225): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 1225): closeFtpServerNative
I/bt-btif ( 1225): cleanup
,D/bt-btif ( 1225): btif_disable_service: Current Services:0x120000
,D/BluetoothAdapterService( 1225): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42810070
D/BluetoothAdapterService(1115750512)( 1225): Message: 1
D/BluetoothAdapterService(1115750512)( 1225): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1225): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 10, doUpdate = true
,D/BluetoothAdapterService( 1225): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHidServiceJni( 1225): Cleaning up Bluetooth HID Interface...
I/bt-btif ( 1225): cleanup
W/bt-btif ( 1225): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1225): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(1115750512)( 1225): Message: 1
D/BluetoothAdapterService(1115750512)( 1225): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1225): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1225): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHealthServiceJni( 1225): Cleaning up Bluetooth Health Interface...
,I/bt-btif ( 1225): cleanup
D/bt-btif ( 1225): Process name (droid.bluetooth)
D/bt-btif ( 1225): btif_disable_service: Current Services:0x120000
D/bt-btif ( 1225): btif_hl_disable
D/bt-btif ( 1225): btif_hl_signal_select_exit
D/bt-btif ( 1225): select unblocked ret=1
D/bt-btif ( 1225): btif_hl_select_wake_signaled, signal ret=1
D/bt-btif ( 1225): btif_hl_select_wake_signaled
D/bt-btif ( 1225): btif_hl_select_wake_reset
D/bt-btif ( 1225): btif_hl_select_wake_signaled, signal:2
D/bt-btif ( 1225): hl thread cleanup
D/bt-btif ( 1225): Exit hl_select_thread for btif_hl_signal_select_exit
W/BluetoothHealthServiceJni( 1225): Cleaning up Bluetooth Health object
,W/LGBluetoothHealthServiceJni( 1225): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(1115750512)( 1225): Message: 1
D/BluetoothAdapterService(1115750512)( 1225): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1225): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 10, doUpdate = true
,D/BluetoothAdapterService( 1225): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 1225): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1225): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(1115750512)( 1225): Message: 1
D/BluetoothAdapterService(1115750512)( 1225): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1225): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 10, doUpdate = true
,D/BluetoothAdapterService( 1225): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothMapService( 1225): cleanup()
D/BluetoothMapService( 1225): MAP Service closeService in
D/LGBluetoothMapAdapter( 1225): [BTUI] LGBluetoothMapAdapter cleanup
,V/BluetoothMapService( 1225): MAP Service closeService out
,D/BluetoothAdapterService(1115750512)( 1225): Message: 1
D/BluetoothAdapterService(1115750512)( 1225): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1225): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 10, doUpdate = true
,D/BluetoothAdapterService( 1225): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1115750512)( 1225): Message: 1
,D/BluetoothAdapterService(1115750512)( 1225): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1225): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1225): Profile still running: com.broadcom.bt.service.ftp.FTPService
W/BluetoothSAPServiceJni( 1225): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
I/bt-btif ( 1225): cleanup
,D/bt-btif ( 1225): btif_disable_service: Current Services:0x100000
W/BluetoothSAPServiceJni( 1225): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
,D/BluetoothAdapterService(1115750512)( 1225): Message: 1
D/BluetoothAdapterService(1115750512)( 1225): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1225): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1225): All profile services stopped...
D/BluetoothFTPService( 1225): cleanup FTP Service
,V/BluetoothFTPServiceJni( 1225): closeFtpServerNative
I/bt-btif ( 1225): cleanup
V/BluetoothFTPServiceJni( 1225): cleanupNative
D/BluetoothAdapterState( 1225): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 1225): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1225): Broadcasting updateAdapterState() to 1 receivers.
W/BluetoothFTPServiceJni( 1225): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 1225): Cleaning up Bluetooth FTP callback object
D/BluetoothManagerService(  964): Message: 60
,I/BluetoothAdapterState( 1225): Entering OffState
D/BluetoothManagerService(  964): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothFTPService( 1225): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 1225): cleanup done
,D/BluetoothManagerService(  964): Broadcasting onBluetoothStateChange(false) to 12 receivers.
,D/BluetoothPbap( 2576): onBluetoothStateChange: up=false
,D/BluetoothMap( 2576): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 2576): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  964): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2576): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 2576): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  964): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  964): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  964): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  964): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42d87348 mBinding = false
,D/BluetoothManagerService(  964): Sending unbind request.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BluetoothAdapterService(1115750512)( 1225): onUnbind, calling cleanup
D/BluetoothAdapterService(1115750512)( 1225): cleanup()
D/BluetoothAdapterService( 1225): Cleaning up adapter native....
I/bluedroid( 1225): cleanup 1
I/bt-btif ( 1225): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 1225): GKI_destroy_task: GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/bt-btif ( 1225): btif_disassociate_evt: notify DISASSOCIATE_JVM
I/bt-btif ( 1225): HAL bt_hal_cbacks->thread_evt_cb
E/bt-gki  ( 1225): gki_pool_usage:  0: size     64 cur   1 max  13  total  48
E/bt-gki  ( 1225): gki_pool_usage:  1: size    288 cur   0 max   3  total  26
E/bt-gki  ( 1225): gki_pool_usage:  2: size    660 cur   0 max  24  total  45
E/bt-gki  ( 1225): gki_pool_usage:  3: size   4112 cur   0 max   4  total 200
E/bt-gki  ( 1225): gki_pool_usage:  4: size   8108 cur   0 max   0  total  20
E/bt-gki  ( 1225): pool:  4: not allocated
E/bt-gki  ( 1225): gki_pool_usage:  5: size    748 cur   0 max   0  total  64
E/bt-gki  ( 1225): pool:  5: not allocated
E/bt-gki  ( 1225): gki_pool_usage:  6: size    268 cur   0 max   0  total  60
E/bt-gki  ( 1225): pool:  6: not allocated
E/bt-gki  ( 1225): gki_pool_usage:  7: size  10264 cur   0 max   0  total   2
E/bt-gki  ( 1225): pool:  7: not allocated
E/bt-gki  ( 1225): gki_pool_usage:  8: size    128 cur   3 max   3  total  30
E/bt-gki  ( 1225): gki_pool_usage:  9: size   8192 cur   0 max   0  total   5
E/bt-gki  ( 1225): pool:  9: not allocated
D/bt-btif ( 1225): btif task exiting
I/GKI_LINUX( 1225): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1225): GKI_destroy_task: GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 1225): GKI_destroy_task: GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1225): GKI_destroy_task: GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1225): GKI_destroy_task: GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1225): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 1225): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1225): GKI_exit_task: GKI_exit_task 0 done
D/bt-btif ( 1225): btif_shutdown_bluetooth done
I/BluetoothServiceJni( 1225): cleanupNative: return from cleanup
D/BluetoothAdapterService( 1225): Done cleaning up adapter native....
W/LGBluetoothServiceJni( 1225): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 1225): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService(  964): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService(1115750512)( 1225): cleanup() done
D/BluetoothAdapterService(1115750512)( 1225): ****onDestroy()********
D/BtGatt.GattService( 1225): cleanup()
W/bt-btif ( 1225): GATTC Module not enabled/already disabled
W/bt-btif ( 1225): GATTS Module not enabled/already disabled
D/LGBluetoothAPIService( 1157): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1157): Message: 2
D/LGBluetoothAPIService( 1157): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@430fb4f8 mBinding = false
D/LGBluetoothAPIService( 1157): Sending unbind request.
D/BluetoothAdapter( 1142): 1117613288: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIServer( 1225): [BTUI] onUnbind()
D/LGBluetoothAPIServer( 1225): [BTUI] cleanup() done
E/LGBluetoothEventManager( 2576): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 2576): [BTUI] clear device connection state
,D/LGBluetoothAPIServer( 1225): [BTUI] onDestroy()
W/ContextImpl( 2576): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
,V/BluetoothPbapReceiver( 1225): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 1225): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1225): ***********state = 10
,D/DockEventReceiver( 2576): finishStartingService: stopping service
,D/BluetoothPermissionRequest( 2576): onReceive
,E/LGBluetoothUtils( 2576): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
,D/BluetoothDiscoverableTimeoutReceiver( 2576): cancelDiscoverableAlarm(): Enter
,D/LGBluetoothResetSettingReceiver( 2576): return without doing reset settings.
,D/LGBluetoothProfileConnectionReceiver( 2576): [BTUI] STATE_OFF : reset connected device information - BluetoothSettings
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 5648): [BTUI] STATE_OFF : reset connected device information EasySettings
,D/AuthorizationBluetoothService( 1554): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiP2pService(  964): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131089
,D/WifiStateMachine(  964): processMsg: InitialState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,I/GAV2    ( 5811): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681536242328229; DSPS: 14457064; Offset: 1449681095047748151
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681540043, nextTick: 59976, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681540049, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681556245591710; DSPS: 15112531; Offset: 1449681095047746252
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681576251777641; DSPS: 15768094; Offset: 1449681095047737114
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681596253607477; DSPS: 16423514; Offset: 1449681095047735895
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681600047, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681600055, nextTick: 59978, mDrawingTime: 0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681616255595177; DSPS: 17078939; Offset: 1449681095047739953
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681636257403711; DSPS: 17734358; Offset: 1449681095047747950
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681656259147714; DSPS: 18389775; Offset: 1449681095047752451
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681660042, nextTick: 59980, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681660049, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681676261077446; DSPS: 19045198; Offset: 1449681095047759575
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681696262865147; DSPS: 19700617; Offset: 1449681095047746739
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681716264633212; DSPS: 20356035; Offset: 1449681095047744785
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681720046, nextTick: 59980, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681720049, nextTick: 59979, mDrawingTime: 2
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  964): Killing 4223:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43223d48 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681736266333777; DSPS: 21011451; Offset: 1449681095047736365
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681756268194134; DSPS: 21666872; Offset: 1449681095047735150
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681776269792407; DSPS: 22322284; Offset: 1449681095047746509
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681780043, nextTick: 59982, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681780048, nextTick: 59977, mDrawingTime: 3
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681796271453182; DSPS: 22977698; Offset: 1449681095047759335
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681816273090101; DSPS: 23633112; Offset: 1449681095047748305
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681836274652541; DSPS: 24288523; Offset: 1449681095047754348
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681840044, nextTick: 59975, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681840059, nextTick: 59968, mDrawingTime: 3
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681856276359982; DSPS: 24943939; Offset: 1449681095047752805
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681876277926640; DSPS: 25599351; Offset: 1449681095047732549
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681896279529757; DSPS: 26254763; Offset: 1449681095047748752
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681900056, nextTick: 59970, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681900060, nextTick: 59970, mDrawingTime: 2
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681916281638240; DSPS: 26910192; Offset: 1449681095047751522
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681936282587191; DSPS: 27565583; Offset: 1449681095047754428
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681956284158694; DSPS: 28220995; Offset: 1449681095047739017
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681960073, nextTick: 59954, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449681960077, nextTick: 59954, mDrawingTime: 1
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681976285865717; DSPS: 28876411; Offset: 1449681095047737055
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449681996287778313; DSPS: 29531833; Offset: 1449681095047757562
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682016289324816; DSPS: 30187244; Offset: 1449681095047747668
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682020042, nextTick: 59975, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682020054, nextTick: 59974, mDrawingTime: 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682036291880017; DSPS: 30842688; Offset: 1449681095047739392
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682056293522718; DSPS: 31498101; Offset: 1449681095047764662
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682076295405939; DSPS: 32153523; Offset: 1449681095047755793
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682080048, nextTick: 59969, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682080058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682096297296921; DSPS: 32808945; Offset: 1449681095047754685
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682116298864985; DSPS: 33464357; Offset: 1449681095047735835
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682136301336021; DSPS: 34119798; Offset: 1449681095047734947
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682140076, nextTick: 59954, mDrawingTime: 3
D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682140077, nextTick: 59956, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682156303285805; DSPS: 34775221; Offset: 1449681095047762124
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682176305152516; DSPS: 35430643; Offset: 1449681095047736745
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682196307083029; DSPS: 36086066; Offset: 1449681095047744651
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682200053, nextTick: 59977, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682200054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682216308742187; DSPS: 36741480; Offset: 1449681095047755859
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682236310391086; DSPS: 37396894; Offset: 1449681095047756809
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682256311961965; DSPS: 38052306; Offset: 1449681095047740774
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682260045, nextTick: 59983, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682260049, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682276313658727; DSPS: 38707721; Offset: 1449681095047759069
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682296315036168; DSPS: 39363127; Offset: 1449681095047732702
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682316316691733; DSPS: 40018541; Offset: 1449681095047740317
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682320052, nextTick: 59979, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682320055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682336318429798; DSPS: 40673958; Offset: 1449681095047738881
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682356320356249; DSPS: 41329381; Offset: 1449681095047742724
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682376322072075; DSPS: 41984797; Offset: 1449681095047749566
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682380043, nextTick: 59988, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682380045, nextTick: 59982, mDrawingTime: 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682396324017849; DSPS: 42640221; Offset: 1449681095047742215
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682416326001487; DSPS: 43295646; Offset: 1449681095047742210
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682436327379343; DSPS: 43951051; Offset: 1449681095047746775
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682440043, nextTick: 59971, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682440055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682456329018190; DSPS: 44606465; Offset: 1449681095047737673
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682476331039693; DSPS: 45261891; Offset: 1449681095047745016
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682496332972186; DSPS: 45917314; Offset: 1449681095047754901
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682500042, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682500049, nextTick: 59979, mDrawingTime: 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682516334633480; DSPS: 46572729; Offset: 1449681095047737729
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682536336273368; DSPS: 47228142; Offset: 1449681095047760185
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682556338132891; DSPS: 47883563; Offset: 1449681095047758136
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682560041, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682560048, nextTick: 59978, mDrawingTime: 3
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682576339718144; DSPS: 48538975; Offset: 1449681095047756475
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682596341895012; DSPS: 49194407; Offset: 1449681095047736077
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682616343868129; DSPS: 49849831; Offset: 1449681095047756069
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682620045, nextTick: 59980, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682620052, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682636345500309; DSPS: 50505245; Offset: 1449681095047740300
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682656347080924; DSPS: 51160657; Offset: 1449681095047734001
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682676349002377; DSPS: 51816080; Offset: 1449681095047732846
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682680042, nextTick: 59985, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682680046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682696350541068; DSPS: 52471490; Offset: 1449681095047745658
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682716352813143; DSPS: 53126924; Offset: 1449681095047759433
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682736354596000; DSPS: 53782343; Offset: 1449681095047741752
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682740036, nextTick: 59963, mDrawingTime: 12
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682740059, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682756356334325; DSPS: 54437760; Offset: 1449681095047740575
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682776358055933; DSPS: 55093176; Offset: 1449681095047753199
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682796359632591; DSPS: 55748588; Offset: 1449681095047742943
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682800045, nextTick: 59975, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682800063, nextTick: 59967, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682816361160292; DSPS: 56403998; Offset: 1449681095047744765
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682836363023306; DSPS: 57059419; Offset: 1449681095047746207
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682856364694235; DSPS: 57714834; Offset: 1449681095047738669
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682860037, nextTick: 59962, mDrawingTime: 14
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682860058, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682876366668082; DSPS: 58370258; Offset: 1449681095047759391
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682896368270939; DSPS: 59025671; Offset: 1449681095047744816
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682916370119889; DSPS: 59681092; Offset: 1449681095047732194
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682920024, nextTick: 59978, mDrawingTime: 15
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682920089, nextTick: 59944, mDrawingTime: 0,
,I/ProcessStatsService(  964): Prepared write state in 65ms
D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  964): Pruning old procstats: /data/system/procstats/state-2015-12-09-03-34-29.bin
,D/dalvikvm( 2631): GC_CONCURRENT freed 2429K, 33% free 16757K/24832K, paused 3ms+3ms, total 61ms
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682936371814726; DSPS: 60336507; Offset: 1449681095047748564
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682956373385447; DSPS: 60991918; Offset: 1449681095047762889
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682976374943408; DSPS: 61647330; Offset: 1449681095047733936
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682980066, nextTick: 59958, mDrawingTime: 8
D/Clock   ( 1142): Clock updated, drawingStartTime : 1449682980067, nextTick: 59965, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449682996376856161; DSPS: 62302752; Offset: 1449681095047754599
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449683016378317559; DSPS: 62958160; Offset: 1449681095047751153
,TIME-OUT KILL (timeout was 1800000ms)
```
