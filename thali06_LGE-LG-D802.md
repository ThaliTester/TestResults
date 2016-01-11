#### Test 55613145e2b298d_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
W/GAV2    ( 4863): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/dalvikvm( 1542): GC_EXPLICIT freed 799K, 29% free 17855K/24832K, paused 2ms+4ms, total 29ms
--------- beginning of /dev/log/system
I/ActivityManager(  964): Killing 4294:com.google.android.configupdater/u0a3 (adj 15): empty #17
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43071820 u0 com.android.settings/.UsbSettings t2}
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2206): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2206): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/ChimeraCfgMgr( 1944): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1944): Module APK com.google.android.play.games already loaded
I/ConfigFetchService( 1944): fetch service done; releasing wakelock
I/ConfigFetchService( 1944): stopping self
D/dalvikvm( 1944): GC_CONCURRENT freed 1539K, 22% free 19563K/24832K, paused 4ms+5ms, total 58ms
D/dalvikvm( 1944): WAIT_FOR_CONCURRENT_GC blocked 25ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1944): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1944): Loaded CLD2 Version V2.0 - 20141016
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1160): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Icing   ( 1944): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,E/BatteryObserver( 1160): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4912): 
D/AndroidRuntime( 4912): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4912): CheckJNI is OFF
D/dalvikvm( 4912): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4912): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4912): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4912): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4912): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4912): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4912): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4912): failed to load memtrack module: -2
D/AndroidRuntime( 4912): Calling main entry com.android.commands.am.Am
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4912
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (211 us)
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{43071820 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  964): resumeTopActivityLocked: Pausing null
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  964): startService SlideAside
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  964): setFocusedStack: mFocusedStack=ActivityStack{4331db58 stackId=1, 2 tasks}
D/UsbSettingsControl( 2567): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2567): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{43071820 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{43071820 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Restarting ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3810): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/AndroidRuntime( 4912): Shutting down VM
D/dalvikvm( 4912): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 2ms
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4929 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3810): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3810): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4929): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4929): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4929): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4929): Binding Chromium to the background looper Looper (main, tid 1) {4284e260}
I/chromium( 4929): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4929): Initializing chromium process, renderers=0
W/chromium( 4929): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4929): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4929): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4929): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4929): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4929): Remote Branch: 
I/Adreno-EGL( 4929): Local Patches: 
I/Adreno-EGL( 4929): Reconstruct Branch: 
I/dalvikvm( 4929): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4929): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4929): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4929): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4929): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4929): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4929): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4929): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4929): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4929): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4929): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4929): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4929): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4929): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4929): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4929): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/BaseRuntimeLoader( 4929): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4929): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4929): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4929): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4929): Enabling debug mode 0
,W/AwContents( 4929): nativeOnDraw failed; clearing to background color.
,W/AwContents( 4929): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  964): IME STATUS OFF
,I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +442ms
,I/ActivityManager( 4929): Timeline: Activity_idle id: android.os.BinderProxy@4284fa30 time:119652
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/JsMessageQueue( 4929): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4929): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42853b10
,D/dalvikvm( 4929): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42853b10
,D/jxcore_app_log( 4929): JniHelper::setJavaVM(0x41713838), pthread_self() = 1632134552
,D/JX-Cordova( 4929): jxcore cordova android initializing
,I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3} time:119967
D/ActivityManager(  964): no-history finish of ActivityRecord{43071820 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  964): Finishing activity token=Token{4313a7c8 ActivityRecord{43071820 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
,D/UsbSettings( 2567): [AUTORUN] onStop()
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{43071820 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{43071820 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{43071820 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4929): GC_CONCURRENT freed 2784K, 12% free 21869K/24832K, paused 3ms+1ms, total 52ms
,D/dalvikvm( 4929): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4929): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 136K, 12% free 21875K/24832K, paused 32ms, total 32ms
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 130K, 12% free 21891K/24832K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4929): Grow heap (frag case) to 23.644MB for 96598-byte allocation
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 180K, 13% free 21926K/24928K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4929): Grow heap (frag case) to 23.723MB for 144892-byte allocation
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 254K, 13% free 21974K/25072K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4929): Grow heap (frag case) to 23.839MB for 217334-byte allocation
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 369K, 13% free 22049K/25288K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4929): Grow heap (frag case) to 24.017MB for 325996-byte allocation
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 572K, 14% free 22170K/25608K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4929): Grow heap (frag case) to 24.290MB for 488990-byte allocation
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 868K, 15% free 22346K/26088K, paused 23ms, total 23ms
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 1289K, 14% free 22604K/26088K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4929): Grow heap (frag case) to 25.296MB for 1100216-byte allocation
,D/dalvikvm( 4929): GC_CONCURRENT freed 1781K, 16% free 22990K/27164K, paused 2ms+3ms, total 30ms
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 285K, 16% free 22921K/27164K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4929): Grow heap (frag case) to 26.131MB for 1650320-byte allocation
,D/dalvikvm( 4929): GC_CONCURRENT freed 1684K, 19% free 23505K/28776K, paused 2ms+2ms, total 29ms
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2206): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2206): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 1332K, 19% free 23571K/28776K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4929): Grow heap (frag case) to 27.553MB for 2475476-byte allocation
,D/dalvikvm( 4929): GC_CONCURRENT freed 404K, 17% free 26008K/31196K, paused 2ms+5ms, total 59ms
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 4265K, 22% free 24557K/31196K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4929): Grow heap (frag case) to 29.696MB for 3713210-byte allocation
,D/dalvikvm( 4929): GC_CONCURRENT freed 510K, 20% free 28016K/34824K, paused 2ms+3ms, total 57ms
,D/dalvikvm( 4929): GC_FOR_ALLOC freed 3081K, 27% free 25508K/34824K, paused 25ms, total 26ms
,W/jxcore-log( 4929): Initializing JXcore engine
,W/jxcore-log( 4929): JXcore engine is ready
,D/dalvikvm( 4929): GC_CONCURRENT freed 320K, 20% free 28183K/34824K, paused 1ms+1ms, total 27ms
,D/dalvikvm( 4929): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4929): Starting JXcore engine
,W/jxcore-log( 4929): Platform android
W/jxcore-log( 4929): 
,W/jxcore-log( 4929): Process ARCH arm
W/jxcore-log( 4929): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4863): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4929): JXcore Cordova bridge is ready!
I/jxcore-log( 4929): 
,W/jxcore-log( 4929): JXcore engine is started
,I/chromium( 4929): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4929): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4929): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/ConfigService( 1542): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/jxcore-log( 4929): Toggling radios to true
I/jxcore-log( 4929): 
D/BluetoothManagerService(  964): Message: 20
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43e6d5d0:true
,D/BluetoothAdapter( 4929): enable(): BT is already enabled..!
D/WifiStateMachine(  964): handleMessage: E msg.what=131145
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doBoolean: DISCONNECT
D/WifiService(  964): New client listening to asynchronous messages
D/WifiService(  964): setWifiEnabled: true pid=4929, uid=10304
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  964): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  964): disconnect pid=4929, uid=10304
I/jxcore-log( 4929): Radios toggled
I/jxcore-log( 4929): 
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2206): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2206): wlan0: Cancelling scan request
D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2206): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2206): TDLS: Tear down peers
D/wpa_supplicant( 2206): wpa_driver_nl80211_disconnect(reason_code=3)
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4929): Received device characteristics:
I/jxcore-log( 4929): Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4929): Bluetooth name: Thali Test's G2
I/jxcore-log( 4929): Device name: LGE-LG-D802
I/jxcore-log( 4929): 
,I/jxcore-log( 4929): Perf Test app loaded loaded
I/jxcore-log( 4929): 
D/WifiService(  964): reconnect pid=4929, uid=10304
,D/wpa_supplicant( 2206): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2206): wlan0: Deauthentication notification
D/wpa_supplicant( 2206): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2206): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2206): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2206): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2206): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2206): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb846fd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2206):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2206): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2206): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2206): nl80211: Event message available
D/wpa_supplicant( 2206): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2206): nl80211: Ignore disconnect event triggered during reassociation
,I/Choreographer( 4929): Skipped 74 frames!  The application may be doing too much work on its main thread.
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
,W/Settings(  964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131146
D/WifiStateMachine(  964): processMsg: DisconnectingState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiNative-wlan0(  964): doBoolean: RECONNECT
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2206): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2206): Fast associate: Old scan results
D/wpa_supplicant( 2206): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2206): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2206): wlan0: nl80211: scan request
,D/wpa_supplicant( 2206): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147460
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection lost
D/wpa_supplicant( 2206): Scan requested (ret=0) - scan timeout 30 seconds
,D/wpa_supplicant( 2206): nl80211: Event message available
D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2206): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2206): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2206): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2206): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2206): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
,D/DhcpStateMachine(  964): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4929): check test folder
I/jxcore-log( 4929): 
,D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 4929): found test : ./testFindPeers.js
I/jxcore-log( 4929): 
,D/WifiStateMachine(  964): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,I/jxcore-log( 4929): found test : ./testSendData.js
I/jxcore-log( 4929): 
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
D/QCNEA   (  527): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  527): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  527): |CAC| updateNetCfgInfo
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC|                   Netconfig               
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  527): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  527): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  527): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  527): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  527): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  527): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| Received bssid= 
D/QCNEA   (  527): |CAC| net type = 3
V/QCNEA   (  527): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  527): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  527): |CAC| 	ssid           =NG700
V/QCNEA   (  527): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  527): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  527): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  527): |CAC| dispatchNetCfg: updating:0xb81708dc
,D/QCNEA   (  527): |CAC| readCallback: read len:0, ret:-1, errno:11
D/WifiHS20(  964): hidePasspointNotification off =false
,D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
V/WfdStateTracker( 1160): handleWifiStateChangedEvent: 0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
,D/WifiStateMachine(  964): handleMessage: X
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131213
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
,D/WifiStateMachine(  964): handleMessage: X
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4979 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
D/HyLog   ( 4979): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4979): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4979): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,I/PCSuite ( 4979): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  264): RouteController
D/PCSuite ( 4979): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4979): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5013 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  964): Killing 4425:com.google.android.talk/u0a77 (adj 15): empty #17
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
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x63788048 clazz=0x6cd00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
,V/NativeCrypto( 1542): Read error: ssl=0x6240ac08: I/O error during system call, Connection timed out
,V/NativeCrypto( 1542): SSL shutdown failed: ssl=0x6240ac08: I/O error during system call, Broken pipe
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5013): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5013): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5013): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 5013): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,I/chromium( 4929): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/QRemote ( 5013): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 5013): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 5013): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 5013): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 5013): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/QRemote ( 5013): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5013): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5013): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 3086:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  964): StoppedState
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  964): battery changed pluggedType: 2
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1228): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1228): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.454193 Y: -0.387558 Z: 9.827347 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454193 .y:-0.387558 .z:9.827347
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.442566 Y: -0.400528 Z: 9.802704 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442566 .y:-0.400528 .z:9.802704
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :false
D/wpa_supplicant( 2206): nl80211: Event message available
D/wpa_supplicant( 2206): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2206): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2206): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2206): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 2206): nl80211: Survey data missing
D/wpa_supplicant( 2206): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 8 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 9 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 10 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 2206): wlan0: New scan results available
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2206): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2206): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2206): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2206): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2206): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[4] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2206): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2206): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2206): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2206): wlan0: Consider,ing connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84715a8  current_ssid=0x0
D/wpa_supplicant( 2206): scard is not null..
D/wpa_supplicant( 2206): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2206): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2206): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2206): wlan0: Cancelling scan request
D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
,D/wpa_supplicant( 2206): wlan0: WPA: clearing own WPA/RSN IE,
,D/wpa_supplicant( 2206): wlan0: Automatic auth_alg selection: 0x1,
D/wpa_supplicant( 2206): RSN: PMKSA cache search - network_ctx=0xb84715a8 try_opportunistic=0,
,D/wpa_supplicant( 2206): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2206): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2206): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2206): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2206): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2206): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2206): wlan0: WPA: using GTK CCMP,
D/wpa_supplicant( 2206): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2206): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2206): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2206): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE,
D/wpa_supplicant( 2206): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2206): wlan0: State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2206): nl80211: Set mode ifindex 23 iftype 2 (STATION)
,D/wpa_supplicant( 2206): nl80211: Unsubscribe mgmt frames handle 0xb8470590 (mode change)
D/wpa_supplicant( 2206): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
,D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590,
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590,
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09,
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=1): 06,
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 0a 11,
D/wpa_supplicant( 2206): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2206):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206):   * freq=2412,
D/wpa_supplicant( 2206):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2206):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206):   * Auth Type 0
D/wpa_supplicant( 2206):   * WPA Versions 0x2
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 c2:ff:d4:d3:aa:48],
D/wpa_supplicant( 2206): nl80211: Connect request send successfully,
D/wpa_supplicant( 2206): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - portControl=Auto,
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 06:7c:34:12:7f:81],
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 38:f8:89:11:e9:11]
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
,D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState,
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2206): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311),
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2206): nl80211: Event message available
D/wpa_supplicant( 2206): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2206): nl80211: Connect event
D/wpa_supplicant( 2206): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2206): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2206): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2206): wlan0: Association info event
D/wpa_supplicant( 2206): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2206): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2206): wlan0: freq=2412 MHz
D/wpa_supplicant( 2206): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2206): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2206): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2206): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): scard is not null..
D/wpa_supplicant( 2206): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2206): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2206): TDLS: Remove peers on association
D/wpa_supplicant( 2206): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2206): EAPOL: enable timer tick
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2206): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2206): wlan0: Cancelling scan request
,D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2206): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 6b dc f6 db 95 2c 62 9d 3b 85 08 67 7a 17 70 ...
D/wpa_supplicant( 2206): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2206): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2206): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2206): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2206): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2206):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2206):   key_nonce - hexdump(len=32): 6b dc f6 db 95 2c 62 9d 3b 85 08 67 7a 17 70 9f e8 9f 9b 63 87 8a cb 06 ff 7d 8d 51 4a ca 95 ea
D/wpa_supplicant( 2206):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 6b dc f6 db 95 2c 62 9d 3b 85 08 67 7a 17 70 ...
D/wpa_supplicant( 2206): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2206): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2206): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2206): WPA: Renewed SNonce - hexdump(len=32): 3d 88 43 45 66 9c 5b 65 41 f9 50 0b 68 5c 58 fe 78 28 03 b4 42 d1 d4 6a 37 4e f2 9f ec 82 b3 d9
D/wpa_supplicant( 2206): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): WPA: Nonce1 - hexdump(len=32): 3d 88 43 45 66 9c 5b 65 41 f9 50 0b 68 5c 58 fe 78 28 03 b4 42 d1 d4 6a 37 4e f2 9f ec 82 b3 d9
D/wpa_supplicant( 2206): WPA: Nonce2 - hexdump(len=32): 6b dc f6 db 95 2c 62 9d 3b 85 08 67 7a 17 70 9f e8 9f 9b 63 87 8a cb 06 ff 7d 8d 51 4a ca 95 ea
D/wpa_supplicant( 2206): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2206): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2206): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2206): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2206): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2206): WPA: Derived Key MIC - hexdump(len=16): 49 98 77 66 32 52 43 08 76 5b 67 ee cc 2c be 30
,D/wpa_supplicant( 2206): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 3d 88 43 45 66 9c 5b 65 41 f9 50 0b 68 5c 58 ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/LicenseContentProvider( 4492): start selecting data
,D/SIMObserver( 4492): simInfo1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4470): begin check event
I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity, noConnectivity : true, but skip! 
,D/wpa_supplicant( 2206): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 6b dc f6 db 95 2c 62 9d 3b 85 08 67 7a 17 70 ...
D/wpa_supplicant( 2206): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2206): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2206): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2206): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2206):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2206):   key_nonce - hexdump(len=32): 6b dc f6 db 95 2c 62 9d 3b 85 08 67 7a 17 70 9f e8 9f 9b 63 87 8a cb 06 ff 7d 8d 51 4a ca 95 ea
D/wpa_supplicant( 2206):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 2206):   key_rsc - hexdump(len=8): 34 21 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_mic - hexdump(len=16): 9e 13 76 a4 6e 0d 4a 02 88 d7 47 2a 40 3d 32 a4
D/wpa_supplicant( 2206): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 6b dc f6 db 95 2c 62 9d 3b 85 08 67 7a 17 70 ...
D/wpa_supplicant( 2206): RSN: encrypted key data - hexdump(len=56): 63 24 a6 c4 2c 22 53 30 cd 5f 02 25 38 6e fe 9c 8d 3a 12 de 00 c7 eb 26 5b d1 f9 60 45 6d 5f ae ...
D/wpa_supplicant( 2206): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2206): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2206): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2206): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 6d 3b ...
D/wpa_supplicant( 2206): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2206): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2206): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2206): WPA: Derived Key MIC - hexdump(len=16): a7 42 2f 4f e6 a3 b0 03 b5 91 dd a5 3a 65 1f 3f
D/wpa_supplicant( 2206): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2206): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8470c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2206):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2206): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2206): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2206): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2206): WPA: RSC - hexdump(len=6): 34 21 00 00 00 00
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6fb203a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2206):    broadcast key
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
I/wpa_supplicant( 2206): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2206): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2206): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2206): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2206): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2206): EAPOL authentication completed successfully
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): Network connection established
,D/WifiNative-wlan0(  964): doString: STATUS
,I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5065 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2206): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-16ms what=147462 obj=android.net.wifi.StateChangeResult@43dd33d0 target=com.android.internal.util.StateMachine$SmHandler }
D/Wi,fiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-11ms what=147462 obj=android.net.wifi.StateChangeResult@44ffc120 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/DhcpStateMachine(  964): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-12ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-5ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2206): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2206): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+3ms, total 28ms
D/HyLog   ( 5065): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5065): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5065): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 22ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 21ms
,V/DownloadManager( 5065): DownloadService onCreate
,I/DownloadManager( 5065): in removeSpuriousFiles
D/EAS     ( 4841): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4841): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4841): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42894778 on behalf of 5065
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5065): in trimDatabase
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42896e80 on behalf of 5065
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428987f8 on behalf of 5065
I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4635): networkInfo.isConnected() = false
,W/linker  ( 4841): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4841): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4841): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4841): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4841): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4841): register_HtmlEditor, Success
D/HtmlEditor( 4841): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4841): register_HtmlEditorTimer, Success
,D/HtmlEditor( 4841): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4841): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4841): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4841): register_HtmlEditorFont, Success
D/HtmlEditor( 4841): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4841): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4841): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4841): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4841): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4841): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4841): JNI_OnLoad Success
V/DownloadManager( 5065): DownloadService onDestroy
I/HubEmail( 4841): JNI_OnLoad()
I/HubEmail( 4841): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4841): registerNatives()
,I/HubEmail( 4841): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4841): registerNativeMethods()
,I/HubEmail( 4841): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2206): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2206): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2206): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5086 uid=10052 gids={50052, 3003}
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
,D/WifiStateMachine(  964): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4328adf8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4328adf8 target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1160): usb Uevent not necessary.
,I/ActivityManager(  964): Killing 4017:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2206): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2206): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2206): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): DHCP successful
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
,D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiP2pService(  964): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/HyLog   ( 5086): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5086): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5086): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  964): handleMessage: X
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1228): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
,D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,E/Parcel  (  527): Reading a NULL string not supported here.
,D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
V/WfdStateTracker( 1160): handleWifiStateChangedEvent: 1
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/LGRssiData( 5086): [loadRssi] File not exist 
V/LGRssiData( 5086): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5086): [loadFeatureFromXml] *** start feature loading from xml
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
W/BaseRuntimeLoader( 5086): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5086): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5086): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5086): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 5086): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5086): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5086): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,D/MobileConnectivityChangeReceiver( 5086): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,V/        (  264): RouteController
,D/MobileConnectivityChangeReceiver( 5086): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 5086): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5086): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,V/        (  264): RouteController
I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5101 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  964): Killing 4610:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
,V/        (  264): RouteController
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 5101): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5101): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5101): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
I/CheckinService( 1944): Checking schedule, now: 1452523269596 next: 1452523203995
I/CheckinService( 1944): active receiver: enabled
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,D/QCNEA   (  527): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  527): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  527): |CAC| updateNetCfgInfo
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC|                   Netconfig               
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  527): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  527): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  527): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  527): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  527): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  527): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  527): |CAC| net type = 1
V/QCNEA   (  527): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
,D/QCNEA   (  527): |CAC| Received ssid= NG700
V/QCNEA   (  527): |CAC| 	ssid           =NG700
V/QCNEA   (  527): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  527): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  527): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  527): |CAC| dispatchNetCfg: updating:0xb81708dc
D/QCNEA   (  527): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/CheckinService( 1944): Preparing to send checkin request
I/EventLogService( 1944): Accumulating logs since 1452523170611
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/DhcpStateMachine(  964): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  964): GC_EXPLICIT freed 23551K, 49% free 29820K/57964K, paused 2ms+7ms, total 125ms
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5138 uid=10066 gids={50066, 4002, 3003, 1028}
,I/CheckinRequestBuilder( 1944): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  964): Killing 4778:com.android.defcontainer/u0a4 (adj 15): empty #17
E/ActivityThread( 1944): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5138): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5138): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5138): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): Killing 4331:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5151 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5151): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5151): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5151): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5151): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5151): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5165 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  964): Killing 4825:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
,D/HyLog   ( 5165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5165): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 5165): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5165): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 5165): intf.getDisplayName() = lo
I/Wireless_Storage( 5165): intf.getDisplayName() = sit0
,I/Wireless_Storage( 5165): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5165): intf.getDisplayName() = teql0
,I/Wireless_Storage( 5165): intf.getDisplayName() = wlan0
D/NFS     ( 5165): interface name:wlan0 name:wlan0
D/NFS     ( 5165): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5165): interface name:wlan0 name:wlan0
D/NFS     ( 5165): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 5165): CONNECT : WIFI_CONNECT
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5178 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 4505:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3}
V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/HyLog   ( 5178): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5178): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5178): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1944): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x4332f8d0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GAV2    ( 5178): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5195 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5195): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5195): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5195): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5195): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5195): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5195): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5195): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5195): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5195): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5195): install
,I/MultiDex( 5195): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5195): loading existing secondary dex files
,I/MultiDex( 5195): load found 3 secondary dex files
,I/MultiDex( 5195): install done
,D/dalvikvm( 5195): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 5195): VFY: unable to resolve instance field 61
,D/dalvikvm( 5195): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5195): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5195): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5195): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5195): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5195): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5195): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5195): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5195): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5195): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42853358
D/dalvikvm( 5195): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42853358
,D/dalvikvm( 5195): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42853358, skipping init
,D/dalvikvm( 5195): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42853358
D/dalvikvm( 5195): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42853358
,V/JNIHelp ( 5195): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 5178): Binding Chromium to the main looper Looper (main, tid 1) {4284b7d0}
,I/chromium( 5178): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5178): Initializing chromium process, renderers=0
,D/dalvikvm( 5195): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42853358
,D/dalvikvm( 5195): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42853358
D/dalvikvm( 5195): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42853358
,D/dalvikvm( 5195): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42853358
,W/chromium( 5178): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5178): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5178): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5178): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5178): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5178): Remote Branch: 
I/Adreno-EGL( 5178): Local Patches: 
I/Adreno-EGL( 5178): Reconstruct Branch: 
,I/NSApplication( 5178): Starting up...
,I/ActivityManager(  964): Killing 4520:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
,I/ProviderInstaller( 5195): Installed default security provider GmsCore_OpenSSL
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 5013): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5013): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5013): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5013): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5013): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5013): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4979): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
I/dalvikvm( 5195): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5195): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5195): VFY: replacing opcode 0x6e at 0x000d
,D/PCSuite ( 4979): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5013): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5013): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/dalvikvm( 5195): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5195): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5195): VFY: replacing opcode 0x6e at 0x0201
I/QRemote ( 5013): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5013): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1542): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1542): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1542): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1944): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WVCdm   (  270): Instantiating CDM.
I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1dc2000
E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1dc2000
D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
D/LocationInitializer( 1944): Restart initialization of location
D/WearableService( 4251): callingUid 10006, callindPid: 4251
E/MDM     ( 1427): [73] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  270): CdmEngine::OpenSession
D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=2171189939
D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
D/dalvikvm( 5195): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a236d8
D/dalvikvm( 5195): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a236d8
D/dalvikvm( 5195): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a236d8, skipping init
D/wpa_supplicant( 2206): EAPOL: startWhen --> 0
D/wpa_supplicant( 2206): EAPOL: disable timer tick
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
W/Settings( 5195): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/dalvikvm( 5195): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1160): usb Uevent not necessary.
D/dalvikvm( 5231): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
D/dalvikvm( 5195): DexOpt: --- END 'f.apk' (success) ---
D/dalvikvm( 5195): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 71ms
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/Adreno-EGL( 5195): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5195): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5195): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5195): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5195): Remote Branch: 
I/Adreno-EGL( 5195): Local Patches: 
I/Adreno-EGL( 5195): Reconstruct Branch: 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/WVCdm   (  270): CdmEngine::OpenSession
D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=971152525
D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,I/dalvikvm( 4929): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4929): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4929): Shutting down VM
,W/dalvikvm( 4929): threadid=1: thread exiting with uncaught exception (group=0x4180ee48)
E/AndroidRuntime( 4929): FATAL EXCEPTION: main
E/AndroidRuntime( 4929): Process: com.test.thalitest, PID: 4929
E/AndroidRuntime( 4929): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4929): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4929): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4929): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4929): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4929): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4929): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4929): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4929): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4929): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4929): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4929): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4929): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4929): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4929): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4929): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4929): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4929): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4929): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  964):   Force finishing activity com.test.thalitest/.MainActivity
,V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3 f}
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  964): handleMessage: X
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5246
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,I/Adreno-EGL( 5195): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5195): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5195): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5195): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5195): Remote Branch: 
I/Adreno-EGL( 5195): Local Patches: 
I/Adreno-EGL( 5195): Reconstruct Branch: 
,I/Adreno-EGL( 5195): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5195): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5195): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5195): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5195): Remote Branch: 
I/Adreno-EGL( 5195): Local Patches: 
I/Adreno-EGL( 5195): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1944): Classify the device as Phone.
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1944): Sending checkin request (11621 bytes)
,W/ActivityManager(  964): Activity pause timeout for ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4331db58 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  964): moveHomeStack:
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  964): resumeTopActivityLocked: Resumed ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1492): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1492): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1452): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1492): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1492): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1812): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:41:11
,D/UpdateThreadPoolManager( 1812): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1812): 2 : quick cover state : opened : 0
D/WeatherService( 1812): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1812): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1812): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1812): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1812): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1812): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:41:11
,D/WeatherService( 1812): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1812): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1812): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1812): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1812): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1812): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1812): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1812): 2 : This is isUpdating : false
D/WeatherService( 1812): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1812): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1812): 2 : Map key string is -2
,D/lim     ( 1812): 2 : time = 15:41
,I/WeatherReflect( 1812): Model Name : LG-D802
D/WeatherTheme( 1812): 2 : Different view - status_min_formatted : 39 != 41
,D/WeatherTheme( 1812): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1812): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1812): 2 : Fixed theme : optimus
,D/WeatherTheme( 1812): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1812): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1812): 2 : Utils getTopActivity com.lge.launcher2 / true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1812): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1812): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1144): GC_FOR_ALLOC freed 6740K, 10% free 71185K/78588K, paused 44ms, total 44ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge( 1492): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/CheckinResponseProcessor( 1944): From server: 0 gservices updates and 1 deletes
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1492): GC_CONCURRENT freed 6158K, 10% free 62303K/68640K, paused 2ms+7ms, total 54ms
,I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1} time:129836
,D/dalvikvm( 1492): GC_FOR_ALLOC freed 1837K, 12% free 60469K/68640K, paused 29ms, total 29ms
,I/dalvikvm-heap( 1492): Grow heap (frag case) to 63.217MB for 2088784-byte allocation
,I/CertBlacklister(  964): Certificate blacklist changed, updating...
,I/CertBlacklister(  964): Certificate blacklist updated
,I/GservicesProvider( 1542): main difference update completed
,I/CheckinRequestBuilder( 1944): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  964): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=5305 uid=10003 gids={50003, 3003, 2001}
E/ActivityThread( 1944): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 5305): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5305): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5305): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager( 1492): Timeline: Activity_idle id: android.os.BinderProxy@4284bf08 time:129972
,W/ContextImpl( 5305): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,D/UsbSettings( 2567): [AUTORUN] onDestroy() : getDefaultFunction =boot
,V/UsbSettings( 2567): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2567): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2567): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{43071820 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
I/UpdateFetcherService( 5305): Update started
,V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{43071820 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1}
,D/DownloadManager( 5065): DB Update : deleted 1
,V/DownloadManager( 5065): DownloadService onCreate
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): DownloadService onStartCommand
E/UpdateRequestReceiver( 5305): Received malformed URL while handling Gservices.CHANGED_ACTION
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428a3190 on behalf of 5065
,V/DownloadManager( 5065): initiating download with UID 10003
,I/DownloadManager( 5065): in trimDatabase
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428a9098 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428a9290 on behalf of 5065
,V/DownloadManager( 5065): processing inserted download 213
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=213:190
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428ad168 on behalf of 5065
,D/DownloadManager( 5065): DB Update : status 192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428afed8 on behalf of 5065
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428b1ef8 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 213, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=213:192
I/DownloadManager( 5065): Download 213 starting
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428b4b70 on behalf of 5065
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/DownloadManager( 5065): fileSize : -1state.mContinuingDownload :false
,W/ContextImpl( 5305): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 5305): Update started
,D/DownloadManager( 5065): DB Update : deleted 1
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/dalvikvm( 1542): GC_EXPLICIT freed 826K, 29% free 17847K/24832K, paused 1ms+3ms, total 25ms
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428c3aa0 on behalf of 5065
,V/DownloadManager( 5065): initiating download with UID 10003
,V/DownloadManager( 5065): processing updated download 213, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=213:192
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2206): wlan0: Control interface command 'SIGNAL_POLL'
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/wpa_supplicant( 2206): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  527): Reading a NULL string not supported here.
,E/Parcel  (  527): Reading a NULL string not supported here.
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428cf9d8 on behalf of 5065
V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataScheduler( 5065): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428d3708 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 213, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=213:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428d5378 on behalf of 5065
,V/DownloadManager( 5065): processing inserted download 214
V/LFT     ( 5065): isReadyToDownload mId, mStatus=214:190
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,E/UpdateRequestReceiver( 5305): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm(  964): GC_EXPLICIT freed 2367K, 48% free 30643K/57964K, paused 4ms+6ms, total 96ms
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428d74d0 on behalf of 5065
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/DownloadManager( 5065): DB Update : status 192
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
E/UpdateRequestReceiver( 5305): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 5305): Received malformed URL while handling Gservices.CHANGED_ACTION
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4292b0d0 on behalf of 5065
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42928aa8 on behalf of 5065
,I/DownloadManager( 5065): Download 214 starting
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 5065): processing updated download 213, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=213:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/ActivityManager(  964): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=5351 uid=10009 gids={50009, 3003}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1228): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429329a8 on behalf of 5065
,D/DownloadManager( 5065): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 5065): processing updated download 214, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=214:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42937010 on behalf of 5065
D/HyLog   ( 5351): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5351): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5351): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x43065b00: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1944): awaiting user notification for token
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/ActivityThread( 5065): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/CheckinRequestBuilder( 1944): Classify the device as Phone.
,I/DownloadManager( 5065): Ignoring Content-Length since Transfer-Encoding is also defined
,V/DownloadManager( 5065): Content-Disposition: null
V/DownloadManager( 5065): Content-Length: -1
V/DownloadManager( 5065): Content-Location: null
V/DownloadManager( 5065): Content-Type: text/plain
V/DownloadManager( 5065): ETag: null
V/DownloadManager( 5065): Transfer-Encoding: chunked
V/DownloadManager( 5065): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 5065): Min update size = 16384
,V/DownloadManager( 5065): getting filename from uri
,W/BaseRuntimeLoader( 5351): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5351): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/DownloadManager( 5065): in verifySpace, destination: 5, path: 10152015-sms-metadata.txt, length: 0
W/BaseRuntimeLoader( 5351): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5351): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/DownloadManager( 5065): keeping extension
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,V/DownloadManager( 5065): target file: /cache/10152015-sms-metadata.txt
D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  964): MasterInitialState.processMessage what=3
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42969840 on behalf of 5065
D/DownloadManager( 5065): DB Update : title 10152015-sms-metadata.txt
,D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 5065): DB Update : total_bytes -1
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/Search.GservicesUpdateTask( 2655): Updating Gservices keys
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4296c3f0 on behalf of 5065
,I/LGDrmService( 5065): _DRM_ServiceGet() : Bind lgdrm service
,V/DownloadManager( 5065): processing updated download 213, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=213:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4296f0f8 on behalf of 5065
,D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): transferData threadNum : -1
,V/DownloadManager( 5065): processing updated download 214, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=214:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 5065): DB Update : current_bytes 383
,D/DownloadManager( 5065): DB Update : total_bytes 383
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4297e5f8 on behalf of 5065
,I/CheckinTask( 1944): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 5065): notifyThroughDatabase after updateDB  id :  214, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 5065): notifyThroughDatabase start id : 214 name : /cache/10152015-sms-metadata.txt status : 200
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4299c4b0 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4299d748 on behalf of 5065
,D/DownloadManager( 5065): DB Update : numfailed 0
V/DownloadManager( 5065): processing updated download 213, status: 192
D/DownloadManager( 5065): DB Update : method 0
D/DownloadManager( 5065): DB Update : lastmod 1452523272697
D/DownloadManager( 5065): DB Update : mimetype text/plain
,D/DownloadManager( 5065): DB Update : _data /cache/10152015-sms-metadata.txt
D/DownloadManager( 5065): DB Update : status 200
V/LFT     ( 5065): isReadyToDownload mId, mStatus=213:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429a16d0 on behalf of 5065
I/CheckinService( 1944): Checking schedule, now: 1452523272709 next: 1453100668695
,I/CheckinService( 1944): active receiver: disabled
,V/DownloadManager( 5065): processing updated download 214, status: 192
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=214:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429ac558 on behalf of 5065
D/DownloadManager( 5065): checkStatusUpdate current status 192 is changed to 200
,D/DownloadManager( 5065): checkStatusUpdate return true mID : mStatus = 214 : 200 => 200
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429b3608 on behalf of 5065
,I/DownloadManager( 5065): Download 214 finished with status SUCCESS
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
V/DownloadManager( 5065): processing updated download 213, status: 192
W/Search.LoginHelper( 2655): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=213:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429be130 on behalf of 5065
,W/Search.LoginHelper( 2655): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
,I/DownloadManager( 5065): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 5065): Content-Disposition: null
,V/DownloadManager( 5065): Content-Length: -1
V/DownloadManager( 5065): Content-Location: null
V/DownloadManager( 5065): Content-Type: text/plain
V/DownloadManager( 5065): ETag: null
V/DownloadManager( 5065): Transfer-Encoding: chunked
V/DownloadManager( 5065): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 5065): Min update size = 16384
V/DownloadManager( 5065): getting filename from uri
I/DownloadManager( 5065): in verifySpace, destination: 5, path: 08202014-metadata.txt, length: 0
V/DownloadManager( 5065): keeping extension
,V/DownloadManager( 5065): target file: /cache/08202014-metadata.txt
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429c2230 on behalf of 5065
,I/SystemUpdateService( 1944): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/DownloadManager( 5065): DB Update : title 08202014-metadata.txt
D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 5065): DB Update : total_bytes -1
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/SystemUpdateService( 1944): onCreate
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429c4cf0 on behalf of 5065
,I/CheckinService( 1944): Checking schedule, now: 1452523272764 next: 1453100668695
I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/CheckinService( 1944): active receiver: disabled
,D/SystemUpdateService( 1944): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/DownloadManager( 5065): processing updated download 213, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=213:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429c6f50 on behalf of 5065
,D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): DB Update : current_bytes 384
,D/DownloadManager( 5065): DB Update : total_bytes 384
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429d3b60 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 213, status: 192
V/LFT     ( 5065): notifyThroughDatabase after updateDB  id :  213, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 5065): notifyThroughDatabase start id : 213 name : /cache/08202014-metadata.txt status : 200
,D/SystemEventReceiver( 1944): Received GSERVICES_CHANGED broadcast
V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,I/OcrUtils( 1944): Updating ocr activity enabled=false
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=213:192
,I/ActivityManager(  964): Killing 4863:com.google.android.apps.docs/u0a73 (adj 15): empty #17
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429d6158 on behalf of 5065
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429d6d78 on behalf of 5065
,D/DownloadManager( 5065): DB Update : numfailed 0
D/DownloadManager( 5065): DB Update : method 0
D/DownloadManager( 5065): DB Update : lastmod 1452523272791
D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 5065): DB Update : status 200
I/SystemUpdateService( 1944): cancelUpdate (empty URL)
,I/SystemUpdateService( 1944): active receiver: disabled
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1}
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429da638 on behalf of 5065
I/DownloadManager( 5065): Download 213 finished with status SUCCESS
I/GCoreUlr( 1427): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,V/DownloadManager( 5065): DownloadService onDestroy
,D/GCM     ( 1542): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/SystemUpdateService( 1944): onDestroy
I/ActivityManager(  964): Killing 4536:com.android.vending/u0a50 (adj 15): empty #17
,I/GCoreUlr( 1427): DispatchingService.onCreate()
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1}
,I/GCoreUlr( 1427): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/dalvikvm( 1944): GC_EXPLICIT freed 1433K, 22% free 19586K/24832K, paused 2ms+5ms, total 42ms
,D/dalvikvm( 1542): GC_EXPLICIT freed 493K, 28% free 17902K/24832K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 1542): null clazz in OP_INSTANCE_OF, single-stepping
,I/GCoreUlr( 1427): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/dalvikvm( 1427): GC_EXPLICIT freed 742K, 28% free 18045K/24832K, paused 1ms+4ms, total 29ms
,I/GCoreUlr( 1427): Unbound from all location providers
,E/DataBuffer( 1427): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@429c32b8)
,I/GCoreUlr( 1427): DispatchingService.onDestroy()
,I/GCoreUlr( 1427): Unbound from all location providers
,D/GCM     ( 1542): Connected
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1542): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/LicenseContentProvider( 4492): start selecting data
,D/SIMObserver( 4492): simInfo1
,I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4470): begin check event
,I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4470): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4470): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4470): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4470): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4470): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 5065): DownloadService onCreate
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4841): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4841): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4841): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429e00b0 on behalf of 5065
,I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
,I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/10152015-sms-metadata.txt
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429e1df0 on behalf of 5065
,I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4635): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 5086): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5086): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5065): processing inserted download 213
,V/DownloadManager( 5065): processing inserted download 214
,I/DownloadManager( 5065): in trimDatabase
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,W/Settings( 4841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429e6260 on behalf of 5065
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5151): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 5065): DownloadService onDestroy
,I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 5165): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5165): CONNECT : WIFI_CONNECT
,W/ContextImpl( 5151): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm(  964): GC_EXPLICIT freed 1278K, 48% free 30614K/57964K, paused 3ms+8ms, total 103ms
,I/CheckinService( 1944): Checking schedule, now: 1452523273279 next: 1453100668695
,I/CheckinService( 1944): active receiver: disabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 1542): GC_EXPLICIT freed 276K, 29% free 17868K/24832K, paused 2ms+3ms, total 25ms
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/LicenseContentProvider( 4492): start selecting data
,D/SIMObserver( 4492): simInfo1
,I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4470): begin check event
,I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5065): DownloadService onCreate
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429ea5d8 on behalf of 5065
D/EAS     ( 4841): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4841): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
,I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/10152015-sms-metadata.txt
I/DownloadManager( 5065): in trimDatabase
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429ec748 on behalf of 5065
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429ee518 on behalf of 5065
,I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4635): networkInfo.isConnected() = true
D/PhoneState( 4635): setPdpRejectCasuse : false
,W/Settings( 4841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5065): processing inserted download 213
,D/MobileConnectivityChangeReceiver( 5086): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5086): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5065): processing inserted download 214
,V/DownloadManager( 5065): DownloadService onDestroy
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5151): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 5165): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5165): CONNECT : WIFI_CONNECT
W/ContextImpl( 5151): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinService( 1944): Checking schedule, now: 1452523273398 next: 1453100668695
,I/CheckinService( 1944): active receiver: disabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 214; sort is lastmod DESC.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429f4cc8 on behalf of 5305
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 214; sort is lastmod DESC.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429f8460 on behalf of 5305
,W/ContextImpl( 5305): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,V/DownloadManager( 5065): initiating download with UID 10003
,V/DownloadManager( 5065): DownloadService onCreate
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429fdae8 on behalf of 5065
I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/10152015-sms-metadata.txt
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 5065): in trimDatabase
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a011b8 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a00490 on behalf of 5065
,V/DownloadManager( 5065): processing inserted download 213
,V/DownloadManager( 5065): processing inserted download 214
,V/DownloadManager( 5065): processing inserted download 215
V/LFT     ( 5065): isReadyToDownload mId, mStatus=215:190
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a06018 on behalf of 5065
,D/DownloadManager( 5065): DB Update : status 192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 213; sort is lastmod DESC.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a0a4f8 on behalf of 5305
,D/GCM     ( 1542): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 213; sort is lastmod DESC.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a10338 on behalf of 5305
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a0d398 on behalf of 5065
,W/ContextImpl( 5305): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a11148 on behalf of 5065
V/DownloadManager( 5065): processing updated download 215, status: 192
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=215:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a13638 on behalf of 5065
,V/DownloadManager( 5065): initiating download with UID 10003
,I/DownloadManager( 5065): Download 215 starting
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/DownloadManager( 5065): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a1c310 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 215, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=215:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a1e6c8 on behalf of 5065
,V/DownloadManager( 5065): processing inserted download 216
V/LFT     ( 5065): isReadyToDownload mId, mStatus=216:190
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a20818 on behalf of 5065
,D/DownloadManager( 5065): DB Update : status 192
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a29978 on behalf of 5065
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a2b758 on behalf of 5065
I/DownloadManager( 5065): Download 216 starting
I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
D/DownloadManager( 5065): fileSize : -1state.mContinuingDownload :false
V/DownloadManager( 5065): processing updated download 215, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=215:192
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a31670 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 216, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=216:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/GCM     ( 1542): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a33338 on behalf of 5065
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/GCM     ( 1542): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/DownloadManager( 5065): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 5065): Content-Disposition: null
V/DownloadManager( 5065): Content-Length: -1
V/DownloadManager( 5065): Content-Location: null
V/DownloadManager( 5065): Content-Type: text/plain
V/DownloadManager( 5065): ETag: null
V/DownloadManager( 5065): Transfer-Encoding: chunked
,V/DownloadManager( 5065): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 5065): Min update size = 16384
V/DownloadManager( 5065): getting filename from uri
I/DownloadManager( 5065): in verifySpace, destination: 5, path: 10152015-sms-blacklist.txt, length: 0
V/DownloadManager( 5065): keeping extension
,V/DownloadManager( 5065): target file: /cache/10152015-sms-blacklist.txt
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1228): Disconnected process message: 10
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a40400 on behalf of 5065
,D/DownloadManager( 5065): DB Update : title 10152015-sms-blacklist.txt
D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 5065): DB Update : total_bytes -1
D/WifiController(  964): battery changed pluggedType: 2
,D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/LGDRM   (  276): [DRM] Part_DetectType() : Buffer contains XML Prologue
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a43f98 on behalf of 5065
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): processing updated download 215, status: 192
D/DownloadManager( 5065): DB Update : current_bytes 13383
V/LFT     ( 5065): isReadyToDownload mId, mStatus=215:192
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5065): DB Update : total_bytes 13383
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a50a08 on behalf of 5065
V/LFT     ( 5065): notifyThroughDatabase after updateDB  id :  215, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 5065): notifyThroughDatabase start id : 215 name : /cache/10152015-sms-blacklist.txt status : 200
V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a52c88 on behalf of 5065
V/DownloadManager( 5065): processing updated download 216, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=216:192
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5065): DB Update : numfailed 0
D/DownloadManager( 5065): DB Update : method 0
D/DownloadManager( 5065): DB Update : lastmod 1452523273601
D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/10152015-sms-blacklist.txt
D/DownloadManager( 5065): DB Update : status 200
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a547a0 on behalf of 5065
,I/DownloadManager( 5065): Download 215 finished with status SUCCESS
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a73148 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 216, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=216:192
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 215; sort is lastmod DESC.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a89968 on behalf of 5305
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a89f40 on behalf of 5065
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1492): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 215; sort is lastmod DESC.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a97868 on behalf of 5305
,W/ContextImpl( 5305): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 5305): Update downloaded, starting installation
,I/UpdateFetcherService( 5305): Started installation
,D/DownloadManager( 5065): DB Update : deleted 1
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): DownloadService onStartCommand
,E/[LGHome]NumberBadge( 1492): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42aa8918 on behalf of 5065
,D/DownloadManager( 5065): deleteFileIfExists() deleting /cache/10152015-sms-metadata.txt
,D/DownloadManager( 5065): deleteFileIfExists() deleting /cache/10152015-sms-blacklist.txt
I/DownloadManager( 5065): Ignoring Content-Length since Transfer-Encoding is also defined
,V/DownloadManager( 5065): Content-Disposition: null
V/DownloadManager( 5065): Content-Length: -1
V/DownloadManager( 5065): Content-Location: null
V/DownloadManager( 5065): Content-Type: text/plain
V/DownloadManager( 5065): ETag: null
V/DownloadManager( 5065): Transfer-Encoding: chunked
,V/DownloadManager( 5065): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 5065): Min update size = 16384
V/DownloadManager( 5065): getting filename from uri
I/DownloadManager( 5065): in verifySpace, destination: 5, path: 08202014-pins.txt, length: 0
V/DownloadManager( 5065): keeping extension
,V/DownloadManager( 5065): target file: /cache/08202014-pins.txt
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42ab8900 on behalf of 5065
,D/DownloadManager( 5065): DB Update : title 08202014-pins.txt
V/DownloadManager( 5065): processing updated download 216, status: 192
,D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/08202014-pins.txt
V/LFT     ( 5065): isReadyToDownload mId, mStatus=216:192
,D/DownloadManager( 5065): DB Update : total_bytes -1
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42aba8d8 on behalf of 5065
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): transferData threadNum : -1
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42ac69c0 on behalf of 5065
,D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): DB Update : current_bytes 32768
V/DownloadManager( 5065): processing updated download 216, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=216:192
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42acafc0 on behalf of 5065
,V/DownloadManager( 5065): downloaded 32768 for https://www.gstatic.com/android/config_update/08202014-pins.txt
D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42acdfc0 on behalf of 5065
,D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): processing updated download 216, status: 192
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=216:192
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42ad0c78 on behalf of 5065
D/DownloadManager( 5065): DB Update : current_bytes 39938
D/DownloadManager( 5065): DB Update : total_bytes 39938
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 5065): notifyThroughDatabase after updateDB  id :  216, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 5065): notifyThroughDatabase start id : 216 name : /cache/08202014-pins.txt status : 200
V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42ad3a58 on behalf of 5065
V/DownloadManager( 5065): processing updated download 216, status: 192
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42ad52a8 on behalf of 5065
V/LFT     ( 5065): isReadyToDownload mId, mStatus=216:192
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5065): DB Update : numfailed 0
D/DownloadManager( 5065): DB Update : method 0
D/DownloadManager( 5065): DB Update : lastmod 1452523273699
D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/08202014-pins.txt
D/DownloadManager( 5065): DB Update : status 200
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42ad74d0 on behalf of 5065
D/DownloadManager( 5065): checkStatusUpdate current status 192 is changed to 200
D/DownloadManager( 5065): checkStatusUpdate return true mID : mStatus = 216 : 200 => 200
I/DownloadManager( 5065): Download 216 finished with status SUCCESS
,V/DownloadManager( 5065): DownloadService onDestroy
V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 216; sort is lastmod DESC.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42adc778 on behalf of 5305
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 216; sort is lastmod DESC.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42adfe78 on behalf of 5305
W/ContextImpl( 5305): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
I/UpdateFetcherService( 5305): Update downloaded, starting installation
I/UpdateFetcherService( 5305): Started installation
D/DownloadManager( 5065): DB Update : deleted 1
,V/DownloadManager( 5065): DownloadService onCreate
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42ae3f00 on behalf of 5065
I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
,V/DownloadManager( 5065): DownloadService onStartCommand
I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/08202014-pins.txt
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 5065): in trimDatabase
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42ae6960 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42ae74a0 on behalf of 5065
V/DownloadManager( 5065): processing inserted download 213
,D/DownloadManager( 5065): deleteFileIfExists() deleting /cache/08202014-metadata.txt
,V/DownloadManager( 5065): processing inserted download 216
,D/DownloadManager( 5065): deleteFileIfExists() deleting /cache/08202014-pins.txt
,V/DownloadManager( 5065): DownloadService onDestroy
I/ConfigUpdateInstallReceiver(  964): Not installing, new version is <= current version
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-12ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
,D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/LicenseContentProvider( 4492): start selecting data
,D/SIMObserver( 4492): simInfo1
,I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4470): begin check event
,I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity, noConnectivity : false, but skip! 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 5065): DownloadService onCreate
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/EAS     ( 4841): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42af14d8 on behalf of 5065
D/EAS     ( 4841): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 5065): in trimDatabase
V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42af26d8 on behalf of 5065
V/DownloadManager( 5065): DownloadService onStartCommand
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4635): networkInfo.isConnected() = true
D/PhoneState( 4635): setPdpRejectCasuse : false
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42af4758 on behalf of 5065
W/Settings( 4841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 5086): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5086): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 5065): DownloadService onDestroy
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
D/LGDMSGCM( 5151): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5165): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5165): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,W/ContextImpl( 5151): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1228): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1228): Disconnected process message: 10
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  964): battery changed pluggedType: 2
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/ActivityManager(  964): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5506 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5506): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5506): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5506): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/dalvikvm( 5506): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5506): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5506): VFY: replacing opcode 0x6e at 0x000b
E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5506): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/GAV2    ( 5178): Thread[GAThread,5,main]: No campaign data found.
I/dalvikvm( 5506): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5506): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5506): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5506): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5506): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5506): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5506): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5506): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5506): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5506): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5506): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5506): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5506): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5506): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5506): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5506): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5506): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5506): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5506): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42af95f0 on behalf of 5506
I/dalvikvm( 5506): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5506): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5506): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5506): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5506): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5506): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5506): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5506): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5506): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5506): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm( 5506): Total arena pages for JIT: 11
,I/dalvikvm( 5506): Total arena pages for JIT: 12
I/dalvikvm( 5506): Total arena pages for JIT: 13
,I/dalvikvm( 5506): Total arena pages for JIT: 14
,D/Finsky  ( 5506): [486] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5506): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  964): Killing 4979:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Killing 5013:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2206): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2206): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5506): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5506): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5506): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5506): VFY: replacing opcode 0x62 at 0x0037
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/dalvikvm(  964): GC_EXPLICIT freed 1154K, 48% free 30580K/57964K, paused 4ms+11ms, total 184ms
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5506): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5506): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1160): usb Uevent not necessary.
,W/Finsky  ( 5506): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5506): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1228): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/Finsky  ( 5506): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/Finsky  ( 5506): [1] DailyHygiene.reschedule: Scheduling new run in 260 minutes (failures=4)
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1228): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  964): battery changed pluggedType: 2
,I/ActivityManager(  964): Killing 4929:com.test.thalitest/u0a304 (adj 15): empty #17
D/DeviceConnectionService( 1427): client connected with version: 7571000
,I/WindowState(  964): WIN DEATH: Window{43dc0e38 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  964): Client connection lost with reason: 4
,I/[LGHome]EVENT( 1492): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{44f22cf8 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1}
,W/Binder  ( 1312): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1312): java.lang.NullPointerException
W/Binder  ( 1312): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1312): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1312): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1312): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  964): IME STATUS OFF
W/InputMethodManagerService(  964): Got RemoteException sending setActive(false) notification to pid 4929 uid 10304
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2206): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2206): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X,
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/PowerManagerService(  964): Going to sleep due to screen timeout...
D/KnockOnPowerController(  964): [updateScreenState] screen on = false
D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  964): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9218 usec
D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  964): hal_acquire_resources
,I/qcom_sensors_hal(  964): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  964): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  964): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  964): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.472855 Y: -0.411926 Z: 9.802856 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.472855 .y:-0.411926 .z:9.802856
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  964): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  964): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  964): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  964): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.468430 Y: -0.400146 Z: 9.810440 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.468430 .y:-0.400146 .z:9.810440
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/Sensors (  511): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  964): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  964): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  964): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  964): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  964): proximitySensorChanged  positive = true
I/KnockOnPowerController(  964): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.464539 Y: -0.388458 Z: 9.781708 
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.467865 Y: -0.426178 Z: 9.782806 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.464539 .y:-0.388458 .z:9.781708
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5604 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/SlideAside( 3810): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
I/SlideAside( 3810): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 2ms+1ms, total 35ms
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.463486 Y: -0.408783 Z: 9.797150 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463486 .y:-0.408783 .z:9.797150
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
D/administrator(  964): Handling package changes for user 0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5604): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5604): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5604): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.444153 Y: -0.411270 Z: 9.810349 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444153 .y:-0.411270 .z:9.810349
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.449600 Y: -0.401917 Z: 9.815506 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449600 .y:-0.401917 .z:9.815506
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5604): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5604): MmsConfig.loadMmsSettings
I/Babel   ( 5604): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5604): MmsConfig.loadFromDatabase
I/MediaCodecList( 5604): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5604): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5604): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5604): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1160): usb Uevent not necessary.
,W/BaseRuntimeLoader( 5604): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5604): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5604): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5604): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5604): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5604): MmsConfig.loadFromResources
,E/Babel   ( 5604): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5604): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5604): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/HeadsetStateMachine( 1228): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,V/KeyguardServiceDelegate(  964): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44879168)
D/KeyguardViewMediator( 1144): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1144): notifyScreenOnLocked
D/KeyguardViewMediator( 1144): handleNotifyScreenOn
D/KeyguardViewManager( 1144): onScreenTurnedOn()
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
V/KeyguardServiceDelegate(  964): **** SHOWN CALLED ****
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,V/LGRssiData( 5604): [loadRssi] File not exist 
V/LGRssiData( 5604): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5604): [loadFeatureFromXml] *** start feature loading from xml
D/WifiController(  964): battery changed pluggedType: 2
I/WindowManager(  964): No lock screen! windowToken=null
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  964): handleScreenStateChanged: true
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2206): wlan0: Control interface command 'SIGNAL_POLL'
V/TelephonyAutoProfiling( 5604): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/WifiServiceExtension(  964): sendKtScanInterval  mRtspPlay : false
V/TelephonyAutoProfiling( 5604): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5604): [getValue] FEATURE key : vzw_roaming_state, value : null
D/WifiOffDelayIfNotUsed(  964): stopMonitoring
E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 2206): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131127
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=132097
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  964): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2206): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2206): initialize kt scan interval and do scan state=9
E/SlideAside( 3810): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
D/WifiStateMachine(  964): handleMessage: X
,I/SlideAside( 3810): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/qdlights( 1160): set_light_notifications: 0,0,0,0,3
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb84a4450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.450653 Y: -0.407318 Z: 9.797821 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450653 .y:-0.407318 .z:9.797821
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
I/EmotionalLed( 1160): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1160): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43373408 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
D/EmotionalLed( 1160): enqueuing start. mLedList.size()=2
I/EmotionalLed( 1160): updateLightsLocked() start. mLedList.size=3
D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
D/AppUp4:Utils( 4470): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4470): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4470): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,E/CliptrayService( 1160): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/EmotionalLed( 1160): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1160): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/LicenseContentProvider( 4492): start selecting data
,D/SIMObserver( 4492): simInfo1
I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
V/GmsNetworkLocationProvi( 1427): DISABLE
,D/AppUp4:CustModeStarterReceiver( 4470): begin check event
D/AppUp4:Utils( 4470): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4470): Event For Nothing, skip.
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5658 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
I/ActivityManager(  964): Killing 5351:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/LocationProviderProxy(  964): applying state to connected service
,D/LocationProviderProxy(  964): applying state to connected service
D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1}
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1160): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1160): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1160): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1160): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1160): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1160): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1160): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1160): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1160): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1160): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1160): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1160): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1160): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1160): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1160): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1160): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1160): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 147, B = 147
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  964): Excessive delay in blankDisplay() while turning screen off: 420ms
,D/qdlights( 1160): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 141, B = 141
,D/HyLog   ( 5658): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5658): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5658): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1160): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1160): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1160): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 123, B = 123
D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523280497, nextTick: 39534, mDrawingTime: 1
D/qdlights( 1160): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1160): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1160): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 105, B = 105
,I/SystemConfig( 5658): BUILD Country: EU
,I/SystemConfig( 5658): BUILD Operator: OPEN
,D/qdlights( 1160): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 99, B = 99
I/ActivityManager(  964): Killing 5305:com.google.android.configupdater/u0a3 (adj 15): empty #17
,D/qdlights( 1160): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 93, B = 93
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523280547, nextTick: 39485, mDrawingTime: 0
,D/qdlights( 1160): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1160): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 81, B = 81
I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5675 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/SystemConfig( 5658): systemFeature RCS result false
,D/SystemConfig( 5658): refreshRcsSupport() :false
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1}
D/qdlights( 1160): set_light_notifications: 2,ff004b4b,10,0,2
D/qdlights( 1160): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1160): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 69, B = 69
,D/WeatherService( 1812): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:41:20
,D/WeatherService( 1812): 2 : ACTION screen on
,D/WeatherService( 1812): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1812): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:41:20
D/qdlights( 1160): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 63, B = 63
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
,E/Parcel  (  527): Reading a NULL string not supported here.
D/qdlights( 1160): set_light_notifications: 2,ff003939,10,0,2
D/qdlights( 1160): [Current] = 255, R = 0, G = 57, B = 57
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.456207 Y: -0.402451 Z: 9.816498 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456207 .y:-0.402451 .z:9.816498
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/GsmSST  ( 1452): Emergency Service
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1160): set_light_notifications: 2,ff003333,10,0,2
D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
,D/qdlights( 1160): [Current] = 255, R = 0, G = 51, B = 51
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
D/HyLog   ( 5675): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5675): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5675): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/qdlights( 1160): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 45, B = 45
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1144): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1144): notifyScreenOffLocked
,I/[LGHome]EVENT( 1492): [Launcher.java:894:onPause()]onPause
,V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1}
D/qdlights( 1160): set_light_notifications: 2,ff002727,10,0,2
D/qdlights( 1160): [Current] = 255, R = 0, G = 39, B = 39
,I/LGImmersionVibrator(  964): Vibrator off
D/qcom_sensors_hal(  964): hal_acquire_resources
D/qcom_sensors_hal(  964): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  964): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  964): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  964): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1160): set_light_notifications: 2,ff002121,10,0,2
D/qdlights( 1160): [Current] = 255, R = 0, G = 33, B = 33
D/KeyguardViewMediator( 1144): setting alarm to turn off keyguard, seq = 2, timeout = 5000
I/[LGHome]EVENT( 1492): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  964): handleScreenStateChanged: false
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=off
D/qdlights( 1160): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 27, B = 27
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
,V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/KeyguardViewMediator( 1144): handleNotifyScreenOff
,D/KeyguardViewManager( 1144): onScreenTurnedOff()
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1160): usb Uevent not necessary.
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{432466d0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,I/EmotionalLed( 1160): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): handleMessage: X
D/qdlights( 1160): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 21, B = 21
,E/CliptrayService( 1160): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=2
D/VolumeVibrator( 1160): clear
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[LGHome]EVENT( 1492): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1160): set_light_notifications: 2,ff000f0f,10,0,2
D/qdlights( 1160): [Current] = 255, R = 0, G = 15, B = 15
D/WeatherService( 1812): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:41:20
D/WeatherService( 1812): 2 : ACTION screen off
D/WeatherService( 1812): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1812): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:41:20
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/qdlights( 1160): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1160): set_light_notifications: 0,0,0,0,3
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/qdlights( 1160): set_light_notifications: 1,ff00ff00,500,2000,1
D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1452): Emergency Service
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
I/EmotionalLed( 1160): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
D/NfcService( 1477): NFC-C OFF
V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_OFF
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1464): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,I/ActivityManager(  964): Killing 4841:com.lge.email/u0a24 (adj 15): empty #17
I/IcingCorporaProvider( 2655): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/WeatherAncestor( 1812): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:41:20
D/UpdateThreadPoolManager( 1812): 2 : This is isUpdating : false
,D/WeatherAncestor( 1812): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:41:20
,D/WeatherService( 1812): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1812): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1812): 2 : shouldTimeTickRegistered : false
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/dalvikvm( 1944): GC_EXPLICIT freed 522K, 22% free 19611K/24832K, paused 4ms+8ms, total 63ms
,D/PackageBroadcastService( 1944): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1944): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  964): Delaying start of: ServiceRecord{44e17f90 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1944): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2655): UpdateCorporaTask done [took 391 ms] updated apps [took 390 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  511): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,I/GAV4    ( 5604): Thread[GAThread,5,main]: No campaign data found.
,D/KeyguardViewMediator( 1144): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1144): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/KeyguardViewMediator( 1144): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1144): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  964): GC_EXPLICIT freed 1857K, 47% free 30822K/57964K, paused 5ms+15ms, total 184ms
,I/VacuumService( 1542): Vacuum at: now=1452523291860 tag=VacuumService
,I/GoogleURLConnFactory( 1542): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1542): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1542): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1542): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1542): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1542): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/Finsky  ( 5506): [486] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5506): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1542): No account for auth token provided
,W/Uploader( 1542): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1542): No account for auth token provided
,W/Uploader( 1542):  no longer exists, so no auth token.
,W/Uploader( 1542): No account for auth token provided
,D/dalvikvm( 1542): GC_CONCURRENT freed 1721K, 28% free 18080K/24832K, paused 29ms+11ms, total 108ms
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523299036592799; DSPS: 5274003; Offset: 1452523138086794216
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1228): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523319037468781; DSPS: 5929391; Offset: 1452523138086815705
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523320031, nextTick: 59997, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523320056, nextTick: 59977, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523339038347767; DSPS: 6584780; Offset: 1452523138086809682
,D/wpa_supplicant( 2206): wlan0: BSS: Remove id 4 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:38:27:cc]
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523359038796618; DSPS: 7240155; Offset: 1452523138086800769
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523379039241745; DSPS: 7895529; Offset: 1452523138086818650
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523380040, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523380055, nextTick: 59978, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  964): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1228): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523399039698997; DSPS: 8550904; Offset: 1452523138086818138
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523419040141728; DSPS: 9206279; Offset: 1452523138086803105
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523439040581444; DSPS: 9861653; Offset: 1452523138086815575
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523440029, nextTick: 59979, mDrawingTime: 11
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523440058, nextTick: 59975, mDrawingTime: 0
,D/wpa_supplicant( 2206): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 8 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 9 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 10 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 3 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 5 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 6 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 7 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 06:7c:34:12:7f:81],
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 38:f8:89:11:e9:11]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 44:e9:dd:10:c0:ab]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 44:e9:dd:10:c0:ad]
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523459041034826; DSPS: 10517028; Offset: 1452523138086811194
,D/dalvikvm( 2640): GC_CONCURRENT freed 7715K, 32% free 16891K/24832K, paused 3ms+1ms, total 49ms
,D/dalvikvm( 2640): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/ActivityManager(  964): Killing 5086:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523479042668761; DSPS: 11172442; Offset: 1452523138086797179
,I/LocationManagerService(  964): remove 434d92a0
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2640): GC_CONCURRENT freed 1834K, 32% free 17057K/24832K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2640): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2640): GC_CONCURRENT freed 1751K, 31% free 17268K/24832K, paused 3ms+1ms, total 25ms
,D/dalvikvm( 2640): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/Mlt MonitorService( 2640): parseLastkmsg to dump
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523499043121169; DSPS: 11827816; Offset: 1452523138086822341
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523500022, nextTick: 59992, mDrawingTime: 10
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523500056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523519043567264; DSPS: 12483191; Offset: 1452523138086810673
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523539044468343; DSPS: 13138581; Offset: 1452523138086796224
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523559045454691; DSPS: 13793973; Offset: 1452523138086806010
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523560032, nextTick: 59983, mDrawingTime: 9
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523560057, nextTick: 59975, mDrawingTime: 0
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x430abc28: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1542): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1542): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1542): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1542): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1542): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1542): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1542): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1542): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 5506): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5506): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5506): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5506): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5506): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5506): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5506): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5506): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 5506): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5506): isDataSchedulerEnabled():false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523579046344896; DSPS: 14449362; Offset: 1452523138086811205
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523599046794670; DSPS: 15104736; Offset: 1452523138086833733
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523619047236170; DSPS: 15760111; Offset: 1452523138086817469
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523620044, nextTick: 59970, mDrawingTime: 9
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523620054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523639047689421; DSPS: 16415486; Offset: 1452523138086812957
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523659048135315; DSPS: 17070861; Offset: 1452523138086801087
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523679048578336; DSPS: 17726235; Offset: 1452523138086816862
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523680030, nextTick: 59991, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523680055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523699049022544; DSPS: 18381610; Offset: 1452523138086803306
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523719049469998; DSPS: 19036984; Offset: 1452523138086823514
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523739049917452; DSPS: 19692359; Offset: 1452523138086813204
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523740039, nextTick: 59970, mDrawingTime: 10
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523740053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523759050828499; DSPS: 20347749; Offset: 1452523138086808724
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523779056079781; DSPS: 21003281; Offset: 1452523138086810983
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523799056944618; DSPS: 21658669; Offset: 1452523138086821327
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523800034, nextTick: 59984, mDrawingTime: 8
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523800042, nextTick: 59990, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1228): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523819057402989; DSPS: 22314044; Offset: 1452523138086821935
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523839057884039; DSPS: 22969420; Offset: 1452523138086814704
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523859058319803; DSPS: 23624794; Offset: 1452523138086823221
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523860040, nextTick: 59976, mDrawingTime: 8
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523860050, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523879059709890; DSPS: 24280200; Offset: 1452523138086809500
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523899060180138; DSPS: 24935575; Offset: 1452523138086821984
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523919060626325; DSPS: 25590950; Offset: 1452523138086810408
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523920046, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523920049, nextTick: 59982, mDrawingTime: 1,
,D/wpa_supplicant( 2206): nl80211: Event message available
D/wpa_supplicant( 2206): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2206): nl80211: Disconnect event
D/wpa_supplicant( 2206): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2206): wlan0: Deauthentication notification
D/wpa_supplicant( 2206): wlan0:  * reason 0
D/wpa_supplicant( 2206): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2206): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2206): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2206): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2206): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2206): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2206): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2206): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
,D/WifiStateMachine(  964): handleMessage: E msg.what=147460
,D/WifiStateMachine(  964): processMsg: ConnectedState,
,D/WifiStateMachine(  964): processMsg: L2ConnectedState,
D/WifiStateMachine(  964): processMsg: ConnectModeState,
,D/WifiStateMachine(  964): Network connection lost,
,D/WifiStateMachine(  964): Stopping DHCP and clearing IP,
,D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  964): doBoolean: SET ps 1,
,D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb846fd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2206):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2206): wlan0: State: COMPLETED -> DISCONNECTED,
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT),
D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2206): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2206): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=0,
,D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2206): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2206): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2206): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  964): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/wpa_supplicant( 2206): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2206): wlan0: nl80211: scan request
,D/wpa_supplicant( 2206): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiNative-wlan0(  964):    returned true
D/wpa_supplicant( 2206): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2206): nl80211: Event message available
D/wpa_supplicant( 2206): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2206): wlan0: nl80211: Scan trigger
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/DhcpStateMachine(  964): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  964): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1160): handleWifiStateChangedEvent: 0
,D/WifiHS20(  964): hidePasspointNotification off =false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
D/QCNEA   (  527): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  527): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  527): |CAC| updateNetCfgInfo
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC|                   Netconfig               
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  527): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  527): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  527): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  527): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  527): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  527): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| Received bssid= 
D/QCNEA   (  527): |CAC| net type = 3
V/QCNEA   (  527): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  527): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  527): |CAC| 	ssid           =NG700
V/QCNEA   (  527): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  527): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  527): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  527): |CAC| dispatchNetCfg: updating:0xb81708dc
D/QCNEA   (  527): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  527): Reading a NULL string not supported here.
,E/Parcel  (  527): Reading a NULL string not supported here.
,D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
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
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6343 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 6343): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6343): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6343): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 6343): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6343): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6343): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/NetworkManagementService(  964): route cmd failed: 
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
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x63788048 clazz=0xb4800001 iface=wlan0 mask=0x3
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
,V/NativeCrypto( 1542): Read error: ssl=0x62443c48: I/O error during system call, Connection timed out
,V/NativeCrypto( 1542): SSL shutdown failed: ssl=0x62443c48: I/O error during system call, Broken pipe
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6377 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  964): Killing 5101:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/HyLog   ( 6377): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6377): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6377): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/DhcpStateMachine(  964): StoppedState
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 6377): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/QRemote ( 6377): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 6377): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6377): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6377): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6377): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6377): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6377): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6377): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 5138:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
D/wpa_supplicant( 2206): nl80211: Event message available
D/wpa_supplicant( 2206): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2206): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2206): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2206): nl80211: Received scan results (13 BSSes)
D/wpa_supplicant( 2206): nl80211: Survey data missing
D/wpa_supplicant( 2206): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 11 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 12 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
,D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 2206): wlan0: BSS: Add new id 13 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos',
,D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2206): wlan0: BSS: Add new id 14 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free',
,D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2206): wlan0: BSS: Add new id 15 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
,D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 2206): wlan0: BSS: Add new id 16 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 17 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 18 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series',
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2206): wlan0: BSS: Add new id 19 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear',
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 20 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 2206): wlan0: BSS: Add new id 21 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB',
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 22 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): BSS: last_scan_res_used=13/32 last_scan_full=0,
,D/wpa_supplicant( 2206): wlan0: New scan results available
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311),
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311),
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 2206): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
,D/wpa_supplicant( 2206): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2206): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2206): WPS: AP a0:c5:62:7a:49:97 type 0 added,
D/wpa_supplicant( 2206): WPS: AP 44:e9:dd:10:c0:ac type 0 added,
,D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2206): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2206): WPS: AP 44:e9:dd:10:c0:ab type 0 added,
D/wpa_supplicant( 2206): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 2206): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
,D/wpa_supplicant( 2206): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[4] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 2206): WPS: AP[6] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 2206): WPS: AP[7] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2206): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-47 wps
D/wpa_supplicant( 2206): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2206): wlan0: 2: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-77 wps
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
,D/wpa_supplicant( 2206): wlan0: 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-80,
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-80
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 5: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-86 wps
,D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-86,
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 7: 44:e9:dd:10:c0:ac ssid='FunBox2-C0AB' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-91 wps
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2206): wlan0: 8: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-89 wps
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2206): wlan0: 9: 00:26:f2:18:08:c8 ssid='m.m.netgear' wpa_ie_len=24 rsn_ie_len=0 caps=0x411 level=-89
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 10: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-89 wps,
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 11: 44:e9:dd:10:c0:ab ssid='FunBox2-C0AB' wpa_ie_len=26 rsn_ie_len=24 caps=0x511 level=-89 wps,
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 12: 44:e9:dd:10:c0:ad ssid='Darmowe_Orange_WiFi' wpa_ie_len=0 rsn_ie_len=0 caps=0x501 level=-86
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2206): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2206): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear),
D/wpa_supplicant( 2206): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2206): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2206): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-47 wps
,D/wpa_supplicant( 2206): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2206): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2206): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
,D/wpa_supplicant( 2206): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84715a8  current_ssid=0x0
D/wpa_supplicant( 2206): scard is not null..,
D/wpa_supplicant( 2206): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30,
,D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
,D/wpa_supplicant( 2206): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2206): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 2206): wlan0: Cancelling scan request
,D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2206): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2206): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2206): RSN: PMKSA cache search - network_ctx=0xb84715a8 try_opportunistic=0
,D/wpa_supplicant( 2206): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2206): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2206): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2206): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2206): wlan0: WPA: clearing AP WPA IE,
D/wpa_supplicant( 2206): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2206): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2206): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2206): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2206): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2206): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2206): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
,D/wpa_supplicant( 2206): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2206): wlan0: State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2206): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0),
D/wpa_supplicant( 2206): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 2206): nl80211: Unsubscribe mgmt frames handle 0xb8470590 (mode change),
D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false,
D/wpa_supplicant( 2206): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0a,
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590,
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590,
,D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
,D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590,
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=1): 06
,D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 0a 07
,D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 0a 11
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 64:7c:34:12:7f:81],
D/wpa_supplicant( 2206): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2206):   * bssid=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2206):   * freq=2412
D/wpa_supplicant( 2206):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2206):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2206):   * Auth Type 0
,D/wpa_supplicant( 2206):   * WPA Versions 0x2
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 38:f8:89:11:e9:11]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 14 06:7c:34:12:7f:81]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 15 a0:c5:62:7a:49:97]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 16 06:7c:34:38:27:cc],
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 17 44:e9:dd:10:c0:ac]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 18 dc:4a:3e:0f:c2:f1]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 19 00:26:f2:18:08:c8]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 20 64:7c:34:38:27:cc]
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/wpa_supplicant( 2206): nl80211: Connect request send successfully
D/wpa_supplicant( 2206): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 21 44:e9:dd:10:c0:ab]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 22 44:e9:dd:10:c0:ad]
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2206): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): nl80211: Event message available
D/wpa_supplicant( 2206): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2206): nl80211: Connect event
D/wpa_supplicant( 2206): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2206): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2206): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2206): wlan0: Association info event
D/wpa_supplicant( 2206): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2206): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2206): wlan0: freq=2412 MHz
D/wpa_supplicant( 2206): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): wlan0: No keys have been configured - skip ke,y clearing
D/wpa_supplicant( 2206): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2206): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2206): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): scard is not null..
D/wpa_supplicant( 2206): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2206): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2206): TDLS: Remove peers on association
D/wpa_supplicant( 2206): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2206): EAPOL: enable timer tick
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2206): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2206): wlan0: Cancelling scan request
D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2206): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 0d 49 0b c4 a6 7e 50 b2 b2 b0 13 e0 ee 13 1b ...
D/wpa_supplicant( 2206): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2206): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2206): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2206): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2206): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2206):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2206):   key_nonce - hexdump(len=32): 0d 49 0b c4 a6 7e 50 b2 b2 b0 13 e0 ee 13 1b 89 38 7b fe 09 17 02 7a d7 03 34 29 74 be 43 91 bc
D/wpa_supplicant( 2206):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 0d 49 0b c4 a6 7e 50 b2 b2 b0 13 e0 ee 13 1b ...
D/wpa_supplicant( 2206): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2206): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2206): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2206): WPA: Renewed SNonce - hexdump(len=32): 42 a7 3f c9 46 dc 01 34 52 91 0f 9f 91 c7 83 8e 04 c7 04 34 21 16 65 c7 04 ff 29 f2 68 47 d0 47
D/wpa_supplicant( 2206): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): WPA: Nonce1 - hexdump(len=32): 42 a7 3f c9 46 dc 01 34 52 91 0f 9f 91 c7 83 8e 04 c7 04 34 21 16 65 c7 04 ff 29 f2 68 47 d0 47
D/wpa_supplicant( 2206): WPA: Nonce2 - hexdump(len=32): 0d 49 0b c4 a6 7e 50 b2 b2 b0 13 e0 ee 13 1b 89 38 7b fe 09 17 02 7a d7 03 34 29 74 be 43 91 bc
D/wpa_supplicant( 2206): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2206): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2206): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2206): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2206): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2206): WPA: Derived Key MIC - hexdump(len=16): 9c fb 64 1e a8 9b 94 89 66 5b 22 b2 d2 de d2 95
D/wpa_supplicant( 2206): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 42 a7 3f c9 46 dc 01 34 52 91 0f 9f 91 c7 83 ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2206): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 0d 49 0b c4 a6 7e 50 b2 b2 b0 13 e0 ee 13 1b ...
D/wpa_supplicant( 2206): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2206): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2206): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2206): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2206):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2206):   key_nonce - hexdump(len=32): 0d 49 0b c4 a6 7e 50 b2 b2 b0 13 e0 ee 13 1b 89 38 7b fe 09 17 02 7a d7 03 34 29 74 be 43 91 bc
D/wpa_supplicant( 2206):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_rsc - hexdump(len=8): 00 24 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_mic - hexdump(len=16): b2 8f e6 69 ca c7 e9 d2 56 21 e3 a8 0b a7 98 c0
D/wpa_supplicant( 2206): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 0d 49 0b c4 a6 7e 50 b2 b2 b0 13 e0 ee 13 1b ...
D/wpa_supplicant( 2206): RSN: encrypted key data - hexdump(len=56): b8 c8 98 cb 2a 77 19 38 1f 1a f0 01 61 c0 9f 6e 0b 9d e6 1a cc d6 fa bd cb 93 19 cc 4d f1 f9 e5 ...
D/wpa_supplicant( 2206): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2206): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2206): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2206): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 6d 3b ...
D/wpa_supplicant( 2206): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2206): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2206): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2206): WPA: Derived Key MIC - hexdump(len=16): 54 84 4e b1 60 60 8d e6 36 ea 26 00 6e 7b 70 5a
D/wpa_supplicant( 2206): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2206): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8470c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2206):    addr=c0:ff:d4:d3:aa:48
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2206): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2206): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2206): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2206): WPA: RSC - hexdump(len=6): 00 24 00 00 00 00
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6fb203a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2206):    broadcast key
I/wpa_supplicant( 2206): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2206): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2206): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2206): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2206): EAP: EAP entering state DISABLED,
D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2206): EAPOL authentication completed successfully
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection established
D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2206): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-37ms what=147462 obj=android.net.wifi.StateChangeResult@44a22e40 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DhcpStateMachine(  964): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): WaitBeforeStartState
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-28ms what=147462 obj=android.net.wifi.StateChangeResult@4333b460 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-28ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
,D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-8ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :false
I/AppUp4:CustModeStarterReceiver( 4470): onReceive
D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4470): isOpenOperator : true
D/AppUp4:CustFacade( 4470): isPhone : true
I/LicenseContentProvider( 4492): start selecting data
D/SIMObserver( 4492): simInfo1
I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4470): begin check event
I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity
,I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6427 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/HyLog   ( 6427): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6427): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6427): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2206): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2206): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2206): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd: failed to issue private commands
I/LGEmail ( 6427): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  264): Setting iface cfg
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4328adf8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4328adf8 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Trying to bring up wlan0
D/WifiStateMachine(  964): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=0 what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2206): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2206): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2206): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): DHCP successful
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
,D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
,E/Parcel  (  527): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  964): handleMessage: X
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
,D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,E/Parcel  (  527): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  964): handleMessage: X
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/LGEmail ( 6427): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
V/WfdStateTracker( 1160): handleWifiStateChangedEvent: 1
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/Parcel  (  527): Reading a NULL string not supported here.
E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,W/BaseRuntimeLoader( 6427): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6427): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6427): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6427): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/        (  264): RouteController
,D/EAS     ( 6427): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6427): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 6427): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/QCNEA   (  527): |CAC| readCallback: read len:492, ret:0, errno:0
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  527): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  527): |CAC| updateNetCfgInfo
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC|                   Netconfig               
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  527): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  527): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  527): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  527): |CAC| 	NetConfig: ip6        =::
,V/QCNEA   (  527): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  527): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  527): |CAC| net type = 1
V/QCNEA   (  527): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  527): |CAC| Received ssid= NG700
V/QCNEA   (  527): |CAC| 	ssid           =NG700
V/QCNEA   (  527): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  527): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  527): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  527): |CAC| dispatchNetCfg: updating:0xb81708dc
,D/QCNEA   (  527): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4635): networkInfo.isConnected() = false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,W/linker  ( 6427): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 6427): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 6427): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 6427): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 6427): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,D/HtmlEditor( 6427): register_HtmlEditor, Success
D/HtmlEditor( 6427): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 6427): register_HtmlEditorTimer, Success
,D/HtmlEditor( 6427): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6464 uid=10052 gids={50052, 3003}
D/HtmlEditor( 6427): register_HtmlEditorDownloader, Success
D/HtmlEditor( 6427): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6427): register_HtmlEditorFont, Success
D/HtmlEditor( 6427): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6427): register_HtmlEditorDrawText, Success
D/HtmlEditor( 6427): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6427): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 6427): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6427): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 6427): JNI_OnLoad Success
I/HubEmail( 6427): JNI_OnLoad()
I/HubEmail( 6427): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6427): registerNatives()
I/HubEmail( 6427): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6427): registerNativeMethods()
I/HubEmail( 6427): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 6427): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 6464): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6464): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6464): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): Killing 5151:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
D/MobileConnectivityChangeReceiver( 6464): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6464): onReceive CONNECTIVITY_CHANGE networkType=1
V/LGRssiData( 6464): [loadRssi] File not exist 
V/LGRssiData( 6464): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 6464): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 6464): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6464): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6464): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6464): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/DhcpStateMachine(  964): DHCP request on wlan0
D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
V/TelephonyAutoProfiling( 6464): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6464): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 6464): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6480 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 5165:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,E/PhoneMonitor( 6464): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 6464): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/CheckinService( 1944): Checking schedule, now: 1452523925780 next: 1452523302695
,I/CheckinService( 1944): active receiver: enabled
,I/CheckinService( 1944): Preparing to send checkin request
,I/EventLogService( 1944): Accumulating logs since 1452523269646
,D/HyLog   ( 6480): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6480): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6480): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6500 uid=10066 gids={50066, 4002, 3003, 1028}
,I/CheckinRequestBuilder( 1944): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1944): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 6500): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6500): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6500): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  964): Killing 5178:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6513 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 6513): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6513): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6513): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 6513): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6526 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  964): Killing 5195:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/HyLog   ( 6526): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6526): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6526): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/NFS     ( 6526): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6526): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 6526): intf.getDisplayName() = lo
I/Wireless_Storage( 6526): intf.getDisplayName() = sit0
I/Wireless_Storage( 6526): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6526): intf.getDisplayName() = teql0
,I/Wireless_Storage( 6526): intf.getDisplayName() = wlan0
D/NFS     ( 6526): interface name:wlan0 name:wlan0
D/NFS     ( 6526): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
,D/NFS     ( 6526): interface name:wlan0 name:wlan0
D/NFS     ( 6526): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 6526): CONNECT : WIFI_CONNECT
,D/dalvikvm(  964): GC_EXPLICIT freed 2688K, 48% free 30713K/57964K, paused 6ms+12ms, total 166ms
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6539 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 5604:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6539): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6539): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6539): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+5ms, total 42ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+4ms, total 31ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 27ms
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GAV2    ( 6539): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1944): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x43257d60: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/wpa_supplicant( 2206): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2206): EAPOL: disable timer tick
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6558 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6558): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6558): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6558): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6558): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6558): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 6558): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6558): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6558): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 6558): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6558): install
,I/MultiDex( 6558): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6558): loading existing secondary dex files
,I/MultiDex( 6558): load found 3 secondary dex files
,V/WebViewChromium( 6539): Binding Chromium to the main looper Looper (main, tid 1) {42851348}
,I/chromium( 6539): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6539): Initializing chromium process, renderers=0
,I/MultiDex( 6558): install done
,W/chromium( 6539): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/dalvikvm( 6558): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6558): VFY: unable to resolve instance field 61
,D/dalvikvm( 6558): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6558): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6558): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 6558): VFY: replacing opcode 0x62 at 0x0067
,I/Adreno-EGL( 6539): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6539): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6539): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6539): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6539): Remote Branch: 
I/Adreno-EGL( 6539): Local Patches: 
I/Adreno-EGL( 6539): Reconstruct Branch: 
D/dalvikvm( 6558): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6558): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6558): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6558): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6558): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6558): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4284d368
D/dalvikvm( 6558): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4284d368
,D/dalvikvm( 6558): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4284d368, skipping init
,D/dalvikvm( 6558): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4284d368
,D/dalvikvm( 6558): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4284d368
,V/JNIHelp ( 6558): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 6539): Starting up...
,I/ActivityManager(  964): Killing 5658:com.android.contacts/u0a21 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 6377): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6377): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/dalvikvm( 6558): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4284d368
,D/dalvikvm( 6558): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4284d368
D/dalvikvm( 6558): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4284d368
,D/dalvikvm( 6558): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4284d368
,D/QRemote ( 6377): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6377): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6377): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6377): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6343): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6343): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6377): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6377): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6377): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6377): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,I/ProviderInstaller( 6558): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1542): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1542): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1542): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1944): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 4251): callingUid 10006, callindPid: 4251
,D/LocationInitializer( 1944): Restart initialization of location
,E/MDM     ( 1427): [74] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 6558): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6558): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6558): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 6558): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6558): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6558): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1dc2000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1dc2000
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=2409221230
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 6558): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a47f98
,D/dalvikvm( 6558): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a47f98
,D/dalvikvm( 6558): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a47f98, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,W/Settings( 6558): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 6558): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6598): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 6558): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6558): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 109ms
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Adreno-EGL( 6558): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6558): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6558): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6558): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6558): Remote Branch: 
I/Adreno-EGL( 6558): Local Patches: 
I/Adreno-EGL( 6558): Reconstruct Branch: 
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,D/GCM     ( 1542): Connected
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1542): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=2823993682
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 6558): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6558): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6558): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6558): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6558): Remote Branch: 
I/Adreno-EGL( 6558): Local Patches: 
I/Adreno-EGL( 6558): Reconstruct Branch: 
,I/Adreno-EGL( 6558): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6558): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6558): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6558): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6558): Remote Branch: 
I/Adreno-EGL( 6558): Local Patches: 
I/Adreno-EGL( 6558): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1944): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/NativeCrypto( 1944): SSL shutdown failed: ssl=0x6cd52148: I/O error during system call, Connection timed out
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/LicenseContentProvider( 4492): start selecting data
,D/SIMObserver( 4492): simInfo1
,I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4470): begin check event
I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4470): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4470): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4470): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4470): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4470): handleAsyncCustNotification do not startCustService
,D/EAS     ( 6427): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5065): DownloadService onCreate
,D/EAS     ( 6427): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 5065): in removeSpuriousFiles
D/eas_req ( 6427): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42afe0a0 on behalf of 5065
,I/DownloadManager( 5065): in trimDatabase
,I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,W/Settings( 6427): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5065): DownloadService onStartCommand
I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4635): networkInfo.isConnected() = false
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/MobileConnectivityChangeReceiver( 6464): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6464): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42afff10 on behalf of 5065
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b01c48 on behalf of 5065
V/DownloadManager( 5065): DownloadService onDestroy
,D/LGDMSGCM( 6513): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 6526): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6526): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 6513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/NativeCrypto( 1944): SSL shutdown failed: ssl=0x6cd653e8: I/O error during system call, Connection timed out
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/LicenseContentProvider( 4492): start selecting data
,D/SIMObserver( 4492): simInfo1
,I/CheckinTask( 1944): Sending checkin request (11627 bytes)
,I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4470): begin check event
,I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5065): DownloadService onCreate
,D/EAS     ( 6427): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6427): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b06368 on behalf of 5065
,V/DownloadManager( 5065): DownloadService onStartCommand
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5065): in trimDatabase
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b09310 on behalf of 5065
I/LgeMiscReceiver( 4635): networkInfo.isConnected() = true
,D/PhoneState( 4635): setPdpRejectCasuse : false
,W/Settings( 6427): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b094d0 on behalf of 5065
,D/MobileConnectivityChangeReceiver( 6464): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6464): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5065): DownloadService onDestroy
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 6513): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 6526): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6526): CONNECT : WIFI_CONNECT
,W/ContextImpl( 6513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 3974): GC_FOR_ALLOC freed 496K, 2% free 37893K/38604K, paused 28ms, total 28ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
,D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/LicenseContentProvider( 4492): start selecting data
,D/SIMObserver( 4492): simInfo1
,I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4470): begin check event
,I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 6427): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5065): DownloadService onCreate
,D/EAS     ( 6427): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4635): networkInfo.isConnected() = true
,D/PhoneState( 4635): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6464): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6464): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6513): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6526): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6526): CONNECT : WIFI_CONNECT
,W/Settings( 6427): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 5065): in removeSpuriousFiles
,D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b0db00 on behalf of 5065
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 5065): in trimDatabase
V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b0f4f8 on behalf of 5065
V/DownloadManager( 5065): DownloadService onStartCommand
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b115b8 on behalf of 5065
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/DownloadManager( 5065): DownloadService onDestroy
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinResponseProcessor( 1944): From server: 1 gservices updates and 0 deletes
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/CertBlacklister(  964): Certificate blacklist changed, updating...
,I/CertBlacklister(  964): Certificate blacklist updated
,I/GservicesProvider( 1542): main difference update completed
,I/ActivityManager(  964): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6715 uid=10003 gids={50003, 3003, 2001}
,I/CheckinRequestBuilder( 1944): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1944): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/HyLog   ( 6715): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6715): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6715): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ContextImpl( 6715): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 6715): Update started
,D/DownloadManager( 5065): DB Update : deleted 1
,V/DownloadManager( 5065): DownloadService onCreate
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,E/UpdateRequestReceiver( 6715): Received malformed URL while handling Gservices.CHANGED_ACTION
V/DownloadManager( 5065): initiating download with UID 10003
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b16048 on behalf of 5065
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): DownloadService onStartCommand
,I/DownloadManager( 5065): in trimDatabase
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b1a6c8 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b1b678 on behalf of 5065
,V/DownloadManager( 5065): processing inserted download 217
V/LFT     ( 5065): isReadyToDownload mId, mStatus=217:190
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b1e560 on behalf of 5065
,D/DownloadManager( 5065): DB Update : status 192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b20fd0 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b22740 on behalf of 5065
V/DownloadManager( 5065): processing updated download 217, status: 192
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=217:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5065): Download 217 starting
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b246d0 on behalf of 5065
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/DownloadManager( 5065): fileSize : -1state.mContinuingDownload :false
,W/ContextImpl( 6715): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/UpdateFetcherService( 6715): Update started
,D/DownloadManager( 5065): DB Update : deleted 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): initiating download with UID 10003
,D/dalvikvm(  964): GC_EXPLICIT freed 1727K, 48% free 30695K/57964K, paused 5ms+13ms, total 178ms
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b2b230 on behalf of 5065
,E/UpdateRequestReceiver( 6715): Received malformed URL while handling Gservices.CHANGED_ACTION
,V/DownloadManager( 5065): DownloadService onStartCommand
,E/UpdateRequestReceiver( 6715): Received malformed URL while handling Gservices.CHANGED_ACTION
V/DownloadManager( 5065): processing updated download 217, status: 192
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=217:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,E/UpdateRequestReceiver( 6715): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  964): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6760 uid=10009 gids={50009, 3003}
,I/GAV2    ( 6539): Thread[GAThread,5,main]: No campaign data found.
,D/HyLog   ( 6760): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6760): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6760): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,W/BaseRuntimeLoader( 6760): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6760): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6760): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6760): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/dalvikvm( 5065): GC_EXPLICIT freed 2630K, 30% free 17489K/24832K, paused 5ms+19ms, total 132ms
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b8bee8 on behalf of 5065
,D/dalvikvm( 1542): GC_EXPLICIT freed 1512K, 28% free 18043K/24832K, paused 3ms+7ms, total 67ms
,V/DownloadManager( 5065): processing inserted download 218
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=218:190
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b7df60 on behalf of 5065
,I/Search.GservicesUpdateTask( 2655): Updating Gservices keys
,D/DownloadManager( 5065): DB Update : status 192
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x42c80a38: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1944): awaiting user notification for token
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429316f0 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428de8f0 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 217, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=217:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4288d408 on behalf of 5065
,I/DownloadManager( 5065): Download 218 starting
,V/DownloadManager( 5065): processing updated download 218, status: 192
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=218:192
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b237f8 on behalf of 5065
I/DownloadManager( 5065): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 5065): Content-Disposition: null
V/DownloadManager( 5065): Content-Length: -1
,V/DownloadManager( 5065): Content-Location: null
V/DownloadManager( 5065): Content-Type: text/plain
V/DownloadManager( 5065): ETag: null
V/DownloadManager( 5065): Transfer-Encoding: chunked
V/DownloadManager( 5065): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 5065): Min update size = 16384
V/DownloadManager( 5065): getting filename from uri
I/DownloadManager( 5065): in verifySpace, destination: 5, path: 08202014-metadata.txt, length: 0
V/DownloadManager( 5065): keeping extension
,V/DownloadManager( 5065): target file: /cache/08202014-metadata.txt
V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,I/CheckinRequestBuilder( 1944): Classify the device as Phone.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42aa0b98 on behalf of 5065
,D/DownloadManager( 5065): fileSize : -1state.mContinuingDownload :false
D/DownloadManager( 5065): DB Update : title 08202014-metadata.txt
,D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 5065): DB Update : total_bytes -1
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429fab60 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 217, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=217:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a16ac8 on behalf of 5065
,D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): processing updated download 218, status: 192
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=218:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 5065): transferData threadNum : -1
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428f4268 on behalf of 5065
D/DownloadManager( 5065): DB Update : current_bytes 384
,D/DownloadManager( 5065): DB Update : total_bytes 384
,I/DownloadManager( 5065): Ignoring Content-Length since Transfer-Encoding is also defined
,V/DownloadManager( 5065): Content-Disposition: null
,V/DownloadManager( 5065): Content-Length: -1
V/DownloadManager( 5065): Content-Location: null
V/DownloadManager( 5065): Content-Type: text/plain
,V/DownloadManager( 5065): ETag: null
,V/DownloadManager( 5065): Transfer-Encoding: chunked
,V/DownloadManager( 5065): X-Oma-Drm-Separate-Delivery: null
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): Min update size = 16384
V/DownloadManager( 5065): getting filename from uri
,I/DownloadManager( 5065): in verifySpace, destination: 5, path: 10152015-sms-metadata.txt, length: 0
V/DownloadManager( 5065): keeping extension
I/SystemUpdateService( 1944): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,V/DownloadManager( 5065): target file: /cache/10152015-sms-metadata.txt
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42997ea8 on behalf of 5065
V/LFT     ( 5065): notifyThroughDatabase after updateDB  id :  217, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 5065): notifyThroughDatabase start id : 217 name : /cache/08202014-metadata.txt status : 200
V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428f1a50 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 217, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=217:192
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428715a0 on behalf of 5065
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a51158 on behalf of 5065
,D/SystemUpdateService( 1944): onCreate
D/DownloadManager( 5065): DB Update : title 10152015-sms-metadata.txt
,D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 5065): DB Update : total_bytes -1
,D/DownloadManager( 5065): DB Update : numfailed 0
,D/DownloadManager( 5065): DB Update : method 0
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
,V/DownloadManager( 5065): processing updated download 218, status: 192
D/DownloadManager( 5065): DB Update : lastmod 1452523931588
D/DownloadManager( 5065): DB Update : mimetype text/plain
,D/DownloadManager( 5065): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 5065): DB Update : status 200
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=218:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/SystemUpdateService( 1944): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42899d08 on behalf of 5065
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 5065): Download 217 finished with status SUCCESS
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428654c8 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 218, status: 192
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=218:192
,D/DownloadManager( 5065): transferData threadNum : -1
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a01938 on behalf of 5065
,D/SystemEventReceiver( 1944): Received GSERVICES_CHANGED broadcast
,D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): DB Update : current_bytes 383
,D/DownloadManager( 5065): DB Update : total_bytes 383
I/SystemUpdateService( 1944): cancelUpdate (empty URL)
,I/SystemUpdateService( 1944): active receiver: disabled
,I/OcrUtils( 1944): Updating ocr activity enabled=false
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4288f2d8 on behalf of 5065
,V/LFT     ( 5065): notifyThroughDatabase after updateDB  id :  218, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 5065): notifyThroughDatabase start id : 218 name : /cache/10152015-sms-metadata.txt status : 200
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429e6b38 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 218, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=218:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/GCoreUlr( 1427): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4294e410 on behalf of 5065
,D/DownloadManager( 5065): DB Update : numfailed 0
D/DownloadManager( 5065): DB Update : method 0
,D/DownloadManager( 5065): DB Update : lastmod 1452523931663
D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 5065): DB Update : status 200
,D/GCM     ( 1542): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/SystemUpdateService( 1944): onDestroy
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5065): Download 218 finished with status SUCCESS
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a1fde0 on behalf of 5065
,V/DownloadManager( 5065): DownloadService onDestroy
I/ActivityManager(  964): Killing 5675:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/CheckinTask( 1944): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/GCoreUlr( 1427): DispatchingService.onCreate()
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 1944): Checking schedule, now: 1452523931756 next: 1453101327720
,I/CheckinService( 1944): active receiver: disabled
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1944): GC_CONCURRENT freed 1969K, 21% free 19640K/24832K, paused 6ms+7ms, total 83ms
I/ActivityManager(  964): Killing 5506:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/CheckinService( 1944): Checking schedule, now: 1452523931820 next: 1453101327720
,I/CheckinService( 1944): active receiver: disabled
,W/Search.LoginHelper( 2655): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 2655): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x42aa9f20: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
,I/GCoreUlr( 1427): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/dalvikvm( 1542): GC_EXPLICIT freed 643K, 28% free 18027K/24832K, paused 2ms+6ms, total 42ms
,I/GCoreUlr( 1427): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1427): Unbound from all location providers
,I/GCoreUlr( 1427): DispatchingService.onDestroy()
,I/GCoreUlr( 1427): Unbound from all location providers
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 217; sort is lastmod DESC.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b1b958 on behalf of 6715
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 217; sort is lastmod DESC.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  964): GC_EXPLICIT freed 1766K, 48% free 30706K/57964K, paused 8ms+14ms, total 213ms
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42925860 on behalf of 6715
,W/ContextImpl( 6715): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/ActivityManager(  964): Killing 6343:com.lge.sync/1000 (adj 15): empty #17
,V/DownloadManager( 5065): initiating download with UID 10003
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,V/DownloadManager( 5065): DownloadService onCreate
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a50f08 on behalf of 5065
,I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
,I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/10152015-sms-metadata.txt
,V/DownloadManager( 5065): DownloadService onStartCommand
I/DownloadManager( 5065): in trimDatabase
V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428c4a68 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428ce990 on behalf of 5065
,V/DownloadManager( 5065): processing inserted download 217
,V/DownloadManager( 5065): processing inserted download 218
,V/DownloadManager( 5065): processing inserted download 219
V/LFT     ( 5065): isReadyToDownload mId, mStatus=219:190
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428979a8 on behalf of 5065
,D/DownloadManager( 5065): DB Update : status 192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b1f0b0 on behalf of 5065
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a409a8 on behalf of 5065
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 218; sort is lastmod DESC.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428c0400 on behalf of 6715
,I/DownloadManager( 5065): Download 219 starting
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 218; sort is lastmod DESC.
V/DownloadManager( 5065): processing updated download 219, status: 192
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=219:192
D/DownloadManager( 5065): fileSize : -1state.mContinuingDownload :false
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429fec70 on behalf of 6715
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429d6790 on behalf of 5065
,W/ContextImpl( 6715): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 5065): initiating download with UID 10003
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42aeff80 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 219, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=219:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428ab540 on behalf of 5065
,V/DownloadManager( 5065): processing inserted download 220
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=220:190
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b887e0 on behalf of 5065
,D/DownloadManager( 5065): DB Update : status 192
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a205d0 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a524a8 on behalf of 5065
,V/DownloadManager( 5065): processing updated download 219, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=219:192
I/DownloadManager( 5065): Download 220 starting
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b078d8 on behalf of 5065
,D/DownloadManager( 5065): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 5065): processing updated download 220, status: 192
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=220:192
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428ca148 on behalf of 5065
,D/dalvikvm( 1542): GC_EXPLICIT freed 152K, 28% free 17993K/24832K, paused 3ms+8ms, total 60ms
,I/DownloadManager( 5065): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 5065): Content-Disposition: null
V/DownloadManager( 5065): Content-Length: -1
V/DownloadManager( 5065): Content-Location: null
V/DownloadManager( 5065): Content-Type: text/plain
V/DownloadManager( 5065): ETag: null
V/DownloadManager( 5065): Transfer-Encoding: chunked
V/DownloadManager( 5065): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 5065): Min update size = 16384
V/DownloadManager( 5065): getting filename from uri
I/DownloadManager( 5065): in verifySpace, destination: 5, path: 08202014-pins.txt, length: 0
V/DownloadManager( 5065): keeping extension
,V/DownloadManager( 5065): target file: /cache/08202014-pins.txt
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42ad8008 on behalf of 5065
,D/DownloadManager( 5065): DB Update : title 08202014-pins.txt
D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/08202014-pins.txt
,D/DownloadManager( 5065): DB Update : total_bytes -1
,I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@428f2ca0 on behalf of 5065
,D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): transferData threadNum : -1
,D/DownloadManager( 5065): transferData threadNum : -1
I/DownloadManager( 5065): Ignoring Content-Length since Transfer-Encoding is also defined
,V/DownloadManager( 5065): Content-Disposition: null
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): Content-Length: -1
,V/DownloadManager( 5065): Content-Location: null
V/DownloadManager( 5065): Content-Type: text/plain
V/DownloadManager( 5065): ETag: null
V/DownloadManager( 5065): Transfer-Encoding: chunked
V/DownloadManager( 5065): X-Oma-Drm-Separate-Delivery: null
,V/DownloadManager( 5065): Min update size = 16384
V/DownloadManager( 5065): getting filename from uri
I/DownloadManager( 5065): in verifySpace, destination: 5, path: 10152015-sms-blacklist.txt, length: 0
,V/DownloadManager( 5065): keeping extension
,V/DownloadManager( 5065): target file: /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 5065): transferData threadNum : -1
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): processing updated download 219, status: 192
,V/LFT     ( 5065): isReadyToDownload mId, mStatus=219:192
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 5065): transferData threadNum : -1
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4296a850 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b1aba8 on behalf of 5065
,D/GCM     ( 1542): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/DownloadManager( 5065): DB Update : title 10152015-sms-blacklist.txt
D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 5065): DB Update : total_bytes -1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): processing updated download 220, status: 192
D/DownloadManager( 5065): transferData threadNum : -1
V/LFT     ( 5065): isReadyToDownload mId, mStatus=220:192
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429dc430 on behalf of 5065
D/DownloadManager( 5065): transferData threadNum : -1
I/DownloadManager( 5065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/LGDRM   (  276): [DRM] Part_DetectType() : Buffer contains XML Prologue
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a1d9d8 on behalf of 5065
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): DB Update : current_bytes 13383
D/DownloadManager( 5065): DB Update : total_bytes 13383
D/DownloadManager( 5065): DB Update : current_bytes 32768
V/DownloadManager( 5065): processing updated download 219, status: 192
V/LFT     ( 5065): isReadyToDownload mId, mStatus=219:192
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 5065): notifyThroughDatabase after updateDB  id :  220, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 5065): notifyThroughDatabase start id : 220 name : /cache/10152015-sms-blacklist.txt status : 200
V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b0a868 on behalf of 5065
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b03548 on behalf of 5065
D/DownloadManager( 5065): DB Update : numfailed 0
D/DownloadManager( 5065): DB Update : method 0
V/DownloadManager( 5065): downloaded 32768 for https://www.gstatic.com/android/config_update/08202014-pins.txt
D/DownloadManager( 5065): DB Update : lastmod 1452523932745
D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): DB Update : _data /cache/10152015-sms-blacklist.txt
D/DownloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): DB Update : status 200
V/DownloadManager( 5065): processing updated download 220, status: 192
D/DownloadManager( 5065): transferData threadNum : -1
V/LFT     ( 5065): isReadyToDownload mId, mStatus=220:192
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 5065): transferData threadNum : -1
D/Dow,nloadManager( 5065): transferData threadNum : -1
D/DownloadManager( 5065): transferData threadNum : -1
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429b1808 on behalf of 5065
D/DownloadManager( 5065): DB Update : current_bytes 39938
D/DownloadManager( 5065): checkStatusUpdate current status 192 is changed to 200
D/DownloadManager( 5065): checkStatusUpdate return true mID : mStatus = 220 : 200 => 200
D/DownloadManager( 5065): DB Update : total_bytes 39938
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 5065): Download 220 finished with status SUCCESS
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a2f1e0 on behalf of 5065
V/LFT     ( 5065): notifyThroughDatabase after updateDB  id :  219, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 5065): notifyThroughDatabase start id : 219 name : /cache/08202014-pins.txt status : 200
V/DownloadManager( 5065): processing updated download 219, status: 192
V/DownloadManager( 5065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 5065): isReadyToDownload mId, mStatus=219:192
V/DownloadManager( 5065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42aee6b0 on behalf of 5065
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4297a5e8 on behalf of 5065
D/DownloadManager( 5065): DB Update : numfailed 0
D/DownloadManager( 5065): DB Update : method 0
D/DownloadManager( 5065): DB Update : lastmod 1452523932763
D/DownloadManager( 5065): DB Update : mimetype text/plain
D/DownloadManager( 5065): DB Update : _data /cache/08202014-pins.txt
D/DownloadManager( 5065): DB Update : status 200
V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 220; sort is lastmod DESC.
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b43918 on behalf of 6715
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a3afc0 on behalf of 5065
I/DownloadManager( 5065): Download 219 finished with status SUCCESS
V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 220; sort is lastmod DESC.
V/DownloadManager( 5065): DownloadService onDestroy
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a4eca0 on behalf of 6715
,W/ContextImpl( 6715): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 6715): Update downloaded, starting installation
,I/UpdateFetcherService( 6715): Started installation
,D/DownloadManager( 5065): DB Update : deleted 1
,V/DownloadManager( 5065): DownloadService onCreate
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@4297b900 on behalf of 5065
,I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/10152015-sms-metadata.txt
I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/08202014-pins.txt
,I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/10152015-sms-blacklist.txt
,I/DownloadManager( 5065): in trimDatabase
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b50180 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b16788 on behalf of 5065
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 219; sort is lastmod DESC.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42ad2448 on behalf of 6715
,V/DownloadManager( 5065): processing inserted download 217
V/DownloadManager( 5065): processing inserted download 218
,D/DownloadManager( 5065): deleteFileIfExists() deleting /cache/10152015-sms-metadata.txt
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 219; sort is lastmod DESC.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a8c248 on behalf of 6715
,V/DownloadManager( 5065): processing inserted download 219
,W/ContextImpl( 6715): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
V/DownloadManager( 5065): processing inserted download 220
,D/DownloadManager( 5065): deleteFileIfExists() deleting /cache/10152015-sms-blacklist.txt
,I/UpdateFetcherService( 6715): Update downloaded, starting installation
,I/UpdateFetcherService( 6715): Started installation
,D/DownloadManager( 5065): DB Update : deleted 1
,V/DownloadManager( 5065): DownloadService onDestroy
,V/DownloadManager( 5065): DownloadService onCreate
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a42ed0 on behalf of 5065
,V/DownloadManager( 5065): DownloadService onStartCommand
I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5065): in removeSpuriousFiles, preserving file /cache/08202014-pins.txt
,I/DownloadManager( 5065): in trimDatabase
V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429f6ec0 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429f7958 on behalf of 5065
V/DownloadManager( 5065): processing inserted download 217
,D/DownloadManager( 5065): deleteFileIfExists() deleting /cache/08202014-metadata.txt
,V/DownloadManager( 5065): processing inserted download 219
,D/DownloadManager( 5065): deleteFileIfExists() deleting /cache/08202014-pins.txt
,V/DownloadManager( 5065): DownloadService onDestroy
I/ConfigUpdateInstallReceiver(  964): Not installing, new version is <= current version
I/ActivityManager(  964): Killing 6377:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3810): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3810): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  964): Handling package changes for user 0
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6868 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
,W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "smsto"
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 6868): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6868): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6868): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
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
,I/Babel   ( 6868): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6868): MmsConfig.loadMmsSettings
,I/Babel   ( 6868): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6868): MmsConfig.loadFromDatabase
,I/MediaCodecList( 6868): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 6868): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 6868): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6868): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 6868): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6868): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6868): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6868): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 6868): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6868): MmsConfig.loadFromResources
,E/Babel   ( 6868): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6868): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1427): DISABLE
,W/Settings( 6868): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6868): [loadRssi] File not exist 
,V/LGRssiData( 6868): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6868): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 6868): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6868): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6868): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4470): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4470): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4470): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
,D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/LicenseContentProvider( 4492): start selecting data
D/SIMObserver( 4492): simInfo1
I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4470): begin check event
D/AppUp4:Utils( 4470): [getPackageName] uri : package:com.google.android.gms
I/AppUp4:CustModeStarterReceiver( 4470): Event For Nothing, skip.
,D/LocationProviderProxy(  964): applying state to connected service
I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6919 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/LocationProviderProxy(  964): applying state to connected service
,D/HyLog   ( 6919): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6919): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6919): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6919): BUILD Country: EU
,I/SystemConfig( 6919): BUILD Operator: OPEN
I/ActivityManager(  964): Killing 6427:com.lge.email/u0a24 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SystemConfig( 6919): systemFeature RCS result false
D/SystemConfig( 6919): refreshRcsSupport() :false
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6939 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): Killing 6480:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6939): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2655): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  964): Killing 6500:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6958 uid=10050 gids={50050, 3003, 1028, 1015}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6958): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6958): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6958): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6958): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6958): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6958): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 6958): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6958): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6958): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6958): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6958): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6958): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6958): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6958): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6958): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6958): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 6958): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6958): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 6958): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6958): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6958): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6958): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6958): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6958): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a835c0 on behalf of 6958
,I/dalvikvm( 6958): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 6958): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6958): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 6958): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 6958): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6958): VFY: replacing opcode 0x6e at 0x0049
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6958): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6958): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6958): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/dalvikvm(  964): GC_EXPLICIT freed 1598K, 48% free 30650K/57964K, paused 6ms+14ms, total 183ms
,D/PackageBroadcastService( 1944): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6958): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/PackageBroadcastService( 1944): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  964): Delaying start of: ServiceRecord{447753d8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1944): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2655): UpdateCorporaTask done [took 486 ms] updated apps [took 486 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6958): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6958): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6958): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6958): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6958): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6958): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6958): Total arena pages for JIT: 11
,I/dalvikvm( 6958): Total arena pages for JIT: 12
,I/dalvikvm( 6958): Total arena pages for JIT: 13
,I/dalvikvm( 6958): Total arena pages for JIT: 14
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6958): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6958): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6958): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6958): [1] DailyHygiene.reschedule: Scheduling new run in 808 minutes (failures=5)
,D/DeviceConnectionService( 1427): client connected with version: 7571000
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523939062231738; DSPS: 26246363; Offset: 1452523138086798389
,I/GAV4    ( 6868): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  964): Killing 6513:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/Finsky  ( 6958): [543] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6958): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523959063190594; DSPS: 26901754; Offset: 1452523138086811200
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523979063646109; DSPS: 27557129; Offset: 1452523138086808951
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523980048, nextTick: 59977, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452523980054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452523999064554174; DSPS: 28212519; Offset: 1452523138086801489
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524019064993690; DSPS: 28867893; Offset: 1452523138086813759
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524039065932593; DSPS: 29523284; Offset: 1452523138086806617
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524040050, nextTick: 59977, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524040053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524059066791117; DSPS: 30178672; Offset: 1452523138086810649
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524079067261680; DSPS: 30834048; Offset: 1452523138086792930
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524099071901576; DSPS: 31489560; Offset: 1452523138086794155
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524100045, nextTick: 59984, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524100054, nextTick: 59979, mDrawingTime: 0
,D/wpa_supplicant( 2206): wlan0: BSS: Remove id 11 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 12 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 13 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 14 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 15 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 16 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 17 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 18 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 19 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 20 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 21 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Remove id 22 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 64:7c:34:12:7f:81]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 38:f8:89:11:e9:11],
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 06:7c:34:12:7f:81]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 a0:c5:62:7a:49:97]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 16 06:7c:34:38:27:cc]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 17 44:e9:dd:10:c0:ac],
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 18 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 19 00:26:f2:18:08:c8]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 20 64:7c:34:38:27:cc]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 21 44:e9:dd:10:c0:ab]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 22 44:e9:dd:10:c0:ad]
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524119073350340; DSPS: 32144967; Offset: 1452523138086808592
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524139073791247; DSPS: 32800341; Offset: 1452523138086822253
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524159074247596; DSPS: 33455716; Offset: 1452523138086820839
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524160033, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524160040, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524179075231211; DSPS: 34111109; Offset: 1452523138086797374
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524199076597211; DSPS: 34766513; Offset: 1452523138086820600
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524219077924318; DSPS: 35421917; Offset: 1452523138086804934
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524220048, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524220051, nextTick: 59979, mDrawingTime: 1
,D/dalvikvm( 1944): GC_EXPLICIT freed 942K, 22% free 19586K/24832K, paused 5ms+9ms, total 71ms
,I/EventLogService( 1944): Aggregate from 1452523925825 (log), 1452522289107 (data)
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x430f8f10: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1542): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1542): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1542): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1542): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1542): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1542): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1542): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1542): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 6958): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6958): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6958): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6958): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6958): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6958): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6958): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6958): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 6958): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6958): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524239079344191; DSPS: 36077324; Offset: 1452523138086790481
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524259080759140; DSPS: 36732730; Offset: 1452523138086801621
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524279082067960; DSPS: 37388133; Offset: 1452523138086798185
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524280048, nextTick: 59976, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524280053, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524299083008037; DSPS: 38043523; Offset: 1452523138086822735
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524319083484240; DSPS: 38698899; Offset: 1452523138086810657
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524339083921883; DSPS: 39354274; Offset: 1452523138086790536
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524340043, nextTick: 59973, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524340054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524359085334746; DSPS: 40009680; Offset: 1452523138086799590
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524379086888256; DSPS: 40665091; Offset: 1452523138086796704
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524399087834854; DSPS: 41320481; Offset: 1452523138086827774
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524400054, nextTick: 59974, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524400058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524419088748112; DSPS: 41975871; Offset: 1452523138086825505
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524439089665805; DSPS: 42631262; Offset: 1452523138086797153
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524459090117538; DSPS: 43286636; Offset: 1452523138086821640
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524460042, nextTick: 59989, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524460043, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524479092210483; DSPS: 43942065; Offset: 1452523138086808872
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524499092398775; DSPS: 44597431; Offset: 1452523138086814059
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524519093272161; DSPS: 45252820; Offset: 1452523138086802435
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524520047, nextTick: 59981, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524520050, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524539094708358; DSPS: 45908227; Offset: 1452523138086804306
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524559096047552; DSPS: 46563631; Offset: 1452523138086800726
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524579096476238; DSPS: 47219005; Offset: 1452523138086802166
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524580048, nextTick: 59981, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524580050, nextTick: 59978, mDrawingTime: 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524599097426322; DSPS: 47874396; Offset: 1452523138086806205
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524619098330367; DSPS: 48529785; Offset: 1452523138086825241
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524639098786992; DSPS: 49185161; Offset: 1452523138086793584
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524640033, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524640040, nextTick: 59989, mDrawingTime: 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524659099741305; DSPS: 49840552; Offset: 1452523138086801852
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524679101170436; DSPS: 50495958; Offset: 1452523138086827175
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524699103527772; DSPS: 51151396; Offset: 1452523138086804140
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524700042, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524700056, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524719104904660; DSPS: 51806801; Offset: 1452523138086807737
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524739105806941; DSPS: 52462191; Offset: 1452523138086794490
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524759106696880; DSPS: 53117580; Offset: 1452523138086799420
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524760039, nextTick: 59970, mDrawingTime: 9
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524760054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524779107586636; DSPS: 53772969; Offset: 1452523138086804166
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524799108951958; DSPS: 54428374; Offset: 1452523138086796197
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524819109397257; DSPS: 55083748; Offset: 1452523138086814250
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524820029, nextTick: 59997, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524820066, nextTick: 59964, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524839110801472; DSPS: 55739154; Offset: 1452523138086814656
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524859112725023; DSPS: 56394577; Offset: 1452523138086815600
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524879113191506; DSPS: 57049952; Offset: 1452523138086824319
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524880039, nextTick: 59987, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524880053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524899114599198; DSPS: 57705359; Offset: 1452523138086797685
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524919115500332; DSPS: 58360748; Offset: 1452523138086813809
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524939116377318; DSPS: 59016137; Offset: 1452523138086805785
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524940032, nextTick: 59986, mDrawingTime: 6
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452524940042, nextTick: 59989, mDrawingTime: 1
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  964): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  964): Done.
,I/ProcessStatsService(  964): Prepared write state in 77ms
,D/QcConnectivityService(  964): Setting timer for 720seconds
,I/ProcessStatsService(  964): Pruning old procstats: /data/system/procstats/state-2016-01-11-00-52-00.bin
,D/GCM     ( 1542): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524959117883390; DSPS: 59671546; Offset: 1452523138086816496
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1542): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1542): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1542): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1542): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1542): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1542): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524979119270769; DSPS: 60326952; Offset: 1452523138086800066
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452524999120156259; DSPS: 60982341; Offset: 1452523138086800547
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452525000033, nextTick: 59994, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452525000036, nextTick: 59995, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452525019121083503; DSPS: 61637732; Offset: 1452523138086781746
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/wpa_supplicant( 2206): nl80211: Event message available
D/wpa_supplicant( 2206): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2206): nl80211: Disconnect event
D/wpa_supplicant( 2206): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2206): wlan0: Deauthentication notification
D/wpa_supplicant( 2206): wlan0:  * reason 0
D/wpa_supplicant( 2206): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2206): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2206): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2206): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2206): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2206): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2206): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2206): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
D/WifiStateMachine(  964): handleMessage: E msg.what=147460
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection lost
D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 1,
,D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb846fd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2206):    addr=c0:ff:d4:d3:aa:48,
,D/wpa_supplicant( 2206): wlan0: State: COMPLETED -> DISCONNECTED
,D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT),
D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=5,
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2206): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2206): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2206): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  964): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiHS20(  964): hidePasspointNotification off =false
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1160): handleWifiStateChangedEvent: 0
D/wpa_supplicant( 2206): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2206): wlan0: nl80211: scan request
,D/wpa_supplicant( 2206): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2206): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2206): nl80211: Event message available
D/wpa_supplicant( 2206): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2206): wlan0: nl80211: Scan trigger
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
,E/Parcel  (  527): Reading a NULL string not supported here.
D/QCNEA   (  527): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  527): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  527): |CAC| updateNetCfgInfo
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC|                   Netconfig               
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  527): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  527): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  527): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  527): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  527): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  527): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| Received bssid= 
D/QCNEA   (  527): |CAC| net type = 3
V/QCNEA   (  527): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  527): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  527): |CAC| 	ssid           =NG700
V/QCNEA   (  527): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  527): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  527): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  527): |CAC| dispatchNetCfg: updating:0xb81708dc
,D/QCNEA   (  527): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  527): Reading a NULL string not supported here.
,E/Parcel  (  527): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
,D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8019 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '97 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 97 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '98 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 98 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '99 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 99 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 8019): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 8019): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 8019): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 8019): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 8019): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 8019): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
,W/NetworkManagementService(  964): route cmd failed: 
W/NetworkManagementService(  964): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '101 route del src v6 2' failed with '400 101 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x63788048 clazz=0x1a700001 iface=wlan0 mask=0x3
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8063 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  964): Killing 6526:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,V/NativeCrypto( 1542): Read error: ssl=0x6240ac08: I/O error during system call, Connection timed out
,V/NativeCrypto( 1542): SSL shutdown failed: ssl=0x6240ac08: I/O error during system call, Broken pipe
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/DhcpStateMachine(  964): StoppedState
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 8063): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 8063): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 8063): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/QRemote ( 8063): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 8063): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 8063): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 8063): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 8063): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 8063): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 8063): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/QRemote ( 8063): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 8063): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 6539:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2206): nl80211: Event message available
D/wpa_supplicant( 2206): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2206): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2206): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2206): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 2206): nl80211: Survey data missing
D/wpa_supplicant( 2206): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 23 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 24 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 25 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 26 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 27 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 28 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 29 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 30 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: BSS: Add new id 31 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 2206): wlan0: New scan results available
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2206): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2206): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2206): WPS: AP 44:e9:dd:10:c0:ac type 0 added
D/wpa_supplicant( 2206): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2206): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplican,t( 2206): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2206): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[4] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[5] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): WPS: AP[6] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2206): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2206): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-47 wps,
,D/wpa_supplicant( 2206): wlan0:    skip - blacklisted (count=1 limit=0),
D/wpa_supplicant( 2206): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-74
,D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2206): wlan0: 3: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-87 wps
,D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-83 wps,
,D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 5: 44:e9:dd:10:c0:ac ssid='FunBox2-C0AB' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-89 wps
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-86
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 7: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-86 wps
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 8: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-89 wps
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 9: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-89
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2206): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2206): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2206): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2206): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2206): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-47 wps
D/wpa_supplicant( 2206): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2206): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg_mdm_auto_connect_policy 0
,D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2206): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84715a8  current_ssid=0x0
,D/wpa_supplicant( 2206): scard is not null..
D/wpa_supplicant( 2206): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2206): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2206): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
,D/wpa_supplicant( 2206): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2206): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2206): wlan0: Cancelling scan request
D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2206): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2206): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2206): RSN: PMKSA cache search - network_ctx=0xb84715a8 try_opportunistic=0
D/wpa_supplicant( 2206): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2206): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2206): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2206): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2206): wlan0: WPA: clearing AP WPA IE,
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 23 c0:ff:d4:d3:aa:4a],
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/wpa_supplicant( 2206): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2206): wlan0: WPA: using GTK CCMP,
,D/wpa_supplicant( 2206): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2206): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2206): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2206): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2206): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2206): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0),
D/wpa_supplicant( 2206): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2206): nl80211: Unsubscribe mgmt frames handle 0xb8470590 (mode change)
D/wpa_supplicant( 2206): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590,
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0c,
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 04 0e,
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=1): 06,
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 0a 07
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 24 38:f8:89:11:e9:11]
D/wpa_supplicant( 2206): nl80211: Register frame type=0xd0 nl_handle=0xb8470590
D/wpa_supplicant( 2206): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2206): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2206):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206):   * freq=2412
,D/wpa_supplicant( 2206):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2206):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2206):   * Auth Type 0
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 25 a0:c5:62:7a:49:97]
D/wpa_supplicant( 2206):   * WPA Versions 0x2
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 26 dc:4a:3e:0f:c2:f1]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 27 44:e9:dd:10:c0:ac]
D/wpa_supplicant( 2206): nl80211: Connect request send successfully
D/wpa_supplicant( 2206): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/Tethering(  964): MasterInitialState.processMessage what=3,
D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 28 06:7c:34:12:7f:81]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 29 64:7c:34:12:7f:81]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 30 64:7c:34:38:27:cc]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 31 06:7c:34:38:27:cc]
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2206): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2206): WPS: Unknown Vendor Extension (Vendor ID 311)
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :false
,D/wpa_supplicant( 2206): nl80211: Event message available
D/wpa_supplicant( 2206): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2206): nl80211: Connect event
D/wpa_supplicant( 2206): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2206): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2206): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2206): wlan0: Association info event
D/wpa_supplicant( 2206): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2206): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2206): wlan0: freq=2412 MHz
D/wpa_supplicant( 2206): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2206): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2206): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2206): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): scard is not null..
D/wpa_supplicant( 2206): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2206): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2206): TDLS: Remove peers on association
D/wpa_supplicant( 2206): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2206): EAPOL: enable timer tick
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2206): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2206): wlan0: Cancelling scan request
,D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2206): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 83 70 bc 2e 71 e7 01 8c 49 d2 a1 8d e6 63 68 ...
D/wpa_supplicant( 2206): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2206): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2206): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2206): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2206): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2206):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2206):   key_nonce - hexdump(len=32): 83 70 bc 2e 71 e7 01 8c 49 d2 a1 8d e6 63 68 0a 6c 59 dc 7c 3d 6a 24 17 8c 83 df d9 0b 90 fc 34
D/wpa_supplicant( 2206):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 83 70 bc 2e 71 e7 01 8c 49 d2 a1 8d e6 63 68 ...
D/wpa_supplicant( 2206): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2206): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2206): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2206): WPA: Renewed SNonce - hexdump(len=32): e0 06 72 d4 ec a3 8f 06 53 c4 37 3f df ef 79 7e 1b d8 56 e2 bb da 63 28 2c 32 cc f6 78 b9 c9 57
D/wpa_supplicant( 2206): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): WPA: Nonce1 - hexdump(len=32): e0 06 72 d4 ec a3 8f 06 53 c4 37 3f df ef 79 7e 1b d8 56 e2 bb da 63 28 2c 32 cc f6 78 b9 c9 57
D/wpa_supplicant( 2206): WPA: Nonce2 - hexdump(len=32): 83 70 bc 2e 71 e7 01 8c 49 d2 a1 8d e6 63 68 0a 6c 59 dc 7c 3d 6a 24 17 8c 83 df d9 0b 90 fc 34
D/wpa_supplicant( 2206): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2206): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2206): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2206): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2206): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2206): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2206): WPA: Derived Key MIC - hexdump(len=16): df 21 55 b1 36 3d 58 c2 05 8d f1 4d ec 6e f8 0f
D/wpa_supplicant( 2206): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 e0 06 72 d4 ec a3 8f 06 53 c4 37 3f df ef 79 ...,
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
,D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4470): isOpenOperator : true
D/wpa_supplicant( 2206): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 83 70 bc 2e 71 e7 01 8c 49 d2 a1 8d e6 63 68 ...
D/wpa_supplicant( 2206): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2206): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2206): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2206): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2206):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2206):   key_nonce - hexdump(len=32): 83 70 bc 2e 71 e7 01 8c 49 d2 a1 8d e6 63 68 0a 6c 59 dc 7c 3d 6a 24 17 8c 83 df d9 0b 90 fc 34
D/wpa_supplicant( 2206):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_rsc - hexdump(len=8): 35 27 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2206):   key_mic - hexdump(len=16): e2 24 b9 c5 8d 96 a7 c2 26 5f 49 b7 39 7b a4 88
D/wpa_supplicant( 2206): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 83 70 bc 2e 71 e7 01 8c 49 d2 a1 8d e6 63 68 ...
D/wpa_supplicant( 2206): RSN: encrypted key data - hexdump(len=56): c7 80 b1 2e ee 6c 15 3b 95 11 12 32 57 8e 53 75 e7 25 40 f2 26 8b 87 2e 68 4a 4b eb fe af d2 1d ...
D/wpa_supplicant( 2206): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2206): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2206): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2206): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 6d 3b ...
D/wpa_supplicant( 2206): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2206): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2206): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2206): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2206): WPA: Derived Key MIC - hexdump(len=16): 7d 6b b4 98 1c 1c 9d bd 8d 65 e2 d6 1d 0c 21 01
,D/wpa_supplicant( 2206): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2206): wlan0: WPA: Installing PTK to the driver
,D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8470c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2206):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 2206): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2206): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2206): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2206): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2206): WPA: RSC - hexdump(len=6): 35 27 00 00 00 00,
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6fb203a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2206):    broadcast key
I/wpa_supplicant( 2206): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2206): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 2206): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2206): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2206): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2206): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2206): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2206): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2206): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state SUCCESS,
D/wpa_supplicant( 2206): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2206): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2206): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2206): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2206): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2206): EAPOL authentication completed successfully
D/wpa_supplicant( 2206): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP]),
D/wpa_supplicant( 2206): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2206): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]],
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection established
,D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2206): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2206): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  964):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  964): ssid=NG700
D/WifiNative-wlan0(  964): id=0
D/WifiNative-wlan0(  964): mode=station
D/WifiNative-wlan0(  964): pairwise_cipher=CCMP
D/WifiNative-wlan0(  964): group_cipher=CCMP
D/WifiNative-wlan0(  964): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  964): wpa_state=COMPLETED
D/WifiNative-wlan0(  964): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  964): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
,E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/AppUp4:CustFacade( 4470): isPhone : true
D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/DhcpStateMachine(  964): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
D/WifiStateMachine(  964): ObtainingIpState{ when=-24ms what=147462 obj=android.net.wifi.StateChangeResult@447059b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-19ms what=147462 obj=android.net.wifi.StateChangeResult@44488560 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-19ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-1ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/LicenseContentProvider( 4492): start selecting data
D/SIMObserver( 4492): simInfo1
I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4470): begin check event
I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity
,I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8112 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/HyLog   ( 8112): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 8112): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 8112): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2206): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2206): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2206): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4328adf8 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
,D/CommandListener(  264): Trying to bring up wlan0
,D/WifiStateMachine(  964): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4328adf8 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
I/LGEmail ( 8112): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-5ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2206): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2206): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2206): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2206): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2206): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2206): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): DHCP successful
D/WifiP2pService(  964): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  527): Reading a NULL string not supported here.
E/Parcel  (  527): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,E/Parcel  (  527): Reading a NULL string not supported here.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
,D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  964): handleMessage: X
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  527): Reading a NULL string not supported here.
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  527): Reading a NULL string not supported here.
,E/Parcel  (  527): Reading a NULL string not supported here.
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1160): handleWifiStateChangedEvent: 1
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/LGEmail ( 8112): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,W/BaseRuntimeLoader( 8112): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 8112): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 8112): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 8112): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 8112): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 8112): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 8112): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4635): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6464): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6464): onReceive CONNECTIVITY_CHANGE networkType=1
,W/linker  ( 8112): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 8112): JNI_OnLoad
,D/HtmlAPI v1.36.23.33395.LG_apps_master( 8112): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 8112): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 8112): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 8112): register_HtmlEditor, Success
D/HtmlEditor( 8112): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 8112): register_HtmlEditorTimer, Success
D/HtmlEditor( 8112): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 8112): register_HtmlEditorDownloader, Success
D/HtmlEditor( 8112): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 8112): register_HtmlEditorFont, Success
D/HtmlEditor( 8112): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 8112): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 8112): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 8112): register_HtmlEditorDrawImage, Success
,D/dalvikvm(  964): GC_EXPLICIT freed 3058K, 47% free 30801K/57964K, paused 5ms+10ms, total 114ms
D/HtmlEditor( 8112): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 8112): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 8112): JNI_OnLoad Success
I/HubEmail( 8112): JNI_OnLoad()
I/HubEmail( 8112): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8112): registerNatives()
I/HubEmail( 8112): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8112): registerNativeMethods()
,I/HubEmail( 8112): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  527): Reading a NULL string not supported here.
,E/Parcel  (  527): Reading a NULL string not supported here.
I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8130 uid=10063 gids={50063, 3003, 1028, 1015}
,E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
E/Parcel  (  527): Reading a NULL string not supported here.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,W/Settings( 8112): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+2ms, total 28ms
,I/ActivityManager(  964): Killing 6760:com.google.android.partnersetup/u0a9 (adj 15): empty #17
V/        (  264): RouteController
D/DhcpStateMachine(  964): DHCP request on wlan0
D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/HyLog   ( 8130): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 8130): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 8130): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 24ms
,V/        (  264): RouteController
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 23ms
,V/        (  264): RouteController
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8166 uid=10066 gids={50066, 4002, 3003, 1028}
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  527): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  527): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  527): |CAC| updateNetCfgInfo
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC|                   Netconfig               
V/QCNEA   (  527): |CAC| *********************************************
V/QCNEA   (  527): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  527): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  527): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  527): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  527): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  527): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  527): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  527): |CAC| net type = 1
V/QCNEA   (  527): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  527): |CAC| Received ssid= NG700
V/QCNEA   (  527): |CAC| 	ssid           =NG700
V/QCNEA   (  527): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  527): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  527): |CAC| *********************************************
D/QCNEA   (  527): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  527): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  527): |CAC| dispatchNetCfg: updating:0xb81708dc
D/QCNEA   (  527): |CAC| readCallback: read len:0, ret:-1, errno:11
,I/ActivityManager(  964): Killing 6558:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 8166): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 8166): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 8166): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  964): Killing 6715:com.google.android.configupdater/u0a3 (adj 15): empty #17
I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=8181 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 8181): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 8181): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 8181): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 8181): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 8181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=8195 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  964): Killing 6868:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 8195): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 8195): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 8195): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 8195): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 8195): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 8195): intf.getDisplayName() = lo
I/Wireless_Storage( 8195): intf.getDisplayName() = sit0
I/Wireless_Storage( 8195): intf.getDisplayName() = p2p0
I/Wireless_Storage( 8195): intf.getDisplayName() = teql0
,I/Wireless_Storage( 8195): intf.getDisplayName() = wlan0
D/NFS     ( 8195): interface name:wlan0 name:wlan0
D/NFS     ( 8195): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 8195): interface name:wlan0 name:wlan0
D/NFS     ( 8195): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 8195): CONNECT : WIFI_CONNECT
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8207 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 6919:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 8207): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 8207): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 8207): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 8207): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WebViewChromium( 8207): Binding Chromium to the main looper Looper (main, tid 1) {42849ac0}
,I/chromium( 8207): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 8207): Initializing chromium process, renderers=0
,I/Adreno-EGL( 8207): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8207): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 8207): Build Date: 01/20/14 Mon
I/Adreno-EGL( 8207): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 8207): Remote Branch: 
I/Adreno-EGL( 8207): Local Patches: 
I/Adreno-EGL( 8207): Reconstruct Branch: 
,W/chromium( 8207): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/wpa_supplicant( 2206): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2206): EAPOL: disable timer tick
,I/NSApplication( 8207): Starting up...
,I/ActivityManager(  964): Killing 6939:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c213b8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 8063): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 8063): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 8063): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 8063): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 8063): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 8063): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 8019): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 8019): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 8063): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 8063): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 8063): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 8063): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  964): handleMessage: X
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
,D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/LicenseContentProvider( 4492): start selecting data
,D/SIMObserver( 4492): simInfo1
,I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4470): begin check event
,I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4470): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4470): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4470): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4470): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4470): handleAsyncCustNotification do not startCustService
,D/EAS     ( 8112): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5065): DownloadService onCreate
,D/EAS     ( 8112): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 8112): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4635): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6464): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6464): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 8181): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 8181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 8195): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 8195): CONNECT : WIFI_CONNECT
,W/Settings( 8112): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 5065): in removeSpuriousFiles
D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a0daf8 on behalf of 5065
,I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 5065): DownloadService onStartCommand
,I/DownloadManager( 5065): in trimDatabase
V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b42248 on behalf of 5065
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42b411d8 on behalf of 5065
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,V/DownloadManager( 5065): DownloadService onDestroy
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/LicenseContentProvider( 4492): start selecting data
,D/SIMObserver( 4492): simInfo1
,I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4470): begin check event
,I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5065): DownloadService onCreate
,D/EAS     ( 8112): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 5065): in removeSpuriousFiles
D/EAS     ( 8112): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a7b260 on behalf of 5065
,I/DownloadManager( 5065): in trimDatabase
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a7cb38 on behalf of 5065
,V/DownloadManager( 5065): DownloadService onStartCommand
,V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42a8e5f0 on behalf of 5065
I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4635): networkInfo.isConnected() = true
,D/PhoneState( 4635): setPdpRejectCasuse : false
,W/Settings( 8112): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 6464): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6464): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5065): DownloadService onDestroy
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 8181): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 8181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 8195): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 8195): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1542): Connected
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1542): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4470): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4470): onReceive
,D/AppUp4:CustFacade( 4470): Context : android.app.ReceiverRestrictedContext@42863f10
D/AppUp4:CustFacade( 4470): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4470): isOpenOperator : true
,D/AppUp4:CustFacade( 4470): isPhone : true
,I/LicenseContentProvider( 4492): start selecting data
,D/SIMObserver( 4492): simInfo1
,I/AppUp4:EulaManager( 4470): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4470): begin check event
,I/AppUp4:CustModeStarterReceiver( 4470): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 8112): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5065): DownloadService onCreate
,D/EAS     ( 8112): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4635): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4635): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4635): networkInfo.isConnected() = true
,D/PhoneState( 4635): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6464): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6464): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 8112): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMSGCM( 8181): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 8181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 8195): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 8195): CONNECT : WIFI_CONNECT
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/DownloadManager( 5065): in removeSpuriousFiles
,V/DownloadManager( 5065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429b7d50 on behalf of 5065
,D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 5065): in trimDatabase
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@429b93f8 on behalf of 5065
V/DownloadManager( 5065): DownloadService onStartCommand
V/DownloadManager( 5065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 5065): created cursor android.database.sqlite.SQLiteCursor@42aad548 on behalf of 5065
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 5065): DownloadService onDestroy
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 8207): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452525039131299955; DSPS: 62293426; Offset: 1452523138086805327
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452525059133181944; DSPS: 62948848; Offset: 1452523138086795226
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452525060048, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1452525060055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452525079134656314; DSPS: 63604256; Offset: 1452523138086804752
,TIME-OUT KILL (timeout was 1800000ms)
```
