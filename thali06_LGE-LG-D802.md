#### Test 55902202f27eba5_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 1532): GC_EXPLICIT freed 1228K, 29% free 17836K/24832K, paused 1ms+3ms, total 25ms
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
W/GAV2    ( 4609): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  957): Killing 4082:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 1 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{43020de0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1152): usb Uevent not necessary.
I/ConfigFetchService( 1939): fetch service done; releasing wakelock
I/ConfigFetchService( 1939): stopping self
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1939): GC_CONCURRENT freed 1490K, 22% free 19466K/24832K, paused 4ms+3ms, total 57ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4652): 
D/AndroidRuntime( 4652): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4652): CheckJNI is OFF
D/dalvikvm( 4652): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4652): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4652): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4652): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4652): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4652): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/BatteryObserver( 1152): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/memtrack( 4652): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4652): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Icing   ( 1939): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1939): Loaded CLD2 Version V2.0 - 20141016
D/AndroidRuntime( 4652): Calling main entry com.android.commands.am.Am
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  957): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4652
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (117 us)
V/ActivityManager(  957): Moving to PAUSING: ActivityRecord{43020de0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  957): resumeTopActivityLocked: Pausing null
V/ActivityManager(  957): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  957): startService SlideAside
W/ContextImpl(  957): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  957): setFocusedStack: mFocusedStack=ActivityStack{42b98290 stackId=1, 2 tasks}
D/ActivityManager(  957): allPausedActivitiesComplete: r=ActivityRecord{43020de0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/AndroidRuntime( 4652): Shutting down VM
D/dalvikvm( 4652): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/UsbSettingsControl( 2596): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2596): [AUTORUN] onPause() : mActiveCurrentFunction = boot
V/ActivityManager(  957): Moving to PAUSED: ActivityRecord{43020de0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Restarting ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 4063): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  957): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4679 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  957): Moving to RESUMED: ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 4063): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4063): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4679): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4679): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4679): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Icing   ( 1939): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
V/WebViewChromium( 4679): Binding Chromium to the background looper Looper (main, tid 1) {42807a08}
I/chromium( 4679): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4679): Initializing chromium process, renderers=0
W/chromium( 4679): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4679): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4679): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4679): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4679): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4679): Remote Branch: 
I/Adreno-EGL( 4679): Local Patches: 
I/Adreno-EGL( 4679): Reconstruct Branch: 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/dalvikvm( 4679): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4679): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4679): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4679): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4679): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4679): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4679): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4679): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4679): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4679): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4679): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4679): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4679): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4679): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4679): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4679): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4679): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4679): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4679): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4679): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4679): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4679): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4679): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4679): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4679): Enabling debug mode 0
W/AwContents( 4679): nativeOnDraw failed; clearing to background color.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/AwContents( 4679): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  957): IME STATUS OFF
I/ActivityManager(  957): Displayed com.test.thalitest/.MainActivity: +526ms
I/ActivityManager( 4679): Timeline: Activity_idle id: android.os.BinderProxy@428092c8 time:108583
D/JsMessageQueue( 4679): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4679): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4280d828
D/dalvikvm( 4679): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4280d828
D/jxcore_app_log( 4679): JniHelper::setJavaVM(0x416d3838), pthread_self() = 1630819736
D/JX-Cordova( 4679): jxcore cordova android initializing
D/ActivityManager(  957): no-history finish of ActivityRecord{43020de0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  957): Finishing activity token=Token{42933588 ActivityRecord{43020de0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  957): Moving to FINISHING: ActivityRecord{43020de0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  957): Timeline: Activity_windows_visible id: ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3} time:108824
D/WifiStateMachine(  957): handleMessage: E msg.what=131155
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
D/UsbSettings( 2596): [AUTORUN] onStop()
V/ActivityManager(  957): Moving to STOPPING: ActivityRecord{43020de0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/wpa_supplicant( 2021): nl80211: survey data missing!
D/WifiStateMachine(  957): handleMessage: X
V/ActivityManager(  957): Moving to STOPPED: ActivityRecord{43020de0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1152): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4679): GC_CONCURRENT freed 2779K, 12% free 21861K/24832K, paused 1ms+3ms, total 48ms
,D/dalvikvm( 4679): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4679): GC_FOR_ALLOC freed 113K, 12% free 21857K/24832K, paused 23ms, total 23ms
,D/dalvikvm( 4679): GC_FOR_ALLOC freed 126K, 12% free 21878K/24832K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4679): Grow heap (frag case) to 23.630MB for 95956-byte allocation
,D/dalvikvm( 4679): GC_FOR_ALLOC freed 179K, 13% free 21912K/24928K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4679): Grow heap (frag case) to 23.709MB for 143930-byte allocation
,D/dalvikvm( 4679): GC_FOR_ALLOC freed 253K, 13% free 21960K/25072K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4679): Grow heap (frag case) to 23.825MB for 215890-byte allocation
,D/dalvikvm( 4679): GC_FOR_ALLOC freed 367K, 13% free 22034K/25284K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4679): Grow heap (frag case) to 24.000MB for 323830-byte allocation
,D/dalvikvm( 4679): GC_FOR_ALLOC freed 566K, 14% free 22154K/25604K, paused 22ms, total 22ms
I/dalvikvm-heap( 4679): Grow heap (frag case) to 24.272MB for 485740-byte allocation
,D/dalvikvm( 4679): GC_FOR_ALLOC freed 863K, 15% free 22330K/26080K, paused 23ms, total 23ms
,D/dalvikvm( 4679): GC_FOR_ALLOC freed 1281K, 14% free 22585K/26080K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4679): Grow heap (frag case) to 25.272MB for 1092904-byte allocation
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/dalvikvm( 4679): GC_CONCURRENT freed 1784K, 16% free 22970K/27148K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4679): GC_FOR_ALLOC freed 271K, 16% free 22900K/27148K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4679): Grow heap (frag case) to 26.100MB for 1639352-byte allocation
,D/dalvikvm( 4679): GC_CONCURRENT freed 1760K, 19% free 23502K/28752K, paused 1ms+5ms, total 36ms
,D/dalvikvm( 4679): GC_FOR_ALLOC freed 1241K, 19% free 23537K/28752K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4679): Grow heap (frag case) to 27.503MB for 2459024-byte allocation
,D/dalvikvm( 4679): GC_CONCURRENT freed 147K, 17% free 25885K/31156K, paused 2ms+3ms, total 30ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4679): GC_CONCURRENT freed 4457K, 22% free 24550K/31156K, paused 2ms+4ms, total 50ms
,D/dalvikvm( 4679): WAIT_FOR_CONCURRENT_GC blocked 35ms
,I/dalvikvm-heap( 4679): Grow heap (frag case) to 29.666MB for 3688532-byte allocation
,D/dalvikvm( 4679): GC_CONCURRENT freed 2957K, 27% free 25627K/34760K, paused 1ms+3ms, total 52ms
,D/dalvikvm( 4679): GC_FOR_ALLOC freed 679K, 27% free 25463K/34760K, paused 23ms, total 23ms
,W/jxcore-log( 4679): Initializing JXcore engine
,W/jxcore-log( 4679): JXcore engine is ready
,D/dalvikvm( 4679): GC_CONCURRENT freed 351K, 20% free 28103K/34760K, paused 2ms+1ms, total 38ms
,D/dalvikvm( 4679): WAIT_FOR_CONCURRENT_GC blocked 35ms
,W/jxcore-log( 4679): Starting JXcore engine
,W/jxcore-log( 4679): Platform android
W/jxcore-log( 4679): 
,W/jxcore-log( 4679): Process ARCH arm
W/jxcore-log( 4679): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4679): JXcore Cordova bridge is ready!
I/jxcore-log( 4679): 
,W/jxcore-log( 4679): JXcore engine is started
,I/chromium( 4679): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4679): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4679): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/jxcore-log( 4679): Toggling radios to true
I/jxcore-log( 4679): 
,D/BluetoothManagerService(  957): Message: 20
,D/BluetoothManagerService(  957): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@432e40a8:true
D/BluetoothAdapter( 4679): enable(): BT is already enabled..!
D/WifiStateMachine(  957): handleMessage: E msg.what=131145
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiNative-wlan0(  957): doBoolean: DISCONNECT
D/WifiService(  957): New client listening to asynchronous messages
D/WifiService(  957): setWifiEnabled: true pid=4679, uid=10304
E/WifiService(  957): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  957): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  957): disconnect pid=4679, uid=10304
,D/WifiService(  957): reconnect pid=4679, uid=10304
I/jxcore-log( 4679): Radios toggled
I/jxcore-log( 4679): 
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2021): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2021): wlan0: Cancelling scan request
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2021): TDLS: Tear down peers
D/wpa_supplicant( 2021): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4679): My device name is: LGE-LG-D802
I/jxcore-log( 4679): 
,D/wpa_supplicant( 2021): wlan0: Event DEAUTH (12) received
,D/wpa_supplicant( 2021): wlan0: Deauthentication notification
D/wpa_supplicant( 2021): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2021): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Auto connect disabled: do not try to re-connect
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2021): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2021): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2021): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7336d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2021): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2021): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2021): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiNative-wlan0(  957):    returned true
D/WifiStateMachine(  957): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  957): invokeExitMethods: ConnectedState
W/Settings(  957): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  957): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  957): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131146
D/WifiStateMachine(  957): processMsg: DisconnectingState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiNative-wlan0(  957): doBoolean: RECONNECT
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2021): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2021): Fast associate: Old scan results
D/wpa_supplicant( 2021): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2021): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2021): wlan0: nl80211: scan request
D/wpa_supplicant( 2021): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2021): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2021): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  957):    returned true
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147460
D/WifiStateMachine(  957): processMsg: DisconnectingState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): Network connection lost
D/WifiStateMachine(  957): Stopping DHCP and clearing IP
D/WifiStateMachine(  957): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  957): doBoolean: SET ps 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  957):    returned true
D/WifiNative-wlan0(  957): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  957): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  957): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  957):    returned true
D/DhcpStateMachine(  957): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  957): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  957): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  957): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
,D/QCNEA   (  528): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  528): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  528): |CAC| updateNetCfgInfo
V/QCNEA   (  528): |CAC| *********************************************
V/QCNEA   (  528): |CAC|                   Netconfig               
V/QCNEA   (  528): |CAC| *********************************************
V/QCNEA   (  528): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  528): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  528): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  528): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  528): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  528): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  528): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  528): |CAC| *********************************************
D/QCNEA   (  528): |CAC| Received bssid= 
D/QCNEA   (  528): |CAC| net type = 3
V/QCNEA   (  528): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  528): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  528): |CAC| 	ssid           =NG700
V/QCNEA   (  528): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  528): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  528): |CAC| *********************************************
D/QCNEA   (  528): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  528): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  528): |CAC| dispatchNetCfg: updating:0xb74558dc
D/QCNEA   (  528): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  528): Reading a NULL string not supported here.
,E/Parcel  (  528): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  957): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,V/WfdStateTracker( 1152): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1138): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  957): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  957): hidePasspointNotification off =false
D/QcConnectivityService(  957): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  957): Attempting to switch to mobile
D/QcConnectivityService(  957): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  957): handleConnectivityChange: preConnState=1 connState=2
I/RemoteControlStatusBar( 1138): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  957): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  957): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  957): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/NetworkManagementService(  957): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131213
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
D/WifiStateMachine(  957): processMsg: SupplicantStartedState
D/WifiStateMachine(  957): processMsg: DefaultState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131213
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
D/WifiStateMachine(  957): processMsg: SupplicantStartedState
D/WifiStateMachine(  957): processMsg: DefaultState
D/WifiStateMachine(  957): handleMessage: X
D/NetworkManagementService(  957): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  957): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
I/ActivityManager(  957): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4749 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/HyLog   ( 4749): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,D/HyLog   ( 4749): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4749): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,W/NetworkManagementService(  957): route cmd failed: 
W/NetworkManagementService(  957): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  957): '
W/NetworkManagementService(  957): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  957): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  957): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  957): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  957): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  957): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  957): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  957): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  957): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  957): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  957): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  957): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  957): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  957): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  957): android_net_utils_resetConnections in env=0x6282f7b0 clazz=0x6af00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  957): resetConnections(wlan0, 3)
,V/NativeCrypto( 1532): Read error: ssl=0x612ed7a0: I/O error during system call, Connection timed out
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/NativeCrypto( 1532): SSL shutdown failed: ssl=0x612ed7a0: I/O error during system call, Broken pipe
I/PCSuite ( 4749): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 4749): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4749): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  957): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4783 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  957): Killing 4180:com.google.android.talk/u0a77 (adj 15): empty #17
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  957): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  957): requiresClat: netType=1, hasIPv4Address=false
D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/LocSvc_java(  957): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  957): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  957): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/HyLog   ( 4783): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4783): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4783): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/QRemote ( 4783): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4783): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4783): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4783): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4783): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4783): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4783): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4783): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4783): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  957): Killing 2129:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  957): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
D/WifiStateMachine(  957): processMsg: SupplicantStartedState
,D/WifiStateMachine(  957): processMsg: DefaultState
,D/WifiStateMachine(  957): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ProcessCpuTracker(  957): Skipping unknown process pid 4773
,W/ProcessCpuTracker(  957): Skipping unknown process pid 4774
,W/ProcessCpuTracker(  957): Skipping unknown process pid 4794
,W/ProcessCpuTracker(  957): Skipping unknown process pid 4805
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4609): Thread[GAThread,5,main]: No campaign data found.
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.452332 Y: -0.393066 Z: 9.799362 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452332 .y:-0.393066 .z:9.799362
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.452484 Y: -0.378265 Z: 9.820450 
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.454712 Y: -0.373825 Z: 9.810471 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.452484 .y:-0.378265 .z:9.820450
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,I/ConfigService( 1532): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1152): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
D/WifiController(  957): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  957): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Tethering(  957): MasterInitialState.processMessage what=3
D/QcConnectivityService(  957): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
,D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@428256c8
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 3036): start selecting data
,D/SIMObserver( 3036): simInfo1
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4037): begin check event
,I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity
,I/ActivityManager(  957): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4810 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4810): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4810): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4810): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2021): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2021): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2021): nl80211: Received scan results (11 BSSes)
D/wpa_supplicant( 2021): nl80211: Survey data missing
D/wpa_supplicant( 2021): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 7 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 8 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 9 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 10 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): BSS: last_scan_res_used=11/32 last_scan_full=0
D/wpa_supplicant( 2021): wlan0: New scan results available
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2021): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2021): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2021): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2021): WPS: AP 44:e9:dd:10:c0:ac type 0 added
D/wpa_supplicant( 2021): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): WPS: AP[4] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): WPS: AP[5] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2021): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2021): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2021): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_suppli,cant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2021): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb73385a8  current_ssid=0x0
D/wpa_supplicant( 2021): scard is not null..
D/wpa_supplicant( 2021): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2021): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2021): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2021): wlan0: Cancelling scan request
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2021): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2021): RSN: PMKSA cache search - network_ctx=0xb73385a8 try_opportunistic=0
D/wpa_supplicant( 2021): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2021): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2021): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2021): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2021): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2021): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2021): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2021): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2021): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2021): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2021): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2021): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2021): nl80211: Unsubscribe mgmt frames handle 0xb7337590 (mode change)
D/wpa_supplicant( 2021): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7337590
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7337590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7337590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7337590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7337590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7337590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7337590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7337590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7337590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7337590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7337590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2021): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2021):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021):   * freq=2412
D/wpa_supplicant( 2021):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2021):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021):   * Auth Type 0
D/wpa_supplicant( 2021):   * WPA Versions 0x2
D/wpa_supplicant( 2021): nl80211: Connect request send successfully
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 44:e9:dd:10:c0:ac]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 fc:94:e3:11:35:3a]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 fe:94:e3:11:35:3c]
D/WifiMonitor(  957): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  957): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  957): handleMessage: E msg.what=147461
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
D/WifiStateMachine(  957): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  957): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2021): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
D/EAS     ( 4591): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 4810): DownloadService onCreate
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/eas_req ( 4591): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
I/DownloadManager( 4810): in removeSpuriousFiles
V/DownloadManager( 4810): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4383): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4383): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@4284cb78 on behalf of 4810
I/DownloadManager( 4810): in trimDatabase
V/DownloadManager( 4810): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2021): nl80211: Connect event
D/wpa_supplicant( 2021): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2021): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2021): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2021): wlan0: Association info event
D/wpa_supplicant( 2021): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2021): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2021): wlan0: freq=2412 MHz
D/wpa_supplicant( 2021): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2021): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2021): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2021): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): scard is not null..
D/wpa_supplicant( 2021): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2021): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2021): TDLS: Remove peers on association
D/wpa_supplicant( 2021): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2021): EAPOL: enable timer tick
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): wlan0: Cancelling scan request
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  957): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
I/LgeMiscReceiver( 4383): networkInfo.isConnected() = false
W/WifiMonitor(  957): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  957): processMsg: ConnectModeState
,D/WifiStateMachine(  957): handleMessage: X
,D/dalvikvm(  957): GC_CONCURRENT freed 1120K, 49% free 29764K/57892K, paused 2ms+6ms, total 101ms
,V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@4284f008 on behalf of 4810
,V/DownloadManager( 4810): DownloadService onStartCommand
,V/DownloadManager( 4810): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/linker  ( 4591): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 a0 f1 74 77 83 02 f8 e8 39 bd c6 29 00 f8 65 ...
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=0
,D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
,D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): a0 f1 74 77 83 02 f8 e8 39 bd c6 29 00 f8 65 88 0a 4a 19 55 bb 48 c0 48 24 c9 23 62 f6 17 61 97
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 a0 f1 74 77 83 02 f8 e8 39 bd c6 29 00 f8 65 ...
D/wpa_supplicant( 2021): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2021): Get randomness: len=32 entropy=11
D/HtmlEditor( 4591): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4591): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4591): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2021): WPA: Renewed SNonce - hexdump(len=32): 67 6d 86 62 b1 0c 96 07 ab 7e 81 48 7f 9d f3 ba 9d 8d 34 a4 60 dc a6 d1 ff 84 af 87 25 ff 4c 09
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/wpa_supplicant( 2021): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): WPA: Nonce1 - hexdump(len=32): 67 6d 86 62 b1 0c 96 07 ab 7e 81 48 7f 9d f3 ba 9d 8d 34 a4 60 dc a6 d1 ff 84 af 87 25 ff 4c 09
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/wpa_supplicant( 2021): WPA: Nonce2 - hexdump(len=32): a0 f1 74 77 83 02 f8 e8 39 bd c6 29 00 f8 65 88 0a 4a 19 55 bb 48 c0 48 24 c9 23 62 f6 17 61 97
D/wpa_supplicant( 2021): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2021): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/WifiStateMachine(  957): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@42852380 on behalf of 4810
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 2/4
,I/ActivityManager(  957): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4835 uid=10052 gids={50052, 3003}
V/DownloadManager( 4810): DownloadService onDestroy
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): 24 77 da ee f1 bd 9e a7 cc 60 1f 06 af 88 91 be
D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 67 6d 86 62 b1 0c 96 07 ab 7e 81 48 7f 9d f3 ...
I/dalvikvm( 4591): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4591): register_HtmlEditor, Success
D/HtmlEditor( 4591): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4591): register_HtmlEditorTimer, Success
D/HtmlEditor( 4591): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4591): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4591): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4591): register_HtmlEditorFont, Success
D/HtmlEditor( 4591): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4835): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HtmlEditor( 4591): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4591): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 a0 f1 74 77 83 02 f8 e8 39 bd c6 29 00 f8 65 ...
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): a0 f1 74 77 83 02 f8 e8 39 bd c6 29 00 f8 65 88 0a 4a 19 55 bb 48 c0 48 24 c9 23 62 f6 17 61 97
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): 10 2e 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): e0 88 a5 a9 59 ec 08 21 01 15 80 a3 89 8f 1c 01
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 a0 f1 74 77 83 02 f8 e8 39 bd c6 29 00 f8 65 ...
D/wpa_supplicant( 2021): RSN: encrypted key data - hexdump(len=56): 50 a2 f3 92 ee 0f b1 a8 a7 61 a6 e1 b0 29 95 c7 f8 91 a8 42 83 5a f4 82 ab 9a 9b f6 05 de 34 0c ...
D/wpa_supplicant( 2021): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 04 29 ...
D/wpa_supplicant( 2021): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/HtmlEditor( 4591): register_HtmlEditorDrawImage, Success
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): 28 d1 34 4d a6 8b 64 c3 0e 95 a9 b7 7f 87 a7 86
D/HtmlEditor( 45,91): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/HtmlEditor( 4591): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4591): JNI_OnLoad Success
D/wpa_supplicant( 2021): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7337c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2021): WPA: Group Key - hexdump(len=16): [REMOVED]
,I/HubEmail( 4591): JNI_OnLoad()
D/wpa_supplicant( 2021): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
I/HubEmail( 4591): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/wpa_supplicant( 2021): WPA: RSC - hexdump(len=6): 10 2e 00 00 00 00
I/HubEmail( 4591): registerNatives()
I/HubEmail( 4591): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4591): registerNativeMethods()
I/HubEmail( 4591): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f4303a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2021):    broadcast key
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
I/wpa_supplicant( 2021): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2021): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=6
W/Settings( 4591): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2021): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2021): EAPOL authentication completed successfully
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  957): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  957): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  957): handleMessage: E msg.what=147459
D/WifiStateMachine(  957): processMsg:, DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): Network connection established
D/WifiNative-wlan0(  957): doString: STATUS
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2021): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  957):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  957): ssid=NG700
D/WifiNative-wlan0(  957): id=0
D/WifiNative-wlan0(  957): mode=station
D/WifiNative-wlan0(  957): pairwise_cipher=CCMP
D/WifiNative-wlan0(  957): group_cipher=CCMP
D/WifiNative-wlan0(  957): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  957): wpa_state=COMPLETED
D/WifiNative-wlan0(  957): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  957): address=34:fc:ef:de:0a:e2
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/WifiServiceExtension(  957): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  957): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  957): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  957): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  957): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  957): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  957): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  957): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
D/WifiStateMachine(  957): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  957): invokeEnterMethods: ObtainingIpState
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
D/DhcpStateMachine(  957): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  957): WaitBeforeStartState
,D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/KeyguardUpdateMonitor( 1138): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/WifiStateMachine(  957): ObtainingIpState{ when=-8ms what=147462 obj=android.net.wifi.StateChangeResult@431c5ee0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/WifiStateMachine(  957): ObtainingIpState{ when=-7ms what=147462 obj=android.net.wifi.StateChangeResult@431951e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147459,
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/WifiStateMachine(  957): ObtainingIpState{ when=-8ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
I/RemoteControlStatusBar( 1138): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131155
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/WifiStateMachine(  957): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL',
D/wpa_supplicant( 2021): nl80211: survey data missing!
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=196612
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/WifiStateMachine(  957): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiNative-wlan0(  957): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  957): Killing 3936:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
V/LGRssiData( 4835): [loadRssi] File not exist 
V/LGRssiData( 4835): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4835): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4835): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4835): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4835): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4835): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4835): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4835): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4835): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 4835): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4835): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4835): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4835): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  957): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4856 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  957): Killing 4353:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4856): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4856): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4856): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  957): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4869 uid=10066 gids={50066, 4002, 3003, 1028}
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  957):    returned true
D/WifiStateMachine(  957): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  957): doBoolean: SET ps 0
,I/ActivityManager(  957): Killing 4515:com.android.defcontainer/u0a4 (adj 15): empty #17
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  957):    returned true
D/WifiNative-wlan0(  957): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  957):    returned null
E/WifiStateMachine(  957): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  957): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  957):    returned null
E/WifiStateMachine(  957): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  957): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  957): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  957): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  957): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
,D/WifiStateMachine(  957): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  957): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  957): handleMessage: X
D/WifiP2pService(  957): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4325da30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  957): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4325da30 target=com.android.internal.util.StateMachine$SmHandler }
D/HyLog   ( 4869): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  957): handleMessage: E msg.what=131212
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/HyLog   ( 4869): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4869): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  957): ObtainingIpState{ when=-4ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
D/WifiStateMachine(  957): processMsg: SupplicantStartedState
D/WifiStateMachine(  957): processMsg: DefaultState
D/WifiStateMachine(  957): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=196613
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/WifiStateMachine(  957): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  957): doBoolean: SET ps 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  957):    returned true
D/WifiNative-wlan0(  957): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  957):    returned true
,D/WifiStateMachine(  957): DHCP successful
D/WifiStateMachine(  957): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  957): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  957): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  957): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  957): VerifyingLinkState enter
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
D/WifiP2pService(  957): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
,D/WifiP2pService(  957): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  957): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  957): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1138): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  528): Reading a NULL string not supported here.
,E/Parcel  (  528): Reading a NULL string not supported here.
,E/Parcel  (  528): Reading a NULL string not supported here.
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  957): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=135190
D/WifiStateMachine(  957): processMsg: VerifyingLinkState
D/WifiStateMachine(  957): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  957): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  957): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  957): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  957): CaptivePortalCheckState enter
D/WifiStateMachine(  957): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/WifiStateMachine(  957): handleMessage: X
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/WifiStateTracker(  957): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  957): 
W/WifiStateTracker(  957):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  957):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  957): requiresClat: netType=1, hasIPv4Address=true
I/RemoteControlStatusBar( 1138): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  957): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  957): handleMessage: E msg.what=131092
D/WifiStateMachine(  957): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  957): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  957): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/KeyguardUpdateMonitor( 1138): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  957): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1138): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  957): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  957): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
,D/LocSvc_java(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  957): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  957): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  957): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  957): handleMessage: X
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,V/WfdStateTracker( 1152): handleWifiStateChangedEvent: 1
,D/KeyguardUpdateMonitor( 1138): received broadcast android.net.wifi.STATE_CHANGE
,D/LGDMClient( 2916): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/ActivityManager(  957): Killing 4549:com.google.android.partnersetup/u0a9 (adj 15): empty #17
I/RemoteControlStatusBar( 1138): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/GpsLocationProvider(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/LocSvc_java(  957): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  957): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  957): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  957): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  528): Reading a NULL string not supported here.
,E/Parcel  (  528): Reading a NULL string not supported here.
,E/Parcel  (  528): Reading a NULL string not supported here.
E/ActivityThread(  957): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  957): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  957): handleConnectivityChange: preConnState=2 connState=1
D/LGDMClient( 2916): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2916): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,E/LGDMClient( 2916): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2916): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
I/ActivityManager(  957): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4884 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
V/        (  264): RouteController
D/LGDMClient( 2916): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2916): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
,D/HyLog   ( 4884): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4884): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4884): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/LGDMSGCM( 4884): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/        (  264): RouteController
W/ContextImpl( 4884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/Nat464Xlat(  957): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager(  957): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4912 uid=10101 gids={50101, 1028, 1015, 3003}
D/LocSvc_java(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  528): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  528): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  528): |CAC| updateNetCfgInfo
V/QCNEA   (  528): |CAC| *********************************************
V/QCNEA   (  528): |CAC|                   Netconfig               
V/QCNEA   (  528): |CAC| *********************************************
V/QCNEA   (  528): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  528): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  528): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  528): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  528): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  528): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  528): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  528): |CAC| *********************************************
D/QCNEA   (  528): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  528): |CAC| net type = 1
V/QCNEA   (  528): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  528): |CAC| Received ssid= NG700
V/QCNEA   (  528): |CAC| 	ssid           =NG700
V/QCNEA   (  528): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  528): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  528): |CAC| *********************************************
D/QCNEA   (  528): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  528): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  528): |CAC| dispatchNetCfg: updating:0xb74558dc
D/QCNEA   (  528): |CAC| readCallback: read len:0, ret:-1, errno:11
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/LocSvc_java(  957): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  957): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 4912): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4912): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4912): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  957): Killing 4577:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
,I/CheckinService( 1939): Checking schedule, now: 1452699394245 next: 1452699340616
,I/CheckinService( 1939): active receiver: enabled
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 4912): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/CheckinService( 1939): Preparing to send checkin request
,I/EventLogService( 1939): Accumulating logs since 1452699308181
I/Wireless_Storage( 4912): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4912): intf.getDisplayName() = lo
I/Wireless_Storage( 4912): intf.getDisplayName() = sit0
I/Wireless_Storage( 4912): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4912): intf.getDisplayName() = teql0
I/Wireless_Storage( 4912): intf.getDisplayName() = wlan0
,D/NFS     ( 4912): interface name:wlan0 name:wlan0
D/NFS     ( 4912): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4912): interface name:wlan0 name:wlan0
,D/NFS     ( 4912): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4912): CONNECT : WIFI_CONNECT
,I/ActivityManager(  957): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4926 uid=10104 gids={50104, 3003, 1028, 1015}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1152): usb Uevent not necessary.
,I/ActivityManager(  957): Killing 4227:com.android.contacts/u0a21 (adj 15): empty #17
,D/DhcpStateMachine(  957): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  957): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinRequestBuilder( 1939): Checkin reason type: 8 attempt count: 1
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
,D/HyLog   ( 4926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4926): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/ActivityThread( 1939): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  957): battery changed pluggedType: 2
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 17ms
D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 16ms
,W/GAV2    ( 4926): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  957): updateLightListLocked :r=NotificationRecord(0x43180348: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1939): awaiting user notification for token
D/NotificationService(  957): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,V/WebViewChromium( 4926): Binding Chromium to the main looper Looper (main, tid 1) {428114f8}
,I/chromium( 4926): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4926): Initializing chromium process, renderers=0
,I/ActivityManager(  957): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4958 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
W/chromium( 4926): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4926): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4926): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4926): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4926): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4926): Remote Branch: 
I/Adreno-EGL( 4926): Local Patches: 
I/Adreno-EGL( 4926): Reconstruct Branch: 
,D/HyLog   ( 4958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4958): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NSApplication( 4926): Starting up...
W/dalvikvm( 4958): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4958): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4958): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4958): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4958): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4958): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4958): install
,I/MultiDex( 4958): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4958): loading existing secondary dex files
,I/MultiDex( 4958): load found 3 secondary dex files
,I/ActivityManager(  957): Killing 4242:com.android.gallery3d/u0a27 (adj 15): empty #17
I/MultiDex( 4958): install done
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
,D/dalvikvm( 4958): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 4958): VFY: unable to resolve instance field 61
,D/dalvikvm( 4958): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 4958): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4958): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4958): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4958): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4958): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4958): VFY: replacing opcode 0x62 at 0x000a
D/QRemote ( 4783): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4783): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/dalvikvm( 4958): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4958): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 4958): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4280d368
D/dalvikvm( 4958): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4280d368
D/dalvikvm( 4958): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4280d368, skipping init
D/dalvikvm( 4958): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4280d368
D/dalvikvm( 4958): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4280d368
V/JNIHelp ( 4958): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/QRemote ( 4783): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4783): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/QRemote ( 4783): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4783): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/PCSuite ( 4749): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 4749): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 4783): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 4783): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4783): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 4783): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/dalvikvm( 4958): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4280d368
,D/dalvikvm( 4958): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4280d368
D/dalvikvm( 4958): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4280d368
,D/dalvikvm( 4958): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4280d368
,I/ProviderInstaller( 4958): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1532): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1532): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1532): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1939): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1867): callingUid 10006, callindPid: 1867
,E/MDM     ( 1425): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1939): Restart initialization of location
,I/dalvikvm( 4958): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4958): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4958): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4958): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
,W/dalvikvm( 4958): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4958): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2049000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2049000
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=1349919900
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4958): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a007b0
D/dalvikvm( 4958): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a007b0
,D/dalvikvm( 4958): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a007b0, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/wpa_supplicant( 2021): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2021): EAPOL: disable timer tick
,D/dalvikvm( 4958): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4989): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4958): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4958): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 80ms
,I/Adreno-EGL( 4958): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4958): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4958): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4958): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4958): Remote Branch: 
I/Adreno-EGL( 4958): Local Patches: 
I/Adreno-EGL( 4958): Reconstruct Branch: 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 4958): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  957): NetTransition Wakelock for ConnectedState released by timeout
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=2956319518
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4958): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4958): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4958): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4958): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4958): Remote Branch: 
I/Adreno-EGL( 4958): Local Patches: 
I/Adreno-EGL( 4958): Reconstruct Branch: 
,I/Adreno-EGL( 4958): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4958): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4958): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4958): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4958): Remote Branch: 
I/Adreno-EGL( 4958): Local Patches: 
I/Adreno-EGL( 4958): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1939): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1939): Sending checkin request (11582 bytes)
,D/DhcpStateMachine(  957): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  957): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  957): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  957): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  957): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  957): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  957): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  957): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  957): RunningState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  957): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  957): handleMessage: E msg.what=131212
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
,D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
D/WifiStateMachine(  957): processMsg: SupplicantStartedState
,D/WifiStateMachine(  957): processMsg: DefaultState
,D/WifiStateMachine(  957): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  957): send additional Connectivity Action
,D/LocSvc_java(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  957): handleConnectivityChange:1 is conntected
,D/WifiStateMachine(  957): handleMessage: X
D/LocSvc_java(  957): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  957): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  957): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  957):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  957): Exception while trying to add src route: java.lang.NullPointerException
,D/GpsLocationProvider(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  957): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1939): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1939): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,W/CheckinRequestBuilder( 1939): awaiting user notification for token
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/NotificationService(  957): updateLightListLocked :r=NotificationRecord(0x43e2df10: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  957): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  957): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
I/CheckinRequestBuilder( 1939): Classify the device as Phone.
,I/CheckinTask( 1939): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1939): Checking schedule, now: 1452699396367 next: 1453276792364
,I/CheckinService( 1939): active receiver: disabled
,D/GCM     ( 1532): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1532): Connected
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1532): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
E/Parcel  (  528): Reading a NULL string not supported here.
,E/Parcel  (  528): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  957): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  957): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
,D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@428256c8
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 3036): start selecting data
,D/SIMObserver( 3036): simInfo1
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  957): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  957): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  957): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/dalvikvm(  957): GC_EXPLICIT freed 2614K, 49% free 29693K/57892K, paused 2ms+6ms, total 110ms
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4037): begin check event
,I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4037): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4037): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4037): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4037): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4037): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 4810): DownloadService onCreate
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4591): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4810): in removeSpuriousFiles
,V/DownloadManager( 4810): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@42858b00 on behalf of 4810
I/LgeMiscReceiver( 4383): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4383): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4383): networkInfo.isConnected() = false
,I/DownloadManager( 4810): in trimDatabase
,V/DownloadManager( 4810): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/Settings( 4591): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4835): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4835): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@4285a048 on behalf of 4810
,V/DownloadManager( 4810): DownloadService onStartCommand
,V/DownloadManager( 4810): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2916): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@4285bd80 on behalf of 4810
,D/LGDMSGCM( 4884): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2916): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 4884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2916): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4912): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4912): CONNECT : WIFI_CONNECT
V/DownloadManager( 4810): DownloadService onDestroy
E/LGDMClient( 2916): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2916): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2916): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2916): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/jxcore-log( 4679): Test app app.js loaded
I/jxcore-log( 4679): 
I/Choreographer( 4679): Skipped 403 frames!  The application may be doing too much work on its main thread.
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/chromium( 4679): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@428256c8
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4037): isOpenOperator : true
D/AppUp4:CustFacade( 4037): isPhone : true
I/LicenseContentProvider( 3036): start selecting data
D/SIMObserver( 3036): simInfo1
I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4037): begin check event
I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/DownloadManager( 4810): DownloadService onCreate
D/EAS     ( 4591): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4591): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4810): in removeSpuriousFiles
V/DownloadManager( 4810): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@42860830 on behalf of 4810
V/DownloadManager( 4810): DownloadService onStartCommand
I/DownloadManager( 4810): in trimDatabase
V/DownloadManager( 4810): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@42861db8 on behalf of 4810
,V/DownloadManager( 4810): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/Settings( 4591): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/LgeMiscReceiver( 4383): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4383): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4383): networkInfo.isConnected() = true
D/PhoneState( 4383): setPdpRejectCasuse : false
V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@42863af0 on behalf of 4810
D/MobileConnectivityChangeReceiver( 4835): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4835): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4810): DownloadService onDestroy
,D/LGDMClient( 2916): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4884): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2916): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2916): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4912): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4912): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2916): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2916): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2916): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2916): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  957): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  957): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
D/HeadsetStateMachine( 1217): Disconnected process message: 10
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  957): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  957): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiServiceExtension(  957): MESSAGE_INTERNET_CHECK msg is received.
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
,D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@428256c8
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 3036): start selecting data
,D/SIMObserver( 3036): simInfo1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4037): begin check event
,I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4810): DownloadService onCreate
,I/DownloadManager( 4810): in removeSpuriousFiles
V/DownloadManager( 4810): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4591): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/WifiServiceExtension(  957): isInternetConnectionAvailable - We got a valid response : 204
I/WifiServiceExtension(  957): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,V/DownloadManager( 4810): DownloadService onStartCommand
,V/DownloadManager( 4810): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@4286a2a8 on behalf of 4810
,V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@42868210 on behalf of 4810
I/LgeMiscReceiver( 4383): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4383): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4383): networkInfo.isConnected() = true
,D/PhoneState( 4383): setPdpRejectCasuse : false
I/DownloadManager( 4810): in trimDatabase
,V/DownloadManager( 4810): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/MobileConnectivityChangeReceiver( 4835): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4835): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4591): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4810): created cursor android.database.sqlite.SQLiteCursor@4286c238 on behalf of 4810
,V/DownloadManager( 4810): DownloadService onDestroy
,D/LGDMClient( 2916): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2916): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4884): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2916): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4912): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4912): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2916): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2916): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2916): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2916): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
W/ContextImpl( 4884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GAV2    ( 4926): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  957): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
D/HeadsetStateMachine( 1217): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  957): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  957): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
E/Parcel  (  528): Reading a NULL string not supported here.
,E/Parcel  (  528): Reading a NULL string not supported here.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/ActivityManager(  957): Killing 4609:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4263): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4263): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/InputReader(  957): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "sms"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  957): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5133 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,D/administrator(  957): Handling package changes for user 0
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "smsto"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1138): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1138): changeTargets() succeeded. size: 20
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mms"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 4063): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 4063): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mmsto"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 5133): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5133): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5133): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "sms"
,I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "smsto"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mms"
D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/WifiController(  957): battery changed pluggedType: 2
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mmsto"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5133): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5133): MmsConfig.loadMmsSettings
I/Babel   ( 5133): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5133): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5133): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5133): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5133): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5133): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5133): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5133): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5133): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5133): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5133): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5133): MmsConfig.loadFromResources
E/Babel   ( 5133): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5133): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5133): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4037): [getPackageName] uri : package:com.google.android.gms
V/LGRssiData( 5133): [loadRssi] File not exist 
D/AppUp4  ( 4037): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 4037): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/LGRssiData( 5133): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5133): [loadFeatureFromXml] *** start feature loading from xml
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@428256c8
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4037): isOpenOperator : true
D/AppUp4:CustFacade( 4037): isPhone : true
,V/TelephonyAutoProfiling( 5133): [getMatchedProfile] selected file : /cust/config/featureset.xml
I/LicenseContentProvider( 3036): start selecting data
V/TelephonyAutoProfiling( 5133): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,D/SIMObserver( 3036): simInfo1
,V/TelephonyAutoProfiling( 5133): [getValue] FEATURE key : vzw_roaming_state, value : null
I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4037): begin check event
D/AppUp4:Utils( 4037): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4037): Event For Nothing, skip.
,I/ActivityManager(  957): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5180 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5180): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5180): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5180): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1425): DISABLE
,I/GCoreNlp( 1425): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SystemConfig( 5180): BUILD Country: EU
,I/SystemConfig( 5180): BUILD Operator: OPEN
,I/ActivityManager(  957): Killing 4749:com.lge.sync/1000 (adj 15): empty #17
,I/SystemConfig( 5180): systemFeature RCS result false
,D/SystemConfig( 5180): refreshRcsSupport() :false
,I/ActivityManager(  957): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5197 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  957): Killing 4783:com.lge.qremote/u0a96 (adj 15): empty #17
,D/LocationProviderProxy(  957): applying state to connected service
,D/LocationProviderProxy(  957): applying state to connected service
D/HyLog   ( 5197): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5197): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5197): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.433365 Y: -0.393066 Z: 9.809448 
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.441132 Y: -0.399719 Z: 9.823883 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.433365 .y:-0.393066 .z:9.809448
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,I/ActivityManager(  957): Killing 4810:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 2 tasks}
,I/IcingCorporaProvider( 2668): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1939): Null package name or gms related package.  Ignoreing.
V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.459366 Y: -0.417892 Z: 9.835159 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459366 .y:-0.417892 .z:9.835159
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,I/Icing   ( 1939): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1939): GC_CONCURRENT freed 1942K, 22% free 19568K/24832K, paused 3ms+5ms, total 55ms
,D/dalvikvm( 1939): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/IcingCorporaProvider( 2668): UpdateCorporaTask done [took 250 ms] updated apps [took 250 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  957): battery changed pluggedType: 2
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
E/Parcel  (  528): Reading a NULL string not supported here.
,E/Parcel  (  528): Reading a NULL string not supported here.
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/CaptivePortalTracker(  957): DelayedCaptiveCheckState{ when=-4ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  957): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  957): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  957): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  957): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  957): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  957): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  957): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/GAV4    ( 5133): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,I/PowerManagerService(  957): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  957): [updateScreenState] screen on = false
D/KnockOnPowerController(  957): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  957): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  957): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,D/KnockOnPowerController(  957): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  957): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  957): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  957): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  957): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  957): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 6866 usec
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  957): hal_acquire_resources
,I/qcom_sensors_hal(  957): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  957): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  957): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  957): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  957): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  957): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  957): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  957): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.450653 Y: -0.413361 Z: 9.812180 
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450653 .y:-0.413361 .z:9.812180
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,I/Sensors (  477): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  957): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  957): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  957): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.455612 Y: -0.407227 Z: 9.820206 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455612 .y:-0.407227 .z:9.820206
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,D/KnockOnPowerController(  957): proximity onSensorChanged : proximity = 1
,D/KnockOnPowerController(  957): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  957): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.447327 Y: -0.398788 Z: 9.818222 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447327 .y:-0.398788 .z:9.818222
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1,
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.435913 Y: -0.405167 Z: 9.807068 
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.435913 .y:-0.405167 .z:9.807068
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.442383 Y: -0.408096 Z: 9.806061 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442383 .y:-0.408096 .z:9.806061
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.440475 Y: -0.406174 Z: 9.833023 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440475 .y:-0.406174 .z:9.833023
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  957): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@448c16c0)
,D/KeyguardViewMediator( 1138): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1138): notifyScreenOnLocked
,D/KeyguardViewMediator( 1138): handleNotifyScreenOn
,D/LockPatternUtilsEx( 1138): OMADM Lock is OFF
,D/KeyguardViewManager( 1138): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  957): **** SHOWN CALLED ****
,I/WindowManager(  957): No lock screen! windowToken=null
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb86b9450
D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/WifiStateMachine(  957): handleScreenStateChanged: true
,D/WifiStateMachine(  957): handleMessage: E msg.what=131154
D/WifiStateMachine(  957): processMsg: ConnectedState
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131127
D/WifiStateMachine(  957): processMsg: ConnectedState
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
,D/WifiStateMachine(  957): handleMessage: E msg.what=131158
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  957): handleMessage: X
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/WifiServiceExtension(  957): sendKtScanInterval  mRtspPlay : false
,D/WifiStateMachine(  957): handleMessage: E msg.what=132097
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  957): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2021): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2021): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  957): stopMonitoring
,E/AudioSystem(  957): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 957
V/SRS_Proc(  270): ParamSet string: screen_state=on
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1152): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1152): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{432e7c18 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1152): enqueuing start. mLedList.size()=2
,D/qdlights( 1152): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1152): updateLightsLocked() start. mLedList.size=3
,E/SlideAside( 4063): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
D/EmotionalLed( 1152): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1152): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
,E/CliptrayService( 1152): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherAncestor( 1831): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:36:57
I/SlideAside( 4063): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/UpdateThreadPoolManager( 1831): 2 : This is isUpdating : false
D/WeatherAncestor( 1831): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:36:57
D/WeatherService( 1831): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1831): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1831): 2 : shouldTimeTickRegistered : false
D/qdlights( 1152): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 255, B = 255
D/LockPatternUtilsEx( 1138): OMADM Lock is OFF
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
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.455139 Y: -0.388947 Z: 9.826233 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455139 .y:-0.388947 .z:9.826233
D/qdlights( 1152): set_light_notifications: 2,ff00f9f9,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 249, B = 249
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,D/qdlights( 1152): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1152): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1152): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1152): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1152): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 219, B = 219
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  957): Excessive delay in blankDisplay() while turning screen off: 400ms
D/qdlights( 1152): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 213, B = 213
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,D/qdlights( 1152): set_light_notifications: 2,ff00cfcf,10,0,2
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.446594 Y: -0.389038 Z: 9.835526 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446594 .y:-0.389038 .z:9.835526
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,D/qdlights( 1152): [Current] = 255, R = 0, G = 207, B = 207
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GlobalAccess( 1138): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1138): changeTargets() succeeded. size: 20
,D/qdlights( 1152): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 201, B = 201
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452699417897, nextTick: 2135, mDrawingTime: 0
,D/qdlights( 1152): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 195, B = 195
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452699417914, nextTick: 2119, mDrawingTime: 0
D/qdlights( 1152): set_light_notifications: 2,ff00bdbd,10,0,2
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/qdlights( 1152): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1152): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 183, B = 183
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1152): set_light_notifications: 2,ff00b1b1,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 177, B = 177
D/WeatherService( 1831): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:36:57
D/WeatherService( 1831): 2 : ACTION screen on
D/WeatherService( 1831): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1831): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:36:57
D/qdlights( 1152): set_light_notifications: 2,ff00abab,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 171, B = 171
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1152): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 165, B = 165
,E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
,E/Parcel  (  528): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : trf_based_vzw, value : null
,D/qdlights( 1152): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 159, B = 159
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/BubblePopupHelper( 1138): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1152): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 153, B = 153
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  957): ACTION_SCREEN_ON
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/qdlights( 1152): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 147, B = 147
,I/qcom_sensors_hal(  957): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  957): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  957): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  957): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1138): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1138): notifyScreenOffLocked
,V/ActivityManager(  957): Moving to PAUSING: ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
D/qdlights( 1152): set_light_notifications: 2,ff008d8d,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 141, B = 141
D/qcom_sensors_hal(  957): hal_acquire_resources
D/qcom_sensors_hal(  957): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  957): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  957): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  957): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  957): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1152): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1152): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 129, B = 129
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ProcessCpuTracker(  957): Skipping unknown process pid 5255
,W/ProcessCpuTracker(  957): Skipping unknown process pid 5256
W/ProcessCpuTracker(  957): Skipping unknown process pid 5267
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,W/ProcessCpuTracker(  957): Skipping unknown process pid 5276
,D/qdlights( 1152): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 123, B = 123
W/ProcessCpuTracker(  957): Skipping unknown process pid 5277
V/ActivityManager(  957): Moving to PAUSED: ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  957): Moving to STOPPING: ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,D/UsbSettings( 2596): [AUTORUN] onDestroy() : getDefaultFunction =boot
,D/KeyguardViewMediator( 1138): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qdlights( 1152): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 117, B = 117
V/ActivityManager(  957): Moving to DESTROYING: ActivityRecord{43020de0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  957): Moving to STOPPED: ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3} (stop complete)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/UsbSettings( 2596): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2596): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2596): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
I/LGImmersionVibrator(  957): Vibrator off
D/WifiStateMachine(  957): handleScreenStateChanged: false
D/WifiStateMachine(  957): handleMessage: E msg.what=131154
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131158
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  957): doBoolean: DRIVER SETSUSPENDMODE 1
D/qdlights( 1152): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 111, B = 111
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/WifiController(  957): CMD_SCREEN_OFF 
,D/WifiController(  957): shouldWifiStayAwake TRUE
E/AudioSystem(  957): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 957
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,I/EmotionalLed( 1152): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/qdlights( 1152): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 105, B = 105
D/KeyguardViewMediator( 1138): handleNotifyScreenOff
,D/KeyguardViewManager( 1138): onScreenTurnedOff()
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  957):    returned true
D/WifiStateMachine(  957): handleMessage: X
,E/CliptrayService( 1152): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
V/ActivityManager(  957): Moving to DESTROYED: ActivityRecord{43020de0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b98290 stackId=1, 1 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,D/VolumeVibrator( 1152): clear
D/qdlights( 1152): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 99, B = 99
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
,I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1152): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 93, B = 93
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
D/qdlights( 1152): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 87, B = 87
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : trf_based_vzw, value : null
D/WeatherService( 1831): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:36:58
D/WeatherService( 1831): 2 : ACTION screen off
,D/WeatherService( 1831): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:36:58
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
E/Parcel  (  528): Reading a NULL string not supported here.
,E/Parcel  (  528): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1138): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1152): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1152): [Current] = 255, R = 0, G = 81, B = 81
,D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_OFF
,D/NfcService( 1475): NFC-C OFF
,D/LockPatternUtilsEx( 1138): OMADM Lock is OFF
D/qdlights( 1152): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 75, B = 75
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  957): ACTION_SCREEN_OFF
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/qdlights( 1152): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1152): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1152): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1152): [Current] = 255, R = 0, G = 57, B = 57
D/WifiStateMachine(  957): handleMessage: E msg.what=131155
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiStateMachine(  957): handleMessage: X
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
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  477): sns_pwr.c(320):releasing wakelock
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1138): handleTimeUpdate
,D/KeyguardModel( 1138): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452699420042, nextTick: 59972, mDrawingTime: 6
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452699420055, nextTick: 59977, mDrawingTime: 0
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiStateMachine(  957): handleMessage: X
,D/KeyguardViewMediator( 1138): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1138): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1138): OMADM Lock is OFF
,D/KeyguardViewMediator( 1138): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1138): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1452699436081785158; DSPS: 5285210; Offset: 1452699274789976076
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1152): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  957): battery changed pluggedType: 2
D/HeadsetStateMachine( 1217): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1138): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1138): handleBatteryUpdate (2) (100)
,I/VacuumService( 1532): Vacuum at: now=1452699448320 tag=VacuumService
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/EventLogService( 1939): Aggregate from 1452699394277 (log), 1452697636047 (data)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1452699456083408068; DSPS: 5940623; Offset: 1452699274789981555
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1452699476085266237; DSPS: 6596044; Offset: 1452699274789978152
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1138): handleTimeUpdate
,D/KeyguardModel( 1138): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452699480037, nextTick: 59961, mDrawingTime: 13
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452699480059, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1452699496086858364; DSPS: 7251456; Offset: 1452699274789983364
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1452699516088664763; DSPS: 7906876; Offset: 1452699274789958709
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1452699536089959078; DSPS: 8562278; Offset: 1452699274789971286
,D/KeyguardUpdateMonitor( 1138): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1138): handleTimeUpdate
,D/KeyguardModel( 1138): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452699540020, nextTick: 59977, mDrawingTime: 16
,D/Clock   ( 1138): Clock updated, drawingStartTime : 1452699540072, nextTick: 59959, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1452699556091757301; DSPS: 9217697; Offset: 1452699274789968971
,I/jxcore-log( 4679): --= Surplus to requirements =--
I/jxcore-log( 4679): 
,I/jxcore-log( 4679): ****TEST TOOK:  ms ****
I/jxcore-log( 4679): 
,I/jxcore-log( 4679): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4679): 
,D/AndroidRuntime( 5474): 
D/AndroidRuntime( 5474): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5474): CheckJNI is OFF
,D/dalvikvm( 5474): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5474): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 5474): Trying to load lib libnativehelper.so 0x0
,D/dalvikvm( 5474): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5474): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5474): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5474): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5474): failed to load memtrack module: -2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 5474): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  957): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  957): Killing 4679:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  957): Moving to DESTROYED: ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
,I/MDM     (  957):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  957):   Force finishing activity ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  957): Moving to FINISHING: ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  957): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  957): moveHomeStack:
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c22cd8 stackId=0, 1 tasks}
,V/ActivityManager(  957): Moving to RESUMED: ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  957): Moving to PAUSING: ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  957): resumeTopActivityLocked: Resumed ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c22cd8 stackId=0, 1 tasks}
D/ActivityManager(  957): allPausedActivitiesComplete: r=ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  957): allPausedActivitiesComplete: r=ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  957): resumeTopActivityLocked: Skip resume: some activity pausing.
,V/ActivityManager(  957): Moving to DESTROYED: ActivityRecord{42ab9718 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c22cd8 stackId=0, 1 tasks}
D/ActivityManager(  957): allPausedActivitiesComplete: r=ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  957): allPausedActivitiesComplete: r=ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  957): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1488): [Launcher.java:4947:onStart()]onStart
I/WindowState(  957): WIN DEATH: Window{431511e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  957): Client connection lost with reason: 4
,W/PackageSettings(  957): Skipping PackageSetting{42ce5d58 com.example.hello/10312} due to missing metadata
,I/ActivityManager(  957): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c22cd8 stackId=0, 1 tasks}
D/ActivityManager(  957): allPausedActivitiesComplete: r=ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  957): allPausedActivitiesComplete: r=ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  957): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1488): [Launcher.java:717:onResume()]onResume
,D/dalvikvm( 2668): GC_EXPLICIT freed 5370K, 27% free 18179K/24832K, paused 6ms+2ms, total 38ms
,D/KeyguardModel( 1138): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  957): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "sms"
,E/SlideAside( 4063): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/SlideAside( 4063): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/PhoneApp( 1450): getIsInUseVoLTE : false
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  957):   Scheme: "smsto"
D/AppUp4:Utils( 4037): [getPackageName] uri : package:com.test.thalitest
W/System.err( 2650): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 2650): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2650): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2650): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2650): 	at android.os.Handler.handleCallback(Handler.java:733)
W/GeofencerStateMachine( 1425): Ignoring removeGeofence because network location is disabled.
W/System.err( 2650): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2650): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2650): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2650): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2650): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2650): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2650): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2650): 	at dalvik.system.NativeStart.main(Native Method)
D/AppUp4  ( 4037): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 4037):  isExcludedPackage  packagename = com.test.thalitest
,I/ActivityManager(  957): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5496 uid=10090 gids={50090}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AppUp4  ( 4037):  isExcludedPackage TRUE : com.test.thalitest
,I/[LGHome]LGActivityUtil( 1488): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ActivityManager(  957): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  957):   Scheme: "mms"
,D/dalvikvm(  957): GC_EXPLICIT freed 2927K, 48% free 30094K/57796K, paused 3ms+18ms, total 119ms
,D/dalvikvm(  957): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/ActivityManager(  957): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mmsto"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1138): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1138): changeTargets() succeeded. size: 20
,D/KeyguardModel( 1138): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/administrator(  957): Handling package changes for user 0
I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "sms"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "smsto"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mms"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mmsto"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/BackupManagerService(  957): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/InteractionManagerConfigurator(  957): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  957): com.test.thalitest isn't inclued in dragdropPackageList
V/BackupManagerService(  957): removePackageParticipantsLocked: uid=10304 #1
,D/dalvikvm(  957): GC_EXPLICIT freed 712K, 49% free 29923K/57796K, paused 5ms+18ms, total 169ms
,D/dalvikvm(  957): WAIT_FOR_CONCURRENT_GC blocked 227ms
,I/[LGHome]EVENT( 1488): [Launcher.java:868:onResume()]onResume end
,I/[LGHome]EVENT( 1488): [Launcher.java:894:onPause()]onPause
V/ActivityManager(  957): Moving to PAUSED: ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  957): Moving to STOPPING: ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/HyLog   ( 5496): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5496): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5496): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
I/ActivityManager(  957): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5522 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/LockScreenSettings( 5496): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/[LGHome]EVENT( 1488): [Launcher.java:4955:onStop()]onStop
,I/[LGHome]EVENT( 1488): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/HyLog   ( 5522): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5522): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5522): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/Binder  ( 1308): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1308): java.lang.NullPointerException
W/Binder  ( 1308): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1308): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1308): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1308): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  957): IME STATUS OFF
W/InputMethodManagerService(  957): Got RemoteException sending setActive(false) notification to pid 4679 uid 10304
,D/[BNRAppListMgrReceiver]( 5522): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
,D/KeyguardModel( 1138): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1138): createShortcutInfo...
I/ActivityManager(  957): Killing 4591:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c22cd8 stackId=0, 1 tasks}
,D/VoicemailCleanupService( 1815): Cleaning up data for package: com.test.thalitest
D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardModel( 1138): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1138): createShortcutInfo...
D/KeyguardModel( 1138): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1138): createShortcutInfo...
,I/ActivityManager(  957): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5537 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
D/HyLog   ( 5537): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5537): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5537): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/ActivityManager(  957): Moving to STOPPED: ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/dalvikvm( 1138): GC_CONCURRENT freed 7571K, 10% free 70782K/78536K, paused 6ms+8ms, total 62ms
D/dalvikvm( 1138): WAIT_FOR_CONCURRENT_GC blocked 57ms
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/ActivityManager(  957): Timeline: Activity_windows_visible id: ActivityRecord{42a609d8 u0 com.lge.launcher2/.Launcher t1} time:281101
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/LGEmail ( 5537): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/LGEmail ( 5537): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,D/dalvikvm( 1488): GC_CONCURRENT freed 5659K, 9% free 60777K/66620K, paused 3ms+3ms, total 24ms
,D/dalvikvm( 1488): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/KeyguardModel( 1138): handleShortcutListChanged...
,D/KeyguardModel( 1138): handleShortcutListChanged...
I/ActivityManager(  957): Killing 4835:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,W/BaseRuntimeLoader( 5537): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5537): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5537): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5537): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c22cd8 stackId=0, 1 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,I/PackageChangeReceiver( 5537): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/dalvikvm(  957): GC_EXPLICIT freed 419K, 49% free 29759K/57796K, paused 4ms+15ms, total 240ms
,I/ActivityManager(  957): Killing 4856:com.android.chrome/u0a63 (adj 15): empty #17
D/PackageIntentReceiver( 2596): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 2596): Receive package name : com.test.thalitest
D/HideNavigationAppsReceiver( 2596): Delete mPackageMame : com.test.thalitest
I/IcingCorporaProvider( 2668): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
I/ActivityManager(  957): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5555 uid=10073 gids={50073, 3003, 1028, 1015}
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c22cd8 stackId=0, 1 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/HyLog   ( 5555): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5555): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5555): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,D/AndroidRuntime( 5474): Shutting down VM
,D/dalvikvm( 5474): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/IcingCorporaProvider( 2668): UpdateCorporaTask done [took 98 ms] updated apps [took 98 ms] 
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1488): Timeline: Activity_idle id: android.os.BinderProxy@4280c0c8 time:281345
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/GAV2    ( 5555): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  957): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5589 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 5589): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5589): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5589): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/ContextImpl( 5589): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,E/SQLiteLog( 1532): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,W/System.err( 1532): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/System.err( 1532): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
,W/System.err( 1532): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
W/System.err( 1532): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
W/System.err( 1532): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 1532): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
W/System.err( 1532): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
,W/System.err( 1532): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
W/System.err( 1532): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
W/System.err( 1532): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2424)
,W/System.err( 1532): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
W/System.err( 1532): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1276)
W/System.err( 1532): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 1532): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5589): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 5589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 5589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 5589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 5589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5589): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5589): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5589): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5589): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5589): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5589): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5589): threadid=10: thread exiting with uncaught exception (group=0x417cee48)
W/System.err( 1532): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 1532): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 1532): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 1532): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 1532): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 1532): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 1532): Sending signal. PID: 1532 SIG: 9
,I/Process ( 5589): Sending signal. PID: 5589 SIG: 9
I/dalvikvm( 4263): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4263): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 4263): VFY: replacing opcode 0x6e at 0x0013
E/AndroidRuntime( 5589): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5589): Process: com.android.keychain, PID: 5589
E/AndroidRuntime( 5589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/AndroidRuntime( 5589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/AndroidRuntime( 5589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 5589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/AndroidRuntime( 5589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5589): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5589): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5589): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5589): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5589): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 5589): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  957): Can't write: system_app_crash
E/DropBoxManagerService(  957): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  957): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  957): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  957): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  957): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  957): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  957): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  957): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  957): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  957): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  957): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  957): 	... 5 more
,I/ActivityManager(  957): Process com.android.keychain (pid 5589) has died.
W/ActivityManager(  957): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c22cd8 stackId=0, 1 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  957): Process com.google.process.gapps (pid 1532) has died.
W/ActivityManager(  957): Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService in 1000ms
,W/ActivityManager(  957): Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService$LightweightWorkerService in 11000ms
W/ActivityManager(  957): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
,W/ActivityManager(  957): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c22cd8 stackId=0, 1 tasks}
,W/RocketImpressions( 1939): ClearcutLogger connection suspended: 1
,E/SQLiteLog( 2650): (3850) statement aborts at 15: [INSERT INTO t001(f006,f003,f002,f005,f004) VALUES (?,?,?,?,?)] disk I/O error
,D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
E/SQLiteDatabase( 2650): Error inserting f006=-1 f003= f002=1452699560918 f005=1532 f004=20
E/SQLiteDatabase( 2650): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2650): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2650): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:785)
E/SQLiteDatabase( 2650): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 2650): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2650): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
E/SQLiteDatabase( 2650): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1440)
E/SQLiteDatabase( 2650): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 2650): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 2650): 	at android.content.ContentResolver.insert(ContentResolver.java:1206)
E/SQLiteDatabase( 2650): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2406)
E/SQLiteDatabase( 2650): 	at com.lge.mlt.MltMonitorService.access$2500(MltMonitorService.java:38)
E/SQLiteDatabase( 2650): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3210)
E/SQLiteDatabase( 2650): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2650): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2650): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3313)

```
