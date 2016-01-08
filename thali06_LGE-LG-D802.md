#### Test 5546736337bcedb_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/Vision  ( 1965): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1965): No vision deps
V/ConfigFetchTask( 1965): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UBWiwhHtU1MWUC8ur9TtRxJ4r68oLXDGSqDAKl8njvxlc9YAsg9t3qai2QjLwouEdeux4b7BfyMW9Xucv5AtXpcxLMlyfwC_h_Z78ihH0U2WKRmWTd4UFWiRpZlZpwzQZejoiitt76jhnSlH_Kd7HoS1pWgPOJka4HVrK0-SLNF0hnhexFuybf9RzsTNoO_GYsZSOj
I/PeopleContactsSync( 1965): CP2 sync disabled
I/GoogleURLConnFactory( 1965): Using platform SSLCertificateSocketFactory
I/dalvikvm( 1965): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1965): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1965): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1965): Using Auth Proxy for data requests.
W/BaseAppContext( 1965): Using Auth Proxy for data requests.
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/BaseAppContext( 1965): Using Auth Proxy for data requests.
W/BaseAppContext( 1965): Using Auth Proxy for data requests.
W/BaseAppContext( 1965): Using Auth Proxy for data requests.
W/BaseAppContext( 1965): Using Auth Proxy for data requests.
,W/GAV2    ( 4632): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  964): Killing 3986:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{430aec98 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1551): GC_EXPLICIT freed 1030K, 29% free 17824K/24832K, paused 1ms+3ms, total 23ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1965): GC_CONCURRENT freed 1587K, 22% free 19462K/24832K, paused 1ms+6ms, total 49ms
D/dalvikvm( 1965): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 1965): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/ChimeraCfgMgr( 1965): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1965): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4682): 
D/AndroidRuntime( 4682): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/AndroidRuntime( 4682): CheckJNI is OFF
D/dalvikvm( 4682): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4682): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4682): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4682): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4682): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/ConfigFetchService( 1965): fetch service done; releasing wakelock
I/ConfigFetchService( 1965): stopping self
D/dalvikvm( 4682): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1965): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1965): Loaded CLD2 Version V2.0 - 20141016
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Icing   ( 1965): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/memtrack( 4682): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4682): failed to load memtrack module: -2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4682): Calling main entry com.android.commands.am.Am
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4682
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (132 us)
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{430aec98 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  964): resumeTopActivityLocked: Pausing null
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  964): setFocusedStack: mFocusedStack=ActivityStack{43157d08 stackId=1, 2 tasks}
I/ActivityManager(  964): startService SlideAside
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/UsbSettingsControl( 2584): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2584): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4682): Shutting down VM
D/dalvikvm( 4682): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 2ms
I/SlideAside( 4066): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{430aec98 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{430aec98 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Restarting ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4717 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 4066): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4066): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4717): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4717): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4717): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/WebViewChromium( 4717): Binding Chromium to the background looper Looper (main, tid 1) {428b0920}
I/chromium( 4717): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4717): Initializing chromium process, renderers=0
W/chromium( 4717): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4717): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4717): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4717): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4717): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4717): Remote Branch: 
I/Adreno-EGL( 4717): Local Patches: 
I/Adreno-EGL( 4717): Reconstruct Branch: 
I/dalvikvm( 4717): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4717): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4717): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4717): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4717): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4717): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4717): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4717): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4717): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4717): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4717): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4717): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4717): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4717): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4717): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4717): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4717): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4717): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4717): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4717): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4717): Enabling debug mode 0
W/AwContents( 4717): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +382ms
W/AwContents( 4717): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  964): IME STATUS OFF
I/ActivityManager( 4717): Timeline: Activity_idle id: android.os.BinderProxy@428b20f0 time:107569
D/JsMessageQueue( 4717): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4717): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428b61d0
D/dalvikvm( 4717): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428b61d0
D/jxcore_app_log( 4717): JniHelper::setJavaVM(0x4177d838), pthread_self() = 1631520312
D/JX-Cordova( 4717): jxcore cordova android initializing
I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3} time:107934
D/ActivityManager(  964): no-history finish of ActivityRecord{430aec98 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  964): Finishing activity token=Token{42c01de0 ActivityRecord{430aec98 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{430aec98 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{430aec98 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2584): [AUTORUN] onStop()
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{430aec98 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4717): GC_CONCURRENT freed 2761K, 12% free 21884K/24832K, paused 2ms+1ms, total 49ms
,D/dalvikvm( 4717): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 4717): GC_FOR_ALLOC freed 130K, 12% free 21864K/24832K, paused 22ms, total 22ms
,D/dalvikvm( 4717): GC_FOR_ALLOC freed 127K, 12% free 21883K/24832K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 23.635MB for 96598-byte allocation
,D/dalvikvm( 4717): GC_FOR_ALLOC freed 180K, 13% free 21917K/24928K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 23.715MB for 144892-byte allocation
,D/dalvikvm( 4717): GC_FOR_ALLOC freed 251K, 13% free 21968K/25072K, paused 20ms, total 21ms
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 23.833MB for 217334-byte allocation
,D/dalvikvm( 4717): GC_FOR_ALLOC freed 373K, 13% free 22040K/25288K, paused 20ms, total 21ms
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 24.007MB for 325996-byte allocation
,D/dalvikvm( 4717): GC_FOR_ALLOC freed 570K, 14% free 22161K/25608K, paused 21ms, total 22ms
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 24.282MB for 488990-byte allocation
,D/dalvikvm( 4717): GC_FOR_ALLOC freed 870K, 15% free 22338K/26088K, paused 24ms, total 24ms
,D/dalvikvm( 4717): GC_FOR_ALLOC freed 1288K, 14% free 22595K/26088K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 25.289MB for 1100216-byte allocation
,D/dalvikvm( 4717): GC_CONCURRENT freed 1730K, 16% free 23032K/27164K, paused 2ms+4ms, total 40ms
,D/dalvikvm( 4717): GC_FOR_ALLOC freed 328K, 16% free 22920K/27164K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 26.130MB for 1650320-byte allocation
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm( 4717): GC_CONCURRENT freed 1605K, 19% free 23489K/28776K, paused 2ms+11ms, total 39ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/dalvikvm( 4717): GC_FOR_ALLOC freed 1415K, 19% free 23569K/28776K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 27.551MB for 2475476-byte allocation
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2034): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2034): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/dalvikvm( 4717): GC_CONCURRENT freed 1870K, 22% free 24367K/31196K, paused 3ms+4ms, total 43ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4717): GC_CONCURRENT freed 2481K, 22% free 24520K/31196K, paused 1ms+4ms, total 37ms
D/dalvikvm( 4717): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/dalvikvm( 4717): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/dalvikvm( 4717): GC_FOR_ALLOC freed 468K, 22% free 24408K/31196K, paused 23ms, total 23ms
I/dalvikvm-heap( 4717): Grow heap (frag case) to 29.550MB for 3713210-byte allocation
D/dalvikvm( 4717): GC_CONCURRENT freed 287K, 20% free 28019K/34824K, paused 2ms+2ms, total 39ms
D/dalvikvm( 4717): GC_FOR_ALLOC freed 3142K, 27% free 25504K/34824K, paused 23ms, total 23ms
W/jxcore-log( 4717): Initializing JXcore engine
W/jxcore-log( 4717): JXcore engine is ready
D/dalvikvm( 4717): GC_CONCURRENT freed 325K, 20% free 28173K/34824K, paused 1ms+1ms, total 25ms
D/dalvikvm( 4717): WAIT_FOR_CONCURRENT_GC blocked 23ms
W/jxcore-log( 4717): Starting JXcore engine
W/jxcore-log( 4717): Platform android
W/jxcore-log( 4717): 
W/jxcore-log( 4717): Process ARCH arm
W/jxcore-log( 4717): 
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4717): JXcore Cordova bridge is ready!
I/jxcore-log( 4717): 
,W/jxcore-log( 4717): JXcore engine is started
,I/chromium( 4717): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4717): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4717): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4632): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4717): Toggling radios to true
I/jxcore-log( 4717): 
,D/BluetoothManagerService(  964): Message: 20
,D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44f28150:true
,D/BluetoothAdapter( 4717): enable(): BT is already enabled..!
,D/WifiStateMachine(  964): handleMessage: E msg.what=131145
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doBoolean: DISCONNECT
D/WifiService(  964): New client listening to asynchronous messages
D/WifiService(  964): setWifiEnabled: true pid=4717, uid=10304
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  964): setWifiEnabled startWifiDelaySendMsg true
,D/WifiService(  964): disconnect pid=4717, uid=10304
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2034): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2034): wlan0: Cancelling scan request
D/wpa_supplicant( 2034): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2034): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2034): TDLS: Tear down peers
,D/wpa_supplicant( 2034): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4717): Radios toggled
I/jxcore-log( 4717): 
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4717): Received device characteristics:
I/jxcore-log( 4717): Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4717): Bluetooth name: Thali Test's G2
I/jxcore-log( 4717): Device name: LGE-LG-D802
I/jxcore-log( 4717): 
,I/jxcore-log( 4717): Perf Test app loaded loaded
I/jxcore-log( 4717): 
,D/WifiService(  964): reconnect pid=4717, uid=10304
D/wpa_supplicant( 2034): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2034): wlan0: Deauthentication notification
D/wpa_supplicant( 2034): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2034): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2034): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2034): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2034): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2034): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb83c1d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2034):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2034): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2034): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2034): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2034): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2034): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOW,ER_UP])
D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2034): nl80211: Event message available
D/wpa_supplicant( 2034): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2034): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): transitionTo: destState=DisconnectingState
,D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
W/Settings(  964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectingState
I/chromium( 4717): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131146
D/WifiStateMachine(  964): processMsg: DisconnectingState
I/Choreographer( 4717): Skipped 74 frames!  The application may be doing too much work on its main thread.
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiNative-wlan0(  964): doBoolean: RECONNECT
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2034): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2034): Fast associate: Old scan results
D/wpa_supplicant( 2034): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2034): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2034): wlan0: nl80211: scan request
D/wpa_supplicant( 2034): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2034): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2034): nl80211: Event message available
D/wpa_supplicant( 2034): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2034): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  964): handleMessage: E msg.what=147460
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection lost
D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2034): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2034): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2034): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
,D/DhcpStateMachine(  964): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4717): check test folder
I/jxcore-log( 4717): 
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 4717): found test : ./testFindPeers.js
I/jxcore-log( 4717): 
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  964): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
D/QCNEA   (  611): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  611): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  611): |CAC| updateNetCfgInfo
V/QCNEA   (  611): |CAC| *********************************************
V/QCNEA   (  611): |CAC|                   Netconfig               
V/QCNEA   (  611): |CAC| *********************************************
V/QCNEA   (  611): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  611): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  611): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  611): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  611): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  611): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  611): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  611): |CAC| *********************************************
D/QCNEA   (  611): |CAC| Received bssid= 
D/QCNEA   (  611): |CAC| net type = 3
V/QCNEA   (  611): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  611): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  611): |CAC| 	ssid           =NG700
V/QCNEA   (  611): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  611): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  611): |CAC| *********************************************
D/QCNEA   (  611): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  611): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  611): |CAC| dispatchNetCfg: updating:0xb70968dc
,D/QCNEA   (  611): |CAC| readCallback: read len:0, ret:-1, errno:11
D/WifiHS20(  964): hidePasspointNotification off =false
D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: DisconnectingState
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
E/Parcel  (  611): Reading a NULL string not supported here.
,E/Parcel  (  611): Reading a NULL string not supported here.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 0
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/jxcore-log( 4717): found test : ./testSendData.js
I/jxcore-log( 4717): 
D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131213
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4782 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
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
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): handleMessage: X
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,D/HyLog   ( 4782): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4782): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4782): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/PCSuite ( 4782): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  271): RouteController
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x628d95f8 clazz=0x6c800001 iface=wlan0 mask=0x3
,D/PCSuite ( 4782): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4782): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
,I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4817 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  964): Killing 4193:com.google.android.talk/u0a77 (adj 15): empty #17
,V/NativeCrypto( 1551): Read error: ssl=0x61013850: I/O error during system call, Connection timed out
,V/NativeCrypto( 1551): SSL shutdown failed: ssl=0x61013850: I/O error during system call, Broken pipe
,I/ConfigService( 1551): onDestroy
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4817): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4817): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4817): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 4817): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4817): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4817): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4817): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4817): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4817): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4817): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4817): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4817): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 3103:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  964): StoppedState
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.457458 Y: -0.415558 Z: 9.797592 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457458 .y:-0.415558 .z:9.797592
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.439377 Y: -0.425049 Z: 9.817215 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.439377 .y:-0.425049 .z:9.817215
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2034): nl80211: Event message available
D/wpa_supplicant( 2034): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2034): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2034): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2034): nl80211: Received scan results (14 BSSes)
D/wpa_supplicant( 2034): nl80211: Survey data missing
D/wpa_supplicant( 2034): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 8 BSSID 64:7c:34:b0:03:6e SSID 'UPC4688432'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 9 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 10 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 11 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 12 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 13 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 14 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): BSS: last_scan_res_used=14/32 last_scan_full=0
D/wpa_supplicant( 2034): wlan0: New scan results available
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2034): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2034): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2034): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 2034): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2034): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2034): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2034): WPS: AP 44:e9:dd:10:c0:ac type 0 added
D/wpa_supplicant( 2034): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2034): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2034): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago, blacklist=0
D/wpa_supplicant( 2034): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[5] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[7] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[8] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[9] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2034): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2034): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2034): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2034): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700',
,D/wpa_supplicant( 2034): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2034): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2034): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2034): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 2034): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2034): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2034): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb83c35a8  current_ssid=0x0
,D/wpa_supplicant( 2034): scard is not null..
,D/wpa_supplicant( 2034): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING,
D/wpa_supplicant( 2034): wpa_supplicant_check_mdm_ac_policy policy: 0,
,D/wpa_supplicant( 2034): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2034): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2034): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 2034): wlan0: [MDM] lg mdm allow/disallow auto connect is not set ,
,D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00,
,D/wpa_supplicant( 2034): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2034): TDLS: TDLS is allowed in the target BSS
,I/wpa_supplicant( 2034): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2034): wlan0: Cancelling scan request
D/wpa_supplicant( 2034): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
D/wpa_supplicant( 2034): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2034): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2034): RSN: PMKSA cache search - network_ctx=0xb83c35a8 try_opportunistic=0
D/wpa_supplicant( 2034): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2034): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2034): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2034): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2034): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2034): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2034): wlan0: WPA: using GTK CCMP,
D/wpa_supplicant( 2034): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2034): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2034): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2034): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2034): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE,
D/wpa_supplicant( 2034): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2034): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
,D/wpa_supplicant( 2034): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2034): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2034): nl80211: Unsubscribe mgmt frames handle 0xb83c2590 (mode change)
D/wpa_supplicant( 2034): nl80211: Subscribe to mgmt frames with non-AP handle 0xb83c2590,
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 04 0b,
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09,
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 04 0e
,D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 0a 07,
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2034): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2034):   * bssid=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2034):   * freq=2412
D/wpa_supplicant( 2034):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2034):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2034):   * Auth Type 0
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 64:7c:34:b0:03:6e]
D/wpa_supplicant( 2034):   * WPA Versions 0x2
D/wpa_supplicant( 2034): nl80211: Connect request send successfully
D/wpa_supplicant( 2034): wlan0: Setting authentication timeout: 10 sec 0 usec,
D/wpa_supplicant( 2034): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2034): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): EAPOL: External notification - portControl=Auto
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 a0:c5:62:7a:49:96]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 44:e9:dd:10:c0:ac]
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
,D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 00:37:b7:9d:3e:73]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 44:e9:dd:10:c0:ab]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 14 44:e9:dd:10:c0:ad]
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2034): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4041): onReceive
,D/AppUp4:CustFacade( 4041): Context : android.app.ReceiverRestrictedContext@428cdfe0
,D/AppUp4:CustFacade( 4041): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4041): isOpenOperator : true
,D/AppUp4:CustFacade( 4041): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,D/wpa_supplicant( 2034): nl80211: Event message available
D/wpa_supplicant( 2034): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2034): nl80211: Connect event
D/wpa_supplicant( 2034): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2034): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2034): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2034): wlan0: Association info event
D/wpa_supplicant( 2034): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2034): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2034): wlan0: freq=2412 MHz
D/wpa_supplicant( 2034): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2034): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2034): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2034): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2034): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2034): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): scard is not null..
D/wpa_supplicant( 2034): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2034): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2034): TDLS: Remove peers on association
D/wpa_supplicant( 2034): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2034): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2034): EAPOL: enable timer tick
D/wpa_supplicant( 2034): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2034): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2034): wlan0: Cancelling scan request
,D/wpa_supplicant( 2034): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,I/AppUp4:EulaManager( 4041): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4041): begin check event
,I/AppUp4:CustModeStarterReceiver( 4041): Event For GoodConnectivity
,D/wpa_supplicant( 2034): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 83 15 1b a6 da 73 f9 3f d8 bb 7c 7b 4e 55 59 ...
D/wpa_supplicant( 2034): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2034): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2034): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2034): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2034): wlan0:   key_length=16 key_data_length=0
,D/wpa_supplicant( 2034):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2034):   key_nonce - hexdump(len=32): 83 15 1b a6 da 73 f9 3f d8 bb 7c 7b 4e 55 59 12 84 65 ba 17 d0 29 a3 2c cd e8 00 97 ca a8 07 c4
D/wpa_supplicant( 2034):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 83 15 1b a6 da 73 f9 3f d8 bb 7c 7b 4e 55 59 ...
D/wpa_supplicant( 2034): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2034): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2034): Get randomness: len=32 entropy=11
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2034): WPA: Renewed SNonce - hexdump(len=32): 36 17 ed b3 84 ee 1a 0e 2d 32 33 08 15 29 1e 3f f5 d4 87 a5 f0 2a 4b 90 cc ec e9 a1 b8 7c d2 c7
D/wpa_supplicant( 2034): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): WPA: Nonce1 - hexdump(len=32): 36 17 ed b3 84 ee 1a 0e 2d 32 33 08 15 29 1e 3f f5 d4 87 a5 f0 2a 4b 90 cc ec e9 a1 b8 7c d2 c7
D/wpa_supplicant( 2034): WPA: Nonce2 - hexdump(len=32): 83 15 1b a6 da 73 f9 3f d8 bb 7c 7b 4e 55 59 12 84 65 ba 17 d0 29 a3 2c cd e8 00 97 ca a8 07 c4
D/wpa_supplicant( 2034): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2034): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2034): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2034): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
,D/wpa_supplicant( 2034): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2034): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2034): WPA: Derived Key MIC - hexdump(len=16): 57 04 fa a5 2d 1e 76 e0 5d 43 e4 af 86 fa 98 7d
,D/wpa_supplicant( 2034): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 36 17 ed b3 84 ee 1a 0e 2d 32 33 08 15 29 1e ...
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4863 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/wpa_supplicant( 2034): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 83 15 1b a6 da 73 f9 3f d8 bb 7c 7b 4e 55 59 ...
D/wpa_supplicant( 2034): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2034): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2034): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2034): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2034):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2034):   key_nonce - hexdump(len=32): 83 15 1b a6 da 73 f9 3f d8 bb 7c 7b 4e 55 59 12 84 65 ba 17 d0 29 a3 2c cd e8 00 97 ca a8 07 c4
D/wpa_supplicant( 2034):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_rsc - hexdump(len=8): f3 20 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_mic - hexdump(len=16): 7f fd bd 23 7f 8f a6 35 ef cc 05 60 6c 95 cd 79
D/wpa_supplicant( 2034): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 83 15 1b a6 da 73 f9 3f d8 bb 7c 7b 4e 55 59 ...
D/wpa_supplicant( 2034): RSN: encrypted key data - hexdump(len=56): 9f 5a f2 7a 4f aa 0f 21 be a4 aa d0 ca e8 d2 03 81 50 78 0d bd 1f 88 ae ed 6f 4a 90 b5 18 6e e7 ...
,D/wpa_supplicant( 2034): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2034): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2034): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2034): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 22 85 ...
D/wpa_supplicant( 2034): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2034): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2034): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2034): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2034): WPA: Derived Key MIC - hexdump(len=16): 06 4f e9 51 59 b9 66 64 07 6f 6f 7b c0 fc 2c c8
D/wpa_supplicant( 2034): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2034): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb83c2c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2034):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 2034): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2034): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2034): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2034): WPA: RSC - hexdump(len=6): f3 20 00 00 00 00
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f3603a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2034):    broadcast key
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
I/wpa_supplicant( 2034): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2034): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
I/wpa_supplicant( 2034): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2034): netlink: Operstate: linkmode=-1, operstate=6
D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2034): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2034): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2034): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2034): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2034): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2034): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2034): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2034): EAPOL authentication completed successfully
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4863): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): Network connection established
,D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2034): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
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
I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  964): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-9ms what=147462 obj=android.net.wifi.StateChangeResult@44f7a978 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-7ms what=147462 obj=android.net.wifi.StateChangeResult@43e35ab0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WifiStateMachine(  964): processMsg: ConnectModeState
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-8ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2034): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2034): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
,D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
,E/Parcel  (  611): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
V/DownloadManager( 4863): DownloadService onCreate
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,I/DownloadManager( 4863): in removeSpuriousFiles
,D/EAS     ( 4615): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4615): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/DownloadManager( 4863): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/eas_req ( 4615): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@428f69a0 on behalf of 4863
V/DownloadManager( 4863): DownloadService onStartCommand
I/DownloadManager( 4863): in trimDatabase
V/DownloadManager( 4863): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4863): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@428fad18 on behalf of 4863
I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4387): networkInfo.isConnected() = false
V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@428fb460 on behalf of 4863
W/linker  ( 4615): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4615): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4615): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4615): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4615): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4615): register_HtmlEditor, Success
D/HtmlEditor( 4615): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4615): register_HtmlEditorTimer, Success
D/HtmlEditor( 4615): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4615): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4615): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4615): register_HtmlEditorFont, Success
D/HtmlEditor( 4615): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4615): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4615): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4615): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4615): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4615): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4615): JNI_OnLoad Success
D/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2034): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2034): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2034): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,I/HubEmail( 4615): JNI_OnLoad()
V/DownloadManager( 4863): DownloadService onDestroy
,D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
I/HubEmail( 4615): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd: failed to issue private commands
I/HubEmail( 4615): registerNatives()
I/HubEmail( 4615): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4615): registerNativeMethods()
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
,I/HubEmail( 4615): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,W/Settings( 4615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4889 uid=10052 gids={50052, 3003}
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432850e8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432850e8 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  271): Setting iface cfg
D/WifiStateMachine(  964): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/CommandListener(  271): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
D/HyLog   ( 4889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4889): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
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
D/WifiStateMachine(  964): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2034): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2034): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2034): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
I/ActivityManager(  964): Killing 3886:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): DHCP successful
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
,D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
,D/WifiStateMachine(  964): processMsg: VerifyingLinkState
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
E/Parcel  (  611): Reading a NULL string not supported here.
,D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState enter
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
V/LGRssiData( 4889): [loadRssi] File not exist 
V/LGRssiData( 4889): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4889): [loadFeatureFromXml] *** start feature loading from xml
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
W/BaseRuntimeLoader( 4889): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4889): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
W/BaseRuntimeLoader( 4889): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,W/BaseRuntimeLoader( 4889): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  611): Reading a NULL string not supported here.
,E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
V/TelephonyAutoProfiling( 4889): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4889): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4889): [getValue] FEATURE key : vzw_roaming_state, value : null
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 1
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/MobileConnectivityChangeReceiver( 4889): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
D/MobileConnectivityChangeReceiver( 4889): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,E/Parcel  (  611): Reading a NULL string not supported here.
E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4904 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 4363:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,E/PhoneMonitor( 4889): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4889): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,V/        (  271): RouteController
,V/        (  271): RouteController
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
V/        (  271): RouteController
V/        (  271): RouteController
D/HyLog   ( 4904): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4904): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4904): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  271): RouteController
,V/        (  271): RouteController
,I/CheckinService( 1965): Checking schedule, now: 1452264625378 next: 1452264571372
,I/CheckinService( 1965): active receiver: enabled
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,D/QCNEA   (  611): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  611): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  611): |CAC| updateNetCfgInfo
V/QCNEA   (  611): |CAC| *********************************************
V/QCNEA   (  611): |CAC|                   Netconfig               
V/QCNEA   (  611): |CAC| *********************************************
V/QCNEA   (  611): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  611): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  611): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  611): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  611): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  611): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  611): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  611): |CAC| *********************************************
D/QCNEA   (  611): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  611): |CAC| net type = 1
V/QCNEA   (  611): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  611): |CAC| Received ssid= NG700
V/QCNEA   (  611): |CAC| 	ssid           =NG700
V/QCNEA   (  611): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  611): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  611): |CAC| *********************************************
D/QCNEA   (  611): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  611): |CAC| dispatching netcfgupdate for wlan
,D/QCNEA   (  611): |CAC| dispatchNetCfg: updating:0xb70968dc
,D/QCNEA   (  611): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/CheckinService( 1965): Preparing to send checkin request
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/EventLogService( 1965): Accumulating logs since 1452264538489
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4933 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  964): Killing 4538:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/CheckinRequestBuilder( 1965): Checkin reason type: 8 attempt count: 1
,D/DhcpStateMachine(  964): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  964): GC_EXPLICIT freed 23551K, 49% free 29765K/57860K, paused 4ms+7ms, total 130ms
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/HyLog   ( 4933): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4933): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4933): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
E/ActivityThread( 1965): Failed to find provider info for com.google.android.wearable.settings
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  964): Killing 4573:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4954 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 4954): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4954): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4954): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4954): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4968 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  964): Killing 4602:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
,D/HyLog   ( 4968): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4968): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4968): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 4968): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4968): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4968): intf.getDisplayName() = lo
I/Wireless_Storage( 4968): intf.getDisplayName() = sit0
I/Wireless_Storage( 4968): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4968): intf.getDisplayName() = teql0
I/Wireless_Storage( 4968): intf.getDisplayName() = wlan0
D/NFS     ( 4968): interface name:wlan0 name:wlan0
,D/NFS     ( 4968): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4968): interface name:wlan0 name:wlan0
D/NFS     ( 4968): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4968): CONNECT : WIFI_CONNECT
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4980 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 4243:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4980): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4980): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4980): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/GAV2    ( 4980): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x432a8380: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1965): awaiting user notification for token
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4998 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4998): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4998): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4998): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  275): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 21ms
,W/dalvikvm( 4998): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4998): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4998): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4998): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4998): VFY: replacing opcode 0x62 at 0x005e
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
I/MultiDex( 4998): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4998): install
,I/MultiDex( 4998): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4998): loading existing secondary dex files
,I/MultiDex( 4998): load found 3 secondary dex files
,I/MultiDex( 4998): install done
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,V/WebViewChromium( 4980): Binding Chromium to the main looper Looper (main, tid 1) {428ba5e0}
,I/chromium( 4980): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4980): Initializing chromium process, renderers=0
D/dalvikvm( 4998): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4998): VFY: unable to resolve instance field 61
,D/dalvikvm( 4998): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4998): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4998): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4998): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4998): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4998): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4998): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4998): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4998): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4998): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428c1830
D/dalvikvm( 4998): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428c1830
,D/dalvikvm( 4998): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428c1830, skipping init
,D/dalvikvm( 4998): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428c1830
D/dalvikvm( 4998): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428c1830
,V/JNIHelp ( 4998): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/chromium( 4980): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4980): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4980): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4980): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4980): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4980): Remote Branch: 
I/Adreno-EGL( 4980): Local Patches: 
I/Adreno-EGL( 4980): Reconstruct Branch: 
,D/dalvikvm( 4998): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428c1830
,D/dalvikvm( 4998): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428c1830
D/dalvikvm( 4998): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428c1830
,D/dalvikvm( 4998): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428c1830
,I/NSApplication( 4980): Starting up...
,I/ActivityManager(  964): Killing 4258:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4817): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4817): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4817): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4817): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4817): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4817): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4782): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4782): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4817): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4817): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4817): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/ProviderInstaller( 4998): Installed default security provider GmsCore_OpenSSL
,I/QRemote ( 4817): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1551): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1551): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1551): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1965): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WearableService( 1875): callingUid 10006, callindPid: 1875
,E/MDM     ( 1423): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 4998): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4998): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4998): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1965): Restart initialization of location
,I/dalvikvm( 4998): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4998): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4998): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d76000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d76000
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=348564258
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2034): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2034): EAPOL: disable timer tick
,D/dalvikvm( 4998): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a94208
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4998): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a94208
D/dalvikvm( 4998): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a94208, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/dalvikvm( 4998): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5053): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4998): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4998): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 61ms
,I/Adreno-EGL( 4998): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4998): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4998): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4998): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4998): Remote Branch: 
I/Adreno-EGL( 4998): Local Patches: 
I/Adreno-EGL( 4998): Reconstruct Branch: 
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  278): PrepareKeyRequest: nonce=597075513
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/dalvikvm( 4717): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4717): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4717): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4717): BLE is supported
I/jxcore-log( 4717): 
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,W/Settings( 4998): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4998): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4998): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4998): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4998): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4998): Remote Branch: 
I/Adreno-EGL( 4998): Local Patches: 
I/Adreno-EGL( 4998): Reconstruct Branch: 
,I/Adreno-EGL( 4998): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4998): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4998): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4998): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4998): Remote Branch: 
I/Adreno-EGL( 4998): Local Patches: 
I/Adreno-EGL( 4998): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1965): Classify the device as Phone.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,I/CheckinTask( 1965): Sending checkin request (11466 bytes)
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1965): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1965): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1965): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x44f78068: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1965): Classify the device as Phone.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/CheckinTask( 1965): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinService( 1965): Checking schedule, now: 1452264627950 next: 1452842023944
,I/CheckinService( 1965): active receiver: disabled
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1155): GC_CONCURRENT freed 2912K, 11% free 25443K/28532K, paused 2ms+3ms, total 34ms
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1551): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2034): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2034): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  611): Reading a NULL string not supported here.
,E/Parcel  (  611): Reading a NULL string not supported here.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1551): Connected
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1551): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4041): onReceive
D/AppUp4:CustFacade( 4041): Context : android.app.ReceiverRestrictedContext@428cdfe0
D/AppUp4:CustFacade( 4041): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4041): isOpenOperator : true
,D/AppUp4:CustFacade( 4041): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,I/AppUp4:EulaManager( 4041): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4041): begin check event
I/AppUp4:CustModeStarterReceiver( 4041): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4041): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4041): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4041): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4041): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4041): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4863): DownloadService onCreate
,I/DownloadManager( 4863): in removeSpuriousFiles
,V/DownloadManager( 4863): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@42901480 on behalf of 4863
D/EAS     ( 4615): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4615): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4863): in trimDatabase
,D/eas_req ( 4615): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4863): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@42902550 on behalf of 4863
I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4387): networkInfo.isConnected() = false
,W/Settings( 4615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4889): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4889): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4863): DownloadService onStartCommand
,V/DownloadManager( 4863): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4954): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4968): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4968): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@42904fe8 on behalf of 4863
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 4863): DownloadService onDestroy
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Tethering(  964): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4041): onReceive
,D/AppUp4:CustFacade( 4041): Context : android.app.ReceiverRestrictedContext@428cdfe0
D/AppUp4:CustFacade( 4041): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4041): isOpenOperator : true
,D/AppUp4:CustFacade( 4041): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,I/AppUp4:EulaManager( 4041): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4041): begin check event
,I/AppUp4:CustModeStarterReceiver( 4041): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4863): DownloadService onCreate
,D/EAS     ( 4615): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 4863): in removeSpuriousFiles
,D/EAS     ( 4615): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4863): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4863): DownloadService onStartCommand
,V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@42909f10 on behalf of 4863
I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4387): networkInfo.isConnected() = true
,D/PhoneState( 4387): setPdpRejectCasuse : false
V/DownloadManager( 4863): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4863): in trimDatabase
V/DownloadManager( 4863): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,W/Settings( 4615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4889): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4889): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@4290c8a8 on behalf of 4863
,V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@4290c690 on behalf of 4863
,V/DownloadManager( 4863): DownloadService onDestroy
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4954): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/NFS     ( 4968): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4968): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  964): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WifiController(  964): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4041): onReceive
,D/AppUp4:CustFacade( 4041): Context : android.app.ReceiverRestrictedContext@428cdfe0
,D/AppUp4:CustFacade( 4041): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4041): isOpenOperator : true
,D/AppUp4:CustFacade( 4041): isPhone : true
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,I/AppUp4:EulaManager( 4041): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4041): begin check event
,I/AppUp4:CustModeStarterReceiver( 4041): Event For GoodConnectivity, noConnectivity : false, but skip! 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4863): DownloadService onCreate
,D/EAS     ( 4615): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4615): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4863): in removeSpuriousFiles
,V/DownloadManager( 4863): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1224): Disconnected process message: 10
V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@42910f38 on behalf of 4863
I/DownloadManager( 4863): in trimDatabase
V/DownloadManager( 4863): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4387): networkInfo.isConnected() = true
,D/PhoneState( 4387): setPdpRejectCasuse : false
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/WifiController(  964): battery changed pluggedType: 2
,D/dalvikvm(  964): GC_EXPLICIT freed 2207K, 49% free 29659K/57860K, paused 4ms+8ms, total 120ms
,V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@42912910 on behalf of 4863
,V/DownloadManager( 4863): DownloadService onStartCommand
,V/DownloadManager( 4863): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/MobileConnectivityChangeReceiver( 4889): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4889): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4863): created cursor android.database.sqlite.SQLiteCursor@42914ac0 on behalf of 4863
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4863): DownloadService onDestroy
,D/LGDMSGCM( 4954): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4968): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4968): CONNECT : WIFI_CONNECT
W/ContextImpl( 4954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4980): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2034): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2034): nl80211: survey data missing!
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  611): Reading a NULL string not supported here.
,E/Parcel  (  611): Reading a NULL string not supported here.
,D/WifiStateMachine(  964): handleMessage: X
,D/Finsky  ( 4278): [402] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4278): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  293): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  964): Killing 4632:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2034): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2034): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5185 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/administrator(  964): Handling package changes for user 0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
E/SlideAside( 4066): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/SlideAside( 4066): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/PackageManager(  964):   Scheme: "mmsto"
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,D/HyLog   ( 5185): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5185): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5185): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Babel   ( 5185): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5185): MmsConfig.loadMmsSettings
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/MediaCodecList( 5185): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5185): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5185): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 5185): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Babel   ( 5185): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5185): MmsConfig.loadFromDatabase
D/WifiController(  964): battery changed pluggedType: 2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/BaseRuntimeLoader( 5185): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5185): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5185): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5185): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5185): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5185): MmsConfig.loadFromResources
W/Settings( 5185): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 5185): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5185): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 5185): [loadRssi] File not exist 
,V/LGRssiData( 5185): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5185): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:Utils( 4041): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4041): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 4041): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/TelephonyAutoProfiling( 5185): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5185): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5185): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/AppUp4:CustModeStarterReceiver( 4041): onReceive
,D/AppUp4:CustFacade( 4041): Context : android.app.ReceiverRestrictedContext@428cdfe0
D/AppUp4:CustFacade( 4041): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4041): isOpenOperator : true
,D/AppUp4:CustFacade( 4041): isPhone : true
I/LicenseContentProvider( 2982): start selecting data
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/SIMObserver( 2982): simInfo1
,D/WifiController(  964): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
V/GmsNetworkLocationProvi( 1423): DISABLE
I/AppUp4:EulaManager( 4041): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4041): begin check event
D/AppUp4:Utils( 4041): [getPackageName] uri : package:com.google.android.gms
I/AppUp4:CustModeStarterReceiver( 4041): Event For Nothing, skip.
I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5233 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5233): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  964): applying state to connected service
,D/LocationProviderProxy(  964): applying state to connected service
,I/SystemConfig( 5233): BUILD Country: EU
,I/SystemConfig( 5233): BUILD Operator: OPEN
,I/SystemConfig( 5233): systemFeature RCS result false
,D/SystemConfig( 5233): refreshRcsSupport() :false
I/ActivityManager(  964): Killing 4782:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5250 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  964): Killing 4817:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
,D/HyLog   ( 5250): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5250): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5250): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
,I/IcingCorporaProvider( 2653): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  964): Killing 4863:android.process.media/u0a23 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1965): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1965): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  964): Delaying start of: ServiceRecord{43febb90 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1965): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1965): GC_CONCURRENT freed 1939K, 22% free 19555K/24832K, paused 3ms+2ms, total 43ms
D/WifiController(  964): battery changed pluggedType: 2
,I/IcingCorporaProvider( 2653): UpdateCorporaTask done [took 210 ms] updated apps [took 210 ms] 
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.455933 Y: -0.424911 Z: 9.806458 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455933 .y:-0.424911 .z:9.806458
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.451691 Y: -0.418137 Z: 9.815033 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451691 .y:-0.418137 .z:9.815033
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2034): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2034): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2034): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2034): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/GAV4    ( 5185): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2034): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2034): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2034): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2034): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/PowerManagerService(  964): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  964): [updateScreenState] screen on = false
D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  964): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8519 usec
D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = true
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
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.431549 Y: -0.411224 Z: 9.821274 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.431549 .y:-0.411224 .z:9.821274
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.432983 Y: -0.424911 Z: 9.815857 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.432983 .y:-0.424911 .z:9.815857
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Sensors (  564): sns_pwr.c(292):acquiring wakelock
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
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.445892 Y: -0.419098 Z: 9.822662 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445892 .y:-0.419098 .z:9.822662
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.440796 Y: -0.417664 Z: 9.819794 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440796 .y:-0.417664 .z:9.819794
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.440903 Y: -0.426834 Z: 9.817780 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440903 .y:-0.426834 .z:9.817780
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.457108 Y: -0.405975 Z: 9.825516 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457108 .y:-0.405975 .z:9.825516
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/KeyguardServiceDelegate(  964): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@449fce88)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.425644 Y: -0.413055 Z: 9.837967 
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.438950 Y: -0.409729 Z: 9.820221 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.425644 .y:-0.413055 .z:9.837967
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  274): Screen released, type=0 flinger=0xb8770450
,D/qdhwcomposer(  274): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  964): **** SHOWN CALLED ****
I/WindowManager(  964): No lock screen! windowToken=null
,D/WifiStateMachine(  964): handleScreenStateChanged: true
,D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2034): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  964): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2034): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
D/WifiOffDelayIfNotUsed(  964): stopMonitoring
D/WifiStateMachine(  964): handleMessage: E msg.what=131127
D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=132097
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  964): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2034): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2034): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  964): handleMessage: X
,E/SlideAside( 4066): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
V/SRS_Proc(  278): ParamSet string: screen_state=on
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
,V/voice   (  278): voice_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  278): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{431fb8c0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1840): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:50:48
,I/SlideAside( 4066): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1840): 2 : This is isUpdating : false
,D/WeatherAncestor( 1840): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:50:48
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/WeatherService( 1840): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1840): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1840): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/SurfaceControl(  964): Excessive delay in blankDisplay() while turning screen off: 391ms
,D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264649005, nextTick: 11028, mDrawingTime: 0
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264649052, nextTick: 10981, mDrawingTime: 0
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
,D/WeatherService( 1840): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:50:49
,D/WeatherService( 1840): 2 : ACTION screen on
,D/WeatherService( 1840): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1840): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:50:49
,D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
,E/Parcel  (  611): Reading a NULL string not supported here.
D/GsmSST  ( 1448): Emergency Service
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
,D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
,D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
D/qcom_sensors_hal(  964): hal_acquire_resources
D/qcom_sensors_hal(  964): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.446198 Y: -0.409927 Z: 9.813553 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446198 .y:-0.409927 .z:9.813553
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3}
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  964): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  964): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  964): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/UsbSettings( 2584): [AUTORUN] onDestroy() : getDefaultFunction =boot
,I/LGImmersionVibrator(  964): Vibrator off
V/UsbSettings( 2584): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2584): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2584): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,D/WifiStateMachine(  964): handleScreenStateChanged: false
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{430aec98 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{43ddf098 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
,D/KeyguardViewMediator( 1141): handleNotifyScreenOff
D/KeyguardViewManager( 1141): onScreenTurnedOff()
E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
V/SRS_Proc(  278): ParamSet string: screen_state=off
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  278): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1155): clear
D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{430aec98 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
,D/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): handleMessage: X
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/qdlights( 1155): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 63, B = 63
,I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1155): set_light_notifications: 2,ff003939,10,0,2
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
,D/qdlights( 1155): [Current] = 255, R = 0, G = 57, B = 57
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
,E/Parcel  (  611): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WeatherService( 1840): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:50:49
,D/WeatherService( 1840): 2 : ACTION screen off
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WeatherService( 1840): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:50:49
,D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1448): Emergency Service
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/qdlights( 1155): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 51, B = 51
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/NfcService( 1473): NFC-C OFF
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,D/qdlights( 1155): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 45, B = 45
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/qdlights( 1155): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 39, B = 39
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/qdlights( 1155): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1155): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 27, B = 27
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  564): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,E/ThermalEngine(  293): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264657075945266; DSPS: 4955763; Offset: 1452264505838060745
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1551): Vacuum at: now=1452264658021 tag=VacuumService
,I/GoogleURLConnFactory( 1551): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1551): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1551): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1551): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1551): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1551): No account for auth token provided
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1551): No account for auth token provided
,W/Uploader( 1551):  no longer exists, so no auth token.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1551): No account for auth token provided
,D/dalvikvm( 1551): GC_CONCURRENT freed 1738K, 28% free 18061K/24832K, paused 9ms+12ms, total 135ms
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264660051, nextTick: 59976, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264660057, nextTick: 59964, mDrawingTime: 4
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264677077254061; DSPS: 5611166; Offset: 1452264505838057284
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1461): GC_CONCURRENT freed 1539K, 7% free 25438K/27280K, paused 3ms+4ms, total 57ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264697078451762; DSPS: 6266565; Offset: 1452264505838064800
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5433
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5435
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264717080373786; DSPS: 6921988; Offset: 1452264505838064216
,D/wpa_supplicant( 2034): wlan0: BSS: Remove id 6 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 dc:4a:3e:0f:c2:f1]
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264720045, nextTick: 59985, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264720061, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264737081511122; DSPS: 7577385; Offset: 1452264505838072402
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264757085478093; DSPS: 8232875; Offset: 1452264505838072088
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264777087252148; DSPS: 8888293; Offset: 1452264505838076123
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264780045, nextTick: 59984, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264780050, nextTick: 59975, mDrawingTime: 3
,I/jxcore-log( 4717): Connected to the server!
I/jxcore-log( 4717): 
,I/chromium( 4717): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264797088118755; DSPS: 9543682; Offset: 1452264505838057720
,D/wpa_supplicant( 2034): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Remove id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Remove id 8 BSSID 64:7c:34:b0:03:6e SSID 'UPC4688432' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Remove id 3 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2034): wlan0: BSS: Remove id 7 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Remove id 9 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 2034): wlan0: BSS: Remove id 10 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Remove id 11 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Remove id 12 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2034): wlan0: BSS: Remove id 13 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 2034): wlan0: BSS: Remove id 14 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:97]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 64:7c:34:b0:03:6e]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 38:f8:89:11:e9:11]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 a0:c5:62:7a:49:96]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 44:e9:dd:10:c0:ac]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:37:b7:9d:3e:73]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 44:e9:dd:10:c0:ab]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 44:e9:dd:10:c0:ad]
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264817089415831; DSPS: 10199084; Offset: 1452264505838073058
,D/dalvikvm( 2641): GC_CONCURRENT freed 7891K, 33% free 16761K/24832K, paused 6ms+2ms, total 37ms
,D/dalvikvm( 2641): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 2641): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264837094215355; DSPS: 10854601; Offset: 1452264505838081322
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264840053, nextTick: 59977, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264840054, nextTick: 59977, mDrawingTime: 1
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x4337d5a0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4278): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4278): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4278): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4278): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4278): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4278): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4278): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4278): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4278): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4278): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LocationManagerService(  964): remove 432b89d8
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2641): GC_CONCURRENT freed 1744K, 32% free 17055K/24832K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 2641): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2641): GC_CONCURRENT freed 1746K, 31% free 17266K/24832K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 2641): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Mlt MonitorService( 2641): parseLastkmsg to dump
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264857095760659; DSPS: 11510012; Offset: 1452264505838070230
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264877096615807; DSPS: 12165400; Offset: 1452264505838070886
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264897097499133; DSPS: 12820789; Offset: 1452264505838069202
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264900034, nextTick: 59979, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264900048, nextTick: 59964, mDrawingTime: 7
,I/jxcore-log( 4717): --- start :testFindPeers.js---
I/jxcore-log( 4717): 
,I/jxcore-log( 4717): testFindPeers created [object Object]
I/jxcore-log( 4717): 
,I/jxcore-log( 4717): serverPort is 8876
I/jxcore-log( 4717): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4717): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4717): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4717): start: Peer ID: 34:FC:EF:9D:93:0B, peer name: Thali Test's G2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4717): bind: Binding a new listener
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4717): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4717): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"Thali Test's G2"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4717): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4717): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1224): SOCK FLAG = 0 ***********************
D/bt-btif ( 1224): btsock_rfc_listen, service_name:Thali_Bluetooth
D/bt-btif ( 1224): BTA_JvCreateRecordByUser:Thali_Bluetooth
I/bt-btif ( 1224): BTA_JvCreateRecordByUser
,D/bt-btif ( 1224): jv_dm_cback: event:11, slot id:4
D/bt-btif ( 1224): name:Thali_Bluetooth, scn:7
,D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1224): BTA_JvRfcommStartServer
D/bt-btif ( 1224): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
,D/bt-btif ( 1224): bta_jv_alloc_rfc_cb port_handle:9 handle:0x84
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4717): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4717): start: OK
,I/io.jxcore.node.ConnectionHelper( 4717): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4717): start: Peer ID: 34:FC:EF:9D:93:0B, peer name: Thali Test's G2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4717): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 4717): bind: Binding a new listener
,W/dalvikvm( 4717): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Waiting for incoming connections...
,W/dalvikvm( 4717): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4717): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4717): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
W/dalvikvm( 4717): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4717): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
E/dalvikvm( 4717): Could not find class 'org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>
W/dalvikvm( 4717): VFY: unable to resolve new-instance 425 (Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
,D/dalvikvm( 4717): VFY: replacing opcode 0x22 at 0x0013
,W/dalvikvm( 4717): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
I/dalvikvm( 4717): Could not find method android.bluetooth.le.ScanResult.getScanRecord, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.checkScanResult
,W/dalvikvm( 4717): VFY: unable to resolve virtual method 90: Landroid/bluetooth/le/ScanResult;.getScanRecord ()Landroid/bluetooth/le/ScanRecord;
,D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x0002
E/dalvikvm( 4717): Could not find class 'android.bluetooth.le.AdvertiseSettings$Builder', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.applySettings
,W/dalvikvm( 4717): VFY: unable to resolve new-instance 20 (Landroid/bluetooth/le/AdvertiseSettings$Builder;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
,D/dalvikvm( 4717): VFY: replacing opcode 0x22 at 0x002d
,W/dalvikvm( 4717): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,W/dalvikvm( 4717): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,W/dalvikvm( 4717): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4717): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4717): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4717): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
I/dalvikvm( 4717): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.start, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.start
,W/dalvikvm( 4717): VFY: unable to resolve virtual method 1804: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.start ()Z
,D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x0016
W/dalvikvm( 4717): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4717): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4717): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4717): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4717): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4717): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,I/dalvikvm( 4717): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.stop, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stop
W/dalvikvm( 4717): VFY: unable to resolve virtual method 1805: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.stop ()V
,D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 4717): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4717): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,D/dalvikvm( 4717): DexOpt: unable to opt direct call 0x0705 at 0x15 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
W/dalvikvm( 4717): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4717): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
,D/dalvikvm( 4717): DexOpt: unable to opt direct call 0x0726 at 0x25 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
,D/dalvikvm( 4717): DexOpt: unable to opt direct call 0x0048 at 0x2f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
,D/dalvikvm( 4717): DexOpt: unable to opt direct call 0x005c at 0x5f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/AndroidRuntime( 4717): Shutting down VM
,W/dalvikvm( 4717): threadid=1: thread exiting with uncaught exception (group=0x41878e48)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): Uncaught exception: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): java.lang.NoClassDefFoundError: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>(BlePeerDiscoverer.java:60)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscovery(DiscoveryManager.java:488)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:248)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:292)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at android.os.Handler.handleCallback(Handler.java:733)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at android.os.Looper.loop(Looper.java:136)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): 	at dalvik.system.NativeStart.main(Native Method)
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264917100562671; DSPS: 13476249; Offset: 1452264505838080982
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264937101003950; DSPS: 14131624; Offset: 1452264505838064497
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264957101464214; DSPS: 14786999; Offset: 1452264505838066998
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264960053, nextTick: 59974, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452264960056, nextTick: 59972, mDrawingTime: 4
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264977101920896; DSPS: 15442374; Offset: 1452264505838065916
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452264997102366418; DSPS: 16097748; Offset: 1452264505838084192
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265017102818281; DSPS: 16753123; Offset: 1452264505838078291
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265020054, nextTick: 59968, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265020060, nextTick: 59970, mDrawingTime: 2
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:12, len:12
D/IOP_DB_BT( 1224): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,D/IOP_DB_BT( 1224): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,W/bt-btif ( 1224): info:x10
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_LINK_UP_EVT
,D/bt-btif ( 1224): BTA_DM_LINK_UP_EVT. Sending BT_ACL_STATE_CONNECTED
,D/        ( 1224): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:12, len:12
D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,I/bt-btif ( 1224): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 1224): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/LGBluetoothServiceUtil( 1224): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
,I/bt-btif ( 1224): a2dp busy level set to 1
,D/bt-btif ( 1224): btif_check_send_bt_off() btif_core_state= (2),ACL links = (1), LE links = 0
,E/LGBluetoothUtils( 2584): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
,D/LGBluetoothUtils( 2584): [BTUI] FileNotFoundException: storeHashmapFromFile: java.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
,D/LGBluetoothPowerSaveListener( 2584): [BTUI] ACL connected => AclLinkCount = 1
,D/bt-att  ( 1224): GATT   ATT protocol channel with BDA: 34fcef11ae67 is connected
,D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :34-fc-ef-11-ae-67
D/bt-att  ( 1224): connected is TRUE reason=0
,I/bt-smp  ( 1224): SMDBG l2c smp_connect_cback 
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x40
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x40
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x40  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x40
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-btif ( 1224): bta_dm_sp_cback: 1
,I/bt-btif ( 1224): dm status: 1
I/bt-btif ( 1224): bta_dm_sp_cback: 0
D/bt-btif ( 1224): btif_dm_set_oob_for_io_req *p_oob_data=0
D/bt-btif ( 1224): bta_dm_co_io_req *p_oob_data = 0
D/bt-btif ( 1224): bta_dm_co_io_req *p_io_cap = 1
D/bt-btif ( 1224): bta_dm_co_io_req *p_auth_req = 0
D/bt-btif ( 1224): bta_dm_co_io_req is_orig = 0
,I/bt-btif ( 1224): io mitm: 0 oob_data:0
,I/bt-btif ( 1224): dm status: 1
,I/bt-btif ( 1224): bta_dm_sp_cback: 2
I/bt-btif ( 1224): dm status: 1
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_SP_CFM_REQ_EVT
D/bt-btif ( 1224): btif_dm_ssp_cfm_req_evt
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:1, len:7
D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:4, len:4
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:5, len:4
,I/bt-btif ( 1224): HAL bt_hal_cbacks->remote_device_properties_cb
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/bt-btif ( 1224): bond_state_changed: state=1 prev_state=0
,I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,D/bt-btif ( 1224): in bd addr:34:fc:ef:11:ae:67
,W/LGMDMUISystemServiceAdapter( 1224): <<<<< checkBluetoothPairing btPolicy: false >>>>>
,I/BluetoothBondStateMachine( 1224): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1224): Entering PendingCommandState State
,D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:4, len:4
,I/bt-btif ( 1224): btif_dm_ssp_cfm_req_evt: Auto-accept JustWorks pairing
I/bt-btif ( 1224): btif_dm_ssp_reply: accept=1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x12
,I/bt-btif ( 1224): bta_dm_sp_cback: 8
,I/bt-btif ( 1224): dm status: 1
,D/BluetoothManagerService(  964): Message: 20
,D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42fe9680:true
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_AUTH_CMPL_EVT
D/bt-btif ( 1224): btif_dm_auth_cmpl_evt: Temporary key. Not storing. key_type=0x4, is_temp=1
I/bt-btif ( 1224): GT^^ : btif_dm_ssp_set_justworks, justworks is set to 1
I/bt-btif ( 1224): GT^^ : btif_dm_ssp_set_justworks: remote_addr=34:fc:ef:11:ae:67
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:14, len:4
,D/bt-btif ( 1224): GT^^ just works = 1
D/IOP_DB_BT( 1224): db_query_create: id HidSdpBlacklist :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1224): db_query_execute: result 1
,I/bt-btif ( 1224): btif_dm_get_remote_services: remote_addr=34:fc:ef:11:ae:67
I/bt-btif ( 1224): bta_dm_search_sm_execute state:0, event:0x202
I/bt-btif ( 1224): bta_dm_discover services_to_search=0x5FFFFFFF, sdp_search=1
D/bt-btif ( 1224): bta_dm_discover_device, BDA:0x34FCEF11AE67
D/bt-btif ( 1224): bta_dm_discover_device name_discover_done = 0 p_btm_inq_info 0x0 
D/bt-btif ( 1224): bta_dm_read_remote_device_name
,D/bt-btif ( 1224): bta_dm_read_remote_device_name: BTM_ReadRemoteDeviceName is started
,D/bt-btif ( 1224): bta_dm_remname_cback len = 248 name=<Nexus 5>
,I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x204
D/bt-btif ( 1224): bta_dm_disc_rmt_name
D/bt-btif ( 1224): bta_dm_discover_device, BDA:0x34FCEF11AE67
D/bt-btif ( 1224): bta_dm_discover_device name_discover_done = 1 p_btm_inq_info 0x0 
D/bt-btif ( 1224): bta_dm_search_cb.services = 5fffffff***********
E/bt-btif ( 1224): services_to_search = 5fffffff
E/bt-btif ( 1224): ****************search UUID = 1200***********
,I/bt-sdp  ( 1224): SDP - Originate started
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGBluetoothEventManager( 2584): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,W/BluetoothEventManager( 2584): CachedBluetoothDevice for device 34:FC:EF:11:AE:67 not found, calling readPairedDevices().
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
,E/CachedBluetoothDevice( 2584): updating profiles for Galaxy S5-2
V/CachedBluetoothDevice( 2584): Class: 5a020c
V/CachedBluetoothDevice( 2584): UUID:
,V/CachedBluetoothDevice( 2584):   0000110a-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   00001105-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   00001115-0000-1000-8000-00805f9b34fb
,V/CachedBluetoothDevice( 2584):   00001116-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   0000112f-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   00001112-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   0000111f-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   00001132-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   00000000-0000-1000-8000-00805f9b34fb
,V/CachedBluetoothDevice( 2584):   00000000-0000-1000-8000-00805f9b34fb
,V/CachedBluetoothDevice( 2584):   0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/dalvikvm(  964): GC_CONCURRENT freed 2955K, 49% free 29896K/57860K, paused 13ms+13ms, total 201ms
,E/CachedBluetoothDevice( 2584): updating profiles for Note4-1
,V/CachedBluetoothDevice( 2584): Class: 5a020c
V/CachedBluetoothDevice( 2584): UUID:
V/CachedBluetoothDevice( 2584):   0000110a-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   00001105-0000-1000-8000-00805f9b34fb
,V/CachedBluetoothDevice( 2584):   00001115-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   00001116-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   0000112d-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   0000112f-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   00001112-0000-1000-8000-00805f9b34fb
,V/CachedBluetoothDevice( 2584):   0000111f-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   00001132-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   00000000-0000-1000-8000-00805f9b34fb
V/CachedBluetoothDevice( 2584):   00000000-0000-1000-8000-00805f9b34fb
,V/CachedBluetoothDevice( 2584):   fa87c0d0-afac-11de-8a39-0800200c9a66
E/BluetoothEventManager( 2584): Got bonding state changed for 34:FC:EF:11:AE:67, but device not added in cache.
,E/LGBluetoothEventManager( 2584): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 11
,I/bt-sdp  ( 1224): SDP - got conn cnf, sent cfg req, CID: 0x41
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x41
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x41  Result: 0
,W/bt-sdp  ( 1224): process_service_search_attr_rsp
,I/bt-sdp  ( 1224): SDP - disconnect  CID: 0x41
,W/bt-rfcomm( 1224): port_select_mtu credit_rx_max 40, credit_rx_low 10, rx_buf_critical 45
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc cfm, CID: 0x41
D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x205
D/bt-btif ( 1224): sdp_result::0x0
D/bt-btif ( 1224): bta_dm_sdp_result services_found = 0000
,D/bt-btif ( 1224): bta_dm_search_cb.services = 5fffffff***********
E/bt-btif ( 1224): services_to_search = 5ffffffe
E/bt-btif ( 1224): ****************search UUID = 0100***********
I/bt-sdp  ( 1224): SDP - Originate started
,D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback, code:0, port_handle:9
D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback code=0 port_handle:0x9 handle:0x84, p_pcb:0x60d6a124, user:4
D/bt-btif ( 1224): bta_jv_add_rfc_port, port_handle:9, change the listen port to open state
D/bt-btif ( 1224): bta_jv_add_rfc_port max_sess=7 used:1 curr_sess:1, listen:1 si:2
D/bt-btif ( 1224): bta_jv_add_rfc_port: p_pcb->handle:0x184, curr_sess:2
D/bt-btif ( 1224): bta_jv_add_rfc_port: sec id in use:4, rfc_cb in use:4
,I/bt-btif ( 1224): BTA_JVSetPmProfile handle:0x84, app_id:255
I/bt-btif ( 1224): BTA_JVSetPmProfile handle:0x84, app_id:255
D/bt-btif ( 1224): create_srv_accept_rfc_slot(open_handle: 0x84, new_listen_handle:0x184) accept_rs->rfc_handle:0x84, srv_rs_listen->rfc_handle:0x184
D/bt-btif ( 1224): create_srv_accept_rfc_slot, accept_rs->rfc_port_handle:0x9, srv_rs_listen->rfc_port_handle:0xa
D/bt-btif ( 1224): sending connect signal & app fd:98to app server to accept() the connection
D/bt-btif ( 1224): server fd:94, scn:7, accept rs id:4 app fd:98
,D/bt-btif ( 1224): close fd:98 after sent
,D/bt-btif ( 1224): PORT_SUCCESS: curr_sess:2, max_sess:7
I/bt-btif ( 1224): bta_jv_set_pm_profile(handle: 0x84, app_id: 255, init_st: 0)
I/bt-btif ( 1224): bta_jv_alloc_set_pm_profile_cb(handle 0x84, app_id 255): idx: 0, (BTA_JV_PM_MAX_NUM: 5), pp_cb: 0x60d6a134
I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a324, handle: 0x84, busy/idle_state: 1, app_id: 255, conn_state: 0)
D/bt-btif ( 1224): bta_dm_pm_cback: st(0), id(26), app(255)
W/bt-btif ( 1224): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Incoming connection accepted
W/bt-btif ( 1224): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 1224): bta_dm_pm_ssr:2, lat:1200
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 0, j: 14
I/bt-btif ( 1224): bta_jv_set_pm_profile(handle: 0x84, app_id: 255, init_st: 6)
I/bt-btif ( 1224): bta_jv_alloc_set_pm_profile_cb already allocated. return cb(handle 0x84, app_id 255): idx: 0)
I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a324, handle: 0x84, busy/idle_state: 1, app_id: 255, conn_state: 6)
D/bt-btif ( 1224): bta_dm_pm_cback: st(6), id(26), app(255)
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
D/bt-btif ( 1224): start dm_pm_timer:0, 7000
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4717): Entering thread (ID: 421)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Incoming connection initialized (thread ID: 421)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Waiting for incoming connections...,
,I/bt-sdp  ( 1224): SDP - got conn cnf, sent cfg req, CID: 0x43,
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x43
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x43  Result: 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): onBytesRead: Read 66 bytes successfully (thread ID: 421)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Got valid identity from [34:FC:EF:11:AE:67 Nexus 5]
I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a324, handle: 0x84, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btif ( 1224): bta_dm_pm_cback: st(7), id(26), app(255)
D/bt-btif ( 1224): stop dm_pm_timer:0
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 7, j: 14
D/bt-btif ( 1224): bta_jv_port_event_sr_cback code=x4 port_handle:9 handle:132
I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a324, handle: 0x84, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btif ( 1224): bta_dm_pm_cback: st(6), id(26), app(255)
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
D/bt-btif ( 1224): start dm_pm_timer:0, 7000
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): onBytesWritten: 74 bytes successfully written (thread ID: 421)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): removeThreadFromList: Removing thread with ID 421
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Handshake thread disposed (thread ID: 421)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): onIncomingConnectionConnected: [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4717): Exiting thread (ID: 421)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/bt-sdp  ( 1224): process_service_search_attr_rsp
,I/bt-sdp  ( 1224): SDP - disconnect  CID: 0x43
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc cfm, CID: 0x43
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x205
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/bt-btif ( 1224): sdp_result::0x0
D/bt-btif ( 1224): bta_dm_sdp_result services_found = 3c8c088
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1800)
D/bt-btif ( 1224): bta_dm_sdp_result (raw_data used = 0x485 raw_data_ptr = 0x60d66dfc)
I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x207
D/bt-btif ( 1224): bta_dm_disc_result
I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x206
D/bt-btif ( 1224): bta_dm_search_cmpl
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1800 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001800-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
D/bt-btif ( 1224): Now add inside config file
D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1112)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1112 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001112-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
,E/bt-btif ( 1224): uuid is already in config file. skip to save
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x111f)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x111f len=2)
E/bt-btif ( 1224): Index: 0 uuid:0000111f-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x110c)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x110c len=2)
,E/bt-btif ( 1224): Index: 0 uuid:0000110c-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
D/bt-btif ( 1224): Now add inside config file
,D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x110a)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x110a len=2)
E/bt-btif ( 1224): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
,D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x110e)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x110e len=2)
E/bt-btif ( 1224): Index: 0 uuid:0000110e-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1116)
,D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1116 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001116-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
,E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1115)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1115 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001115-0000-1000-8000-00805f9b34fb
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
,D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1132)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1132 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001132-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
,E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x112f)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x112f len=2)
E/bt-btif ( 1224): Index: 0 uuid:0000112f-0000-1000-8000-00805f9b34fb
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1105)
,D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1105 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001105-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
,E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 2
D/bt-btif ( 1224): btif_dm_search_services_evt:(result=0x0, services 0x3c8c088)
E/bt-btif ( 1224): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1224): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1224): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1224): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 9 uuid:00000000-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 10 uuid:00000000-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 11 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
D/bt-btif ( 1224): btif_dm_search_services_evt Remote Service SDP done. Call bond_state_changed_cb BONDED
,D/bt-btif ( 1224): bond_state_changed: state=0 prev_state=1
,I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,I/bt-btif ( 1224): btif_in_storage_request_copy_cb
,D/BluetoothRemoteDevices( 1224): [BTUI] setTrustState : false
,D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1224): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1224): StableState(): Entering Off State
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:192
,W/BluetoothEventManager( 2584): CachedBluetoothDevice for device 34:FC:EF:11:AE:67 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
,E/BluetoothEventManager( 2584): Got bonding state changed for 34:FC:EF:11:AE:67, but we have no record of that device.
E/LGBluetoothEventManager( 2584): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 10
,D/LGBluetoothUtils( 2584): [BTUI] BOND_NONE == reason(0) [failed:1 / rejected:2 / canceled:3 / down:4 / timeout:6 / rem_canceled:8 / removed:9]
,D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,I/bt-btif ( 1224): HAL bt_hal_cbacks->remote_device_properties_cb
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] Get BRCM HeadsetService
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 4
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:3, len:512
,I/bt-btif ( 1224): HAL bt_hal_cbacks->remote_device_properties_cb
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] Get BRCM HeadsetService
,I/bt-btif ( 1224): execute storage remote request event : 5
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:13, len:4
,E/bt-btif ( 1224): Unknow prop type:13
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265037113811736; DSPS: 17408844; Offset: 1452264505838054901
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 0
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
,W/bt-btif ( 1224): proc dm_pm_timer expires
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:0, idx:0, info:x10
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:5
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265057114245295; DSPS: 18064217; Offset: 1452264505838091731
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:0
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:0, 7000
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x44
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x44
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x44  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x44
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 0
I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
W/bt-btif ( 1224): proc dm_pm_timer expires
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:0, idx:0, info:x2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:5
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:0
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:0, 7000
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x45
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x45
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x45  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x45
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x46
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x46
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x46  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x46
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265077114700002; DSPS: 18719593; Offset: 1452264505838058157
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:12, len:12
,D/IOP_DB_BT( 1224): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,I/bt-btif ( 1224): SET ACL PRIORITY 0
,I/bt-btif ( 1224): SET ACL PRIORITY 0
,E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d431b4 rs_disc_pending=0
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,D/bt-att  ( 1224): GATT   ATT protocol channel with BDA: 7cf90e3796ab is connected
,D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :7c-f9-0e-37-96-ab
D/bt-att  ( 1224): connected is TRUE reason=0
,I/bt-smp  ( 1224): SMDBG l2c smp_connect_cback 
,D/IOP_DB_BT( 1224): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
W/bt-btif ( 1224): info:x10
,D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_LINK_UP_EVT
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:24576
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1224): db_query_execute: result 1
,D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0
D/bt-btif ( 1224): BTA_DM_LINK_UP_EVT. Sending BT_ACL_STATE_CONNECTED
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x47
,D/        ( 1224): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:12, len:12
,D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,I/bt-btif ( 1224): HAL bt_hal_cbacks->acl_state_changed_cb
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/BluetoothRemoteDevices( 1224): aclStateChangeCallback: Device is NULL
,D/LGBluetoothServiceUtil( 1224): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
,I/bt-btif ( 1224): a2dp busy level set to 2
,D/bt-btif ( 1224): btif_check_send_bt_off() btif_core_state= (2),ACL links = (2), LE links = 0
,D/LGBluetoothPowerSaveListener( 2584): [BTUI] ACL connected => AclLinkCount = 2
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x47
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x47  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x47
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-btif ( 1224): SET ACL PRIORITY 0
,E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d43000 rs_disc_pending=1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,D/bt-btif ( 1224): bta_dm_acl_change role chg info:x2 new_role:0 dev count:2
W/bt-btif ( 1224): bta_dm_check_av:0
,D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
,W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,I/bt-btif ( 1224): SET ACL PRIORITY 0
,E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d431b4 rs_disc_pending=1
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,D/bt-btif ( 1224): bta_dm_acl_change role chg info:x10 new_role:0 dev count:2
W/bt-btif ( 1224): bta_dm_check_av:0
,D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
,W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265080041, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265080046, nextTick: 59985, mDrawingTime: 1
,D/bt-att  ( 1224): GATT   ATT protocol channel with BDA: 7cf90e3796ab is disconnected
,D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :7c-f9-0e-37-96-ab
D/bt-att  ( 1224): gatt_cleanup_upon_disc 
,D/bt-att  ( 1224): exit gatt_cleanup_upon_disc 
D/bt-att  ( 1224): ATT disconnected
,I/bt-smp  ( 1224): SMDBG l2c smp_connect_cback 
,E/bt-btm  ( 1224): btm_sec_disconnected - Clearing Pending flag
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_LINK_DOWN_EVT
,D/bt-btif ( 1224):  btif_storage_check_ble_bonding_keys in bd addr:7c:f9:0e:37:96:ab
D/bt-btif ( 1224):  btif_storage_check_ble_bonding_keys ret =:0,
D/bt-btif ( 1224): remove_temp_device: Temporary device, remove from device db
D/bt-btif ( 1224): btif_hh_virtual_unplug
,E/bt-btif ( 1224): btif_hh_virtual_unplug: Error, device 7C:F9:0E:37:96:AB not opened.,
I/bt-btif ( 1224): bta_dm_sm_execute event:0x18
D/bt-att  ( 1224): gatt_delete_dev_from_srv_chg_clt_list
,D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :7c-f9-0e-37-96-ab,
,D/bt-btif ( 1224): BTA_DM_LINK_DOWN_EVT. Sending BT_ACL_STATE_DISCONNECTED
,I/bt-btif ( 1224): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 1224): aclStateChangeCallback: Device is NULL
,D/LGBluetoothServiceUtil( 1224): [BTUI] sendBroadcastAclConnection: DisConnected, but device is null, sendBroadcast
,I/bt-btif ( 1224): GT^^ : btif_dm_ssp_get_justworks: remote_addr=7c:f9:0e:37:96:ab
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:14, len:4
I/bt-btif ( 1224): GT^^ : btif_dm_ssp_get_justworks: justworks =1
,I/bt-btif ( 1224): btif_dm_remove_bond: bd_addr=7c:f9:0e:37:96:ab
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
,I/bt-btif ( 1224): a2dp busy level set to 1
D/bt-btif ( 1224): btif_check_send_bt_off() btif_core_state= (2),ACL links = (1), LE links = 0
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_DEV_UNPAIRED_EVT
D/bt-btif ( 1224): btif_hh_remove_device: bda = 7c:f9:0e:37:96:ab
,W/bt-btif ( 1224):  Oops, can't find device [7c:f9:0e:37:96:ab]
D/bt-btif ( 1224):  btif_storage_remove_ble_bonding_keys in bd addr:7c:f9:0e:37:96:ab
,D/bt-btif ( 1224): in bd addr:7c:f9:0e:37:96:ab
,D/bt-btif ( 1224): bond_state_changed: state=0 prev_state=0
,I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1224): No record of the device:null
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
I/bt-btif ( 1224): btif_dm_generic_evt: event=33027
D/bt-btif ( 1224): btif_hh_virtual_unplug
E/bt-btif ( 1224): btif_hh_virtual_unplug: Error, device 7C:F9:0E:37:96:AB not opened.
I/bt-btif ( 1224): bta_dm_sm_execute event:0x18
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_DEV_UNPAIRED_EVT
D/bt-btif ( 1224): btif_hh_remove_device: bda = 7c:f9:0e:37:96:ab
W/bt-btif ( 1224):  Oops, can't find device [7c:f9:0e:37:96:ab]
D/bt-btif ( 1224):  btif_storage_remove_ble_bonding_keys in bd addr:7c:f9:0e:37:96:ab
D/bt-btif ( 1224): in bd addr:7c:f9:0e:37:96:ab
D/bt-btif ( 1224): bond_state_changed: state=0 prev_state=0
,I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1224): No record of the device:null
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/LGBluetoothPowerSaveListener( 2584): [BTUI] ACL disconnected => AclLinkCount = 1
,W/bt-btif ( 1224): dm_pm_timer expires
W/bt-btif ( 1224): dm_pm_timer expires 0
I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
W/bt-btif ( 1224): proc dm_pm_timer expires
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:0, idx:0, info:x2
I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:5
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x48
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
D/bt-btif ( 1224): bta_dm_pm_btm_status:0
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:0, 7000
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x48
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x48  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x48
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 0
I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
W/bt-btif ( 1224): proc dm_pm_timer expires
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:0, idx:0, info:x2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:5
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:12, len:12
,D/IOP_DB_BT( 1224): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): SET ACL PRIORITY 0
,D/bt-att  ( 1224): GATT   ATT protocol channel with BDA: 7cf90e3796ab is connected
,D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :7c-f9-0e-37-96-ab
D/bt-att  ( 1224): connected is TRUE reason=0
,I/bt-smp  ( 1224): SMDBG l2c smp_connect_cback 
,D/IOP_DB_BT( 1224): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,W/bt-btif ( 1224): info:x10
D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_LINK_UP_EVT
D/bt-btif ( 1224): BTA_DM_LINK_UP_EVT. Sending BT_ACL_STATE_CONNECTED
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:24576,
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
D/        ( 1224): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3,
D/IOP_DB_BT( 1224): db_query_execute: result 1
,D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x49
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:12, len:12
D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,I/bt-btif ( 1224): HAL bt_hal_cbacks->acl_state_changed_cb
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x49
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x49  Result: 0
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x49
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,E/BluetoothRemoteDevices( 1224): aclStateChangeCallback: Device is NULL
,D/LGBluetoothServiceUtil( 1224): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
I/bt-btif ( 1224): a2dp busy level set to 2
,D/bt-btif ( 1224): btif_check_send_bt_off() btif_core_state= (2),ACL links = (2), LE links = 0
,D/LGBluetoothPowerSaveListener( 2584): [BTUI] ACL connected => AclLinkCount = 2
,I/bt-btif ( 1224): bta_dm_sp_cback: 1
,I/bt-btif ( 1224): dm status: 1
I/bt-btif ( 1224): bta_dm_sp_cback: 0
D/bt-btif ( 1224): btif_dm_set_oob_for_io_req *p_oob_data=0
D/bt-btif ( 1224): bta_dm_co_io_req *p_oob_data = 0
D/bt-btif ( 1224): bta_dm_co_io_req *p_io_cap = 1
D/bt-btif ( 1224): bta_dm_co_io_req *p_auth_req = 0
D/bt-btif ( 1224): bta_dm_co_io_req is_orig = 0
I/bt-btif ( 1224): io mitm: 0 oob_data:0
,I/bt-btif ( 1224): dm status: 1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,I/bt-btif ( 1224): bta_dm_sp_cback: 2
,I/bt-btif ( 1224): dm status: 1
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_SP_CFM_REQ_EVT
,D/bt-btif ( 1224): btif_dm_ssp_cfm_req_evt
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:1, len:4
D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:4, len:4
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:5, len:4
,I/bt-btif ( 1224): HAL bt_hal_cbacks->remote_device_properties_cb
,D/LGBluetoothEventManager( 2584): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,D/bt-btif ( 1224): bond_state_changed: state=1 prev_state=0
I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,W/LGMDMUISystemServiceAdapter( 1224): <<<<< checkBluetoothPairing btPolicy: false >>>>>
,D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1224): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1224): Entering PendingCommandState State
D/bt-btif ( 1224): in bd addr:7c:f9:0e:37:96:ab
D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:4, len:4
,W/BluetoothEventManager( 2584): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
E/BluetoothEventManager( 2584): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,E/LGBluetoothEventManager( 2584): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 11
,I/bt-btif ( 1224): btif_dm_ssp_cfm_req_evt: Auto-accept JustWorks pairing
,I/bt-btif ( 1224): btif_dm_ssp_reply: accept=1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x12
,I/bt-btif ( 1224): bta_dm_sp_cback: 8
,I/bt-btif ( 1224): dm status: 1
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_AUTH_CMPL_EVT
,D/bt-btif ( 1224): btif_dm_auth_cmpl_evt: Temporary key. Not storing. key_type=0x4, is_temp=1
I/bt-btif ( 1224): GT^^ : btif_dm_ssp_set_justworks, justworks is set to 1
I/bt-btif ( 1224): GT^^ : btif_dm_ssp_set_justworks: remote_addr=7c:f9:0e:37:96:ab
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:14, len:4
D/bt-btif ( 1224): GT^^ just works = 1
D/IOP_DB_BT( 1224): db_query_create: id HidSdpBlacklist :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1224): db_query_execute: result 1
I/bt-btif ( 1224): btif_dm_get_remote_services: remote_addr=7c:f9:0e:37:96:ab
I/bt-btif ( 1224): bta_dm_search_sm_execute state:0, event:0x202
,I/bt-btif ( 1224): bta_dm_discover services_to_search=0x5FFFFFFF, sdp_search=1
D/bt-btif ( 1224): bta_dm_discover_device, BDA:0x7CF90E3796AB
D/bt-btif ( 1224): bta_dm_discover_device name_discover_done = 0 p_btm_inq_info 0x0 
D/bt-btif ( 1224): bta_dm_read_remote_device_name
,D/bt-btif ( 1224): bta_dm_read_remote_device_name: BTM_ReadRemoteDeviceName is started
,D/bt-btif ( 1224): bta_dm_remname_cback len = 248 name=<A5-1>
,I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x204
D/bt-btif ( 1224): bta_dm_disc_rmt_name
D/bt-btif ( 1224): bta_dm_discover_device, BDA:0x7CF90E3796AB
D/bt-btif ( 1224): bta_dm_discover_device name_discover_done = 1 p_btm_inq_info 0x0 
D/bt-btif ( 1224): bta_dm_search_cb.services = 5fffffff***********
,E/bt-btif ( 1224): services_to_search = 5fffffff
E/bt-btif ( 1224): ****************search UUID = 1200***********
,I/bt-sdp  ( 1224): SDP - Originate started
,I/bt-sdp  ( 1224): SDP - got conn cnf, sent cfg req, CID: 0x4a
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x4a
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x4a  Result: 0
,W/bt-sdp  ( 1224): process_service_search_attr_rsp
,I/bt-sdp  ( 1224): SDP - disconnect  CID: 0x4a
,W/bt-rfcomm( 1224): port_select_mtu credit_rx_max 40, credit_rx_low 10, rx_buf_critical 45
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc cfm, CID: 0x4a
D/bt-sdp  ( 1224): releasing SDP rsp_list
I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x205
D/bt-btif ( 1224): sdp_result::0x0
,D/bt-btif ( 1224): bta_dm_sdp_result services_found = 0000
D/bt-btif ( 1224): bta_dm_search_cb.services = 5fffffff***********
E/bt-btif ( 1224): services_to_search = 5ffffffe
E/bt-btif ( 1224): ****************search UUID = 0100***********
,I/bt-sdp  ( 1224): SDP - Originate started
,D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback, code:0, port_handle:10
,D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback code=0 port_handle:0xa handle:0x84, p_pcb:0x60d6a138, user:5
D/bt-btif ( 1224): bta_jv_add_rfc_port, port_handle:10, change the listen port to open state
D/bt-btif ( 1224): bta_jv_add_rfc_port max_sess=7 used:2 curr_sess:2, listen:1 si:3
,D/bt-btif ( 1224): bta_jv_add_rfc_port: p_pcb->handle:0x284, curr_sess:3
D/bt-btif ( 1224): bta_jv_add_rfc_port: sec id in use:4, rfc_cb in use:4
I/bt-btif ( 1224): BTA_JVSetPmProfile handle:0x184, app_id:255
,I/bt-btif ( 1224): BTA_JVSetPmProfile handle:0x184, app_id:255
D/bt-btif ( 1224): create_srv_accept_rfc_slot(open_handle: 0x184, new_listen_handle:0x284) accept_rs->rfc_handle:0x184, srv_rs_listen->rfc_handle:0x284
,D/bt-btif ( 1224): create_srv_accept_rfc_slot, accept_rs->rfc_port_handle:0xa, srv_rs_listen->rfc_port_handle:0xb
,D/bt-btif ( 1224): sending connect signal & app fd:99to app server to accept() the connection
D/bt-btif ( 1224): server fd:94, scn:7, accept rs id:5 app fd:99
,D/bt-btif ( 1224): close fd:99 after sent
,D/bt-btif ( 1224): PORT_SUCCESS: curr_sess:3, max_sess:7
,I/bt-sdp  ( 1224): SDP - got conn cnf, sent cfg req, CID: 0x4c
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x4c
I/bt-btif ( 1224): bta_jv_set_pm_profile(handle: 0x184, app_id: 255, init_st: 0)
,I/bt-btif ( 1224): bta_jv_alloc_set_pm_profile_cb(handle 0x184, app_id 255): idx: 1, (BTA_JV_PM_MAX_NUM: 5), pp_cb: 0x60d6a148
I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a330, handle: 0x184, busy/idle_state: 1, app_id: 255, conn_state: 0)
D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:24576
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1224): db_query_execute: result 1
,D/bt-btif ( 1224): bta_dm_pm_cback: st(0), id(26), app(255)
W/bt-btif ( 1224): new conn_srvc id:26, app_id:255
W/bt-btif ( 1224): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1224): bta_dm_pm_ssr:2, lat:1200
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 0, j: 14
,I/bt-btif ( 1224): bta_jv_set_pm_profile(handle: 0x184, app_id: 255, init_st: 6)
,I/bt-btif ( 1224): bta_jv_alloc_set_pm_profile_cb already allocated. return cb(handle 0x184, app_id 255): idx: 1)
I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a330, handle: 0x184, busy/idle_state: 1, app_id: 255, conn_state: 6)
D/bt-btif ( 1224): bta_dm_pm_cback: st(6), id(26), app(255)
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
D/bt-btif ( 1224): start dm_pm_timer:0, 7000
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x4c  Result: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Incoming connection initialized (thread ID: 422)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4717): Entering thread (ID: 422)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): onBytesRead: Read 63 bytes successfully (thread ID: 422)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Got valid identity from [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): onBytesWritten: 74 bytes successfully written (thread ID: 422)
I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a330, handle: 0x184, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btif ( 1224): bta_dm_pm_cback: st(7), id(26), app(255)
,D/bt-btif ( 1224): stop dm_pm_timer:0
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 7, j: 14
D/bt-btif ( 1224): bta_jv_port_event_sr_cback code=x4 port_handle:10 handle:132
,I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a330, handle: 0x184, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btif ( 1224): bta_dm_pm_cback: st(6), id(26), app(255)
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:0, 7000
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): removeThreadFromList: Removing thread with ID 422
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Handshake thread disposed (thread ID: 422)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4717): Exiting thread (ID: 422)
,W/bt-sdp  ( 1224): process_service_search_attr_rsp
,I/bt-sdp  ( 1224): SDP - disconnect  CID: 0x4c
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc cfm, CID: 0x4c
D/bt-sdp  ( 1224): releasing SDP rsp_list
I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x205
,D/bt-btif ( 1224): sdp_result::0x0
,D/bt-btif ( 1224): bta_dm_sdp_result services_found = 3c2c088
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): bta_dm_sdp_result (raw_data used = 0x4c4 raw_data_ptr = 0x60d66dfc)
,D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1800)
I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x207
D/bt-btif ( 1224): bta_dm_disc_result
,I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x206
D/bt-btif ( 1224): bta_dm_search_cmpl
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1800 len=2)
,E/bt-btif ( 1224): Index: 0 uuid:00001800-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
D/bt-btif ( 1224): Now add inside config file
,D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
,D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x110c),
,D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x110c len=2)
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
E/bt-btif ( 1224): Index: 0 uuid:0000110c-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
,D/bt-btif ( 1224): Now add inside config file
,D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
,D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x110a)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x110a len=2)
,E/bt-btif ( 1224): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 1224): uuid is already in config file. skip to save
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1112)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1112 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001112-0000-1000-8000-00805f9b34fb
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
,D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x111f)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x111f len=2)
E/bt-btif ( 1224): Index: 0 uuid:0000111f-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x112d)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x112d len=2)
,E/bt-btif ( 1224): Index: 0 uuid:0000112d-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1116)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1116 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001116-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1115)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1115 len=2)
,E/bt-btif ( 1224): Index: 0 uuid:00001115-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
,D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x112f)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x112f len=2)
E/bt-btif ( 1224): Index: 0 uuid:0000112f-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1132)
,D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1132 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001132-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1105)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1105 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001105-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 2
D/bt-btif ( 1224): btif_dm_search_services_evt:(result=0x0, services 0x3c2c088)
,E/bt-btif ( 1224): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1224): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 9 uuid:00000000-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1224): Index: 10 uuid:00000000-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 11 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
D/bt-btif ( 1224): btif_dm_search_services_evt Remote Service SDP done. Call bond_state_changed_cb BONDED
D/bt-btif ( 1224): bond_state_changed: state=0 prev_state=1
,I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,I/bt-btif ( 1224): btif_in_storage_request_copy_cb
,D/BluetoothRemoteDevices( 1224): [BTUI] setTrustState : false
,I/BluetoothBondStateMachine( 1224): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1224): StableState(): Entering Off State
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:192
D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,I/bt-btif ( 1224): HAL bt_hal_cbacks->remote_device_properties_cb
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] Get BRCM HeadsetService
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 4
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:3, len:512
,W/BluetoothEventManager( 2584): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
,E/BluetoothEventManager( 2584): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
E/LGBluetoothEventManager( 2584): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 10
,D/LGBluetoothUtils( 2584): [BTUI] BOND_NONE == reason(0) [failed:1 / rejected:2 / canceled:3 / down:4 / timeout:6 / rem_canceled:8 / removed:9]
,I/bt-btif ( 1224): HAL bt_hal_cbacks->remote_device_properties_cb
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] Get BRCM HeadsetService
,I/bt-btif ( 1224): execute storage remote request event : 5
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:13, len:4
,E/bt-btif ( 1224): Unknow prop type:13
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x4d
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
D/bt-btif ( 1224): bta_dm_pm_btm_status:0
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:1, 7000
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x4d
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x4d  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x4d
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x4e
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x4e
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x4e  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x4e
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-btif ( 1224): SET ACL PRIORITY 0
,E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d43000 rs_disc_pending=0
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
D/bt-btif ( 1224): bta_dm_acl_change role chg info:x2 new_role:1 dev count:2
,W/bt-btif ( 1224): bta_dm_check_av:0
D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
,W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265097115149109; DSPS: 19374967; Offset: 1452264505838080018
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 0
I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
,W/bt-btif ( 1224): proc dm_pm_timer expires
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:2, idx:0, info:x14
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:0
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:0, 7000
,I/bt-btif ( 1224): SET ACL PRIORITY 0
E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d431b4 rs_disc_pending=0
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
D/bt-btif ( 1224): bta_dm_acl_change role chg info:x4 new_role:1 dev count:2
W/bt-btif ( 1224): bta_dm_check_av:0
D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
,W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 1
I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
,W/bt-btif ( 1224): proc dm_pm_timer expires
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:0, idx:0, info:x2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:5
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 0
I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
W/bt-btif ( 1224): proc dm_pm_timer expires
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
D/bt-btif ( 1224): bta_dm_pm_sniff cur:2, idx:0, info:x4
,D/bt-btif ( 1224): bta_dm_pm_sniff BTM_SetPowerMode() returns BTM_SUCCESS
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:12, len:12
D/IOP_DB_BT( 1224): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,D/IOP_DB_BT( 1224): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,W/bt-btif ( 1224): info:x10
D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_LINK_UP_EVT
D/bt-btif ( 1224): BTA_DM_LINK_UP_EVT. Sending BT_ACL_STATE_CONNECTED
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:24576
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0,
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
D/        ( 1224): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:12, len:12
,D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,I/bt-btif ( 1224): HAL bt_hal_cbacks->acl_state_changed_cb
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/BluetoothRemoteDevices( 1224): aclStateChangeCallback: Device is NULL
,D/LGBluetoothServiceUtil( 1224): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
I/bt-btif ( 1224): a2dp busy level set to 3
,D/bt-btif ( 1224): btif_check_send_bt_off() btif_core_state= (2),ACL links = (3), LE links = 0
,D/bt-att  ( 1224): GATT   ATT protocol channel with BDA: 08eca9507627 is connected
,D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :08-ec-a9-50-76-27
D/bt-att  ( 1224): connected is TRUE reason=0
,I/bt-smp  ( 1224): SMDBG l2c smp_connect_cback 
,D/LGBluetoothPowerSaveListener( 2584): [BTUI] ACL connected => AclLinkCount = 3
,E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d43368 rs_disc_pending=1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
D/bt-btif ( 1224): bta_dm_acl_change role chg info:x10 new_role:1 dev count:3
W/bt-btif ( 1224): bta_dm_check_av:0
D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
D/bt-btif ( 1224):  bta_dm_policy_cback cmd:16, policy:0x1
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
,W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x4f
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x4f
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x4f  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x4f
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-btif ( 1224): bta_dm_sp_cback: 1
,I/bt-btif ( 1224): dm status: 1
I/bt-btif ( 1224): bta_dm_sp_cback: 0
D/bt-btif ( 1224): btif_dm_set_oob_for_io_req *p_oob_data=0
D/bt-btif ( 1224): bta_dm_co_io_req *p_oob_data = 0
D/bt-btif ( 1224): bta_dm_co_io_req *p_io_cap = 1
D/bt-btif ( 1224): bta_dm_co_io_req *p_auth_req = 0
D/bt-btif ( 1224): bta_dm_co_io_req is_orig = 0
I/bt-btif ( 1224): io mitm: 0 oob_data:0
,I/bt-btif ( 1224): dm status: 1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
D/bt-btif ( 1224): bta_dm_pm_btm_status:0
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:0, 7000
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:0
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:1, 7000
,I/bt-btif ( 1224): bta_dm_sp_cback: 2
,I/bt-btif ( 1224): dm status: 1
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_SP_CFM_REQ_EVT
,D/bt-btif ( 1224): btif_dm_ssp_cfm_req_evt
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:1, len:22
D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:4, len:4
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:5, len:4
,I/bt-btif ( 1224): HAL bt_hal_cbacks->remote_device_properties_cb
,D/bt-btif ( 1224): bond_state_changed: state=1 prev_state=0
,I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,D/LGBluetoothEventManager( 2584): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,W/LGMDMUISystemServiceAdapter( 1224): <<<<< checkBluetoothPairing btPolicy: false >>>>>
,D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1224): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1224): Entering PendingCommandState State
D/bt-btif ( 1224): in bd addr:08:ec:a9:50:76:27
,D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:4, len:4
,W/BluetoothEventManager( 2584): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
I/bt-btif ( 1224): btif_dm_ssp_cfm_req_evt: Auto-accept JustWorks pairing
I/bt-btif ( 1224): btif_dm_ssp_reply: accept=1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x12
E/BluetoothEventManager( 2584): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,E/LGBluetoothEventManager( 2584): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 11
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265117115609466; DSPS: 20030342; Offset: 1452264505838082611
,I/bt-btif ( 1224): bta_dm_sp_cback: 8
,I/bt-btif ( 1224): dm status: 1
,I/bt-btif ( 1224): SET ACL PRIORITY 0
,E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d43000 rs_disc_pending=1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
D/bt-btif ( 1224): bta_dm_acl_change role chg info:x2 new_role:0 dev count:3
,W/bt-btif ( 1224): bta_dm_check_av:0
,D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
,W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_AUTH_CMPL_EVT
,D/bt-btif ( 1224): btif_dm_auth_cmpl_evt: Temporary key. Not storing. key_type=0x4, is_temp=1
I/bt-btif ( 1224): GT^^ : btif_dm_ssp_set_justworks, justworks is set to 1
I/bt-btif ( 1224): GT^^ : btif_dm_ssp_set_justworks: remote_addr=08:ec:a9:50:76:27
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:14, len:4
D/bt-btif ( 1224): GT^^ just works = 1
D/IOP_DB_BT( 1224): db_query_create: id HidSdpBlacklist :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1224): db_query_execute: result 1
,I/bt-btif ( 1224): btif_dm_get_remote_services: remote_addr=08:ec:a9:50:76:27
,I/bt-btif ( 1224): bta_dm_search_sm_execute state:0, event:0x202
I/bt-btif ( 1224): bta_dm_discover services_to_search=0x5FFFFFFF, sdp_search=1
,D/bt-btif ( 1224): bta_dm_discover_device, BDA:0x08ECA9507627
D/bt-btif ( 1224): bta_dm_discover_device name_discover_done = 0 p_btm_inq_info 0x0 
,D/bt-btif ( 1224): bta_dm_read_remote_device_name
,D/bt-btif ( 1224): bta_dm_read_remote_device_name: BTM_ReadRemoteDeviceName is started
,D/bt-btif ( 1224): bta_dm_remname_cback len = 248 name=<Thali Test (Galaxy A3)>
,I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x204
D/bt-btif ( 1224): bta_dm_disc_rmt_name
,D/bt-btif ( 1224): bta_dm_discover_device, BDA:0x08ECA9507627
,D/bt-btif ( 1224): bta_dm_discover_device name_discover_done = 1 p_btm_inq_info 0x0 
,D/bt-btif ( 1224): bta_dm_search_cb.services = 5fffffff***********
,E/bt-btif ( 1224): services_to_search = 5fffffff
,E/bt-btif ( 1224): ****************search UUID = 1200***********
,I/bt-sdp  ( 1224): SDP - Originate started
,I/bt-sdp  ( 1224): SDP - got conn cnf, sent cfg req, CID: 0x40
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x40
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x40  Result: 0
,W/bt-sdp  ( 1224): process_service_search_attr_rsp
,I/bt-sdp  ( 1224): SDP - disconnect  CID: 0x40
,W/bt-rfcomm( 1224): port_select_mtu credit_rx_max 40, credit_rx_low 10, rx_buf_critical 45
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc cfm, CID: 0x40
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x205
,D/bt-btif ( 1224): sdp_result::0x0
,D/bt-btif ( 1224): bta_dm_sdp_result services_found = 0000
,D/bt-btif ( 1224): bta_dm_search_cb.services = 5fffffff***********
,E/bt-btif ( 1224): services_to_search = 5ffffffe
,E/bt-btif ( 1224): ****************search UUID = 0100***********
,I/bt-sdp  ( 1224): SDP - Originate started
,D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback, code:0, port_handle:11
,D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback code=0 port_handle:0xb handle:0x84, p_pcb:0x60d6a14c, user:6
,D/bt-btif ( 1224): bta_jv_add_rfc_port, port_handle:11, change the listen port to open state
,D/bt-btif ( 1224): bta_jv_add_rfc_port max_sess=7 used:3 curr_sess:3, listen:1 si:4
,D/bt-btif ( 1224): bta_jv_add_rfc_port: p_pcb->handle:0x384, curr_sess:4
,D/bt-btif ( 1224): bta_jv_add_rfc_port: sec id in use:4, rfc_cb in use:4
,I/bt-btif ( 1224): BTA_JVSetPmProfile handle:0x284, app_id:255
,I/bt-btif ( 1224): BTA_JVSetPmProfile handle:0x284, app_id:255
,D/bt-btif ( 1224): create_srv_accept_rfc_slot(open_handle: 0x284, new_listen_handle:0x384) accept_rs->rfc_handle:0x284, srv_rs_listen->rfc_handle:0x384
,D/bt-btif ( 1224): create_srv_accept_rfc_slot, accept_rs->rfc_port_handle:0xb, srv_rs_listen->rfc_port_handle:0xc
,D/bt-btif ( 1224): sending connect signal & app fd:100to app server to accept() the connection
,D/bt-btif ( 1224): server fd:94, scn:7, accept rs id:6 app fd:100
,D/bt-btif ( 1224): close fd:100 after sent
,D/bt-btif ( 1224): PORT_SUCCESS: curr_sess:4, max_sess:7
,I/bt-sdp  ( 1224): SDP - got conn cnf, sent cfg req, CID: 0x43
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x43
,I/bt-btif ( 1224): bta_jv_set_pm_profile(handle: 0x284, app_id: 255, init_st: 0)
,I/bt-btif ( 1224): bta_jv_alloc_set_pm_profile_cb(handle 0x284, app_id 255): idx: 2, (BTA_JV_PM_MAX_NUM: 5), pp_cb: 0x60d6a15c
,I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a33c, handle: 0x284, busy/idle_state: 1, app_id: 255, conn_state: 0)
,D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:24576
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0,
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,D/bt-btif ( 1224): bta_dm_pm_cback: st(0), id(26), app(255)
,W/bt-btif ( 1224): new conn_srvc id:26, app_id:255
,W/bt-btif ( 1224): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1224): bta_dm_pm_ssr:2, lat:1200
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 0, j: 14
,I/bt-btif ( 1224): bta_jv_set_pm_profile(handle: 0x284, app_id: 255, init_st: 6)
,I/bt-btif ( 1224): bta_jv_alloc_set_pm_profile_cb already allocated. return cb(handle 0x284, app_id 255): idx: 2),
,I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a33c, handle: 0x284, busy/idle_state: 1, app_id: 255, conn_state: 6)
,D/bt-btif ( 1224): bta_dm_pm_cback: st(6), id(26), app(255)
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14,
,D/bt-btif ( 1224): start dm_pm_timer:2, 7000
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Incoming connection initialized (thread ID: 423)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4717): Entering thread (ID: 423)
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x43  Result: 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): onBytesRead: Read 81 bytes successfully (thread ID: 423)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Got valid identity from [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a33c, handle: 0x284, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btif ( 1224): bta_dm_pm_cback: st(7), id(26), app(255)
,D/bt-btif ( 1224): stop dm_pm_timer:2
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 7, j: 14
,D/bt-btif ( 1224): bta_jv_port_event_sr_cback code=x4 port_handle:11 handle:132
,I/bt-btif ( 1224): bta_jv_pm_state_change(p_cb: 0x60d6a33c, handle: 0x284, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btif ( 1224): bta_dm_pm_cback: st(6), id(26), app(255)
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:2, 7000
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): onBytesWritten: 74 bytes successfully written (thread ID: 423)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): removeThreadFromList: Removing thread with ID 423
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4717): Handshake thread disposed (thread ID: 423)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4717): onIncomingConnectionConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4717): Exiting thread (ID: 423)
,E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d431b4 rs_disc_pending=1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,D/bt-btif ( 1224): bta_dm_acl_change role chg info:x0 new_role:1 dev count:3
,W/bt-btif ( 1224): bta_dm_check_av:0
,D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
,D/bt-btif ( 1224):  bta_dm_policy_cback cmd:16, policy:0x1
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
,W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,I/bt-btif ( 1224): SET ACL PRIORITY 0
,E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d43368 rs_disc_pending=1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,D/bt-btif ( 1224): bta_dm_acl_change role chg info:x10 new_role:0 dev count:3
,W/bt-btif ( 1224): bta_dm_check_av:0
,D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
,W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 1224): process_service_search_attr_rsp
,I/bt-sdp  ( 1224): SDP - disconnect  CID: 0x43
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc cfm, CID: 0x43
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x205
,D/bt-btif ( 1224): sdp_result::0x0
,D/bt-btif ( 1224): bta_dm_sdp_result services_found = 3c2c088
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
,D/bt-btif ( 1224): bta_dm_sdp_result (raw_data used = 0x4c4 raw_data_ptr = 0x60d66dfc)
,I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x207
,D/bt-btif ( 1224): bta_dm_disc_result
,I/bt-btif ( 1224): bta_dm_search_sm_execute state:3, event:0x206
,D/bt-btif ( 1224): bta_dm_search_cmpl
,D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1800)
,D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1800 len=2)
,E/bt-btif ( 1224): Index: 0 uuid:00001800-0000-1000-8000-00805f9b34fb
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
,D/bt-btif ( 1224): Now add inside config file
,D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
,D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x110c)
,D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x110c len=2)
,E/bt-btif ( 1224): Index: 0 uuid:0000110c-0000-1000-8000-00805f9b34fb
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
,D/bt-btif ( 1224): Now add inside config file
,D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x110a)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x110a len=2)
,E/bt-btif ( 1224): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
,E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1112)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1112 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001112-0000-1000-8000-00805f9b34fb
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
,D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x111f)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x111f len=2)
E/bt-btif ( 1224): Index: 0 uuid:0000111f-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x112d)
,D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x112d len=2)
E/bt-btif ( 1224): Index: 0 uuid:0000112d-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1116)
,D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1116 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001116-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
,E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1115)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1115 len=2)
,E/bt-btif ( 1224): Index: 0 uuid:00001115-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
,E/bt-btif ( 1224): uuid is already in config file. skip to save
I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x112f)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x112f len=2)
,E/bt-btif ( 1224): Index: 0 uuid:0000112f-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1132)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1132 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001132-0000-1000-8000-00805f9b34fb
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:15, len:16
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
,E/bt-btif ( 1224): uuid is already in config file. skip to save
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 3
D/bt-btif ( 1224): btif_dm_search_services_evt:, services 0x1105)
D/bt-btif ( 1224): btif_dm_search_services_evt:(service 0x1105 len=2)
E/bt-btif ( 1224): Index: 0 uuid:00001105-0000-1000-8000-00805f9b34fb
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:15, len:16
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
E/bt-btif ( 1224): uuid is already in config file. skip to save
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 2
D/bt-btif ( 1224): btif_dm_search_services_evt:(result=0x0, services 0x3c2c088)
E/bt-btif ( 1224): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1224): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1224): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 9 uuid:00000000-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1224): Index: 10 uuid:00000000-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1224): Index: 11 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
D/bt-btif ( 1224): btif_dm_search_services_evt Remote Service SDP done. Call bond_state_changed_cb BONDED
D/bt-btif ( 1224): bond_state_changed: state=0 prev_state=1
,I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,I/bt-btif ( 1224): btif_in_storage_request_copy_cb
,D/BluetoothRemoteDevices( 1224): [BTUI] setTrustState : false
,D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1224): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1224): StableState(): Entering Off State
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:192
,D/bt-btif ( 1224): post cmd type:1, size:0, h:7, 
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/bt-btif ( 1224): HAL bt_hal_cbacks->remote_device_properties_cb
,W/BluetoothEventManager( 2584): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] Get BRCM HeadsetService
,I/bt-btif ( 1224): btif_dm_search_services_evt:  event = 4
,D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:3, len:512
,D/BluetoothAdapterService(1116602736)( 1224): Get Bonded Devices being called
,I/bt-btif ( 1224): HAL bt_hal_cbacks->remote_device_properties_cb
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] Get BRCM HeadsetService
,I/bt-btif ( 1224): execute storage remote request event : 5
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:13, len:4
,E/bt-btif ( 1224): Unknow prop type:13
E/BluetoothEventManager( 2584): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,E/LGBluetoothEventManager( 2584): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 10
,D/LGBluetoothUtils( 2584): [BTUI] BOND_NONE == reason(0) [failed:1 / rejected:2 / canceled:3 / down:4 / timeout:6 / rem_canceled:8 / removed:9]
,I/bt-btif ( 1224): SET ACL PRIORITY 0
,E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d43000 rs_disc_pending=0
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
D/bt-btif ( 1224): bta_dm_acl_change role chg info:x2 new_role:1 dev count:3
W/bt-btif ( 1224): bta_dm_check_av:0
,D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
,W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1224): send none, EAGAIN or EWOULDBLOCK, errno:11
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 0
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
,W/bt-btif ( 1224): proc dm_pm_timer expires
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:2, idx:0, info:x4
,D/bt-btif ( 1224): bta_dm_pm_sniff BTM_SetPowerMode() returns BTM_SUCCESS
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
,W/bt-btif ( 1224): proc dm_pm_timer expires
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:0, idx:0, info:x2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:5
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:0
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:0, 7000
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
,W/bt-btif ( 1224): proc dm_pm_timer expires
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:0, idx:0, info:x10
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:5
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x44
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x44
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x44  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x44
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:0
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:1, 7000
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 0
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
,W/bt-btif ( 1224): proc dm_pm_timer expires
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:2, idx:0, info:x4
,D/bt-btif ( 1224): bta_dm_pm_sniff BTM_SetPowerMode() returns BTM_SUCCESS
,I/bt-btif ( 1224): SET ACL PRIORITY 0
,E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d43368 rs_disc_pending=0
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,D/bt-btif ( 1224): bta_dm_acl_change role chg info:x2 new_role:1 dev count:3
,W/bt-btif ( 1224): bta_dm_check_av:0
,D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
,W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:0
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:0, 7000
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x45
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x45
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x45  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x45
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x46
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x46
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x46  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x46
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/ActivityManager(  964): Killing 4615:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265137116545969; DSPS: 20685733; Offset: 1452264505838073069
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
,W/bt-btif ( 1224): proc dm_pm_timer expires
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:0, idx:0, info:x2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:5
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265140050, nextTick: 59978, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265140053, nextTick: 59978, mDrawingTime: 1
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 0
I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
W/bt-btif ( 1224): proc dm_pm_timer expires
,D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
D/bt-btif ( 1224): bta_dm_pm_sniff cur:2, idx:0, info:x4
,D/bt-btif ( 1224): bta_dm_pm_sniff BTM_SetPowerMode() returns BTM_SUCCESS
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x47
I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
D/bt-btif ( 1224): bta_dm_pm_btm_status:0
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): start dm_pm_timer:0, 7000
,I/bt-sdp  ( 1224): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x47
,I/bt-sdp  ( 1224): SDP - Rcvd cfg cfm, CID: 0x47  Result: 0
,I/bt-sdp  ( 1224): SDP - Rcvd L2CAP disc, CID: 0x47
,D/bt-sdp  ( 1224): releasing SDP rsp_list
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:2
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x10
,D/bt-btif ( 1224): bta_dm_pm_btm_status:4
,W/bt-btif ( 1224): dm_pm_timer expires
,W/bt-btif ( 1224): dm_pm_timer expires 0
I/bt-btif ( 1224): bta_dm_sm_execute event:0x11
W/bt-btif ( 1224): proc dm_pm_timer expires
D/bt-btif ( 1224): bta_dm_pm_set_mode: srvcsid: 26, state: 6, j: 14
,D/bt-btif ( 1224): bta_dm_pm_sniff cur:2, idx:0, info:x4
,D/bt-btif ( 1224): bta_dm_pm_sniff BTM_SetPowerMode() returns BTM_SUCCESS
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265157116986054; DSPS: 21341107; Offset: 1452264505838085908
,D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback, code:16, port_handle:9
,D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback code=16 port_handle:0x9 handle:0x84, p_pcb:0x60d6a124, user:4
D/bt-btif ( 1224): PORT_CLOSED before BTA_JV_RFCOMM_CLOSE_EVT: curr_sess:4, max_sess:7
D/bt-btif ( 1224): BTA_JV_RFCOMM_CLOSE_EVT: user_data:4
,D/bt-btif ( 1224): on_rfc_close, slot id:4, fd:95, rfc scn:7, server:0
,D/bt-btif ( 1224): cleanup slot:4, fd:95, scn:0, sdp_handle:0x0
D/bt-btif ( 1224): closing rfcomm connection, rfc_handle:0x84
,I/bt-btif ( 1224): BTA_JvRfcommClose
D/bt-btif ( 1224): PORT_CLOSED after BTA_JV_RFCOMM_CLOSE_EVT: curr_sess:4, max_sess:7
,D/bt-att  ( 1224): GATT   ATT protocol channel with BDA: 34fcef11ae67 is disconnected
,D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :34-fc-ef-11-ae-67
,D/bt-att  ( 1224): gatt_add_srv_chg_clt
,D/bt-att  ( 1224): enqueue a srv chg client
D/bt-att  ( 1224): gatt_cleanup_upon_disc ,
D/bt-att  ( 1224): exit gatt_cleanup_upon_disc 
,D/bt-att  ( 1224): ATT disconnected
,I/bt-smp  ( 1224): SMDBG l2c smp_connect_cback ,
E/bt-btm  ( 1224): btm_sec_disconnected - Clearing Pending flag
,D/bt-btif ( 1224): bta_jv_rfcomm_close, rfc handle:132
,D/bt-btif ( 1224): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 5, rfc_cb->handle: 0x84,
D/bt-btif ( 1224): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:4, p_pcb:0x60d6a124, user:4, state:5, jv handle: 0x84
,D/bt-btif ( 1224): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_OPEN, scn:7, user_data:4,
I/bt-btif ( 1224): bta_jv_free_set_pm_profile_cb(jv_handle: 0x84), idx: 0, app_id: 0xff,
,D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:12, len:12
,D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 34:fc:ef:11:ae:67,
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:24576
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab,
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29,
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 1224): db_query_execute: result 1
,W/bt-btif ( 1224): invalid rfc slot id: 4
D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0,
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1224): db_query_execute: result 1,
D/bt-btif ( 1224): bta_dm_pm_cback: st(1), id(26), app(255)
,D/bt-btif ( 1224): bta_jv_rfcomm_close: sec id in use:4, rfc_cb in use:4
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8,
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_LINK_DOWN_EVT
D/bt-btif ( 1224):  btif_storage_check_ble_bonding_keys in bd addr:34:fc:ef:11:ae:67
D/bt-btif ( 1224):  btif_storage_check_ble_bonding_keys ret =:0
D/bt-btif ( 1224): remove_temp_device: Temporary device, remove from device db
D/bt-btif ( 1224): btif_hh_virtual_unplug,
E/bt-btif ( 1224): btif_hh_virtual_unplug: Error, device 34:FC:EF:11:AE:67 not opened.
D/bt-btif ( 1224): BTA_DM_LINK_DOWN_EVT. Sending BT_ACL_STATE_DISCONNECTED
,I/bt-btif ( 1224): HAL bt_hal_cbacks->acl_state_changed_cb
D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1224): db_query_execute: result 1
D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 1224): db_query_execute: result 1
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
I/bt-btif ( 1224): bta_dm_sm_execute event:0x18
D/bt-att  ( 1224): gatt_delete_dev_from_srv_chg_clt_list
,D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :34-fc-ef-11-ae-67
,D/bt-att  ( 1224): bda is in the srv chg clt list
E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d43368 rs_disc_pending=1
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
D/bt-btif ( 1224): bta_dm_acl_change role chg info:x2 new_role:1 dev count:2
W/bt-btif ( 1224): bta_dm_check_av:0
,D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
,D/bt-btif ( 1224):  bta_dm_policy_cback cmd:16, policy:0x1
,D/WifiServiceExtension(  964): Connected BT device : -1
,I/bt-btif ( 1224): GT^^ : btif_dm_ssp_get_justworks: remote_addr=34:fc:ef:11:ae:67
D/bt-btif ( 1224): in, bd addr:34:fc:ef:11:ae:67, prop type:14, len:4
I/bt-btif ( 1224): GT^^ : btif_dm_ssp_get_justworks: justworks =1
I/bt-btif ( 1224): btif_dm_remove_bond: bd_addr=34:fc:ef:11:ae:67
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
I/bt-btif ( 1224): a2dp busy level set to 2
D/bt-btif ( 1224): btif_check_send_bt_off() btif_core_state= (2),ACL links = (2), LE links = 0
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_DEV_UNPAIRED_EVT
D/bt-btif ( 1224): btif_hh_remove_device: bda = 34:fc:ef:11:ae:67
,W/bt-btif ( 1224):  Oops, can't find device [34:fc:ef:11:ae:67]
D/bt-btif ( 1224):  btif_storage_remove_ble_bonding_keys in bd addr:34:fc:ef:11:ae:67
D/bt-btif ( 1224): in bd addr:34:fc:ef:11:ae:67
D/bt-btif ( 1224): bond_state_changed: state=0 prev_state=0
,I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,I/bt-btif ( 1224): btif_dm_generic_evt: event=33027
D/bt-btif ( 1224): btif_hh_virtual_unplug
E/bt-btif ( 1224): btif_hh_virtual_unplug: Error, device 34:FC:EF:11:AE:67 not opened.
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x18
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_DEV_UNPAIRED_EVT
D/bt-btif ( 1224): btif_hh_remove_device: bda = 34:fc:ef:11:ae:67
,W/bt-btif ( 1224):  Oops, can't find device [34:fc:ef:11:ae:67]
D/bt-btif ( 1224):  btif_storage_remove_ble_bonding_keys in bd addr:34:fc:ef:11:ae:67
D/bt-btif ( 1224): in bd addr:34:fc:ef:11:ae:67
D/bt-btif ( 1224): bond_state_changed: state=0 prev_state=0
,I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/LGBluetoothPowerSaveListener( 2584): [BTUI] ACL disconnected => AclLinkCount = 2
,D/BluetoothManagerService(  964): Message: 20
,D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@433ae7a8:true
,I/BTConnectionReceiver( 2653): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2653): Bluetooth Device Name: Nexus 5
,D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback, code:16, port_handle:10
D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback code=16 port_handle:0xa handle:0x84, p_pcb:0x60d6a138, user:5
D/bt-btif ( 1224): PORT_CLOSED before BTA_JV_RFCOMM_CLOSE_EVT: curr_sess:3, max_sess:7
D/bt-btif ( 1224): BTA_JV_RFCOMM_CLOSE_EVT: user_data:5
D/bt-btif ( 1224): on_rfc_close, slot id:5, fd:98, rfc scn:7, server:0
D/bt-btif ( 1224): cleanup slot:5, fd:98, scn:0, sdp_handle:0x0
D/bt-btif ( 1224): closing rfcomm connection, rfc_handle:0x184
,I/bt-btif ( 1224): BTA_JvRfcommClose
,D/bt-btif ( 1224): PORT_CLOSED after BTA_JV_RFCOMM_CLOSE_EVT: curr_sess:3, max_sess:7
D/bt-att  ( 1224): GATT   ATT protocol channel with BDA: 7cf90e3796ab is disconnected
,D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :7c-f9-0e-37-96-ab
,D/bt-att  ( 1224): gatt_add_srv_chg_clt
D/bt-att  ( 1224): enqueue a srv chg client
D/bt-att  ( 1224): gatt_cleanup_upon_disc 
,D/bt-att  ( 1224): exit gatt_cleanup_upon_disc 
D/bt-att  ( 1224): ATT disconnected
I/bt-smp  ( 1224): SMDBG l2c smp_connect_cback 
E/bt-btm  ( 1224): btm_sec_disconnected - Clearing Pending flag
D/bt-btif ( 1224): bta_jv_rfcomm_close, rfc handle:388
,D/bt-btif ( 1224): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x184, state: 5, rfc_cb->handle: 0x84,
D/bt-btif ( 1224): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:3, p_pcb:0x60d6a138, user:5, state:5, jv handle: 0x184
D/bt-btif ( 1224): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_OPEN, scn:7, user_data:5
,I/bt-btif ( 1224): bta_jv_free_set_pm_profile_cb(jv_handle: 0x184), idx: 1, app_id: 0xff,
,D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:12, len:12
D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0,
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1224): db_query_execute: result 1,
D/IOP_DB_BT( 1224): db_query_create: id MasterRoleDelayed :: key KEY_BDADDR, value 08:ec:a9:50:76:27,
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1224): db_query_add_key: key KEY_LMP_VER, value 7:0,
,D/IOP_DB_BT( 1224): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1224): db_query_execute: result 1
,D/bt-btif ( 1224): bta_dm_pm_cback: st(1), id(26), app(255),
D/bt-btif ( 1224): bta_jv_rfcomm_close: sec id in use:4, rfc_cb in use:4
,I/bt-btif ( 1224): bta_dm_sm_execute event:0x8,
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_LINK_DOWN_EVT
D/bt-btif ( 1224):  btif_storage_check_ble_bonding_keys in bd addr:7c:f9:0e:37:96:ab
,D/bt-btif ( 1224):  btif_storage_check_ble_bonding_keys ret =:0
D/bt-btif ( 1224): remove_temp_device: Temporary device, remove from device db
D/bt-btif ( 1224): btif_hh_virtual_unplug,
E/bt-btif ( 1224): bta_dm_sm_execute event:0x8
D/bt-btif ( 1224): BTA_DM_LINK_DOWN_EVT. Sending BT_ACL_STATE_DISCONNECTED
,I/bt-btif ( 1224): HAL bt_hal_cbacks->acl_state_changed_cb
W/bt-btif ( 1224): HAL bt_hal_cbacks->acl
,I/bt-btif ( 1224): HAL bt_hal_cbacks->acl_stat,
I/bt-btif ( 1224): bta_dm_sm_execute event:0x18
D/bt-att  ( 1224): gatt_delete_dev_from_srv_chg_clt_list
,D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :7c-f9-0e-37-96-ab
D/bt-att  ( 1224): bda is in the srv chg clt list
,E/bt-btm  ( 1224): tBTM_SEC_DEV:0x60d43368 rs_disc_pending=1,
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8,
D/bt-btif ( 1224): bta_dm_acl_change role chg info:x2 new_role:1 dev count:1
W/bt-btif ( 1224): bta_dm_check_av:0
,D/bt-btif ( 1224): bta_av_sys_rs_cback: 0
,D/bt-btif ( 1224):  bta_dm_policy_cback cmd:16, policy:0x1
,D/WifiServiceExtension(  964): Connected BT device : -2
,I/bt-btif ( 1224): GT^^ : btif_dm_ssp_get_justworks: remote_addr=7c:f9:0e:37:96:ab
D/bt-btif ( 1224): in, bd addr:7c:f9:0e:37:96:ab, prop type:14, len:4
I/bt-btif ( 1224): GT^^ : btif_dm_ssp_get_justworks: justworks =1
I/bt-btif ( 1224): btif_dm_remove_bond: bd_addr=7c:f9:0e:37:96:ab
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
I/bt-btif ( 1224): a2dp busy level set to 1
,D/bt-btif ( 1224): btif_check_send_bt_off() btif_core_state= (2),ACL links = (1), LE links = 0
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_DEV_UNPAIRED_EVT
D/bt-btif ( 1224): btif_hh_remove_device: bda = 7c:f9:0e:37:96:ab
W/bt-btif ( 1224):  Oops, can't find device [7c:f9:0e:37:96:ab]
D/bt-btif ( 1224):  btif_storage_remove_ble_bonding_keys in bd addr:7c:f9:0e:37:96:ab
D/bt-btif ( 1224): in bd addr:7c:f9:0e:37:96:ab
D/bt-btif ( 1224): bond_state_changed: state=0 prev_state=0
,I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ROLE_CHG_EVT
W/bt-btif ( 1224): btif_dm_cback : unhandled event (14)
,I/bt-btif ( 1224): btif_dm_generic_evt: event=33027
D/bt-btif ( 1224): btif_hh_virtual_unplug
E/bt-btif ( 1224): btif_hh_virtual_unplug: Error, device 7C:F9:0E:37:96:AB not opened.
I/bt-btif ( 1224): bta_dm_sm_execute event:0x18
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_DEV_UNPAIRED_EVT
D/bt-btif ( 1224): btif_hh_remove_device: bda = 7c:f9:0e:37:96:ab
W/bt-btif ( 1224):  Oops, can't find device [7c:f9:0e:37:96:ab]
,D/bt-btif ( 1224):  btif_storage_remove_ble_bonding_keys in bd addr:7c:f9:0e:37:96:ab
D/bt-btif ( 1224): in bd addr:7c:f9:0e:37:96:ab
D/bt-btif ( 1224): bond_state_changed: state=0 prev_state=0
,I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/LGBluetoothPowerSaveListener( 2584): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 2653): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2653): Bluetooth Device Name: A5-1
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback, code:16, port_handle:11
D/bt-btif ( 1224): bta_jv_port_mgmt_sr_cback code=16 port_handle:0xb handle:0x84, p_pcb:0x60d6a14c, user:6
D/bt-btif ( 1224): PORT_CLOSED before BTA_JV_RFCOMM_CLOSE_EVT: curr_sess:2, max_sess:7
D/bt-btif ( 1224): BTA_JV_RFCOMM_CLOSE_EVT: user_data:6
D/bt-btif ( 1224): on_rfc_close, slot id:6, fd:99, rfc scn:7, server:0
D/bt-btif ( 1224): cleanup slot:6, fd:99, scn:0, sdp_handle:0x0
D/bt-btif ( 1224): closing rfcomm connection, rfc_handle:0x284
I/bt-btif ( 1224): BTA_JvRfcommClose
,D/bt-btif ( 1224): PORT_CLOSED after BTA_JV_RFCOMM_CLOSE_EVT: curr_sess:2, max_sess:7
,D/bt-att  ( 1224): GATT   ATT protocol channel with BDA: 08eca9507627 is disconnected
D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :08-ec-a9-50-76-27
D/bt-att  ( 1224): gatt_add_srv_chg_clt
D/bt-att  ( 1224): enqueue a srv chg client
D/bt-att  ( 1224): gatt_cleanup_upon_disc 
,D/bt-att  ( 1224): exit gatt_cleanup_upon_disc 
D/bt-att  ( 1224): ATT disconnected
I/bt-smp  ( 1224): SMDBG l2c smp_connect_cback 
,E/bt-btm  ( 1224): btm_sec_disconnected - Clearing Pending flag
D/bt-btif ( 1224): bta_jv_rfcomm_close, rfc handle:644
D/bt-btif ( 1224): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x284, state: 5, rfc_cb->handle: 0x84
D/bt-btif ( 1224): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:2, p_pcb:0x60d6a14c, user:6, state:5, jv handle: 0x284
,D/bt-btif ( 1224): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_OPEN, scn:7, user_data:6,
I/bt-btif ( 1224): bta_jv_free_set_pm_profile_cb(jv_handle: 0x284), idx: 2, app_id: 0xff
D/bt-btif ( 1224): bta_dm_pm_cback: st(1), id(26), app(255)
,D/bt-btif ( 1224): bta_jv_rfcomm_close: sec id in use:4, rfc_cb in use:4
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8,
I/bt-btif ( 1224): bta_dm_sm_execute event:0x8
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_LINK_DOWN_EVT
D/bt-btif ( 1224):  btif_storage_check_ble_bonding_keys in bd addr:08:ec:a9:50:76:27
,D/bt-btif ( 1224):  btif_storage_check_ble_bonding_keys ret =:0
,D/bt-btif ( 1224): remove_temp_device: Temporary device, remove from device db
D/bt-btif ( 1224): btif_hh_virtual_unplug
,E/bt-btif ( 1224): btif_hh_virtual_unplug: Error, device 08:EC:A9:50:76:27 not opened.,
W/bt-btif ( 1224): invalid rfc slot id: 6
I/bt-btif ( 1224): bta_dm_sm_execute event:0x18,
D/bt-att  ( 1224): gatt_delete_dev_from_srv_chg_clt_list
D/bt-att  ( 1224): gatt_is_bda_in_the_srv_chg_clt_list :08-ec-a9-50-76-27,
,D/bt-att  ( 1224): bda is in the srv chg clt list
D/bt-btif ( 1224): BTA_DM_LINK_DOWN_EVT. Sending BT_ACL_STATE_DISCONNECTED
,I/bt-btif ( 1224): HAL bt_hal_cbacks->acl_state_changed_cb
D/WifiServiceExtension(  964): Connected BT device : -3
I/bt-btif ( 1224): GT^^ : btif_dm_ssp_get_justworks: remote_addr=08:ec:a9:50:76:27
D/bt-btif ( 1224): in, bd addr:08:ec:a9:50:76:27, prop type:14, len:4
I/bt-btif ( 1224): GT^^ : btif_dm_ssp_get_justworks: justworks =1
I/bt-btif ( 1224): btif_dm_remove_bond: bd_addr=08:ec:a9:50:76:27
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
I/bt-btif ( 1224): a2dp busy level set to 0
D/bt-btif ( 1224): btif_check_send_bt_off() btif_core_state= (2),ACL links = (0), LE links = 0
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_DEV_UNPAIRED_EVT
D/bt-btif ( 1224): btif_hh_remove_device: bda = 08:ec:a9:50:76:27
W/bt-btif ( 1224):  Oops, can't find device [08:ec:a9:50:76:27]
D/bt-btif ( 1224):  btif_storage_remove_ble_bonding_keys in bd addr:08:ec:a9:50:76:27
D/bt-btif ( 1224): in bd addr:08:ec:a9:50:76:27
D/bt-btif ( 1224): bond_state_changed: state=0 prev_state=0
I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
I/bt-btif ( 1224): btif_dm_generic_evt: event=33027
D/bt-btif ( 1224): btif_hh_virtual_unplug
E/bt-btif ( 1224): btif_hh_virtual_unplug: Error, device 08:EC:A9:50:76:27 not opened.
I/bt-btif ( 1224): bta_dm_sm_execute event:0x18
I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_DEV_UNPAIRED_EVT
D/bt-btif ( 1224): btif_hh_remove_device: bda = 08:ec:a9:50:76:27
W/bt-btif ( 1224):  Oops, can't find device [08:ec:a9:50:76:27]
D/bt-btif ( 1224):  btif_storage_remove_ble_bonding_keys in bd addr:08:ec:a9:50:76:27
D/bt-btif ( 1224): in bd addr:08:ec:a9:50:76:27
D/bt-btif ( 1224): bond_state_changed: state=0 prev_state=0
I/bt-btif ( 1224): HAL bt_hal_cbacks->bond_state_changed_cb
I/BluetoothBondStateMachine( 1224): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/LGBluetoothPowerSaveListener( 2584): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 2653): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2653): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265177117449495; DSPS: 21996483; Offset: 1452264505838061068
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265197119600807; DSPS: 22651913; Offset: 1452264505838076149
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265200054, nextTick: 59969, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265200060, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265217120053636; DSPS: 23307288; Offset: 1452264505838071215
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265237120958377; DSPS: 23962678; Offset: 1452264505838060428
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265257128877093; DSPS: 24618297; Offset: 1452264505838075092
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265260039, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265260049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265277129361867; DSPS: 25273673; Offset: 1452264505838071584
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265297130683303; DSPS: 25929076; Offset: 1452264505838080764
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265317131121457; DSPS: 26584450; Offset: 1452264505838091672
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265320044, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265320060, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265337132101882; DSPS: 27239843; Offset: 1452264505838065017
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  964): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  964): Done.
,D/QcConnectivityService(  964): Setting timer for 720seconds
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265357133481473; DSPS: 27895248; Offset: 1452264505838071317
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265377134355226; DSPS: 28550637; Offset: 1452264505838060060
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265380041, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265380047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265397134838802; DSPS: 29206012; Offset: 1452264505838085873
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265417135741372; DSPS: 29861402; Offset: 1452264505838072915
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265437136192296; DSPS: 30516777; Offset: 1452264505838066076
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265440031, nextTick: 59998, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265440034, nextTick: 59998, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265457136662287; DSPS: 31172152; Offset: 1452264505838078303
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265477137613676; DSPS: 31827543; Offset: 1452264505838083647
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265497138059837; DSPS: 32482918; Offset: 1452264505838072045
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265500036, nextTick: 59992, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265500039, nextTick: 59993, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265517139598586; DSPS: 33138329; Offset: 1452264505838054397
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265537140482471; DSPS: 33793717; Offset: 1452264505838083790
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265557140945127; DSPS: 34449092; Offset: 1452264505838088682
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265560030, nextTick: 59999, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265560052, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265577141427647; DSPS: 35104468; Offset: 1452264505838082921
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265597142324185; DSPS: 35759858; Offset: 1452264505838063932
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265617142765620; DSPS: 36415232; Offset: 1452264505838078120
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265620036, nextTick: 59987, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265620043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265637143698992; DSPS: 37070623; Offset: 1452264505838065448
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265657144572913; DSPS: 37726012; Offset: 1452264505838054359
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265677145024277; DSPS: 38381386; Offset: 1452264505838078477
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265680030, nextTick: 59998, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265680051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265697145529627; DSPS: 39036763; Offset: 1452264505838065028
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265717146429131; DSPS: 39692152; Offset: 1452264505838079522
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265737146875399; DSPS: 40347527; Offset: 1452264505838068026
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265740039, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265740042, nextTick: 59991, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265757147856136; DSPS: 41002919; Offset: 1452264505838072201
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265777149306351; DSPS: 41658327; Offset: 1452264505838057572
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265797150178523; DSPS: 42313715; Offset: 1452264505838075252
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265800034, nextTick: 59995, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265800048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265817150655545; DSPS: 42969091; Offset: 1452264505838063993
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265837151566603; DSPS: 43624481; Offset: 1452264505838059523
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265857151999011; DSPS: 44279855; Offset: 1452264505838064685
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265860039, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265860042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265877152917181; DSPS: 44935245; Offset: 1452264505838067328
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265897153847346; DSPS: 45590635; Offset: 1452264505838081966
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265917154742128; DSPS: 46246025; Offset: 1452264505838061220
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265920032, nextTick: 59984, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265920043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265937155192883; DSPS: 46901400; Offset: 1452264505838054212
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265957156095852; DSPS: 47556789; Offset: 1452264505838072171
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265977156563782; DSPS: 48212164; Offset: 1452264505838082337
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265980080, nextTick: 59949, mDrawingTime: 3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452265980083, nextTick: 59950, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452265997157469317; DSPS: 48867554; Offset: 1452264505838072345
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266017158351446; DSPS: 49522943; Offset: 1452264505838069464
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266037159911014; DSPS: 50178354; Offset: 1452264505838072636
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266040044, nextTick: 59985, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266040046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266057160384631; DSPS: 50833730; Offset: 1452264505838057971
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  964): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  964): Done.
,D/QcConnectivityService(  964): Setting timer for 720seconds
,D/GCM     ( 1551): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266077161796260; DSPS: 51489136; Offset: 1452264505838065792
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266097162240188; DSPS: 52144510; Offset: 1452264505838082474
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266100040, nextTick: 59985, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266100058, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266117163143842; DSPS: 52799900; Offset: 1452264505838070600
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266137164451668; DSPS: 53455303; Offset: 1452264505838066170
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266157164899810; DSPS: 54110677; Offset: 1452264505838087066
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266160053, nextTick: 59968, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266160060, nextTick: 59971, mDrawingTime: 1,
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266177165376994; DSPS: 54766053; Offset: 1452264505838075969
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266197166284927; DSPS: 55421443; Offset: 1452264505838068375
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266217166721656; DSPS: 56076817; Offset: 1452264505838077858
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266220052, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266220055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266237167623707; DSPS: 56732207; Offset: 1452264505838064381
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266257169190616; DSPS: 57387618; Offset: 1452264505838074894
,D/wpa_supplicant( 2034): nl80211: Event message available
D/wpa_supplicant( 2034): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2034): nl80211: Disconnect event
D/wpa_supplicant( 2034): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2034): wlan0: Deauthentication notification
D/wpa_supplicant( 2034): wlan0:  * reason 0
D/wpa_supplicant( 2034): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2034): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2034): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2034): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2034): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2034): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2034): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2034): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2034): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
,D/WifiStateMachine(  964): handleMessage: E msg.what=147460,
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb83c1d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2034):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2034): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2034): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): Network connection lost
,D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 1
,D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2034): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2034): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2034): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/DhcpStateMachine(  964): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  964): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/wpa_supplicant( 2034): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2034): wlan0: nl80211: scan request
,D/wpa_supplicant( 2034): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2034): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2034): nl80211: Event message available
D/wpa_supplicant( 2034): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2034): wlan0: nl80211: Scan trigger
,D/WifiHS20(  964): hidePasspointNotification off =false
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
D/QCNEA   (  611): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  611): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  611): |CAC| updateNetCfgInfo
V/QCNEA   (  611): |CAC| *********************************************
V/QCNEA   (  611): |CAC|                   Netconfig               
V/QCNEA   (  611): |CAC| *********************************************
V/QCNEA   (  611): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  611): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  611): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  611): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  611): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  611): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  611): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  611): |CAC| *********************************************
D/QCNEA   (  611): |CAC| Received bssid= 
D/QCNEA   (  611): |CAC| net type = 3
V/QCNEA   (  611): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  611): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  611): |CAC| 	ssid           =NG700
V/QCNEA   (  611): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  611): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  611): |CAC| *********************************************
D/QCNEA   (  611): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  611): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  611): |CAC| dispatchNetCfg: updating:0xb70968dc
D/QCNEA   (  611): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 0
D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6896 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
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
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 6896): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6896): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6896): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/PCSuite ( 6896): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6896): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6896): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
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
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x628d95f8 clazz=0xe2b00001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1551): Read error: ssl=0x5e917b60: I/O error during system call, Connection timed out
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
,V/NativeCrypto( 1551): SSL shutdown failed: ssl=0x5e917b60: I/O error during system call, Broken pipe
,I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6933 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  964): Killing 4889:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/DhcpStateMachine(  964): StoppedState
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6933): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6933): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6933): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 6933): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QRemote ( 6933): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 6933): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
I/QRemote ( 6933): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/QRemote ( 6933): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6933): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/QRemote ( 6933): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/QRemote ( 6933): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6933): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 4904:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2034): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/wpa_supplicant( 2034): nl80211: Event message available
D/wpa_supplicant( 2034): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2034): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2034): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2034): nl80211: Received scan results (12 BSSes)
D/wpa_supplicant( 2034): nl80211: Survey data missing
D/wpa_supplicant( 2034): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 15 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 16 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 17 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 18 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 19 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 20 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 21 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 22 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 23 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 24 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 25 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: BSS: Add new id 26 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): BSS: last_scan_res_used=12/32 last_scan_full=0
D/wpa_supplicant( 2034): wlan0: New scan results available
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c, ...
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2034): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2034): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2034): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2034): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2034): WPS: AP 44:e9:dd:10:c0:ac type 0 added
D/wpa_supplicant( 2034): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2034): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2034): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2034): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[4] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[5] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[6] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): WPS: AP[7] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2034): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2034): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch
,D/wpa_supplicant( 2034): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2034): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2034): wlan0: 2: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-80 wps
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2034): wlan0: 3: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-87 wps
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2034): wlan0: 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-83
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2034): wlan0: 5: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-86
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2034): wlan0: 6: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-86 wps
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2034): wlan0: 7: 44:e9:dd:10:c0:ac ssid='FunBox2-C0AB' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-92 wps,
,D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2034): wlan0: 8: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-89
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2034): wlan0: 9: 44:e9:dd:10:c0:ab ssid='FunBox2-C0AB' wpa_ie_len=26 rsn_ie_len=24 caps=0x511 level=-89 wps
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2034): wlan0: 10: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-89 wps
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2034): wlan0: 11: 44:e9:dd:10:c0:ad ssid='Darmowe_Orange_WiFi' wpa_ie_len=0 rsn_ie_len=0 caps=0x501 level=-89
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2034): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2034): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2034): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2034): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2034): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2034): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2034): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2034): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2034): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2034): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
,D/wpa_supplicant( 2034): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2034): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2034): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 2034): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2034): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb83c35a8  current_ssid=0x0
,D/wpa_supplicant( 2034): scard is not null..
D/wpa_supplicant( 2034): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2034): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2034): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2034): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2034): TDLS: TDLS is allowed in the target BSS,
I/wpa_supplicant( 2034): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2034): wlan0: Cancelling scan request
D/wpa_supplicant( 2034): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
D/wpa_supplicant( 2034): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2034): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2034): RSN: PMKSA cache search - network_ctx=0xb83c35a8 try_opportunistic=0
D/wpa_supplicant( 2034): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2034): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2034): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2,
D/wpa_supplicant( 2034): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2034): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2034): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2034): wlan0: WPA: using PTK CCMP
,D/wpa_supplicant( 2034): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2034): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2034): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0,
D/wpa_supplicant( 2034): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2034): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2034): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2034): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2034): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2034): nl80211: Unsubscribe mgmt frames handle 0xb83c2590 (mode change),
,D/wpa_supplicant( 2034): nl80211: Subscribe to mgmt frames with non-AP handle 0xb83c2590,
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 04 0a
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 15 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 16 c0:ff:d4:d3:aa:48]
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
,D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590,
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590,
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
,D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590,
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2034): nl80211: Register frame type=0xd0 nl_handle=0xb83c2590
D/wpa_supplicant( 2034): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2034): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2034):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034):   * freq=2412
D/wpa_supplicant( 2034):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2034):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2034):   * Auth Type 0
,D/wpa_supplicant( 2034):   * WPA Versions 0x2
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 17 64:7c:34:12:7f:81],
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 18 a0:c5:62:7a:49:97]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 19 06:7c:34:12:7f:81]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 20 38:f8:89:11:e9:11]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 21 dc:4a:3e:0f:c2:f1]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 22 44:e9:dd:10:c0:ac]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 23 06:7c:34:38:27:cc],
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 24 44:e9:dd:10:c0:ab]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 25 64:7c:34:38:27:cc]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 26 44:e9:dd:10:c0:ad],
,D/wpa_supplicant( 2034): nl80211: Connect request send successfully
D/wpa_supplicant( 2034): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2034): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2034): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState,
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2034): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2034): WPS: Unknown Vendor Extension (Vendor ID 311)
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ],
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2034): nl80211: Event message available
D/wpa_supplicant( 2034): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0,
D/wpa_supplicant( 2034): nl80211: Connect event
D/wpa_supplicant( 2034): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2034): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2034): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2034): wlan0: Association info event
D/wpa_supplicant( 2034): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...,
D/wpa_supplicant( 2034): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00,
D/wpa_supplicant( 2034): wlan0: freq=2412 MHz
D/wpa_supplicant( 2034): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2034): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2034): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2034): wlan0: WPA: clearing AP WPA IE,
,D/wpa_supplicant( 2034): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2034): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): scard is not null..
D/wpa_supplicant( 2034): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2034): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2034): TDLS: Remove peers on association
D/wpa_supplicant( 2034): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2034): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2034): EAPOL: enable timer tick
D/wpa_supplicant( 2034): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2034): wlan0: Setting authentication timeout: 10 sec 0 usec,
D/wpa_supplicant( 2034): wlan0: Cancelling scan request
D/wpa_supplicant( 2034): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/wpa_supplicant( 2034): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 32 a9 b8 12 3e ce ad 3e 61 10 ea b6 24 ad 87 ...
D/wpa_supplicant( 2034): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2034): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2034): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2034): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2034): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2034):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2034):   key_nonce - hexdump(len=32): 32 a9 b8 12 3e ce ad 3e 61 10 ea b6 24 ad 87 37 22 91 dc 14 c8 48 39 35 2a 94 a9 89 19 40 5f 0d
D/wpa_supplicant( 2034):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 32 a9 b8 12 3e ce ad 3e 61 10 ea b6 24 ad 87 ...
D/wpa_supplicant( 2034): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2034): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2034): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2034): WPA: Renewed SNonce - hexdump(len=32): e7 30 08 7b eb 72 4a 7f 7d e2 f7 d1 26 07 70 81 98 90 57 d1 f0 b3 bb d5 d0 0c d4 9b 51 2c 39 fa
D/wpa_supplicant( 2034): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): WPA: Nonce1 - hexdump(len=32): e7 30 08 7b eb 72 4a 7f 7d e2 f7 d1 26 07 70 81 98 90 57 d1 f0 b3 bb d5 d0 0c d4 9b 51 2c 39 fa
D/wpa_supplicant( 2034): WPA: Nonce2 - hexdump(len=32): 32 a9 b8 12 3e ce ad 3e 61 10 ea b6 24 ad 87 37 22 91 dc 14 c8 48 39 35 2a 94 a9 89 19 40 5f 0d
D/wpa_supplicant( 2034): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2034): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2034): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2034): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01,
D/wpa_supplicant( 2034): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2034): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2034): WPA: Derived Key MIC - hexdump(len=16): 1c 0d 4d 92 d6 27 5f 23 b0 fb 9e 4b 67 dd 72 bd
,W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 e7 30 08 7b eb 72 4a 7f 7d e2 f7 d1 26 07 70 ...
D/Tethering(  964): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false,
D/WifiStateMachine(  964): handleMessage: X
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700],
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/wpa_supplicant( 2034): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 32 a9 b8 12 3e ce ad 3e 61 10 ea b6 24 ad 87 ...
D/wpa_supplicant( 2034): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2034): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2034): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2034): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2034):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2034):   key_nonce - hexdump(len=32): 32 a9 b8 12 3e ce ad 3e 61 10 ea b6 24 ad 87 37 22 91 dc 14 c8 48 39 35 2a 94 a9 89 19 40 5f 0d
D/wpa_supplicant( 2034):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_rsc - hexdump(len=8): d8 25 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2034):   key_mic - hexdump(len=16): 4c a2 84 df 9b 18 62 7c e1 4f 1e 8a 24 3f 33 59
D/wpa_supplicant( 2034): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 32 a9 b8 12 3e ce ad 3e 61 10 ea b6 24 ad 87 ...
D/wpa_supplicant( 2034): RSN: encrypted key data - hexdump(len=56): db ef c6 b2 04 b7 fb 25 5f 81 9c e1 3a 0b 3e bc 07 fb a7 8d b1 86 e2 9c e7 47 bc 14 20 d9 66 15 ...
D/wpa_supplicant( 2034): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2034): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2034): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2034): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 22 85 ...
D/wpa_supplicant( 2034): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2034): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2034): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2034): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2034): WPA: Derived Key MIC - hexdump(len=16): b1 a4 5f 1e 44 b4 69 02 1e 1f e0 04 33 6d 11 03
D/wpa_supplicant( 2034): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2034): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb83c2c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2034):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/wpa_supplicant( 2034): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2034): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2034): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2034): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2034): WPA: RSC - hexdump(len=6): d8 25 00 00 00 00
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f3603a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2034):    broadcast key
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2034): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(l,en=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2034): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2034): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2034): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2034): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2034): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2034): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2034): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2034): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2034): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2034): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2034): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2034): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2034): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2034): EAPOL authentication completed successfully
D/wpa_supplicant( 2034): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2034): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2034): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
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
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2034): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2034): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/DhcpStateMachine(  964): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/DhcpStateMachine(  964): WaitBeforeStartState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-26ms what=147462 obj=android.net.wifi.StateChangeResult@446cf4b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] connect :false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-14ms what=147462 obj=android.net.wifi.StateChangeResult@43e8af40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-15ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/AppUp4:CustModeStarterReceiver( 4041): onReceive
D/AppUp4:CustFacade( 4041): Context : android.app.ReceiverRestrictedContext@428cdfe0
D/AppUp4:CustFacade( 4041): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4041): isOpenOperator : true
D/AppUp4:CustFacade( 4041): isPhone : true
I/LicenseContentProvider( 2982): start selecting data
D/SIMObserver( 2982): simInfo1
I/AppUp4:EulaManager( 4041): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4041): begin check event
,I/AppUp4:CustModeStarterReceiver( 4041): Event For GoodConnectivity
I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=6988 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 6988): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6988): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6988): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2034): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2034): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2034): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
,E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
,D/CommandListener(  271): Setting iface cfg
,D/CommandListener(  271): Trying to bring up wlan0
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432850e8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432850e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
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
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2034): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2034): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2034): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2034): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2034): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2034): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): DHCP successful
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
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
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
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  964): handleMessage: X
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
E/Parcel  (  611): Reading a NULL string not supported here.
,E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 1
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  611): Reading a NULL string not supported here.
E/Parcel  (  611): Reading a NULL string not supported here.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
E/Parcel  (  611): Reading a NULL string not supported here.
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,D/dalvikvm( 2641): GC_CONCURRENT freed 2440K, 33% free 16760K/24832K, paused 20ms+4ms, total 56ms
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/DownloadManager( 6988): DownloadService onCreate
,I/DownloadManager( 6988): in removeSpuriousFiles
,V/        (  271): RouteController
,V/DownloadManager( 6988): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@428f7db8 on behalf of 6988
V/        (  271): RouteController
,I/DownloadManager( 6988): in trimDatabase
,V/DownloadManager( 6988): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@428fb4e0 on behalf of 6988
,V/DownloadManager( 6988): DownloadService onStartCommand
,I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7018 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
V/DownloadManager( 6988): DownloadService onStartCommand
V/        (  271): RouteController
V/DownloadManager( 6988): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/        (  271): RouteController
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@428fd910 on behalf of 6988
,V/        (  271): RouteController
,V/DownloadManager( 6988): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@42901968 on behalf of 6988
,V/DownloadManager( 6988): DownloadService onDestroy
,D/HyLog   ( 7018): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/QCNEA   (  611): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  611): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  611): |CAC| updateNetCfgInfo
V/QCNEA   (  611): |CAC| *********************************************
V/QCNEA   (  611): |CAC|                   Netconfig               
V/QCNEA   (  611): |CAC| *********************************************
V/QCNEA   (  611): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  611): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  611): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  611): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  611): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  611): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  611): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  611): |CAC| *********************************************
D/QCNEA   (  611): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  611): |CAC| net type = 1
V/QCNEA   (  611): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  611): |CAC| Received ssid= NG700
V/QCNEA   (  611): |CAC| 	ssid           =NG700
V/QCNEA   (  611): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  611): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  611): |CAC| *********************************************
D/QCNEA   (  611): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
,D/QCNEA   (  611): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  611): |CAC| dispatchNetCfg: updating:0xb70968dc
D/QCNEA   (  611): |CAC| readCallback: read len:0, ret:-1, errno:11
I/ActivityManager(  964): Killing 4933:com.lge.drmservice/u0a66 (adj 15): empty #17
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/HyLog   ( 7018): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7018): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/DhcpStateMachine(  964): DHCP request on wlan0
D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/LGEmail ( 7018): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 7018): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,W/BaseRuntimeLoader( 7018): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7018): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7018): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7018): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 7018): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 7018): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 7018): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4387): networkInfo.isConnected() = false
,W/linker  ( 7018): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 7018): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 7018): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 7018): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 7018): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 7018): register_HtmlEditor, Success
D/HtmlEditor( 7018): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 7018): register_HtmlEditorTimer, Success
,D/HtmlEditor( 7018): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 7018): register_HtmlEditorDownloader, Success
D/HtmlEditor( 7018): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7018): register_HtmlEditorFont, Success
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=7047 uid=10052 gids={50052, 3003}
D/HtmlEditor( 7018): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7018): register_HtmlEditorDrawText, Success
D/HtmlEditor( 7018): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7018): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 7018): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7018): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 7018): JNI_OnLoad Success
I/HubEmail( 7018): JNI_OnLoad()
I/HubEmail( 7018): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7018): registerNatives()
I/HubEmail( 7018): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7018): registerNativeMethods()
I/HubEmail( 7018): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 7018): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HyLog   ( 7047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7047): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): Killing 4954:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 7047): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,V/LGRssiData( 7047): [loadRssi] File not exist 
V/LGRssiData( 7047): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 7047): [loadFeatureFromXml] *** start feature loading from xml
D/MobileConnectivityChangeReceiver( 7047): onReceive CONNECTIVITY_CHANGE networkType=1
W/BaseRuntimeLoader( 7047): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7047): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7047): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7047): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 7047): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 7047): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 7047): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7063 uid=10063 gids={50063, 3003, 1028, 1015}
,E/PhoneMonitor( 7047): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 7047): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  964): Killing 4968:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7063): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7063): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7063): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1965): Checking schedule, now: 1452266271589 next: 1452264657944
,I/CheckinService( 1965): active receiver: enabled
,I/CheckinService( 1965): Preparing to send checkin request
,I/EventLogService( 1965): Accumulating logs since 1452264625431
,I/CheckinRequestBuilder( 1965): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1965): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7077 uid=10066 gids={50066, 4002, 3003, 1028}
,D/HyLog   ( 7077): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7077): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7077): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): Killing 4980:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=7090 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 7090): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7090): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7090): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  275): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+4ms, total 42ms
,D/LGDMSGCM( 7090): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7090): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+4ms, total 28ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 27ms
,I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=7104 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  964): Killing 4998:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/wpa_supplicant( 2034): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2034): EAPOL: disable timer tick
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7104): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7104): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7104): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 7104): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7104): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 7104): intf.getDisplayName() = lo
I/Wireless_Storage( 7104): intf.getDisplayName() = sit0
I/Wireless_Storage( 7104): intf.getDisplayName() = p2p0
,I/Wireless_Storage( 7104): intf.getDisplayName() = teql0
I/Wireless_Storage( 7104): intf.getDisplayName() = wlan0
D/NFS     ( 7104): interface name:wlan0 name:wlan0
D/NFS     ( 7104): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
,D/NFS     ( 7104): interface name:wlan0 name:wlan0
D/NFS     ( 7104): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 7104): CONNECT : WIFI_CONNECT
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7116 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 5185:com.google.android.talk/u0a77 (adj 15): empty #17
V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7116): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7116): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7116): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1965): awaiting user notification for token
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x439acfc8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GAV2    ( 7116): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7132 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 7132): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7132): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7132): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1141): GC_CONCURRENT freed 9552K, 13% free 68882K/78620K, paused 4ms+12ms, total 73ms
,D/dalvikvm( 1141): WAIT_FOR_CONCURRENT_GC blocked 69ms
,W/dalvikvm( 7132): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7132): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 7132): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7132): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7132): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 7132): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7132): install
,I/MultiDex( 7132): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 7132): loading existing secondary dex files
,I/MultiDex( 7132): load found 3 secondary dex files
,I/MultiDex( 7132): install done
,D/dalvikvm( 7132): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7132): VFY: unable to resolve instance field 61
,D/dalvikvm( 7132): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 7132): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7132): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7132): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 7132): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7132): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7132): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7132): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7132): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 7132): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b92a8
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
D/dalvikvm( 7132): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b92a8
D/dalvikvm( 7132): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b92a8, skipping init
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 7132): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b92a8
D/dalvikvm( 7132): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b92a8
,V/JNIHelp ( 7132): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 7132): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b92a8
V/WebViewChromium( 7116): Binding Chromium to the main looper Looper (main, tid 1) {428b1cb8}
,D/dalvikvm( 7132): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428b92a8
D/dalvikvm( 7132): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b92a8
,D/dalvikvm( 7132): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428b92a8
,I/chromium( 7116): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7116): Initializing chromium process, renderers=0
,W/chromium( 7116): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 7116): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7116): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7116): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7116): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7116): Remote Branch: 
I/Adreno-EGL( 7116): Local Patches: 
I/Adreno-EGL( 7116): Reconstruct Branch: 
,I/ProviderInstaller( 7132): Installed default security provider GmsCore_OpenSSL
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  964): GC_EXPLICIT freed 2973K, 48% free 29807K/57248K, paused 5ms+13ms, total 143ms
,I/NSApplication( 7116): Starting up...
,I/ActivityManager(  964): Killing 5233:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 6933): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6933): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6933): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/dalvikvm( 7132): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 7132): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 7132): VFY: replacing opcode 0x6e at 0x000d
,I/QRemote ( 6933): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/dalvikvm( 7132): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 7132): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 7132): VFY: replacing opcode 0x6e at 0x0201
,D/QRemote ( 6933): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6933): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6896): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/PCSuite ( 6896): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 6933): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6933): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 6933): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6933): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/GCM     ( 1551): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1551): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1551): Proximity feature is not enabled.
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
,D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d76000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d76000
,V/GmsCoreStatsServiceLauncher( 1965): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/WearableService( 1875): callingUid 10006, callindPid: 1875
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,E/MDM     ( 1423): [72] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1965): Restart initialization of location
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=439560682
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,W/ProcessCpuTracker(  964): Skipping unknown process pid 7179
,D/dalvikvm( 7132): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ac1818
D/dalvikvm( 7132): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ac1818
,D/dalvikvm( 7132): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ac1818, skipping init
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 7132): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 7207): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 7132): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 7132): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 81ms
,I/Adreno-EGL( 7132): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7132): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7132): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7132): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7132): Remote Branch: 
I/Adreno-EGL( 7132): Local Patches: 
I/Adreno-EGL( 7132): Reconstruct Branch: 
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=4024714757
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,W/Settings( 7132): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 7132): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7132): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7132): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7132): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7132): Remote Branch: 
I/Adreno-EGL( 7132): Local Patches: 
I/Adreno-EGL( 7132): Reconstruct Branch: 
,I/Adreno-EGL( 7132): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7132): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7132): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7132): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7132): Remote Branch: 
I/Adreno-EGL( 7132): Local Patches: 
I/Adreno-EGL( 7132): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1965): Classify the device as Phone.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/NativeCrypto( 1965): SSL shutdown failed: ssl=0x6b4aaa30: I/O error during system call, Connection timed out
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-6ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4041): onReceive
,D/AppUp4:CustFacade( 4041): Context : android.app.ReceiverRestrictedContext@428cdfe0
,D/AppUp4:CustFacade( 4041): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4041): isOpenOperator : true
,D/AppUp4:CustFacade( 4041): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,I/AppUp4:EulaManager( 4041): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4041): begin check event
,I/AppUp4:CustModeStarterReceiver( 4041): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4041): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4041): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4041): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4041): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4041): handleAsyncCustNotification do not startCustService
,D/EAS     ( 7018): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6988): DownloadService onCreate
,D/EAS     ( 7018): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 7018): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4387): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 7047): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7047): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 6988): in removeSpuriousFiles
,V/DownloadManager( 6988): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@42905db8 on behalf of 6988
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 6988): in trimDatabase
V/DownloadManager( 6988): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/LGDMSGCM( 7090): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@42907ab8 on behalf of 6988
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/Settings( 7018): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ContextImpl( 7090): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/DownloadManager( 6988): DownloadService onStartCommand
V/DownloadManager( 6988): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 7104): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 7104): CONNECT : WIFI_CONNECT
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@42909960 on behalf of 6988
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 6988): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4041): onReceive
D/AppUp4:CustFacade( 4041): Context : android.app.ReceiverRestrictedContext@428cdfe0
D/AppUp4:CustFacade( 4041): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4041): isOpenOperator : true
,D/AppUp4:CustFacade( 4041): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,I/AppUp4:EulaManager( 4041): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4041): begin check event
,I/AppUp4:CustModeStarterReceiver( 4041): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/NativeCrypto( 1965): SSL shutdown failed: ssl=0x6b484e18: I/O error during system call, Connection timed out
,V/DownloadManager( 6988): DownloadService onCreate
,I/DownloadManager( 6988): in removeSpuriousFiles
,D/EAS     ( 7018): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 7018): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6988): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@4290dae8 on behalf of 6988
,I/DownloadManager( 6988): in trimDatabase
,V/DownloadManager( 6988): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@4290f190 on behalf of 6988
,V/DownloadManager( 6988): DownloadService onStartCommand
,V/DownloadManager( 6988): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4387): networkInfo.isConnected() = true
,D/PhoneState( 4387): setPdpRejectCasuse : false
V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@42911690 on behalf of 6988
,W/Settings( 7018): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 7047): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7047): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinTask( 1965): Sending checkin request (11465 bytes)
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 6988): DownloadService onDestroy
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 7090): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 7090): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 7104): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 7104): CONNECT : WIFI_CONNECT
E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4041): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4041): onReceive
,D/AppUp4:CustFacade( 4041): Context : android.app.ReceiverRestrictedContext@428cdfe0
D/AppUp4:CustFacade( 4041): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4041): isOpenOperator : true
,D/AppUp4:CustFacade( 4041): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,I/AppUp4:EulaManager( 4041): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4041): begin check event
,I/AppUp4:CustModeStarterReceiver( 4041): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 7018): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6988): DownloadService onCreate
,D/EAS     ( 7018): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4387): networkInfo.isConnected() = true
,D/PhoneState( 4387): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 7047): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7047): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 7090): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7090): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 7104): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7104): CONNECT : WIFI_CONNECT
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 6988): in removeSpuriousFiles
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 6988): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/Settings( 7018): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@42915818 on behalf of 6988
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/dalvikvm( 3925): GC_FOR_ALLOC freed 374K, 2% free 37783K/38444K, paused 45ms, total 56ms
V/DownloadManager( 6988): DownloadService onStartCommand
,V/DownloadManager( 6988): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 6988): in trimDatabase
,V/DownloadManager( 6988): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@42918d80 on behalf of 6988
,V/DownloadManager( 6988): created cursor android.database.sqlite.SQLiteCursor@42918f98 on behalf of 6988
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 6988): DownloadService onDestroy
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinRequestBuilder( 1965): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1965): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1965): awaiting user notification for token
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x44aa6b28: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinRequestBuilder( 1965): Classify the device as Phone.
,I/CheckinTask( 1965): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1965): Checking schedule, now: 1452266276209 next: 1452843672199
,I/CheckinService( 1965): active receiver: disabled
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1551): Connected
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CheckinService( 1965): Checking schedule, now: 1452266276273 next: 1452843672199
,I/CheckinService( 1965): active receiver: disabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1551): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1551): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/GAV2    ( 7116): Thread[GAThread,5,main]: No campaign data found.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266277169645013; DSPS: 58042993; Offset: 1452264505838071527
,I/ActivityManager(  964): Killing 4278:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  964): Killing 5250:com.android.gallery3d/u0a27 (adj 15): empty #18
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266280038, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266280049, nextTick: 59982, mDrawingTime: 1
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=7313 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,E/SlideAside( 4066): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 4066): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
D/administrator(  964): Handling package changes for user 0
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
,W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/HyLog   ( 7313): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7313): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7313): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
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
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 7313): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 7313): MmsConfig.loadMmsSettings
,I/Babel   ( 7313): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 7313): MmsConfig.loadFromDatabase
I/MediaCodecList( 7313): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 7313): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 7313): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 7313): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 7313): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7313): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7313): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7313): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 7313): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 7313): MmsConfig.loadFromResources
,E/Babel   ( 7313): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 7313): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 7313): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4041): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4041): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4041): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
I/AppUp4:CustModeStarterReceiver( 4041): onReceive
,V/LGRssiData( 7313): [loadRssi] File not exist 
V/LGRssiData( 7313): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 7313): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:CustFacade( 4041): Context : android.app.ReceiverRestrictedContext@428cdfe0
D/AppUp4:CustFacade( 4041): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4041): isOpenOperator : true
D/AppUp4:CustFacade( 4041): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,V/TelephonyAutoProfiling( 7313): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 7313): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 7313): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:EulaManager( 4041): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4041): begin check event
D/AppUp4:Utils( 4041): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4041): Event For Nothing, skip.
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7357 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,V/GmsNetworkLocationProvi( 1423): DISABLE
,D/HyLog   ( 7357): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7357): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7357): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  964): applying state to connected service
,D/LocationProviderProxy(  964): applying state to connected service
,I/SystemConfig( 7357): BUILD Country: EU
,I/SystemConfig( 7357): BUILD Operator: OPEN
I/ActivityManager(  964): Killing 6896:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7378 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,I/SystemConfig( 7357): systemFeature RCS result false
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
D/SystemConfig( 7357): refreshRcsSupport() :false
,I/ActivityManager(  964): Killing 6933:com.lge.qremote/u0a96 (adj 15): empty #17
D/HyLog   ( 7378): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7378): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7378): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): Killing 6988:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2653): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7395 uid=10050 gids={50050, 3003, 1028, 1015}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  964): GC_EXPLICIT freed 2520K, 48% free 29885K/57248K, paused 5ms+15ms, total 173ms
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7395): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7395): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7395): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 7395): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 7395): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7395): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 7395): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 7395): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 7395): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7395): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 7395): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7395): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7395): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7395): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 7395): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 7395): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7395): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 7395): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 7395): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 7395): VFY: replacing opcode 0x6e at 0x011e
,D/dalvikvm( 1965): GC_CONCURRENT freed 1949K, 22% free 19549K/24832K, paused 8ms+5ms, total 75ms
I/dalvikvm( 7395): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7395): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7395): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 7395): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7395): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 7395): VFY: replacing opcode 0x6e at 0x029a
,I/IcingCorporaProvider( 2653): UpdateCorporaTask done [took 513 ms] updated apps [took 512 ms] 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/dalvikvm( 7395): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 7395): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 7395): VFY: replacing opcode 0x6e at 0x001a
,I/ActivityManager(  964): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=7437 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/dalvikvm( 7395): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 7395): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 7395): VFY: replacing opcode 0x6e at 0x0049
D/HyLog   ( 7437): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7437): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7437): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Finsky  ( 7395): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7395): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager(  964): Killing 7018:com.lge.email/u0a24 (adj 15): empty #17
,D/PackageBroadcastService( 1965): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1965): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1965): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,V/DownloadManager( 7437): DownloadService onCreate
,I/DownloadManager( 7437): in removeSpuriousFiles
,V/DownloadManager( 7437): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7437): created cursor android.database.sqlite.SQLiteCursor@428f92a0 on behalf of 7437
,V/DownloadManager( 7437): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 7437): DownloadService onStartCommand
,I/DownloadManager( 7437): in trimDatabase
,V/DownloadManager( 7437): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 7437): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7437): created cursor android.database.sqlite.SQLiteCursor@428ffc28 on behalf of 7395
,V/DownloadManager( 7437): created cursor android.database.sqlite.SQLiteCursor@42900e18 on behalf of 7437
,V/DownloadManager( 7437): created cursor android.database.sqlite.SQLiteCursor@429025d0 on behalf of 7437
,D/Finsky  ( 7395): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 7437): DownloadService onDestroy
,D/Finsky  ( 7395): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 7395): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 7395): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7395): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7395): VFY: replacing opcode 0x62 at 0x0037
,D/dalvikvm( 1551): GC_EXPLICIT freed 1367K, 28% free 18003K/24832K, paused 3ms+6ms, total 50ms
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Finsky  ( 7395): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-5ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7395): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/dalvikvm( 7395): Total arena pages for JIT: 11
,I/dalvikvm( 7395): Total arena pages for JIT: 12
I/dalvikvm( 7395): Total arena pages for JIT: 13
,I/dalvikvm( 7395): Total arena pages for JIT: 14
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7395): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7395): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7395): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7395): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1423): client connected with version: 7571000
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ProcessCpuTracker(  964): Skipping unknown process pid 7472
,W/ProcessCpuTracker(  964): Skipping unknown process pid 7475
,I/GAV4    ( 7313): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  964): Killing 7047:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157d08 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266297170553084; DSPS: 58698383; Offset: 1452264505838064071
,D/Finsky  ( 7395): [510] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7395): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266317171966575; DSPS: 59353789; Offset: 1452264505838073753
,I/ProcessStatsService(  964): Prepared write state in 20ms
,I/ProcessStatsService(  964): Prepared write state in 24ms
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/EventLogService( 1965): Aggregate from 1452266271628 (log), 1452264534726 (data)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ProcessStatsService(  964): Pruning old procstats: /data/system/procstats/state-2016-01-07-17-20-00.bin
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266337172891207; DSPS: 60009179; Offset: 1452264505838082858
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266340039, nextTick: 59985, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266340044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266357173325175; DSPS: 60664554; Offset: 1452264505838059062
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266377174211003; DSPS: 61319943; Offset: 1452264505838059880
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266397175125703; DSPS: 61975333; Offset: 1452264505838059053
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266400057, nextTick: 59968, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1452266400061, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1452266417175571897; DSPS: 62630707; Offset: 1452264505838078001
,TIME-OUT KILL (timeout was 1800000ms)
```
